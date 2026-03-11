# Forms Designer

> Form designer, controls, properties, layouts, FD tutorials

**Sections:** 68

---

## Quick Reference

- [FD Tutorial: Custom Form refreshed on a timer](#fd-tutorial-custom-form-refreshed-on-a-timer)
- [FD Tutorial: Dashboard Analysis of Expenses](#fd-tutorial-dashboard-analysis-of-expenses)
- [FD Tutorial: Dashboard Cash](#fd-tutorial-dashboard-cash)
- [FD Tutorial: Dashboard Monthly Sales](#fd-tutorial-dashboard-monthly-sales)
- [FD Tutorial: Dashboard Reports](#fd-tutorial-dashboard-reports)
- [FD Tutorial: Display a Memory Table in a Grid](#fd-tutorial-display-a-memory-table-in-a-grid)
- [FD Tutorial: Totalling for List Grids](#fd-tutorial-totalling-for-list-grids)
- [Form Designer](#form-designer)
- [Form Designer Alignment](#form-designer-alignment)
- [Form Designer Bevel Properties](#form-designer-bevel-properties)
- [Form Designer Button Properties](#form-designer-button-properties)
- [Form Designer Check Box Properties](#form-designer-check-box-properties)
- [Form Designer Code tab](#form-designer-code-tab)
- [Form Designer Color Properties](#form-designer-color-properties)
- [Form Designer Combo Methods](#form-designer-combo-methods)
- [Form Designer Component Editor](#form-designer-component-editor)
- [Form Designer Component Events](#form-designer-component-events)
- [Form Designer Component Methods](#form-designer-component-methods)
- [Form Designer Component Order](#form-designer-component-order)
- [Form Designer Component Palette](#form-designer-component-palette)
- [Form Designer Data Combo Properties](#form-designer-data-combo-properties)
- [Form Designer Date Edit Properties](#form-designer-date-edit-properties)
- [Form Designer Design Window](#form-designer-design-window)
- [Form Designer Drop Down List Properties](#form-designer-drop-down-list-properties)
- [Form Designer Edit Grid Properties](#form-designer-edit-grid-properties)
- [Form Designer Edit Properties](#form-designer-edit-properties)
- [Form Designer File Open Dialog Properties](#form-designer-file-open-dialog-properties)
- [Form Designer File Save Dialog Properties](#form-designer-file-save-dialog-properties)
- [Form Designer Folder Dialog Properties](#form-designer-folder-dialog-properties)
- [Form Designer for High DPI](#form-designer-for-high-dpi)
- [Form Designer Form Navigator Properties](#form-designer-form-navigator-properties)
- [Form Designer Form Properties](#form-designer-form-properties)
- [Form Designer Graph Editor](#form-designer-graph-editor)
- [Form Designer Graph Methods](#form-designer-graph-methods)
- [Form Designer Graph Properties](#form-designer-graph-properties)
- [Form Designer Grid Navigator Methods](#form-designer-grid-navigator-methods)
- [Form Designer Grid Navigator Properties](#form-designer-grid-navigator-properties)
- [Form Designer Grid Scroller Properties](#form-designer-grid-scroller-properties)
- [Form Designer Group Box Properties](#form-designer-group-box-properties)
- [Form Designer HTML Memo Properties](#form-designer-html-memo-properties)
- [Form Designer Image Properties](#form-designer-image-properties)
- [Form Designer Label Properties](#form-designer-label-properties)
- [Form Designer Link Label Properties](#form-designer-link-label-properties)
- [Form Designer List Grid Properties](#form-designer-list-grid-properties)
- [Form Designer Memo Methods](#form-designer-memo-methods)
- [Form Designer Memo Properties](#form-designer-memo-properties)
- [Form Designer Memory Table Properties](#form-designer-memory-table-properties)
- [Form Designer Move Components](#form-designer-move-components)
- [Form Designer Number Edit Properties](#form-designer-number-edit-properties)
- [Form Designer Objects](#form-designer-objects)
- [Form Designer Page Control Properties](#form-designer-page-control-properties)
- [Form Designer Panel Properties](#form-designer-panel-properties)
- [Form Designer Period Lookup Combo Properties](#form-designer-period-lookup-combo-properties)
- [Form Designer Scroll Box Properties](#form-designer-scroll-box-properties)
- [Form Designer Speed Button Properties](#form-designer-speed-button-properties)
- [Form Designer Spin Edit Properties](#form-designer-spin-edit-properties)
- [Form Designer Splitter Properties](#form-designer-splitter-properties)
- [Form Designer Style Guidelines](#form-designer-style-guidelines)
- [Form Designer Surrogate Data Combo Properties](#form-designer-surrogate-data-combo-properties)
- [Form Designer Surrogate Edit Data Combo Properties](#form-designer-surrogate-edit-data-combo-properties)
- [Form Designer Tab Sheet Properties](#form-designer-tab-sheet-properties)
- [Form Designer Table Field Editor](#form-designer-table-field-editor)
- [Form Designer Table Methods](#form-designer-table-methods)
- [Form Designer Table Properties](#form-designer-table-properties)
- [Form Designer Time Edit Properties](#form-designer-time-edit-properties)
- [Form Designer Timer Properties](#form-designer-timer-properties)
- [Form Designer Tutorials](#form-designer-tutorials)
- [Form Events](#form-events)

---

## FD Tutorial: Custom Form refreshed on a timer

Source: https://accredo.co.nz/webhelp/FDTutorialCustomFormTimer.htm

FD Tutorial: Custom Form refreshed on a timer
This tutorial will show you how to create a form that displays an amount that is regularly refreshed on a timer.
Go to Navigator > Setup > Form Designer. Form Designer will open with a blank form.
Add a Label component. You can do this by selecting Label from the Component menu, then clicking the form, or by clicking the
Label component icon, then clicking the form.
Set the Caption for the label to
Sales Invoices Value this Period To Date
. Resize the label to fit the caption.
Add another label under the first label. This one will display the calculated Sales Invoices Value for the current period.
Click in the Font properties to change the Font Size for the label. Enter a larger font size, such as
14
. Set the Label name to
lSalesValue
.
Add a
Timer component. This component is not shown on the form, so it doesn't matter where you place it.
Go to the Code tab. Enter code to add the Gross Amount Bs for Invoices in the current period. Enter the following code:
Sub CalcSalesValue
Dim SalesValue as Number
SalesValue = 0
Dim INHead as Object
INHead = OpenTable("INHead")
InHead.IndexName = "PeriodDocument"
INHead.SetRange(CurrentPeriod("IN"))
Do
If INHead.DocumentClass = "I" Then SalesValue = SalesValue + INHead.GrossAmountBs
INHead.Next
Loop Until INHead.EOF
lSalesValue.Caption = FormatNumber(SalesValue,",0.00")
End Sub
Note: This code adds values for Posted and Unposted Invoices, and excludes Credits. You can modify the code if you want to change this.
Go to the Layout tab. Select the form from the component list. Go to the Events tab. Set the OnShow event to
CalcSalesValue
.
Select the Timer component. Set the Enabled property to
True
. Set the Interval to
600000
. This is the millisecond equivalent of 10 minutes.
Go to the Events tab. Set the OnExecute event to
CalcSalesValue
.
Click
Run
(
Ctrl+R
). The form will display the Sales Invoice Value for this period, and will update the figure every ten minutes.
You can Save the form, then add it to a shortcut on the Menu Bar or in the Navigator. See
Script Shortcut Editor
.
To change the form from a Normal Window to a Floating Window, click the Accredo Mercury or Saturn icon in the top left corner of the form, then select
Move to New Window
. To change it back to a Normal Window, click the icon again and select
Move to Main Window
.

---

## FD Tutorial: Dashboard Analysis of Expenses

Source: https://accredo.co.nz/webhelp/FDTutorialAnalysisExpenses_1.htm

FD Tutorial: Dashboard Analysis of Expenses
Using the Form Designer, you can create a dashboard to show graphs and list key figures for your company. This tutorial requires the AP Module.
This tutorial will show you how to display an analysis of expenses for a range of periods.
Go to Navigator > Setup > Form Designer.
Click the
Memory Table
button, then click inside the form on the right. A Memory Table object will be added to the form. The memory table object will not be displayed when the form runs, so it doesn't matter where you put it.
Click the memory table icon on the form. The properties will be listed on the left.
Change the
Name
of your table to
tblGraphExp
.
Double-click the Memory Table icon on your form. The FD Memory Table Designer will open.
Add the following fields to the table:
No.
Name
Display Label
Type
Domain
Size
Width
Visible
1
AnalysisCode
Expenses
String
Analysis Code
8
15
Selected
2
AnalysisName
Analysis Name
String
Analysis Name
60
25
Selected
3
PeriodBalance
Period Balance
Float
Amount
15
Selected
4
YrToDateBalance
YTD Balance
Float
Amount
15
Selected
5
LastYRBalance
LY Balance
Float
Amount
10
Selected
6
GLAccountCode
Account Code
String
GL Account Code
8
15
Clear
7
AccountClass
Account Class
String
Description
60
28
Clear
Click
Save
. The FD Memory Table Designer will close.
Set the
Active
property of the Memory Table to
True
.
Click the
List Grid
button, then click inside the form on the right. A List Grid will be added to the form.
Click the List Grid on the form, to show the properties on the left.
Change the
Name
of the grid to
gridExp
.
To change the display of the grid, set the following properties:
Property
Value
Description
Height
270
Sets the grid height. You can also drag to change the height.
Left
25
Moves the grid to the left of the form.
Top
30
Sets the grid position from the top. You can also drag to change the position.
Width
550
Sets the grid width. You can also drag to change the width.
Set the graph
Table
property to
tblGraphExp
. This links the grid to the memory table created previously.
Click the
Grid Navigator
button. Click beside the List Grid to add a navigator next to the grid.
Change the
Name
of the navigator to
navExp
.
Change the following properties of the grid navigator.
Property
Value
Description
Height
270
Sets the navigator height. You can also drag to change the height.
Left
0
Moves the navigator to the left of the form.
Top
30
Sets the grid position from the top. You can also drag to change the position.
Visible Buttons
ebOpen
ebPrint
ebFilterSort
ebCustomise
Select the buttons to show on the grid navigator. Set the buttons listed to
True
, all others to
False
.
Width
25
Sets the grid width. You can also drag to change the width.
Set the
Table
to
tblGraphExp
. This links the grid to the memory table created previously. Set the
Hook Control
to
gridExp
, to link the navigator to the grid.
You can now write the MaxBasic code to populate the Memory Table and graph.
Enter the following code, to extract the expense information and populate the memory table, and display it in the grid:
Sub RefreshExpenses
Dim tblExpenses as Object
SQLExpenses = "SELECT APANL.AnalysisCode as AnalysisCode" & _
"      ,APANL.AnalysisName as AnalysisName " & _
"      ,APANL.CurrentPeriodBalance as PeriodBalance " & _
"      ,APANL.LastYearBalance as LastYRBalance " & _
"      ,APANL.YearToDateBalance as YRToDateBalance " & _
"      ,APANL.GLAccountCode as AccountCode " & _
"      ,APANL.AccountClass as Class " & _
"FROM   APANL " & _
"Order By AnalysisCode"
tblExpenses = ExecuteSQL(SQLExpenses)
tblGraphExp.empty
tblGraphExp.AllowInsertDelete = True
tblExpenses.First
Do Until tblExpenses.EOF
tblGraphExp.Append
tblGraphExp.AnalysisCode = tblExpenses.AnalysisCode
tblGraphExp.AnalysisName = tblExpenses.AnalysisName
tblGraphExp.PeriodBalance = tblExpenses.PeriodBalance
tblGraphExp.LastYRBalance = tblExpenses.LastYRBalance
tblGraphExp.YRToDateBalance = tblExpenses.YRToDateBalance
tblGraphExp.GLAccountCode = tblExpenses.AccountCode
If tblExpenses.Class = "A" Then
tblGraphExp.AccountClass = "Asset"
ElseIf tblExpenses.Class = "C" Then
tblGraphExp.AccountClass = "Capital"
ElseIf tblExpenses.Class = "E" Then
tblGraphExp.AccountClass = "Expenses"
ElseIf tblExpenses.Class = "I" Then
tblGraphExp.AccountClass = "Income"
ElseIf tblExpenses.Class = "L" Then
tblGraphExp.AccountClass = "Liability"
End If
tblGraphExp.Save
tblExpenses.Next
Loop
tblGraphExp.AllowInsertDelete = False
tblGraphExp.First
End Sub
Create a routine called OnCreate to run when the form is created. This will call the RefreshExpenses sub-routine. Enter the following code:
Sub OnCreate
RefreshExpenses
End Sub
Click the Layout tab. Click on the form, or select the frmFDForm component.
Go to the Events tab. Set
OnCreate
to
OnCreate
.
Add the following code to enable the Open and Print buttons:
Sub OnNavExp(Sender as Object, Button as Number, ByRef Handled as Boolean)
Dim Report as Object
If Button = ebOpen Then
Dim Form1 as Object
Form1 = CreateObject("Accredo.APExpenseCodeForm")
Form1.Find(tblGraphExp.AnalysisCode)
Form1.GraphSelection = "Range of Periods"
Form1.GraphPeriodFrom = StartPeriod
Form1.GraphPeriodTo = EndPeriod
Form1.GraphField2 = ""
Form1.GraphField2 = ""
Form1.GraphField = "PeriodActivity"
End If
If Button = ebPrint Then
Report = CreateReport(tblGraphExp, " Expenses For Last 12 Months ")
Report.Destination = "Screen"
Report.Run
Handled = True
End If
End Sub
Go to the layout tab. Select the
navExp
component. Go to the Events tab. Set
OnClick
to
OnNavExp
.
You can add a Link label as a title to the graph. Click the
Link Label
button, then click on the form.
Change the
Caption
to
Analysis of Expenses
.
You can change label size, position, font, colour or other properties.
Add code to go to the IN Invoice Report when the Link Label is clicked. Go to the Code tab, and enter the following code:
Sub OnLinkExpenses
Dim Form1 as Object
Form1 = CreateObject("Accredo.APExpenseDetailedReport")
Form1.Layout = "Expense Analysis Detail"
End Sub
Go to the layout tab. Select the Link Label component. Go to the Events tab. Set
OnClick
to
OnLinkExpenses
.
Click
Save Form
(Ctrl+S)
.
Click
Run
(Ctrl+R)
to test the form.
In This Section
FD Tutorial: Dashboard Product Sales
FD Tutorial: Dashboard Cash
See Also
FD Dashboard Tutorials

---

## FD Tutorial: Dashboard Cash

Source: https://accredo.co.nz/webhelp/FDTutorialCash_1.htm

FD Tutorial: Dashboard Cash
Using the Form Designer, you can create a dashboard to show graphs and list key figures for your company. This tutorial requires the AP Module.
This tutorial will show you how to display an analysis of expenses for a range of periods.
Go to Navigator > Setup > Form Designer.
Click the
Memory Table
button, then click inside the form on the right. A Memory Table object will be added to the form. The memory table object will not be displayed when the form runs, so it doesn't matter where you put it.
Click the memory table icon on the form. The properties will be listed on the left.
Change the
Name
of your table to
tblCash
.
Double-click the Memory Table icon on your form. The FD Memory Table Designer will open.
Add the following fields to the table:
No.
Name
Display Label
Type
Domain
Size
Width
Visible
1
BankAccount
Account
String
CB Bank Account Code
8
8
Selected
2
CurrencyCode
Currency
String
Description
60
10
Selected
3
CBBalance
Balance
Float
Amount
10
Selected
4
CBBalanceBs
BalanceBs
Float
Amount
10
Click
Save
. The FD Memory Table Designer will close.
Set the
Active
property of the Memory Table to
True
.
Click the
List Grid
button, then click inside the form on the right. A List Grid will be added to the form.
Click the List Grid on the form, to show the properties on the left.
Change the
Name
of the grid to
gridCash
.
To change the display of the grid, set the following properties:
Property
Value
Description
Height
200
Sets the grid height. You can also drag to change the height.
Left
25
Moves the grid to the left of the form.
Top
30
Sets the grid position from the top. You can also drag to change the position.
Width
200
Sets the grid width. You can also drag to change the width.
Set the graph
Table
property to
tblCash
. This links the grid to the memory table created previously.
Click the
Grid Navigator
button. Click beside the List Grid to add a navigator next to the grid.
Change the
Name
of the navigator to
navCash
.
Change the following properties of the grid navigator.
Property
Value
Description
Height
200
Sets the navigator height. You can also drag to change the height.
Left
0
Moves the navigator to the left of the form.
Top
30
Sets the grid position from the top. You can also drag to change the position.
Visible Buttons
ebOpen
ebPrint
ebFilterSort
ebCustomise
Select the buttons to show on the grid navigator. Set the buttons listed to
True
, all others to
False
.
Width
25
Sets the grid width. You can also drag to change the width.
Set the
Table
to
tblCash
. This links the grid to the memory table created previously. Set the
Hook Control
to
gridCash
, to link the navigator to the grid.
You can now write the MaxBasic code to populate the Memory Table and graph.
Enter the following code, to extract the expense information and populate the memory table, and display it in the grid:
Sub RefreshCash
Dim tblCBBank as Object
tblCBBank = OpenTable("CBBank")
tblCBBank.IndexName = "ActiveBank"
tblCash.Empty
tblCash.AllowInsertDelete = True
tblCBBank.First
Do Until tblCBBank.EOF
tblCash.Append
If tblCBBank.Inactive = False Then
tblCash.BankAccount = tblCBBank.BankAccountCode
tblCash.CurrencyCode = tblCBBank.CurrencyCode
tblCash.CBBalance = tblCBBank.CashBookBalance
tblCash.CBBalanceBs = tblCBBank.CashBookBalanceBs
tblCash.Save
End If
tblCBBank.Next
Loop
tblCash.AllowInsertDelete = False
tblCash.First
End Sub
Create a routine called OnCreate to run when the form is created. This will call the RefreshExpenses sub-routine. Enter the following code:
Sub OnCreate
RefreshCash
End Sub
Click the Layout tab. Click on the form, or select the frmFDForm component.
Go to the Events tab. Set
OnCreate
to
OnCreate
.
Add the following code to enable the Open and Print buttons:
Sub OnNavCash(Sender as Object, Button as Number, ByRef Handled as Boolean)
Dim Report as Object
If Button = ebOpen Then
Dim Form1 as Object
Form1 = CreateObject("Accredo.CBBankAccountForm")
Form1.Find(tblCash.BankAccount)
End If
If Button = ebPrint Then
Report = CreateReport(tblCash, " Bank Account Balances ")
Report.Destination = "Screen"
Report.Run
Handled = True
End If
End Sub
Go to the layout tab. Select the
navCash
component. Go to the Events tab. Set
OnClick
to
OnNavCash
.
You can add a label as a title to the graph. Click the
Label
button, then click on the form.
Change the
Caption
to
Cash
.
You can change label size, position, font, colour or other properties.
Click
Save Form
(Ctrl+S)
.
Click
Run
(Ctrl+R)
to test the form.
See Also
FD Tutorial: Dashboard Analysis of Expenses

---

## FD Tutorial: Dashboard Monthly Sales

Source: https://accredo.co.nz/webhelp/FDTutorialMonthlySales.htm

FD Tutorial: Dashboard Monthly Sales
Using the Form Designer, you can create a dashboard to show graphs and list key figures for your company. This tutorial requires the AR and IN Modules.
This tutorial will show you how to display Monthly Sales on a form.
Go to Navigator > Setup > Form Designer.
Click the
Memory Table
button, then click inside the form on the right. A Memory Table object will be added to the form. The memory table object will not be displayed when the form runs, so it doesn't matter where you put it.
Click the memory table icon on the form. The properties will be listed on the left.
Change the
Name
of your table to
tblGrpSales
, by typing this beside the Name property, over
tblMemoryTable1
. The table is going to contain the monthly sales data, so it is helpful to give it a meaningful name, indicating the table contents.
Double-click the Memory Table icon on your form. The FD Memory Table Designer will open.
Add the following fields to the table:
No.
Name
Display Label
Type
Domain
Size
Width
Req
Visible
1
PeriodID
PeriodID
Byte
10
Clear
2
ExclusiveAmount
Amount
Float
Amount
10
Selected
3
PeriodName
Period
String
16
15
Selected
Go to the FD Memory Table Designer - Keys tab.
Add the following key to the table.
No.
Name
Unique
Primary
Parts
1
Period
Selected
+PeriodID
Click
Save
. The FD Memory Table Designer will close.
Set the
Active
property of the Memory Table to
True
.
Set the
IndexName
property of the Memory Table to
Period
.
Click the
Graph
button, then click inside the form on the right. A Graph object will be added to the form.
Click the Graph on the form, to show the properties on the left.
Change the
Name
of the graph to
graphSales
.
To change the display of the graph, set the following properties:
Property
Value
Description
Anchors
[akLeft]
Click the Expand [x] button next to Anchors, and set akTop to False. This will bind the graph to the left.
BackWallColor
clWhite
Click the [...] button in BackWallColor, and click white, to set the graph back wall to white.
Height
258
Sets the graph height. You can also drag to change the height.
Left
0
Moves the graph to the left of the form.
ShowGridLines
False
Hides the grid lines.
ShowLegend
False
Hides the legend.
Top
52
Sets the graph position from the top. You can also drag to change the position.
Width
640
Sets the graph width. You can also drag to change the width.
Set the
Table
to
tblGroupSales
. This links the Graph to the memory table created previously. Set the
XLabelFieldName
to
PeriodName
.
Double-click the graph in the form. The FD Graph Editor opens.
Add the following field to the Graph Editor:
Field Name
Show Key Border
Pen Style
Pen Width
ExclusiveAmount
Selected
psClear
2
Click
Save
. The FD Graph Editor will close.
You can now write the MaxBasic code to populate the Memory Table and graph.
Initialise variables to be used in the dashboard. Click on the Code tab. Enter the following:
Dim PeriodToUse as Number, StartPeriod as Number, EndPeriod as Number
PeriodToUse = CurrentPeriod("AR")
StartPeriod = AddPeriod(PeriodToUse, -12,True)
EndPeriod = AddPeriod(PeriodToUse, -1,True)
This sets the
PeriodToUse
to the current AR Period, the
StartPeriod
to 12 periods prior to the PeriodToUse, and
EndPeriod
to 1 period before PeriodToUse.
Enter the following code, to extract the sales information and populate the memory table, and display it in the graph:
Sub RefreshSales
Dim tblSales as Object 'Will be used to store the query data
Dim TotalSales as Number
tblGrpSales.empty 'Clear the memory table
'Enter the SQL Query to extract the sales amounts per period
SQLSales ="SELECT   INHEAD.PeriodID as PeriodID " & _
"        ,Sum(INHEAD.ExclusiveAmountBs) as ExclusiveAmount " & _
"FROM   INHEAD " & _
"WHERE INHEAD.PeriodID Between :LYStart AND :TYEnd " & _
"   AND INHEAD.PostStatus = 'P' " & _
"   AND INHEAD.DocumentClass IN ('I', 'C') " & _
"GROUP BY INHEAD.PeriodID " & _
"ORDER BY INHEAD.PeriodID "
tblSales = ExecuteSQL(SQLSales, StartPeriod, EndPeriod)
tblGrpSales.AllowInsertDelete = True
tblGrpSales.IndexName = "Period"
tblSales.First
Do Until tblSales.EOF
tblGrpSales.Append
CopyFieldsByName(tblSales, tblGrpSales)
tblGrpSales.PeriodName = PeriodName(tblSales.PeriodID)
tblGrpSales.Save
tblSales.Next
Loop
tblGrpSales.AllowInsertDelete = False
tblGrpSales.IndexName = "Period"
graphSales.RefreshData
End Sub
Create a routine called OnCreate to run when the form is created. This will call the RefreshSales sub-routine. Enter the following code:
Sub OnCreate
RefreshSales
End Sub
Click the Layout tab. Click on the form, or select the frmFDForm component.
Go to the Events tab. Set
OnCreate
to
OnCreate
.
You can add a Link label as a title to the graph. Click the
Link Label
button, then click on the form.
Change the Link Label
Caption
to
Monthly Sales for Last 12 Months
.
You can change label size, position, font, colour or other properties.
Add code to go to the IN Invoice Report when the Link Label is clicked. Go to the Code tab, and enter the following code:
Sub OnLinkSales
Dim Report as Object
Report = CreateObject("Accredo.INInvoiceReport")
Report.Layout = "Invoice"
Report.Destination = "Screen"
Report.Type.Invoice = True
Report.Type.Credit = True
Report.Type.Quote = False
Report.PostStatus.Posted = True
Report.PostStatus.Unposted = False
Report.PostStatus.Open = False
Report.PostStatus.Deleted = False
Report.CurrentHistory = "Both Current and History"
Report.Invoices = "Range of Periods"
Report.PeriodFrom = StartPeriod
Report.PeriodTo = EndPeriod
Report.Preferences.IncludeRecordsWithEmptyDetail = False
End Sub
Go to the layout tab. Select the Link Label component. Go to the Events tab. Set
OnClick
to
OnLinkSales
.
Click
Save Form
(Ctrl+S)
.
Click
Run
(Ctrl+R)
to test the form.
See Also
FD Dashboard Tutorials

---

## FD Tutorial: Dashboard Reports

Source: https://accredo.co.nz/webhelp/FDTutorialReports_1.htm

FD Tutorial: Dashboard Reports
Using the Form Designer, you can create a dashboard to show graphs and list key figures for your company.
This tutorial will show you how to create buttons to link to Reports on the form.
Go to Navigator > Setup > Form Designer.
Click the
Button
button, then click inside the form on the right. A button object will be added to the form.
Click the button on the form, to show the properties on the left.
Change the
Name
of the button to
btnGLReport
.
Change the
Caption
of the button to
GL Trial Balance
.
Resize the button to show the caption.
You can now write the MaxBasic code to run the report
Write the code to run the report. Click on the Code tab. Enter the following:
Sub ONLinkTrialBalance
Dim Form1 as Object
PeriodToUse = CurrentPeriod("AR")
Form1 = CreateObject("Accredo.GLTrialBalanceReport")
Form1.Layout = "Trial Balance"
Form1.Period = PeriodToUse
End Sub
Go to the Layout tab, and click the button.
Go to the Events tab. Set
OnClick
to
OnLinkTrialBalance
.
You can add a label as a title to the form. Click the
Label
button, then click on the form.
Change the
Caption
to
Reports
.
You can change label size, position, font, colour or other properties.
To add other reports, repeat steps 2 - 9, changing the code in Step 7. You can add different reports by changing the code. Also change the name of the sub-routines, and the button captions. Some other reports you could add are:
Report
Code
AR Trial Balance
Dim Form1 as Object
PeriodToUse = CurrentPeriod("AR")
Form1 = CreateObject("Accredo.ARAgedBalancesReport")
Form1.Layout = "Aged Trial Balance"
Form1.Period = PeriodToUse
AP Trial Balance
Dim Form1 as Object
PeriodToUse = CurrentPeriod("AP")
Form1 = CreateObject("Accredo.APAgedBalancesReport")
Form1.Layout = "Aged Trial Balance"
Form1.Period = PeriodToUse
Cash Flow
Dim Form1 as Object
Form1 = CreateObject("Accredo.CBCashFlowReport")
Form1.Layout = "Cash Flow Report"
Product Balances
Dim Form1 as Object
PeriodToUse = CurrentPeriod("AR")
Form1 = CreateObject("Accredo.ICProductBalancesReport")
Form1.Layout = "Product Balances"
Form1.Period = PeriodToUse
Click
Save Form
(Ctrl+S)
.
Click
Run
(Ctrl+R)
to test the form.
See Also
FD Dashboard Tutorials

---

## FD Tutorial: Display a Memory Table in a Grid

Source: https://accredo.co.nz/webhelp/FDTutorialDisplayMemoryTableInGrid.htm

FD Tutorial: Display a Memory Table in a Grid
This tutorial will show you how to create a form that will display information from a memory table in a grid.
Go to Navigator > Setup > Form Designer. Form Designer will open with a blank form.
Add an Edit Grid component. You can do this by selecting Edit Grid from the Component menu, then clicking the form, or by clicking the
Edit Grid component icon, then clicking the form.
Add a
Memory Table component. This component is not shown on the form, so it doesn't matter where you place it.
Double-click the Memory Table, or right-click the Memory Table and select Memory Table Designer. Add fields to the Memory Table. For example you could add:
No.
Name
Display Label
Type
Domain
Uppr
1
Product
Product
String
IC Product Code
Selected
2
Quantity
Quantity
Integer
Clear
3
Price
Price
Float
Amount
Clear
Click Save.
Click the Edit Grid. In the Properties, set the Table to the MemoryTable. The memory table fields will be displayed in the grid.
Right-click the Edit Grid, and select Create Default Editors. Resize the Edit Grid if necessary to show all the fields.
You have now created a form that allows you to enter a list of products, quantities and prices. Click save and give your form a name such as memorytableform.pfd.
If you want to add a running total of the Price x Quantities added, do the following.
Add a
Label component under the grid.
Go to the Code tab and enter the following code:
Sub RefreshTotal
tblMemoryTable1.First
Dim totalbalance As Number
totalbalance = 0
Do While Not tblMemoryTable1.eof
totalbalance = totalbalance + (tblMemoryTable1.price * tblMemoryTable1.quantity)
tblMemoryTable1.Next
Loop
lLabel1.caption = totalbalance
End Sub
This creates a sub-procedure that goes through each row in the Memory Table, and adds the Price * Quantity to the total balance. It then displays the total balance in the Label.
Go back to the Layout tab. Click on the Quantity Spin Edit in the Edit Grid. Go to the Events tab. Set the
OnAfterChange
to RefreshTotal. This means that when the Quantity is changed, the RefreshTotal sub-procedure will run, and will update the Total Balance shown in the label.
Click on the Price Number Edit in the Edit Grid. Go to the Events tab. Set the
OnAfterChange
to RefreshTotal. This means the Total Balance will also be refreshed when the Price is changed.
You have now added a running total, showing the running total of information entered in the Edit Grid.
If you want to automatically extract the NZRETAIL sell price for the Product, do the following.
Go to the Code tab and enter the following code:
Sub GetSellPrice
Dim tbltemp as Object
SQL = "SELECT ICSELL.Price " & _
"    ,ICSELL.ProductCode " & _
"FROM ICSELL " & _
"WHERE (ICSELL.PriceCode = 'NZRETAIL') "
tblTemp = ExecuteSQL(SQL)
tbltemp.First
Do Until tbltemp.eof
If tbltemp.ProductCode = tblMemoryTable1.Product Then
tblMemoryTable1.Price = tblTemp.Price
Exit Do
End If
tbltemp.Next
Loop
End Sub
This will extract all the Product Codes and Sell Prices for ICSELL where the Price Code is NZRETAIL. It then searches through these to find the Product Code selected in the Edit Grid, and sets the Edit Grid Price to the corresponding Sell Price.
Go to the Layout tab. Select the Product Data Combo on the Edit Grid. Go to the Events tab. Set the
OnAfterChange
to GetSellPrice.
Now when you select a Product in your Edit Grid, the Price will be automatically updated.
See Also
Form Designer

---

## FD Tutorial: Totalling for List Grids

Source: https://accredo.co.nz/webhelp/FDTutorialTotallingForListGrids.htm

FD Tutorial: Totalling for List Grids
List Grid Component
Property:
AllowTotals
(Boolean)
Needs to be set to true to allow totals on the grid
Property:
GridTotalled
(Boolean)
Boolean toggle to turn grid totalling on based on AllowTotals being true
Method:
GetTotalValue
(Number)
Method that takes in a string of the field and returns the total value if the grid has been totalled
gridListGrid1.GetTotalValue("ExclusiveAmountBs")
Returns null if the grid is not totalled or the field cannot be totalled (e.g. FX Mixed)
Can be tested with the IsNull() method
Grid Navigator Component
Property:
Grid
(String)
The ListGrid name that the totalling will be for
Property:
Visible Button
: ebTotal
Set  true will enable the calculate totals button on the grid
How to use:
â¢	Available for List Grid Component
â¢	Can be a table component or a Memory Table component
â¢	Must set the list grid component's property of Allow Totals = True
â¢	Must set the "Grid" property of the grid navigator to be the grid it is pointing to
â¢	Must enable the ebTotal = true button on the visible buttons of the grid navigator

---

## Form Designer

Source: https://accredo.co.nz/webhelp/FormDesigner.htm

Form Designer
Navigator > Setup > Form Designer > Layout tab
We recommend only advanced Accredo users who are familiar with Visual Basic style programming use Form Designer.
You can create your own Accredo forms (.pfd files) to interact with Accredo data objects and custom tables. Custom forms are saved in the System Folder/Forms Directory. You can add shortcuts to access custom forms from the Navigator and the Accredo toolbar. The File Menu lists the last 9 files accessed at the end of the menu.
To create forms, Data Interchange (DI) is required, and Table Designer (TD) and Report Designer (RD) are recommended.
You create custom forms by:
Placing components in the Design Window to design the form,
Using Properties and Events to determine component behaviour.
The Form Designer Layout tab contains:
FD Component Palette
FD Component Editor
FD Design Window
, from which you can access:
FD Memory Table Designer
FD Field Editor
FD Graph Editor
From the Code tab you can access:
FD Code Editor
, and use
MaxBasic
code to determine, events, properties and variables.
Toolbar
Blank Form
(Ctrl+N)
Create a blank form.
Open Form
(Ctrl+O)
Open an existing form.
Save Form
(Ctrl+S)
Save the form as a .pfd file.
Add Shortcut
Opens the
Script Shortcut Editor
to create a shortcut to the form. Available after the form is saved.
Undo
(
Ctrl+Z)
Undo the last editing operation.
Redo
(Ctrl+Y)
Redo the last editing operation.
Cut
(
Ctrl+X)
Cut selected component, text or figures to the clipboard.
Copy
(
Ctrl+C)
Copy selected component, text or figures to the clipboard.
Paste
(Ctrl+V)
Paste previously cut or copied component, text or figures from the clipboard.
Document Component
(Ctrl+D)
Document the selected component.
Note: You can also press
Ctrl+F1
to document the form.
Procedure List
Open the
Procedure List
in the Code Editor.
Run
(Ctrl+R)
Execute the form for testing.
In This Section
Form Designer Component Palette
Form Designer Design Window
Form Designer Component Editor
Form Designer Component Events
Form Designer Code tab
Form Designer Table Field Editor
Form Designer Memory Table Designer
Form Designer Graph Editor
FD Tutorial: Display a Memory Table in a Grid
FD Tutorial: Custom Form refreshed on a timer
FD Tutorial: Totalling for List Grids
FD Tutorial: Dashboard Top Customers
FD Dashboard Tutorials
Form Designer Style Guidelines
Form Designer for High DPI

---

## Form Designer Alignment

Source: https://accredo.co.nz/webhelp/FDAlignment.htm

Form Designer Alignment
Navigator > Setup > Form Designer > Design Window > [Select Component(s)] > Right-click >
Align...
Align components horizontally and / or vertically.
Horizontal
Select options to align components horizontally. Select from:
No change
Left sides
Centres
Right sides
Space Equally
Vertical
Select options to align components vertically. Select from:
No change
Left sides
Centres
Right sides
Space Equally
OK
(F9)
Align the components using selections, and close the window.
Cancel
(Esc)
Discard changes and close the window.

---

## Form Designer Bevel Properties

Source: https://accredo.co.nz/webhelp/BevelFDComponent.htm

Form Designer Bevel Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Bevel Components:
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
Hint
The Hint text to be displayed when the mouse hovers over the component.
Shape
Select the Bevel shape from:
Box
Frame
Top Line
Bottom Line
Left Line
Right Line
Spacer
Style
Select the Bevel style from:
Lowered
Raised
Visible
When
True
, the component will be displayed.

---

## Form Designer Button Properties

Source: https://accredo.co.nz/webhelp/ButtonFDComponent.htm

Form Designer Button Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Button Components:
Cancel
When
True
, indicates that the button is a Cancel button, and can be triggered by pressing the
Esc
key.
Caption
The label for the button.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
Default
When
True
, indicates that the button is the default button, and can be triggered by pressing the
Enter
key.
Hint
The Hint text to be displayed when the mouse hovers over the component.
ImageIndex
Select a glyph to be displayed on the button.
ModalResult
When the form is shown modally, the
ModalResult
is the response returned by the form when the user clicks the button. When this is not set to
mrNone
, the modal form will close when the button is clicked.
ParentFont
When
True
, sets the
Font
to the font of the parent container.
ShortCut
Select a short cut key sequence to activate the button.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.

---

## Form Designer Check Box Properties

Source: https://accredo.co.nz/webhelp/CheckBoxFDComponent.htm

Form Designer Check Box Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Check Box Components:
ButtonSize
When zero default size (13), values other than zero override this. Not available for grid bound Check Box.
Checked
When
True
, the check box is checked.
Hint
The hint text to be displayed when the mouse hovers over the component.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
LabelCaption
The text to be displayed beside the Check box.
LabelVisible
When False, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.

---

## Form Designer Code tab

Source: https://accredo.co.nz/webhelp/FDCodeTab.htm

Form Designer Code tab
Navigator > Setup > Form Designer > Code tab
Use the Form Designer Code tab to write code to determine how the form will run. You can enter MaxBasic code, enter the value of an expression property, or select an item from a menu to insert at the pointer position. You can construct statements and expressions. See also
Script Editor Shortcut Keys
for shortcut combinations. You can also insert Automated code snippets in the Code tab, see
Automated Snippets
.
To access the Code Editor
Context Menu
, right-click in the script editor window, or press
Shift+F10
.
You can write sub routines, that can then be triggered by
Component Events
.
To change component font properties using MaxBasic, see
Font Properties
.
Operators
(Alt+O)
Lists all
MaxBasic operators
.
Objects
(Alt+J)
Lists the
objects
and components available from the code. Each components on the form will be listed here, and you can select from each component's fields and methods. When you select a property it will appear in the code.
The following objects are available for all forms in Form Designer:
Company - details of the Company, such as name and address.
Self - details of the form being designed.
User - details of the current User, such as User Name.
Functions
(Alt+F)
MaxBasic functions
and additional functions. When you select a function that expects arguments, the parentheses and commas for the arguments are shown and the pointer is positioned for the first argument, for example,
InStr(|, ).
Automated
(Alt+A)
Lists the
Automated
Objects available.
Procedures
(Alt+E)
Lists
Function
and
Sub
procedures defined in or imported into the script. Use
Ctrl+E
to open the
Procedure List
in a separate window.
Help
(Alt+H)
Access related Help topics.
Snippet
(Alt+T)
Insert a code
Snippet
. Snippets are listed alphabetically, and the first line of each snippet is displayed.
Buttons
Check Code
(Alt+C)
Validates the code to ensure it compiles correctly.
Print
(Ctrl+P)
Print the code.
Breakpoint
(Alt+B)
Set a code
breakpoint
on the current line. Click again to toggle to clear the breakpoint. You can also click to the right of a line to set or clear a breakpoint.
Hover the mouse over a breakpoint, then right-click to make a breakpoint unavailable, or access the
Breakpoint Properties
.
If a condition has been set for a breakpoint, it will be shown when you hover over the breakpoint.
In This Section
Form Designer Objects
Form Designer Component Methods
Form Designer Combo Methods
Form Designer Graph Methods
Form Designer Grid Navigator Methods
Form Designer Memo Methods
Form Designer Table Methods
Font Properties

---

## Form Designer Color Properties

Source: https://accredo.co.nz/webhelp/ColorPropertyFD.htm

Form Designer Color Properties
Note: In Form Designer, color properties are displayed as $00BGR and in code, an Integer must be assigned or a runtime error is thrown.
Colors can be expressed as:
BGR (Blue Green Red) HTML Notation
<six hex digits>
, such as
0000FF.
RGB (Red Green Blue) HTML Notation with a hash character
#<six hex digits>
, such as
#FF0000.
Color Name, such as "
Red"
, when using the
ColorByName
function.
See the
Color table
for available colors and their RGB Notation.
To set the Color property of an FD component in MaxBasic, you can either use
ColorByName
, or
ColorRGB
. For example, to change the color of a component, you could use one of these code examples:
panPanel1.color = 123456
panPanel1.color = "123456"
panPanel1.color = ColorByName("green")
panPanel1.color = ColorRGB(064,226,001)

---

## Form Designer Combo Methods

Source: https://accredo.co.nz/webhelp/FormDesignerComboMethods.htm

Form Designer Combo Methods
Navigator > Setup > Form Designer > Code tab
Components each have different methods available to them. Methods available are listed under
Objects
> [Component Type] > [Component Name] > Methods.
See also
Form Designer Component Methods
for methods available to all component types.
The following methods are available to Combo Components:
Component
Method
Description
Data Combo, Surrogate Data Combo, Period Lookup Combo
CancelRange
Cancels the range that has been set for the table.
Data Combo, Surrogate Data Combo, Period Lookup Combo
SetRangeEnd
Set the value(s) for the end of the range to be included.
Data Combo, Surrogate Data Combo, Period Lookup Combo
SetRangeStart
Set the value(s) for the start of the range to be included.
Data Combo, Surrogate Data Combo, Period Lookup Combo
SetSubSet
Sets a subset to be displayed in the combo, based on the combo Index.
In This Section
CancelRange - Memory Table Method
SetRangeEnd - Memory Table Method
SetRangeStart - Memory Table Method
SetSubSet
See Also
Form Designer Code tab

---

## Form Designer Component Editor

Source: https://accredo.co.nz/webhelp/FDComponentEditor.htm

Form Designer Component Editor
Navigator > Setup > Form Designer > Layout tab
When you select a component in the Design Window, the Component Editor shows the component name, properties and any associated events.
See
Form Designer Component Palette
for a list of available components.
Properties tab
Edit and set values for component properties. Properties associated with the selected component will appear, you can edit them to adjust their appearance and behaviour. See
Form Designer Component Properties
for properties common to all component types, and the individual Properties topic for the component type.
Click
Return to Parent
(
Shift+Esc
) beside the Component Name to go to the component's parent component.
Events tab
Any events associated with the selected component are shown. You can set sub-routines that will be triggered by these events. See
Form Designer Component Events
.
In This Section
Form Designer Component Properties
Form Designer Form Properties
Form Designer Label Properties
Form Designer Edit Properties
Form Designer Number Edit Properties
Form Designer Spin Edit Properties
Form Designer Date Edit Properties
Form Designer Time Edit Properties
Form Designer Memo Properties
Form Designer HTML Memo Properties
Form Designer Data Combo Properties
Form Designer Surrogate Data Combo Properties
Form Designer Surrogate Edit Data Combo Properties
Form Designer Period Lookup Combo Properties
Form Designer Drop Down List Properties
Form Designer Check Box Properties
Form Designer Panel Properties
Form Designer Group Box Properties
Form Designer Bevel Properties
Form Designer Scroll Box Properties
Form Designer Button Properties
Form Designer Speed Button Properties
Form Designer Image Properties
Form Designer Page Control Properties
Form Designer List Grid Properties
Form Designer Edit Grid Properties
Form Designer Form Navigator Properties
Form Designer Grid Navigator Properties
Form Designer Grid Scroller Properties
Form Designer Table Properties
Form Designer Memory Table Properties
Form Designer Timer Properties
Form Designer Folder Dialog Properties
Form Designer File Open Dialog Properties
Form Designer File Save Dialog Properties
Form Designer Graph Properties
Form Designer Link Label Properties
Form Designer Splitter Properties

---

## Form Designer Component Events

Source: https://accredo.co.nz/webhelp/FDComponentEvents.htm

Form Designer Component Events
Navigator > Setup > Form Designer > Layout tab > Events tab
Components in the Form Designer have events, depending on the component type. These are listed in the Component panel, Events tab.
Click
Lookup Code
beside an event to locate the Sub procedure in the Code tab. If a Sub procedure has not been assigned a Sub will automatically be appended and assigned to the event. The naming convention is Event name if the component is "Self", or ComponentName_EventName.
Click
to select from the available Sub procedures.
See also
Events Sequences
to see the order events are triggered in relation to other events.
Event
Description
AfterSave
Occurs after a record is saved to the table.
Sub AfterSave(Sender as Object)
AfterScroll
Occurs when the currently selected row in a table or memory table is changed.
Sub AfterScroll(Sender as Object)
BeforeClose
Occurs before a form or live edit grid is closed.
Sub BeforeClose(Sender as Object)
BeforeSave
Occurs before a record is saved to the table.
Sub BeforeSave(Sender as Object)
FieldAfterChange
Occurs after a field is changed when a row is being posted to a table. Field Events are dynamic events that are based on fields in the table, they are only available for Custom tables and Memory tables.
Sub FieldAfterChange(Sender as Object, OldValue as Object)
FieldBeforeChange
Occurs before the field is changed when a row is being posted to the table. You can replace the value for the field by setting the NewValue parameter. Field Events are dynamic events that are based on fields in the table, they are only available for Custom tables and Memory tables.
Sub FieldBeforeChange(Sender as Object, ByRef NewValue as Object)
OnActivate
For the Form object, occurs when a form is activated.
Sub OnChange(Sender as Object)
OnAfterChange
Occurs after the text for the edit component has changed.
Sub OnAfterChange(Sender as Object, OldValue as Object, NewValue as Object)
OnBeforeChange
Occurs before the text for the edit component is about to change. You can replace the value for the Edit component by setting the NewValue parameter.
Sub OnBeforeChange(Sender as Object, OldValue as Object, ByRef NewValue as Object)
OnBtnClick
Occurs when the user clicks on a button in a grid navigator. The button identifier for use in the code is the name listed in the Properties Tab > Visible Buttons.
Set the Handled parameter to
true
to stop further processing of the button click.
Sub OnBtnClick(Sender as Object, Button as Number, ByRef Handled as Boolean)
OnCalcCellColors
Changes the colours of the grid cells when a cell is calculated. Only available for grids.
Sub OnCalcCellColors(Sender as Object, Field as Object, Row as Number, Highlight as Boolean, CellFont as Object, ByRef BackColor as Number)
OnCanDelete
OnCanInsert
OnCanModify
These memory table events can be used to control per row behavior. For example, if a row can be deleted based on some criteria, this logic can be added to the OnCanDelete event. Same with the OnCanModify and OnCanInsert. FD grid Navigators also fire these events based on keyboard shortcuts e.g when F3 on a grid is pressed or the Delete button is clicked, then the OnCanDelete event is triggered for the memory table bound to the grid. The Afterscroll event also triggers these events.
All three methods have the following signature
Method(Sender as Object, ByRef Allowed as Boolean)
e.g. If a memory table row can be deleted, provided it's inactive column is set to false, then the event implementation would look like this
Sub OnCanDelete(Sender as Object, ByRef CanDelete as Boolean)
CanDelete = MemTable.Inactive = False
End Sub
e.g.2. If Insert within the grid is only allowed based on a global variable called InsertMode
Sub OnCanInsert(Sender as Object, ByRef CanInsert as Boolean)
CanInsert = InsertMode
End Sub
Since these events get triggered so often, it is a good idea to keep the logic as simple as possible to avoid painting issues and flicker.
OnChange
Occurs when the text for the edit component may have changed.
Sub OnChange(Sender as Object)
OnClick
Occurs when the user clicks the component.
Sub OnClick(Sender as Object)
OnClose
Occurs when the form closes.
Sub OnClose(Sender as Object)
OnCloseQuery
Occurs when the form attempts to close. Set the CanClose parameter to
true
to allow the Form to close.
Sub OnCloseQuery(Sender as Object, ByRef CanClose as Boolean)
OnCreate
Occurs when the form is created.
Sub OnCreate(Sender as Object)
OnDblClick
Occurs when the user double-clicks the left mouse button when the mouse pointer is over the component.
Sub OnDblClick(Sender as Object)
OnDeactivate
For the Form object, occurs when a form is deactivated.
Important
: Do not make any changes to the focus in an OnDeactivate event. Focus must be controlled by the event.
Sub OnDeactivate(Sender as Object)
OnDestroy
Occurs when the form is destroyed.
Sub OnDestroy(Sender as Object)
OnEnter
Occurs when a component receives the input focus.
Sub OnEnter(Sender as Object)
OnExit
Occurs when the input focus shifts away from one component to another.
Sub OnExit(Sender as Object)
OnNewRecord
Occurs after a new record has been added to the table.
Sub OnNewRecord(Sender as Object)
OnNewValueEntered
Occurs when a new value (text) is entered into a drop down list.
Sub OnNewValueEntered(Sender as Object)
OnShow
Occurs when the form is shown.
Sub OnShow(Sender as Object)
OnTabChange
Occurs after the cursor position has changed from one row to another.
Sub OnTabChange(Sender as Object)
OnValueEntered
Occurs when a value (text) is set in a combo.
Sub OnValueEntered(Sender as Object)

---

## Form Designer Component Methods

Source: https://accredo.co.nz/webhelp/FormDesignerComponentMethods.htm

Form Designer Component Methods
Navigator > Setup > Form Designer > Code tab
Components each have different methods available to them. Methods available are listed under
Objects
> [Component Name] > Methods.
The following methods are available to all Component types:
Method
Description
GetPropertyValue
Returns the value of a property of the component. For example:
btnButton1.GetPropertyValue("Caption")
will return the Caption of button component btnButton1.
PropertyType
Returns the type of a property for the component. For example:
btnButton1.PropertyType("Caption")
will return "String", as the Caption is a string.
SetPropertyValue
Sets the value of a property of the component. For example:
btnButton1.SetPropertyValue("Caption", "Click")
will set the caption of button component btnButton1 to
Click
.
The following methods are available to most Component types:
Method
Description
SetFocus
Set the focus to the component. For example:
btnButton1.SetFocus
will set the focus to component btnButton1.
ShowErrorHint
Show an error hint for the component. Specify the hint.
ShowStatusHint
Show a status hint for the component. Specify the hint.
Other methods are available to specific component types:
Component
Method
Description
Drop Down List
AddItem
Add an item to a drop-down list.
Drop Down List
AddStrings
Add items from a
StringList
to a drop-down list.
Drop Down List
Clear
Clears the list or memo text.
Button
Click
Triggers the OnClick event for the button.
Edit Grid
CreateDefaultEditors
Create default editors for each field in the grid, based on the field type.
File Open Dialog, File Save Dialog, Folder Dialog
Execute
Displays the dialog modally, and returns
True
if the user did not select Cancel.
Drop Down List
RemoveItem
Remove an item from a drop-down list.
Form
ScaleToForm
Returns the number of pixels at application scaling.
See also
Form Designer Combo Methods
,
Graph Methods
,
Memo Methods
and
Table Methods
.
In This Section
AddItem
AddStrings - Drop Down List Method
BringToFront
Click
Close - Method
CreateDefaultEditors - Input Grid Method
ExpandNavigator
ForceWindowToForeground
GetPropertyValue - Method
Hide
MinimiseNavigator
PropertyType - Method
RemoveItem
ScaleToForm
SendToBack - Method
SetFocus
SetPropertyValue - Method
Show
ShowErrorHint - Method
ShowFieldErrorHint - Method
ShowModal
ShowStatusHint
See Also
Form Designer Code tab

---

## Form Designer Component Order

Source: https://accredo.co.nz/webhelp/FormDesignerComponentOrder.htm

Form Designer Component Order
Navigator > Setup > Form Designer > Layout tab > Component Order Window
Select to show or hide the Component Order from the Form Designer > Component > Show / Hide Component Order menu option.
This shows where components are situated in relation to other components. The hierarchical relation between components is shown. This allows you to see where components are positioned on other components.
This is very useful when designing High DPI forms and when using splitters between components. You can drag and drop components in the Component Order window to relocate components.
When you click on a component in the Component Order window, the component will become selected, and its properties will be displayed in the Component Property list.
Toolbar
Expand all
(Shift+F4)
Expand all component hierarchies in the Component Order window.
Collapse all
(Shift+F3)
Collapse all component hierarchies in the Component Order window.
Refresh
(F5)
Reloads changes made on the form to synchronise the order shown.
See Also
Form Designer Component Palette

---

## Form Designer Component Palette

Source: https://accredo.co.nz/webhelp/FDComponent_Palette.htm

Form Designer Component Palette
Navigator > Setup > Form Designer > Layout tab
Components are also available from the Form Designer > Component menu.
Each button on the Component Palette represents a component with properties that can be edited using Form Designer
Component Editor
. Click the Component button or select the component from the Component menu, then click in the Design Window to insert the selected component. The top left corner of the component will be positioned where you click the mouse.
Components have properties, that are shown in the Component section of the Form Designer. See
Form Designer Component Properties
for a list of properties common to all components. To see properties specific to a component type, click the name of the component type. Each component has
Events
that can trigger code sub-routines to run.
See also the
Form
properties for properties of the form itself.
Go to Form Designer > Component >
Show Component Order
to display the
Component Order
. This shows where components are situated in relation to other components. This is very useful when designing High DPI forms and when using splitters between components. You can drag and drop components in the Component Order window to relocate components.
See the
FD Dashboard Tutorials
for examples of how components can be used in forms.
Select Pointer
Use the pointer to select and move objects in the Design Window.
Label
Shows text the user cannot select or manipulate, such as title text or control labels.
Edit
An editing area where the user can enter or modify a single line of text.
Number Edit
An edit component where the user can enter numbers.
Spin Edit
An edit component where the user can enter numbers, with a spinner to increase or decrease the number.
Date Edit
An edit component where the user can enter or select a date.
Time Edit
An edit component where the user can enter or select a time.
Memo
An editing area where the user can enter or modify multiple lines of text.
HTML Memo
Display HTML read-only.
Data Combo
An edit box that is linked to an Accredo table. The user can enter a Code that is in the table, or select from records in the table. The Code will be displayed.
Surrogate Data Combo
A drop down combo linked to an Accredo table, where the record ID does not clearly reflect the item, so the Name rather than the ID is displayed. Tables available are Periods, Years, AR Contacts, AP Contacts and AR Delivery Addresses. The user cannot type in the combo, but can select an item.
The Value property of the combo returns the record ID, and the Name property returns the name.
Surrogate Edit Data Combo
Similar to a Surrogate Data Combo, but the user can enter or select an item. This is only available for the Country table.
The Value property of the combo returns the record ID, and the Name property returns the name.
Period Lookup Combo
Similar to a Surrogate Data Combo, this is used to display Periods in an Edit Grid.
When a Surrogate Data Combo is used in an edit grid, it displays the Record ID, rather than the Name of the selection. The Period Lookup Combo will display the Name of the period selected.
Drop Down List
A combined list box and edit box. You can enter a list of
Items
.
The user can select items from a drop-down list, or can type in another entry. You can set the
Style
to
dsDropDownList
to disable the edit capability, so the user must select an item from the list.
Check Box
An option that the user can toggle between Checked or Unchecked. Use check boxes to show a group of choices that are not mutually exclusive.
Panel
A container that can hold other components on a form. This can be used for grouping or for decoration.
Group Box
Similar to a Panel, a box with a caption that can hold other components on a form. This can be used to subdivide a form by function.
Bevel
Similar to a Panel, an indented container that can hold other components on a form. This can be used for grouping or for decoration.
Scroll box
Similar to a Panel, a container that can hold other components, that automatically shows scroll bars when necessary.
Button
A button that you can set to trigger actions when clicked.
Speed Button
A button that has an image but no text. Speed buttons can be grouped together within a panel to create a tool palette.
Image
An image, such as a bitmap, icon, or metafile.
Page Control
A container that can have multiple tabbed pages. Use this control to define multiple logical pages or sections of information within the same window.
To add
Tab Sheets
to a Page Control, right-click in a Page Control component, then select
New Sheet
from the context menu.
List Grid
A grid used to display table data.
Edit Grid
A grid that displays table data and allows data to be edited. Edit Grids can only be used for Custom tables and Memory tables.
To set Editors for the fields in the grid, you can:
Right-click in the grid then select
Create Default Editors
to add default editors - OR -
Hold down the
Ctrl
key, then add a component to the grid in the field, to set a component as a field editor.
Form Navigator
Adds a navigator bar to the form. You can select which buttons to display on the navigator.
Grid Navigator
Adds a navigator bar to a grid. You can select which buttons to display on the navigator. Standard grid buttons are selected by default.
Grid Scroller
Adds a scroll bar to a grid, to allow the user to scroll records. All available buttons are selected by default.
Table
A table source. This can be an Accredo table or a Custom table. The table is not displayed on the form, but can be linked to other components. After you select the
TableName
, double-click the table, or right-click then select
Field Editor
to edit the fields in the table.
Memory Table
A custom table source where you define the fields. This is not displayed on the form, but can be linked to other components. To customise the memory table, double-click the memory table, or right-click then select
Memory Table Designer
.
Timer
A timer that fires the
onExecute
event at regular intervals. Set the interval property in milliseconds to define the interval.
Folder Dialog
A non-visible component used to let the user open a dialog box to browse for a folder. In the code, use:
{FolderName}.Execute
The
Execute
method returns a boolean value, True if a folder was selected, or False otherwise.
File Open Dialog
A non-visible component used to let the user open a dialog box to browse for a file. In the code, use:
{FileOpenName}.Execute
The
Execute
method returns a boolean value, True if a file was selected, or False otherwise.
File Save Dialog
A non-visible component used to let the user open a dialog box to save a file. In the code, use:
{FileSaveName}.Execute
The
Execute
method returns a boolean value, True if files were selected, or False otherwise.
Graph
A graph that can be used to show data from a Table or Memory Table.
Link Label
A label that can be clicked to initiate an action, such as a hyperlink. The font can change when the mouse is hovered over the link label. This can be used as an alternative to a button.
Splitter
A splitter control that can be placed between aligned controls to divide a form into several panes, each containing multiple controls.
In This Section
Form Designer Component Order

---

## Form Designer Data Combo Properties

Source: https://accredo.co.nz/webhelp/DataComboFDComponent.htm

Form Designer Data Combo Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Data Combo Components:
BorderStyle
Set the border style for the combo, to
Single
or
None
.
ButtonsAvailable
Click the + button to expand. Select which buttons will be available on the data combo from:
Lookup
Filter
Display Inactive -
If selected the
IndexName
property must be left empty since the control will dynamically select the index when the button is toggled. See below for hint on using with Memory tables.
Display Inactive Menu
-
Show Inactive Records
will be available in the right-click context menu.
Memo
Open
Word Lookup
Link
DittoSibling
You can select another combo to be paired with this component. When components are paired, the user can press
Ctrl
+
'
to copy the value of the paired component into the component.
Note: Both components must have the same
LookupSource
.
This can be useful where you have related components, such as
Period From
and
Period To
fields, or
Date From
and
Date To
fields.
ExactAllowEmpty
When
True
, the Data Combo is allows to be empty. When
False
, the Data Combo must have a value.
ExactMatch
When
True
, text entered must exactly match a value in the drop down list.
Hint
The Hint text to be displayed when the mouse hovers over the component.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
IndexName
Select a field to index the table. This determines the order of the drop-down list.
Note: Leave empty if
Display Inactive
button is selected so that the index can be set dynamically when the button is toggled. If
IndexName
is set this will override the Display Inactive button.
LabelCaption
The text to be displayed beside the Combo box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
LookupFilter
You can enter a filter to apply when data is added to the drop-down list.
LookupSource
Select a table to populate the drop-down list from.
LookupType
Select to lookup from a
Normal
,
Custom
or
Memory
table.
ReadOnly
When
True
, the user cannot edit the component on the form.
ShowAlternateLookup
When
True
, the Alternate Lookup will be shown when the list is dropped down. You can use
Alt+F2
to display the normal lookup.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the component.
Visible
When
True
, the component will be displayed on the form.
Hint: For Combos backed by Memory Tables, the
Display Inactive
button in
ButtonsAvailable
will only work if the memory table has two indexes: one called "
Primary
Key", and one called "Active
Primary
Key", where "Active
Primary
Key" is a key on a boolean field called "Inactive". At design time, the combo and the memory table must use the non-active index in the IndexName property.
For example, if the Primary Key is CustomerCode, then Index1 could be "Customer" and Index 2 could be "ActiveCustomer".

---

## Form Designer Date Edit Properties

Source: https://accredo.co.nz/webhelp/DateEditFDComponent.htm

Form Designer Date Edit Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Date Edit Components:
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
Hint
The Hint text to be displayed when the mouse hovers over the edit box.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
LabelCaption
The text to be displayed beside the Edit box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the edit box.
Visible
When
True
, the edit box will be displayed on the form.

---

## Form Designer Design Window

Source: https://accredo.co.nz/webhelp/FDDesignWindow.htm

Form Designer Design Window
Navigator > Setup > Form Designer > Layout tab
Place components in the Design Window, view and edit their properties in the
FD Component Editor
.
Placing Components
To place a component in the Design Window:
Select the component from the Component Palette or the Component menu.
Click the desired position in the Design Window.
Once the component is placed, set its properties from the Property tab.
Position and Size properties can be changed by dragging the component handles.
Selecting Components
in the Design Window
Click to select a component. To select multiple components, hold down Ctrl while selecting. If multiple components are selected, the mouse handles appear grey, internal to the components.
Select multiple components by region. To do this, hold down
Shift
, click outside a component, then drag to create a rectangle covering the components. Release the mouse button and the enclosed components are selected.
Note: A
Preference
determines whether you use
Shift
+
Drag
for Select by Region and
Ctrl
+
Click
for Multi Select for Components, or
Ctrl
+
Drag
for Select by Region and
Shift
+
Click
for Multi Select for Components.
Press Ctrl+A
to select all components on a form. This is also available from the right-click menu.
Moving Components
To move components you can either:
- drag them. You can multi-select components and move them all. Selected components can be "nudged" 1 pixel by holding down
Ctrl
and pressing the
Up
,
Down
,
Left
or
Right
arrow key.
- use the right-click Context menu, then select Move.
Resizing Components
If a single component is selected, resize it by dragging the handles. To set a number of components to the same size, multi-select and set the size on the Properties tab.
Aligning Components
Right-click can be used to align components. Select the component and right-click.
Form Designer Context Menu
To access the Form Designer Context Menu, right-click in the Form Designer design window. Options available in the context menu are:
Bring To Front
Bring the component(s) to the front, in front of other components.
Send To Back
Send the component(s) to the back, behind other components.
Align...
Available when more than one component is selected. Opens the
Alignment
window to align the selected components to each other.
Cut
(
Ctrl+X
)
Cut selected component(s) to the clipboard.
Copy
(
Ctrl+C
)
Copy selected component(s) to the clipboard.
Paste
(
Ctrl+V
)
Paste previously cut or copied component(s) from the clipboard.
Delete
(
Del
)
Delete selected component(s).
Select All
(
Ctrl+A
)
Select all components on the form.
Move...
Opens the
Move Components
window to move the component(s) by a set amount.
In This Section
Form Designer Alignment
Form Designer Move Components

---

## Form Designer Drop Down List Properties

Source: https://accredo.co.nz/webhelp/DropDownListFDComponent.htm

Form Designer Drop Down List Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Drop Down List Components:
Border Style
Set the border style for the component, to
Single
or
None
.
Hint
The Hint text to be displayed when the mouse hovers over the component.
Ignore Grid Parent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
Items
Enter the items to be included in the drop-down list.
Label Caption
The text to be displayed beside the Edit box.
Label Visible
When
False
, the
Label Caption
will not be displayed.
Label Width
Set the width of the
Label Caption
.
Max Length
Set the maximum number of  characters that can be entered in the box.
Read Only
When
True
, the user cannot edit the component on the form.
Sorted
When
True
, items in the list are sorted alphabetically.
Style
Select the style from:
Drop Down
- text can be entered in the box.
Drop Down List
- text cannot be entered.
Tab Order
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
Tab Stop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the component.
Visible
When
True
, the component will be displayed on the form.

---

## Form Designer Edit Grid Properties

Source: https://accredo.co.nz/webhelp/EditGridFDComponent.htm

Form Designer Edit Grid Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
To set Editors for the for fields in the grid, you can:
Right-click in the grid then select
Create Default Editors
from the context menu to add default editors - OR -
Hold down the
Ctrl
key, then add a component to the grid in the field, to set a component as a field editor.
Right-click and select
Open Table
from the context menu, to open the Table Field Editor for the Table linked to the grid.
The following properties are available for Edit Grid Components:
ActiveColumn
The default active column.
ActiveFocused
When
True
, the active cell will display highlighted with the
Active Row Color
.
ActiveRowColor
The colour to highlight the active row in the grid, if
ActiveFocused
is set to true. Click
Open Color Dialog
(F2)
to select the
colour
.
AutoPost
When
True
, when a user makes changes in the grid, the changes are automatically posted.
Hint
The Hint text to be displayed when the mouse hovers over the component.
ScrollBars
Set whether scroll bars are available on the component. Select from
None
,
Horizontal
,
Vertical
or
Both
.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Table
Select a table to display in the grid.
Edit Grid Context Menu
To access the Edit Grid Context Menu, right-click on the page control. Options available in the context menu are:
Create Default Editors
Adds default editors for each field in the grid.
Delete All Field Editors
Deletes all field editors in the grid.

---

## Form Designer Edit Properties

Source: https://accredo.co.nz/webhelp/EditFDComponent.htm

Form Designer Edit Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Edit Components:
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
CharCase
Select the character case for text in the edit box from
Normal
,
Upper Case
or
Lower Case
.
Hint
The Hint text to be displayed when the mouse hovers over the edit box.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
LabelCaption
The text to be displayed beside the Edit box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
MaxLength
Set the maximum number of characters that can be entered in the box.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the edit box.
Visible
When
True
, the edit box will be displayed on the form.

---

## Form Designer File Open Dialog Properties

Source: https://accredo.co.nz/webhelp/FileOpenFDComponent.htm

Form Designer File Open Dialog Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for File Open Dialog Components:
DefaultExt
The default file extension to be opened or saved.
FileName
The default file name to be opened or saved.
Filter
The list of file filters, with a description and file type, separated by pipes, for example:
"JPG Files (*.jpg)|*.jpg|PNG Files (*.png)|*.png|All Files|*.*"
FilterIndex
Sets the default file filter when the dialog is first opened.
InitialDir
Enter the initial directory to default to.
Options
Click + to expand. Select options for the File dialog:
ofOverwritePrompt
- if the file is an existing file, the user will be prompted whether to overwrite the file.
ofNoChangeDir
- prevents the dialog from changing the current directory when the user presses the OK button.
ofAllowMultiSelect
- allows the user to select more than one file.
ofPathMustExist
- restricts the user to selecting a path that already exists.
ofFileMustExist
- restricts the user to selecting a file that already exists.
ofCreatePrompt
- if the file entered doesn't exist, prompts the user on whether to create the file.
ofNoReadOnlyReturn
- prevents the user for opening or saving a read-only file. An error message is shown.
ofNoDereferenceLinks
- if a shortcut file is selected, the
FileName
is set to the name of the shortcut itself, rather than the linked file.
ofDontAddToRecent
- does not add the file name to the list of recent files.
Title
The title displayed on the dialog.

---

## Form Designer File Save Dialog Properties

Source: https://accredo.co.nz/webhelp/FileSaveFDComponent.htm

Form Designer File Save Dialog Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for File Save Dialog Components:
DefaultExt
The default file extension to be opened or saved.
FileName
The default file name to be opened or saved.
Filter
Filter by different types of files, such as image files (*.jpg) or all files (*.*).
FilterIndex
Sets the default file filter when the dialog is first opened.
InitialDir
Enter the initial directory to default to.
Options
Click + to expand. Select options for the File dialog:
ofOverwritePrompt
- if the file is an existing file, the user will be prompted whether to overwrite the file.
ofNoChangeDir
- prevents the dialog from changing the current directory when the user presses the OK button.
ofPathMustExist
- restricts the user to selecting a path that already exists.
ofNoReadOnlyReturn
- prevents the user for opening or saving a read-only file. An error message is shown.
ofNoDereferenceLinks
- if a shortcut file is selected, the
FileName
is set to the name of the shortcut itself, rather than the linked file.
ofDontAddToRecent
- does not add the file name to the list of recent files.
Title
The title displayed on the dialog.

---

## Form Designer Folder Dialog Properties

Source: https://accredo.co.nz/webhelp/FolderFDComponent.htm

Form Designer Folder Dialog Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Folder Dialog Components:
Directory
Enter the default directory for the folder.
Options
Click + to expand. Select options for the Folder Dialog:
bfFileSysDirsOnly
- folders available are file system folders (they are files, directories or root directories).
bfDontGoBelowDomain
- network folders below the domain level are not available.
bfStatusText
- when the mouse is hovered over a folder, displays the folder status.
bfFileSysAncestors
- folders available are either file system folders, or contain at least one descendent that is a file system folder.
bfBrowseIncludeFiles
- the browse box displays files as well as folders.
bfNewUI
- the
Make New Folder
button will be displayed.
bfShowPathInStatusArea
- displays the path in the status area.
bfScreenCenter
- when
True
, display the Browse window in the center of the screen.
bfParentCenter
- when
True
, display the Browse window in the centre of the parent container.
Text
Enter any text to be displayed in the Folder Dialog.
Title
Title shown on the Dialog window.

---

## Form Designer for High DPI

Source: https://accredo.co.nz/webhelp/FormDesignerForHighDPI.htm

Form Designer for High DPI
When High DPI Aware is selected in
Preferences - Display tab
and the application size is greater than 100%, forms will be displayed differently to how they are shown at 100%. When designing forms, it is important to consider the way forms will be displayed at a larger size.
Scroll Box
and
Splitter Bar
components can be used to ensure entire forms can be seen at a larger size.
Scroll boxes can be placed on forms to ensure entire areas can be scrolled to. Place a scroll box on a form or panel, then set the
Alignment
to
alClient
to fill the form or panel it is placed on. When components are placed on the scroll box, they will always be accessible via the scroll bar.
You can also use Splitter Bars to separate panels or scroll boxes. Splitter bars allow you to resize areas on a form, so you can view the components you need at any screen size. Place a container component, such as a Scroll Box, with Alignment set to
alLeft
or
alTop
. Then place a Splitter Bar after the component, with the same alignment. Next place another container component after the Splitter Bar, with the same Alignment or with the Alignment set to
alClient
. Alignment of
alClient
will fill the remaining space. When you run the form, you will be able to resize the container components by clicking and dragging the Splitter Bar. When forms are displayed at a higher size than 100%, information can be cut off. Using Splitter Bars allows you increase the size of a container component to show more information.
Note: The order you place container components and splitter bars is very important. Splitter bars can be linked to the component placed immediately before the splitter is placed. Make sure the parent component for the splitter and the container components is selected when you place a splitter bar.
See Also
Form Designer

---

## Form Designer Form Navigator Properties

Source: https://accredo.co.nz/webhelp/FormNavigatorFDComponent.htm

Form Designer Form Navigator Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Form Navigator Components:
AlternateColour
When
True
, the Alternate colour will be used for the navigator background. When
False
, the parent colour will be used.
Flat
When
True
, buttons on the Navigator are displayed flat. When
False
, buttons are displayed raised.
Hint
The Hint text to be displayed when the mouse hovers over the component.
HookControl
You can select a component to link the Navigator to, so when the user selects options on the Navigator, they will be applied to the component.
Layout
Select to display the navigator horizontally or vertically.
MenuButtonVisible
When
True
, the Expand Toolbar button will be displayed.
Visible
When
True
, the component will be displayed.
VisibleButtons
Click + to expand. Select the buttons to be displayed on the navigator or scroller.
Note that if the
Customise
button is used when a form is running from Form Designer, changes will not be saved. Customisations will only be saved when the form is deployed.

---

## Form Designer Form Properties

Source: https://accredo.co.nz/webhelp/FormFDComponent.htm

Form Designer Form Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Form Components:
BorderIcons
Click the + button to expand.
biSystemMenu
- when True the System Menu icon will be shown on the form.
biMinimize
- when True the minimise button will be shown on the form.
biMaximize
- when True the maximise button will be shown on the form.
BorderStyle
Set the border style for the form to
None
,
Single
,
Sizeable
or
Dialog
.
BorderWidth
The width of the border.
Caption
The text to be displayed on the form.
Note: If the Caption starts with the
Company Name
, this will not be displayed in the Accredo Window drop-down menu.
ClientHeight
The height of the client window.
ClientWidth
The width of the client window.
Color
The colour to fill the background of the form. Click
Open Color Dialog
(F2)
to select the
colour
.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the form.
Padding
Click the + button to expand. Set padding for the
Bottom
,
Left
,
Right
and
Top
of the form.
SaveSizeName
The name of the form to set the size from. Defaults to the file name when the form is saved.
Visible
When
True
, the form will be visible. When
False
, the form will not be visible.
WindowState
The state the form will run in. Select from
Normal
,
Minimised
or
Maximised
.

---

## Form Designer Graph Editor

Source: https://accredo.co.nz/webhelp/FDGraphEditor.htm

Form Designer Graph Editor
Navigator > Setup > Form Designer > Layout tab >
Graph Component
>
Double-click
- OR -
Navigator > Setup > Form Designer > Layout tab >
Graph Component
>
Right-click
> Graph Editor
The FD Graph Editor is used to select the fields to include in the graph.
Field Name
Name of a field in the linked table to be displayed in the graph.
Display Label
The Label to be displayed for the Field.
Show Key
Selected
, displays the values at key points on the graph.
Show Key Border
Selected
, displays borders around key values.
Key Font
Controls the font details used for series keys.
Brush Color
The colour used to show the field in the graph.
Brush Style
A brush style determines the pattern used to fill field represented in the graph. Predefined styles are,
bsSolid
- fill with solid colour
bsClear
- no fill
bsHorizontal
- fill with horizontal lines
bsVertical
- fill with vertical lines
bsFDiagonal
- fill with diagonal lines form top left to bottom right
bsBDiagonal
- fill with diagonal lines from bottom left to top right
bsCross
- fill with a horizontal and vertical line cross pattern
bsDiagCross
- fill with a diagonal line cross pattern
Pen Color
The colour used to outline the field in the graph.
Pen Style
The type of line drawn as the boundaries of the field in the graph.
psSolid
- a solid line
psDash
- a dashed line
psDot
- a dotted line
psDashDot
- a line of alternating dashes and dots
psDashDotDot
- a line of alternating dashes and pairs of dots
psClear
- no line
Pen Width
The width in millimetres of the boundary line for the shape.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert an item at the selected line.
Move
(Ctrl+Up) (Ctrl+ Down)
Select an item and move it higher or lower on the list.
Delete
(F3)
Delete the selected item.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Buttons
Save
(F9)
Saves the graph.
Cancel
(Esc)
Close the form without saving any changes.

---

## Form Designer Graph Methods

Source: https://accredo.co.nz/webhelp/FormDesignerGraphMethods.htm

Form Designer Graph Methods
Navigator > Setup > Form Designer > Code tab
Components each have different methods available to them. Methods available are listed under
Objects
> [Component Type] > [Component Name] > Methods.
See also
Form Designer Component Methods
for methods available to all component types.
The following methods are available to Graph Components:
Component
Method
Description
Graph
AddField
Add a field to the graph or table definition.
Graph
AddPieColor
Add a colour to a pie graph.
Graph
ClearFields
Clears all the field definitions.
Graph
FindField
Returns the field if found, otherwise returns null.
Graph
Print
Displays options for printing the graph.
Graph
RefreshData
Reloads the graph with current data.
Graph
RemoveField
Removes a field from the graph.
Graph
ResetPieColors
Resets a pie graph to the default colours.
In This Section
AddField - Memory Table Builder Method
AddPieColor
ClearFields - Memory Table Builder Method
FindField
Print
RefreshData
RemoveField
ResetPieColors
See Also
Form Designer Code tab

---

## Form Designer Graph Properties

Source: https://accredo.co.nz/webhelp/GraphFDComponent.htm

Form Designer Graph Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
Graph component displays series of numeric data in graphical format. Accredo provides Bar, Line or Pie graph styles.
Double-click a graph, or right-click and select
Graph Editor
from the context menu, to display the
Graph Editor
, which allows selection and customisation of fields in the graph.
The following properties are available for Graph Components:
BackWall
When
True
, the back wall is displayed.
BackWallColor
The colour to fill the back wall of the graph. Click
Open Color Dialog
(F2)
to select the
colour
.
BackWallStyle
The style to fill the back wall of the graph.
bsPlain
- Fill with the
BackWallColor.
bsGradient
- Fill with gradually changing colour, from white to the
BackWallColor
, in the direction selected in
GradientDirection
.
BackgroundColor
The colour to fill the background of the graph. Click
Open Color Dialog
(F2)
to select the
colour
.
BarOrientation
For Bar Graphs, select the orientation of the graph.
gboVertical
- The bars will be displayed vertically.
gboHorizontal
- The bars will be displayed horizontally.
BottomAxis
When
True
, the bottom axis is displayed.
BottomAxisPosition
The position of the bottom axis relative to the bottom of the chart, specified as a percentage. For example, 50 will position the bottom axis in the middle of the chart, half way up.
BottomAxisValuesFormat
Format applied to the values displayed on the bottom axis. e.g.
graphGraph1.BottomAxisValuesFormat = "Amount;Amount;"""
BottomWall
When
True
, the bottom wall is displayed. Only apparent in 3D mode.
GradientDirection
The gradient direction used to fill the back wall of the graph, when the
BackWallStyle
is
bsGradient
.
gdTopBottom
- fill with the selected colour at the top of the graph, gradually changing to white at the bottom.
gdBottomTop
- fill with the selected colour at the bottom of the graph, gradually changing to white at the top.
gdLeftRight
- fill with the selected colour at the left of the graph, gradually changing to white on the right.
gdRightLeft
- fill with the selected colour at the right of the graph, gradually changing to white on the left.
gdFromCenter
- fill with white at the center, gradually changing to the selected colour at the corners.
gdFromTopLeft
- fill with the selected colour at the top left of the graph, gradually changing to white at the bottom right.
gdFromBottomLeft
- fill with the selected colour at the bottom left of the graph, gradually changing to white at the top right.
gdRadial
- fill with white at the center, gradually changing to the selected colour at the corners in a circular transition.
gdDiagonalUp
-  fill with the selected colour at the top right of the graph, gradually changing to white at the bottom left.
gdDiagonalDown
-  fill with the selected colour at the bottom right of the graph, gradually changing to white at the top left.
Hint
The Hint text to be displayed when the mouse hovers over the component.
KeyCalloutLength
The length of the space between the top of each bar and the bottom of the key border, if keys are shown (selected in
FD Graph Editor
).
This is only applicable to Bar Graphs.
LabelsAngle
The degrees to rotate the X-axis labels. To display labels at a 90 degree angle, enter
90
.
LeftAxis
When
True
, the left axis is displayed.
LeftAxisPosition
The position of the left axis relative to the left hand side of the chart, specified as a percentage. For example, 50 will position the left axis in the middle of the chart, half way in from the left.
LeftAxisValuesFormat
Format applied to the values displayed on the left axis. e.g.
graphGraph1.LeftaxisValuesFormat = "Amount;Amount;"""
LeftWall
When
True
, the left hand wall is displayed. Only applies when
View3D
is
True
.
RightWall
When
True
, the right side wall is displayed. Only applies when
View3D
is
True
.
ShowAverage
When
True
, displays the average amounts across the graph.
This is only applicable to Bar Graphs and Line Graphs.
ShowGridLines
When
True
, displays gridlines on the back wall of the graph.
This is only applicable to Bar Graphs and Line Graphs.
ShowLegend
When
True
, displays the legend underneath the graph.
Style
Determines the type of graph.
csBar
- Bar Graph.
csLine
- Line Graph.
csPie
- Pie Graph.
Table
The table containing the data to display in the graph.
View3D
When
True
, displays the graph in 3D.
xDataFieldName
The field that will be used to populate the data on the X Axis of the graph.
xLabelFieldName
The field that will be displayed as a label on the X Axis of the graph.
Note: You can change the colours in a Pie Graph by using the
AddPieColor
and
ResetPieColors
methods.

---

## Form Designer Grid Navigator Methods

Source: https://accredo.co.nz/webhelp/FormDesignerGridNavigatorMethods.htm

Form Designer Grid Navigator Methods
Navigator > Setup > Form Designer > Code tab
Components each have different methods available to them. Methods available are listed under
Objects
> [Component Type] > [Component Name] > Methods.
See also
Form Designer Component Methods
for methods available to all component types.
The following methods are available to Grid Navigator Components:
Component
Method
Description
Grid Navigator
SetButtonEnabled
Set button state on the Grid Navigator.
In This Section
SetButtonEnabled

---

## Form Designer Grid Navigator Properties

Source: https://accredo.co.nz/webhelp/GridNavigatorFDComponent.htm

Form Designer Grid Navigator Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Grid Navigator Components:
AlternateColour
When
True
, the Alternate colour will be used for the navigator background. When
False
, the parent colour will be used.
Flat
When
True
, buttons on the Navigator are displayed flat. When
False
, buttons are displayed raised.
Grid(String)
The ListGrid name that the totalling will be for.
Hint
The Hint text to be displayed when the mouse hovers over the component.
HookControl
You can select a component to link the Navigator to, so when the user selects options on the Navigator, they will be applied to the component.
Layout
Select to display the navigator horizontally or vertically.
MenuButtonVisible
When
True
, the Expand Toolbar button will be displayed.
Table
Select the table source for the navigator.
TrackDataSource
When
True
, the grid navigator or scroller will repaint itself as the user scrolls through the grid. This allows the navigator or scroller to enable available buttons and disable unavailable buttons.
Visible
When
True
, the component will be displayed.
VisibleButtons
Click + to expand. Select the buttons to be displayed on the navigator or scroller.
Note: If the
Customise
button is used when a form is running from Form Designer, changes will not be saved. Customisations will only be saved when the form is deployed.
For Customisations to be saved the length of FormName.ComponentName must be <= 60 char.

---

## Form Designer Grid Scroller Properties

Source: https://accredo.co.nz/webhelp/GridScrollerFDComponent.htm

Form Designer Grid Scroller Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Grid Scroller Components:
BevelInner
Select the bevel type for the inner bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BevelOuter
Select the bevel type for the outer bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BevelWidth
Enter the width of the Bevel.
Flat
When
True
, buttons on the Navigator are displayed flat. When
False
, buttons are displayed raised.
Hint
The Hint text to be displayed when the mouse hovers over the component.
Table
Select the table source for the navigator.
TrackDataSource
When
True
, the grid navigator or scroller will repaint itself as the user scrolls through the grid. This allows the navigator or scroller to enable available buttons and disable unavailable buttons.
Visible
When
True
, the component will be displayed.
VisibleButtons
Click + to expand. Select the buttons to be displayed on the navigator or scroller.
Note that if the
Customise
button is used when a form is running from Form Designer, changes will not be saved. Customisations will only be saved when the form is deployed.

---

## Form Designer Group Box Properties

Source: https://accredo.co.nz/webhelp/GroupBoxFDComponent.htm

Form Designer Group Box Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
A Group Box is a box with a caption that can hold other components on a form. This can be used to subdivide a form by function. This is similar to a
Panel
.
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Group Box Components:
Caption
The label for the group box.
CaptionFont
Select the font for the group box caption.
CaptionParentFont
When
True
, sets the Caption Font to the font of the parent container.
Color
The group box colour. Click
Open Color Dialog
(F2)
to select the
colour
.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
Hint
The Hint text to be displayed when the mouse hovers over the component.
Style
Select the Group Box style from:
Standard
Box
Top Only
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.

---

## Form Designer HTML Memo Properties

Source: https://accredo.co.nz/webhelp/HTMLMemoFDComponent.htm

Form Designer HTML Memo Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for HTMLMemo Components:
BevelInner
Select the bevel type for the inner bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BevelKind
Select the type of bevel, form
None
,
Tile
,
Soft
or
Flat
.
BevelOuter
Select the bevel type for the outer bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
Color
The component background colour. Click
Open Color Dialog
(F2)
to select the
colour
.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
HTML
Runtime readonly stringlist property to set HTML to display.
Alternatively the
LoadFromFile
method can be called to set the HTML to display.
ParentColor
When
True
, uses the Color of the parent container.
ParentFont
When
True
, uses the Font of the parent container.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.

---

## Form Designer Image Properties

Source: https://accredo.co.nz/webhelp/ImageFDComponent.htm

Form Designer Image Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Image Components:
AutoSize
When
True
, the component will be automatically resized set to fit the image.
Center
When
True
, the image will be centred in the Image component.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
Hint
The Hint text to be displayed when the mouse hovers over the component.
PicturePath
Select the Image file to be displayed.
Proportional
When
True
, when the image is resized, the height and width will be kept in proportion.
Stretch
When
True
, this image will be stretched to fill the image component.
Transparent
When
True
, the image is displayed as transparent, and other components can be viewed through it. When
False
, the image is displayed as opaque.
Visible
When
True
, the component will be displayed.

---

## Form Designer Label Properties

Source: https://accredo.co.nz/webhelp/LabelFDComponent.htm

Form Designer Label Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to all component types.
The following properties are available for Label Components:
Angle
The angle to display the Caption on. For example, setting the
Angle
to
90
will display the Caption vertically.
AutoSize
When
True
, the size of the component will be automatically adjusted to fit the Caption.
Caption
The text to be displayed on the label.
Color
The component background colour. Click
Open Color Dialog
(F2)
to select the
colour
.
Layout
Set the text alignment of the Caption to the
Top
,
Centre
or
Bottom
of the component.
ParentColor
When
True
, uses the background colour of the parent container.
ParentFont
When
True
, uses the Font of the parent container for the Caption.
Transparent
When
True
, other components can be displayed behind the component. When
False
, components behind this component are not displayed.

---

## Form Designer Link Label Properties

Source: https://accredo.co.nz/webhelp/LinkLabelFDComponent.htm

Form Designer Link Label Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to all component types.
The following properties are available for Link Label Components:
Angle
The angle to display the Caption on. For example, setting the
Angle
to
90
will display the Caption vertically.
AutoSize
When
True
, the size of the component will be automatically adjusted to fit the Caption.
Caption
The text to be displayed on the label.
Color
The component background colour. Click
Open Color Dialog
(F2)
to select the
colour
.
HoverFont
Select the font to display the Caption in when the mouse hovers over the component.
Layout
Set the text alignment of the Caption to the
Top
,
Centre
or
Bottom
of the component.
ParentColor
When
True
, uses the background colour of the parent container.
ParentFont
When
True
, uses the Font of the parent container for the Caption.
Transparent
When
True
, other components can be displayed behind the component. When
False
, components behind this component are not displayed.

---

## Form Designer List Grid Properties

Source: https://accredo.co.nz/webhelp/ListGridFDComponent.htm

Form Designer List Grid Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
Right-click and select
Open Table
from the context menu, to open the Table Field Editor for the Table linked to the grid.
The following properties are available for List Grid Components:
ActiveRowColor
The colour to highlight the active row in the grid, if
ActiveFocused
is set to true. Click
Open Color Dialog
(F2)
to select the
colour
.
AllowTotals
Set
AllowTotals
True
to allow totals on the grid.
GridTotalled
If
AllowTotals
is
True
toggles
Grid totalling on / off.
Hint
The Hint text to be displayed when the mouse hovers over the component.
ScrollBars
Set whether scroll bars are available on the component. Select from
None
,
Horizontal
,
Vertical
or
Both
.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Table
Select a table to display in the grid.
Use the following Method to access Totals in List Grids
Method: GetTotalValue (Number)
Method that takes in a string of the field and returns the total value if the grid has been totalled.
gridListGrid1.GetTotalValue("ExclusiveAmountBs")
Returns null if the grid is not totalled or the field cannot be totalled (e.g. FX Mixed)
Can be tested with the IsNull() method.

---

## Form Designer Memo Methods

Source: https://accredo.co.nz/webhelp/FormDesignerMemoMethods.htm

Form Designer Memo Methods
Navigator > Setup > Form Designer > Code tab
Components each have different methods available to them. Methods available are listed under
Objects
> [Component Type] > [Component Name] > Methods.
See also
Form Designer Component Methods
for methods available to all component types.
The following methods are available to Memo Components:
Component
Method
Description
Memo
Clear
Clears the list or memo text.
Memo
AddLine
Add a line to the memo.
Memo
GetLine
Returns the text on a line number.
Memo
ScrollTo
Scroll to a particular line number.
Memo
SetLine
Set a line in the memo.
Memo
SpellCheck
Activates the Spell Checker for the memo.
In This Section
Clear - Memory Table Builder Method
AddLine
GetLine
ScrollTo
SetLine
SpellCheck
See Also
Form Designer Code tab

---

## Form Designer Memo Properties

Source: https://accredo.co.nz/webhelp/MemoFDComponent.htm

Form Designer Memo Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Memo Components:
BevelEdges
Click the + button to expand. Set which edges of the component to bevel.
BevelInner
Select the bevel type for the inner bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BevelKind
Select the type of bevel, from
None
,
Tile
,
Soft
or
Flat
.
BevelOuter
Select the bevel type for the outer bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
CharCase
Set the character case for text in the component to
Normal
,
Upper Case
or
Lower Case
.
Color
The component background colour. Click
Open Color Dialog
(F2)
to select the
colour
.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
FixedFont
If you want the user to input in a fixed-width font, you can select from the available fixed fonts.
HideSelection
When
False
, if text in the component is selected, it will remain highlighted when the component loses focus.
Hint
The Hint text to be displayed when the mouse hovers over the edit box.
InlineSpellcheck
When
True
, spelling is checked as you type, right-click words for suggested corrections. Spell check options and dictionaries are set in Company Settings - Spellcheck tab.
LineLength
The maximum number of characters that can be entered on a line in the component. You must use a fixed font for this to apply. The Memo component width will be resized to the line length.
Lines
The initial text that will be displayed in the component. Click [...] to open the string list editor.
MaxLength
Set the maximum number of characters that can be entered in the box.
OEMConvert
When
True
, any text entered is converted from ANSI to OEM, then back to ANSI. This ensures all characters can be converted to OEM. This is useful when entering file names when Unicode standards are not enforced.
ParentColor
When
True
, uses the Color of the parent container.
ParentFont
When
True
, uses the Font of the parent container.
ReadOnly
When
True
, the user cannot edit the component on the form.
ReadOnlyColor
The component background colour when ReadOnly. Click
Open Color Dialog
(F2)
to select the
colour
.
The
DefaultReadOnlyColor
function can be used to obtain the Read Only colour as specified in View > Preferences >
Colour
.
ScrollBars
Select scroll bars to be shown on the component. Select from
None
,
Horizontal
,
Vertical
or
Both
.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.
WantReturns
When
True
, users can enter Return characters in the component.
WantTabs
When
True
, users can enter Tab characters in the component.
WordWrap
When
True
, text can wrap over multiple lines.

---

## Form Designer Memory Table Properties

Source: https://accredo.co.nz/webhelp/MemoryTableFDComponent.htm

Form Designer Memory Table Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
Double click a Memory Table, or right-click and select
Memory Table Designer
to open the
FD Memory Table Designer
.
The following properties are available for Memory Table Components:
Active
When
True
, the table is active and can be referenced.
AmountFormatting
Select which amount formatting style to adopt. Styles are set up in
Company Settings - Currency Format tab
.
CloneTable
Select a table to clone. The fields and indexes from the CloneTable will be applied to this table.
IndexName
Select an index for the table.
ReadOnly
When
True
, the Memory Table is read-only and cannot be changed.

---

## Form Designer Move Components

Source: https://accredo.co.nz/webhelp/FDMoveComponents.htm

Form Designer Move Components
Navigator > Setup > Form Designer > Design Window > [Select Component(s)] > Right-click > Move...
Move components horizontally and / or vertically.
Horizontal (mm)
Enter the millimetres to move the component(s) horizontally. Positive values move the components right, negative values move the components left.
Vertical (mm)
Enter the millimetres to move the component(s) vertically. Positive values move the components down, negative values move the components up.
OK
(F9)
Move the component(s) by the amounts specified, and close the window.
Cancel
(Esc)
Discard changes and close the window.

---

## Form Designer Number Edit Properties

Source: https://accredo.co.nz/webhelp/NumberEditFDComponent.htm

Form Designer Number Edit Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Number Edit Components:
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
CalculatorFontSize
The size to display the font in the calculator.
CurrencyCode
You can select from available currencies to make the input a currency figure. The number entered will be displayed as a currency.
Decimals
Enter the maximum number of decimals allowed in the edit box.
Domain
You can select a numeric domain for the edit input. If a
Currency Code
is entered, you are limited to price domains.
Hint
The Hint text to be displayed when the mouse hovers over the edit box.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
LabelCaption
The text to be displayed beside the Edit box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
MinValue
The minimum amount that a user can enter. Make sure to set the
MinMaxCheck
to enforce the minimum limit.
(Only available for Spin Edit components.)
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the edit box.
UseDecimals
When
True
, amounts can contain decimals.
Visible
When
True
, the edit box will be displayed on the form.

---

## Form Designer Objects

Source: https://accredo.co.nz/webhelp/FormDesignerObjects.htm

Form Designer Objects
Navigator > Setup > Form Designer > Code tab >
Objects
(Alt+J)
The following Objects are available to all forms in Form Designer:
Object
Description
Company
Details of the Company, such as name and address.
Self
Details of the form being designed.
User
Details of the current User, such as User Name.
In This Section
Company Object
Self Object
User Object
See Also
Form Designer Code tab

---

## Form Designer Page Control Properties

Source: https://accredo.co.nz/webhelp/PageControlFDComponent.htm

Form Designer Page Control Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
A page set used to make a multi-page dialog box. Use this control to define multiple logical pages or sections of information within the same window.
To add
Tab Sheets
to a Page Control, right-click in a Page Control component, then select
New Sheet
from the context menu.
The following properties are available for Page Control Components:
ActiveTab
Select the tab to be the default active tab.
Hint
The Hint text to be displayed when the mouse hovers over the component.
MultiLine
When
True
, tabs will be shown on multiple lines if they do not fit on the page control horizontally.
ShowSingleTab
When
True
, if only one Tab exists, the tab will be shown. When
False
, if only one tab exists, the tab will not be shown.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.
Page Control Context Menu
To access the Page Control Context Menu, right-click on the page control. Options available in the context menu are:
New Sheet
Add a new
Tab Sheet
to the Page Control.
Next Sheet
Select the next Tab Sheet.
Previous Sheet
Select the previous Tab Sheet.
Delete Sheet
Delete the selected Tab Sheet.
In This Section
Form Designer Tab Sheet Properties

---

## Form Designer Panel Properties

Source: https://accredo.co.nz/webhelp/PanelFDComponent.htm

Form Designer Panel Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
A panel is a container that can hold other components on a form. This can be used for grouping or for decoration. You can right-click on a Panel to send it to the front or back.
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Panel Components:
AlternateColor
When
True
, the Panel
Color
is set to the default Form Background colour set in
Company Display
settings.
BevelInner
Select the bevel type for the inner bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BevelOuter
Select the bevel type for the outer bevel, from
None
,
Lowered
,
Raised
, or
Space
.
BevelWidth
The width of the Panel bevel.
BorderStyle
Set the border style for the component, to
Single
or
None
.
BorderWidth
The width of the border.
Color
The Panel colour. Click
Open Color Dialog
(F2)
to select the
colour
.
Hint
The Hint text to be displayed when the mouse hovers over the component.
ParentColor
When
True
, the
Color
is set to the colour of the parent form.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.

---

## Form Designer Period Lookup Combo Properties

Source: https://accredo.co.nz/webhelp/PeriodDataComboFDComponent.htm

Form Designer Period Lookup Combo Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Period Lookup Combo Components:
BorderStyle
Set the border style for the combo, to
Single
or
None
.
DittoSibling
You can select another combo to be paired with this component. When components are paired, the user can press
Ctrl
+
'
to copy the value of the paired component into the component.
Note: Both components must have the same
LookupSource
.
This can be useful where you have related components, such as
Period From
and
Period To
fields, or
Date From
and
Date To
fields.
Hint
The Hint text to be displayed when the mouse hovers over the component.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
IndexName
Select a field to index the table. This determines the order of the drop-down list.
LabelCaption
The text to be displayed beside the Combo box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
LookupFilter
You can enter a filter to apply when data is added to the drop-down list.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed on the form.
Hint: For Combos backed by Memory Tables, the
Display Inactive
button in
ButtonsAvailable
will only work if the memory table has two indexes: one called "
Primary
Key", and one called "Active
Primary
Key", where "Active
Primary
Key" is a key on a boolean field called "Inactive". At design time, the combo and the memory table must use the non-active index in the IndexName property.
For example, if the Primary Key is CustomerCode, then Index1 could be "Customer" and Index 2 could be "ActiveCustomer".

---

## Form Designer Scroll Box Properties

Source: https://accredo.co.nz/webhelp/ScrollBoxFDComponent.htm

Form Designer Scroll Box Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Scroll Box Components:
AutoSize
When
True
, the size of the component will be automatically set to fit the contents.
BorderStyle
Set the border style for the scroll box, to
Single
or
None
.
Color
The scroll box colour. Click
Open Color Dialog
(F2)
to select the
colour
.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the component.
Ctl3D
When
True
, the component control is shown in 3D.
Hint
The Hint text to be displayed when the mouse hovers over the component.
Style
Select the Scroll Box style from:
Standard
Box
Top Only
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed.

---

## Form Designer Speed Button Properties

Source: https://accredo.co.nz/webhelp/SpeedButtonFDComponent.htm

Form Designer Speed Button Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Speed Button Components:
Hint
The Hint text to be displayed when the mouse hovers over the component.
ImageIndex
Select a glyph to be displayed on the button.
ShortCut
Select a short cut key sequence to activate the button.

---

## Form Designer Spin Edit Properties

Source: https://accredo.co.nz/webhelp/SpinEditFDComponent.htm

Form Designer Spin Edit Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Spin Edit Components:
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
Decimals
Enter the maximum number of decimals allowed in the edit box.
Delta
The amount to increase or decrease the number entered when the spinner is clicked.
Domain
You can select a numeric domain for the edit input. If a
Currency Code
is entered, you are limited to price domains.
Hint
The Hint text to be displayed when the mouse hovers over the edit box.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
LabelCaption
The text to be displayed beside the Edit box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
MaxValue
The maximum amount that a user can enter. Make sure to set the
MinMaxCheck
to enforce the maximum limit.
MinMaxCheck
Set whether to check the value:
mmNone
- doesn't check the value.
mmMinimum-
only check the minimum value.
mmMaximum
- only check the maximum value.
mmBoth-
check both the minimum and maximum values.
MinValue
The minimum amount that a user can enter. Make sure to set the
MinMaxCheck
to enforce the minimum limit.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the edit box.
UseDecimals
When
True
, amounts can contain decimals.
Visible
When
True
, the edit box will be displayed on the form.

---

## Form Designer Splitter Properties

Source: https://accredo.co.nz/webhelp/SplitterFDComponent.htm

Form Designer Splitter Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
A Splitter control can be placed between aligned components to allow users to resize the components. You can use Splitters with components like Panels and Group Boxes. Splitters let you divide a form into several panes with multiple controls on each pane.
The order you place components and Splitter controls is very important. Splitters can be linked to the component placed immediately before the splitter. Make sure the parent component of the splitter is selected when you place a splitter bar.
To use a Splitter, first place a container component on the form, such as a panel or a scroll box, then add a Splitter with the same alignment as the control. Add another container component and set its
Align
to the same as the splitter or to
alClient
. Set the
MinSize
to specify the minimum size the splitter must leave the components when resizing. Setting
Align
to
alClient
will make the component take up the remaining space on its parent control.
For example, you can place a panel on the left edge of a form and set the
Align
to
alLeft
, then place a splitter that is also aligned to
alLeft
to the right of the panel. Finally place another panel aligned to
alLeft
or
alClient
to the right of the splitter. It is recommended that the right-most or bottom panel is set to
alClient
.
Accredo remembers window sizes and splitter positions when not Tabbed or Maximised.
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Splitter Components:
AutoSnap
When
False
, the splitter cannot resize neighbouring objects to zero when the user tries to make them smaller than the
MinSize
. This defaults to
True
.
Beveled
When
True
, the splitter's edge has a 3D look.
Color
The colour of the splitter. Click
Open Color Dialog
(F2)
to select the
colour
.
Constraints
Click the + button to expand. Select the maximum and minimum sizes for the splitter.
Hint
The Hint text to be displayed when the mouse hovers over the component.
LinkedControl
The container control the splitter is linked to.
MinSize
The minimum size the splitter must leave when resizing its neighbouring control.
For example, if the
Align
property is alLeft or alRight, the splitter cannot resize the regions to its left or right any smaller than MinSize pixels. Defaults to
30
.
Note: Always set MinSize to less than half the client width of its parent, or the splitter will not be able to move.
ParentColor
When
True
, the
Color
is set to the colour of the parent form.
ResizeStyle
Choose the resize style from:
rsNone
rsLine
rsUpdate
rsPattern
Visible
When
True
, the component will be displayed.

---

## Form Designer Style Guidelines

Source: https://accredo.co.nz/webhelp/FormDesignerStyleGuidelines.htm

Form Designer Style Guidelines
Form designer controls have default property values set to match Accredo internal forms, to make FD designed forms look like standard Accredo forms. FD designed forms provided with Accredo are designed following Accredo best practices, such as using panels for layouts. By default, the look and feel of FD forms should match Accredo's internal forms without having to explicitly tweak the properties.
The standard font for forms is Segoe UI. Forms designed in previous versions may have different fonts. You can change the font of all components on a form that have the Form component default font. Change the Form component Font and the change will be applied to all components with that default font.
Some standards to design forms in the Accredo style are:
Panel - BevelOuter {bvNone|bvLowered|bvRaised|bvSpace} Default to bvNone.
Grid Navigator - BevelOuter {bvNone|bvLowered|bvRaised|bvSpace} Default to bvNone.
Grid Scroller - BevelOuter {bvNone|bvLowered|bvRaised|bvSpace} Default to bvNone.
List Grid and Edit Grid components automatically draw without 3D look border bevels.
There are properties on some controls that help with the Accredo UI look and feel:
Panel, Grid Navigator - AlternateColour {True|False} Default to False.
If the property value is True the panel will be painted the Form Background colour set in Navigator > Setup > Company > Configuration > Company Display.
If the property value is False the panel will be painted the colour in the Color property.
Group Box - Style {gbsStandard|gbsBox|gbsTopOnly} Default to gbsBox.
If the property value is gbsStandard the group box will be painted with a full pale bevelled border.
If the property value is gbsBox the group box will be painted with a full darker bevelled border and improved caption alignment.
If the property value is gbsTopOnly the group box is painted with a bevel at the top only.
Other style guidelines to apply to forms are:
Remove all bevels as dividers and use colours to differentiate between work and navigational areas. Work areas remain at the default clBtnFace and the navigational areas change to the form background colour. Use panels with Alternate Colour set to True or False to create this effect.
Add a Navigator to the left side of forms that holds all of the navigational, and form level process buttons. This navigator has Alternate Colour = True.
A Form Navigator component is available in FD with default properties to match.
Form and Grid navigator components automatically have a button at the top to Expand Toolbar.

---

## Form Designer Surrogate Data Combo Properties

Source: https://accredo.co.nz/webhelp/SurrogateDataComboFDComponent.htm

Form Designer Surrogate Data Combo Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Surrogate Data Combo Components:
BorderStyle
Set the border style for the combo, to
Single
or
None
.
DittoSibling
You can select another combo to be paired with this component. When components are paired, the user can press
Ctrl
+
'
to copy the value of the paired component into the component.
Note: Both components must have the same
LookupSource
.
This can be useful where you have related components, such as
Period From
and
Period To
fields, or
Date From
and
Date To
fields.
Hint
The Hint text to be displayed when the mouse hovers over the component.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
IndexName
Select a field to index the table. This determines the order of the drop-down list.
LabelCaption
The text to be displayed beside the Combo box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
LookupFilter
You can enter a filter to apply when data is added to the drop-down list.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed on the form.
Hint: For Combos backed by Memory Tables, the
Display Inactive
button in
ButtonsAvailable
will only work if the memory table has two indexes: one called "
Primary
Key", and one called "Active
Primary
Key", where "Active
Primary
Key" is a key on a boolean field called "Inactive". At design time, the combo and the memory table must use the non-active index in the IndexName property.
For example, if the Primary Key is CustomerCode, then Index1 could be "Customer" and Index 2 could be "ActiveCustomer".

---

## Form Designer Surrogate Edit Data Combo Properties

Source: https://accredo.co.nz/webhelp/SurrogateEditDataComboFDComponent.htm

Form Designer Surrogate Edit Data Combo Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Surrogate Edit Data Combo Components:
BorderStyle
Set the border style for the combo, to
Single
or
None
.
DittoSibling
You can select another combo to be paired with this component. When components are paired, the user can press
Ctrl
+
'
to copy the value of the paired component into the component.
Note: Both components must have the same
LookupSource
.
This can be useful where you have related components, such as
Period From
and
Period To
fields, or
Date From
and
Date To
fields.
Hint
The Hint text to be displayed when the mouse hovers over the component.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
IndexName
Select a field to index the table. This determines the order of the drop-down list.
LabelCaption
The text to be displayed beside the Combo box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
LookupFilter
You can enter a filter to apply when data is added to the drop-down list.
LookupSource
Select a table to populate the drop-down list from.
ReadOnly
When
True
, the user cannot edit the component on the form.
TabOrder
Set the sequential tab order for components, when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Visible
When
True
, the component will be displayed on the form.
Hint: For Combos backed by Memory Tables, the
Display Inactive
button in
ButtonsAvailable
will only work if the memory table has two indexes: one called "
Primary
Key", and one called "Active
Primary
Key", where "Active
Primary
Key" is a key on a boolean field called "Inactive". At design time, the combo and the memory table must use the non-active index in the IndexName property.
For example, if the Primary Key is CustomerCode, then Index1 could be "Customer" and Index 2 could be "ActiveCustomer".

---

## Form Designer Tab Sheet Properties

Source: https://accredo.co.nz/webhelp/TabSheetFDComponent.htm

Form Designer Tab Sheet Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
To add Tab Sheets to a
Page Control
, right-click in a Page Control component, then select
New Sheet
from the context menu.
The following properties are available for Tab sheet components:
Caption
The text to be displayed on the component.
Hint
The Hint text to be displayed when the mouse hovers over the component.
PageIndex
The ordering index of tabs on the Page Control.
TabVisible
When
True
, the component will be displayed.

---

## Form Designer Table Field Editor

Source: https://accredo.co.nz/webhelp/FDFieldEditor.htm

Form Designer Table Field Editor
Navigator > Setup > Form Designer > Layout tab >
Table Component
>
Double-click
- OR -
Navigator > Setup > Form Designer > Layout tab >
Table Component
>
Right-click
> Table Editor
Use Field Editor to select the fields to be available in the table. You must set the
TableName
property for the table before you can access the Field Editor.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a field. The available fields for the table are displayed. Select one field or select
All
to insert all fields from the table.
Move
(Shift+Up) (Shift+Down)
Select a field and reorder the list.
Delete
(F3)
Remove the selected field from the table.
Select all
(Shift+F4)
Set
Visible
on all fields to
Selected
.
Unselect all
(Shift+F3)
Set
Visible
on all fields to
Clear.
Buttons
Generate
(Alt+G)
Generate MaxBasic code to create a memory table based on field selections. Code will be displayed in the
Script Editor
.
Save
(F9)
Save the table.
Cancel
(Esc)
Close the form without saving any changes.

---

## Form Designer Table Methods

Source: https://accredo.co.nz/webhelp/FormDesignerTableMethods.htm

Form Designer Table Methods
Navigator > Setup > Form Designer > Code tab
Components each have different methods available to them. Methods available are listed under
Objects
> [Component Type] > [Component Name] > Methods.
See also
Form Designer Component Methods
for methods available to all component types.
The following methods are available to Table and Memory Table Components:
Component
Method
Description
Memory Table
AddField
Add a field to the graph or table definition.
Memory Table
AddIndex
Add a new index to the Memory Table.
Memory Table, Table
Append
Append a record to the memory table.
Memory Table
ApplyOrder
Order items in the memory table in order of a supplied array.
Memory Table
Cancel
Cancel pending changes that haven't been saved.
Table, Memory Table
CancelRange
Cancels the range that has been set for the table.
Memory Table
ClearFields
Clears all the field definitions.
Memory Table, Table
Clone
Copy field and index definitions from another table and links the tables.
Memory Table
CopyTable
Copy field and index definitions from another table.
Memory Table, Table
Delete
Delete the current row from the table or memory table.
Memory Table, Table
Edit
Opens the table or memory table for editing.
Memory Table
Empty
Empties all data from the memory table.
Memory Table, Table
Find
Finds the closest match in a table.
Memory Table, Table
FindExact
Finds an exact match in a table.
Memory Table, Table
First
Go to the first record in a table.
Memory Table, Table
Insert
Insert a record at the current position in a table.
Memory Table, Table
Last
Go to the last record in a table.
Memory Table
LoadFromCSV
Populate a memory table from a CSV file.
Memory Table
LoadFromExcel
Populate a memory table from an Excel file.
Memory Table
LoadFromFile
Populate a memory table from a delimited file.
Memory Table, Table
Next
Go to the next record in a table.
Memory Table, Table
Prev
Go to the previous record in a table.
Memory Table, Table
Refresh
Refresh data in a table.
Memory Table, Table
Save
Save data in a table.
Memory Table
SaveToCSV
Export data from a memory table to a CSV file.
Memory Table
SaveToExcel
Export data from a memory table to an Excel file.
Memory Table
SaveToFile
Export data from a memory table to a delimited file.
Memory Table, Table
SetRange
Set a range, and move to the first record in the range.
Table, Memory Table
SetRangeEnd
Set the value(s) for the end of the range to be included.
Table, Memory Table
SetRangeStart
Set the value(s) for the start of the range to be included.
Memory Table, Table
ShowFieldErrorHint
Display an error hint on a field in a table.
Memory Table
Sort
Sort a table by fields listed.
Table
StampModified
For custom tables, updates the tracking fields.
Memory Table
StartFormUpdates
When a memory table is bound to a grid on a form, this starts the grid being automatically updated.
Memory Table
StopFormUpdates
When a memory table is bound to a grid on a form, this stops the grid being automatically updated.
Memory Table
SwapDown
Move the current record down one position.
Memory Table
SwapUp
Move the current record up one position.
In This Section
AddField - Memory Table Builder Method
AddIndex - Memory Table Method
Append - Memory Table Method
ApplyOrder - Memory Table Method
Cancel - Memory Table Method
CancelRange - Memory Table Method
ClearFields - Memory Table Builder Method
Clone - Memory Table Method
CopyTable - Memory Table Method
Delete - Memory Table Method
Edit - Memory Table Method
Empty - Memory Table Method
Find - Memory Table Method
FindExact - Memory Table Method
First - Memory Table Method
Insert - Memory Table Method
Last - Memory Table Method
LoadFromCSV - Memory Table Method
LoadFromExcel - Memory Table Method
LoadFromFile - Memory Table Method
Next - Memory Table Method
Prev - Memory Table Method
Refresh - Memory Table Method
Save - Memory Table Method
SaveToCSV - Memory Table Method
SaveToExcel - Memory Table Method
SaveToFile - Memory Table Method
SetRange - Memory Table Method
SetRangeEnd - Memory Table Method
SetRangeStart - Memory Table Method
ShowFieldErrorHint - Method
Sort - Memory Table Method
StampModified
StartFormUpdates - Memory Table Method
StopFormUpdates - Memory Table Method
SwapDown - Memory Table Method
SwapUp - Memory Table Method
See Also
Form Designer Code tab

---

## Form Designer Table Properties

Source: https://accredo.co.nz/webhelp/TableFDComponent.htm

Form Designer Table Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
Double click a Table, or right-click and select
Field Editor
from the context menu, to open the
FD Field Editor
.
The following properties are available for Table Components:
Active
When
True
, the table is active and can be referenced.
AmountFormatting
Select which amount formatting style to adopt. Styles are set up in
Company Settings - Currency Format tab
.
CloneTable
Select a table to clone. The fields and indexes from the CloneTable will be applied to this table.
IndexName
Select an index for the table.
IsCustom
When
True
, the
TableName
is a Custom table.
Custom tables can call the
StampModified
method to update Modified fields (Modified User Code, Modified Date and Modified Time).
TableName
The table the component is representing.

---

## Form Designer Time Edit Properties

Source: https://accredo.co.nz/webhelp/TimeEditFDComponent.htm

Form Designer Time Edit Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following properties are available for Time Edit Components:
BorderStyle
Set the border style for the edit box, to
Single
or
None
.
EndTime
The latest time period option to be listed in the drop-down.
Hint
The Hint text to be displayed when the mouse hovers over the edit box.
IgnoreGridParent
When
True
, when the component is on a grid it will not be checked to see if it is unconnected.
Interval
The interval in minutes to separate time options displayed in the drop-down list by.
LabelCaption
The text to be displayed beside the Edit box.
LabelVisible
When
False
, the
Label Caption
will not be displayed.
LabelWidth
Set the width of the
Label Caption
.
ReadOnly
When
True
, the user cannot edit the component on the form.
StartTime
The earliest time period option to be listed in the drop-down.
TabOrder
Set the sequential tab order for components when the
Tab
key is pressed in the form.
TabStop
When
True
, this component will be included in the tab order. When
False
, the
Tab
key will not stop at this component.
Text
Text to be displayed in the edit box.
UseSeconds
When
True
, seconds are included in the time.
Visible
When
True
, the edit box will be displayed on the form.

---

## Form Designer Timer Properties

Source: https://accredo.co.nz/webhelp/TimerFDComponent.htm

Form Designer Timer Properties
Navigator > Setup > Form Designer > Layout tab > Component Editor > Properties tab
See also
Form Designer Component Properties
for properties common to different component types.
The following property is available for Timer Components:
Interval
Enter the time interval in milliseconds at which the
OnExecute
Event will be triggered.

---

## Form Designer Tutorials

Source: https://accredo.co.nz/webhelp/FormDesignerTutorials.htm

Form Designer Tutorials
In This Section
FD Tutorial: Display a Memory Table in a Grid
FD Tutorial: Custom Form refreshed on a timer
FD Dashboard Tutorials

---

## Form Events

Source: https://accredo.co.nz/webhelp/FormEvents.htm

Form Events
Navigator > Setup > Company > Scripts > Script Events
Form events are triggered when data in Accredo is accessed or manipulated via a form. If data is manipulated at data level (that is, if a script is used to manipulate data objects at data level, bypassing one or more forms) then form level scripts are not triggered. Data level events are only available with DI present.
See
Events Documentation
for a list of available events for each form.
Form events interact with
Data events
are triggered in sequences, see
Events Sequences
.
Hint: In Form Event scripts, we recommend you explicitly declare variables using the
Dim statement
, to avoid confusion between variable names between scripts. See
Passing Information Between Events
for details of sharing data.
Note: For Line Events, by default, totals are not calculated until the operation is complete. To change this and force totalling per line, use the configuration switch
/LineEventSums
.
You can use the .OnOpen event to make a standard form unavailable. See
Using Events to Control Form Access
.
Some examples of form level events are:
Type
Description
Examples
*.Header.AfterChange
Runs after a value is changed.
Can be used when changing a field changes other fields on the form, such as Customer on an Invoice form.
The TriggerField method can be used to identify the field that was changed.
INInvoiceEntryForm.Header.AfterChange - You can compare old and new values after changing.
*.AfterInsert
Runs immediately after a User selects the Insert option on the form.
This can be used to pre-fill certain fields with information that is already available.
ARCustomerForm.AfterInsert - You can pre-fill the Salesperson field with details from the current User.
INInvoiceEntryForm.AfterInsert - You can pre-fill the Origination Date field with today's date.
*.AfterPost
Runs after a Post action is executed.
Can be used to specify the next required or logical step for optimum processing.
JCBatchTransactionEntryForm.AfterPost - You can print a report and send it to the factory manager.
*.AfterSave
Runs after a Save action is executed.
This can be used to specify the next required or logical step for optimum processing.
Form.Aftersave is triggered only after all events triggered by the same operation have completed.
INInvoiceEntryForm.AfterSave - You can print a mailing label and start a new invoice.
*.Line.AfterSave
Runs after a line is saved.
Use this to apply a script to each line after it is saved.
The ActiveProperty field will return the field that triggered the event.
INInvoiceEntryForm.Line.AfterSave - You can add information on lines.
*.Header.BeforeChange
Runs before a value is changed.
Can be used when changing a field changes other fields on the form, such as Customer on an Invoice form.
The TriggerField method can be used to identify the field that was changed.
INInvoiceEntryForm.Header.BeforeChange - You can compare old and new values before changing.
*.BeforeClose
Runs when a user selects to close a form, before the form is closed.
Can be used to trigger validation rules before a form is closed.
APCategories1GridForm.BeforeClose - You can validate entries in the grid before closing the form.
ICStockGroupForm.BeforeClose - You can validate the form before closing.
*.BeforePost
Runs when a Post option is selected, before the Post action is executed.
This can be used to enforce business rules and ensure forms are completed correctly.
INInvoiceEntryForm.BeforePost - You can calculate bonus points based on Products and quantities purchased, and transfer to Customer records.
*.BeforeSave
Runs when a Save option is selected, immediately before the Save action is executed.
This can be used to enforce business rules and ensure forms are completed correctly.
OESalesOrderEntryForm.BeforeSave - You can check margins against minimum levels set and warn or refuse to save if below target.
*.Line.BeforeSave
Runs after a line is saved.
Use this to apply a script to each line before it is saved.
The Line.TriggerField field will return the field that triggered the event.
INInvoiceEntryForm.Line.BeforeSave - You can validate information on lines before saving.
*.OnClose
Runs after a form is closed.
This can be used to specify the next required or logical step for optimum processing.
APCreditorForm.OnClose - You can open the IC Products form to add or assign products for the new creditor.
GLBatchEditForm.OnClose - You can prompt to print a report.
*.OnOpen
Runs after a User opens a form, before the form is shown.
This can be used to specify default views and preferences.
INInvoiceEntryForm.OnOpen - You can pre-fill the Salesperson field with the User code or pre-fill Origination Date field with today's date.
Use
ActiveProperty
to set the active control, allowing you to set values on another form or tab.
Set the ActiveProperty = "" to set focus to the primary selection, e.g the customer code on the customer maintenance form.
*.OnPrint
*.OnPrintLabel
*.OnPrintProductLabels
Runs after a user selects a print option.
This can be used to specify whether a record needs to be saved before printing.
You can also specify email properties, which will be passed to the Preview form if Mail Report is later selected.
InInvoiceEntryForm.OnPrint - You can run a validation script on key fields before allowing an invoice to be printed.
*.OnShow
Runs after a form is shown.
InInvoiceEntryForm.OnShow - You can open other forms to show in front of the form.
*.BeforeEdit
Runs when the edit option is selected on a document.
InInvoiceEntryForm.BeforeEdit - You can call Abort from here to cancel the edit.
*.AfterEdit
Runs immediately after the edit options is selected on a document.
POPurchaseOrderEntryForm.AfterEdit - You can validate information on the form immediately after Edit is selected.
*.Master.BeforeChange
Runs on a form immediately before a masterfile record is changed.
JCJobForm.Master.BeforeChange - You can capture information in a MasterFile before it is changed.
*.Master.AfterChange
Runs on a form immediately after a masterfile record is changed.
JCJobForm.Master.AfterChange - You can capture information changed in a MasterFile for comparison.
*.AfterAddOrderLine
Runs on the AP Enter Shipments form immediately after a line is added.
APShipmentEntryForm.AfterAddOrderLine - Can be used to add costs to shipment lines.
*.BeforeGenerate
Runs on the IC Manufacture Batch form when Manufacture Component is selected.
ICManufactureBatchForm.BeforeGenerate - Can be used to check a batch has been saved before Manufacture Component is selected.
*.AfterExtend
Runs on the IC Manufacture Batch form after Manufacture Components are extended.
ICManufactureBatchForm.AfterExtend - Can be used to iterate components following expansion to update generated tracking.
Note: When records are posted, the following events all are run in the order: BeforeSave, BeforePost, AfterPost, AfterSave.
In This Section
Using Events to Control Form Access
Using Events to set Batch Selection Defaults

---

