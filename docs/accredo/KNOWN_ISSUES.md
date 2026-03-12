# Known Issues, Fixes & Lessons Learned

> This file logs every bug, workaround, and gotcha discovered while building Accredo scripts.
> **Claude MUST Grep this file before writing code to avoid repeating past mistakes.**

---

<!--
HOW TO ADD AN ENTRY:
Copy this template and fill it in:

## Short description of the problem
**Problem:** What went wrong or what was confusing
**Solution:** What actually works
**Tags:** comma, separated, keywords, function names, error messages
---
-->

## `Integer` type does not exist in MaxBasic
**Problem:** `Dim x as Integer` causes "Unexpected token 'Integer'" error.
**Solution:** Use `Number` instead. MaxBasic only has `String`, `Number`, `Object`, `Boolean` — no `Integer`, `Int`, `Long`, etc.
**Tags:** Integer, Dim, type, Unexpected token, Number
---

## `CStr` does not exist in MaxBasic
**Problem:** `CStr(value)` causes "Unexpected token 'CStr'" error.
**Solution:** Use string concatenation to convert: `"" & value` instead of `CStr(value)`.
**Tags:** CStr, string conversion, Unexpected token
---

## XML comments crash Accredo form parser
**Problem:** `<!-- comment -->` in .pfd XML files causes parse errors (e.g. "Unexpected token" on the line after the comment).
**Solution:** Do NOT use XML comments in .pfd files. Accredo's form parser does not support them. Use comments only in the CDATA script section (with `'` prefix).
**Tags:** XML, comment, pfd, form, parse error
---

## Modal forms must have Visible="False"
**Problem:** `ShowModal` on a form with `Visible="True"` causes "Cannot make a visible window modal" error.
**Solution:** Set `Visible="False"` in the form's XML. ShowModal will make it visible.
**Tags:** ShowModal, Visible, modal, Cannot make a visible window modal
---

## CreateCustomForm path resolution
**Problem:** `CreateCustomForm("MyForm.pfd")` can't find the form even when it's in the same directory as the calling script.
**Solution:** Accredo resolves form paths relative to a system directory, NOT the script's directory. Use full server paths: `CreateCustomForm("H:\DBNZ\Warehouse\George Custom Accredo Scripts\MyForm.pfd")`. The existing Barcoding forms work with relative paths like `"Barcoding\Qty_Entry.pfd"` because that path is relative to Accredo's configured scripts directory.
**Tags:** CreateCustomForm, path, not found, form file definition
---

## DataCombo OnAfterChange cannot modify the combo's own text
**Problem:** Setting `eCombo.Text = ""` inside the combo's own `OnAfterChange` event causes "eProductSearch disallowed OnValueSelect change" crash.
**Solution:** Do NOT clear or modify the DataCombo's text inside its own OnAfterChange handler. Leave the last selected value showing.
**Tags:** DataCombo, OnAfterChange, OnValueSelect, disallowed, clear text
---

## TUserEditGrid cells are read-only by default
**Problem:** Cells in a `TUserEditGrid` bound to a `TUserMemoryTable` are not editable — clicking does nothing.
**Solution:** Grid fields without editors are read-only. You must either:
1. Call `gridName.CreateDefaultEditors` in code to create editors for all fields (but this conflicts with manual Append/Save — causes "Dataset not in edit or insert mode" errors), OR
2. Use a button/double-click handler to change values via `tblName.Edit` / `tblName.Save`.
Option 2 is more reliable for forms that also programmatically add rows.
**Tags:** EditGrid, editable, read-only, CreateDefaultEditors, Dataset not in edit or insert mode, AutoPost
---

## CreateDefaultEditors conflicts with programmatic Append/Save
**Problem:** After calling `gridTint.CreateDefaultEditors` with `AutoPost="True"`, using `tblTint.Append` in code causes "Dataset not in edit or insert mode" error because the grid controls the dataset state.
**Solution:** Don't use `CreateDefaultEditors` + `AutoPost` on grids where you also programmatically add rows. Use the button/double-click pattern instead (see above).
**Tags:** CreateDefaultEditors, AutoPost, Append, Dataset not in edit or insert mode
---

## dsEdit / dsInsert constants don't exist in MaxBasic
**Problem:** `tblName.State = dsEdit` causes "Unexpected token 'dsEdit'" — these Delphi dataset state constants are not available.
**Solution:** Don't check dataset state. Use Try/Catch around Save calls, or structure code to always know the state.
**Tags:** dsEdit, dsInsert, dsBrowse, State, dataset state
---

## Design Version in .pfd files
**Problem:** Using `Version="3"` in the Design element may cause issues.
**Solution:** Use `Version="1"` to match working forms (e.g. OrderExitForm.pfd, Qty_Entry.pfd). Some forms use `Version="2"` — both 1 and 2 seem to work.
**Tags:** Design, Version, pfd, XML
---

## TUserGridEdit class does not exist
**Problem:** Adding `<TUserGridEdit>` as a child of `TUserEditGrid` causes "Class TUserGridEdit not found" crash.
**Solution:** Grid editors are NOT added as XML child elements. They are created at runtime via `gridName.CreateDefaultEditors` method, or by holding Ctrl and adding a component in the Form Designer GUI.
**Tags:** TUserGridEdit, TUserGridSpinEdit, grid editor, Class not found
---

## InputBox text gets cut off with multi-line prompts
**Problem:** Using `Chr(13)` in InputBox prompt causes text to overlap with the input field — the dialog doesn't resize.
**Solution:** Keep InputBox prompts to a single short line. Don't use `Chr(13)` for multi-line prompts.
**Tags:** InputBox, Chr(13), text overlap, dialog
---

## ShowModal may not work from within another modal form
**Problem:** Calling `CreateCustomForm(...).ShowModal` from inside a form that is itself shown modally may silently fail — no form appears, no error shown.
**Solution:** Not yet fully resolved. The button/double-click handler sub may not fire at all. Debug by adding `MsgBox("test")` at the very first line of the sub to confirm it's being called.
**Tags:** ShowModal, modal, nested modal, CreateCustomForm, button not working
---

## INInvoiceListForm.Invoice.Open conflicts if invoice is already open in UI
**Problem:** Using `INInvoiceListForm` + `Invoice.Open` to edit an invoice that is already open in the Accredo UI causes "Error resolving Save (80020006)". This is a COM conflict — the form-level object clashes with the already-open form.
**Solution:** Use `INInvoiceData` (data-level object) instead of `INInvoiceListForm` (form-level). Find the invoice DocumentID via `ExecuteSQL` on INHEAD, then use `CreateObject("Accredo.INInvoiceData")` with `FindExact(DocumentID)` to edit at the data level. This avoids any conflict with open UI forms.
**Tags:** INInvoiceListForm, INInvoiceData, Invoice.Open, Error resolving Save, 80020006, MIXJOTUN, COM error
---

## tblMemoryTable.Eof can be True even with rows present
**Problem:** After operations like Append/Save/Delete, the cursor can end up past the last record, making `.Eof` return True even though the table has rows (RecordCount > 0).
**Solution:** Before accessing current row data, check `RecordCount` first, then call `.First` or `.Last` to reposition the cursor. Don't rely solely on `.Eof` to determine if rows exist.
**Tags:** Eof, RecordCount, memory table, cursor position, TUserMemoryTable
---

## IN Invoice lines use QuantitySupplied, not Quantity
**Problem:** Setting `INDATA.Line.Quantity = value` on an IN Invoice line silently fails — the field doesn't exist. Lines save but with no quantity, so they appear blank/zero.
**Solution:** Use `INDATA.Line.QuantitySupplied` instead. IN Invoice lines use `QuantitySupplied` as the quantity field, not `Quantity`.
**Tags:** INInvoiceData, QuantitySupplied, Quantity, invoice line, silent fail
---

## OEDATA.GenerateInvoice returns DocumentID not DocumentNo
**Problem:** `OEDATA.GenerateInvoice` returns the invoice's internal `DocumentID` (e.g. 3187), not the display invoice number (e.g. "11608"). Passing this directly as an invoice reference shows wrong number.
**Solution:** Look up the actual display number: `INInvoiceData.FindExact(INNumber)` then use `INInvoiceData.DocumentNo`.
**Tags:** GenerateInvoice, DocumentID, DocumentNo, invoice number, OEOrderData
---
