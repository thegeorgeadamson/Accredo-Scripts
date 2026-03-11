# Invoicing (IN)

> Invoices, charge rates, invoice categories, invoice processing

**Sections:** 90

---

## Quick Reference

- [Export Invoices Example](#export-invoices-example)
- [Extend Start New Invoice Script](#extend-start-new-invoice-script)
- [FD Tutorial: Dashboard Current Period Invoices](#fd-tutorial-dashboard-current-period-invoices)
- [Import Invoices Example](#import-invoices-example)
- [Import Invoices Example - Line Type 1 tab](#import-invoices-example---line-type-1-tab)
- [Import Invoices Example - Other Line Type tabs](#import-invoices-example---other-line-type-tabs)
- [Import Invoices Example - Process Save tab](#import-invoices-example---process-save-tab)
- [IN Categories](#in-categories)
- [IN Change Tracking Log](#in-change-tracking-log)
- [IN Charges](#in-charges)
- [IN Email Invoice Results](#in-email-invoice-results)
- [IN Email Invoices](#in-email-invoices)
- [IN Email Printed Invoices](#in-email-printed-invoices)
- [IN Enter Invoices](#in-enter-invoices)
- [IN Enter Memos](#in-enter-memos)
- [IN Find Document By Number](#in-find-document-by-number)
- [IN Find Document By Order No](#in-find-document-by-order-no)
- [IN HTML Document Designer Wizard](#in-html-document-designer-wizard)
- [IN Insufficient Query](#in-insufficient-query)
- [IN Invoice Designer](#in-invoice-designer)
- [IN Invoice Email Designer](#in-invoice-email-designer)
- [IN Invoice HTML Designer](#in-invoice-html-designer)
- [IN Invoice Labels](#in-invoice-labels)
- [IN Invoice Line Fields](#in-invoice-line-fields)
- [IN Invoice List](#in-invoice-list)
- [IN Invoice Reports - Add Layout](#in-invoice-reports---add-layout)
- [IN Invoices - Charges tab](#in-invoices---charges-tab)
- [IN Invoices - Header tab](#in-invoices---header-tab)
- [IN Invoices - Lines tab](#in-invoices---lines-tab)
- [IN Invoices - Links tab](#in-invoices---links-tab)
- [IN Invoices - Memos Tab](#in-invoices---memos-tab)
- [IN Label Designer](#in-label-designer)
- [IN Link List](#in-link-list)
- [IN Memo Designer](#in-memo-designer)
- [IN Memo List](#in-memo-list)
- [IN Memo Reports - Add Layout](#in-memo-reports---add-layout)
- [IN Post Invoices](#in-post-invoices)
- [IN Post Invoices Results](#in-post-invoices-results)
- [IN Print Invoices](#in-print-invoices)
- [IN Print Quotes](#in-print-quotes)
- [IN Report Period](#in-report-period)
- [IN Reprice Invoice Results](#in-reprice-invoice-results)
- [IN Reprice Invoices](#in-reprice-invoices)
- [IN Reprint Invoices](#in-reprint-invoices)
- [IN Revalue Foreign Invoices](#in-revalue-foreign-invoices)
- [IN Revalue Foreign Invoices Results](#in-revalue-foreign-invoices-results)
- [IN Settings - Display Labels tab](#in-settings---display-labels-tab)
- [IN Settings - Email tab](#in-settings---email-tab)
- [IN Settings - General tab](#in-settings---general-tab)
- [IN Settings - Links tab](#in-settings---links-tab)
- [IN Settings - Memos tab](#in-settings---memos-tab)
- [IN Settings - Misc tab](#in-settings---misc-tab)
- [IN Settings - Reprice tab](#in-settings---reprice-tab)
- [IN Settings - Rounding tab](#in-settings---rounding-tab)
- [IN Shipper](#in-shipper)
- [IN Tutorial: Add Watermarked Second Page to Invoice](#in-tutorial-add-watermarked-second-page-to-invoice)
- [income](#income)
- [increment](#increment)
- [IndexOf](#indexof)
- [IndexOfName](#indexofname)
- [Initialisation File](#initialisation-file)
- [input](#input)
- [Input Functions](#input-functions)
- [InputGrid Object](#inputgrid-object)
- [Insert](#insert)
- [Insert Links](#insert-links)
- [Install Accredo Client](#install-accredo-client)
- [Install Accredo Server](#install-accredo-server)
- [Install OLEDB/ODBC Drivers](#install-oledb-odbc-drivers)
- [Installation Options](#installation-options)
- [Installation Troubleshooting](#installation-troubleshooting)
- [integrated](#integrated)
- [inventories](#inventories)
- [inventory value](#inventory-value)
- [invoice](#invoice)
- [Invoicing System](#invoicing-system)
- [Invoicing System - Maintain](#invoicing-system---maintain)
- [Invoicing System - Reports](#invoicing-system---reports)
- [Invoicing System - Setup](#invoicing-system---setup)
- [Invoicing System - Tasks](#invoicing-system---tasks)
- [JC Select Invoice](#jc-select-invoice)
- [JC Transaction Invoice Query](#jc-transaction-invoice-query)
- [OE Generate Invoices](#oe-generate-invoices)
- [OE Generate Invoices Results](#oe-generate-invoices-results)
- [OE Select Invoice](#oe-select-invoice)
- [Script to Add Narrative Lines to an Invoice](#script-to-add-narrative-lines-to-an-invoice)
- [Script to Change Invoice Lines](#script-to-change-invoice-lines)
- [Script to Create a New Invoice](#script-to-create-a-new-invoice)
- [Script to Run Standing Invoices](#script-to-run-standing-invoices)
- [Script to Toggle Invoice Lines Type](#script-to-toggle-invoice-lines-type)

---

## Export Invoices Example

Source: https://accredo.co.nz/webhelp/ExportInvoicesExample.htm

Export Invoices Example
Invoices in Accredo can be exported to a file, using the Export Designer Wizard.
Data can be exported to the following file types:
CSV
Tab Separated
Fixed Width
You can select which invoices to export, and which information you would like included.
Exporting invoices can be used for:
Communicating with other companies.
Importing into other software packages.
Exporting invoices for a particular product.
Exporting invoices for a particular customer.
Exporting invoices sent in a given time period.
Export Designer
The
Export Designer
Wizard can generate MaxBasic code to extract Invoice Data from Accredo.
Navigator > Setup > Data Interchange > Export Designer
To extract Invoice data:
Select the Data Module
INInvoiceData
. Click
Next
.
Each Invoice has a Header row, and several Line rows. Select the Master Fields to be included in the
Invoice Header Row
for each Invoice. Use the Move Record Up
and Move Record Down
buttons to order the fields. Click
Next
.
Select the Detail (Line) Fields to include in the
Invoice Line Rows
for each invoice. Use the Move Record Up
and Move Record Down
buttons to order the fields. Click
Next
.
If using Foreign Exchange, select the Foreign Exchange rate fields to include for each invoice. Use the Move Record Up
and Move Record Down
buttons to order the fields. Click
Next
.
Click
Generate
.
The MaxBasic code will be displayed in the
Script Editor
.
The code by default will export the Invoices to a CSV file.
If you wish to export to a Tab separated file:
Inactivate the line of code with
Option Print ",", CHR(34)
, by adding a single quote character (') to the start of the line. This is usually Line 2.
Activate the line of code with
Option Print CHR(9)
, by removing the single quote character (') from the start of the line. This is usually Line 5.
If you wish to export to a fixed width file:
Inactivate the line of code with
Option Print ",", CHR(34)
, by adding a single quote character (') to the start of the line. This is usually Line 2.
Activate the line of code with
Option Print ""
, by removing the single quote character (') from the start of the line. This is usually Line 8.
Click
Save
to save the code as a script file (.pfs). Enter the file name and location and click
Save
. The file can then be run from
EDI Exporting
.
You can also run the code from the Script Editor. Click
Run
. Select fields to filter and sort by. For example, you can select to export invoices for a particular product, customer or time period. Click
Save
. The exported data will be displayed as Script Output.
EDI Exporting
Once the MaxBasic script is created and saved using the Export Designer wizard,
EDI Exporting
can be used to export to a selected file.
Navigator > Reports > EDI Exporting
Type or select the .pfs script file as the Export Definition.
Type or select the File Name to export into.
Select whether to Append to an existing file. If this is
Clear
, the existing file will be overwritten.
Click
Run
. Select fields to filter and sort by. For example, you can select to export invoices for a particular product, customer or time period. Click
Save
.
EDI Exporting will export the data to the specified file.

---

## Extend Start New Invoice Script

Source: https://accredo.co.nz/webhelp/ExtendStartNewInvoiceScript.htm

Extend Start New Invoice Script
This example shows you how to setup a script to:
Open an Invoice
Prompt for Customer code
Fill in header details
Go to first line
Looking back at the first script we wrote in
Script to Create a New Invoice
, we can now look at taking that concept a few steps further. For example we could:
Select whether the user is in a form we can re-use
Use an InputCode to prompt for the Customer code
Auto-fill some header information and take the user into the invoice lines
Open the
NewInvoice1.pfs
script.
Dim frmINInvoice1 as Object
frmINInvoice1 = CreateObject("Accredo.INInvoiceEntryForm")
frmINInvoice1.InsertInvoice
Add code to check if the Invoice Entry form is already open, and make sure an invoice is not currently being edited.
Dim frmINInvoice1 as Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) Or frmINInvoice1.ClassName <> "INInvoiceEntryForm" Then ' Can we reuse the current form
frmINInvoice1 = CreateObject("Accredo.INInvoiceEntryForm") 'f not open a new one
ElseIf frmINInvoice1.ClassName = "INInvoiceEntryForm" And frmINInvoice1.Editing Then
Error "Current Invoice is being edited, Insert cancelled, please save changes and re-try."
End If
frmINInvoice1.InsertInvoice
Add code to auto-fill in some of the header information:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) Or frmINInvoice1.ClassName <> "INInvoiceEntryForm" Then ' Can we reuse the current form
frmINInvoice1 = CreateObject("Accredo.INInvoiceEntryForm") 'f not open a new one
ElseIf frmINInvoice1.ClassName = "INInvoiceEntryForm" And frmINInvoice1.Editing Then
Error "Current Invoice is being edited, Insert cancelled, please save changes and re-try."
End If
frmINInvoice1.InsertInvoice
Customer = InputCode("ARCUST", "Customer code", "Customer")
If IsNull(Customer) Then Error "Cancelled by User"
frmINInvoice1.CustomerCode = Customer
frmINInvoice1.InternalReference = LoginUserName
frmINInvoice1.Comment = Time & " " & Date
Add code to take the user to the Invoice lines:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) Or frmINInvoice1.ClassName <> "INInvoiceEntryForm" Then ' Can we reuse the current form
frmINInvoice1 = CreateObject("Accredo.INInvoiceEntryForm") 'f not open a new one
ElseIf frmINInvoice1.ClassName = "INInvoiceEntryForm" And frmINInvoice1.Editing Then
Error "Current Invoice is being edited, Insert cancelled, please save changes and re-try."
End If
frmINInvoice1.InsertInvoice
Customer = InputCode("ARCUST", "Customer code", "Customer")
If IsNull(Customer) Then Error "Cancelled by User"
frmINInvoice1.CustomerCode = Customer
frmINInvoice1.InternalReference = LoginUserName
frmINInvoice1.Comment = Time & " " & Date
frmINInvoice1.Line.Append

---

## FD Tutorial: Dashboard Current Period Invoices

Source: https://accredo.co.nz/webhelp/FDTutorialCurrentPeriodInvoices.htm

FD Tutorial: Dashboard Current Period Invoices
Using the Form Designer, you can create a dashboard to show current invoice totals, with links to lists of the invoices. This tutorial requires the IN Module.
Go to Navigator > Setup > Form Designer.
Add four Labels to the form. Click the
Label
button, then click on the form, four times.
Set the
Width
of each Label to around
180
, and the
Height
to around
40
. To set properties for multiple components, hold down the Shift key and click each component. You can then set a property for all selected components. You can also drag to resize the components.
Set the
Caption
property of each label to be blank.
Set the
Name
properties of the four labels to:
lblInvOpen
;
lblInvUnposted
;
lblInvPosted
;
lblInvTotal
.
Move the labels next to each other.
Change the colours of the labels, by setting the Color property, to distinguish between them. You could use alternating colours, such as yellow, blue, yellow, blue.
Click the
Link Label
button, then click to add a link label in each of the first three labels.
Set the
Caption
properties of the three link labels to:
OPEN
;
UNPOSTED
;
POSTED
.
Set the
Name
properties of the three link labels to:
linkInvOpen
;
linkInvUnposted
;
linkInvPosted
.
Position one of the Link Labels at the top of a label. Set the Top property of the other Link Labels to be the same.
Set the following properties on the Link Labels:
Property
Value
Alignment
taCentre
ParentColor
True
Transparent
True
Add a Label as a heading, above the existing labels. Click the
Label
button, then click on the form. Set the label
Caption
to
Current Period Invoices - Exclusive Amounts
.
You can change label size, position, font, colour or other properties.
Next, you can write MaxBasic code to add the figures to the labels.
Click on the Code tab. Enter the following:
Sub RefreshCurrentPeriodInvoices
Dim PeriodToUse as Number
Dim TotalSales as Number
PeriodToUse = CurrentPeriod("AR")
TotalSales = 0
'Enter the SQL Query to extract the current Open Invoices
strSQLInvoices ="SELECT   INHEAD.PeriodID as PeriodID " & _
"        ,Sum(INHEAD.ExclusiveAmountBs) as ExclusiveAmount " & _
"FROM   INHEAD " & _
"WHERE INHEAD.PeriodID = :PeriodToUse " & _
"   AND INHEAD.PostStatus = 'O' " & _
"   AND INHEAD.DocumentClass IN ('I', 'C') " & _
"GROUP BY INHEAD.PeriodID " & _
"ORDER BY INHEAD.PeriodID "
tblInvoices = ExecuteSQL(strSQLInvoices, PeriodTouse)
lblInvOpen.caption = "          " & CHR(10) & "                $" & FormatNumber(tblInvoices.ExclusiveAmount, ",0.00")
TotalSales = TotalSales + tblInvoices.ExclusiveAmount
'Enter the SQL Query to extract the current Posted Invoices
SQLInvoices ="SELECT INHEAD.PeriodID as PeriodID " & _
"        ,Sum(INHEAD.ExclusiveAmountBs) as ExclusiveAmount " & _
"FROM   INHEAD " & _
"WHERE INHEAD.PeriodID = :PeriodToUse " & _
"   AND INHEAD.PostStatus = 'P' " & _
"   AND INHEAD.DocumentClass IN ('I', 'C') " & _
"GROUP BY INHEAD.PeriodID " & _
"ORDER BY INHEAD.PeriodID "
tblInvoices = ExecuteSQL(SQLInvoices, PeriodTouse)
lblInvPosted.caption = "         " & CHR(10) & "           $" & FormatNumber(tblInvoices.ExclusiveAmount, ",0.00")
TotalSales = tblInvoices.ExclusiveAmount
'Enter the SQL Query to extract the current Unposted Invoices
strSQLInvoices ="SELECT   INHEAD.PeriodID as PeriodID " & _
"        ,Sum(INHEAD.ExclusiveAmountBs) as ExclusiveAmount " & _
"FROM   INHEAD " & _
"WHERE INHEAD.PeriodID = :PeriodToUse " & _
"   AND INHEAD.PostStatus = 'U' " & _
"   AND INHEAD.DocumentClass IN ('I', 'C') " & _
"GROUP BY INHEAD.PeriodID " & _
"ORDER BY INHEAD.PeriodID "
tblInvoices = ExecuteSQL(strSQLInvoices, PeriodTouse)
lblInvUnPosted.caption = "          " & CHR(10) & "         $" & FormatNumber(tblInvoices.ExclusiveAmount, ",0.00")
TotalSales = TotalSales + tblInvoices.ExclusiveAmount
lblInvTotal.caption = "        TOTAL " & CHR(10) & "      $" & FormatNumber(TotalSales, ",0.00")
End Sub
Create a routine called OnCreate to run when the form is created. This will call the RefreshSales sub-routine. Enter the following code:
Sub OnCreate
RefreshCurrentPeriodInvoices
End Sub
Click the Layout tab. Click on the form, or select the frmFDForm component.
Go to the Events tab. Set
OnCreate
to
OnCreate
.
Click
Save Form
(Ctrl+S)
.
Click
Run
(Ctrl+R)
to test the form.
Next, you can link the Link Labels to lists of invoices.
Click on the Code tab. Enter the following code to display all current open invoices:
Sub ONLinkInvOpen
Dim Form1 as Object
Form1 = CreateObject("Accredo.INInvoiceListForm")
Form1.AutoSelect = True
Form1.ToggleShowAll
Form1.Selection = "All Documents"
Form1.PeriodSelection = "Period"
Form1.Invoice.FilterSort.Filter = "(DocumentClass=""C"" Or DocumentClass=""I"") And (PostStatus=""O"")"
End Sub
Enter the following code to display all current posted invoices:
Sub ONLinkInvPosted
Dim PeriodToUse as Number
PeriodToUse = CurrentPeriod("AR")
SQLInvoices ="SELECT INHEAD.DocumentID as DocumentID " & _
"      ,INHEAD.CustomerCode as Customer " & _
"      ,INHEAD.DocumentDate as Date" & _
"      ,INHEAD.DocumentNo as InvoiceNo " & _
"      ,INHEAD.DocumentClass as Type " & _
"      ,INHEAD.GrossAmountBs as GrossAmount" & _
"      ,INHEAD.PeriodID as PeriodID " & _
"      ,INHEAD.ExclusiveAmountBs as ExclusiveAmount " & _
"FROM   INHEAD " & _
"WHERE INHEAD.PeriodID = :PeriodToUse " & _
"   AND INHEAD.PostStatus = 'P' " & _
"   AND INHEAD.DocumentClass IN ('I', 'C') " & _
"   ORDER BY INHEAD.DocumentID "
tblPostedInvoices = ExecuteSQL(SQLInvoices, PeriodTouse)
tblPostedInvoices.Fields.Item(5).Total=True
tblPostedInvoices.Fields.Item(7).Total=True
Report = CreateReport(tblPostedInvoices, " Posted Invoices For Period " & PeriodName(PeriodToUse))
Report.Destination = "Screen"
Report.Run
End Sub
Enter the following code to display all unposted invoices:
Sub ONLinkInvUnposted
Dim Form1 as Object
Form1 = CreateObject("Accredo.INInvoiceListForm")
Form1.AutoSelect = True
Form1.ToggleShowAll
Form1.Selection = "All Documents"
Form1.PeriodSelection = "Period"
Form1.Invoice.FilterSort.Filter = "(DocumentClass=""C"" Or DocumentClass=""I"") And (PostStatus=""U"")"
End Sub
Link the code to the link labels. Click the linkInvOpen link label, then go to the Events tab. Set
OnClick
to
ONLinkInvOpen
. Set the
OnClick
event for
linkInvUnposted
to
ONLinkInvUnposted
. Set the
OnClick
event for
linkInvPosted
to
ONLinkInvPosted
.
Click
Save Form
(Ctrl+S)
.
Click
Run
(Ctrl+R)
to test the form. When you click on the Link Labels you will see the relevant list of Invoices.
See Also
FD Dashboard Tutorials

---

## Import Invoices Example

Source: https://accredo.co.nz/webhelp/ImportInvoicesExample.htm

Import Invoices Example
You can use the
Import Designer
to import Invoices from another Accredo company, or another accounting system, into Accredo.
Accredo provides a sample import definition files for most masterfiles, including Invoices, in the
\Imports\EDIImports\SampleImports
directory. Corresponding export script files for all import files are also provided in the
\Scripts\EDIExports\SampleExports
directory.
When designing an Import routine, we recommend starting with an existing sample import definition, and modifying it to meet your requirements. The Accredo supplied file is
INInvoice.pfi
.
Go to Navigator > Setup > Data Interchange > Import Designer.
Click
Load...
(Alt+L)
to load the supplied sample Invoice routine, or another Invoice import routing.
Import File
You will need an invoice file to import. You can create a file from Accredo by running the sample Invoice Export script. If you have an existing invoice file to import, you can modify the sample Import routine to match your file.
Set the
Default Input File
to your input file.
You can click the
View Data...
(Alt+W)
button to see the data in the input file.
Definition Tab
The Definition tab is used to define the overall Import routine. The code on the Definition tab will call the code on the other tabs.
The code in the sample Invoice Import file starts with:
Dim Data as Object
Data = CreateObject("Accredo.InInvoiceData")
If you place the cursor in the
InInvoiceData
text then press
F1
, the
InInvoiceData Documentation
will be displayed. This shows all the properties and methods of the InInvoiceData object. Some properties, such as Line have their own properties and methods. This is another object within the INInvoiceData object. The InInvoiceData.Line object contains the Invoice Line information. Other sub-objects are Charge, Ship and Banking. The code creates objects for each of these:
Dim Line as Object
Line = Data.Line
Dim Charge as Object
Charge = Data.Charge
Dim Ship as Object
Ship = Data.Ship
Dim Banking as Object
Banking = Data.Banking
If you are importing each of these objects, you need a LineType tab for each one. In the example, there are 5 line types. Check your input file to see how the data can map to the main InInvoice object, and the sub-objects. In the examples, each line in the input file begins with a line type, showing which object the line has data for.
The following code sets up a loop that reads each line of the data file, and processes the relevant line type.
Do Until ImportFile.EOF
ImportFile.BeginTransaction
ImportFile.GetNextLine
If ImportFile.LineType = "" Then
' Do nothing with blank lines
ElseIf Upper(ImportFile.LineType) = "COMMENT" Then
' Do nothing with comment lines
ElseIf Upper(ImportFile.LineType) = "ININVOICE" Then
ProcessLineType(1)
HeadError = ImportFile.Error
ImportFile.GetNextLine
Do Until Upper(ImportFile.LineType) <> "ININVLN"
If Not HeadError Then ProcessLineType(2)
If ImportFile.Error Then
Line.Cancel
ImportFile.Result = False
End If
ImportFile.GetNextLine
Loop
Do Until Upper(ImportFile.LineType) <> "ININVCHG"
If Not HeadError Then ProcessLineType(3)
If ImportFile.Error Then
Charge.Cancel
ImportFile.Result = False
End If
ImportFile.GetNextLine
Loop
Do Until Upper(ImportFile.LineType) <> "ININVSHP"
If Not HeadError Then ProcessLineType(4)
If ImportFile.Error Then
Ship.Cancel
ImportFile.Result = False
End If
ImportFile.GetNextLine
Loop
Do Until Upper(ImportFile.LineType) <> "ININVBANK"
If Not HeadError Then ProcessLineType(5)
If ImportFile.Error Then
Banking.Cancel
ImportFile.Result = False
End If
ImportFile.GetNextLine
Loop
ImportFile.Rewind
ProcessSave
Else
Print "Unknown line: " & ImportFile.LineType
ImportFile.Error = True
End If
If ImportFile.Error And Data.Editing Then Data.Cancel
ImportFile.EndTransaction
Loop
Data = Nothing
This code checks the first field (
LineType
) of the line. If it is blank, or contains COMMENT (for header lines) it does nothing. If it recognises the Line Type, it calls the relevant Line Type code, then calls
Process Save
. It displays a message if the Line Type is unknown, and it cancels if there is an error processing the line.
See
Import Invoices Example - Process Save tab
,
Import Invoices Example - Line Type 1 tab
and
Import Invoices Example - Other Line Type tabs
for the rest of the example.
In This Section
Import Invoices Example - Process Save tab
Import Invoices Example - Line Type 1 tab
Import Invoices Example - Other Line Type tabs

---

## Import Invoices Example - Line Type 1 tab

Source: https://accredo.co.nz/webhelp/ImportInvoicesExample_LineType1.htm

Import Invoices Example - Line Type 1 tab
See first
Import Invoices Example
.
The Line Type tabs are used to import lines of data into the correct object. Line Type 1 is used for the main data object. Code in the Definition tab calls the LineType code with the
ProcessLineType
(1)
function.
If you select
First Line Contains Headers
on the Definition tab, you can import the field names from the file. Click the
Add Fields
button. (This is not available for ASCII files.) You will be prompted to enter the line number that contains the headers for this line type. Your input file can contain several header records. Alternately, you can enter the fields and offsets.
Validation
In the example Invoice import file, the Line Type 1 code starts by checking that the invoice date falls in the available periods, and is not blank.
If PeriodForDate(DateValue(DocumentDate.Value)) >= FirstAvailablePeriod("AR") and PeriodForDate(DateValue(DocumentDate.Value)) <= LastAvailablePeriod("AR") And PeriodForDate(DateValue(DocumentDate.Value)) <> 0 Then
It then checks if the Invoice is in a foreign currency, and if so, whether Foreign Sales are allowed:
If Not ApplicationSetting("CO\AllowForeignSales") and CurrencyCode.Value <> ApplicationSetting("CO\BaseCurrencyCode") Then
If these criteria are not met, an error message is displayed, and the line is not processed.
Insert Document
The Line Type 1 code then creates the document. To import an Invoice, you need to use the
Insert
Type
method. The example Import routine checks the DocumentClass field, and inserts the relevant type.
Select Case DocumentClass.Value
Case "I"
Data.InsertInvoice
Case "C"
Data.InsertCredit
Case "Q"
Data.InsertQuote
Case "S"
Data.InsertStandingInvoice
End Select
Check Customer
In the example Import routine, the Line Type 1 code checks if the Customer is a foreign customer, and if so, checks whether foreign sales are allowed. If it is an allowed foreign customer, it sets the FX rate details for the Invoice. It then sets the Customer Code for the Invoice.
Dim Customer as Object
Customer = CreateObject("Accredo.ARCustomerData")
Customer.FindExact(CustomerCode.Value)
If Customer.CurrencyCode <> ApplicationSetting("CO\BaseCurrencyCode") Then
If Not ApplicationSetting("CO\AllowForeignSales") Then
Error "Foreign Sales not allowed, cannot import customer with currency " & Customer.CurrencyCode
Else
If Not ApplicationSetting("CO\UseExchangeRateTable") Then
Data.FXRateCache.Insert
Data.FXRateCache.CurrencyCode = Customer.CurrencyCode
Data.FXRateCache.ExchangeRate = ExchangeRate.Value
Else
Data.RateType = RateType.Value
End If
Data.CustomerCode = CustomerCode.Value
Data.ExchangeRate = ExchangeRate.Value
End If
Else
Data.CustomerCode = CustomerCode.Value
End If
Import Fields
The example Import routine Line Type 1 then imports the other fields. Use the
InInvoiceData Documentation
for a list of properties in the  Invoice object, to map the fields in your import file to the InInvoiceData properties. Note that some of the InInvoiceData properties are
required
. You cannot import the Invoice without these fields. Also, some of the InInvoiceData properties are
read-only
. You cannot import these properties.
You can do further validation on fields. The example Import routine checks date fields to ensure they are not blank. For example:
If DocumentDate.Value <> "" Then Data.DocumentDate = DateValue(DocumentDate.Value)
It also sets the Invoice Period to the period the Invoice Date occurs in.
Data.PeriodID = PeriodForDate(Data.DocumentDate)
It checks if Manual Numbering is allowed, and if so it sets the Document Number.
If ApplicationSetting("IN\AllowManualNumbering") Then
Data.DocumentNo = DocumentNo.Value
End If
It then InInvoiceData properties from the fields mapped from the Import File.
Data.OrderNo = OrderNo.Value
Data.SalesPersonCode = SalesPersonCode.Value
....
Ensure all required fields are set, and that all relevant fields in the Import file are mapped and set.

---

## Import Invoices Example - Other Line Type tabs

Source: https://accredo.co.nz/webhelp/ImportInvoicesExample_OtherLineType.htm

Import Invoices Example - Other Line Type tabs
See first
Import Invoices Example
.
Other Line Types are used to import data in to sub-objects. The InInvoiceData sub-objects are:
Line - Invoice Line data, shown on the
IN Invoices - Lines tab
.
Charge - Additional Charge data, shown on the
IN Invoices - Charges tab
.
Ship - Shipper data, shown on the
IN Invoices - Charges tab
.
Bank - Banking data, shown on the
IN Invoices - Charges tab
.
To add Line Type tabs, click
Add Line Type
(Alt+Y)
on the
Import Designer - Definition tab
.
Code in the Definition tab calls the LineType tab code with the
ProcessLineType
(x)
function, such as
ProcessLineType(2)
.
If you select
First Line Contains Headers
on the Definition tab, you can import the field names from the file. Click the
Add Fields
button. (This is not available for ASCII files.) You will be prompted to enter the line number that contains the headers for this line type. Your input file can contain several header records. Alternately, you can enter the fields and offsets.
Use the
InInvoiceData Documentation
for a list of properties in each sub-object. Click the + next to
property
Sub-Object
to see the properties of the sub-object, for example,
property
Line to see the Line sub-object properties. Use this to map fields from the Input file to the sub-object properties.
Enter code in the Line Type tab to set the sub-object properties to mapped fields from the Input file, similarly to
Import Invoices Example - Line Type 1 tab
.
Ensure all required fields are set, and that all relevant fields in the Import file are mapped and set.
After setting all the fields, save the sub-object. In the example Invoice Import, for the Line sub-object (Line Type 2) the code is:
Line.Save

---

## Import Invoices Example - Process Save tab

Source: https://accredo.co.nz/webhelp/ImportInvoicesExample_ProcessSave.htm

Import Invoices Example - Process Save tab
See first
Import Invoices Example
.
The Process Save tab is used to save data after it has been imported. The Definition tab calls this code with the
ProcessSave
function.
In the example Invoice import routine, the code checks for errors, and checks data is in edit mode, then saves the data.
If Not ImportFile.Error And Data.Editing Then
Data.Save
End If

---

## IN Categories

Source: https://accredo.co.nz/webhelp/INCategories.htm

IN Categories
Navigator > Maintain > Invoicing System >
Categories 1 & 2

---

## IN Change Tracking Log

Source: https://accredo.co.nz/webhelp/InvoicingSystemTrackingLog.htm

IN Change Tracking Log
Navigator > Setup > Invoicing System >
Change Tracking Log
See Also
Invoicing System - Setup

---

## IN Charges

Source: https://accredo.co.nz/webhelp/INCharges.htm

IN Charges
Navigator > Setup > Invoicing System > Charges
Edit the charges that appear in the footer section of invoices. User defined charges are available plus a fourth pre-defined charge to handle rounding of invoice totals. These can appear in the footer of the invoice and can be named; examples are Freight and Insurance. Each charge has a GST code and a Sales Group code for where the amount of the charge is to be analysed.
The Rounding charge can only be GST code
E
for exempt. Invoice rounding can be maintained from
Settings
. The charge descriptions apply to screens, reports and printed invoices - unless you use
Invoice Designer
.
Code
Code for the charge type.
Description
Description of the charge type.
GST
GST Rate to be applied to the charges.
Sales Group
Sales Group to analyse the charges to. Search for a sales group using the
Accredo Lookups
.
Print
(Ctrl+P)
Print a report of IN Charges.

---

## IN Email Invoice Results

Source: https://accredo.co.nz/webhelp/INEmailInvoiceResults.htm

IN Email Invoice Results
Navigator > Reports > Invoicing System > Email Invoices >
Run
Navigator > Reports > Invoicing System > Email Printed Invoices >
Run
Lists emailed invoices and those that were not emailed due to error.
Display
Show
All Results
,
Errors
only or
Success
only.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open to view details.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Print
(Ctrl+P)
Print a report of the information in the grid.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Refresh
(F5)
Reloads changes other Users may have made.
Totals
Errors
Total number of invoices that were not emailed due to errors.
Gross Errors
Total amount of the invoices that were not emailed.
Records
Total number of invoices successfully emailed.
Gross Success
Total amount of the invoices successfully emailed.

---

## IN Email Invoices

Source: https://accredo.co.nz/webhelp/INEmailInvoices.htm

IN Email Invoices
Navigator > Reports > Invoicing System > Email Invoices
You can batch email invoices, credits and quotes. Invoices are printed by Invoice number (default), then by Customer code. An invoice with no Invoice number will be allocated the next available computer generated number prior to sending. Invoice email is only generated for customers with an invoice email address. If
Email Contact
is selected on the Invoice, the contact email address is used. An email is created with the invoice attached.
Selections tab
Options depend on individual or batch, and if the invoice has been sent, see
Report Selections Form
.
Format
The format for the attachment.
Adobe PDF
PDF file (that is, a file viewed using Adobe
View Saved Report
on the Reports tab or Adobe Reader).
CSV File
Fields on each line are separated by a comma.
Tab Delimited File
Fields are separated by the Tab character.
Quoted CSV File
All string fields are enclosed in double quote marks(" ").
Excel XLSX File
Excel XLSX file.
HTML Document
Uses the HTML Document design selected in Email Template to print the document in the email body. A default HTML design may be specified in
IN Settings - Email tab
.
PDF and HTML Document
Uses the HTML Document design selected in Email Template to print the document in the email body, and attaches the invoice printed as a pdf using the Report File Name.
Column and row positions for formats other than pdf are specified explicitly in the Invoice document design.
Email Template
For HTML Document formats the file that defines the email body. An HTML Invoice (extension .pfj) designed using IN Invoice HTML Designer. A default HTML design may be specified in
IN Settings - Email tab
.
Click
Open In Designer
to open the selected file in the
IN Invoice HTML Designer
.
For other Formats an email template file (extension .html) designed using IN Invoice Email Designer is loaded in the HTML Email Editor. You can set a default email template from Navigator > Setup > Company > Reporting >
Document Defaults
.
Report File Name
Specifies the file that defines the Invoice layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IN Invoice Designer
.
Customer - From / To
Select a customer or a range of customers.
Date - From / To
Invoice date from to.
Number - From / To
Invoice Number from to.
Type
Available for send invoice batch. Send invoices, credits, quotes, standing invoices or a combination, use
Filter & Sort
.
Post Status
Available for send invoice batch. Send only Unposted invoices, only Posted invoices or all Unprinted invoices.
Up to Period
Select the period to email invoices up to.
Branch
Select the Branch.
Clear,
invoices will be emailed for all. (Accredo Saturn Only)
Attach Links
Selected,
files
linked
to the document will be attached.
Use SMTP Mailing
This defaults from the
User Email settings
.
Selected
, use SMTP to send email from Accredo. The SMTP message defaults will be used. Setup a
Company
and
User defaults
for SMTP mailing.
Clear
, use MAPI (default) to send email from Accredo.
Log SMTP Session
If errors occur using SMTP mailing you can log the conversation with the SMTP Server. After sending the log is opened and can be printed to give to whoever configures the SMTP Server. Show SMTP log is not saved with the User settings, it is available for the duration of Email Invoices only.
Request Read Receipt
You can request notification when an email message is opened by it's recipient.
Consolidate Emails On
Select from:
None
- Emails are not consolidated.
Email
- One email will be sent per email address. If there is more than one invoice, each will be a separate attachment.
Customer and Email
- One email will be sent per email address per Customer Code. If there is more than one invoice, each will be a separate attachment.
The default value is set in
IN Settings Email tab
.
Not available for HTML Document formats.
Consolidate Attachments
Selected
, one attachment is produced for all invoices on an email when consolidating emails.
Trigger Mail Events
Selected
, when Batch Emails are sent, the Mailer Before and After Send events for emails will be triggered for each email.
Note: If emails are consolidated for documents, the Account File and Account Code of first document will be used for the email.
Unselected
, events for Batch Emails will not be triggered.
The default value is set in
Trigger Mail Events for Batch Emails
.
HTML Email Editor tab
See
Email Editor
.
The Email Template specified is loaded.
You can create email templates in the
IN Invoice Email Designer
.
Attachments tab
You can add one or more attachments to be emailed with each email. Email errors return the Customer and email address that failed.
In This Section
IN Email Invoice Results

---

## IN Email Printed Invoices

Source: https://accredo.co.nz/webhelp/INEmailPrintedInvoices.htm

IN Email Printed Invoices
Navigator > Reports > Invoicing System > Email Printed Invoices > Selections tab
You can batch email printed invoices, credits and quotes. Invoices are printed by Invoice number (default), then by Customer code. Invoice email is only generated for customers with an invoice email address. If
Email Contact
is selected for the invoice the contact email address is used.
Selections tab
Format
The format for the attachment.
Adobe PDF
PDF file (that is, a file viewed using Adobe
View Saved Report
on the Reports tab or Adobe Reader).
CSV File
Fields on each line are separated by a comma.
Tab Delimited File
Fields are separated by the Tab character.
Quoted CSV File
All string fields are enclosed in double quote marks(" ").
Excel XLS File
Excel spreadsheet.
HTML Document
Uses the HTML Document design selected in Email Template to print the document in the email body. A default HTML design may be specified in
IN Settings - Email tab
.
PDF and HTML Document
Uses the HTML Document design selected in Email Template to print the document in the email body, and attaches the invoice printed as a pdf using the Report File Name.
Column and row positions for formats other than pdf are specified explicitly in the Invoice document design.
Email Template
For HTML Document formats the file that defines the email body. An HTML Invoice (extension .pfj) designed using IN Invoice HTML Designer. A default HTML design may be specified in
IN Settings - Email tab
.
Click
Open In Designer
to open the selected file in the
IN Invoice HTML Designer
.
For other Formats an email template file (extension .html) designed using IN Invoice Email Designer is loaded in the HTML Email Editor. You can set a default email template from Navigator > Setup > Company > Reporting >
Document Defaults
.
Report File Name
Specifies the file that defines the Invoice layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IN Invoice Designer
.
Customer - From / To
Select a customer or a range of customers.
Date - From / To
Invoice date from to.
Number - From / To
Invoice number from to.
Type
Reprint Invoices, Credits and Quotes, use
Filter & Sort
.
Print Status
Printed
- Include previously printed and emailed documents.
Manual
- Include documents flagged as manual.
Post Status
Print only unposted invoices, only posted invoices or all invoices.
Invoices
Limit invoices to reprint by period or range. To reprint all unposted documents select
All Periods
.
Branch
Select the Branch.
Clear,
invoices will be produced for all.  (Accredo Saturn Only)
Print as Copy
Available if the invoice status is printed (that is, you are individually printing an invoice previously printed or you have selected Reprint Invoices Batch). The standard Accredo Invoice will print the words "COPY ONLY".
Attach Links
Selected,
files
linked
to the document will be attached.
Use SMTP Mailing
This defaults from the
User Email settings
.
Selected
, use SMTP to send email from Accredo. The SMTP message defaults will be used. Setup a
Company
and
User defaults
for SMTP mailing.
Clear
, use MAPI (default) to send email from Accredo.
Log SMTP Session
If errors occur using SMTP mailing you can log the conversation with the SMTP Server. After sending the log is opened and can be printed to give to whoever configures the SMTP Server. Show SMTP log is not saved with the User settings, it is available for the duration of Email Invoices only.
Request Read Receipt
You can request notification when an email message is opened by it's recipient.
Consolidate Emails On
Select from:
None
- Emails are not consolidated.
Email
- One email will be sent per email address. If there is more than one invoice, each will be a separate attachment.
Customer and Email
- One email will be sent per email address per Customer Code. If there is more than one invoice, each will be a separate attachment.
Not available for HTML Document formats.
Consolidate Attachments
Selected
, one attachment if produced for all invoices on an email when consolidating emails.
Trigger Mail Events
Selected
, when Batch Emails are sent, the Mailer Before and After Send events for emails will be triggered for each email.
Note: If emails are consolidated for documents, the Account File and Account Code of first document will be used for the email.
Unselected
, events for Batch Emails will not be triggered.
The default value is set in
Trigger Mail Events for Batch Emails
.
HTML / Plain Text Email Editor tab
See
Email Editor
The email template specified in
Document Defaults
is loaded.
You can create email templates in the
IN Invoice Email Designer
.
Attachments tab
Navigator > Reports > Invoicing System > Email Invoices > Attachments tab
You can add one or more attachments to be emailed with each invoice. Email errors return the Customer and email address that failed.

---

## IN Enter Invoices

Source: https://accredo.co.nz/webhelp/INEnterInvoices.htm

IN Enter Invoices
Navigator > Tasks > Invoicing System > Enter Invoices
Enter Invoices, Credits, Standing Invoices and Quotes. Tools available are based on invoice status and permissions.
See also
IN Invoices - Header tab
for fields on the Header tab.
Invoice Document Types
Invoice
Stock items are allocated on
Save.
Posting an invoice debits the total against the Customer account, adds amounts to Sales Analysis totals and GST and reduces stock levels by the quantities entered. You can post invoices as cash sales to create a matching receipt entry.
Credit
When posted the account is credited with the credit total, amounts are deducted from Sales Analysis totals and quantities entered for stock items are added to the quantity in stock.
Standing Invoice
Use Standing Invoices to create templates for invoices. Items are not allocated from stock for Standing Invoices. When an Invoice is saved from a Standing Invoice, items will be allocated from stock.
Hint: To use a Standing Invoice for many customers, click
Duplicate
(Shift+F4)
and change the Customer code.
Quote
Quotes are similar to a pro-forma invoice. Quotes do not affect accounting or stock figures. An invoice can be generated from a quote.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Click to edit the saved document.
Note: If prices have changed since the document was saved, the changes will not be reflected in the document. To update prices click
Reprice
.
Insert
(F4)
Select a document type from the drop-down menu to create a new document.
Duplicate
(Shift+F4)
Select a document type from the drop-down, to create a duplicate document. When duplicating an Invoice as a Credit, the period of the original document is preserved where possible, to keep contras in the same period as the original document.
For Duplicate to Credit on FX Invoices, the original exchange rate is used and cannot be changed.
Delete
(F3)
Delete the document. Only available for saved, unposted documents, when the user has permission.
Drill Up
(Shift+F11)
Available when the Invoice has been posted. Opens the posted transaction.
For Quotes, opens the Order or Invoice created from the quote.
Drill down
(Shift+F12)
View the source document, only available if the invoice is saved and sourced from another document.
Print
(Ctrl+P)
In Edit mode, the invoice is saved first. Invoices can also be
batch emailed
or
printed
.
Print Label
(Ctrl+L)
Print labels for the current invoice. The number of labels defaults to the total of the quantities in the Shipping grid in the
Charges tab
, if this is greater than zero.
Links
(Alt+F6)
Opens
Links On...
for the record, with a list of links for the record. The button changes to indicate if links are present.
Memos
(F6)
Memos and alarms can be entered or edited. The button changes to indicate if memos and alarms are present. Opens
Memos On...
with a list of Memos.
Print Preview
(Ctrl+R)
View on screen what the printed version of the document will look like.
Reprice
(Alt+R)
When details in the Header tab are changed, changes will apply to new Invoice lines, but not to existing invoice lines. Use the
Reprice
option to update prices for all lines.
Re-pricing defaults to updating the current
Cost Price
,
Selling Price
,
Discount
and
GST Code
. These are based on the Customer and Product.
Select
Description
to update the invoice line description based on the current description for the product. Select
Sales Group
to update the invoice line Sales Group codes based on the current Sales Group for the product.
If you use
Special Pricing
, select
Selling Price
and
Discount
to include all Special Pricing rules.
Re-pricing does not affect
Automatic Kitset
lines, but is applied to all the component lines that comprise the Automatic Kitset. Re-pricing is not applied to Job lines as they have been priced in JC.
Select
GST code
to recalculate the GST for all lines. This is useful if the GST rate changes and you have unprocessed invoices. New GST calculations will also be applied if the GST basis (Inclusive or Exclusive) has changed for the
Price code
. (This would be unusual unless the basis was incorrectly set.)
See also
Reprice Invoices
for re-pricing bulk invoices.
Delete Nil Lines
(Alt+D)
Available when editing, deletes all nil product lines from the invoice. A line is considered to be nil if the quantity, extended cost and extended amount are zero, that is lines containing just a description are considered to be nil. Often this is used when duplicating a Standing Invoice, entering quantities supplied, then deleting lines not being supplied.
Mark Historic
(Alt+T)
Available for standing invoices only.
Changes standing invoice from current to history. The Post Status is changed to Posted. The Standing Invoice can be viewed in
IN Invoice List
when you select
History
documents.
Invoices and credits move to history when printed and posted or deleted; quotes move to history when accepted or deleted.
Refresh Weight and Volume
(Alt+W)
If the weight and / or volume of a Product changes, existing lines on Invoices are not automatically updated. Click
Refresh Weight and Volume
to re-calculate weight and volume from current Product Weight and Volume figures for all lines.
Print Product Labels
(Alt+U)
Print
IC Product Batch Labels
for Diminishing products, manual kitsets and quantities (rounded up to nearest whole number). Product Label design is set in
Document Defaults
.
Invoice from Quote
(Alt+Q)
Available for saved Unposted Quotes only.
Generate an invoice from a quote. Save a quote before generating as an invoice. The invoice can be edited, printed and posted in the same way as an entered invoice. When you generate an invoice from a quote, stock is allocated for the quantities on each line. The status for the Quote is set to Posted when the Invoice is saved.
Order from Quote
(Alt+F)
Available for saved Quotes only, where OE is installed.
Generate a new OE Sales Order based on the current quote.
If the Quote is Unposted, the status for the Quote is set to Posted when the Order is saved and the Order is linked to the Quote as its source.
Note: You cannot create an Order from a Quote with
Entered Discount
amounts but no
Discount Percentage
. Discounts on order lines must be entered as percentages, as Order Lines can be partially supplied.
Order from Invoice
(Alt+I)
Available for Invoices only, where OE is installed. Creates a new OE Sales Order based on the current invoice.
Note: You cannot create an Order from an Invoice with
Entered Discount
amounts but no
Discount Percentage
. Discounts on order lines must be entered as percentages, as Order Lines can be partially supplied.
Cash Sale
(Alt+C)
Available for Invoices and Credits only.
Saves and posts the invoice and a receipt to the Customer account as a cash sale. Enter banking details for the receipt from the
Charges tab
.
The invoice is saved, printed, posted to AR and IC and an associated receipt (based on the banking details entered) is posted to the Customer account. The receipt is allocated against the invoice. All other details for cash sale receipt transactions are taken from the invoice: the reference is the invoice number, date is the invoice date, amount is the invoice total. See
Cash Sales
.
Post Invoice /
Save and Post Invoice Immediately / Post Credit / Save and Post Credit Immediately
(Alt+O)
Available for Invoices and Credits only.
For unsaved invoices, saves first, then posts to AR and IC. Posted invoices can be printed later (for example, in a batch).
For credits, if permissions permit and the Customer Account type is
Open Item
, you will be prompted for Allocation after posting an IN Credit.
Print Packing Slip
(Ctrl+K)
Available for Invoices and Credits. Prints the invoice as a Packing Slip. Packing Slip formatting is set in
Document Defaults
.
Manual Invoice
(Alt+N)
Available for Invoices and Credits only. Only available if the invoice or credit has an
Invoice No
and the
Print Status
is not
Printed
. This sets the
Print Status
to
Manual
. This is useful when a computer printed document is not required.
Convert to Credit/
Convert to Invoice/
Convert
(Alt+V)
Select to change
Document Class
from
Invoice
to
Credit
or
Credit
to
Invoice
and flip quantity sign to retain the same net effect.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Form Fields
Period
Defaults to the System period. You can select another period for invoicing.
Document Type
Shows the Type (Invoice, Credit, Standing Invoice or Quote) and the Invoice Number if entered. Read-only.
ID
An allocated number that identifies the invoice. Read-only.
Order
Shows
OE Generation Basis
:
None
- Not generated from an OE Order.
Packing Slip
- Generated from an OE Order on Packing Slip basis.
Back Order
- Generated from an OE Order on Back Order basis.
Currency and Regime
The
Currency code
and
Tax regime
for the document.
Customer Code
Select the Customer Code before entering details. The Customer Name, Currency and Tax Regime are displayed.
Defaults from the customer including Price List, GST code, and Delivery Address will be applied. If the Customer code is changed, new defaults will be applied to new lines added.
The Invoice Sales Area is updated from the Customer Code when the invoice is created, edited and posted.
Note: If the Customer is changed, defaults will not be applied to existing Lines in the invoice. Accredo attempts to preserve existing pricing. Use the
Reprice
button if you wish to apply new defaults to existing lines.
Type
The Customer Type.
Normal
- customer with credit account.
Prospect
- restricted to Quote documents only.
Cash
- restricted to Cash Sale invoices only.
One-time -
expected to be single invoice and receipt but not a cash sale.
Invoice Totals
Customise
Opens
Customise Fields
, you can customise the fields visible in the totals panel.
Net
The invoice total excluding GST and charges entered on the
Charges tab
. The Exclusive Amount.
Charges
Shows the GST Exclusive total of the charges entered on the
Charges tab
.
GST
The GST total on both the net amount and the charges.
Gross
Total so far, including
Invoice rounding
.
Margin
The percentage margin on the invoice total so far, calculated as
100*(Exclusive Amount - Exclusive Cost) / Exclusive Amount
.
Total Weight
Total weight for the Invoice.
Where
UOM
is
Active
, the Weight for each product is calculated as:
(Product
Weight
* Product
UOM Multiplier
) +
UOM Additional Weight
.
The
UOM Additional Weight
is set in
IC Units of Measure
.
Where UOM is not Active, the Product
Weight * Quantity
for each line is used.
Total Volume
Total volume for the Invoice.
Where
UOM
is
Active
, the Volume for each product is calculated as:
(Product
Volume
* Product
UOM Multiplier
) +
UOM Additional Volume
.
The
UOM Additional Volume
is set in
IC Units of Measure
.
Where UOM is not Active, the Product
Volume * Quantity
for each line is used.
Buttons
Invoice List
(Alt+L)
Opens
Invoice List
and selects the document.
Back Orders
(Alt+B)
Opens
Document Back Orders
, showing back orders for the invoice and Customer.
Number and Save
(Alt+A)
Allocates the next invoice (or credit) number from the automatic sequence and saves the invoice.
Save
Saves the invoice and assigns an ID Number. Saved invoices are available for batch printing, posting to debtors, inventory and Sales Analysis files or for editing.
Cancel
Cancels any changes.
In This Section
Cash Sale
IN Invoices - Header tab
IN Invoices - Lines tab
IN Invoices - Charges tab
IN Invoices - Links tab
IN Invoices - Memos Tab

---

## IN Enter Memos

Source: https://accredo.co.nz/webhelp/INEnterMemos.htm

IN Enter Memos
Navigator > Tasks > Invoicing System >
Enter Memos
Defaults for inserting Memos, Alarms and Reminders are set in
IN Settings - Memos tab
.

---

## IN Find Document By Number

Source: https://accredo.co.nz/webhelp/INFindDocument.htm

IN Find Document By Number
Navigator > Maintain > Invoicing System > Invoice List >
Number
(Alt+N)
Enter a Document Number or Packing Slip Number to find a document.
The Document Number is the IN
Invoice No
, the packing Slip Number is the IN
P/Slip Number
.
To search for a document using the unique Document ID assigned to documents by Accredo, click
Find
(
Ctrl+F
).
See Also
IN Invoice List

---

## IN Find Document By Order No

Source: https://accredo.co.nz/webhelp/FindINByOrderNo.htm

IN Find Document By Order No
Navigator > Maintain > Invoicing System > Invoice List >
Order
(Alt+O)
Enter a Customer Code and Order Number to find a document.
The Order Number is the IN
Order No
.

---

## IN HTML Document Designer Wizard

Source: https://accredo.co.nz/webhelp/INHTMLInvoiceWizard.htm

IN HTML Document Designer Wizard
Navigator >Setup > Invoicing System > Invoice HTML Designer >
Wizard
button
Use the HTML Document Design Wizard to design HTML invoice documents. The Wizard will use selections to generate the HTML Document.

---

## IN Insufficient Query

Source: https://accredo.co.nz/webhelp/INInsufficientQuery.htm

IN Insufficient Query
Navigator > Tasks > Invoicing System > Enter Invoices > Lines tab > Quantity Entered
When there is insufficient stock available to supply the quantity entered, you can select the action to take.
You can set the default selection or turn off this prompt see
IN Settings - General tab
.
Action
Effect
Supply
Supply the entire quantity entered, going into negative stock available.
Available
Supply the available quantity and disregard the balance of the entered quantity.
Note: You can override the default supply behaviour using
MaxBasic
code to change the
InInvoiceData
InsufficientSupply
property.

---

## IN Invoice Designer

Source: https://accredo.co.nz/webhelp/INInvoiceDesigner.htm

IN Invoice Designer
Navigator > Setup > Invoicing System > Invoice Designer
Use the Invoice Designer to design layouts for Invoices, Credits, Quotes and Packing Slips generated from IN. You can design your own invoice documents or open and modify existing invoice document designs. To design an invoice document quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
Packing Slips produced from orders entered in OE can be designed in
OE Packing Slip Designer
.
The IN Invoice Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Usually an Invoice document consists of a:
Header band
showing customer details and invoice number
Repeating Detail band
showing invoice lines, and
Footer band
for totals.
Iterators are available to create sub-sets of records. Bands are selected for the iterators. Iterators iterate through the records associated with the document. You can filter and sort the iterators to control which records are included and in which order. For example, you can filter the Supply iterator to exclude Usage, or you can sort by Bin Code.
One or more Detail, Group Header and Group Footer bands added to the report design can be selected for an iterator.
Name
Iterators determine the records shown in the report. Available Iterators are:
JobDescription
- if the Invoice is linked to a Job, iterates through the description lines of the job.
Supply
- iterates through the invoice lines.
CustomerBackOrder
- iterates through items on back-order for the customer in OE.
InvoiceBackOrder
- iterates through items on back-order for orders related to the invoice.
Shipping
- iterates through the shipping lines for the invoice.
Bank
- iterates through the banking lines for the invoice.
Tracking
- iterates through the tracking detail for the invoice line.
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Invoice Designer in addition to the standard
objects
are:
BankAccount
Fields from the Bank Account record.
BankLine
Fields from the Bank line records.
Branch
Fields from the Branch record.
Contact
Fields from the Customer Contact records. If a Contact has been specified, this object is populated with the information associated with the document. If no Contact is specified, this object is populated with the primary contact information (if specified).
Customer
Fields from the Customer record.
CustomerBackOrder
Fields from the Back-order summary records for the Customer.
DeliveryAddress
Fields from the delivery address records.
InvoiceBackOrder
Summary of items back ordered on orders that this invoice is for.
InvoiceHead
Fields from the Invoice header record.
InvoiceLine
Fields from the Invoice line records.
itBank
Properties of the Bank iterator.
itCustomerBackOrder
Properties of the CustomerBackOrder iterator.
itInvoiceBackOrder
Properties of the InvoiceBackOrder iterator.
itJobDescription
Properties of the JobDescription iterator.
itShipping
Properties of the Shipping iterator.
itBackOrder*
Properties of the BackOrder iterator.
itDescription*
Properties of the JobDescription iterator.
itSupply
Properties of the Supply iterator.
itTracking
Properties of the Tracking iterator.
Job
Fields from the Job (if a JC Invoice).
JobDescription
Fields from the Job description records (if a JC Invoice).
JobTransaction
Fields from the Job transaction records (if a JC Invoice).
OrderHead
Fields from the Order Header record.
OrderLine
Fields from the Order line records.
Product
Fields from the Product specified in the Invoice line.
ProductQty
Fields from the quantity for the Product specified in the Invoice line.
SalePerson
Fields from the SalesPerson record.
Shipper
Fields from the Shipper record.
ShipperLine
Fields from the Shipper line records.
Tracking
Fields from the Tracker record.
Report functions available in addition to the standard
MaxBasic functions
are:
CashInvoice
A Boolean function that returns True if the invoice is printed as part of processing as a cash sale. This function could be useful to allow a message such as "Paid, Thank You" to be printed on cash sale invoices.
ChargeName (charge)
A function that returns the name of the
charge
specified by the parameter charge which must be in the range 1-4.
CopyInvoice
A Boolean function that returns True if
Print as Copy
is selected when reprinting invoices. This allows the words "Copy Only" or similar to be printed on copy invoices.
PackingSlip
A Boolean function that returns True if the invoice is printed as a Packing Slip.
Sample IN Invoices are provided with the Accredo Server Install, and are also available on the Accredo website. Sample IN Invoices include:
INInvoice.pfd
- standard IN Invoice.
INInvoice_NoWrap.pfd
- IN Invoice without word-wrapped narrative lines.
INInvoiceWithInvoiceBackOrders.pfd
- IN Invoice including back orders.
To use documents downloaded from the website, ensure your document designer is the latest version.
In This Section
IN Report Period
IN Tutorial: Add Watermarked Second Page to Invoice

---

## IN Invoice Email Designer

Source: https://accredo.co.nz/webhelp/INInvoiceEmailDesigner.htm

IN Invoice Email Designer
Navigator > Setup > Invoicing System > Invoice Email Designer
You can design your own invoice emails or open and modify an existing invoice email design. To design an invoice email quickly, start with an existing email design and modify it, ensuring you save it with a different file name. Select the default email design in
Document Defaults
.
Use Invoice Email Designs when you
IN Email Invoices
.
HTML Body tab
Enter the email text for HTML Emails. See
HTML Email Editor
.
Plain Text Body tab
Enter the email text for plain text emails.
Preview
(Alt+P)
Display a preview of what the email will look like. A current Invoice must be available.
Load...
(Alt+L)
Load an existing Invoice Email to use for designing different emails.
Save...
(Ctrl+S)
Save the current email as a HTML file. You can reload the file in the designer to refine or create a new email.

---

## IN Invoice HTML Designer

Source: https://accredo.co.nz/webhelp/INHTMLInvoiceDesigner.htm

IN Invoice HTML Designer
Navigator > Setup > Invoicing System > Invoice HTML Designer
In This Section
IN HTML Document Designer Wizard

---

## IN Invoice Labels

Source: https://accredo.co.nz/webhelp/InvoiceLabels.htm

IN Invoice Labels
Navigator > Reports > Invoicing System > Invoice Labels
You can print Invoice labels you have designed previously using
Label Designer
. The Report File Name specifies the file that defines the label design layout. Typically these labels are used to print Customer details for dispatch. See
Document Defaults
.
See also
Report Selections Form
.
Report File Name
The file that defines the invoice labels layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
Label Designer
.
Customer From / To
Select a Customer or a range of Customers to print Invoice labels for.
Type, Post Status Print Status
Select the documents to print labels for. You can filter on the Invoice header, for example, to select an invoice by Invoice number.
Branch
This is useful to print labels for all (or selected) invoices at a branch. (Accredo Saturn Only)
Number of label copies
You can specify the number of copies for each label. For details on how to design labels that print different information on different copies, see the Label Designer.
Start from label
Typically on sheet feed labels, you can start printing at a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.

---

## IN Invoice Line Fields

Source: https://accredo.co.nz/webhelp/INInvoiceLineFields.htm

IN Invoice Line Fields
Navigator > Tasks > Invoicing System > Enter Invoices > Lines Tab >
Zoom
or
Customise Fields
Field Name
Description
Line Type
Select
Product
or
Narrative
.
Auto Kitset
,
Manual Kitset
,
Component
and
Usage
line types are selected from the Product code entered and do not appear in the line type lookup. See
Components
. Job lines do not appear in the line type lookup as they are generated from JC.
Product
Enter product items.
Narrative
Enter extended lines of text, such as a detailed description of a job. Click
Narrative
(F2)
in the
Description
field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Auto Kitset
Followed by a list of components. When posted, the components on the lines following are sold, not the product on the Auto Kitset line.
Component
Lines below an Auto Kitset line. These products are recognised as sold when the invoice is posted.
Manual Kitset
The product is manufactured on the fly from the usage lines below and then sold. If
Supply Whole Manual Kitsets
is selected in
IN Settings
, usage quantities for Manual Kitsets cannot be edited once calculated based on the Kitset quantity. If
Supply Whole Manual Kitsets
is unselected, usage quantities can be edited on the Invoice lines.
Usage
Lines below a Manual Kitset line. When the invoice is posted, these products are used to manufacture the Manual Kitset Product which is recognised as a sale.
Product
The Product code from IC (if IC is installed). Selecting a Product code loads a number of defaults: the Description, Unit, Group and Commission fields are loaded with the values from the Product record.
Description
Defaults to the description of the selected product (can be overwritten). Up to 60 characters are available on the selected line. For
Narrative
lines, for more characters, click
Narrative
(F2)
to open the
Narrative Editor
.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. Only available when
UOM
is
Active
. If the Product has more than one UOM Code, you can select the code to use.
Note: If the quantity is not representable in the selected UOM Code decimals, the UOM Code will default to the Base UOM Code.
UOM Quantity
(
UOM
Active Only)
The quantity of the UOM on the Invoice. If the UOM has a
Multiplier
of more than
1
, the
Quantity
will be calculated as the
UOM Quantity
*
UOM Multiplier
.
Quantity
The quantity of the Product on the invoice.
If
UOM
is
Active:
Quantity
is calculated as the
UOM Quantity
*
UOM Multiplier
.
Quantity
is not shown in the grid by default.
If
UOM
is not Active, the
Quantity
is entered.
Unit
The unit for the product (for example, Each or Doz) usually printed on the invoice. If a UOM Code is entered, shows the UOM Code Description. If no UOM Code exists, this can be entered.
Price
Price per the Discount mode in the
Discount Schedule
. If the Discount Mode is:
Explicit
, displays the Sell Price for the item before a discount, the discount appears in the
Disc%
field.
Implicit
, displays the discounted price. No discount shows in the
Disc%
field.
If using
Special Pricing
, shows the special price according to the rules above.
If
UOM
is
Active
, the Price is not shown in the grid by default.
UOM Selling Price
(
UOM
Active Only)
The UOM Selling Price is calculated as the
Price
*
UOM Multiplier
. This can be overwritten.
Disc %
The discount shown depends on the Discount Mode specified in the
Discount Schedule
. If the Discount Mode is:
Explicit,
shows the discount percentage applied to the extended amount (Quantity x Price).
Implicit,
no discount shown.
If you use
Special Pricing
, shows the total discount according to the rules above.
GST
The GST code for the line. If a GST Override has been specified for the Customer, that will be the default. Otherwise, the GST is the default GST code for the Product, or Sales Group if the line does not have a Product code. It is unusual to need to change this code manually.
Group
The Sales Group the net sale on the line is analysed to when an invoice is generated and posted. If the line does not include a product from IC, type the appropriate Sales Group code or the amount will be analysed to unspecified group code
0000
- to avoid code
0000
, ensure
Allow Unspecified 0000 Sales Analysis Codes
is
clear
in
AR Settings
..
Amount
The extended line amount, calculated as
QuantitySupplied x SellingPrice - EnteredDiscount.
Read-only.
AlternateCode
The alternate code from the product record. Read-only.
Bar Code
The default bar code from the product record. Read-only.
Base UOM Code
(
UOM
Active)
The Base UOM Code for the Product. Only available when
UOM
is
Active
.
Bin Code
Bin  from the product record. Read-only.
BranchCode
The Branch the sale on the line is analysed to when processing the Invoice. (Accredo Saturn Only)
Comm Amount
The amount of commission. Normally calculated from the commission percentage applied to the price or the gross profit on the line, based on the
Commission Basis
. If commission is based on profit, it can be recalculated during Invoice posting (when the latest Cost Price is available).
Comment
Comment for the JC transaction. This field is only available if JC is installed. See
JC Enter Transactions
.
Commission%
Commission percentage applicable to this line. By default it is loaded from the Product record.
Commission Amount Bs
Commission amount in the Base Currency. Read-only.
Complete For WIP
Available when a Job Code is selected for the Invoice or the Line.
Selected
, the transaction will be excluded from WIP calculations when the invoice is posted.
Clear
, the transaction is included in WIP calculations.
Not available for OE sourced lines.
Component code
Component Code from the job record. Read-only.
Cost Centre Code
Cost Centre from the job record. Read-only.
Cost Price
The Cost Price for the Product record. This is determined by the
Valuation Basis
(
Standard
,
Average
or
Latest Cost
) in
IC Settings
. Read-only.
Cost Price BS
Cost price in the Base Currency. Read-only.
Currency Code
Currency code for the invoice. Read-only.
Custom 1 & Custom 2
Use these fields to add information stored with orders to be printed on packing slips and invoices. To change the field names, select Customise on the line grid and change the Display Label.
Date Supplied
Date the product line was supplied.
Dept
The Department the line is analysed to. (Accredo Saturn Only)
Disc
Discount dollar amount can be entered if the Discount Percentage is blank, allows discounts that do not represent an exact percentage.
Disc Bs
Discount dollar amount in the Base Currency. Read-only.
Eff. Sell Price
Effective sell price. Read-only.
Eff. Sell Price Bs
Effective sell price in the Base Currency. Read-only.
EnteredAmountBs
Entered amount in the Base Currency. Read-only.
Excl Amount
Selling Price, excluding GST, less applicable discounts, of all the items in the Invoice line. Read-only.
Exclusive Amount Bs
Exclusive amount in the Base Currency. Read-only.
Exclusive Cost Bs
Exclusive cost price in the Base Currency. Read Only.
Exclusive Discount
Exclusive discount amount. Read-only.
Exclusive Discount Bs
Exclusive discount amount in the Base Currency. Read-only.
Ext Cost
Extended cost value for the line. It is calculated as
QuantitySupplied x CostPrice.
Read-only.
Extended Volume
If UOM is Active, this is calculated as (
Volume
*
UOM Quantity)+UOM Additional Volume
.
If UOM is not Active, this is calculated as the
Volume
*
Quantity.
UOM Additional Volume
is setup in
IC Units of Measure
.
Extended Weight
If UOM is Active, this is calculated as (
Weight
*
UOM Quantity)+UOM Additional Weight
.
If UOM is not Active, this is calculated as the
Weight
*
Quantity.
UOM Additional Weight
is setup in
IC Units of Measure
.
GL Account Code
You can override the GL Account associated with the Sales Group. For example, if you sell a fixed asset you can use a Miscellaneous Sales Group and override the GL Account with the Asset GL code, adding a narration to explain this. If a GL Account code is:
Entered,
Accredo will override the GL Account code mapped from the Analysis code on transfer to the GL.
Not entered
, Accredo will use the default GL Account code mapped from the Analysis code on transfer to the GL.
Group Name
Name of the Sales Group specified in the Group field.
GST Amount
Amount of GST on the line, can be edited if the
GST Code
is
G
(all GST).
See
GST Line Calculations
for calculation details.
GST Amount Bs
GST amount in the Base Currency. Read-only.
JC Actuals
Available when a Job Code is selected for the Invoice or the Line.
Selected
, JC Actuals and related IC Usages will be created for the JC Transaction when the Invoice is posted. If
Allow IN Sourced Invoice Lines
is selected in
JC Settings
,
Complete for WIP
will also be set to
Selected
.
Not available for OE sourced lines.
JC Tran Type
JC transaction type. Read-only.
JCTransaction ID
The unique identifier for the JC transaction, if the line comes from a JC transaction. Read-only.
Job Code
Job code for the line. Not available for OE sourced lines.
Line Break
Used for lines imported from the
Narrative Editor
. Indicates whether to include a line break when invoices are printed.
Line Number
Shows the current line number on the invoice. Read-only.
LineID
Identifier for the line. Read-only.
Line Space
Used for lines imported from the
Narrative Editor
. Indicates whether to include a line space when invoices are printed.
Location
The product supply location, only needed on lines with a Product code. (Accredo Saturn Only)
Margin
The percentage gross margin for the line, calculate as:
100 * (ExclusiveAmount - ExclusiveCost) / ExclusiveAmount)
Read-only. Hint: See Permissions on restricting access to Commissions, Cost and Selling Prices.
Markup (%)
The percentage Markup for the line, calculated as:
Markup = ((SellPrice * (100-Discount%)/100) - CostPrice) * 100 / CostPrice
SellPrice (before discount) = CostPrice * (100 + Markup%) / (100 - Discount%)
Note: If the Sell Price is GST inclusive, the GST is not deducted before the calculation, that is, Markup includes GST.
Hint: See Permissions on restricting access to Commissions, Cost and Selling Prices.
Narration
Type a narration to explain the reason for overriding the GL Account code, for example
Fixed Asset Sale
. This can be customised into the grid.
Order Number
Populated when Invoice lines are obtained from a sales order.
OrderID
Identifier for the order. Read-only.
OrderLineID
Identifier for the order line. Read-only.
P/Slip Number
Packing slip number if the invoice was generated from an Order.
Product Details
Details from the product record. Read-only.
Selling Price Bs
Selling price in the Base Currency.
Serial No
For
Serial No
tracked products if the quantity is 1 or -1 the Serial No may be entered, for other quantities enter Serial Nos in the Tracking tab.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
UOM Cost Price
(
UOM
Active Only)
Calculated as the
Cost Price
*
UOM Multiplier
. Read-only.
UOM Cost Price Bs
(
UOM
Active Only)
The
UOM Cost Price
in the Base Currency. Read-only.
UOM Eff. Sell Price
(
UOM
Active Only)
Calculated as the
Price
*
UOM Multiplier
. Read-only.
UOM Eff. Sell Price Bs
(
UOM
Active Only)
The
UOM Eff. Sell Price
in the Base Currency. Read-only.
UOM Multiplier
(
UOM
Active Only)
The multiplier for the UOM
Unit
, set in
IC Units of Measure
. Read-only.
UOM Selling Price Bs
(
UOM
Active Only)
The
UOM Selling Price
in the Base Currency.
Usage cost
Usage cost. Read-only.
Usage Cost Bs
Usage cost in the base currency. Read-only.
Volume
For Automatic Kitsets, this is the sum of the Volume of the component lines. For other products, this is the Product Volume from the Product record. Read-only.
Weight
For Automatic Kitsets, this is the sum of the Weight of the component lines. For other products, this is the Product Weight from the Product record. Read-only.
Write Off
Available for Credit lines only (i.e. Credit with positive quantity or Invoice with negative quantity).
Selected
, when the Credit is posted a write off IC Adjustment transaction will be posted to adjust the quantity out of stock after the IC Credit transaction which returns the stock.
See Also
IN Invoices - Lines tab

---

## IN Invoice List

Source: https://accredo.co.nz/webhelp/INInvoiceList.htm

IN Invoice List
Navigator > Maintain > Invoicing System > Invoice List
Access Invoices, Credits, Standing invoices and Quotes.
Selections
Customer
Select from the
Lookup
. Click
Show All
(Ctrl+A)
to show all selected documents for all customers.
Period
Select a period to view for:
Period
- Select a single period in the
From
selection.
Year
- Displays documents for the current year.
All Periods
- All document are displayed.
Range of Periods
- Select the
From
and
To
periods to display a range.
Period lookup has a year selection. Press
Ctrl+Up
and
Ctrl+Down
or
Ctrl++
and
Ctrl+-
(numeric keypad) to move through a year at a time. Press
+
or
-
(numeric keypad) to move forward or backward a period.
Default is Range of Periods with From Period set to First Available period for AR or period of first Current Document whichever is earlier, and To Period set to Last Available period for AR.
Document
Select the type of documents to display from:
Invoice
Credit
Quote
Standing Invoice
Current / History
Select to show documents that are:
Current
History
Both Current and History
Display Deleted
Selected,
deleted documents are shown in
History
.
Clear,
(default) deleted documents are not shown.
Sales Area
Sales Person
You can filter the list by selecting a Sales Area or Sales Person.
Category 1 Category 2
You can filter the list by selecting Invoice Categories.
Branch
Department
You can filter the list by selecting a Branch or Department.  (Accredo Saturn Only)
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Invoices
to apply selections, filters and sorts to the list.
The default value is set in
IN Settings Misc tab
.
Select Invoices
(F9)
Apply selections, filters and sorts to the list.
Default ordering for selected records is Period ID, Document ID.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
If you selected Invoice or Standing Invoice, the selected document is inserted. If History or All Documents, choose a document type from the drop-down.
Delete
(F3)
Delete transfers to history, it is not deleted from the files, if unsure, open it first.
Open Details
(F12)
Open document to view and edit details.
Print
(Ctrl+P)
Print a report of the list, or save it as a PDF file to send as an email attachment.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Note: To see whether Documents in the list are Allocated, select the Customise button and select the
Fully Allocated
,
UnallocatedAmount
or
UnallocatedAmountBs
fields.
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Create List View
(Alt+L)
Save the current list state as a
List View
.
Find
(Ctrl+F)
Find
a document using the Document ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Footer
Record Count
The total number of records shown in the list. Click
to refresh the total number.
Number
(Alt+N)
Click to
find
a document by entering a Document Number or Packing Slip Number.
Order
(Alt+O)
Click to
find
a document by entering a Customer Code and their Order Number.
In This Section
IN Find Document By Number
IN Find Document By Order No

---

## IN Invoice Reports - Add Layout

Source: https://accredo.co.nz/webhelp/INInvoiceReports.htm

IN Invoice Reports - Add Layout
Navigator > Reports > Invoicing System > Invoice Reports > Add Layout
Produce a report that lists invoices and other documents. You can select document types, and a
post
and
print
status. The
Current/History
selection allows optimised scanning of the invoice files. An invoice is current if it is not deleted and is unprinted or unposted. An invoice is historic if it is deleted or both printed and posted. Select invoices (and other documents) belonging to a period or period range. Print reports on invoices entered and on the stock allocated on invoices. The layouts available are Invoice Status, Invoice, Allocation and Shipping.
See also
Report Selections Form
.
Layouts
Allocation
Produces reports for stock allocated against invoices that have not been posted. See
Order Allocation Reports
(OE installed).
You can specify ranges of customers and products and the required Post Status. Customise this layout to group by customer or product. To customise and add grouping, place the number
1
in the Group field for
CustomerCode
and
CustomerName
or for
ProductCode
and
Description
. After the report layout has been saved, access the customisation from Options > Customise on the selection form.
Customer Grouping,
Reports on allocated Stock Grouped by Customer. Customer allocation reports are sorted by Customer, then invoice. Allocated quantities and amounts are sub-totalled for each Customer. Grand totals for all allocated quantities and values appear at the end of the report.
Product Grouping,
Reports on allocated Stock Grouped by Product. The Product allocation reports are sorted by Product, then Customer then Invoice. Allocated quantities and amounts are sub-totalled for each Product. Grand totals for all allocated quantities and values appear at the end of the report.
Invoice
Lists invoice header and line information. You can also show the invoice banking line information. You can specify ranges of Customers and / or Products and their Post Status. The
Current/ History
selection is to allow optimised scanning of the invoice files. An invoice is current if it is not deleted and is unprinted or unposted. An invoice is historic if it is deleted or both printed and posted. You can specify the period or a range of periods from which to select invoices.
Invoice Links
This report shows the links associated with invoices for a range of periods.
Invoice Totals
Report on totals (excluding GST and Charges) of Invoices, Credits and Quotes entered but not yet posted to Customers accounts. Separate totals are shown for Entered and Held Open. Held Open invoices can represent work in progress or be invoices entered ahead for future periods. You can use this report at the end of the month before printing statements in AR to check all invoices have been posted.
Picking
Report tracking detail for selected current documents. With selections for range of Customers, Products, Packing Slip No, Invoice No and Bin Codes.
Shipping
Shows the Shipper assigned to each invoice.
Status
Select a
post
and
print
status. Select types of documents, and specific post and print statuses. The
Current/History
selection scans invoice files. An invoice is current if it is not posted and printed. An invoice is historic if it is deleted or printed and posted. Select invoices that belong to a period or period range.

---

## IN Invoices - Charges tab

Source: https://accredo.co.nz/webhelp/INEnterInvoices_Charges.htm

IN Invoices - Charges tab
Navigator > Tasks > Invoicing System > Enter Invoices > Charges tab
The Charges tab also contains the Shipping grid and banking details for cash sales.
Charges
Useful for invoicing amounts you do not want to show against Sales Analysis categories (Sales Area and Sales Person). Charges entered on orders are transferred to the invoice when generated. If back ordered items remain, charges are not transferred to the back order.
Note that charges are not included in the Customer Sales Values calculations.
Description
Charge types,
Charge 1
,
Charge 2
and
Charge 3
, can be changed from Navigator > Setup > Invoicing System >
Charges
.
For example, you can setup one for freight and postage, one for insurance and one for miscellaneous charges. Charges are GST exclusive or inclusive as determined by the Price code for the order.
Charge
Amount of the charge.
GST Code
The GST code is set for the charge from Navigator > Setup > Invoicing System >
Charges
unless this is overridden by a Customer's
GST Override
. You can change the GST code.
Charges Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Hold Amount
Hold Amount
Hold Amount for the invoice. An amount held back as not due for payment on the due date. Payment Terms permission required.
Hold Amount
and
Due Date
can be edited from the AR Transaction or during allocation after posting.
Shipping Grid
Shipper
The code for the Shipper. Shipper details can be added and maintained in
IN Shippers
> Maintain tab, or click
on the Lookup in the
Shipper
field. You can specify a default
Shipper
code for a Delivery Address in
AR Customer
. This can be changed, an alternative shipper can be selected.
If all Shipper lines are for the same Shipper the
Shipper Code
is replicated to the Document header on Save.
Shipper Name
The name of the Shipper.
Reference
General text field. Can be used for information such as the courier tracking number.
Quantity
Quantity of items shipped.
Tracking Address
A tracking address that can be used to store a tracking link.
Web Address
The shipper's web address.
Shipping Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new line.
Move
(Shift+Up) (Shift+ Down)
Move selected lines.
Delete
(F3)
Delete a selected line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Tip: Click
, select
Custom 1
and
Custom 2
to make them visible to record courier details, such as ticket#, weight, and volume. Email addresses can also be customised into the grid.
Visit web site
(Ctrl+W)
Go to the web address for the shipper. Data from the Reference field (for example, courier tracking number) will be copied to the clipboard for pasting into the website.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Banking grid
Details apply when you process an invoice as a cash sale. Banking details can be entered and saved for an invoice for processing as a cash sale. Banking details can be entered and saved for quotes, and these will copy through to the order or invoice when the quote is accepted. Similarly banking details entered and saved with a sales order are copied through to the invoice when it is generated. This allows for recording Credit card payment details at the time the order is placed.
Receipts can have multiple banking types, so can use split tender.
Banking details saved with an invoice will not be posted during batch posting as they need to be processed as a cash sale.
Media
The banking media type, set up in
Banking Media
.
Amount
The amount received for the current media type.
Payer Name
Reference
Particulars
Reference information for the transaction.
Banking Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new line.
Move
(Shift+Up) (Shift+ Down)
Move selected lines.
Delete
(F3)
Delete a selected line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Balance Banking
(Ctrl+=)
Quickly calculate the amount left to pay (if payment is made up of different amounts) or the change to be given (if one or more of the payments are cash). When all other payments have been entered, select the next blank line, select Cash as the Media and click
.
The amount to pay appears as a positive amount. Change will be expressed as a negative amount. You can specify the
Banking media
type. The default Media type from
AR Customer (Banking)
will appear.
Save banking details
(Ctrl+D)
Save the Payer Name, Reference and Particulars details for the current line against the Customer record.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IN Invoices - Header tab

Source: https://accredo.co.nz/webhelp/INEnterInvoices_Header.htm

IN Invoices - Header tab
Navigator > Tasks > Invoicing System > Enter Invoices > Header tab
See also
IN Enter Invoices
.
Invoice Date
Defaults to the last invoice date entered, or the System Date if this is the first invoice for the session. Can be changed, must be within the period range.
Hint: Use the numeric keypad
+
and
-
keys to step the date back and forward.
Origination Date
The date the order was placed. If the invoice was generated from an order, the origination date from the order appears. This is useful for forward ordering and tracking. Not restricted by period.
Delivery Date
Dispatch date, defaults to blank.
Rate Type
Exchange Rate
Defaults from the Customer Code.
If
Use Exchange Rate Table
is selected in
FX Settings
, the Rate is fetched from the
Exchange Rate Table
based on Currency Code, Rate Type and Date.
Click
Fix Exchange Rate
beside the Exchange Rate field to lock the Exchange Rate. When the rate is fixed, the rate cannot be changed on this invoice, and this invoice will be excluded from Revaluations. If not fixed, the rate will be re-fetched from the rate table when Rate type, Currency code or Invoice date are changed, and also when the invoice is posted.
Invoice No/
Credit Invoice No
/
Document No/
Quotation No
Allocated on print or post.
Click the
Number and Save
button to allocate the next number and save.
If
Allow Manual Invoice Numbers
is selected in
IN Settings
, you can allocate a number manually then use the
Manual Invoice
button to change the
Print Status
to
Manual
.
Job
The Job Code for the document, if one exists. When a Job Code is selected, the
Sales Person
,
Price code
,
Discount Code
,
Contact
,
Email Contact
and
Order Number
are changed to the Job defaults. The
Branch
,
Department
and
Location
are changed to the Job defaults (in Accredo Saturn).
The Job can also be displayed on the
Lines tab
, if selected.
To edit the Job, you must select
Allow IN Sourced Invoice Lines
in
JC Settings - Invoicing tab
. The Jobs available to select are controlled by the JC settings and the Document class.
Order Number
Customer Order number. If the customer has
Order No. Required
, an Order No. must be entered before an Invoice can be saved.
The
IN Setting
for
Order No Check
controls when a hint is displayed for repeating a Customer Order No.
Internal Ref
A reference for printing, for example, a reference to the Sales Order number.
Quotation Ref
The Quote Number if the invoice is generated from a quote, can be changed.
P/Slip Number
If
Allow Manual Packing Slip Numbers
is
Selected
in
IN Settings
, you can enter a Packing Slip number. If you use the
Print Packing Slip
button, this number will be allocated.
For Invoices
generated
from an OE Sales Order the Packing slip number from the Source Order. Accumulates (to limit of available space) if there is more than one Generate to the invoice with differing Packing Slip no's, i.e. when orders are consolidated by Order or Customer.
Sales Person
Sales Person
Analysis code. Defaults from the Customer Sales Person code or User
Default Sales Person Code
, can be changed. If no Sales Person code is entered, the default is
0000.
Discount Code
The range of discounts that apply for invoicing. If the Invoice was created from Job Costing (JC), this defaults to the Job Discount Code. If the Invoice was not created from JC, this defaults to the Customer Discount Code. This can be changed.
The Invoice Discount Code overrides the Customer and Job Discount Codes. This can be useful when the Customer and Job have different Discount Codes. See
Discount Schedule
.
Price Code
Defaults to the Price code for the Customer.
If you change the Price Code after Invoice Lines have been entered, the new price code will not be applied to the existing lines. Accredo aims to preserve what has been entered. To apply the new Price Code to the existing lines, select the
Reprice
button.
If Inventory Control is not installed select a Price code for GST exclusive or GST inclusive invoicing, see
Price Lists
.
Warning: The GST basis for
Special Pricing
is based on the Price Code for the invoice. If you use Special Pricing and change the GST basis, this will affect prices and margins.
Basis
Displays the Sell Price GST basis for the
Price Code
. GST Basis is set up in
Price Lists
. This is useful where invoices have been imported for Customers whose Price Code has a different Basis to the invoice imported.
Comment
A comment transferred to the Customer transaction when the Invoice is posted.
Narration
Narration transferred to the Customer transaction when the invoice is posted, and included in detailed transfers to GL.
Post Status
Invoice status can be changed between
Unposted
and
Open
.
Posted
and
Deleted
occur as a result of processing options and cannot change.
Unposted
Not yet posted to AR and IC. Unposted documents can be edited.
Open
An extended version of the Unposted status that prevents the Invoice/Credit from being posted. A warning appears if you try to print an Open Invoice. Open Invoice/Credits are not available to be batch printed/emailed.
Posted
Has been posted to AR and IC, can be viewed and reprinted, not edited.
Deleted
Document has been deleted and moved to history.
Print Status
Read-only, shows the print status of the document.
Unprinted
Document not printed.
Printed
Document printed.
Packing Slip
Applies to Invoices. Printed as a Packing Slip, not as an Invoice.
Manual
Applies to Invoices and Credits. Document has been marked as manually prepared, will not print with an Invoice print run.
View the
Print Log
(requires Read access Permission for Company > Settings).
Contact
A contact for the invoice. Defaults to the Primary Contact for the Customer.
Email Contact
Selected
, emails regarding the document will be sent to the Contact Email Address.
Unselected
, emails regarding the document will be sent to the
Email Document
Address specified for the Customer.
Due Date
If Customer Payment Due unit is
Period
then Due Date is not available.
For other Payment Due units the Payment Due date, defaults from Invoice date based on Customer
Payment Due
terms, and can be changed subject to user Payment Terms permission, may not be earlier than Invoice Date.
Hint: Use the numeric keypad
+
and
-
keys to step the date back and forward.
Discount Date
The Payment Discount date. Defaults from Invoice date based on Customer
Payment Discount Available
terms, can be changed subject to user Payment Terms permission, may not be earlier than Invoice Date.
Payment Discount
is calculated from the Customer
Payment Discount %
and can be shown in the Invoice Totals.
Branch
Department
The Branch and Department codes to apply to all Invoice lines. Defaults from the Customer or User settings. If this is changed, the changes will be applied to all Invoice Lines that have not been manually changed. (Accredo Saturn Only)
Default Location
The Location Code to apply to new Invoice lines. If the Location
Sell From
option in
IC Stock Location
is
Clear
, the Location will be unavailable. If this is changed, the changes will be applied to all Invoice Lines. (Accredo Saturn Only)
Category 1
Category 2
Categories can be added via
Categories
on the Maintain tab, or click
Open Category
(Shift+F12)
beside the Categories. Labels can be replaced in
IN Settings
.
Custom 1
Custom 2
Extra text fields to store information. These fields have no effect on posting unless incorporated by a User defined script. Labels can be replaced in
IN Settings
.
Store Person
IC
Store Person
code. Defaults from the User
Default Store Person Code
, can be changed. If no Store Person code is entered, the default is
0000.
P/Slip Count
For Invoices
generated
from an OE Sales Order the Packing slip count from the Order. Clears if there is more than one Generate to the invoice, i.e. when orders are consolidated by Order or Customer.
Balances
The current aged balances for the Customer account.
Credit Limit
Credit limit for the Customer. If the credit limit has been exceeded, it is shown in red. Depending on
Permissions
, you can override a Credit limit on posting an Invoice.
Delivery Instructions
Select a Delivery Code or enter a delivery address. Defaults from the Customer Code. You can edit the address or select another.
Filter/Sort
- apply a
Filter & Sort
to the list of delivery addresses.  Press
Alt+F2
to sort addresses by alternate code Sort Order.
Save as new delivery address
- opens New Delivery Address with a Set As Default option.
Selected,
the saved delivery address will be the default.
Save delivery address
(Ctrl+D)
- provides a quick way to edit addresses without having to open the Customer form.
Delivery Code
Code for the delivery address. Customers can have several Delivery Addresses.

---

## IN Invoices - Lines tab

Source: https://accredo.co.nz/webhelp/INEnterInvoices_Lines.htm

IN Invoices - Lines tab
Navigator > Tasks > Invoicing System > Enter Invoices > Lines tab
Job Defaults panel (if Job Costing available)
Job Defaults are displayed if
Show Job Defaults on IN Lines
is selected in
JC Settings
. If
Allow IN Sourced Invoice Lines
is selected in
JC Settings
, Job Defaults may be changed, and lines can be added directly to Job Invoices. Lines with a Job code do not allocate or issue stock; they post a Job transaction with invoiced quantity and values only, so they do not add costs for a job.
Job
The default Job code for the Invoice. The Job Code will apply as new lines are inserted.
When a Job Code is selected, the Invoice
Sales Person
,
Price code
,
Discount Code
,
Contact
, and
Email Contact
are changed to the Job defaults. The
Branch
,
Department
and
Location
are changed to the Job defaults (in Accredo Saturn).
The Job code is also displayed on the
Header tab
.
Type
The JC transaction type (Material, Disbursement or Time) that will apply to new lines as they are inserted.
Overridden if the product code selected for the line has
Job defaults
set.
Cost Centre
The Cost Centre that will apply as new lines are inserted.
Overridden if the product code selected for the line has
Job defaults
set.
Component
The Component that will apply as new lines are inserted.
Overridden if the product code selected for the line has
Job defaults
set.
Apply to all
(Ctrl+A)
Applies the selected Job Code, Cost Centre or Component to all Invoice lines.
Invoice lines grid
When entering or editing Invoice lines,
Ctrl+Enter
moves to the start of the next line.
The following fields are shown by default. Zoom to Form view, or select
Customise
(
Alt+F5)
to view all
IN Invoice Line Fields
, including the
GL Account Code
.
Note: When changes are made on the
Header tab
, Accredo attempts to preserve the pricing on existing lines. Changes will be applied to new lines added but not always to existing lines. To make changes to existing lines, select the
Reprice
button.
For Documents created from
JC Job Invoicing
, you must have
permission
for
JC / Tasks / Invoicing
to edit invoice lines.
Grid Fields
Line Type
Select
Product
or
Narrative
.
Auto Kitset
,
Manual Kitset
,
Component
and
Usage
line types are selected from the Product code entered and do not appear in the line type lookup. See
Components
. Job lines do not appear in the line type lookup as they are generated from JC.
Product
Enter product items.
Narrative
Enter extended lines of text, such as a detailed description of a job. Click
Narrative
(F2)
in the Description field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Auto Kitset
Followed by a list of components. When posted, the components on the lines following are sold, not the product on the Auto Kitset line.
Component
Lines below an Auto Kitset line. These products are recognised as sold when the invoice is posted.
Manual Kitset
The product is manufactured on the fly from the usage lines below and then sold. If
Supply Whole Manual Kitsets
is selected in
IN Settings
, usage quantities for Manual Kitsets cannot be edited once calculated based on the Kitset quantity. If
Supply Whole Manual Kitsets
is unselected, usage quantities can be edited on the Invoice lines.
Usage
Lines below a Manual Kitset line. When the invoice is posted, these products are used to manufacture the Manual Kitset Product which is recognised as a sale.
Product
The Product code from IC (if IC is installed). Selecting a Product code loads a number of defaults: the Description, Unit, Group and Commission fields are loaded with the values from the Product record.
You can also enter a Bar code, and the relevant IC Product will be selected.
If you change the Product Code for an OE sourced line, the line will no longer be linked to the OE line.
If
Job defaults
have been set for the Product sets Transaction Type, Cost Centre and Component from the Product.
Description
Defaults to the description of the selected product (can be overwritten). Up to 60 characters are available on the selected line. For
Narrative
lines, for more characters, click
Narrative
(F2)
to open the
Narrative Editor
.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Quantity / UOM Quantity
The quantity supplied on the invoice. When a product is selected, defaults to the
Default Invoice Line Quantity
value specified in
IN Settings
(often
1
).
You can set the default behaviour for insufficient supply in
IN Settings
, and you can select to prompt if
insufficient quantity
is available.
Unit
The unit for the product (for example, Each or Doz) usually printed on the invoice. If a UOM Code is entered, shows the UOM Code Description. If no UOM Code exists, this can be entered.
Price / UOM Selling Price
Price is calculated based on the
Discount mode
in the
Discount Schedule
. If the Discount Mode is:
Explicit,
the Price shows the Sell Price for the item before a discount, and the discount appears in the
Disc%
field.
Implicit,
the Price shows the discounted price (that is, the Sell Price minus the Discount). No discount shows in the
Disc%
field.
If using
Special Pricing
, Price shows the special price according to the rules above.
Note: If prices have changed since the line was saved, the changes will not be reflected. To update prices click
Reprice
.
Disc%
The discount shown depends on the
Discount Mode
specified in the
Discount Schedule
. If the Discount Mode is:
Explicit,
Disc% shows the discount percentage applied to the extended amount (Quantity x Price).
Implicit,
no discount is shown.
If you use
Special Pricing
, Disc% shows the total discount according to the rules above.
Note: For Automatic Kitset products, if any of the component Products have a Discount Code set, the Discount Codes of each of the products will be used. You can manually change these.
GST
The GST code for the line. If the Customer has a
GST Override
set, it will be the default, otherwise the GST code comes from the Product. If there is no Product Code, the GST code will come from the Sales Group. It is unusual to need to change this code manually.
Group
The Sales Group the net sale on the line is analysed to when the invoice is posted. If the line does not include a product from IC, remember to type the appropriate Sales Group code. Failing to do so will result in the amount being analysed to the unspecified Sales Group Code
0000
. To avoid code
0000
being used in error, ensure that
Allow Unspecified 0000 Sales Analysis Codes
is not selected in
AR Settings
. Search for a sales group using the
Accredo Lookups
.
Amount
The extended line amount. You cannot enter in this field; it is calculated as,
QuantitySupplied x SellingPrice - EnteredDiscount.
Complete For WIP
Available when a Job Code is selected for the Invoice or the Line. Not available for OE sourced lines.
Selected
, the transaction will be excluded from WIP calculations when the invoice is posted.
Clear
, the transaction is included in WIP calculations.
JC Actuals
Available when a Job Code is selected for the Invoice or the Line. Not available for OE sourced lines.
Selected
, JC Actuals and related IC Usages will be created for the JC Transaction when the Invoice is posted. Only enabled if
Allow IN Sourced Invoice Lines
is selected in
JC Settings
, and line is IN Sourced, i.e. not generated from Job Invoicing form for an existing JC Transaction.
Complete for WIP
will also be set to
Selected
.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Access grid fields in Form view for each line on the grid. Invoice lines can be entered/edited in the form or on the grid. To view more fields use the scroll buttons or resize the window. See
IN Invoice Line Fields
.
Insert
(F4)
Insert a new line.
Move
(Shift+Up) (Shift+ Down)
Move the selected line.
Delete
(F3)
Delete the selected line.
Drill down
(Shift+F12)
View the source document (only available if the invoice was saved and sourced from another document).
Sort
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved when the invoice is saved.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Prompt for Delete Line On / Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Hide / Show Usages
(Ctrl+H)
Toggle on and off to hide and show usages for Manual Kitsets. The default state is set in
Users, Groups and Roles - Preferences tab
.
Product Quantities
(Ctrl+Q)
Opens
IC Product Quantity
(if IC is Installed) showing quantities to view stock availability and pending stock movements. Allows juggling stock 'on the fly'. Quantities at each location are shown (in Accredo Saturn).
Special Pricing Information
(Ctrl+4)
Opens
SP Price Query
. You can query the results of a rule applied to a line. If a Special Price is applied, the rule reference displays with other information, depending on the Special Pricing script.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Tracking Panel
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the
tracking
detail for the current line.
Stock Levels
Customise
Opens
Customise Fields
, you can customise the fields visible in the stock levels panel.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
In Stk / UOM In Stk
Quantity of the selected product in stock on hand.
Alloc / UOM Alloc
Quantity of the selected product currently allocated to customers.
Avail / UOM Avail
Quantity of the selected product available for sale.
Bk Ord / UOM Bk Ord
Quantity of the selected product on back order for customers.
Ship / UOM Ship
Quantity of the selected product on shipments not yet receipted.
On Ord / UOM On Ord
Quantity of the selected product on order from suppliers.
Note: For
Automatic Kitset
products, the following fields come from the individual components products, not the kitset product, but can be changed:
Discount %
Commission %
Location Code
Branch Code
(Accredo Saturn Only)
Department Code
(Accredo Saturn Only)
JC Transaction Type
Job Code
Component Code
Cost Centre Code
In This Section
IN Invoice Line Fields
IN Insufficient Query
See Also
IN Enter Invoices

---

## IN Invoices - Links tab

Source: https://accredo.co.nz/webhelp/INInvoices_Links.htm

IN Invoices - Links tab
Navigator > Tasks > Invoicing System > Enter Invoices >
Links tab
See
IN Settings > Misc tab
for options to replicate quote links on
Invoice from Quote
.
See
OE Settings > Misc tab
for options to replicate links from order on
Generate Invoice
and to order on
Order from Quote
.

---

## IN Invoices - Memos Tab

Source: https://accredo.co.nz/webhelp/INInvoices_Memos.htm

IN Invoices - Memos Tab
Navigator > Tasks > Invoicing System > Enter Invoices >
Memos tab
See
IN Settings > Misc tab
for options to replicate quote memos on
Invoice from Quote
.
See
OE Settings > Misc tab
for options to replicate memos from order on
Generate Invoice
and to order on
Order from Quote
.

---

## IN Label Designer

Source: https://accredo.co.nz/webhelp/INLabelDesigner.htm

IN Label Designer
Navigator > Setup > Invoicing System >
Label Designer

---

## IN Link List

Source: https://accredo.co.nz/webhelp/INLinkList.htm

IN Link List
Navigator > Maintain > Invoicing System >
Link List

---

## IN Memo Designer

Source: https://accredo.co.nz/webhelp/INMemoDesigner.htm

IN Memo Designer
Navigator > Setup > Invoicing System > IN
Memo Designer

---

## IN Memo List

Source: https://accredo.co.nz/webhelp/INMemoList.htm

IN Memo List
Navigator > Maintain > Invoicing System >
Memo List

---

## IN Memo Reports - Add Layout

Source: https://accredo.co.nz/webhelp/INMemoReports.htm

IN Memo Reports - Add Layout
Navigator > Reports > Invoicing System > Memo Reports > Add Layout
See
Memo Report
.

---

## IN Post Invoices

Source: https://accredo.co.nz/webhelp/INPostInvoices.htm

IN Post Invoices
Navigator > Tasks > Invoicing System > Post Invoices
Post invoices and credits to AR and IC. Invoices can also be posted individually from
Enter Invoices
. Posting applies the invoice details to inventory, debtors and Sales Analysis, so that customer account balances are adjusted in AR, transactions are added, Sales Analysis and GST analysis adjusted, and in IC sales figures are adjusted and transactions posted.
Customer - From / To
Specify a range of Customers. Useful if you need to post invoices for specific Customers.
Date - From / To
Specify a range of date to post invoices between.
Number - From / To
Specify a range of invoice numbers to post invoices between.
Type
Select the type of documents to be posted.
Print Status
Select the print status of the documents to be posted.
Up to Period
Select the final period to post documents to.
Branch
Applies posting to Invoices for a single Branch. (Accredo Saturn Only)
Allow Credit Limit exceeded
Selected,
Invoices exceeding the
Customer
Credit Limit
will be posted. Requires
Control
permission for AR\Customers\CreditLimits.
Clear,
(default) Invoices exceeding the Customer
Credit Limit
will error.
Buttons
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Run
(F9)
Invoices matching the entered criteria will be posted and their status changed to
Posted
. Batch posting invoices posts by Invoice number, those without a number, then by Customer code. An invoice that has not been allocated an Invoice number will be allocated the next available computer generated number during posting. Shows
IN Post Invoices Results
.
Effect of Posting Invoices and Credits
Posting an invoice debits the period balance of the Customer account (or the Bill To account)  with the gross amount of the invoice, updates the Sales Area, Sales Person and Sales Group analysis with the net amounts of the invoice and issues from stock product items on the invoice. Posting a credit does the reverse.
When posting credits individually you may be prompted to allocate the credit against invoices depending on the customers Auto allocate setting.
Stock is allocated immediately an invoice is entered to keep inventory current, but sales, and therefore the closing stock figures (that is, in stock), are not updated until the invoice is posted.
In This Section
IN Post Invoices Results

---

## IN Post Invoices Results

Source: https://accredo.co.nz/webhelp/INPostInvoices_Results.htm

IN Post Invoices Results
Navigator > Tasks > Invoicing System > Post Invoices >
Run
Lists posted invoices and those that did not post due to error. If a Customer Credit limit is exceeded during batch posting, an error message will appear and the invoice will not be posted. Depending on
permissions
, you can override the Credit limit when posting an invoice from the
Enter Invoices
form.
Show All Results, Errors only, or Successes only.
Fields
- most of the fields contain information from the selection form and are read-only.
Display
- show All results, Errors only or Successes only.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open to view details.
Print
(Ctrl+P)
Print a report of the information in the grid.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Totals
Errors
Total number of invoices that were not posted due to errors.
Gross Errors
Total amount of the invoices that were not posted.
Records
Total number of invoices successfully posted.
Gross Success
Total amount of the invoices successfully posted.

---

## IN Print Invoices

Source: https://accredo.co.nz/webhelp/INPrintInvoices.htm

IN Print Invoices
Navigator > Reports > Invoicing System > Print Invoices
Navigator > Reports > Invoicing System > Reprint Invoices
Navigator > Tasks > Invoicing System > Enter Invoices >
Print
(Ctrl+P)
button
Print invoices, credits and standing invoices in a batch, or individually from
Enter Invoices
. Invoices are produced by Invoice number (default), followed by invoices with no Invoice number allocated, then by Customer code. An invoice that has not been allocated an Invoice number will be allocated the next available computer generated number before printing. Invoices that have already been printed can be reprinted.
See also
Report Selections Form
.
Additional selections
Report File Name
The file that defines the invoice layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IN Invoice Designer
.
Customer - From/ To
Select one or a range of customers to print invoices for.
Date - From/ To
Select a range of dates.
Number - From/ To
Select a range of invoice numbers.
Type
Available for the invoice batch printing option. Print Invoices, Credits, Standing Invoices or a combination. Use
Filter & Sort
to select an invoice.
Print Status
For Reprint only:
Printed
- Include previously printed or emailed documents.
Manual
- Include documents flagged as manual.
AdditionsPot Status
Print only unposted invoices, only posted invoices, or all invoices.
Invoices
For Reprint only:
Limit invoices to reprint by period or range. To reprint all unposted documents select
All Periods
.
Print as Copy
For Reprint only:
Selected, Invoices will be marked with "Copy Only".
Up to Period
For Print only:
Limit invoices to reprint by period. Select the final period to select invoices from.
Branch
Select the branch to print invoices for.
Clear
, invoices will be printed for all. (Accredo Saturn Only)
Exclude Email Customers
Selected
, invoices for customers with an email address in the
Invoices
field on the
Contacts
tab, will not be printed.
Additional selections for individual document print to Mail Message
Format
Two additional options are available:
HTML Document
- uses the HTML Document design selected in Email Template to print the document in the email body. A default HTML design may be specified in
IN Settings - Email tab
.
PDF and HTML Document
- uses the HTML Document design selected in Email Template to print the document in the email body, and attaches the invoice printed as a pdf using the Report File Name.
Email Template
The file that defines the email body.
Either an email template file (extension .html) designed using IN Invoice Email Designer. You can set a default email template from Navigator > Setup > Company > Reporting >
Document Defaults
.
Or an HTML Invoice (extension .pfj)  designed using IN Invoice HTML Designer.  A default HTML design may be specified in
IN Settings - Email tab
.
Click
Open In Designer
to open the selected file in the
IN Invoice HTML Designer
.

---

## IN Print Quotes

Source: https://accredo.co.nz/webhelp/INPrintQuotes.htm

IN Print Quotes
Navigator > Reports > Invoicing System > Print Quotes
Print quotes in a batch, or individually from
Enter Invoices
. Quotes are produced by Quotation number.
See also
Report Selections Form
.
Additional selections
Report File Name
The file that defines the quote layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IN Invoice Designer
.
Customer - From / To
Select one or a range of customers to print quotes for.
Date - From/ To
Select a range of dates.
Number - From/ To
Select a range of quote numbers.
Type
Select whether to print previously unprinted and / or printed quotes.
Up to Period
Limit quotes to reprint by period. Select the final period to select quotes from.
Branch
Select the branch to print quotes for.
Clear
, quotes will be printed for all. (Accredo Saturn Only)
Exclude Email Customers
Selected
, quotes for customers with an email address in the
Invoices
field on the
Contacts
tab, will not be printed.

---

## IN Report Period

Source: https://accredo.co.nz/webhelp/INReportDesignerPeriod.htm

IN Report Period
Navigator > Setup > Invoicing System > Statement Designer > View > Reporting Period
Select the period to view data for when you click
Execute Report
(
Ctrl+R
).
Field
Period
Select the Reporting Period to be used when you click
Execute Report
. This defaults to the current period, but you can select a different period if the current period does not have suitable test data.
See Also
IN Invoice Designer

---

## IN Reprice Invoice Results

Source: https://accredo.co.nz/webhelp/INRepriceInvoiceResults.htm

IN Reprice Invoice Results
Navigator > Tasks > Invoicing System > Reprice Invoices >
Run
(F9)
Lists repriced invoices and those that were not processed due to error.
Fields
- most of the fields contain information from the selection form and are read-only.
Display
- show All results, Errors only or Successes only.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open to view details.
Print
(Ctrl+P)
Print a report of the information in the grid.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Totals
Errors
Total number of invoices that were not repriced due to errors.
Gross Errors
Total amount of the invoices that were unprocessed.
Records
Total number of invoices successfully repriced.
Gross Success
Total amount of the invoices successfully repriced.

---

## IN Reprice Invoices

Source: https://accredo.co.nz/webhelp/INRepriceInvoices.htm

IN Reprice Invoices
Navigator > Tasks > Invoicing System > Reprice Invoices
You can update the Cost and Selling prices on unposted and open invoices, credits, Standing invoices and quotes. Discount, GST code, Product description and Sales Group can also be updated. This updates pricing on all, or a selection of invoices at one time. To reprice a single invoice, select it from the Invoice list to access
Enter Invoices
. Customer selection is useful for repricing invoices for specific customers. Product selection is used when repricing applies to certain products. You can choose a document type. Reprice Standing invoices or quotes to bring them up to date. Repricing is not applied to
Automatic Kitset
lines, it is applied to the Component lines that make up the Automatic Kitset.
Customer - From / To
Specify a range of Customers. Useful if you need to reprice orders for specific Customers.
Product - From / To
Used when updated pricing is only applied to some products. Select document types. It is common to reprice Standing-orders to bring them up to date. Repricing is not applied to Automatic Kitset lines, but is applied to all of the Component lines which make up the Automatic Kitset.
Type
Select the type of documents to be repriced.
Update
Specify if the unit Cost Price is to be updated to reflect current costings. This is used when invoices are entered before the Cost Prices of the items are known. Note that Cost Price is updated at the time of posting, unless the line is manually priced. You can specify if the Selling Price is to be updated to reflect current pricing. The Selling Price will not be updated if the price in IC is
zero
.
You can choose a selection of fields. If you use Special Pricing, you must select both Selling Price and Discount to include all Special Pricing rules in repricing.
Re-pricing is not applied to:
Automatic Kitset lines, but is applied to all the Component lines that comprise the Automatic Kitset.
Job lines as those have been priced in JC.
Cost prices are not updated for
Manually Costed
Products.
If you use implicit discounting and repricing results in a zero price,
Special Pricing of zero will be applied unless disallowed under Special Pricing rules.
zero prices in IC will not be applied.
If you select GST code, the GST rates will be loaded and re-applied for each code. This is useful if the rate of GST has changed and you have unprocessed invoices in Accredo. New GST calculations will also be applied if GST basis (Inclusive or Exclusive) has changed for the Price code. This would be unusual, unless the basis had been incorrectly set in the first instance.
Selections default from
IN Settings - Reprice tab
.
Branch
Applies repricing to Invoices for a single Branch. (Accredo Saturn Only)
Run
(F9)
The number of documents repriced is returned at the end of the reprice run and you can print a report of the documents.
IN Reprice Invoice Results
is displayed.
In This Section
IN Reprice Invoice Results

---

## IN Reprint Invoices

Source: https://accredo.co.nz/webhelp/INReprintInvoices.htm

IN Reprint Invoices
Navigator > Reports > Invoicing System >
Reprint Invoices

---

## IN Revalue Foreign Invoices

Source: https://accredo.co.nz/webhelp/INRevalueForeignInvoices.htm

IN Revalue Foreign Invoices
Navigator > Tasks > Invoicing System > Revalue Foreign Invoices
If the Exchange Rates table is in use you can update exchange rates and recalculate base values on unposted invoices where the Exchange rate has not been fixed. Invoices and credits are automatically revalued from the Exchange rates table when posted if the rate has not been fixed.
Type
Select the type of documents to be revalued.
Run
(F9)
Documents matching the selected types will be revalued. Shows
IN Revalue Foreign Invoice Results
.
In This Section
IN Revalue Foreign Invoices Results

---

## IN Revalue Foreign Invoices Results

Source: https://accredo.co.nz/webhelp/INRevalueForeignInvoicesResults.htm

IN Revalue Foreign Invoices Results
Navigator > Tasks > Invoicing System > Revalue Foreign Invoices >
Run
Lists revalued invoices and those that were not processed due to error.
Fields
- most of the fields contain information from the selection form and are read-only.
Display
- show All results, Errors only or Successes only.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open to view details.
Print
(Ctrl+P)
Print a report of the information in the grid.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Totals
Errors
Total number of foreign invoices that were not revalued due to errors.
Records
Total number of foreign invoices successfully revalued.

---

## IN Settings - Display Labels tab

Source: https://accredo.co.nz/webhelp/INSettings_DisplayLabels.htm

IN Settings - Display Labels tab
Navigator > Setup > Invoicing System > Settings > Display Labels tab
Set the display labels for the categories and custom fields.
Name
The name of the custom or category field, and where it is used.
Label
Enter the label you wish to be used for the custom or category field. If no label is entered, the field
Name
will be displayed.

---

## IN Settings - Email tab

Source: https://accredo.co.nz/webhelp/INSettings_Email.htm

IN Settings - Email tab
Navigator > Setup > Invoicing System > Settings > Email tab
See also
IN Settings - General tab
.
Exclude Email Customers from Invoice Printing
Selected
, if you batch print invoices, excludes customers with an
Invoices
email address when printing invoices. Invoices will only be printed for customers with no
Invoices
email address.
Email Documents Preferred
Selected,
when Print is selected from IN Invoice Entry Form, if an email address is available (that is,
Email Contact
is selected and the Contact has an email address, or the Customer has an
Invoices
email address), the
Destination
field will be set to
Mail Message
not Printer.
Email Packing Slips Preferred
Selected,
when
Print Packing Slip
is selected from
IN Enter Invoices
, if a packing slip email address is available, (that is,
Email Contact
is selected and the Contact has an email address, or the Customer has a
Packing Slips
email address), the
Destination
field will be set to
Mail Message
not Printer.
Consolidate Emails On
Select from:
None
- Emails are not consolidated.
Email
- One email will be sent per email address. If there is more than one invoice, each will be a separate attachment.
Customer and Email
- One email will be sent per email address per Customer Code. If there is more than one invoice, each will be a separate attachment.
Consolidate Attachments
Selected,
one attachment containing all invoices will be sent per email.
Default HTML Document
Select the HTML Document design to use when sending a document via Mail Message with Format HTML Document. HTML Document designs have file extension .pfj and are designed using the
Invoice HTML Designer
.

---

## IN Settings - General tab

Source: https://accredo.co.nz/webhelp/INSettings_General.htm

IN Settings - General tab
Navigator > Setup > Invoicing System > Settings > General tab
Maintain control fields and settings to determine the default operation of IN, and set the next computer supplied numbers for invoices, credits, packing slips and quotes. You can also maintain the Invoice Rounding Table, for example, for rounding invoice totals to the nearest 5 or 10 cents. See also
Company Setup
.
Document Numbers
Next Computer Supplied Invoice Number
Set the start of the invoice numbering sequence to be assigned to the invoice and then be incremented. When an invoice is first printed or posted, it is allocated the next number in the sequence (if it does not already have a number). Defaults to blank, and must be set.
Next Computer Supplied Credit Invoice Number
When you start using Accredo, select the start of the Credit numbering sequence to be assigned to the invoice and the be incremented. When a credit is first printed or posted, it will be allocated the next number in this sequence (if it does not have a number). Defaults to blank, and must be set.
Next Packing Slip Number
If you print packing slips from entered invoices (or from orders with OE installed), this sets the first packing slip number that will be assigned to the invoice and be incremented after each is printed. Defaults to blank, and must be set.
Next Quotation Number
Assigned when a quote is saved (if it does not have a number) and incremented ready for the next. When a quote is accepted, the Quote number is transferred to the Quote reference of the invoice. Defaults to blank, and must be set.
Allow Manual Invoice Numbers
Selected
, you can type the Invoice number manually on an invoice, and the Quote number on quotes.
Clear
, the next available number is allocated.
Always Number On Save
Selected,
the next computer generated Invoice number will be assigned immediately on
Save.
Do this if you require an Invoice number before the invoice is printed (to record it elsewhere).
Allow Manual Packing Slip Numbers
Selected,
you can manually type the packing slip number on an invoice.
Clear,
the invoice is given the next available number when a packing slip is printed.
Unique Invoice Numbers Required
Selected
, you cannot save an invoice if the Invoice number is already in use. Usually invoice numbers are unique as they are allocated sequentially. This is useful if using manually generated invoice numbers to ensure they are not duplicated.
Order No Check
All
, (default) status hint "Order number xxx already used" will appear if an Order number is repeated.
Required
, warnings only appear for repeated order numbers for customers with
Order Number Req'd
selected in
AR Customer
.
None
, hint will not appear on repetition of an Order number.
Invoice Lines
Default Line Type
Select the default line type for IN Invoice Lines, from:
Product
Narrative
Default Invoice Line Quantity
The quantity that will appear on an Invoice line when a product is selected. Usually set to
1
for invoicing products, or may be set to
zero.
Default If Insufficient Stock
Determines the default action when entering an invoice if insufficient stock is available.
Value
Meaning
Supply
Supply the entire quantity entered, that is, go into negative stock available.
Available
Supply the available quantity and disregard the balance of the entered quantity.
Note: You can override the default supply behaviour using
MaxBasic
code to change the
InInvoiceData
InsufficientSupply
property.
Prompt If Insufficient Stock
Selected,
you will be prompted for the action to take when entering an invoice if insufficient stock is available. The default action selected above will be preselected.
Clear,
you will not be prompted if insufficient stock is available, the default action specified above will apply and you will be notified that there was insufficient stock.
Supply Whole Manual Kitsets
Selected,
(default), usage quantities for Manual Kitsets cannot be edited once calculated. Generate Invoice from Order does not invoice usages from a Manual Kitset while usages are on back order.
Clear,
usage quantities can be edited on
Invoice lines
. This setting affects OE. You cannot back order Manual Kitsets unless you work with whole kitsets, as the supply can't be determined from the kitset.
Default Write Off on Credit
Selected,
Write Off
will be selected by default on
IN Credit Lines
.
Clear,
(default) Write Off will be clear by default on
IN Credit Lines
.
Discount Mode
Determines how discounted prices are treated on orders and invoices:
Explicit,
the discount appears on the invoice, the price shown is the Selling Price from IC or Special Pricing.
Implicit,
the discount does not appear on the invoice, the Selling Price will be less the discount in
Discount Schedule
or Special Pricing.
Buttons
Edit
(F11)
Enter edit mode.
Save
(F9)
Save changes.
Cancel
(Esc)
Discard changes and close the form.
In This Section
IN Settings - Misc tab
IN Settings - Email tab
IN Settings - Rounding tab
IN Settings - Reprice tab
IN Settings - Display Labels tab
IN Settings - Memos tab
IN Settings - Links tab

---

## IN Settings - Links tab

Source: https://accredo.co.nz/webhelp/INSettings_Links.htm

IN Settings - Links tab
Navigator > Setup > Invoicing System > Settings > Links tab
For each Account you can specify the default Link path within the Links folder. This path will be resolved and used as the default path for the
Link File
dialog and the
AddFileLink
function when adding links for the Account.
Link paths can reference fields in the Account File and the ModuleCode inside <> tags. If PeriodID is a field in the account file PeriodName and PeriodEndDate may also be used inside tags. Date fields in link paths format as YYYYMMDD.
e.g. <ModuleCode>\<CustomerCode>
The Links folder is either under the Accredo System folder or the Accredo Data folder based on your
Company Settings
.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.

---

## IN Settings - Memos tab

Source: https://accredo.co.nz/webhelp/INSettings_Memos.htm

IN Settings - Memos tab
Navigator > Setup > Invoicing System > Settings > Memos tab
For each Account File you can specify the default Memo type.
You can also set an Account File as the default for a
Memo, Alarm or Reminder
.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Set as Default
Set the selected memo as the default for IN memos.

---

## IN Settings - Misc tab

Source: https://accredo.co.nz/webhelp/INSettings_Misc.htm

IN Settings - Misc tab
Navigator > Setup > Invoicing System > Settings > Misc tab
See also
IN Settings - General tab
.
Allow Edit for Posted Invoices
Selected,
posted Invoices can be edited, where the User has permission.
Clear,
posted Invoices cannot be edited.
Allow Customer Change After Print Packing Slip
Selected,
Customer can be changed after a Packing Slip has been printed.
Clear,
Customer cannot be changed after a Packing Slip has been printed.
Note: The Customer cannot be changed after an Invoice has been printed.
Allow Packing Slip Number change After Print
Selected,
Manual Packing Slip Numbers can be changed after packing slips are printed. This only applies if
Allow Manual Packing Slip Numbers
is selected (see above).
Clear,
Packing Slip Numbers cannot be changed after a Packing Slip has been printed.
Allow Jobs on OE Sourced Lines
Available when OE and JC are installed.
Selected,
OE sourced Invoice Lines can contain a JC Job Code, JC Actuals true is enforced for these lines.
Clear,
JC Job Code is not available for OE sourced Invoice Lines.
Auto Select
IN Invoice List
IN Memo List
IN Link List
IN Tracking Log
Selected,
Auto Select for the list is selected by default.
Clear
, Auto Select is unselected for the list. This is recommended where there is a large number of records or the network is slow.
Replicate Links and Memos
Invoice from Quote Links
Invoice from Quote Memos
For Invoices created from Quotes.
Leave
, Memos / Links remain on the original quote, no replication.
Copy,
Memos / Links remain on the original quote, and are copied to the invoice.
Move,
Memos / Links are moved from the original quote to the invoice.
See Also
IN Settings - General tab

---

## IN Settings - Reprice tab

Source: https://accredo.co.nz/webhelp/INSettings_Reprice.htm

IN Settings - Reprice tab
Navigator > Setup > Invoicing System > Settings > Reprice tab
See also
IN Settings - General tab
.
Update
Select fields to be updated by default when IN or OE is repriced. Select from:
Cost Price
Selling Price
Discount
GST Code
Description
Sales Group
Weight and Volume
(applies to Batch Updates only)
Note: If Special Pricing (SP) is installed, both
Selling Price
and
Discount
must be either selected or unselected. You cannot select one of these and not the other.

---

## IN Settings - Rounding tab

Source: https://accredo.co.nz/webhelp/INSettings_Rounding.htm

IN Settings - Rounding tab
Navigator > Setup > Invoicing System > Settings > Rounding tab
Invoice totals may need to be rounded when supplying goods or services for cash, for example, to the nearest five cents. Each invoice is rounded depending on the final digit of the invoice total. Each digit from 1 to 9 can be rounded to another digit from 0 to 10. Note that rounding to 10 rounds up to the next 10 cents. When rounding to the nearest 5 cents, round off (positive or negative) will be analysed to the Rounding
charge
to ensure Sales Analysis always balances.
By default,
Banking Media Rounding
is
Selected
for new companies.
See also
IN Settings - General tab
.
Banking Media Rounding
Selected,
(default) only invoices and orders with rounded
Banking Media code
(for example, CASH) for Banking Lines will be rounded.
Clear,
all invoices and orders will be rounded.
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Restore Defaults
Restore settings to their defaults.

---

## IN Shipper

Source: https://accredo.co.nz/webhelp/INShippers.htm

IN Shipper
Navigator > Maintain > Invoicing System > Shippers
Enter shipping details for delivering orders. Details are available on the Charges tab of
Sales OE
and
Invoice Entry
. Type details in the grid to add, edit and delete shippers.
Grid Fields
Code
A 16 character code that must be unique as it is used to identify the specific record. You will notice that this field is shown in the read-only colour to indicate that it cannot be edited.
Shipper Name
Prints on reports and shows in Lookups.
Web Address
The shipper's web address.
Email Address
The shipper's primary email address. Click
to create a
Mail Message
(Ctrl+M).
Phone Nos
Customer telephone numbers. If Accredo is setup to interface with the
telephone system
, click
to dial.
Note: You can change the labels of the phone no fields in
Company Settings - Display Labels
.
Custom 1 & 2
Extra text fields to store information. These fields have no effect on posting unless incorporated by a User defined script. Labels can be replaced in
IN Settings
.
Inactive
Shippers marked inactive will be hidden from selections, with financial information and history retained for reporting.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zooms to Form view. View the details for the shipper. Shippers can be inserted, edited and deleted.
Insert
(F4)
Type additional shippers.
Delete
(F3)
Delete shippers.
Print
(Ctrl+P)
Print a report of the information in the grid.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IN Tutorial: Add Watermarked Second Page to Invoice

Source: https://accredo.co.nz/webhelp/INTutorialWatermarkedPageInvoice_1.htm

IN Tutorial: Add Watermarked Second Page to Invoice
This tutorial shows you how to add a watermarked second copy of an invoice using the Invoice Designer. The second copy can be marked and used as a Head Office copy.
To open an invoice design, go to Navigator > Setup > Invoicing System > Invoice Designer.
Click
Open
(Ctrl+O)
and select an Invoice Document Design file, such as INInvoice.pfd.
Add a Watermark
To add a band for the watermark, click
Add Band
(F4)
. A band will be inserted at the bottom of the document.
Click the band, the properties for the band will be displayed on the left. Change the
BandType
property from
btDetail
to
btWatermark
. This tells the Designer to print this band as a watermark.
Add a label to the watermark band. Click
Add new label
, then click in the watermark band.
Double-click the label. Type the watermark text, for example,
Office Copy
. Click
Save
(F9)
.
You can rotate the text using the
Angle
property. For example, enter
45
to rotate the label 45Â°.
You can change the font and font size using the
Font
property. For example, to print a large watermark, click
Open Font Dialog
(F2)
on the Font, then change the font
Size
to
72
. You will need to expand the band height, by dragging the band border.
You can also change the font colour using the
Font
property. For example, to print the watermark in a lighter colour, click
Open Font Dialog
(F2)
on the Font, then change the font colour to Silver. Click OK.
Click
Execute Report
(Ctrl+R)
to check the watermark is in the correct place. Adjust the size of the Watermark Band and the position of the Label to display correctly.
Add a Second Page
In the lookup above the Properties, select the Report (the first item in the
Lookup
).
Change the
PartCount
property from
1
to
2
. This tells the designer to print 2 copies of the document.
Click the Watermark Band.
In the
BeforeBand
Property, click (Code)
Open Code Editor
(F2)
. A code window opens.
Type the following code:
If partnumber = 2 Then
self.print=true
Else
self.print = False
End If
This tells the Invoice Designer to only print the Watermark Band if the page is the second copy. Click
Save
(F9)
.
Click
Execute Report
(Ctrl+R)
. Each invoice will print twice, with a watermark on the second copy.
Go to File > Save As, and save the document with a new name to ensure it won't be overwritten when a system update is performed.
See Also
Module Tutorials

---

## income

Source: https://accredo.co.nz/webhelp/90.htm#o5539

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## increment

Source: https://accredo.co.nz/webhelp/90.htm#o5540

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## IndexOf

Source: https://accredo.co.nz/webhelp/SLIndexOf.htm

IndexOf
method IndexOf(Text: String): Number
Available for StringList Objects. Returns the Index of the first item in the list with a value of
Text
.
IndexOf method syntax has these named arguments:
Parameter
Description
Text
Required. The text to return the index number of in the list.
Note: IndexOf is case insensitive.
For example:
dim sl as object
sl = createobject("Accredo.StringList")
sl.add("text")
sl.add("other")
sl.add("text")
print (sl.indexof("text"))
print (sl.indexof("TEXT"))
both print statements will return
0
, as this is the index of first instance of "text" in the list.
See Also
Stringlist Object

---

## IndexOfName

Source: https://accredo.co.nz/webhelp/SLIndexOfName.htm

IndexOfName
method IndexOf(Name: String): Number
Available for StringList Objects. Returns the Index of the first item in the list with a key of
Name
.
IndexOfName method syntax has these named arguments:
Parameter
Description
Name
Required. The key to return the index number of in the list.
For example:
Dim StringList as Object
StringList = CreateObject("Accredo.StringList")
StringList.AddPair("A", "Alpha")
StringList.AddPair("B", "Beta")
StringList.AddPair("G", "Gamma")
StringList.AddPair("Z", "Zeta")
Msgbox(StringList.IndexOfName("g"))
will return
2
, as this is the index of first instance of the key "g" in the list.

---

## Initialisation File

Source: https://accredo.co.nz/webhelp/InitialisationFile.htm

Initialisation File
Accredo installs an initialisation
.ini
file, that has the same name as the Client executable file. For example
AccredoSaturn64.ini
.
The .ini file contains the system path. The Accredo Client executable file compares file dates in the System Path with those in the client path. Older files are overwritten.
The format of the .ini file is:
[Config]
SystemPath=[System Path]
If the update path is different to the system path, it will also contain an update path:
UpdatePath=[Update Path]
Other settings may also be stored in the .ini file.
See Also
Installation Options

---

## input

Source: https://accredo.co.nz/webhelp/90.htm#o5541

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## Input Functions

Source: https://accredo.co.nz/webhelp/InputFunctions.htm

Input Functions
Function
Description
FindCode
Finds nearest code to value.
InputBinCode
Prompt the user for a Bin Code.
(Saturn only.)
InputBoolean
Prompt for a boolean.
InputBox
Prompt for a string.
InputCode
Prompt for a given code.
InputContact
Prompt for a contact from AP or AR.
InputCountry
Prompt for a country.
InputCustomCode
Prompt for a given code from a custom table.
InputDate
Prompt for a date.
InputDeliveryAddress
Prompt for an AR Delivery Address.
InputEnum
Prompt for an enum.
InputFileOpen
Prompt for an existing file.
InputFileSave
Prompt for a file.
InputFolder
Prompt for a folder.
InputInteger
Prompt for an integer.
InputList
Prompt for a value from a list.
InputMemo
Prompts user for a block of text.
InputNumber
Prompt for a number.
InputPeriod
Prompt for a period.
InputPrinter
Prompt for a Printer name.
InputQuery
Prompt for an answer.
InputTime
Prompt for a time.
MsgBox
Display a message.
In This Section
FindCode - MaxBasic Function
InputBinCode - MaxBasic Function
InputBoolean - MaxBasic Function
InputBox - MaxBasic Function
InputCode - MaxBasic Function
InputContact - MaxBasic Function
InputCountry - MaxBasic Function
InputCustomCode - MaxBasic Function
InputDate - MaxBasic Function
InputDeliveryAddress - MaxBasic Function
InputEnum - MaxBasic Function
InputFileOpen - MaxBasic Function
InputFileSave - MaxBasic Function
InputFolder - MaxBasic Function
InputInteger - MaxBasic Function
InputList - MaxBasic Function
InputMemo - MaxBasic Function
InputNumber - MaxBasic Function
InputPeriod - MaxBasic Function
InputPrinter - MaxBasic Function
InputQuery - MaxBasic Function
InputTime - MaxBasic Function
MsgBox - MaxBasic Function
See Also
MaxBasic Functions

---

## InputGrid Object

Source: https://accredo.co.nz/webhelp/InputGridObject.htm

InputGrid Object
Once created by the
ScriptedForm.InputGrid
method, the grid can be further modified by calling its methods. These allow you to control the type of editing controls placed on each field. Fields without an editor are treated as if they were marked as read-only in the dataset used to create the grid. CreateDefaultEditors can be used to create the default editors for each field based on the underlying type of the fields the grid is displaying. The available methods are:
Method
Description
CreateDefaultEditors
Create default editors for each field in the table.
InputBoolean
Define a radio button control for a boolean value.
InputBox
Define a single line text edit control.
InputButton
Define a button that runs a Sub-Statement when clicked.
InputCode
Define a control that allows input of a code.
InputCustomCode
Define a control that allows input of a custom defined code.
InputDate
Define a control that allows input of a date.
InputInteger
Define a control that allows input of an integer.
InputList
Define a combo edit control that allows selection from a set of values.
InputNumber
Define a number edit control that allows input of a number.
InputPeriod
Define a combo control that allows input of a financial period.
In This Section
CreateDefaultEditors - Input Grid Method
InputBoolean - Input Grid Method
InputBox - Input Grid Method
Input Button - Input Grid Method
InputCode - Input Grid Method
InputCustomCode - Input Grid Method
InputDate - Input Grid Method
InputInteger - Input Grid Method
InputList - Input Grid Method
InputNumber - Input Grid Method
InputPeriod - Input Grid Method
See Also
Scripted Forms

---

## Insert

Source: https://accredo.co.nz/webhelp/SLInsert.htm

Insert
method
Insert(Index: Number, Text: String)
Available for StringList Objects. Inserts the string
Text
at position number
Index
.
Insert method syntax has these named arguments:
Parameter
Description
Index
Required. The Index number position to insert the String.
Index is zero-based.
Text
Required. The text to be inserted into the String List.
For example:
strList.Insert(1, "Second")
will insert the string
Second
in the second position in the list.
See Also
Stringlist Object

---

## Insert Links

Source: https://accredo.co.nz/webhelp/MailInsertLinks.htm

Insert Links
Mail Editor > Add Links
Select links to be included as attachments in the Mail Message.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Select
(F4)
Select the highlighted link to be included as an attachment.
Select all
(Shift+F4)
Select all links to be included as attachments.
Unselect
(F3)
Unselect the the highlighted link to be excluded from attachments.
Unselect all
(Shift+F3)
Unselect all links to be excluded from attachments.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Buttons
OK
(F9)
Attach selected links to the Mail Message.
Cancel
(Esc)
Close the Insert Links form without changing attachments.
See Also
Mail Editor

---

## Install Accredo Client

Source: https://accredo.co.nz/webhelp/InstallAccredoClient.htm

Install Accredo Client
Install the Accredo Server on a Network Server before installing the Accredo Client on a workstation or server, see
Install Accredo Server
.
Accredo Client installs the Accredo Client, Online Help, Team Viewer, ODBC driver and User Guide, registers Accredo for COM, and registers the AccredoDB.
Install the Accredo Client on the server, as well as workstations. When updates are installed on the Server, the Accredo executable file checks for updates and copies the new files to the client machine the next time the Accredo Client is opened on the workstation.
The installation creates a shortcut to the
Accredo Client
on the workstation desktop and adds
Accredo Client
to the
Programs
folder of the Windows Start Menu.
When you install Accredo on a workstation for the first time, restart the workstation after installation to activate the Registry changes.
Close all Windows programs.
Download and run the
Saturn Client
or
Mercury
Client
install file from the
Accredo Download Centre
.
Click
Next.
Read the License Statement, click
I accept the agreement
, click
Next.
Click
Next
to accept the default destination folder, which creates an Accredo folder in Program Files, or
Browse
to select another location.
Click
Next
to accept the default Start Menu Folder, or
Browse
to select another folder.
Select to Create a desktop icon, and Register as a COM Server, click
Next.
Click
Install.
When the
Installation Complete
dialog appears, click
Finish.
Restart the workstation if this is a first time installation.

---

## Install Accredo Server

Source: https://accredo.co.nz/webhelp/InstallAccredoServer.htm

Install Accredo Server
Install Accredo Server on a network Server using the install key supplied with the Accredo Installation media.
Only install Accredo Server on one computer (the Network Server). Installation on more than one computer is an infringement of the licensing agreement. When the User License is installed on the Server, other computers on the network can access the Accredo Server.
Accredo Server installs the Accredo Server, Online Help, User Guide, Team Viewer and ODBC driver. The Server Install creates a set of folders used by the system, which must not be deleted. These include templates for new companies.
It is important to install the Server software directly onto the server, not via a workstation. This ensures that necessary registry settings are applied on the server.
Also install and run the Client on the Server, to ensure updates will install. The Accredo .exe file in the server directory should only be used for update purposes.
When you install Accredo on a Server for the first time, restart the Server after installation to activate the registry changes.
Close all Windows programs.
Download and run the
Saturn Server
or
Mercury
Server
install file from the
Accredo Download Centre
.
Click
Next.
Read the License Statement, click
I accept the agreement
, click
Next.
Click
Next
to accept the default location or
Browse
to select another location.
Enter the 20-character installation key: dashes are optional and letters are not case sensitive. Click
Next
. If the message "Invalid install key" appears, ensure the key is typed correctly and retry. A common error is not distinguishing
I
(capital i) from
1
(one).
Click
Next
to accept the default Start Menu Folder or
Browse
to select another folder.
Click
Install
.
When the
Installation Complete
dialog opens, click
Finish.
Restart the Server.

---

## Install OLEDB/ODBC Drivers

Source: https://accredo.co.nz/webhelp/InstallOLEDB_ODBCDrivers.htm

Install OLEDB/ODBC Drivers
To access the Accredo database via OLEDB/ODBC from within other applications such as Microsoft Excel and Access, install the Accredo OLEDB/ODBC drivers. The
Data Interchange
module must be installed in the relevant Accredo database.
Access to Accredo data via OLEDB/ODBC is read only. To write back to the database from another application, use Data Interchange and the Accredo data objects to maintain data integrity.
The OLEDB/ODBC drivers can be 32-bit or 64-bit. The OLEDB/ODBC drivers must be the same bit selection as the client.
To install the Accredo OLEDB/ODBC driver, you can either:
Insert the Accredo Installation Media. If the Accredo Installer does not open, use Windows explorer to browse to the Accredo Installation Media folder, then run the
AutoRun
file. Click
OLEDB/ODBC Driver Install
or
OLEDB/ODBC Driver 64bit Install.
- OR -
From the Accredo website, download the
Accredo OLEDB/ODBC Driver
or
Accredo OLEDB/ODBC Driver (64)
. Run the downloaded file.
Follow the prompts to install the OLEDB/ODBC Driver. The default destination folder is
C:\Program Files\AccredoDB.
See Also
Installation Options

---

## Installation Options

Source: https://accredo.co.nz/webhelp/InstallationOptions.htm

Installation Options
In This Section
Initialisation File
Single Sign On
Command Line Switches
Startup Configuration - System.cfg file
Guarded File
Install OLEDB/ODBC Drivers
Accredo Data Interchange (DI)
Save as .pdf

---

## Installation Troubleshooting

Source: https://accredo.co.nz/webhelp/InstallationTroubleshooting.htm

Installation Troubleshooting
Network is slow
See
Network Considerations
.
The
Install Options
Menu does not automatically open when the Accredo Installation media is inserted.
Open Windows Explorer. Go to the Accredo Installation media folder, then double-click
Autorun
or
Autorun.exe.
After manually selecting
Autorun
the
Install Options
Menu does not appear.
Open Windows Explorer. Go to the Accredo Installation media folder, then select the
Setups
folder. Double-click the relevant
Setup*.exe
file.
I can't see a file or a file extension in Windows Explorer.
In Windows Explorer, go to the View tab.
Set
File name extensions
to
Selected
.
Set
Hidden items
to
Selected
.
There is no USB port on a workstation where I want to install Accredo.
Use another workstation on the network with a USB port, share the USB drive and access the Accredo installation media across the network. Alternatively you can download the install files from the
Accredo website
.
An uninstall procedure was not completed successfully.
Delete program files manually from the workstation or Server. Be careful not to delete data files in sub folders.
Installation was not completed, such as if a workstation crashed, or there was insufficient space, or a power failure occurred.
Note the error messages shown and follow instructions to remedy the error. Repeat the installation. If the installation is not successful, contact Accredo Support or your QSP.
Corrupt Installation Detected
This indicates an issue with the particular workstation. Try to install from another workstation across the network.
The drive or UNC share you selected does not exist or is not accessible. Please select another.
If you are installing Accredo to a network location, you will need to install to a UNC path which you have rights to rather than a mapped drive i.e. \\share\directory. As the installer is elevated to have administrator privileges, it cannot see mapped drives.
See Also
Accredo Installation

---

## integrated

Source: https://accredo.co.nz/webhelp/90.htm#o5542

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## inventories

Source: https://accredo.co.nz/webhelp/90.htm#o5543

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## inventory value

Source: https://accredo.co.nz/webhelp/90.htm#o5544

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## invoice

Source: https://accredo.co.nz/webhelp/90.htm#o5545

Glossary of Terms
abort
Deliberately terminate a job prior to its completion.
access
To store data to, or retrieve data from memory or other storage devices. To locate data, usually in a file.
accounting period
A period of time within a financial year. In most cases a financial year consists of 12 or 13 accounting periods.
accounts payable (creditors ledger)
Amounts companies owe suppliers for goods and services. Listed in the current liabilities section on the statement of financial position.
accounts receivable (debtors ledger)
Amounts customers owe a company from sales of goods or services that the company expects to collect within one year. Listed in the current assets section on the statement of financial position.
accrual accounting
The method of accounting for the income and expenses of a period as they are earned or incurred, independent of the time when cash is received or paid. Accredo Accounts Receivable and Accounts Payable Modules operate on an accruals basis. The opposite of cash accounting.
adjustment period
Financial adjustment periods are optional, only visible to the GL, and occur on the final day of the year. They allow you to separate year end adjustments (e.g. adjustments from your Accountant) from other GL processing and to easily report with or without the adjustments applied. There is no separate end of period update required for the Adjustment period.
administration expenses
The costs of directing and controlling a business, for example, stationery, rent, rates, legal fees, and office salaries.
allocate
To apportion a cost or income against one or more accounts or transactions.
alphanumeric character
The set of characters containing the letters of the alphabet (A-Z), numerals (0-9) and some other symbols. Alphanumeric codes contain a combination of these characters.
annual accounts
The end of year financial statement for a company, made up of a Statement of Financial Performance, Statement of Movements in Equity and Statement of Financial Position.
ANSI
Acronym for the American National Standards Institute. The ANSI Character Set is a set of special characters and codes adopted by the ANSI standards organisation.
API
Application program interface. A set of protocols and tools for building software applications.
application software
Programs written to do specific tasks. Examples are accounting programs such as Accredo, word processing programs, spreadsheets, and database programs.
ASCII
Acronym for American Standard Code for Information Interchange. It refers to the computer representation of a character.
assets
Anything companies own. These things might be physical assets such as buildings, trucks, inventories of products, equipment and cash. They also could be intangible assets such as goodwill, trademarks and patents. Assets are listed as a category on the statement of financial position. See also accounts receivable, current assets, fixed assets, and non-current assets.
available
Able to be clicked (referring to an icon or button) or edited (referring to a field).
backup
The process of creating extra copies of usually compressed files to protect against the loss of data or programs. The files created by this process are also referred to as a backup.
bad debts
Uncollectible accounts receivable.
balance
The difference between the debits and credits in a ledger account.
balance forward
In balance forward accounts, receipts or payments are allocated to the oldest debt. Accredo allows maintenance of balance forward accounts or open item accounts.
balance sheet
A financial statement that reports a company’s assets and the claims against them, liabilities and stockholders’ equity, at a set date noted on the statement. This is also referred to as a statement of financial position. The total value of the asset accounts minus the liability accounts will always equal the total value of the equity accounts.
bank overdraft
A current account that a banker has permitted to be overdrawn, so the customer is in debt to the bank.
bank reconciliation
A procedure or report that explains a difference between the current balance of the bank account and the balance of the statement issued by the bank. The difference is made up of un-presented withdrawals and outstanding deposits.
batch processing
A method where transactions to be processed are first collected into groups (batches), then input into Accredo, as opposed to online processing.
book value
The value of an asset, a liability or a stockholder's equity account. For a fixed asset, this is typically the cost of the asset minus accumulated depreciation. As companies continue to use fixed assets to generate revenue, book values lessen and sometimes ultimately reach zero.
budget
Financial plans showing how the business is expected to perform in the future. The size of variations from budgets are an indication of whether the business is performing to expectation.
bug
A program error.
capital
The owner's equity in a business.
cash accounting
The method of accounting for the income and expenses of a period as they are received or paid in cash. Accredo Cash Book operates on a cash basis. This is the opposite of accrual accounting.
cash book
A record of cash received and cash paid transactions, forming a ledger containing a running balance of the cash banked.
cash flow
Cash Receipts less cash payments for a given accounting period.
character
A number, letter or symbol you can type on the computer.
chart of accounts
A list of accounts in a general ledger, showing all non-financial details of the accounts.
client
A computer that shares the resources of another (server) computer.
client/server network
A type of network where one station is designated the Server, and all others act as terminals or clients.
closing stock
The inventory on hand at the end of an accounting period.
corruption
Information in the computer or data on the disk changed from what it should be, for example, by a power surge, or by bad media handling.
cost of sales
The cost of inventory sold during a period. Equals opening stock plus purchase and cost of goods manufactured minus closing stock.
crash
When a computer program stops functioning properly and stops. Users can often restart the program by first restarting the computer.
credit note (credit)
A document issued by the seller to the buyer noting the amount repayable to the buyer for goods returned or overcharged.
creditor
A person to whom money is owed.
current account
An account that transactions between two parties are recorded in, for example, a customer's cheque account with a bank.
current assets
Assets a company can convert to cash within one year. Examples are accounts receivable and inventories of products to sell. These are listed in the assets category on the statement of financial position. See also accounts receivable, assets, fixed assets.
current liabilities
Obligations a company has to others, such as creditors, suppliers and tax authorities, payable within one year. Listed in the liabilities category on the statement of financial position. See also accounts payable, debt, income taxes.
cursor
A small flashing bar showing the current position in a user interface, where the next typed character will be displayed. It can also indicate that the computer is requesting input from the operator.
debtor
A Company or person who owes money to the business.
default
A value pre-selected by the computer before the operator enters information. Default values can often be changed by over-typing or selecting another option.
deposit
A credit transaction; a transaction appearing in the credit/deposit field of the bank statement.
depreciation
An allowance for wear or age made to the value of a fixed asset, allocating its cost over its estimated useful life. It is listed in the assets category on the statement of financial position. See also book value.
directory
The directory acts as a table of contents for a disk. For each file saved on a disk, the directory stores the name, address, size, date and time of creation.
document definition file
A template used for creating standard documents such as invoices, cheques or statements. A set of standard document definition files are provided with Accredo, or you can create new ones using an Accredo document or label designer.
double entry book keeping
A method of recording transactions in terms of a balance of debits and credits. This is based on the equation that liabilities plus owner equity equals assets.
drawings
Cash withdrawn or payments made on behalf of the proprietor or partner in a business. Drawings are not an expense but a direct deduction from the owner's equity.
edit
To change, add or delete data.
error message
A message that indicates a mistake.
expenses
Costs such as salaries, rent, office supplies, advertising and taxes. These are listed in the operating expenses category on the statement of earnings.
export
To take the data from one application and move it to another application, or to a file that another application can read.
field
A unit of information, for example, a name, a date, or an account balance.
file
A collection of records, for example, in Accredo the collection of all customer records forms the customer file.
file name
The name of a file used to identify and reference it on the disk.
fixed assets
Anything companies use for more than one year to manufacture, display, store and transport products. These are also called "Property, plant and equipment". These are listed after current assets in the assets category on the statement of financial position.
formatting
Preparing a digital storage media for a computer to be able to read to or write from it.
function keys
Specially marked keys on the keyboard usually prefixed with the letter F, such as F1.
general ledger
The summary account where records of other accounts are shown to create reports that give a complete picture of the business' finances.
gross margin
The difference between an item's cost and its selling price. The percentage margin is the relationship between the gross margin and the item's selling price. Gross margin and percentage margin are indications of profitable products.
gross profit
The difference between a company’s total sales and its cost of sales. This is listed as a category on the statement of earnings. It is also called gross income.
hard copy
A printed copy of a document on paper, as opposed to being read on a screen.
hardware
All the computer equipment that can be seen and touched, for example, the computer, monitor, disk drive, and printer.
income
Revenue generated by supply of goods and services by the business.
increment
In coding, to increase the value of a variable, usually by one.
input
Data supplied to a computer.
integrated
When an accounting package is said to be integrated, data generated in one area that is needed in another area is posted to the other area. This eliminates needless re-keying of the same data to different areas. Accredo is an integrated package, for example, data entered in IN is posted to AR, IC, and finally to the GL.
inventories
All goods and materials available for sale (in the case of wholesalers, retailers and distributors) or raw materials and supplies, work in process and finished goods (in the case of manufacturers). These are listed in the current assets section on the statement of financial position.
inventory value
Inventory can be valued based on the Average Cost, Latest Cost or Standard Cost of each item in stock.
invoice
A document sent by a seller to a buyer showing details of goods traded.
journal entry
Record of a transaction with details as to which accounts are to be Debited and Credited.
ledger
A systematic collection of individual accounts, see
general ledger
and
subsidiary ledger
in this Glossary.
ledger date
The last day of an accounting period. This date is printed on Financial Reports for the period.
liabilities
A company’s debts to a lender, a supplier of goods and services, a tax authority, a landlord and others. This is listed as a category on the statement of financial position.
local area network (LAN)
A communications system connecting computers and peripherals together to form an integrated system able to share resources and information. A LAN usually spans a limited area such as an office block.
lock
A network facility that allows records and files to be protected during use from corruption or changes by other users.
locked down
Referring to a button or icon to indicate that the related function (for example, Memos & Alarms or Filter & Sort) is in use.
log on
To start a session on a computer terminal by using a command and usually a password, for example you can log on to Accredo.
long term liability
Liability due for payment more than twelve months away.
macro
A set of commands that are executed by a single command or keystroke, see
Scripting
.
maintaining files
Keeping files up to date. Generally this includes adding, editing and deleting records.
margin and markup calculation
The calculations for Margin and Markup and how they relate.
Profit = Sell - Cost
Margin = Profit / Sell * 100
Markup = Profit / Cost * 100
Markup = Margin / (100 - Margin) * 100
Sell = Cost + (Cost * Markup) / 100
Sell = Cost / ((100 - Margin) / 100)
matrix
A layout of data in rows and columns, where each item can be identified by its row and column numbers.
media
Material that computer data is recorded on, for example, disks, tapes or CDs.
memory
The part of a computer that stores data and programs. The memory in a computer consists of random access memory (RAM) and read-only memory (ROM).
menu
A list of available options shown on a screen to guide a user around a program.
modal window
A modal window is a window subordinate to the main open window, that creates a mode where the main window cannot be used. The modal window must be closed before the user can return to the main window.
month to date (MTD)
The period from the date of the last month end update to the present processing date, within the Current Period. MTD and PTD (period to date) are used interchangeably in Accredo as Accredo is usually used on a monthly basis.
multi-tasking
The apparent capacity of a computer to perform more than one task at a time.
multi-user
Multi-user software means that more than one user can access files at the same time. Accredo is made multi-user through very careful design considerations, that lock minimal parts of Accredo that are critical to one user's needs to prevent another user conflicting with those needs, but allow access to all other functions. Accredo software is fully multi-user.
net profit
A company’s total revenue less total expenses, showing what a company earned (or if lost, called net loss) for a set period, usually one year. Listed often literally as the "bottom line" on the statement of earnings. Also called net earnings and net income.
network
A network consists of a number of computers linked together to allow sharing of resources such as printers and disks. Within a network there will be one or more file servers that contain files accessible by other computers on the network.
numeric character
A number.
numeric keypad
A set of numbered keys grouped together usually on the right of the keyboard.
ODBC
Open Database Connectivity. A software protocol that allows exchange of data between different databases. The Data Interchange module must be installed to use this in Accredo.
OEM
Acronym for Original Equipment Manufacturer. The OEM Character Set is the character set of the original IBM PC, or MS DOS.
OLEDB
Object Linking and Embedding Database. An API that allows accessing data from different sources in a uniform manner. The Data Interchange module must be installed to use this in Accredo.
online processing
A method of data processing where data is processed at the time of entry, as opposed to batch processing.
opening entries
The journal entries necessary to record the initial assets, liabilities and owner's equity on the formation of an accounting entity.
operator
A function shown by a symbol, to apply to data. In Accredo, operators are used in Filter & Sorts to define the way search criteria must be met. Examples of operators include:
= (equal to)
> (greater than)
* (containing)
overwrite
To write data over the top of existing data, thereby replacing the original data.
owner's equity
The money owed by a business to the owner. Calculated by subtracting the book value of the liabilities form the book value of the assets. Also called net assets, net worth or shareholders' equity. There are two main areas:
Capital -
The money invested in the business by the owner.
Profits -
The money earned by the business but not taken by the owner.
password
A security code for accessing a computer system.
peer to peer
A type of network where any workstation can be both a server and a client at the same time, without a client-server infrastructure.
period to date (PTD)
Period from the last end of Period to the present processing date in the current Period. PTD and MTD (month to date) are used interchangeably in Accredo as it is assumed Accredo is usually used on a monthly basis.
piracy
Illegally copying a computer program.
posting
The process of transferring information to a transaction in a ledger. For example, posting an Invoice in Accredo creates a transaction in the Accounts Receivable ledger.
profit and loss
The statement of income, expenses, gains and losses, showing the results of the business' operations in a period.
prompt
A request from a software application for information to be supplied by the user.
read
The action of retrieving stored data.
receipt
Written acknowledgement of having received an amount of money or goods.
reconciliation
Comparing two sets of figures from different sources. For example, in Accredo a bank reconciliation compares records of bank transactions against a bank statement to ensure both records are in agreement.
record
A group of one or more related fields. For example, the fields representing a customer's name, address, account balances, and other fields are grouped into a record called the Customer record.
remittance advice
A document sent with a payment to a creditor, showing what the payment is for.
residual value
The amount a company expects to be able to sell (trade-in or scrap) a fixed asset for at the end of its useful life. Also known as salvage value.
restore
The process of reverting to information saved previously in a backup.
retained earnings
The total amount of a company’s net earnings since its inception, minus any payments made to stockholders. Retained earnings is part of the stockholders’ equity, and represents the portion of a company’s assets that are financed from profitable operations rather than from selling stock to investors or borrowing from external sources. This is listed on the statement of financial position.
scrolling
The process of moving a window or image on screen that takes up more than its allocated space.
search
To question a document, file, database or disk to find a specific record or piece of information.
server
A computer that contains files and resources that can be accessed by other computers. A dedicated server can only be used to share files and resources, whereas a non-dedicated server can also be used as a computer in its own right.
SMTP
Simple Mail Transfer Protocol. An Internet standard for email transmission, providing a fast way of sending emails.
spreadsheet
A program that manipulates tables of data over a number of rows or columns.
statement
A written summary of transactions during a period. For example, A debtor's statement usually summarises one month's transactions and shows the balance due for payment.
stock
Another term for
inventory
.
stock on hand
The stock held for resale. Also referred to as inventory on hand.
subassembly
Collection of products used together as a unit, to be then used as a component in another product.
subsidiary ledger
A ledger containing the individual accounts for a set of assets or liabilities, for example, the debtors ledger and creditors ledger. The total for the subsidiary ledger is represented in a control account in the GL, for example, the sundry debtors and sundry creditors accounts.
toggle
To switch from one state to another. For example, a checkbox allows you to toggle from selected to clear.
trading account
The part of an income statement showing the gross profit arising from trading (sales less cost of goods sold).
trial balance
A listing of the accounts in the GL and the totals of their respective debit and credit balances.
unavailable
Not able to be clicked (referring to an icon or button) or edited (referring to a field), and is often shown in grey. This can be because:
you are in View mode, see Edit & View modes
the data in the field cannot be edited (for example, permanent information, such as codes)
you do not have one or more required Accredo Modules installed
you do not have access, see
Users, Groups and Roles - Permissions tab
the function you are trying to access is not available
unicode
A computing industry standard for consistent representation of text.
unreconciled
An unreconciled transaction is one that is entered into the cash book but has not yet appeared on the bank statement.
update
To modify existing information in a file or program with more current information.
upgrade
To modify existing resources or programs to an enhanced version.
user
A person who operates application software.
user defined
Fields that the user can set to suit the needs of the business. For example, the Accredo invoice headings and a number of Accredo reports are user defined.
UTC
UTC (Coordinated Universal Time) is the 24-hour global time standard commonly used to determine local times around the world. Every time zone is defined by its difference from UTC, known as its UTC timezone offset.
variance
The difference, for example, between the actual and budgeted expenses or income.
verify
To confirm accuracy, for example, the process of checking a backup to ensure it is readable.
wide area network (WAN)
A communications system connecting an assortment of computers and peripherals together to form an integrated system, able to share resources and information. A WAN can cover an unlimited area, including offices in different parts of a country, or in more than one country.
withdrawal
A debit transaction that appears in the Debit/Withdrawal field of the bank statement.
write
The process of storing information in memory devices such as RAM or disks.
year to date (YTD)
The period from the date of the last year-end update to the present processing date within the current year.

---

## Invoicing System

Source: https://accredo.co.nz/webhelp/InvoicingSystem.htm

Invoicing System
The Invoicing System (IN) requires Accounts Receivable (AR) to be installed. Invoices can be printed and posted to update the Debtors account and for Sales analysis. Before posting, invoices can be edited. Stock figures in Inventory Control (IC) are updated when stock is allocated against an invoice, and when they are posted to AR. You can:
Enter sales invoices using AR Customer codes and IC Product codes.
Print packing-slips from invoices.
Use Standing invoices to generate repeat invoices.
Generate invoices from Order Entry (OE).
Print quotes and generate them as invoices.
Retain an invoice history for query, reprinting invoices, printing packing-slips and Sales Analysis.

---

## Invoicing System - Maintain

Source: https://accredo.co.nz/webhelp/InvoicingSystem_Maintain.htm

Invoicing System - Maintain
Navigator > Maintain > Invoicing System
In This Section
IN Invoice List
IN Shipper
IN Categories
IN Memo List
IN Link List

---

## Invoicing System - Reports

Source: https://accredo.co.nz/webhelp/INReports.htm

Invoicing System - Reports
Navigator > Reports > Invoicing System
Reports are grouped on the Navigator, you can print labels from invoices, and obtain:
An Invoice Status Report (summary of current and / or historic invoices and quotes, showing print and processing status)
Allocation Reports (stock allocated on invoices by customer or product)
Invoice Totals Report (totals for unposted and held open invoices, credits and quotes)
In This Section
IN Invoice Reports - Add Layout
IN Memo Reports - Add Layout
IN Print Invoices
IN Print Quotes
IN Reprint Invoices
IN Email Invoices
IN Email Printed Invoices
IN Invoice Labels

---

## Invoicing System - Setup

Source: https://accredo.co.nz/webhelp/InvoicingSystem_Setup.htm

Invoicing System - Setup
Navigator > Setup > Invoicing System
In This Section
IN Settings - General tab
IN Change Tracking Log
IN Charges
IN Invoice Designer
IN Invoice HTML Designer
IN Label Designer
IN Memo Designer
IN Invoice Email Designer

---

## Invoicing System - Tasks

Source: https://accredo.co.nz/webhelp/InvoicingSystem_Tasks.htm

Invoicing System - Tasks
Navigator > Tasks > Invoicing System
In This Section
IN Enter Invoices
IN Enter Memos
IN Reprice Invoices
IN Post Invoices
IN Revalue Foreign Invoices

---

## JC Select Invoice

Source: https://accredo.co.nz/webhelp/JCSelectInvoice.htm

JC Select Invoice
Navigator > Tasks > Job Costing > Job Invoicing > Generate Invoice
JC Select Invoice opens if there are saved unposted invoices (or credits) in the period selected that can be appended to, this is determined by
JC Settings - Invoicing tab
,
Jobs Allowed Per Invoice
field. You can append to an existing invoice or create a new invoice. If you have omitted a transaction from a Job Invoice, you can generate again, appending to the existing invoice.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens the selected invoice, you can view details before adding to the invoice.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Buttons
Select
(F9)
Append generated lines to the selected invoice.
New Invoice
(F4)
Generate a new invoice.

---

## JC Transaction Invoice Query

Source: https://accredo.co.nz/webhelp/JCShowInvoices.htm

JC Transaction Invoice Query
Navigator > Maintain > Job Costing > Jobs > Transactions tab >
Show Invoices
(
Ctrl+S
)
Displays the Invoices for the selected transaction.
Grid toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open the selected invoice in
IN Invoices
. You can edit the Invoice details.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
See Also
JC Job - Transactions tab

---

## OE Generate Invoices

Source: https://accredo.co.nz/webhelp/OEGenerateInvoices.htm

OE Generate Invoices
Navigator > Tasks > Order Entry > Generate Invoices
You can batch generate invoices for available stock from orders with packing slips printed, or for available stock from all orders. When you generate, the invoice date and period must be selected. Invoices are generated with status
Unposted
and
Unprinted
print status.
Invoice lines are created for all supplied quantities on the order and for narrative lines. Sticky narrative lines are copied to the invoice if the lines they are attached to are copied. Charges entered in the Order footer are entered in the Invoice footer.
If you enter an Order line and do not enter a supplied or back ordered quantity, the line will be transferred to the invoice on generate. If you do not want the lines to show, delete them.
Note: Net negative value supplies will generate as a credit.
A number of
OE Settings
control Generate Invoice behavior.
Once the invoice has been generated,
For orders which are fully supplied the Order status will change to
Processed
. Depending on the Order Completion setting it may also transfer to history.
For orders that have back-order quantities, if
Order Generation Basis
is
Packing Slip
, a Packing Slip document is created, status Processed to record the information generated to the invoice. The Order remains
Unprocessed
and quantities supplied are added to quantities invoiced, and cleared. Packing slip count is incremented and packing slip number is retained or cleared per the
Retain Packing Slip No On Generate
setting.
For orders that have back-order quantities, if
Order Generation Basis
is
Back Order
,  the Order status will change to
Processed
. Depending on the Order Completion setting it may also transfer to history. A new Back Order document is created. The back-order has the same Order number and date as the original order, status
Unprocessed
and
Unprinted
print status, packing slip count is incremented and packing slip number is retained or cleared per the
Retain Packing Slip No On Generate
setting.
OE Generate Invoices Results
opens when invoices are generated.
Customer - From / To
Select a customer or range of customers.
Print Status
Select orders to Generate with by
Print Status
. Usually orders have packing slips printed to allow invoices to be generated for dispatched orders only.
Unprinted
Order has not been printed.
Printed
Order has been printed as a Packing Slip or Print Status set to Manual.
Confirmed
Order has been printed as a Confirmation and not printed as a Packing Slip.
Posting Period
Posting Date
Date the invoice will be posted. System Period and date (default). You can change to the period and date required for the generated invoices, must be within the date range for the period.
Generate for
Determine orders and lines to be included. Set defaults from Navigator > Setup > Order Entry >
Settings - General tab
.
Full Orders
Generate when items for the order can be supplied in full.
Full Lines
Generate an invoice line only if the line can be supplied in full. An invoice is generated only if at least one line can be supplied in full.
All Lines
Include all orders and order lines, whether or not the line can be supplied in full. An Invoice is generated if at least one line can be partially supplied.
Generate Invoices per
Packing Slip
,
new invoice for each source document.
Order
,
add to an Unprinted and Unposted or Held Open invoice with the same Source Order ID if found (prompt when generating from the OE Sales Order Entry form).
Customer
,
add to an Unprinted and Unposted or Held Open invoice for the same Customer if found (prompt when generating from the OE Sales Order Entry form).
See
OE Generate Invoices Per Order or Customer
for restrictions on generating invoices.
Up To Period
Generate orders up to or prior to the period selected, usually to avoid generating invoices for future (or forward) orders.
Branch
Branch code to generate invoices for a single branch, a selection on the order not the Order lines. You can apply a
Filter & Sort
to generate invoices for specific orders.  (Accredo Saturn Only)
Use Order Date On Future Orders
Date and period when generating invoices from Sales Orders, when the Order Date and Period entered are in the future relative to the Current AR period.
Selected,
invoice date and period will be the Order date and period from
OE Enter Sales Orders
.
Clear
, default invoice date and period for the invoices will be the Posting Period and Posting Date, or if no date and period selected, the
System Date and Period
.
In This Section
OE Generate Invoices Results
See Also
Order Entry - Tasks

---

## OE Generate Invoices Results

Source: https://accredo.co.nz/webhelp/OEGenerateInvoicesResults.htm

OE Generate Invoices Results
Navigator > Tasks > Order Entry > Generate Invoices >
Run
(F9)
Lists orders that invoices were generated for and those that could not be generated due to error. If a Customer's Credit limit is exceeded during batch processing, an error message will appear and the invoice will not be processed. You can override the Credit limit when generating from an order, but not during batch processing. See
permissions
.
Fields
- most of the fields contain information from the selection form and are read-only.
Display
- show All results, Errors only or Successes only.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open to view details.
Drill down
(Shift+F12)
View the source document. You can also double-click a line to open the document.
Print
(Ctrl+P)
Print a report of the information in the grid.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Totals
Errors
Total number of invoices that were not generated due to errors.
Gross Errors
Total amount of the invoices that were not generated.
Records
Total number of invoices successfully generated.
Gross Success
Total amount of the invoices successfully generated.
Invoices
(Alt+I)
Print generated invoices.
Invoices
(Alt+V)
Email the generated invoices. Open
IN Email Invoices
.
Close
(
Esc
)
Close the form.

---

## OE Select Invoice

Source: https://accredo.co.nz/webhelp/OESelectInvoice.htm

OE Select Invoice
Navigator > Tasks > Order Entry > Enter Sales Orders > Generate Invoice
If you are generating invoices per customer or order, OE Select Invoice opens if there are saved unposted invoices that can be appended to. This is determined by
OE Settings
for
Generate Invoices Per
. See
OE Generate Invoices Per Order or Customer
for restrictions on generating invoices.
You can append to an existing invoice or create a new invoice.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens the selected invoice, you can view details before adding to the invoice.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Buttons
Select
(F9)
Append generated lines to the selected invoice.
New Invoice
(F4)
Generate a new invoice.

---

## Script to Add Narrative Lines to an Invoice

Source: https://accredo.co.nz/webhelp/ScriptToAddNarrativeLinesToInvoice.htm

Script to Add Narrative Lines to an Invoice
This example shows you another way to record, save and play a basic script. This example also introduces you to error trapping. The script in this example will add two narrative lines to an invoice.
Run the
NewInvoice.pfs
script created previously, you can use your shortcut to do so. The IN Enter Invoices form will open. Go to the
Lines
tab.
Click
Record
(
ALT+F1).
Add the following narrative lines to the invoice:
These goods remain the property of ABC.
Holdings Limited until payment is received in full.
Note: The pop-up Narrative Editor (activated by clicking
Open Narrative Editor
in the Description field) is not supported by scripting, so cannot be used here.
Move the cursor from the
Description
field to another field.
Note: Any spelling mistakes you fix as you go are not recorded. Field entries are recorded after you move off the field, so don't end recording till you move past the last narrative description.
Click
Record
(
Alt+F1)
to turn off the script recorder.
Result:
Script Editor opens and displays what it has recorded:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
frmINInvoice1.Line.Append
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.Line.Description = "These goods remain the property of ABC"
frmINInvoice1.Line.Append
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.Line.Description = "Holdings Limited until payment is received in full"
Look at what the recorder has done to trap errors. The following part of the code means that an error message will be produced if the IN Invoice Entry form is not open when the script is run:
If IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
Save the script with the name
InvoicePropertyStatement.pfs
.
Run the script.
Result:
The script should add another two narrative lines to your invoice.
Now select a Customer, then save the invoice. Try running the script again.
Result:
You should receive an Error message because you are not in Edit mode.
To modify the script in Edit mode:
Open Script Editor (select Accredo > Script > Script Editor or double-click
Record
(
Alt+F1)
), and load the script.
Insert
frmINInvoice1.Edit
before the first instance of
frmINInvoice1.Line.Append
. The script will look like this:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
frmINInvoice1.Edit
frmINInvoice1.Line.Append
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.Line.Description = "These goods remain the property of ABC"
frmINInvoice1.Line.Append
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.Line.Description = "Holdings Limited until payment is received in full"
Run the script. Running from Script Editor ignores the Script Editor as the active object.
Result:
Accredo should move you into Edit mode (if it can) and append the lines. It doesn't matter if you are already in Edit mode.
Now try running the script with a non editable invoice (one which is posted).
Result:
You should receive an Error message again because the invoice cannot be edited. At this point, you could add another step to the code to select if the invoice is editable and provide a simple error message (rather than the cryptic one displayed) if it isn't. However, this is not essential as the current Error message ensures no damage can be done.
Save the Script.

---

## Script to Change Invoice Lines

Source: https://accredo.co.nz/webhelp/ScriptToChangeInvoiceLines.htm

Script to Change Invoice Lines
This example shows you how to edit invoice lines, giving quantity break pricing. We will also introduce data level scripting and use the
Do ... Loop
statement on invoice lines. We'll use a pretty simple rule for the script. If the quantity is:
Greater than 30 the customer gets Selling price 1 (Wholesale).
Between 15 and 29 the customer gets Selling price 2 (Trade).
Less than 15 the customer gets Selling Price 3 (Retail).
We'll assume the user will be running this script after entering the invoice and before printing or saving. So we can either use the same starting point we used earlier for entering a narrative line using a script, or we can record this starting point again and edit it. In this example, we'll use the existing starting point.
Open Script Editor and add the following code:
Dim frmINInvoice1 Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) or Form1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
Save the script with the name
SellingPrices.pfs
.
We don't have to stick to the variable names or errors the recorder suggests. For example, we could change frmINInvoice
1
to
InvForm
and change the error message:
Dim InvForm as Object
InvForm = GetActiveObject
If IsNull(InvForm) or InvForm.ClassName <> "INInvoiceEntryForm" Then Error "Wrong form for script"
To look up the selling prices we are going to need a product enquiry, so that's the next step. Add the following code to open the IC Product form:
Dim ProdForm as Object
ProdForm = CreateObject("Accredo.ICProductForm")
Since we'll refer to the invoice line several times in the code we can give it a short name:
Line
.
Dim Line as Object
Line = InvForm.Line
Then we need to go to the first line and work down the invoice lines with a Do ... Loop.
Line.First
Do Until Line.EOF
Line.Next
Loop
Now we need the action to be performed on each line within the loop. We only want to select for price breaks if we are dealing with a Product line, so that will use an If statement. Then we want to select what the quantity on the product line is, so we'll use another If statement, and set a variable
Pricebreak
based on that.
If Line.LineType = "Product" Then
If Line.QuantitySupplied > 30 Then
Pricebreak = 1
ElseIf Line.QuantitySupplied > 15 Then
Pricebreak = 2
Else
Pricebreak = 3
End If
End If
Next, we want to look up the new price if we need one. This will find the first three prices from the Price grid on the Product form. We will set an Array called
Prices[]
and save the prices in this Array.
If ProdForm.FindExact(Line.ProductCode) Then
Dim Prices[1 to 3] as number
For i = 1 To 3
Prices[i] = ProdForm.Price.SellingPrice
ProdForm.Price.Next
Next
End if
Finally we want to set the Selling Price on the line to the correct price from the
Prices
Array.
If PriceList = 1 Then
Form1.Line.SellingPrice = Prices[1]
ElseIf PriceList = 2 Then
Form1.Line.SellingPrice = Prices[2]
Else
Form1.Line.SellingPrice = Prices[3]
End If
Now put them all together:
Dim Form1 as Object
Form1 = GetActiveObject
If IsNull(Form1) or Form1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
Dim ProdForm as Object
ProdForm = CreateObject("Accredo.ICProductForm")
Dim Line as Object
Line = Form1.Line
Line.First
Do Until Line.EOF
If Line.LineType = "Product" Then
If Line.QuantitySupplied > 30 Then
Pricebreak = 1
ElseIf Line.QuantitySupplied > 15 Then
Pricebreak = 2
Else
Pricebreak = 3
End If
If ProdForm.FindExact(Line.ProductCode) Then
Dim Prices[1 to 3] as number
For i = 1 To 3
Prices[i] = ProdForm.Price.SellingPrice
ProdForm.Price.Next
Next
If Pricebreak = 1 Then
Form1.Line.SellingPrice = Prices[1]
ElseIf Pricebreak = 2 Then
Form1.Line.SellingPrice = Prices[2]
Else
Form1.Line.SellingPrice = Prices[3]
End If
End If
End If
Line.Next
Loop
Note: We need to move the End If and Loop statements to the end, to ensure the statements continue.
Save the script again and try running it.
Result:
The script runs, but the product form flashes up on screen and disappears as it runs through each product record. What we are doing here, because we are using the forms, is called
Form Level Scripting
.
If you have the DI module installed, you can access data objects as well as form objects and do data level scripting. This would replace:
Dim ProdForm as Object
ProdForm = CreateObject("Accredo.ICProductForm")
with
Dim ProdForm as Object
ProdForm = CreateObject("Accredo.ICProductData")
Make that change and try running the script.
Result
: You won't see the IC Product form flashing up.
Now get the script to check if DI is available so it will work in either context. To do this, use the ModuleAvailable function:
Dim Form1 as Object
Form1 = GetActiveObject
If IsNull(Form1) or Form1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
Dim ProdForm as Object
If ModuleAvailable("EDI") then
ProdForm = CreateObject("Accredo.ICProductData")
Else
ProdForm = CreateObject("Accredo.ICProductForm")
End If
Dim Line as Object
Line = Form1.Line
Line.First
Do Until Line.EOF
If Line.LineType = "Product" Then
If Line.QuantitySupplied > 30 Then
Pricebreak = 1
ElseIf Line.QuantitySupplied > 15 Then
Pricebreak = 2
Else
Pricebreak = 3
End If
If ProdForm.FindExact(Line.ProductCode) Then
Dim Prices[1 to 3] as number
For i = 1 To 3
Prices[i] = ProdForm.Price.SellingPrice
ProdForm.Price.Next
Next
If Pricebreak = 1 Then
Form1.Line.SellingPrice = Prices[1]
ElseIf Pricebreak = 2 Then
Form1.Line.SellingPrice = Prices[2]
Else
Form1.Line.SellingPrice = Prices[3]
End If
End If
End If
Line.Next
Loop
If Not ModuleAvailable("EDI") then
ProdForm.Close
ProdForm = Nothing
End If

---

## Script to Create a New Invoice

Source: https://accredo.co.nz/webhelp/ScriptToCreateNewInvoice.htm

Script to Create a New Invoice
This example shows how to record, save and play a basic script. This script will automatically create a new invoice.
Click
Record Script
(Alt+F1)
to start recording. Your actions will now be recorded in the script.
Go to Navigator > Tasks > Invoicing System > Enter Invoices. Select
Invoice
.
Click
Stop Recording
(Alt+F1)
to turn off the script recorder. The Script Editor will open with the recorded code:
Dim frmINInvoice1 as Object
frmINInvoice1 = CreateObject("Accredo.INInvoiceEntryForm")
frmINInvoice1.InsertInvoice
Click
Save
(CTRL+S)
to save the script.
Name the script
NewInvoice1.pfs
then click
Save.
Scripts are usually saved in the \AccredoSaturn\Scripts folder and are available to all Companies. Accredo Script files have the extension
.pfs
.
Click
Run Script
(Ctrl+R)
to run the script from Script Editor. This will create a new invoice.
Close the Script Editor.
Click
Play a script
(Alt+F3) on the toolbar. Open the saved script
NewInvoice1.pfs
. Running the script will repeat the actions recorded before, and will create a new invoice.

---

## Script to Run Standing Invoices

Source: https://accredo.co.nz/webhelp/ScriptToRunStandingInvoices.htm

Script to Run Standing Invoices
This example shows how a script can be broken into various steps.
Typically, the process for a standing invoice run will include some or all of the following steps:
Create the invoices for the current run, either by:
Duplicating a standing invoice which is setup for each customer (for example, for a cleaning company invoicing their monthly charges which are different for each customer) - OR -
Duplicating a single template invoice to all customers (for example, for an annual subscription fee which is the same for all clients but may vary year to year).
Edit the invoices and/or the template as the invoices are duplicated, for example, to increment the date, enter the number of days in the month as a quantity, or increment an instalment number.
Print the invoices if required, or number and mark as manual.
Either post the invoices, or cash sale the invoices if you are paid by direct credit or draw down direct debits.
Export the direct debits as a bank file.
Print a report of what has been done.
Lets take a simple case first. The following script will:
Copy and save all standing invoices with Internal Reference "Monthly" as current Invoices for the same customer
Edit the standing invoice to increment the date by one month and the order number by 1
Count the number of invoices generated and display that at the end.
Dim InvList as Object
Dim InvForm as Object
Dim Invoice as Object
InvList = CreateObject("Accredo.INInvoiceListForm")
InvList.Selection = "Standing Invoice"
InvList.ToggleShowAll
Invoice = InvList.Invoice
Count = 0
Invoice.First
Do Until Invoice.EOF
If Upper(Invoice.InternalReference) = "MONTHLY" Then
Invoice.Open
InvForm = GetActiveObject
If IsNull(InvForm) or InvForm.ClassName <> "INInvoiceEntryForm" Then
Error "Bad Karma"
End If
Count = Count + 1
InvForm.DuplicateInvoice
InvForm.Save
InvForm.Close
Invoice.Open
InvForm = GetActiveObject
If IsNull(InvForm) or InvForm.ClassName <> "INInvoiceEntryForm" Then
Error "Bad Karma"
End If
InvForm.Edit
InvForm.OrderNo = Val(InvForm.OrderNo) + 1
InvForm.DocumentDate = AddMonths(InvForm.DocumentDate,1 ,31)
InvForm.PeriodID = PeriodName(PeriodForDate(InvForm.DocumentDate))
InvForm.Save
InvForm.Close
End If
Invoice.Next
Loop
InvList.Close
Print Count & " Invoices Generated"
This process will be quite slow if you have a lot of invoices to create and are working at the form level. Modified to work at the data level the script looks like this:
Dim InvData as Object
Dim Invoice as Object
InvData = CreateObject("Accredo.INInvoiceData")
InvData.IndexName = "TypeCustomerPeriodDocument"
InvData.SetRange("N")
Invdata.FilterSort.Filter = "(DocumentClass=""S"") And (InternalReference=""Monthly"")"
Invoice = CreateObject("Accredo.INInvoiceData")
Invoice.IndexName = "Document"
Count = 0
InvData.First
Do Until InvData.EOF
Invoice.SetRange(InvData.DocumentID)
Invoice.DuplicateInvoice
Invoice.DocumentDate = InvData.DocumentDate
Invoice.PeriodID = (PeriodForDate(Invoice.DocumentDate))
Invoice.Save
Count = Count + 1
InvData.Edit
InvData.OrderNo = Val(InvData.OrderNo) + 1
InvData.DocumentDate = AddMonths(InvData.DocumentDate,1 ,31)
InvData.PeriodID = PeriodForDate(InvData.DocumentDate)
InvData.Save
InvData.Next
Loop
Invoice = Nothing
InvData = Nothing
Print Count & " Invoices Generated"
Some other enhancements you may want to make are:
Working through a similar process, but working from a single standing invoice attached to a specific customer.
Printing the resulting invoices as you go.
Using the cash sale process to post, receipt and allocate the resulting invoices, then linking the resulting banking summary to the customer records and exporting a file of direct debits to load into your banking software.
If we want to print a report listing the invoices generated, the quickest way to record this is to create the report, add it to a new report list, then edit the report list and copy the code into our script.

---

## Script to Toggle Invoice Lines Type

Source: https://accredo.co.nz/webhelp/ScriptToToggleInvoiceLinesType.htm

Script to Toggle Invoice Lines Type
This example shows you how to record a script to change an Invoice line Type from Product to Narrative or vice versa.
Record a script to change the invoice line type from Product to Narrative:
Open an invoice and select a line to change. If it is not already a Product line, set the Type to Product.
Click
Record
(
Alt+F1).
Change the line Type to Narrative.
Move your focus to the Description field and enter some text (for example type
stuff
).
Tab to the next field.
Click
(Alt+F1)
to turn off the script recorder.
Result:
Script Editor opens and displays what it has recorded:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetTriggerObject
if IsNull(frmINInvoice1) then frmINInvoice1 = GetActiveObject
if IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.Line.Description = "stuff"
Next we will change the script so that the Description is not set to the same thing (for example
stuff
) each time. We will change the script to keep the Description field selected, so we can enter a description after the script has run.
Forms have an
ActiveProperty
property, that contains the form field that currently has focus. You can set the ActiveProperty to change the focus on the form. This lets us put the cursor in a field, without having to add text to the field.
To do this, change the last line of the script to:
frmINInvoice1.ActiveProperty = "Line.Description".
Save this script with the name
NarrativeLine.pfs
. Leave the Script Editor form open.
Now we will record a script to change the line type back to Product, as we did in Steps 1 and 2. Select a line with type Narrative, or set the line type to Narrative. Now repeat Steps 1 and 2, but change the line type to Product.
A new Script Editor window should show the code:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetTriggerObject
if IsNull(frmINInvoice1) then frmINInvoice1 = GetActiveObject
if IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
frmINInvoice1.Line.LineType = "Product"
frmINInvoice1.ActiveProperty = "Line.Description"
We want to combine the two scripts,  so that if the line Type Is
Product
the script changes it to
Narrative
, but if the type is
Narrative
the script changes it to
Product
. Copy the code from your second script editor, and paste it in the first script editor, after the existing code.
We will modify the code to include an
If
statement, to check what the existing line Type is. Modify the code as follows:
Dim frmINInvoice1 as Object
frmINInvoice1 = GetTriggerObject
if IsNull(frmINInvoice1) then frmINInvoice1 = GetActiveObject
if IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" then Error "Wrong form class for script"
If frmINInvoice1.Line.LineType = "Product" then
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.ActiveProperty = "Line.Description"
ElseIf frmINInvoice1.Line.LineType = "Narrative" then
frmINInvoice1.Line.LineType = "Product"
frmINInvoice1.ActiveProperty = "Line.Description"
End If
We can even take this further so the script can be run using the same keyboard shortcut in an invoice, order or purchase order. This is a script we supply as a sample in the Demo and Live systems. Load the "ToggleLineType" script and have a look:
'Toggle document line type between Narrative and Product
'Script Shortcut - Keyboard shortcut only Ctrl+\
Dim frmINInvoice1 as Object
frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) then
'Do nothing if no form open
ElseIf frmINInvoice1.ClassName = "INInvoiceEntryForm" or frmINInvoice1.ClassName = "POPurchaseOrderEntryForm" or frmINInvoice1.ClassName = "OESalesOrderEntryForm" then
If frmINInvoice1.Editing then
If frmINInvoice1.Line.LineType <> "Narrative" then
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.ActiveProperty = "Line.Description"
ElseIf frmINInvoice1.Line.LineType = "Narrative" then
frmINInvoice1.Line.LineType = "Product"
frmINInvoice1.ActiveProperty = "Line.ProductCode"
End If
Else
Abort(frmINInvoice1.ClassName & " not in Edit mode, cannot change line type.")
End If
ElseIf frmINInvoice1.ClassName = "JCBatchTransactionEntryForm" or frmINInvoice1.ClassName = "JCTimesheetTransactionEntryForm" then
If frmINInvoice1.Editing then
If frmINInvoice1.Line.TransactionType <> "Narrative" then
frmINInvoice1.Line.TransactionType = "Narrative"
frmINInvoice1.ActiveProperty = "Line.Description"
ElseIf frmINInvoice1.Line.TransactionType = "Narrative" then
frmINInvoice1.Line.TransactionType = frmINInvoice1.TransactionType
If frmINInvoice1.CostCentreCode <> "" Then frmINInvoice1.Line.CostCentreCode = frmINInvoice1.CostCentreCode
If frmINInvoice1.ComponentCode <> "" Then frmINInvoice1.Line.ComponentCode = frmINInvoice1.ComponentCode
If frmINInvoice1.ProductCode <> "" Then frmINInvoice1.Line.ProductCode = frmINInvoice1.ProductCode
If frmINInvoice1.CreditorCode <> "" Then frmINInvoice1.Line.CreditorCode = frmINInvoice1.CreditorCode
If frmINInvoice1.Unit <> "" Then frmINInvoice1.Line.Unit = frmINInvoice1.Unit
frmINInvoice1.ActiveProperty = "Line.TransactionQuantity"
End If
Else
Abort(frmINInvoice1.ClassName & " not in Edit mode, cannot change line type.")
End If
ElseIf frmINInvoice1.ClassName = "JCJobForm" then
If frmINInvoice1.Editing then
If frmINInvoice1.Estimate.EstimateLineType <> "Narrative" then
frmINInvoice1.Estimate.EstimateLineType = "Narrative"
frmINInvoice1.ActiveProperty = "Estimate.Description"
ElseIf frmINInvoice1.Estimate.EstimateLineType = "Narrative" then
frmINInvoice1.Estimate.EstimateLineType = "Material"
frmINInvoice1.ActiveProperty = "Estimate.ProductCode"
End If
Else
Abort(frmINInvoice1.ClassName & " not in Edit mode, cannot change line type.")
End If
ElseIf frmINInvoice1.ClassName = "APShipmentEntryForm"  then
If frmINInvoice1.Editing AND frmINInvoice1.ActivePage = 2 then ' if in edit mode and in the lines tab
If frmINInvoice1.Line.LineType <> "Narrative" then
frmINInvoice1.Line.LineType = "Narrative"
frmINInvoice1.ActiveProperty = "Line.Description"
ElseIf frmINInvoice1.Line.LineType = "Narrative" then
frmINInvoice1.Line.LineType = "Product"
frmINInvoice1.ActiveProperty = "Line.ProductCode"
End If
Else
Abort(frmINInvoice1.ClassName & " not in Edit mode or not in the Lines tab, cannot change line type.")
End If
Else
'Do nothing if wrong form open
End If
frmINInvoice1 = Nothing
The first two lines document what the script is for. The apostrophe at the start of the line "remarks" out the line so it is not treated as part of our code. The script has been structured to fail silently if run in the wrong place, but to tell the user what is wrong if run in the right place but wrong context, such as if you are not editing your document.

---

