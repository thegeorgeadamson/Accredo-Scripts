# Scripted Forms

> Scripted form properties, methods, events, and development

**Sections:** 35

---

## Quick Reference

- [ActiveProperty - Scripted Form Property](#activeproperty---scripted-form-property)
- [Caption - Scripted Form Property](#caption---scripted-form-property)
- [ClassName - Scripted Form Property](#classname---scripted-form-property)
- [Execute - Scripted Form Method](#execute---scripted-form-method)
- [GetValue - Scripted Form Method](#getvalue---scripted-form-method)
- [InputBinCode - Scripted Form Method](#inputbincode---scripted-form-method)
- [InputBoolean - Scripted Form Method](#inputboolean---scripted-form-method)
- [InputBox - Scripted Form Method](#inputbox---scripted-form-method)
- [InputButton - Scripted Form Method](#inputbutton---scripted-form-method)
- [InputCode - Scripted Form Method](#inputcode---scripted-form-method)
- [InputContact - Scripted Form Method](#inputcontact---scripted-form-method)
- [InputContact Scripted Form Example](#inputcontact-scripted-form-example)
- [InputCountry - Scripted Form Method](#inputcountry---scripted-form-method)
- [InputCustomCode - Scripted Form Method](#inputcustomcode---scripted-form-method)
- [InputDate - Scripted Form Method](#inputdate---scripted-form-method)
- [InputDeliveryAddress - Scripted Form Method](#inputdeliveryaddress---scripted-form-method)
- [InputEnum - Scripted Form Method](#inputenum---scripted-form-method)
- [InputFileOpen - Scripted Form Method](#inputfileopen---scripted-form-method)
- [InputFileSave - Scripted Form Method](#inputfilesave---scripted-form-method)
- [InputFolder - Scripted Form Method](#inputfolder---scripted-form-method)
- [InputGrid - Scripted Form Method](#inputgrid---scripted-form-method)
- [InputInteger - Scripted Form Method](#inputinteger---scripted-form-method)
- [InputList - Scripted Form Method](#inputlist---scripted-form-method)
- [InputMemo - Scripted Form Method](#inputmemo---scripted-form-method)
- [InputNumber - Scripted Form Method](#inputnumber---scripted-form-method)
- [InputPeriod - Scripted Form Method](#inputperiod---scripted-form-method)
- [InputPrinter - Scripted Form Method](#inputprinter---scripted-form-method)
- [InputTime - Scripted Form Method](#inputtime---scripted-form-method)
- [Name- - Scripted Form Property](#name----scripted-form-property)
- [Scripted Form Example](#scripted-form-example)
- [Scripted Forms](#scripted-forms)
- [ScriptedForm Object](#scriptedform-object)
- [SetValue - Scripted Form Method](#setvalue---scripted-form-method)
- [ShowStatusHint - Scripted Form Method](#showstatushint---scripted-form-method)
- [ShowText - Scripted Form Method](#showtext---scripted-form-method)

---

## ActiveProperty - Scripted Form Property

Source: https://accredo.co.nz/webhelp/ActiveProperty.htm

ActiveProperty - Scripted Form Property
property
ActiveProperty: String
This returns property on the scripted form that is active.
Setting the ActiveProperty to "" sets focus to the Masterfile Code selection.
For example:
ARCustomerForm.ActiveProperty = ""
Sets the focus to the AR Customer Form Customer Code drop-down field.
See Also
ScriptedForm Object

---

## Caption - Scripted Form Property

Source: https://accredo.co.nz/webhelp/CaptionProperty.htm

Caption - Scripted Form Property
property
Caption: String
This returns the caption displayed on the scripted form's title bar.
See Also
ScriptedForm Object

---

## ClassName - Scripted Form Property

Source: https://accredo.co.nz/webhelp/ClassNameProperty.htm

ClassName - Scripted Form Property
property
ClassName: String (Read-only)
This returns the class name of the scripted form. Always returns "Scripted Form".
See Also
ScriptedForm Object

---

## Execute - Scripted Form Method

Source: https://accredo.co.nz/webhelp/ExecuteMethod.htm

Execute - Scripted Form Method
method
Execute: Boolean
Display the form or dialog modally, and return
True
if the User selects the OK or Open button.
See Also
ScriptedForm Object

---

## GetValue - Scripted Form Method

Source: https://accredo.co.nz/webhelp/MBGetValue.htm

GetValue - Scripted Form Method
method
GetValue(ControlName: String): Variant
This returns the value of the previously defined control named Control Name. The type of the value varies depending on the type of the control.
GetValue method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control to retrieve the value from.
See Also
ScriptedForm Object

---

## InputBinCode - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputBinCodeSFMethod.htm

InputBinCode - Scripted Form Method
Accredo Saturn only, use InputCode.
method
InputBinCode(ControlName: String, Location: String, Prompt: String[, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean]): String (Accredo Saturn only, use InputCode in Accredo Mercury.)
Define a lookup control on a scripted form that allows input of a Bin Code.
InputBinCode method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Location
Required. The Location to show Bin Codes for.
Prompt
Required. Prompt text to display to left of the control.
Filter
Optional. String containing a filter value to apply to Bins available.
Filter Button Visible
Optional, defaults to
False
. Determines whether to display the Filter button.
Allow Inactive
Optional, defaults to
False
. Determines if Inactive Bins are available.
See also MaxBasic
InputBinCode
function.

---

## InputBoolean - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputBooleanSFMethod.htm

InputBoolean - Scripted Form Method
method
InputBoolean(ControlName: String, Prompt: String)
Define a checkbox control on a scripted form that allows selection of boolean (yes/no) values.
InputBoolean method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to the left of the control.
See also MaxBasic
InputBoolean
function and Input Grid
InputBoolean
method.
See Also
ScriptedForm Object

---

## InputBox - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputBoxSFMethod.htm

InputBox - Scripted Form Method
method
InputBox(ControlName: String, Prompt: String[, PasswordChar: Char])
Define a single line text edit control on a scripted form that allows input of arbitrary text.
InputBox method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to the left of the control.
Password Char
Optional. Character to mask user input.
See also MaxBasic
InputBox
function and Input Grid
InputBox
method.
See Also
ScriptedForm Object

---

## InputButton - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputButtonSFMethod.htm

InputButton - Scripted Form Method
method
InputButton(Glyph: String/Number, OnClick: SubStatement, Caption: String)
Define a button control on a scripted form that runs a Sub Statement when clicked.
InputButton method syntax has these named arguments:
Parameter
Description
Glyph
Required. String or number identifying the glyph to be displayed on the button.
On Click
Required. The Sub Statement to be called when the button is clicked. Use
GetRef
to define the sub statement.
Caption
Required. The text to be displayed on the button.
See also Input Grid
InputButton
method.
See Also
ScriptedForm Object

---

## InputCode - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputCodeSFMethod.htm

InputCode - Scripted Form Method
method
InputCode(ControlName: String, CodeType: String, Prompt: String[, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean, AllowEmpty: Boolean, UseExactMatch: Boolean])
Define a lookup control on a scripted form that allows input of a code from a specified master record.
InputCode method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Code Type
Required. Code type to display in the Lookup.
Prompt
Required. Prompt text to display to left of the control.
Filter
Optional. Filter expression for limiting available master file code.
Filter Button Visible
Optional. Determines if the filter button is available on the control. Defaults to
True.
Allow Inactive
Optional. Determines if Display Inactive Records button is available on the control. Defaults to
False.
Allow Empty
Optional. Determines if the Lookup can be cleared after a value has been selected. Defaults to
False.
Use Exact Match
Optional. Determines if the Lookup can accept and return values not in the code list. Defaults to
True.
See also MaxBasic
InputCode
function and Input Grid
InputCode
method.
See Also
ScriptedForm Object

---

## InputContact - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputContactSFMethod.htm

InputContact - Scripted Form Method
method
InputContact(ControlName: String, CodeType: String, CodeValue: String, Prompt: String[, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean])
Define a lookup control on a scripted form that allows input of a Contact.
InputContact method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Code Type
Required. The contact table name. Use "ARCONTCT" for AR Contacts or "APCONTCT" for AP Contacts.
Code Value
Required. Can be blank for all contacts, or set to a Customer or Creditor code to limit to contacts for a particular Customer or Creditor, based on the Code Type.
Prompt
Required. Prompt text to display to left of the control.
Filter
Optional. String containing a filter value to apply to contacts available.
Filter Button Visible
Optional, defaults to
False
. Determines whether to display the Filter button.
Allow Inactive
Optional, defaults to
False
. Determines if Inactive Contacts are available.
InputContact has the following method:
Method
Description
SetSubset
Use the SetSubset method to filter the list of contacts shown, such as to show the contacts for a particular Customer or Creditor. For example:
eContact.SetSubset(eCustomer.Value)
InputContact has the following property:
Property
Description
IndexName
Use the IndexName property to index the contacts shown in the list. Valid values are the IndexName values for the table specified in the Code Type parameter (ARCONTCT or APCONTCT).
For example:
eContact.IndexName = "CodeLastFirst"
To see other Methods and Properties for the InputContact object, use the MaxBasic
DocumentObject
function. For example:
DocumentObject(eContact)
For an example of a using an InputContact object on a scripted form to prompt for a customer, then set the InputContact to match the Customer selected, see
InputContact Scripted Form Example
.
See also MaxBasic
InputContact
function.
In This Section
InputContact Scripted Form Example
See Also
ScriptedForm Object

---

## InputContact Scripted Form Example

Source: https://accredo.co.nz/webhelp/InputContactSFExample.htm

InputContact Scripted Form Example
The following example code uses a scripted form to prompt for a Customer, then set the lists of contacts to match the customer.
Dim eCustomer as Object, eContact as Object
Sub OnCustomerExit(Sender as object)
If eCustomer.Value <> "" Then
eContact.SetSubset(eCustomer.Value)
End If
End Sub
Dim scForm1 as Object
scForm1 = CreateObject("Accredo.ScriptedForm")
eCustomer = scForm1.InputCode("eCust","ARCUST","Customer Code","",True,False,True)
eContact = scForm1.InputContact("eContactID", "ARCONTCT", "","Contact","",false,true)
eCustomer.OnExit = AddressOf(OnCustomerExit)
'DocumentObject(eContact)
'Print eContact.IndexName
Do
If scForm1.Execute Then
scForm1.BringtoFront
eCustomerCode = scForm1.GetValue("eCust")
eContactID = scForm1.GetValue("eContactID")
Exit Do
Else
'Cancelled
Abort("",true)
End If
Loop

---

## InputCountry - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputCountrySFMethod.htm

InputCountry - Scripted Form Method
method
InputCountry(ControlName: String, Prompt: String[, Default: String, AllowEmpty: Boolean])
Define a lookup control on a scripted form that allows input of a Country code.
InputCountry method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Default
Optional. Default value to be displayed.
Allow Empty
Optional. Determines if the Lookup can be cleared after a value has been selected. Defaults to
False.
See also MaxBasic
InputCountry
function.
See Also
ScriptedForm Object

---

## InputCustomCode - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputCustomCodeSFMethod.htm

InputCustomCode - Scripted Form Method
method
InputCustomCode(FieldName: String, TableName: String, Prompt: String[, Filter: String, FilterButtonVisible: Boolean, AllowEmpty: Boolean, UseExactMatch: Boolean])
Define a lookup control on a scripted form that allows input of a code from a specified custom table or memory table.
InputCustomCode method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Table Name
Required. Custom table or memory table object to select code to display in the Lookup.
Prompt
Required. Prompt text to display to left of the control.
Filter
Optional. Filter expression for limiting available master file code.
Filter Button Visible
Optional. Determines if the filter button is available on the control. Defaults to
True.
Allow Empty
Optional. Determines if the Lookup can be cleared after a value has been selected. Defaults to
False.
Use Exact Match
Optional. Determines if the Lookup can accept and return values not in the code list. Defaults to
True.
Note: You can load and save customisations to the drop-down list by right-clicking in the list and selecting
Customise
.
See also MaxBasic
InputCustomCode
function and Input Grid
InputCustomCode
method.
See Also
ScriptedForm Object

---

## InputDate - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputDateSFMethod.htm

InputDate - Scripted Form Method
method
InputDate(ControlName: String, Prompt: String)
Define a date edit control on a scripted form that allows input of a date.
InputDate method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to the left of the control.
See also MaxBasic
InputDate
function and Input Grid
InputDate
method.
See Also
ScriptedForm Object

---

## InputDeliveryAddress - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputDeliveryAddressSFMethod.htm

InputDeliveryAddress - Scripted Form Method
method
InputDeliveryAddress(ControlName: String, CodeValue: String, Prompt: String[, Filter: String, FilterButtonVisible: Boolean])
Define a lookup control on a scripted form that allows input of a Delivery address.
InputDeliveryAddress method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Code Value
Required. The Customer Code to select the address for.
Prompt
Required. Prompt text to display to left of the control.
Filter
Optional. String containing a filter value to apply to delivery addresses available.
Filter Button Visible
Optional, defaults to
False
. Determines whether to display the Filter button.
See also MaxBasic
InputDeliveryAddress
function.
See Also
ScriptedForm Object

---

## InputEnum - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputEnumSFMethod.htm

InputEnum - Scripted Form Method
method
InputEnum (ControlName: String, Domain: String, Prompt: String[, Default: String, AllowEmpty: Boolean])
Define a Lookup control on a scripted form that allows input of an enum (Enumerated Type) from a domain.
InputEnum method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Domain
Required. Enum domain.
Prompt
Required. Prompt text to display to left of the control.
Default
Optional. Default value to be displayed.
Allow Empty
Optional. Determines if the Lookup can be cleared after a value has been selected. Defaults to
False.
See also MaxBasic
InputEnum
function.
See Also
ScriptedForm Object

---

## InputFileOpen - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputFileOpenSFMethod.htm

InputFileOpen - Scripted Form Method
method
InputFileOpen(ControlName: String, Prompt: String[, Title: String, InitialDirectory: String, Filter: String]) : Object
Define a file select control on a scripted form that allows input of a file name.
InputFileOpen method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Title
Optional. String expression in the title bar of the Select File dialog box. If you omit title, "Select File" is placed in the title bar.
Initial Directory
Optional. The initial directory the file will load from, for example, "C:\".
Filter
Optional. The list of file filters, with a description and file type, separated by pipes, for example:
"JPG Files (*.jpg)|*.jpg|PNG Files (*.png)|*.png|All Files|*.*"
See also MaxBasic
InputFileOpen
function.
See Also
ScriptedForm Object

---

## InputFileSave - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputFileSaveSFMethod.htm

InputFileSave - Scripted Form Method
method
InputFileSave(ControlName: String, Prompt: String[, Title: String, InitialDirectory: String, Filter: String, DefaultExtension: String]) : Object
Define a file select control on a scripted form that allows input of a file name.
InputFileSave method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Title
Optional. String expression in the title bar of the Select File dialog box. If you omit title, "Select File" is placed in the title bar.
Initial Directory
Optional. The initial directory the Windows file select dialog will open in, for example, "C:\Data".
Filter
Optional. The list of file filters for the Save as Type selection, separated by pipes, for example, "Text Files(*.txt)|*.txt|All Files|*.*".
Note that the first extension in the list is applied as the default extension if one is not specified.
Default Extension
Optional. If specified, then this extension gets added to the end of the file name which is returned if an extension is not specified.
See also MaxBasic
InputFileSave
function.
See Also
ScriptedForm Object

---

## InputFolder - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputFolderSFMethod.htm

InputFolder - Scripted Form Method
method
InputFolder(ControlName: String, Prompt: String[, Title: String, InitialDir: String])
Define a folder select control on a scripted form that allows input of a folder name.
InputFolder method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Title
Optional. String expression in the title bar of the Select File dialog box. If you omit title, "Browse for Folder" is placed in the title bar.
Initial Directory
Optional. The initial directory the folder will load from, for example, "C:\".
See also MaxBasic
InputFolder
function.
See Also
ScriptedForm Object

---

## InputGrid - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputGridSFMethod.htm

InputGrid - Scripted Form Method
method
InputGrid
(ControlName: String, Prompt: String, Table: Object[, Height: Number, Width: Number])
Define a grid control on a scripted form that allows viewing and editing of data in a predefined table. Returns the grid object created so that further grid properties can be manipulated.
InputGrid method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Table
Required. Dataset object to use to provide storage for the grid control.
Height
Optional. Height in pixels of the grid control, defaults to 100.
Width
Optional. Width in pixels of the grid control, defaults to 300.
See Also
ScriptedForm Object

---

## InputInteger - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputIntegerSFMethod.htm

InputInteger - Scripted Form Method
method
InputInteger(ControlName: String, Prompt: String)
Define a spin edit control on a scripted form that allows input of integer values.
InputInteger method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
See also MaxBasic
InputInteger
function and Input Grid
InputInteger
method.
See Also
ScriptedForm Object

---

## InputList - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputListSFMethod.htm

InputList - Scripted Form Method
method
InputList(ControlName: String, Prompt: String[, AllowEmpty: Boolean, UseExactMatch: Boolean, Value1: String, ...])
Define a combo edit control on a scripted form that allows selection from a defined set of values.
InputList method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Allow Empty
Optional. Determines if the Lookup can be cleared after a value has been selected, defaults to
False.
Use Exact Match
Optional Determines if the Lookup can accept and return values not in the code list, defaults to
True.
Value(s)
Optional. A string list of parameter values, with values separated by a comma (,).
See also MaxBasic
InputList
function and Input Grid
InputList
method.
See Also
ScriptedForm Object

---

## InputMemo - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputMemoSFMethod.htm

InputMemo - Scripted Form Method
method
InputMemo(ControlName: String, Prompt: String[, MemoHeight: Number, MemoWidth: Number][, Maxlength: Number])
Define a memo control on a scripted form that allows input of arbitrary text. You can optionally set the control height and width.
InputMemo method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Memo Height
Optional. The height of the Memo control.
Memo Width
Optional. The width of the Memo control.
Max Length
Optional. Set the maximum number of characters that can be entered in the memo.
See also MaxBasic
InputMemo
function.
See Also
ScriptedForm Object

---

## InputNumber - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputNumberSFMethod.htm

InputNumber - Scripted Form Method
method
InputNumber(ControlName: String, Prompt: String[, Domain: String, CurrencyCode: String])
Define a number edit control on a scripted form that allows input of arbitrary numbers.
InputNumber method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Domain
Optional. Domain to be applied to the number. Valid domains are listed in
Domains
.
Currency Code
Optional. String expression representing the Currency Code for the number.
Domain
must be set to either
Amount
,
Price
,
Cost Price
or
Sell Price
.
See also MaxBasic
InputNumber
function and Input Grid
InputNumber
method.
See Also
ScriptedForm Object

---

## InputPeriod - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputPeriodSFMethod.htm

InputPeriod - Scripted Form Method
method
InputPeriod(ControlName: String, Prompt: String[, PeriodFrom: Number, PeriodTo: Number, Financial: Boolean])
Define a period combo control on a scripted form that allows input of financial periods.
InputPeriod method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Period From
Optional. Period ID to restrict available periods. First period available in the look-up control.
Period To
Optional. Period ID to restrict available periods. Last period available in the look-up control.
Financial
Optional. Determines if only Financial periods are included. If
True
, restricts periods to Financial periods only. If
False
, includes Financial and Adjustment periods. Defaults to
True.
See also MaxBasic
InputPeriod
function and Input Grid
InputPeriod
method.
See Also
ScriptedForm Object

---

## InputPrinter - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputPrinterSFMethod.htm

InputPrinter - Scripted Form Method
method
InputPrinter(ControlName: String, Prompt: String[, Default: String, AllowEmpty: Boolean])
Define a printer list control on a scripted form that allows selection of a printer by name.
InputPrinter method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Default
Optional. Printer name displayed in the look-up control as the default response if no other input is provided. If you omit default, the default printer for Accredo is displayed.
Allow Empty
Optional, defaults to
False
. Determines if the Lookup can be cleared after a value has been selected.
See also MaxBasic
InputPrinter
function.
See Also
ScriptedForm Object

---

## InputTime - Scripted Form Method

Source: https://accredo.co.nz/webhelp/InputTimeSFMethod.htm

InputTime - Scripted Form Method
method
InputTime (ControlName: String, Prompt: String[, Default: Time])
Define a time edit control on a scripted form that allows input of a time.
InputTime method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Prompt
Required. Prompt text to display to left of the control.
Default
Optional. Time expression displayed in the time control as the default response if no other input is provided. If you omit default, the time control is displayed empty.
See also MaxBasic
InputTime
function.
See Also
ScriptedForm Object

---

## Name- - Scripted Form Property

Source: https://accredo.co.nz/webhelp/NameProperty.htm

Name- - Scripted Form Property
property
Name: String
This returns the name of the scripted form.
See Also
ScriptedForm Object

---

## Scripted Form Example

Source: https://accredo.co.nz/webhelp/MBScriptedFormExample.htm

Scripted Form Example
'This example introduces the concept of a scripted form. When we use the Input Functions to prompt for input, we are limited to one prompt at a time. We can take this further and use a scripted form to prompt for multiple pieces of information. The following script shows the use of a form and some of the different types of information we can prompt for, that displays the details.
'You can cut and paste this code into the
Script Editor
, then click
Run
to execute the code.
Dim Form as Object
Form = CreateObject("Accredo.ScriptedForm")
'Create the form and assign it into an object variable.
Form.Caption = "Test Dialog"
Form.ShowText("This is some text that is here to test the" & _
" automatic word wrapping and sizing of static text" & _
" boxes in the new dialogs")
'Add explanatory text to the form.
Form.InputCode("CustCode", "ARCUST", "Customer code", "BalanceTotal <> 0.00", False)
'The first control defined is a Lookup on the Customer code with a filter expression.
Form.InputBox("Text", "Talk to me")
Form.InputBoolean("checkbox", "Like this?")
Form.InputDate("Date", "What date?")
Form.SetValue("Date", SystemDate)
Form.InputNumber("Number", "How many?")
Form.InputInteger("Integer", "How few")
Form.InputList("List", "Which one", "Item1","Item2","ItemN")
Form.InputMemo("Memo","Enter memo")
Form.SetValue("Memo","Blah, blah, blah.")
'Add input controls that gather more information from the User, then start a loop that will either terminate once the User has entered some valid data, or clicks Cancel to stop the process. In this case the validity of the data is defined by the User selecting a Customer.
Do
If Form.Execute Then
CustCode = Form.GetValue("CustCode")
If CustCode <> "" Then
Print CustCode
Print Form.GetValue("checkbox")
Print Form.GetValue("Date")
Print Form.GetValue("List")
Print Form.GetValue("Memo")
Exit Do
Else
MsgBox("Select a Customer code")
End If
Else
Abort("Cancelled by User")
End If
Loop

---

## Scripted Forms

Source: https://accredo.co.nz/webhelp/MaxBasicScriptedForms.htm

Scripted Forms
Scripted forms are Accredo form that are created in a script, and can be used to create and display modal dialog boxes for gathering data and feedback from Users. Scripted forms use standard controls that interact with Accredo forms. Use a
Scripted Form object
to define the controls, once controls are defined the form will display on Execute, until a User accepts or cancels the form.
See
Scripted Form example
for an example of a script that creates a scripted form to capture user input.
For help regarding a specific scripted form, contact the person who created the form.
In This Section
Scripted Form Example
ScriptedForm Object
InputGrid Object
SF Tutorial: Select Multiple Products on Invoice

---

## ScriptedForm Object

Source: https://accredo.co.nz/webhelp/ScriptedForm.htm

ScriptedForm Object
As well as the standard properties and methods available on all forms, the ScriptedForm object has the following properties and methods to create controls, store and retrieve values, and control execution.
Property
Description
ActiveProperty
Return the name of the property on the scripted form that is active.
Caption
Return the caption displayed on the form's title bar.
ClassName
Return the class name of the scripted form.
Name
Return the name of the scripted form.
Method
Description
Close
Close the scripted form.
Execute
Display the scripted form modally.
GetPropertyValue
Return the value of a property or MaxBasic variable.
GetValue
Return the value of a control.
InputBinCode
Define a control that allows input of a Bin code.(Saturn only)
InputBoolean
Define a checkbox for a boolean value.
InputBox
Define a single line text edit control.
InputButton
Define a button control.
InputCode
Define a control that allows input of a code.
InputContact
Define a control that allows input of a Contact.
InputCountry
Define a control that allows input of a Country Code.
InputCustomCode
Define a control that allows input of a custom defined code.
InputDate
Define a control that allows input of a date.
InputDeliveryAddress
Define a control that allows input of a Delivery Address.
InputEnum
Define a control that allows input of an enum.
InputFileOpen
Define a file select control to open a file.
InputFileSave
Define a file select control to save a file.
InputFolder
Define a folder select control.
InputGrid
Define a grid control.
InputInteger
Define a spin edit control that allows input of a integer.
InputList
Define a combo edit control that allows selection from a set of values.
InputMemo
Define a memo control that allows input of text.
InputNumber
Define a number edit control that allows input of a number.
InputPeriod
Define a period combo control that allow input of a financial period.
InputPrinter
Define a printer list control that allows selection of a printer.
InputTime
Define a time edit control that allows input of a time.
PropertyType
Returns the type of a property.
SendToBack
Send the scripted form to the back of open objects and windows.
SetPropertyValue
Set the value of a property of MaxBasic variable.
SetValue
Store a value in a control.
ShowErrorHint
Display the Error Hint for a control.
ShowStatusHint
Display the Status Hint for a control.
ShowText
Display text on the scripted form.
In This Section
ActiveProperty - Scripted Form Property
Caption - Scripted Form Property
ClassName - Scripted Form Property
Name- - Scripted Form Property
Close - Method
Execute - Scripted Form Method
GetPropertyValue - Method
GetValue - Scripted Form Method
InputBinCode - Scripted Form Method
InputBoolean - Scripted Form Method
InputBox - Scripted Form Method
InputButton - Scripted Form Method
InputCode - Scripted Form Method
InputContact - Scripted Form Method
InputCountry - Scripted Form Method
InputCustomCode - Scripted Form Method
InputDate - Scripted Form Method
InputDeliveryAddress - Scripted Form Method
InputEnum - Scripted Form Method
InputFileOpen - Scripted Form Method
InputFileSave - Scripted Form Method
InputFolder - Scripted Form Method
InputGrid - Scripted Form Method
InputInteger - Scripted Form Method
InputList - Scripted Form Method
InputMemo - Scripted Form Method
InputNumber - Scripted Form Method
InputPeriod - Scripted Form Method
InputPrinter - Scripted Form Method
InputTime - Scripted Form Method
PropertyType - Method
SendToBack - Method
SetPropertyValue - Method
SetValue - Scripted Form Method
ShowErrorHint - Method
ShowStatusHint - Scripted Form Method
ShowText - Scripted Form Method
See Also
Scripted Forms

---

## SetValue - Scripted Form Method

Source: https://accredo.co.nz/webhelp/MBSetValue.htm

SetValue - Scripted Form Method
method
SetValue(ControlName: String, Value: Variant[, SetReadOnly: Boolean])
Store a value into a previously defined control named by the parameter. The type of the value varies depending on the type of the control.
SetValue method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of the control. Must be a valid MaxBasic identifier.
Value
Required. Value to store into the control.
Set Read Only
Optional. If
True
, the value is read-only. Defaults to
False.
See Also
ScriptedForm Object

---

## ShowStatusHint - Scripted Form Method

Source: https://accredo.co.nz/webhelp/ShowStatusHintSFMethod.htm

ShowStatusHint - Scripted Form Method
method
ShowStatusHint(Hint: String[, FieldName: String])
For scripted forms, display the Status Hint for a field.
ShowStatusHint method syntax has these named arguments:
Parameter
Description
Hint
Required. Status hint to be displayed.
Field Name
Optional. Name of the field to have the status hint displayed. Defaults to the current field.
See also MaxBasic
ShowStatusHint
function.
See Also
ScriptedForm Object

---

## ShowText - Scripted Form Method

Source: https://accredo.co.nz/webhelp/MBShowText.htm

ShowText - Scripted Form Method
method
ShowText(Text: String)
Display arbitrary text on the scripted form. This will be displayed as a label, with the width of the form, anchored left and right.
ShowText method syntax has these named arguments:
Parameter
Description
Text
Required. Text to display on the form.
See Also
ScriptedForm Object

---

