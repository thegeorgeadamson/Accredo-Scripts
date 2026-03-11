# Inventory Control (IC)

> Products, stock takes, transfers, adjustments, warehousing, BOMs, tracking

**Sections:** 172

---

## Quick Reference

- [Alias Bin Codes](#alias-bin-codes)
- [Alias Codes](#alias-codes)
- [Alias Delivery Codes](#alias-delivery-codes)
- [Alias Lot Nos](#alias-lot-nos)
- [Alias Serial Nos](#alias-serial-nos)
- [CO Alias and Merge Log](#co-alias-and-merge-log)
- [FD Tutorial: Dashboard Product Sales](#fd-tutorial-dashboard-product-sales)
- [IC - Tracking Tab or Panel](#ic---tracking-tab-or-panel)
- [IC Adjustment Batch - Links tab](#ic-adjustment-batch---links-tab)
- [IC Adjustment Batch - Memos tab](#ic-adjustment-batch---memos-tab)
- [IC Adjustment Batch List](#ic-adjustment-batch-list)
- [IC Apply Default UOM - Stock Group](#ic-apply-default-uom---stock-group)
- [IC Apply UOM Results](#ic-apply-uom-results)
- [IC Basic Count](#ic-basic-count)
- [IC Basic Count - Enter Quantities](#ic-basic-count---enter-quantities)
- [IC Bin Batch Labels](#ic-bin-batch-labels)
- [IC Bin Count](#ic-bin-count)
- [IC Bin Count List](#ic-bin-count-list)
- [IC Bin Label Designer](#ic-bin-label-designer)
- [IC Bin Movement](#ic-bin-movement)
- [IC Bin Movement List](#ic-bin-movement-list)
- [IC Bin Processing](#ic-bin-processing)
- [IC Bin Tracking Quantities](#ic-bin-tracking-quantities)
- [IC Bins](#ic-bins)
- [IC Categories](#ic-categories)
- [IC Change Tracking Log](#ic-change-tracking-log)
- [IC Component](#ic-component)
- [IC Component - Parts tab](#ic-component---parts-tab)
- [IC Component - Prices tab](#ic-component---prices-tab)
- [IC Components - Links tab](#ic-components---links-tab)
- [IC Components - Memos tab](#ic-components---memos-tab)
- [IC Count Designer](#ic-count-designer)
- [IC Count Sheets](#ic-count-sheets)
- [IC Edit Count](#ic-edit-count)
- [IC End Of Period](#ic-end-of-period)
- [IC Enter Adjustment Batch](#ic-enter-adjustment-batch)
- [IC Enter Manufacture Batch](#ic-enter-manufacture-batch)
- [IC Enter Manufactures](#ic-enter-manufactures)
- [IC Enter Memos](#ic-enter-memos)
- [IC Enter Receipt Batch](#ic-enter-receipt-batch)
- [IC Enter Stock Transfers](#ic-enter-stock-transfers)
- [IC Find Adjustment Batch ID](#ic-find-adjustment-batch-id)
- [IC Find Bin Code](#ic-find-bin-code)
- [IC Find Manufacture Batch ID](#ic-find-manufacture-batch-id)
- [IC Find Product](#ic-find-product)
- [IC Find Receipt Batch ID](#ic-find-receipt-batch-id)
- [IC Find Stocktake](#ic-find-stocktake)
- [IC Find Stocktake Count](#ic-find-stocktake-count)
- [IC Find Stocktake ID](#ic-find-stocktake-id)
- [IC Generate Bin Count](#ic-generate-bin-count)
- [IC Generate Counts](#ic-generate-counts)
- [IC Generate Stocktake](#ic-generate-stocktake)
- [IC Global Price Update](#ic-global-price-update)
- [IC Import Count](#ic-import-count)
- [IC Insert Count](#ic-insert-count)
- [IC Insert Products](#ic-insert-products)
- [IC Label Designer](#ic-label-designer)
- [IC Link List](#ic-link-list)
- [IC Manufacture - Links tab](#ic-manufacture---links-tab)
- [IC Manufacture - Memos tab](#ic-manufacture---memos-tab)
- [IC Manufacture Batch - Grid](#ic-manufacture-batch---grid)
- [IC Manufacture Batch - Links tab](#ic-manufacture-batch---links-tab)
- [IC Manufacture Batch - Memos tab](#ic-manufacture-batch---memos-tab)
- [IC Manufacture Batch List](#ic-manufacture-batch-list)
- [IC Manufacture Sheet Designer](#ic-manufacture-sheet-designer)
- [IC Memo Designer](#ic-memo-designer)
- [IC Memo List](#ic-memo-list)
- [IC Memo Reports - Add Layout](#ic-memo-reports---add-layout)
- [IC Pending Usage for UOM](#ic-pending-usage-for-uom)
- [IC Price List Copy](#ic-price-list-copy)
- [IC Price Update Query](#ic-price-update-query)
- [IC Print Basic Stocktake](#ic-print-basic-stocktake)
- [IC Print Bin Labels](#ic-print-bin-labels)
- [IC Print Counts](#ic-print-counts)
- [IC Print Manufacture Sheets](#ic-print-manufacture-sheets)
- [IC Print Stocktake Sheet](#ic-print-stocktake-sheet)
- [IC Print Transfers](#ic-print-transfers)
- [IC Product - Activity tab](#ic-product---activity-tab)
- [IC Product - Image tab](#ic-product---image-tab)
- [IC Product - Information tab](#ic-product---information-tab)
- [IC Product - Links tab](#ic-product---links-tab)
- [IC Product - Locations Tab](#ic-product---locations-tab)
- [IC Product - Memos tab](#ic-product---memos-tab)
- [IC Product - Product tab](#ic-product---product-tab)
- [IC Product - Quantity tab](#ic-product---quantity-tab)
- [IC Product - Supplemental tab](#ic-product---supplemental-tab)
- [IC Product - Tracking](#ic-product---tracking)
- [IC Product - Transactions tab](#ic-product---transactions-tab)
- [IC Product - UOM tab](#ic-product---uom-tab)
- [IC Product Batch Labels](#ic-product-batch-labels)
- [IC Product Bin](#ic-product-bin)
- [IC Product Component Of](#ic-product-component-of)
- [IC Product Labels](#ic-product-labels)
- [IC Product List](#ic-product-list)
- [IC Product Quantities](#ic-product-quantities)
- [IC Product Reports - Add Layout](#ic-product-reports---add-layout)
- [IC Product Sheet Designer](#ic-product-sheet-designer)
- [IC Product Sheets](#ic-product-sheets)
- [IC Product Tracking Query](#ic-product-tracking-query)
- [IC Product Tree](#ic-product-tree)
- [IC Product Usage for UOM](#ic-product-usage-for-uom)
- [IC Product Validation Failures](#ic-product-validation-failures)
- [IC Receipt Batch List](#ic-receipt-batch-list)
- [IC Report Period](#ic-report-period)
- [IC Reprice from Components](#ic-reprice-from-components)
- [IC Revalue Stock on Hand](#ic-revalue-stock-on-hand)
- [IC Select Products](#ic-select-products)
- [IC Select Stocktake](#ic-select-stocktake)
- [IC Sell Prices Grid](#ic-sell-prices-grid)
- [IC Settings - Display Labels tab](#ic-settings---display-labels-tab)
- [IC Settings - First Period on Perpetual Integration / First Period on Periodic Integration](#ic-settings---first-period-on-perpetual-integration---first-period-on-periodic-integration)
- [IC Settings - General tab](#ic-settings---general-tab)
- [IC Settings - Integration tab](#ic-settings---integration-tab)
- [IC Settings - Links tab](#ic-settings---links-tab)
- [IC Settings - Memos tab](#ic-settings---memos-tab)
- [IC Settings - Misc tab](#ic-settings---misc-tab)
- [IC Settings - Period tab](#ic-settings---period-tab)
- [IC Settings - Prices tab](#ic-settings---prices-tab)
- [IC Settings - Stocktake tab](#ic-settings---stocktake-tab)
- [IC Settings - Words tab](#ic-settings---words-tab)
- [IC Single Count](#ic-single-count)
- [IC Single Count - Enter Quantities](#ic-single-count---enter-quantities)
- [IC Stock Group](#ic-stock-group)
- [IC Stock Locations](#ic-stock-locations)
- [IC Stock Transfers - Links tab](#ic-stock-transfers---links-tab)
- [IC Stock Transfers - Memos tab](#ic-stock-transfers---memos-tab)
- [IC Stocktake - Counts tab](#ic-stocktake---counts-tab)
- [IC Stocktake - Links tab](#ic-stocktake---links-tab)
- [IC Stocktake - Memos tab](#ic-stocktake---memos-tab)
- [IC Stocktake - Products tab](#ic-stocktake---products-tab)
- [IC Stocktake Count - Counts tab](#ic-stocktake-count---counts-tab)
- [IC Stocktake Count - Links tab](#ic-stocktake-count---links-tab)
- [IC Stocktake Count - Memos tab](#ic-stocktake-count---memos-tab)
- [IC Stocktake Designer](#ic-stocktake-designer)
- [IC Stocktake Import](#ic-stocktake-import)
- [IC Stocktake List](#ic-stocktake-list)
- [IC Stocktake Processing](#ic-stocktake-processing)
- [IC Stocktake Reports - Add Layout](#ic-stocktake-reports---add-layout)
- [IC Store Persons](#ic-store-persons)
- [IC Supplier Cost Update](#ic-supplier-cost-update)
- [IC Tracking Reports - Add Layout](#ic-tracking-reports---add-layout)
- [IC Transaction List](#ic-transaction-list)
- [IC Transaction Reports - Add Layout](#ic-transaction-reports---add-layout)
- [IC Transactions](#ic-transactions)
- [IC Transactions - Adjustment](#ic-transactions---adjustment)
- [IC Transactions - Issue/Credit](#ic-transactions---issue-credit)
- [IC Transactions - Links tab](#ic-transactions---links-tab)
- [IC Transactions - Memos tab](#ic-transactions---memos-tab)
- [IC Transactions - Receipt](#ic-transactions---receipt)
- [IC Transfer Designer](#ic-transfer-designer)
- [IC Transfer List](#ic-transfer-list)
- [IC Transfer Reports - Add Layout](#ic-transfer-reports---add-layout)
- [IC Transfer to GL](#ic-transfer-to-gl)
- [IC Units of Measure](#ic-units-of-measure)
- [IC UOM Groups](#ic-uom-groups)
- [IC Update Prices](#ic-update-prices)
- [Inventory Control](#inventory-control)
- [Inventory Control - Maintain](#inventory-control---maintain)
- [Inventory Control - Reports](#inventory-control---reports)
- [Inventory Control - Setup](#inventory-control---setup)
- [Inventory Control - Tasks](#inventory-control---tasks)
- [MB Script: IC Product Quantities by Location Pivot Table](#mb-script-ic-product-quantities-by-location-pivot-table)
- [MB Script: IC Products and Prices Pivot Table](#mb-script-ic-products-and-prices-pivot-table)
- [MB Tutorial: IC Product Quantities by Location Pivot Table](#mb-tutorial-ic-product-quantities-by-location-pivot-table)
- [MB Tutorial: IC Products and Prices Pivot Table](#mb-tutorial-ic-products-and-prices-pivot-table)
- [Merge Bin Codes](#merge-bin-codes)
- [Merge Lot Nos](#merge-lot-nos)
- [Product Tracking Quantities](#product-tracking-quantities)
- [Serial No Picker](#serial-no-picker)
- [SF Script: Select Multiple Products on Invoice](#sf-script-select-multiple-products-on-invoice)
- [SF Tutorial: Select Multiple Products on Invoice](#sf-tutorial-select-multiple-products-on-invoice)
- [UOMDecimals - MacBasic Function](#uomdecimals---macbasic-function)

---

## Alias Bin Codes

Source: https://accredo.co.nz/webhelp/AliasBinCodes.htm

Alias Bin Codes
Use Alias Codes.
(Accredo Saturn Only, in Mercury use Alias Codes)
Navigator > Setup > Company > Utilities > Alias Bin Codes
You can alias a Bin Code record to change the code. This will move data and history to the new code.
When you use Alias Bin Code, a log of the code changes is appended to the File Recovery
Error Log
, with each alias appended to an
Alias.csv
file in the data directory to provide a change log. This is useful when you are integrating a third party application that will need to consider aliased records. Any affected
word lookups
will be rebuilt.
Warning: You will be prompted to back up your data before running this utility, as this utility restructures Accredo data files. If you experience power or other failure during posting, restore the backup and perform the Alias again, or if this is not possible due to other users processing since the backup, add
From
codes and perform
Merge
codes.
Important: Do not run a file recovery before performing the steps above as file recovery will delete records relating to missing codes.
Selections
Location
Select the location to display Bin Codes for.
Fields
From Code
Select an existing Bin code from the list of codes. To include inactive records click
Show Inactive Records
(Ctrl+I)
.
To Code
Enter the new code, that the
From Code
will be changed to.
Description
The description for the code. Read-only.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of Bin codes to be changed. This can save time from entering codes individually. The import file must be a text file with one line per code change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From code
Alpha
16
To code
Alpha
16
Additional fields will be ignored by the import. Only lines in which the From code and To code differ, and a match for the From code is found are imported. When you import you are prompted with the Alias Importing report selections, this report shows the records that have been imported into the grid and error messages for lines which are not imported. If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Click
Post
(
Alt+T
) to merge the imported selections.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Buttons
Print
(Ctrl+P)
Print the Summary of Alias IC  report. See
Report Selections Form
.Bin Code
Post
(Alt+T)
Post the changes.
See Also
Utilities

---

## Alias Codes

Source: https://accredo.co.nz/webhelp/AliasCodes.htm

Alias Codes
Navigator > Setup > Company > Utilities > Alias Codes
Alias a code to rename the code. This will move data and history to a new code, deleting the old one.
When you Alias codes:
each change is recorded in the
Alias and Merge Log
.
each change is appended to an Alias.csv file in the data directory.
the
Alias
event and
Backup Confirmation
are recorded in the
File Recovery log
.
if the aliased record is
Change Tracked
the
Alias
is recorded as a Delete of the From Code and an Add of the To Code.
for change tracking of other tables containing the aliased code this
Alias
is recorded as an Update.
Tracking and logging is useful when you are integrating a third party application that will need to consider aliased records.
Warning: You will be prompted to back up your data before running this utility, as this utility restructures Accredo data files.
If you experience power or other failure during posting, Modules are locked during critical processing. You will need to restore the backup, and perform the Alias again or contact Accredo Support.
Important: Do not run a file recovery before performing the steps above as file recovery will delete records relating to missing codes.
Notes:
To identify possible issues in the structure of the Chart Of Accounts, validate the GL after performing Alias on GL Account Codes.
GL Subsidiary Company codes can be aliased if the Company Code for the subsidiary is changed.
Selections
Select Code
Select the type of code to be aliased.
Fields
From Code
Select an existing code from the list of codes. To include inactive records click
Show Inactive Records
(Ctrl+I)
. To open a list of Alias Codes, click
Open
(Shift+F12)
.
To Code
Enter the new code, that the
From Code
will be changed to.
Description
The description for the code. Read-only.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of codes to be changed. This can save time from entering codes individually. The import file must be a text file with one line per code change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From code
Alpha
Depends on code selected
To code
Alpha
Depends on code selected
Additional fields will be ignored by the import. Only lines in which the From code and To code differ, and a match for the From code is found are imported. When you import, if there are errors you are prompted with the Alias Importing report selections, this report shows the error messages for lines which are not imported. If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Click
Post
(
Alt+T
) to alias the imported selections.
Buttons
Print
(Ctrl+P)
Print the Summary of Alias Codes report. See
Report Selections Form
.
Post
(Alt+T)
Post the changes.

---

## Alias Delivery Codes

Source: https://accredo.co.nz/webhelp/AliasDelivery.htm

Alias Delivery Codes
Navigator > Setup > Company > Utilities > Alias Delivery Codes
Available when AR is installed.
Alias a delivery code to rename the code. This will move data and history to a new code, deleting the old one. When you use Alias Deliver Codes, each alias is appended to an
Alias.csv
file in the data directory to provide a change log. This is useful when you are integrating a third party application that will need to consider aliased records.  Any affected
word lookups
will be rebuilt.
Warning: You will be prompted to back up your data before running this utility, as this utility restructures Accredo data files. If you experience power or other failure during posting, restore the backup and perform the Alias again, or if this is not possible due to other users processing since the backup, add
From
codes and perform Alias Delivery Codes again.
Important: Do not run a file recovery before performing the steps above as file recovery will delete records relating to missing codes.
Selections
Customer
Select the customer to alias delivery codes for.
Fields
From Code
Select an existing delivery code from the list of codes.
To Code
Enter the new code, that the
From Code
will be changed to.
Description
The description for the code. Read-only.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of codes to be changed. This can save time from entering codes individually. The import file must be a text file with one line per code change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From code
Alpha
20
To code
Alpha
20
Additional fields will be ignored by the import. Only lines in which the From code and To code differ, and a match for the From code is found are imported. When you import you are prompted with the Alias Importing report selections. This report shows the records that have been imported into the grid and error messages for lines which are not imported.
If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Click
Post
(
Alt+T
) to alias the imported selections.
Buttons
Print
(Ctrl+P)
Print the Summary of Alias AR Delivery Address report. Prints information in the grid, regardless of whether it has been posted. See
Report Selections Form
.
Post
(Alt+T)
Post the changes.
See Also
Utilities

---

## Alias Lot Nos

Source: https://accredo.co.nz/webhelp/AliasLot.htm

Alias Lot Nos
Navigator > Setup > Company > Utilities > Alias Lot Nos
Select the product code. Search for a product using the
Accredo Lookups
.
Alias Lot Nos to correct mis-entered Lot No, Expiry date or Lot date. This will update data and history to the new number and dates. When you Alias Lot Nos, a log of the changes is appended to the File Recovery
Error Log
, and recorded in the
CO Alias and Merge Log
. This is useful when you are integrating a third party application that will need to consider aliased records.
Selections
Product
Select the product to alias Lot No's for.
Fields
From Lot No,
From Lot Date,
From Expiry Date
Enter or select an existing Lot No from the list of Nos. Lot Date and Expiry Date will be displayed.
To Lot No,
To Lot Date,
To Expiry Date
Enter the new Lot No, Lot Date or Expiry Date. The To Lot No must not already exists in the system, if only the dates are to be changed the To Lot No may be the same as the From Lot No.
Note: Changing the Expiry Date for a lot does not re-visit any existing supply decisions.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of Lot Nos to be changed. This can save time from entering Lot Nos individually. The import file must be a text file with one line per change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From Lot No
Alpha
16
To Lot No
Alpha
16
To Lot Date
Date
To Expiry Date
Date
Additional fields will be ignored by the import. Only lines in which the From Lot No is found and the To Lot is either the same as the From Lot No or is not found are imported. When you import you may be prompted with the Alias Importing report selections, this report shows any error messages for lines which are not imported. If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Buttons
Print
(Ctrl+P)
Print the Summary of Alias IC  report. See
Report Selections Form
Bin Code.
Post
(Alt+T)
Post the changes.
See Also
Inventory Control - Setup

---

## Alias Serial Nos

Source: https://accredo.co.nz/webhelp/AliasSerial.htm

Alias Serial Nos
Navigator > Setup > Company > Utilities > Alias Serial Nos
Select the product code. Search for a product using the
Accredo Lookups
.
Alias Serial Nos to correct mis-entered Serial numbers. This will update data and history to the new Serial No. When you Alias Serial Nos, a log of the changes is appended to the File Recovery
Error Log
, and recorded in the
CO Alias and Merge Log
. This is useful when you are integrating a third party application that will need to consider aliased records.
Selections
Product
Select the product to alias Serial Nos for.
Fields
From Serial Number
Enter the Serial No to be aliased.
To Serial Number
Enter the new Serial No. The
To Serial No
must not already exist in the system.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of Serial Nos to be changed. This can save time from entering Serial Nos individually. The import file must be a text file with one line per change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From Serial No
Alpha
28
To Serial No
Alpha
28
Additional fields will be ignored by the import. Only lines in which the From Serial No and To Serial No differ, and a match for the From Serial No is found are imported. When you import you may be prompted with the Alias Importing report selections, this report shows any error messages for lines which are not imported. If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Buttons
Print
(Ctrl+P)
Print the list of Serial Nos aliased.
Post
(Alt+T)
Post the changes.

---

## CO Alias and Merge Log

Source: https://accredo.co.nz/webhelp/COAliasLog.htm

CO Alias and Merge Log
Navigator > Setup > Company > Alias and Merge Log
View changes made through Alias and Merge operations.
Selections
From - To Date
Set a date range to see changes made. Leave blank to see all dates. Defaults to changes made within the last month of the machine date.
User
Select a user to see changes made by a particular user.
Select
(F9)
Click to apply selections, filters and sorts to the list.
Log  Fields
Alias ID
Alias or Merge Identification number.
Account File
Table being aliased or merged.
Old Code
Code before the Alias or Merge.
New Code
Code after the Alias or Merge.
Parent code
The field Parent Account Code.
Alias Type
Alias or Merge.
Module
Module affected.
Created User Code
The User who performed the Alias or Merge.
Created Date
Date of the Alias or Merge.
Created Time
Time of the Alias or Merge.
Log Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Print
(Ctrl+P)
Print the list, save it to an Excel worksheet or PDF file.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
After setting the filter, click
Select
(
F9
) to show the changes.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
See Also
Company - Setup

---

## FD Tutorial: Dashboard Product Sales

Source: https://accredo.co.nz/webhelp/FDTutorialProductSales_1.htm

FD Tutorial: Dashboard Product Sales
You can modify the
FD Tutorial: Dashboard Analysis of Expenses
to instead return product sales. This tutorial requires the IC Module.
Follow the steps in the tutorial, with the following changes.
4. Name the table
tblGrpProducts
.
6. Add the following fields to the table:
No.
Name
Display Label
Type
Domain
Size
Width
Visible
1
ProductCode
Product
String
IC Product Code
28
15
Selected
2
Description
Description
String
Product Description
60
22
Selected
3
CostOfSalesYTD
CostYTD
Float
Amount
12
Selected
4
SalesValueYTD
SalesYTD
Float
Amount
12
Selected
5
GrossProfitYTD
GrossProfitYTD
Float
Amount
14
Selected
6
MarginYTD
MarginYTD
Float
Percent1
11
Selected
7
SalesQtyYTD
SalesQtyYTD
Float
Quantity
4
12
Selected
8
CostOfSalesPTD
CostPTD
Float
Amount
12
9
SalesValuePTD
SalesPTD
Float
Amount
12
10
GrossProfitPTD
GrossProfitPTD
Float
Amount
14
11
MarginPTD
MarginPTD
Float
Percent1
11
12
SalesQtyPTD
SalesQtyPTD
Float
Quantity
12
11. Name the grid
gridProdSales
.
13. Set the table to
tblGrpProducts
.
14. Change the
Name
of the navigator to
navProdSales
.
17. Set the
Table
to
tblGrpProducts.
This links the grid to the memory table created previously. Set the
Hook Control
to
gridProductSales
, to link the navigator to the grid.
18. Enter the following code, to extract the sales product and populate the memory table, and display it in the grid:
Sub RefreshProducts
Dim tblProducts as Object
SQLPROD = "SELECT ICPROD.ProductCode as Product " & _
"      ,ICPROD.Description " & _
"      ,ICPROD.CostOfSalesYearToDate as CostOfSalesYTD " & _
"      ,ICPROD.SalesValueYearToDate as SalesValueYTD " & _
"      ,(ICPROD.SalesValueYearToDate - ICPROD.CostOfSalesYearToDate) as GrossProfitYTD " & _
"      ,ICPROD.MarginYearToDate as MarginYTD " & _
"      ,ICPROD.SalesQuantityYearToDate as SalesQtyYTD " & _
"      ,ICPROD.CostOfSalesPeriodToDate as CostOfSalesPTD " & _
"      ,ICPROD.SalesValuePeriodToDate as SalesValuePTD " & _
"      ,(ICPROD.CostOfSalesPeriodToDate - ICPROD.SalesValuePeriodToDate) as GrossProfitPTD " & _
"      ,ICPROD.MarginPeriodToDate as MarginPTD " & _
"      ,ICPROD.SalesQuantityPeriodToDate as SalesQtyPTD " & _
"FROM   ICPROD " & _
"WHERE (ICPROD.Inactive = False) " & _
"AND   (ICPROD.SalesValueYearToDate > 0) " & _
"ORDER BY GrossProfitYTD DESC "
tblProducts = ExecuteSQL(SQLPROD)
tblProducts.First
tblGrpProducts.Empty
tblGrpProducts.AllowInsertDelete = True
Do Until tblProducts.EOF
tblGrpProducts.Append
tblGrpProducts.ProductCode = tblProducts.Product
tblGrpProducts.Description = tblProducts.Description
tblGrpProducts.CostOfSalesYTD  = tblProducts.CostOfSalesYTD
tblGrpProducts.SalesValueYTD = tblProducts.SalesValueYTD
tblGrpProducts.GrossProfitYTD = tblProducts.GrossProfitYTD
tblGrpProducts.MarginYTD = tblProducts.MarginYTD
tblGrpProducts.SalesQtyYTD= tblProducts.SalesQtyYTD
tblGrpProducts.CostOfSalesPTD  = tblProducts.CostOfSalesPTD
tblGrpProducts.SalesValuePTD = tblProducts.SalesValuePTD
tblGrpProducts.GrossProfitPTD = tblProducts.GrossProfitPTD
tblGrpProducts.MarginPTD = tblProducts.MarginPTD
tblGrpProducts.SalesQtyPTD= tblProducts.SalesQtyPTD
tblGrpProducts.Save
tblProducts.Next
Loop
tblGrpProducts.AllowInsertDelete = False
tblGrpProducts.First
End Sub
19. Create a routine called OnCreate to run when the form is created. This will call the RefreshProducts sub-routine. Enter the following code:
Sub OnCreate
RefreshProducts
End Sub
22. Add the following code to enable the Open and Print Buttons:
Sub OnNavProd(Sender as Object, Button as Number, ByRef Handled as Boolean)
Dim Report as Object
If Button = ebOpen Then
Dim Form1 as Object
Form1 = CreateObject("Accredo.ICProductForm")
Form1.Find(tblGrpProducts.ProductCode )
Form1.GraphSelection = "Range of Periods"
Form1.GraphField2 = ""
Form1.GraphField = "SalesValue"
End If
If Button = ebPrint Then
Report = CreateReport(tblGrpProducts, " Product Sales For Last 12 Months ")
Report.Destination = "Screen"
Report.Run
Handled = True
End If
End Sub
23. Go to the layout tab. Select the
navProdSales
component. Go to the Events tab. Set
OnClick
to
OnNavProd
.
25. Change the link label
Caption
to
Product Sales
.
27. Add code to go to the IC 13 Period Sales Report when the Link Label is clicked. Go to the Code tab, and enter the following code:
Sub OnLinkProduct
Dim Form1 as Object
Form1 = CreateObject("Accredo.ICThirteenPeriodSalesReport")
Form1.Layout = "13 Period Sales"
End Sub
28. Go to the layout tab. Select the Link Label component. Go to the Events tab. Set
OnClick
to
OnLinkProduct
.
See Also
FD Tutorial: Dashboard Analysis of Expenses

---

## IC - Tracking Tab or Panel

Source: https://accredo.co.nz/webhelp/ICTrackingTabPanel.htm

IC - Tracking Tab or Panel
Tracking bar (right hand side)
Show Tracking
Hide Tracking
(Ctrl+T)
Show and or hide the tracking panel and focus the tracking for the current line, or line for the tracking.
Previous Tracking
(Ctrl+F7)
Move to previous tracked line.
Tracking Complete / Tracking not Complete
The button changes to indicate the tracking state for the current line.
Next Tracking
(Ctrl+F8)
Move to next tracked line.
Previous Tracking Required
(Alt+F7)
The button indicates if any previous line requires more tracking information before post, e.g. Serial Nos required.
Move to previous line requiring tracking.
Next Tracking Required
(Alt+F8)
The button indicates if any following line requires more tracking information before post, e.g. Serial Nos required.
Move to next line requiring tracking.
Product Tracking Quantities
Opens
IC Product Tracking Quantities
for the product.
Tracking Grid
Used to enter the tracking breakdown for products which are Lot No and/or Serial No tracked, and for tracked Locations (Accredo Saturn Only).
Inwards Tracking lines are generated as quantities are entered but may require further information before you can post, e.g. Lot Nos, Expiry Dates, Serial Nos before before receipting issuing or crediting.
Outwards Tracking lines may be
generated
as quantities are entered, or manually entered if preferred, subject to the
Generate Outwards Tracking
setting in
IC Settings - General tab
. Tracking must be complete before you can post.
Tracking grid fields displayed adjust automatically depending on the tracking required for the line. You can customise to change display labels, width and ordering. The grid fields are described below.
It is simplest to think of tracking in terms of the direction with respect to Quantity In Stock, i.e. Inwards movements and Outwards movements.
UOM Code
(
UOM
Active Only)
The UOM Code for the tracking. Only available when
UOM
is
Active
. If the Product has more than one UOM Code, you can select the code to use.
Note: If the quantity is not representable in the selected UOM Code decimals, the UOM Code will default to the Base UOM Code.
UOM Quantity
(
UOM
Active Only)
The quantity of the UOM in the tracking. If the UOM has a
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
The quantity of the Product in the tracking.
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
For Inwards Movement e.g. Receipts
Bin
Available and required for
Bin Tracked
Locations.
The Bin the product will be added to, defaults to the Bin Code for the Location in
IC Product - Locations tab
if one is set. (Accredo Saturn Only)
Lot No
The Lot No for the tracking quantity,
Lot No
tracked Products only. May be generated from Lot Date or Expiry Date if selected for the Product.
Note: If a Lot No is specified in a Document or Batch line it is entered in the tracking grid. A Lot No entered in the tracking grid does not update the Lot No field in the line since this is a many (tracking lines) to one (document or batch line) relationship.
Lot Date
Defaults from the date of the document or transaction, Lot No tracked Products only.
Expiry Date
The Expiry Date for the Lot,
Lot No
and
Expiry Date
tracked Products only.
Serial No
The Serial No for the tracking quantity for Serial No
Purchase
tracked products.
Enter or scan Serial Nos in the
Serial Nos
box. Serial Nos may be entered as a comma separated list. Enter to submit and validate Serial Nos.
Note: If a Serial No is specified in a Document or Batch line (quantity must be 1) it is entered in the tracking grid. A Serial No entered in in the tracking grid does not update the Serial No field in the line.
For Outwards Movement e.g. Invoices
Bin
Available and required for
Bin Tracked
Locations.
The Bin to pick the product from. Tracking lines are generated to pick smallest quantities in preferred bins, i.e. to empty bins based on bin priority.
Click
Bin Picker
(F2)
to select from available Bins. (Accredo Saturn Only)
Lot No
The Lot No to pick for supply,
Lot No
tracked Products only.
Tracking lines are generated to preferentially use up smallest lots taking
Supply Single Lot
and
Minimum Expiry
into consideration.
Click
Lot Picker
(F2)
to select from available Lots.
Note: If a Lot No is specified in a Document or Batch line it restricts available Lots to the specified Lot No and is entered in the tracking grid if stock is available. A Lot No entered or selected in the tracking grid does not update the Lot No field in the line since this is a many (tracking lines) to one (document or batch line) relationship.
Lot Date
The Lot Date for the selected Lot No.
Expiry Date
(Lot and Expiry Date Tracked Product only)
The Expiry Date for the selected Lot No. Tracking lines are generated to preferentially use up lots which are oldest and have at least the
Minimum Expiry
from the date of the document or transaction.
The IC Expired Stock permission controls whether Expired or Dated (not yet Expired but has less than Minimum Expiry period) stock can be seen and selected.
Serial No
(Serial Tracked Product only)
The Serial No for the tracking quantity for Serial No
Purchase
or
Sales
tracked products.
For Purchase tracked Serial Nos click
Serial No Picker
to select from available Serial Nos.
Enter or scan Serial Nos in the
Serial Nos box
. Serial Nos may be entered as a comma separated list. Enter to submit and validate Serial Nos.
Note: If a Serial No is specified in a Document or Batch line (quantity must be 1) it is entered in the tracking grid subject to availability. A Serial No entered in in the tracking grid does not update the Serial No field in the line.
For Adjustments
For adjustment transactions only tracking lines are not generated, and may be a mixture of inwards and outwards movements.
Note: Outwards movements on Adjustments are validated against the In Stock quantity for the Lot No or Serial No. For all other transactions validation is against the Available Quantity.
For Bin tracked locations posting Adjustments, including from Bin Movements or Stocktakes, will "bin forward" any affected outward tracking if allocated stock is moved from one bin to another in the tracking for the transaction. Saturn only.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new tracking line.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Delete the tracking line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Note: The columns shown adjust automatically depending on the tracking required for the line. Customise to change display labels, width and ordering.
Balance Quantity
(Ctrl+=)
Select this to add the
Balance To Track
to the tracking line.
Refresh Tracking
(F5)
Refresh generated tracking. Will generate for missing tracking or tracking that could not previously be generated but now can since availability has changed.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
In This Section
Lot / Bin Picker
Serial No Picker
Generated Outward Tracking

---

## IC Adjustment Batch - Links tab

Source: https://accredo.co.nz/webhelp/ICAdjustmentBatch_Links.htm

IC Adjustment Batch - Links tab
Navigator > Tasks > Inventory Control > Enter Adjustment Batch >
Links tab

---

## IC Adjustment Batch - Memos tab

Source: https://accredo.co.nz/webhelp/ICAdjustmentBatch_Memos.htm

IC Adjustment Batch - Memos tab
Navigator > Tasks > Inventory Control > Enter Adjustment Batch >
Memos tab

---

## IC Adjustment Batch List

Source: https://accredo.co.nz/webhelp/ICAdjustmentBatchList.htm

IC Adjustment Batch List
Navigator > Maintain > Inventory Control > Adjustment Batch List
Click
to make selections, and use the
lookups
.
Selections
Period
Select a period to view for:
Period
- Select a single period in the
From
selection.
Year
- Displays batches for the current year.
All Periods
- All batches are displayed.
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
Default is Range of Periods with From Period set to First Available period for IC or period of first Current Batch whichever is earlier, and To Period set to Last Available period for IC.
Selection
Select to show batches that are:
Unposted
Open
Posted
Deleted
All Batches
(excludes Deleted batches)
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Adjustments
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Adjustments
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Batch
The Adjustment Batch identifier.
Details
Details entered for the batch.
Date
Date of the adjustment batch.
Status
Post status of the adjustment batch.
Location
Location of the adjustment batch. (Accredo Saturn Only)
Period
Period the adjustment batch occurs in.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert an adjustment batch.
Delete
(F3)
Delete the adjustment batch. Only available for saved, unposted batches, when the user has permission.
Open Details
(F12)
Opens Batch data entry. View the details for the
Adjustment Batch
including all lines. You can edit an unposted batch.
Print
(Ctrl+P)
Print the IC Adjustments List. You can save as an Excel worksheet or PDF file and send as an email attachment.
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
The Adjustment Batch list to reload changes other Users may have made.
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
Post selected
(
Alt+T
)
Post the selected adjustment batch.
Post all up to current period
(
Alt+A
)
Post all adjustment batches up to the selected period.
Find
(Ctrl+F)
Find a batch using the Batch ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.
Button
Batch
(Alt+B)
Locate a Batch by the Batch ID.
In This Section
IC Find Adjustment Batch ID

---

## IC Apply Default UOM - Stock Group

Source: https://accredo.co.nz/webhelp/ICApplyDefaultUOM.htm

IC Apply Default UOM - Stock Group
Navigator > Maintain > Inventory Control > Stock Groups >
Apply Default UOM Codes to Products Base UOM Code
button
Sets the
Default UOM
of the selected Stock Group as the
Base UOM
for a range of Products within the Stock Group.
Note: The
Base UOM
will only be changed for products in the selected range that are in the selected UOM Stock Group. Products selected that are not in the selected Stock Group will not be changed.
Product - From
Enter or Select the first Product in the range.
Select a product, see Drop-down menu.
Word Lookup
- search for a product.
Show inactive product records.
Filter & Sort
the list of products.
Product - To
Enter or Select the last Product in the range.
Select a product, see Drop-down menu.
Word Lookup
- search for a product.
Show inactive product records.
Override Existing
Selected
, will override the existing
Base UOM
with the selected
Default UOM
, for products in the selected Stock Group.
Run
(F9)
Sets the
Base UOM
of the selected products in the Stock Group to the
Default UOM
of the Stock Group. Products selected that are not in the selected Stock Group are not affected. Displays the results in a report.
In This Section
IC Apply UOM Results

---

## IC Apply UOM Results

Source: https://accredo.co.nz/webhelp/ICApplyUOMResults.htm

IC Apply UOM Results
Navigator > Maintain > Inventory Control > Stock Groups >
Apply Default UOM Codes to Products Base UOM Code
button >
Run
(F9)
Lists products with the default UOM applied and those that did not have the default UOM applied due to error.
Display
Show
All results
,
Errors
only or
Successes
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
Total number of products that did not have the default UOM applied.
Records
Total number of products with the default UOM successfully applied.

---

## IC Basic Count

Source: https://accredo.co.nz/webhelp/ICBasicCount.htm

IC Basic Count
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Basic Count
Available when the
Count Type
in
IC Settings - Stocktake tab
is
Basic
.
Available when the
Count Type
for one or more Locations in
IC Stock Locations
is
Basic
. ( Accredo Saturn.)
You can select a range of products and Stock Groups and/or a Creditor code to be shown for stocktaking in
IC Basic Count - Enter Quantities
.
Location
Select the location for the stocktake. (Accredo Saturn Only)
Product From / To
Select a range of products for the stocktake, or leave blank to include all products.
Stock Group From / To
Select a range of stock groups for the stocktake, or leave blank to include all stock groups.
Creditor
Select a creditor for the stocktake, or leave blank to include all creditors.
Period
Select the period for the stocktake and to show quantities for.
Run
(F9)
The selected records appear in
IC Basic Count - Enter Quantities
.
In This Section
IC Basic Count - Enter Quantities

---

## IC Basic Count - Enter Quantities

Source: https://accredo.co.nz/webhelp/ICBasicCountEnterQuantities.htm

IC Basic Count - Enter Quantities
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Basic Count >
Run
(F9)
button
Available when the
Count Type
in
IC Settings - Stocktake tab
is
Basic
.
Available when the
Count Type
for one or more Locations in
IC Stock Locations
is
Basic
. ( Accredo Saturn.)
IC Basic Count Enter Quantities grid is live - information is saved as you move off each field.
The form will open with the products selected for the stocktake loaded with the current
Expected
figures. This is a snapshot at the time the form is opened. When a stocktake quantity is keyed for a product in the form, Accredo checks the quantity In Stock, and if it has changed, discards the figure entered and refreshes the
Expected
,
Counted
and
Variance
figures, and the message
Stock count has changed
will appear. If the form is left open for a long time, such as if it is opened in the morning and worked in all day, the figures for products may change during the life of the form.
You cannot change quantities of products entered in other unposted stocktakes for the same period.
IC Enter Quantities grid
Code, Description, Unit
Product details from the product record.
Quantity Expected
The number of items recorded as in-stock.
Quantity Counted
Enter the counted quantity.
Variance
The difference between the
Expected
and
Counted
figures above. This is updated when you enter an quantity in the
Counted
field and move off the field.
Counted
Becomes
Selected
when a figure is entered in the number
Counted
column, or when the
Mark Counted
or
Mark All Counted
buttons are clicked.
Note: Where Quantity Expected = Quanity Counted only lines marked Counted are added to the Stocktake and updated when the Stocktake is posted.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Print
(Ctrl+P)
Print the IC Stocktake Report.
Filter & Sort
(Ctrl+F2)
Clear
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
Find
(Ctrl+F)
Find
a product using the Product Code.
Mark Counted
(
F4
)
Mark the selected product as
Counted
.
Mark Uncounted
(
F3
)
Mark the selected product as
Uncounted
.
Mark All Counted
(
Shift+F4
)
Mark all products as
Counted
.

---

## IC Bin Batch Labels

Source: https://accredo.co.nz/webhelp/ICReports_BatchBinLabel.htm

IC Bin Batch Labels
Navigator > Reports > Inventory Control > Product Batch Labels - OR -
Navigator > Tasks > Invoicing System > Enter Invoice >
Print Product Labels
(Alt+U)
button
An alternative to
Bin Labels
, you can select the Bins and Count you require labels for.
You can print labels previously designed using
Label Designer
.
Accredo Saturn Only: Select a Location Code to print bins for.
Default report file names can be setup from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
Label Designer
.
See also
Report Selections Form
.
Bin Grid Toolbar
Select Bin codes and Count of labels to print.
Note: You can click
Customise Fields (Alt+F5) to show in the UOM in the grid if
UOM
is enabled.
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort
(Ctrl+F2)
Sort the list.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Ctrl+I)
Import a tab delimited or CSV file listing labels to print.
Format is Bin Code, Count. Count defaults to 1 if not specified.
Export
(Ctrl+E)
Export contents of the grid to a tab delimited file, same columns as the import format.
Start from label
On sheet feed labels, you can start printing a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.

---

## IC Bin Count

Source: https://accredo.co.nz/webhelp/ICBinCount.htm

IC Bin Count
Bin tracking is only available for Accredo Saturn Stock Locations.
Navigator > Tasks > Inventory Control > Bin Processing > Generate Bin Count - OR -
Navigator > Tasks > Inventory Control > Bin Processing > Bin Count List >
Insert
button
Confirm Products and quantities in a Bin. Counted but Unposted Bin Counts create pending Variance movements and add to the Variance quantities.
This option available if
Bin Tracked
is selected for a
Location
.
Header fields
Period
Current System Period (default), select a period to post to, dates in the grid must be within the date range for the selected period.
ID, Location, Bin Code
Fields show Batch ID, Location and Bin Code (read-only).
Vertical toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
details
(F11)
Edit a movement batch.
Insert
(F4)
Generate
a new bin count.
While a bin count is in progress the bin is locked, transactions with tracking detail for the bin may not be posted.
Delete
(F3)
Delete the bin count. Only available for saved, unposted batches, when the user has permission.
Print report
(Ctrl+P)
Print an IC Bin Count report of the information in the grid.
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
Delete Nil Lines
(Alt+D)
Delete all nil quantity lines from the batch. A line is considered nil if the quantity is zero.
Add Missing Products
Adds products in the bin which have not been counted.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Batch tab
Date
The date that adjustment transactions will be posted. Must be within the Period selected. Defaults to the System Date.
Store Person
The Store Person associated with the receipt batch. This defaults from the User's
Default Store Person Code
.
Details
Optional description for the bin movement batch header.
Store Person
The Store Person associated with the bin movement batch. This defaults from the User's
Default Store Person Code
.
Reference
Reference for the bin movement batch.
Comment
Comment for the bin movement batch.
Post Status
The status of the Bin Count. You can change between
Counted
and
Uncounted
using the button at the bottom of the form prior to posting. If the Bin Count has been posted, this will show
Posted
, and cannot be changed.
Print Status
Shows the batch print status (read-only). Print Status is set to Printed when a batch is printed.
IC Bin Count Grid
Product Code
The product counted.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Counted / UOM Counted
The quantity counted.
If UOM Active the
Quantity Counted
will be calculated as the
UOM Quantity Counted * UOM Multiplier
.
Unit
Product unit code.
Serial No
For Products which are Purchase Serial No tracked the Serial No counted.
Lot No
For Products which are Lot No tracked to Lot No counted.
Adjust
Selected
, the default. Variances will be adjusted into or out of stock when posted.
Unselected
, nil adjustments are posted for variances with quantities moved from/to the Unspecified bin.
Variance
The difference between the Counted quantity and the current In Stock quantity for the bin. The quantity that would be adjusted or moved to the Unspecified bin on post.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see the batch line details.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort list
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved on
Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Bin quantities
(Ctrl+Q)
Opens
Bin Tracking Quantities
showing quantities in the bin.
Tracking Panel
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the
tracking
detail for the current line.
When the Count is set to Counted count lines collapse to a unique line per Product, Lot No and Serial No and any records not counted but currently In Stock in the bin are added. Tracking is generated where there are differences.
Buttons
Batch List
(Alt+L)
Opens
IC Bin Count List
, you can view a list of all unposted batches.
Uncounted / Counted
Changes the
Post Status
of the bin count from
Counted
to
Uncounted
or from
Uncounted
to
Counted
. When a bin count is set as
Counted
, Variances are recorded. If you change a
Counted
bin count to
Uncounted
, variances are removed.
Missing Products are added to the count when it is set
Counted
. This may be done earlier using the
Add Missing Products
button.
Post
(Alt+S)
Post adjustment transactions for the lines with variances.
Save
(F9)
Save the batch. Blank lines at the end will be trimmed. You can re-open saved batches for further editing and/or posting from
IC Bin Count List
.
Cancel
(Esc)
Close without saving.

---

## IC Bin Count List

Source: https://accredo.co.nz/webhelp/ICBinCountList.htm

IC Bin Count List
Bin tracking is only available for Accredo Saturn Stock Locations.
Navigator > Tasks > Inventory Control > Bin Processing > Bin Count List
This option available if
Bin Tracked
is selected for a
Location
.
Click
to make selections, and use the
lookups
.
Selections
Location
Select from the
Lookup
. Click
Show All
(Ctrl+A)
to show all selected batches for all locations.
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
Default is Range of Periods with From Period set to First Available period for IC or period of first Current Batch whichever is earlier, and To Period set to Last Available period for IC.
Store Person
You can filter the list by selecting a Store Person.
Post Status
Select to show batches that are:
Uncounted
Counted
Posted
Deleted
(excludes deleted batches)
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Bin Counts
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Bin Counts
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Bin Code
The Bin Code for the count.
Batch
The Batch identifier.
Details
Details entered for the batch.
Date
Date of the batch.
Status
Status of the bin count.
Location
Location of the bin.
Period
Period the batch occurs in.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Generate
a bin count.
Delete
(F3)
Delete the bin count. Only available for saved, unposted batches, when the user has permission.
Open Details
(F12)
Opens Bin Count data entry. View the details for the Bin Count including all lines. You can edit an unposted Bin Count.
Print
(Ctrl+P)
Print the IC Bin Count List. You can save as an Excel worksheet or PDF file and send as an email attachment.
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
Refresh the Bin Count list to reload changes other users may have made.
Create List View
(Alt+L)
Save the current list state as a
List View
.
Post selected
(
Alt+T
)
Post the selected bin count.
Post all up to current period
(
Alt+A
)
Post all bin counts up to the selected period.
Find
(Ctrl+F)
Find a bin count using the Batch ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.

---

## IC Bin Label Designer

Source: https://accredo.co.nz/webhelp/ICBinLabelDesigner.htm

IC Bin Label Designer
Navigator > Setup > Inventory Control > Bin
Label Designer

---

## IC Bin Movement

Source: https://accredo.co.nz/webhelp/ICBinMovement.htm

IC Bin Movement
Bin tracking is only available for Accredo Saturn Stock Locations.
Navigator > Tasks > Inventory Control > Bin Processing > Bin Movement - OR -
Navigator > Tasks > Inventory Control > Bin Processing > Bin Movement List >
Insert
button
This option available if
Bin Tracked
is selected for a
Location
.  Accredo Saturn only.
Products can be moved between bins in a batch. Unposted batches create pending Variance detail movements and add to the detail Variance quantities.
You can select to enter a Batch Type of:
Put-Away
to move stock from a source bin to destination bins, e.g where stock is initially receipted to an inwards stock bin then put away in the warehouse.
Pick
to move stock into a destination bin from source bins, e.g to pick stock for an order to a dispatch bin ready for shipping to a customer.
Header fields
Period
Current System Period (default), select a period to post to.
Batch Class & ID
Fields show Batch class and Batch ID (read-only).
Vertical toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit details
(F11)
Edit a movement batch.
Insert
(F4)
Select a batch class from the menu to insert a new Bin movement batch.
Delete
(F3)
Delete the bin movement batch. Only available for saved, unposted batches, when the user has permission.
Print report
(Ctrl+P)
Print an IC Bin Movement report of the information in the grid. The information included may be customised from the Report Selections dialog under Options > Customise.
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
Delete Nil Lines
(Alt+D)
Delete all nil quantity lines from the batch. A line is considered nil if the quantity is zero.
Add Products from Bin
Available for
Put-Away
batches. Opens
Select Products
to add lines to the bin movement.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Batch header
Location
The bin tracked location for the bin movement.This defaults from the User's
Default Location Code
.
Bin
The default bin for new lines. For
Put-Away
batches the bin stock is being moved from, for
Pick
batches the bin stock is being moved to.
Date
The date that the batch will be posted for. Must be within the Period selected. Defaults to the System Date.
Details
Optional description for the bin movement batch header.
Store Person
The Store Person associated with the bin movement batch. This defaults from the User's
Default Store Person Code
.
Reference
Reference for the bin movement batch.
Comment
Comment for the bin movement batch.
Post Status
Posted and Deleted occur as a result of processing options and cannot be changed.
Unposted,
not yet posted, can be edited.
Open
, open and cannot be posted.
Posted,
has been posted and the movements have occurred, cannot be edited.
Deleted,
has been deleted and moved to history.
Print Status
Shows the batch print status (read-only). Print Status is set to Printed when a batch is printed.
IC Bin Movement Grid
Product Code
The product to be moved.
Bin
For
Put-Away
batches the bin stock is being moved from, for
Pick
batches the bin stock is being moved to. Defaults from Bin in the header.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Quantity / UOM Quantity
The quantity to be moved, must be less that or equal to the quantity currently in the bin.
If UOM Active the
Quantity
will be calculated as the
UOM Quantity * UOM Multiplier
.
Unit
Product unit.
Serial No
For Products which are Purchase Serial No tracked the Serial No to be moved.
Lot No
For Products which are Lot No tracked to Lot No to be moved.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see the batch line details.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort list
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved on
Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Bin quantities
(Ctrl+Q)
Opens
Bin Tracking Quantities
showing quantities in the bin.
Tracking Panel
For
Put-Away
batches specifies the bins stock is being moved to.
For
Pick
batches specifies the bin stock is being moved from.
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the
tracking
detail for the current line.
Edit tracking detail if required to specify the bins lines are moving to.
Buttons
Batch List
(Alt+L)
Opens
IC Bin Movement List
, you can view a list of all unposted batches.
Post
(Alt+S)
Post nil adjustment transactions for the lines with bin movement tracking detail.
Save
(F9)
Save the batch. Blank lines at the end will be trimmed. You can re-open saved batches for further editing and/or posting from
IC Bin Movement List
.
Cancel
(Esc)
Close without saving.
In This Section
IC Select Products

---

## IC Bin Movement List

Source: https://accredo.co.nz/webhelp/ICBinMovementList.htm

IC Bin Movement List
Bin tracking is only available for Accredo Saturn Stock Locations.
Navigator > Tasks > Inventory Control > Bin Processing > Bin Movement List
This option available if
Bin Tracked
is selected for a
Location
.(Accredo Saturn Only.)
Click
to make selections, and use the
lookups
.
Selections
Location
Select from the
Lookup
. Click
Show All
(Ctrl+A)
to show all selected batches for all locations.
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
Default is Range of Periods with From Period set to First Available period for IC or period of first Current Batch whichever is earlier, and To Period set to Last Available period for IC.
Store Person
You can filter the list by selecting a Store Person.
Batch Class
Select the type of batches to display from:
Put-Away
Pick
Selection
Select to show batches that are:
Unposted
Posted
Deleted
All Batches
(excludes deleted batches)
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
selections, filter and sorts are not applied to the list until
Select Select Bin Movements
is clicked.
The default value is set in
IC Settings Misc tab
.
Select Bin Movement
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Bin Code
The Bin Code for bin movement.
Batch
The Batch identifier.
Details
Details entered for the batch.
Date
Date of the batch.
Status
Status of the bin movement.
Location
Location of the bin.
Period
Period the batch occurs in.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a bin movement.
Delete
(F3)
Delete the bin movement. Only available for saved, unposted batches, when the user has permission.
Open Details
(F12)
Opens Bin Movement data entry. View the details for the Bin Movement including all lines. You can edit an unposted Bin Movement.
Print
(Ctrl+P)
Print the IC Bin Movement List. You can save as an Excel worksheet or PDF file and send as an email attachment.
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
Refresh the Bin Movement list to reload changes other users may have made.
Create List View
(Alt+L)
Save the current list state as a
List View
.
Post selected
(
Alt+T
)
Post the selected bin movement.
Post all up to current period
(
Alt+A
)
Post all bin movements up to the selected period.
Find
(Ctrl+F)
Find a bin movement using the Batch ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.

---

## IC Bin Processing

Source: https://accredo.co.nz/webhelp/BinProcessing.htm

IC Bin Processing
Accredo Mercury holds stock at a single location and bin. Bin tracking within a location is only available for Accredo Saturn.
For Bin Tracked locations can move products between bins and perform bin counts. These options only available if at least one
Location
is
Bin Tracked
. Saturn only.
In This Section
IC Bin Count List
IC Generate Bin Count
IC Bin Count
IC Bin Movement List
IC Bin Movement

---

## IC Bin Tracking Quantities

Source: https://accredo.co.nz/webhelp/BinQuantities.htm

IC Bin Tracking Quantities
Navigator > Maintain > Inventory Control > Bin Tracking Quantities
For bin tracked locations you can enquire on detail of quantities by bin. (in Accredo Saturn)
Accredo Saturn only.
Selections
Location
Select a bin tracked location to show bin quantities for.
Bin Code
Select a bin at the location to show quantities for.
Include Pending Quantities
Selected
, Products with quantities which are pending for the bin but not posted e.g. shipped quantities coming into the bin are included.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information.
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
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Bins

Source: https://accredo.co.nz/webhelp/ICBins.htm

IC Bins
Navigator > Maintain > Inventory Control > Bins
Setup and maintain the Bin Codes for each location (in Accredo Saturn).
This is only available when
Coded Bin Lookup
is selected in
IC Settings
.
Selections
Location
Select the location to display Bin Codes for. (Accredo Saturn Only)
Fields
Bin Code
The code or identifier for the Bin.
Bin Name
The name of the bin code.
Priority
The Priority for picking, used for
Generating Outward Tracking
if Location is
Bin Tracked
. With priority
1
most preferred, priority
9
least preferred.  (Accredo Saturn Only)
Picking Sequence
Optionally set a sequence number to sort bins by for picking, e.g. the sequence bins are laid out in a warehouse.
Generate From
Selected
, (default) the bin will be included when
Generating Outward Tracking
.
Unselected
, the bin will be excluded when Generating Outward Tracking but may be selected manually and from the Bin picker. (Accredo Saturn Only)
Custom 1
A 30 character field for reference.
Custom 1
label can be replaced in
IC Settings
.
Custom 2
A 30 character field for reference.
Custom 2
label can be replaced in
IC Settings
.
Inactive
When
Selected
, the Bin Code is inactive.
Grid Toolbars
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new Bin Code.
Delete
(F3)
Delete the Bin Code.
Print
(Ctrl+P)
Print a list of Bin Codes for the Location (in Accredo Saturn).
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
Find
(Ctrl+F)
Find
a document using the Document ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Categories

Source: https://accredo.co.nz/webhelp/ICCategories.htm

IC Categories
Navigator > Maintain > Inventory Control >
Categories 1 & 2

---

## IC Change Tracking Log

Source: https://accredo.co.nz/webhelp/InventoryControlTrackingLog.htm

IC Change Tracking Log
Navigator > Setup > Inventory Control >
Change Tracking Log
See Also
Inventory Control - Setup

---

## IC Component

Source: https://accredo.co.nz/webhelp/ICComponents.htm

IC Component
Navigator > Maintain > Inventory Control > Components > Parts tab
Setup and maintain the component structure for
Manufactured
and
Kitset
products.
Manufactured
products are diminishing products which are held in stock and manufactured from other products, which are listed as components.
Manual Kitsets
are non-diminishing products that are sold at the price specified on the kitset. Their components are issued from stock when invoices are posted. You can select to show or hide usages (components) on invoices and orders.
Automatic Kitsets
are non-diminishing products sold with the individual components invoiced separately. A Product Code of an Automatic Kitset provides a quick way of pulling the components onto the invoice or order.
Component Header
Select Product
Select the Product to add or edit components for.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit Components.
Print
(Ctrl+P)
Print the Component report.
Update Product Weight
Update the Product weight with the total weight of the components.
Update Product Volume
Update the Product volume with the total volume of the components.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Header
Component Mode
None
- Components not in use.
Manufacture
- for
Diminishing
products only, product can be Manufactured from components.
Automatic Kitset
- for
Non-Diminishing
products only. When product is selected on a Sales Order or Invoice the Components are expanded. It is the components which are sold at their sell prices.
Manual Kitset
- for
Non-Diminishing
products only. When product is selected on a Sales Order or Invoice components are expanded as Usages. It is the Kitset product which is sold at the kitset selling price.
You can select whether to show or hide Usages (i.e. components) for Manual Kitsets on invoices. Set the default for
Hide Usages by Default
in
Users, Groups and Roles - Preferences tab
.
Note: Kitsets are not available for selection in Job Costing.
Non Diminishing
Clear,
stock quantities increase and decrease as Sales, Receipts and Credits are processed. In the context of Components product may be a Manufacture.
Selected
, sales figures are recorded, but no stock quantities are maintained. In the context of Components product may be a Kitset.
Indicates the current state for the Product and may be changed from
Product
maintenance.
Automatic Subcomponent
Sub-assemblies included as components of
Manufactured
(diminishing) products are other diminishing products with components.
When a subassembly is required for a
Manufacture transaction
, and there is insufficient stock of the subassembly, the Automatic / Manual selection determines how the insufficiency is handled.
If
Automatic,
then if there is sufficient stock of the components to make up the subassembly, then it will automatically be manufactured and used to make up the shortfall.
If
Manual
, then insufficiency is reported regardless of availability of the components on the subassembly.
Note automatic sub component behaviour does not apply for Manufacture Batches, sub-assemblies must be manufactured separately as required.
Serial No
Enabled if Product has
Serial Nos
Purchase
selected, settings so that Serial Nos can be generated and assigned during Manufacture from Manufacture Batches.
Prefix
- Optional text to include at the start of generated serial numbers.
Counter
- Incrementing number to generate next serial number from. Updated when a Manufacture batch is posted.
Suffix
- Optional text to include at the end of generated serial numbers.
Length
- Serial number counter will be zero padded to create serial numbers of the specified length inclusive of any suffix or prefix.
Expiry
Enabled if Product is
Lot tracked
and
Expiry Date
is selected.
Unit
- Days, weeks, months or years, defaults initially from Minimum Expiry Unit on Product.
Count
- The number of Expiry Unit to apply to calculate the Expiry Date for the Manufacture.
Used to calculate Expiry Date from Manufacture Date for a Manufacture Batch.
Total Costs Panel
Customise
(Alt+F5)
Opens
Customise Fields
- you can customise fields visible in the totals panel.
Standard Cost
Total of Standard Costs for the components and quantities.
Latest Cost
Total of Latest Costs for the components and quantities.
Average Cost
Total of Average Costs for the components and quantities.
Total Weight
The total weight of the components.
Total Volume
The total volume of the components.
Location
When a Location is selected, Product Quantities shown in the Parts grid are only for the selected Location. Click
All Locations
to show all locations. (Accredo Saturn Only)
In This Section
IC Component - Parts tab
IC Component - Prices tab
IC Components - Links tab
IC Components - Memos tab

---

## IC Component - Parts tab

Source: https://accredo.co.nz/webhelp/ICComponents_Parts.htm

IC Component - Parts tab
Navigator > Maintain > Inventory Control > Components > Parts tab
Setup and maintain the component parts for
Manufactured
and
Kitset
products.
Grid Fields
Type
The Component Type select
Variable, Fixed
or
Narrative
.
Variable
Enter product code and quantity. Quantity of the component used for a  Manufacture or Kitset is extended by the quantity Manufactured or Supplied.
Fixed
Enter product code and quantity. Quantity of the used for a Manufacture is not extended by Quantity Manufactured. For example used where there is a fixed cost for setup regardless of number manufactured.
Fixed components are only available for Manufacture Batches and are not included in
Manufacture Transactions
or Kitsets.
Narrative
Enter extended lines of text. Click
Narrative
(F2)
in the Description field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Narrative
components are not included in
Manufacture Transactions
.
Narrative
components expand as
Sticky Narrative
lines for Kitsets in OE Sales Orders in order to retain the connection to the kitset.
Part Code
Select the products to be used.
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
Enter the quantity required for each Variable or Fixed part.
Note: If quantity is not entered the part will be not be included in
Manufacture Transactions
or Manual Kitsets if
Supply Whole Manual Kitsets
is selected.
Unit
Will default from the part.
Sub
This will be selected if the component product has parts of its own. Indicates that the product is a subassembly.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a row in the grid for a new part to be added.
Move
(Shift+Up) (Shift+Down)
Select a line and move it up or down the list.
Delete
(F3)
Remove a part from the recipe.
Open
(F12)
Opens the component in IC Component, if the component has its own components.
Sort list
(Ctrl+F2)
Select the sort criteria in
Sort - Part
.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Copy components from
(Ctrl+I)
Allows you to copy components from another Product. You will be prompted for the Product Code to copy from.
Delete All
(Ctrl+F3)
Remove all components shown in the Component grid.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Component - Prices tab

Source: https://accredo.co.nz/webhelp/ICComponents_Prices.htm

IC Component - Prices tab
Navigator > Maintain > Inventory Control > Components > Prices tab
Cost Prices
Component Cost
is the total Cost of the components entered for the item. Cost Prices are shown if you have Cost Price permission.
Component Price
is the total selling price based on the components entered.
Product Cost
is the cost prices from the product record.
Product Price
is the sell prices from the product record.
The buttons in the centre field are available when:
You are in Edit mode (press
F11
).
You have Permission to edit that price.
The Total Price and current Product Price are different (the available button will indicate this).
When Kitsets are accessed during invoicing, the records for all the components must also be accessed. This means that if a Kitset is made up of a large number of components, there can be some speed degradation.
For multi-User systems, if another User is editing a component you will be denied access to the Kitset.
Component Costs
Displays the Standard, Latest and Average component costs. Read-only.
Product Costs
Displays the Standard, Latest and Average Product costs. Can be updated.
Copy All Prices
(Shift+F4)
Copy all Component Costs and Prices to Product Costs and Prices. All Product fields are updated.
Copy Cost Prices
(Shift+F4)
Copy all Component Costs to Product Costs. All Product Cost Price fields are updated.
Copy price
(Ctrl+=)
Copy the corresponding Component Cost to the Product Cost.
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
Copy price
(Ctrl+=)
Copy the corresponding Component Price to the Product Price.
Markup prices
(Alt+M)
Applies the Markup percentage to the Cost or Sell price to determine the Selling Price, based on settings in
IC Settings - Prices tab
.
Copy Sell Prices
(Alt+S)
Copy all Component Prices to Product Prices. All Product Sell Price fields are updated.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Components - Links tab

Source: https://accredo.co.nz/webhelp/ICComponents_Links.htm

IC Components - Links tab
Navigator > Maintain > Inventory Control > Components >
Links tab

---

## IC Components - Memos tab

Source: https://accredo.co.nz/webhelp/ICComponents_Memos.htm

IC Components - Memos tab
Navigator > Maintain > Inventory Control > Components >
Memos tab
For each Account File you can specify a default Memo type. You can also set an Account File as the default for
Enter Memos
.

---

## IC Count Designer

Source: https://accredo.co.nz/webhelp/ICCountDesigner.htm

IC Count Designer
Navigator > Setup >Inventory Control > Count Designer
You can design your own Count Report, or open and modify an existing count report design. To design a count report quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
The IC Count Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code.
Name
Iterators filter records that are shown in the report. Available Iterators are:
Lines
- Lines in the IC Stocktake Count.
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Count Designer in addition to the standard
objects
are:
Count
Fields from the Count records.
Product
Fields from the Product record.
Stocktake
Fields from the Stocktake record.
Sample IC Counts are provided with the Accredo Server Install, and are also available on the Accredo website. Sample IC Counts include:
ICCount.pfd
- standard IC Count.
ICCount_AlternateShading.pfd
- IC Count with alternate rows shaded.
To use documents downloaded from the website, ensure your document designer is the latest version.

---

## IC Count Sheets

Source: https://accredo.co.nz/webhelp/ICCounts.htm

IC Count Sheets
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Print Count Sheets
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake >
Print Count Sheets
Print Count Sheets for the stocktake. Default report file names can be set from
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IC Count Designer
.
See also
Report Selections Form
.

---

## IC Edit Count

Source: https://accredo.co.nz/webhelp/ICEnterStocktakeCount.htm

IC Edit Count
Navigator > Tasks > Inventory Control > Stocktake Processing > Edit Count
For
Single, Additive
and
Detailed
Stocktakes only, selected in
IC Settings - Stocktake tab
.
Select Count ID
Enter the Stocktake Count number.
Location
Select a location to display counts for in the grid. (Accredo Saturn Only)
Counts Grid
Normal counts are listed in the grid. You can double-click a Count in the grid to open it. If there is no
Count ID
entered, you can click
Open
to open the Count selected in the grid.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Buttons
Open
(F9)
If a Count ID is entered, opens
IC Stocktake Count
for the selected Stocktake Count.  You can also press
Enter
to open the Stocktake Count.
If no Count ID is entered, and a Count is selected in the grid, opens
IC Stocktake Count
for the the selected Count.
Close
(Esc)
Closes the form window.

---

## IC End Of Period

Source: https://accredo.co.nz/webhelp/ICEndOfPeriodUpdate.htm

IC End Of Period
Navigator > Tasks > Inventory Control > End Of Period
You can move the Current Period for Inventory Control processing and reporting forward one period.
Normally this is done each month at the end of the accounting period after:
Any Stocktake variances have been updated.
All IC Batches (Manufacture Batches, Adjustment Batches, Receipt Batches) have been posted.
All Invoices and Credits have been posted.
All Shipment Receipts have been posted.
All JC Batches have been posted.
End of period report lists have been run.
IC End of Period Update
Take a monthly backup as well as the daily backup before you perform an End Of Period.
End of period is not reversible, it should usually be done after all processing for the period is completed, though transactions may still be posted subject to available periods and other constraints, and reports are available as at any period.
Before the update form is displayed, a number of checks occur and warnings will appear if there are unposted documents or batches or if no transactions have been posted for the period.
View the Current Period to ensure you are in the correct period.
Usually you would print reports prior to the End Of Period.
Click
Run
to proceed with the End of Period which will:
Advance the Current Period and available period range, setting status for the period to Open if required.
Add balance records as required.
Revalue stock on hand if that has not been done prior.
Set value sold, cost of sales and gross margin month to date figures to zero.

---

## IC Enter Adjustment Batch

Source: https://accredo.co.nz/webhelp/ICAdjustmentBatch.htm

IC Enter Adjustment Batch
Navigator > Tasks > Inventory Control > Enter Adjustment Batch
Stock adjustments can be entered in a batch. Unposted batches create pending Variations and add to the Stocktake Variance quantities.
Header fields
Period
Current System Period (default), select a period to post to, dates in the grid must be within the date range for the selected period.
Batch Type & ID
Fields show Batch type and Batch ID (read-only).
Vertical toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit details
(F11)
Edit an adjustment batch.
Insert
(F4)
Insert a new adjustment batch.
Duplicate
(Shift+F4)
Insert a batch by duplicating or duplicating contra the current adjustment batch. Duplicate Contra will replicate the current adjustment batch with reverse signed quantities.
Delete
(F3)
Delete the adjustment batch. Only available for saved, unposted batches, when the user has permission.
Print report
(Ctrl+P)
Print an IC Adjustment Batch report of the information in the grid.
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
Reprice
(Alt+R)
Re-price the batch with changes that occurred since the last save. This will recost adjustments and recalculate the totals. Batches are recosted on Post automatically.
Delete Nil Lines
(Alt+D)
Delete all nil value lines from the adjustment batch. A line is considered nil if the quantity is zero.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Batch tab
Location
The location for the adjustment transactions.This defaults from the User's
Default Location Code
.
Changing the Location Code will change the Location on each line. (Accredo Saturn Only)
Date
Date of the transactions. Must be within the Period selected. Defaults to the System Date.
Store Person
Store Person
code. Defaults from the User
Default Store Person Code
, can be changed. If no Store Person code is entered, the default is
0000.
Details
Optional description for the adjustment batch header.
Branch
The Branch of the Location. (Accredo Saturn Only)
Reference
Reference for the adjustment batch.
Comment
Comment for the adjustment batch.
Department
The Department of the Location. (Accredo Saturn Only)
Post Status
Posted and Deleted occur as a result of processing options and cannot be changed.
Unposted,
not yet posted, can be edited.
Open
, open and cannot be posted.
Posted,
has been posted and the adjustments have occurred, cannot be edited.
Deleted,
has been deleted and moved to history.
Print Status
Shows the batch print status (read-only). Print Status is set to Printed when a the batch is printed.
IC Adjustment Batch Grid
Type
The Line Type select
Product
or
Narrative
.
Product
Enter product items.
Narrative
Enter extended lines of text, such as a detailed description of the reason for the adjustments. Click
Narrative
(F2)
in the Description field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Product Code
The product this adjustment affects.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Quantity / UOM Quantity
The quantity to be adjusted.
If UOM Active the
Quantity
will be calculated as the
UOM Quantity * UOM Multiplier
.
Unit
Product unit code.
Cost Price / UOM Cost Price
The Cost Price. When a Product code is entered, this is loaded with the appropriate Cost Price from the Product record. The UOM Cost Price is calculated as the
Cost Price
*
UOM Multiplier.
Cost Value
The cost value is calculated as the product of the Cost Price and the quantity entered.
Branch Department
Available for
Perpetual Integration
only, read-only for
Periodic Integration
.These fields are default from the Location. (Accredo Saturn Only)
GL Account
Available for
Perpetual Integration
only and requires IC > Transactions > GL Account permission.
The GL Account for the adjustment transaction. If no Account is entered, the GL Adjustment Account of the Stock Group will be used.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see the batch line details.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort list
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved on
Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Product quantities
(Ctrl+Q)
Opens
Product Quantity
showing quantities at each location (in Accredo Saturn). Product Quantities lookup provides a quick overview of stock availability and pending stock movements as you enter stock transfers, and allows juggling stock 'on the fly'.
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
Stock Panel
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the panel.
UOM Code (
UOM
Active only)
UOM code for the Product.
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
Commit / UOM Commit
Quantity of the selected product On Order or Shipped that is already committed to a Job.
Transit / UOM Transit
Quantity of the selected product in transit.
Totals Panel
Total Quantity
Total quantity of all the products.
Total Cost
Total cost of all the products.
Total Weight
The total weight of all the products.
Total Volume
The total volume of all the products.
Buttons
Batch List
(Alt+L)
Opens
IC Adjustment Batch List
, you can view a list of all unposted batches.
Post
(Alt+S)
Post adjustment transactions for the IC Product records.
Save
(F9)
Save the batch. Blank lines at the end will be trimmed. You can re-open saved batches for further editing and/or posting from
IC Adjustment Batch List
.
Cancel
(Esc)
Close without saving.
In This Section
IC Adjustment Batch - Links tab
IC Adjustment Batch - Memos tab

---

## IC Enter Manufacture Batch

Source: https://accredo.co.nz/webhelp/ICManufactureBatch.htm

IC Enter Manufacture Batch
Navigator > Tasks > Inventory Control > Enter Manufacture Batch
This allows you to allocate stock to a Manufacture, and allows substitutions within a manufacture by editing batches.
You can manufacture products from components setup in
IC Component
. You can also view stock availability and shortages for manufacture, and print a report. Only Diminishing products with component details can be manufactured.
Unlike single
Manufactures
, Manufacture Batches are single-level only, meaning that sub-assemblies will be allocated but not manufactured. Any manufacture of sub-assemblies required must be entered as separate batches. You can use the
Manufacture Component
button on the
grid toolbar
to create batches for sub-assemblies.
Header fields
Period
Current System Period (default), select a period to post to, dates in the grid must be within the date range for the selected period.
Batch Type & ID
Fields show Batch type and Batch ID (read-only).
Vertical toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit a manufacture batch.
Insert
(F4)
Insert a new manufacture batch.
Duplicate
(Shift+F4)
Insert a batch by duplicating or duplicating contra the current manufacture batch. Duplicate Contra will replicate the current manufacture batch with reverse signed quantities.
Delete
(F3)
Delete the manufacture batch. Only available for saved, unposted batches, when the user has permission.
Print
(Ctrl+P)
Print an IC Manufacture Batch report of the information in the grid.
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
Reprice
(Alt+R)
Re-price the batch with changes that occurred since the last save. This will recost usages and recalculate the totals.
Note: Cost Price of products set as
Manually Costed
will not be changed.
Delete Nil Lines
(Alt+D)
Delete all nil quantity lines from the manufacture batch. A line is considered nil if the quantity is zero.
Print Manufacture Sheet
Prints a Manufacture Sheet, using
IC Print Manufacture Sheets
. Sets Print Status to Printed.
Print Log
View the
Print Log
(requires Read access Permission for Company > Settings).
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Batch tab
Product
Type or select the Product Code to be manufactured. You can use the
Accredo Lookups
to find the Product.
When the Product Code is changed, the components for the selected Product will be displayed in the grid, but the Quantity selected will not change.
Location
The location the stock will be manufactured into. This is also the default location that components will be sourced from. This defaults from the User's
Default Location Code
.
Changing the Location Code will change the Location on each line. (Accredo Saturn Only)
Date
The date of the manufacture batch. Defaults to the System Date. For
Lot No
tracked Products this is the
Lot Date
.
Store Person
Store Person
code. Defaults from the User
Default Store Person Code
, can be changed. If no Store Person code is entered, the default is
0000.
UOM Code
(
UOM
Active only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
UOM Quantity
(
UOM
Active Only)
The quantity of the UOM of the product. The
Quantity
will be calculated as the
UOM Quantity * UOM Multiplier
.
UOM Multiplier
(
UOM
Active Only)
The multiplier of the UOM Code. Read-only.
Quantity
The quantity of items in the manufacture batch. Entering the Quantity or UOM Quantity will populate the components in the grid.
The Unit of the Product is shown.
Details
Optional description for the manufacture batch header.
Bin Code
If the location is bin tracked select the bin stock will be manufactured into. This defaults from the bin code specified for the location in
IC Product - Locations tab
. (Accredo Saturn Only)
Reference
Reference for the manufacture batch.
Serial No
If the Product has Serial Nos
Purchase
selected, either Serial Nos will generate on post from the Serial No settings in the
IC Component
record, or a quantity of 1 may be manufactured and the Serial No entered directly.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
Lot No
The Lot No for the Manufacture,
Lot No
tracked Products only. May be generated from Lot Date or Expiry Date if selected for the Product.
Branch Department
These fields are read-only as they are determined from the Location. (Accredo Saturn Only)
Post Status
Posted and Deleted occur as a result of processing options and cannot be changed.
Unposted,
not yet posted, can be edited.
Open
, open and cannot be posted.
Posted,
been posted and the manufacture batch has occurred, cannot be edited.
Deleted,
has been deleted and moved to history.
Print Status
Shows the batch print status (read-only). Print Status is set to Printed when a Manufacture Sheet is printed for the batch.
Expiry Date
The Expiry Date for the Lot,
Lot No
and
Expiry Date
tracked Products only.
Comment
Comment for the adjustment batch.
Grid Fields and Totals
, see
IC Manufacture Batch - Grid
.
Tracking Panel
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the
tracking
detail for the current line.
Totals Panel
Customise
(Alt+F5)
Opens
Customise Fields
- you can customise fields visible in the totals panel.
Unit Cost Price / UOM Unit Cost Price
Unit Cost Price from the Product record.
Cost Value Exclusive
The exclusive cost value of the manufacture batch.
UOM Code
(
UOM
Active Only)
The UOM Code of the Product.
In Stk / UOM In Stk
Quantity of the product in stock on hand.
Alloc / UOM Alloc
Quantity of the product currently allocated to customers.
Avail / UOM Avail
Quantity of the product available for sale.
Bk Ord / UOM Bk Ord
Quantity of the product on back order for customers.
Ship / UOM Ship
Quantity of the product on shipments not yet receipted.
On Ord / UOM On Ord
Quantity of the product on order from suppliers.
Total Weight
The total weight of the components.
Total Volume
The total volume of the components.
Buttons
Batch List
(Alt+L)
Opens
IC Manufacture Batch List
, you can view a list of all unposted batches.
Post
(Alt+S)
Generate usages for the IC Product records. You can print a report of the posted transactions before close.
Save
(F9)
Save the batch. Blank narrative lines at the end will be trimmed. You can re-open saved batches for further editing and/or posting from
IC Manufacture Batch List
.
Cancel
(Esc)
Close without saving.
In This Section
IC Manufacture Batch - Grid
IC Manufacture Batch - Links tab
IC Manufacture Batch - Memos tab
See Also
Inventory Control - Tasks

---

## IC Enter Manufactures

Source: https://accredo.co.nz/webhelp/ICManufacture.htm

IC Enter Manufactures
Navigator > Tasks > Inventory Control > Enter Manufactures
Manufacture transactions can be entered when
Allow IC Manufacture Transactions
is
Selected
in
IC Settings
.
IC Manufacture Batches are recommended for processing Manufactures where stock needs to be allocated, and must be used when Tracked ProductsTracking or Bin Tracked Locations (Saturn Only) are involved.
You can manufacture products from components setup in
IC Component
. You can also view stock availability and shortages for manufacture, and print a report. Only Diminishing products with component details can be manufactured.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
This button is unavailable as Manufactures cannot be edited.
Insert
(F4)
Create a new manufacture.
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
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Transaction tab
Product Code
The Product to be manufactured.
Note:
You cannot manufacture Non-Diminishing products.
To manufacture products which are Lot No or Serial No tracked or have components which are tracked use
IC Manufacture Batch
.
Branch Department
These fields are read-only as they are determined from the Location. (Accredo Saturn Only)
Location
The location the product will be manufactured into.
To manufacture for locations which are bin tracked use
IC Manufacture Batch
. (Accredo Saturn Only) (Accredo Saturn Only)
Date
The date of the manufacture. Defaults to the date of the previous manufacture, or the System Date.
Reference
Reference for the transaction. This is retained over a series of transactions.
Serial No
The field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
UOM Quantity
(
UOM
Active Only)
The quantity of the UOM of the product. The
Quantity
will be calculated as the
UOM Quantity * UOM Multiplier
.
UOM Multiplier
(
UOM
Active Only)
The multiplier of the UOM Code. Read-only.
Quantity
The quantity of items, normally a positive figure unless you are reversing a previous transaction or correcting an error.
Cost Value
The cost value is calculated as the product of the Cost Price (standard, average or latest depending on the stock valuation basis) and the quantity entered. If the Cost Prices are GST inclusive, GST is first deducted, that is, the cost value is GST exclusive.
Quantities
Information only. The fields are the same as those on the Quantity tab of IC Products. The In Stock and Available quantities will update when the transaction is posted. The values shown are for the selected location (in Accredo Saturn).
Manufacture Entry window - Component grid
Part Code
The Part Code of the manufactured item.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use in the
IC Component
form.
Used / UOM Used
The quantity to be used (or has been used) to manufacture the selected quantity of the finished item.
Manufactured / UOM Manufactured
The quantity that will be (or may have been) manufactured to complete the manufacture. Only components which are subassemblies (that is, have components) and have
Component Mode
set to Automatic, can be manufactured.
Unit
The unit for the component, for example, Doz.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Open the component details.
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
Previous Shortage
(Alt+F7)
Shows the previous component on the grid with an insufficient stock level to complete the transaction.
Next Shortage
(Alt+F8)
Shows the next component on the grid that has an insufficient stock level to complete the transaction.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Buttons
Print
(Ctrl+P)
Takes a snapshot of the data in the grid to print a report from - available before and after
Save.
Save
(F9)
Saves the manufacture transaction and posts all usages. If there are insufficient quantities available for a component you will be asked if you are sure you want to save. Answering Yes will continue and result in negative available stock for these components. Selecting No will cancel the save and return you to the manufacture. After saving, the window will become read-only. At this point, you can print a report of the posted manufacture before closing the window.
Cancel
(Esc)
Cancels the current transaction entry.
Manufacturing creates 2 types of transactions
Usage
For each component stock item used in the manufacture a usage transaction is posted. The usage quantity is increased by the quantity used and the closing stock is decreased. Usages have no effect on sales, cost of sales or gross margins.
Manufacture
For each stock item manufactured a manufacture transaction is posted. The manufactured quantity and closing stock are increased by the quantity manufactured. Manufactures have no effect on sales, cost of sales or gross margins. If you operate with subassemblies which are manufactured both a manufacture and a usage will be posted to the subassembly.
Hint: If you have a finished item to disassemble into components, you can enter a negative manufacture quantity.
In This Section
IC Manufacture - Links tab
IC Manufacture - Memos tab

---

## IC Enter Memos

Source: https://accredo.co.nz/webhelp/ICEnterMemos.htm

IC Enter Memos
Navigator > Tasks > Inventory Control >
Enter Memos
Defaults for inserting Memos, Alarms and Reminders are set in
IC Settings - Memos tab
.

---

## IC Enter Receipt Batch

Source: https://accredo.co.nz/webhelp/ICReceiptBatch.htm

IC Enter Receipt Batch
Navigator > Tasks > Inventory Control > Enter Receipt Batch
Receipts can be entered in a batch. Unposted batches create pending Shipped movements and add to the Shipped quantities.
This option available if
Allow IC Sourced Receipts
is
Selected
in
IC Settings
,  if AP is installed use
AP Shipments
for Receipting.
Header fields
Period
Current System Period (default), select a period to post to, dates in the grid must be within the date range for the selected period.
Batch Type & ID
Fields show Batch type and Batch ID (read-only).
Vertical toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit details
(F11)
Edit a receipt batch.
Insert
(F4)
Insert a new receipt batch.
Duplicate
(Shift+F4)
Insert a batch by duplicating or duplicating contra the current receipt batch. Duplicate Contra will replicate the current receipt batch with reverse signed quantities.
Delete
(F3)
Delete the receipt batch. Only available for saved, unposted batches, when the user has permission.
Print report
(Ctrl+P)
Print an IC Receipt Batch report of the information in the grid.
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
Reprice
(Alt+R)
Re-price the batch with changes that occurred since the last save. This will recost receipts and recalculate the totals.
Delete Nil Lines
(Alt+D)
Delete all nil quantity lines from the batch. A line is considered nil if the quantity is zero.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Batch tab
Location
The location for the receipt transactions.This defaults from the User's
Default Location Code
.
Changing the Location Code will change the Location on each line. (Accredo Saturn Only)
Date
Date of the transactions. Must be within the Period selected. Defaults to the System Date.
Store Person
The Store Person associated with the receipt batch. This defaults from the User's
Default Store Person Code
.
Details
Optional description for the receipt batch header.
Branch
The Branch of the Location. (Accredo Saturn Only)
Reference
Reference for the receipt batch.
Comment
Comment for the receipt batch.
Department
The Department of the Location. (Accredo Saturn Only)
Post Status
Posted and Deleted occur as a result of processing options and cannot be changed.
Unposted,
not yet posted, can be edited.
Open
, open and cannot be posted.
Posted,
has been posted and the receipts have occurred, cannot be edited.
Deleted,
has been deleted and moved to history.
Print Status
Shows the batch print status (read-only). Print Status is set to Printed when a the batch is printed.
IC Receipt Batch Grid
Type
The Line Type select
Product
or
Narrative
.
Product
Enter product items.
Narrative
Enter extended lines of text, such as a detailed description of the reason for the receipts. Click
Narrative
(F2)
in the Description field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Product Code
The product this receipt affects.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Quantity / UOM Quantity
The quantity to be receipted.
If UOM Active the
Quantity
will be calculated as the
UOM Quantity * UOM Multiplier
.
Unit
Product unit code.
Cost Price / UOM Cost Price
The Cost Price. When a Product code is entered, this is loaded with the appropriate Cost Price from the Product record. It may be edited and will update latest and average costs when the receipts are posted. The UOM Cost Price is calculated as the
Cost Price
*
UOM Multiplier.
Cost Value
The cost value is calculated as the product of the Cost Price and the quantity entered.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see the batch line details.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort list
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved on
Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Product quantities
(Ctrl+Q)
Opens
Product Quantity
showing quantities at each location (in Accredo Saturn). Product Quantities lookup provides a quick overview of stock availability and pending stock movements as you enter stock transfers, and allows juggling stock 'on the fly'.
Tracking Panel
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the
tracking
detail for the current line.
Stock Panel
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the panel.
UOM Code (
UOM
Active only)
UOM code for the Product.
In Stk / UOM In Stk
Quantity of the selected product in stock on hand.
Alloc / UOM Alloc
Quantity of the selected product currently allocated to customers.
Avail / UOM Avail
Quantity of the selected product available for sale.
Bk Ord / UOM Bk Ord
Quantity of the selected product on back order for customers.
Ship / UOM Ship
Quantity of the selected product on shipments or receipt batches not yet receipted.
On Ord / UOM On Ord
Quantity of the selected product on order from suppliers.
Commit / UOM Commit
Quantity of the selected product On Order or Shipped that is already committed to a Job.
Transit / UOM Transit
Quantity of the selected product in transit.
Totals Panel
Total Quantity
Total quantity of all the products.
Total Cost
Total cost of all the products.
Total Weight
The total weight of all the products.
Total Volume
The total volume of all the products.
Buttons
Batch List
(Alt+L)
Opens
IC Receipt Batch List
, you can view a list of all unposted batches.
Post
(Alt+S)
Post receipt transactions for the IC Product records.
Save
(F9)
Save the batch. Blank lines at the end will be trimmed. You can re-open saved batches for further editing and/or posting from
IC Receipt Batch List
.
Cancel
(Esc)
Close without saving.

---

## IC Enter Stock Transfers

Source: https://accredo.co.nz/webhelp/ICStockTransfers.htm

IC Enter Stock Transfers
Accredo Mercury holds stock at a single location. Stock transfers between locations are only available for Accredo Saturn.
Navigator > Tasks > Inventory Control > Enter Transfers
You can transfer products between locations. A number of items can be transferred. You can dispatch and receipt goods simultaneously, or dispatch to a transit location and receipt later to the final destination. You can enter details of products being transferred. When an IC Stock Transfer is dispatched the cost of each product is recorded at the time of dispatch, this cost is used when the transfer is receipted.
If a transit location is used it must not be the same as either the Source or Destination location.
Vertical toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit the stock transfer.
Insert
(F4)
Create a new stock transfer.
Duplicate
(Shift+F4)
Duplicate the stock transfer. You can select to
Duplicate
or
Duplicate Contra
.
Delete
(F3)
Delete the document. Only available for saved, unposted documents, when the user has permission.
Print Transfer
(Ctrl+P)
In Edit mode, the transfer is saved first.
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
Refresh Weight and Volume
If the weight and / or volume of a Product changes, existing lines on Transfers are not automatically updated. Click
Refresh Weight and Volume
to re-calculate weight and volume from current Product Weight and Volume figures for all lines.
Print Dispatch Labels
Print labels using Dispatch Quantity. Product Label formatting is set in
Document Defaults
.
Print Receipt Labels
Print labels using Receipt Quantity. Product Label formatting is set in
Document Defaults
.
Delete Nil Lines
(Alt+D)
Delete all nil quantity lines from the transfer. A line is considered nil if all quantities are zero.
Print Log
View the
Print Log
(requires Read access Permission for Company > Settings).
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Batch header
Source Location
Date
Period
Store Person
The original location, dispatch date, and the period goods were dispatched in. These fields must be completed if goods are being dispatched and receipted simultaneously, or dispatched to a transit location for later receipting to a final destination.
Dispatch
The Dispatch Status is shown.
Dispatch status can be changed between
Unposted
and
Open
.
Unposted
Dispatch not yet posted.
Open
An extended version of the Unposted status that prevents the Dispatch from being posted.
Transit Location
Reference
Comment
The location of goods in-transit, along with shipping document numbers and expected arrival dates.
These are optional fields and can be left blank if goods are being dispatched and receipted at the same time.
Destination Location
Date
Period
Store Person
The destination with the date of receipt and the period receipted in. The Destination field must be completed, if goods are being dispatched and receipted simultaneously, or dispatched to a transit location for later receipting to a final destination.
The Date and Period fields must be completed before goods can be receipted to the final destination. To transfer the cost of products between branches and departments, you must type the relevant GL Account in the GL Transfer Out and Transfer In fields in
IC Stock Group
.
Print Status
Read-only, shows the print status of the document.
Unprinted
, Document not printed.
Printed,
Document printed.
View the
Print Log
(requires Read access Permission for Company > Settings).
Receipt
The Receipt Status is shown.
Receipt Status can be changed between
Unposted
and
Open
.
Unposted
Receipt not yet posted.
Open
An extended version of the Unposted status that prevents the Receipt from being posted.
Transfer grid
Type
The Line Type select
Product
or
Narrative
.
Product
Enter product items.
Narrative
Enter extended lines of text, such as a detailed description of the reason for the adjustments. Click
Narrative
(F2)
in the Description field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Product
The Product code to transfer.
UOM Code
(
UOM
Active)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Dispatch / UOM Dispatch
The number of units dispatched from the Source Location above.
Receipt / UOM Receipt
The number of units received at the Destination Location above.
Adjustment / UOM Adjustment
The difference between the number of units dispatched and the number of units received, for example if items are lost or destroyed in-transit. The Receipt plus Adjustment figures must equal the Dispatch figure before you can post Receipt transactions.
Source Avail
The number of the Product available at the Source Location.
Dest Avail
The number of the Product available at the Destination Location.
Source In stock
The number of the Product in stock at the Source Location.
Dest In Stock
The number of the Product in stock at the Destination Location.
Unit
These are obtained from the Product record. They can be used (in a script) for apportioning freight and other costs across different Products.
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
Cost Value
Calculated as the
Cost Price * Quantity
. Read-only.
Serial No
For
Serial No
Purchase
tracked products if the quantity is 1 or -1 the Serial No may be entered, for other quantities enter Serial Nos in the Tracking tab.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Opens IC Transfer Line form view showing all visible fields in the customised grid, and additional fields not visible by default on the grid.
Insert
(F4)
Insert a new line.
Move
(Shift+Up) (Shift+Down)
Move the selected line.
Delete
(F3)
Delete the selected line.
Sort List
(Ctrl+F2)
Select the sort criteria in
Sort - Line
. The sort criteria will be retained on Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Product Quantities
(Ctrl+Q)
Opens
IC Product Quantity
showing quantities at each location, to view stock availability and pending stock movements. Allows juggling stock 'on the fly'.
Select all
(Shift+F4)
Clears the Adjustments field making all quantities in the Receipt field equal to those in the Dispatch field.
Revert all
(Shift+F3)
Reverts to the most recently saved quantities in the Receipt and Adjustment fields. If the transfer is saved, this is unavailable.
UOM to Base
Available if
UOM
is Active. Converts the UOM for the selected line to the Base UOM, to allow you to make adjustments.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Tracking Panel
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the Outwards and Inwards
tracking
detail for the current line.
Stock Panel
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the panel.
UOM Code (
UOM
Active only)
UOM code for the Product.
Source / Destination
All Quantities are available for Source Location and Destination Location.
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
Commit / UOM Commit
Quantity of the selected product On Order or Shipped that is already committed to a Job.
Transit / UOM Transit
Quantity of the selected product in transit.
Totals
Customise
Opens
Customise Fields
, you can customise the fields visible in the stock levels panel.
Total Weight
Total weight for the Transfer.
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
Total volume for the Transfer.
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
Transfer List
Opens
Transfer List
and selects the document.
Dispatch
Dispatch products from the source to the Transit Location. This affects the following data in IC Product > Quantity tab,
Source Location,
in-stock figures reduce by quantities specified.
Transit Location,
in-stock figures increase by quantities specified; in-transit figures reduce by quantities specified.
Destination Location,
in-transit figures increase by quantities specified.
If a line cannot be posted, for example, due to invalid data, make corrections before the transactions are posted. After posting, the window becomes read-only. At this point, you can print a report of posted transactions before closing the window. Once goods are dispatched, the transfer document will appear in the Transfers selection of the
IC Transfer List
as a posted transaction. From here, you can open the document when you are ready to Receipt the goods.
Receipt
Receipt products from the transit to the source location. This affects the following data in IC Products > Quantity tab,
Transit Location
, in-stock figures reduce by the quantities specified.
Destination Location
, in-stock figures increase by quantities specified; in-transit figures reduce by quantities specified.
If a line cannot be posted, for example, due to invalid data, type corrections before the transactions are posted. After posting, the window becomes read- only. At this point, you can print a report of posted transactions before closing the window. Once goods are receipted, the transfer document will appear in the History selection of the
IC Transfer List
as a posted transaction. You can post transfer transactions for all specified product records for transit and destination locations.
This affects the data in IC Product > Quantity tab > Transit Location
Both
You can post transfer transactions for all specified product records for Source and Destination locations. This affects the following data from
IC Products - Quantity tab
:
Source Location
- In Stock figures reduce by quantities specified.
Destination Location
- In Stock figures increase by quantities specified.
If there are lines which cannot be posted, for example, due to invalid data, you must enter corrections before the transactions are posted. After posting, the window will become read-only. At this point, you can print a report of the posted transactions before closing the window. Once goods are receipted, the transfer document will appear in the History selection of the
IC Transfer List
as a posted transaction.
Save
Saves the transfer without posting transactions (for example, to complete later). The transfer will appear in the Transfers selection of the
IC Transfer List
as an unposted transaction.
Cancel
Cancels any changes.
In This Section
IC Stock Transfers - Links tab
IC Stock Transfers - Memos tab

---

## IC Find Adjustment Batch ID

Source: https://accredo.co.nz/webhelp/ICFindAdjustmentBatchID.htm

IC Find Adjustment Batch ID
Navigator > Maintain >Inventory Control > Adjustment Batch List >
Batch
(Alt+B)
Enter a Batch ID to find a batch. The Batch ID is a unique number Accredo assigns to each batch.
Batch IDs are displayed in the header information on the Adjustment Batch form. The Batch
ID
is displayed at the top right of the form.

---

## IC Find Bin Code

Source: https://accredo.co.nz/webhelp/ICBinLocations_Find.htm

IC Find Bin Code
Navigator > Maintain > Inventory Control > Bin code >
Run
(
F9
) >
Find
(Ctrl+F)
Find the bin code of a product at a Location. Enter or select the Product Code.
If a match is found, the row will be selected.
See Also
IC Product Bin

---

## IC Find Manufacture Batch ID

Source: https://accredo.co.nz/webhelp/ICFindManufactureBatchID.htm

IC Find Manufacture Batch ID
Navigator > Maintain > Inventory Control > Manufacture Batch List >
Batch
(Alt+B)
Enter a Batch ID to find a batch. The Batch ID is a unique number Accredo assigns to each batch.
Batch IDs are displayed in the header information on the Manufacture Batch form. The Batch
ID
is displayed at the top right of the form.
See Also
IC Manufacture Batch List

---

## IC Find Product

Source: https://accredo.co.nz/webhelp/ICFindProduct.htm

IC Find Product
Find
(
Ctrl+F
)
Enter or select a Product Code to find the next line in the list for a Product.

---

## IC Find Receipt Batch ID

Source: https://accredo.co.nz/webhelp/ICFindReceiptBatchID.htm

IC Find Receipt Batch ID
Navigator > Maintain >Inventory Control > Receipt Batch List >
Batch
(Alt+B)
Enter a Batch ID to find a batch. The Batch ID is a unique number Accredo assigns to each batch.
Batch IDs are displayed in the header information on the Receipt Batch form. The Batch
ID
is displayed at the top right of the form.

---

## IC Find Stocktake

Source: https://accredo.co.nz/webhelp/ICFindStocktake.htm

IC Find Stocktake
Navigator > Maintain > Inventory Control > Stocktake Processing > Stocktake List >
Stocktake
(Alt+S)
Find a Stocktake from a Count ID. Enter the Count ID to find the Stocktake for that count.
The Count
ID
is a unique number Accredo assigns to each Count. Count IDs are displayed in the header information on the Count tab and Count form.
See Also
IC Stocktake List

---

## IC Find Stocktake Count

Source: https://accredo.co.nz/webhelp/ICStocktakeForm_CountsTab_Find.htm

IC Find Stocktake Count
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List > Select Stocktake > Counts tab >
Find
(
Ctrl+F
)
Find a Count in the Count List by entering the Count ID. The Count ID is a unique number Accredo assigns to each document.
Accredo Document IDs are displayed in the header information on Document forms. The Document
ID
is displayed at the top right of the Document form.
If a match is found, the row will be selected.
See Also
IC Stocktake - Counts tab

---

## IC Find Stocktake ID

Source: https://accredo.co.nz/webhelp/ICStocktakeList_Find.htm

IC Find Stocktake ID
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Find
(Ctrl+F)
Enter a Stocktake ID to find a Stocktake. The Stocktake ID is a unique number Accredo assigns to each document.
Accredo Document IDs are displayed in the header information on Document forms. The Document
ID
is displayed at the top right of the Document form.
If a match is found, the row will be selected.
See Also
IC Stocktake List

---

## IC Generate Bin Count

Source: https://accredo.co.nz/webhelp/ICGenerateBinCount.htm

IC Generate Bin Count
Bin tracking is only available for Accredo Saturn Stock Locations.
Navigator > Tasks > Inventory Control > Bin Processing > Bin Count List >
Insert
button - OR -
Navigator > Tasks > Inventory Control > Bin Processing > Bin Count >
Insert
button
This option available if
Bin Tracked
is selected for a
Location
.
You can generate a Bin Count batch. Enter selections for the bin count, then click
Run
to generate the bin count.
Location
Select the bin tracked location for the bin count.
Bin Code
Select the bin to be counted.
While a bin count is in progress the bin is locked, transactions with tracking detail for the bin may not be posted.
Period
Select the Period for the bin count, from the available periods.
Date
The date that adjustment transactions will be posted. Must be within the Period selected. Defaults to the System Date.
Reference
Enter a reference, if required, to be applied to the bin count.
Details
Enter details, if required, to be applied to the bin count.
Date
Date of the transactions. Must be within the Period selected. Defaults to the System Date.
Store Person
The Store Person associated with the receipt batch. This defaults from the User's
Default Store Person Code
.
Generate Lines
Selected
, all Products in stock in the bin will be added as lines for the count.
Copy Expected to Counted
When Generate Lines is selected.
Selected
, the Expected quantity will be copied to the Counted quantity.
Adjust
Set the default for generated lines.
Selected
, the default. Variances will be adjusted into or out of stock when posted.
Unselected
, nil adjustments are posted for variances with quantities moved from/to the Unspecified bin.

---

## IC Generate Counts

Source: https://accredo.co.nz/webhelp/ICGenerateCounts.htm

IC Generate Counts
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Generate Counts
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake >
Generate Counts
Generate counts for products. This can be used to generate counts for all uncounted products as a final step once all other counts are entered, to show if any products expected to be counted were not found.
Product - From / To
Select a product or range to generate Counts for. Only products included in the Stocktake are added to the counts.
Generate For
Select to generate counts for:
Uncounted Products
- products in the Stocktake that are not currently on any Count sheets will be added. This is the default option.
All Products
- all products in the Stocktake will be added, regardless of whether they are currently included in existing Counts.
Variance Products
- products that have a variance will be added to the count. This is available for
Additive
stocktakes only.
Counts Per
For
Single
and
Additive
stocktakes, you can select one or more fields IC Product fields to group products by in a count. For example, you can group by Creditor Code, Stock Group, Categories or Bin Code.
Number of Counts
Enter the number of counts to be generated.
For
Additive
Stocktakes, the number of counts will be created with all products for the stocktake.
For Single
Stocktakes,
products will be split evenly between the number of counts.
Defaults from
IC Settings - Stocktake tab
.
Copy Expected to Counted
Available for Single counts.
Selected
, the Expected amount will be copied to the Counted amount.
Confirm Generated Counts
Available when generating for Uncounted Products.
Selected
, the generated Counts will be Confirmed.
Details
The Details of the Stocktake Count.
Run
(F9)
Generate the count, based on the selections.

---

## IC Generate Stocktake

Source: https://accredo.co.nz/webhelp/ICGenerateStocktake.htm

IC Generate Stocktake
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake - OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Insert
button
For
Single,
Additive and Detailed
Stocktakes. Default Stocktake type selected in
IC Settings - Stocktake tab
, set per Location in IC Stock Locations. Detailed recommended for Bin Tracked Locations (in Accredo Saturn only).
You can generate a Stocktake document, to enter stocktake counts. Enter selections for the stocktake, then click
Run
to generate the stocktake. Each product can only be included in one unposted Stocktake per Period, per Location (in Accredo Saturn).
Note: To create a Stocktake with no Products, open the
IC Stocktake List
, then select
Insert
> Insert Stocktake.
Location
Select the location for the stocktake. If this is run from the
IC Stocktake List
, defaults to the Location selected, otherwise defaults to the User Location, if set.
Locations with Count Type set to Basic are excluded from Generate, use
Enter Basic Count
.  (Accredo Saturn Only)
Period
Select the Period for the stocktake, from the available periods.
Date
The date that adjustment transactions will be posted. Defaults to the period end date. The
Date
must occur in the
Period
.
Reference
Enter a reference, if required, to be applied to the stocktake.
Details
Enter details, if required, to be applied to the stocktake.
Product From / To
Select a range of products for the stocktake, or leave blank to include all products.
Click
Filter / Sort
(Ctrl+F2)
to filter the products.
Stock Group From / To
Select a range of stock groups for the stocktake, or leave blank to include all stock groups.
Creditor
Select a creditor for the stocktake, or leave blank to include all creditors.
Include Nil Quantity
Selected
, Products with nil quantities will be included in the stocktake. Defaults from
IC Settings - Stocktake tab
.
Count Type
Defaults from
IC Settings - Stocktake tab
. Defaults from selected Location.
Select the type of Count from:
Single
- One count will be done per Product and Location.
Additive
- Several counts can be done for each Product and Location.
Detailed
- For tracked Products Serial No and/or Lot No detail must be included in the counts.
For Bin tracked Locations Bin code must be included in the counts.
Tracking detail for the stocktake is generated when the stocktake is marked Counted.
Locations, Saturn Only.
Note:
Additive
and
Detailed
include support for
UOM
if required.
Generate Counts
Selected
, Count Lines and a Count Header will be created for the stocktake. Defaults from
IC Settings - Stocktake tab
.
Click
Sort
(Ctrl+F2)
to apply a sort order to the Counts.
For
Detailed
counts at a
Bin Tracked
location a Count Line per Product and Bin with a quantity InStock is generated.
Locations, Warehouse Management, Saturn Only.
Store Person
When
Generate Counts
is selected, the Store Person associated with the Counts. This defaults from the User's
Default Store Person Code
.
Count Per
When
Generate Counts
is selected, you can select one or more IC Product fields to group products by, in a count. For example, you can group by Creditor Code, Stock Group, Categories or Bin Code.
Number of Counts
If
Count Per
is not selected, enter the number of counts to be created.
For
Additive
or
Detailed
Stocktakes, the number of counts will be created with all products for the stocktake.
For Single
Stocktakes,
products will be split evenly between the number of counts.
Defaults from
IC Settings - Stocktake tab
.
Copy Expected to Counted
Available for
Single
counts, when Generate Counts is selected.
Selected
, the Expected quantity will be copied to the Counted quantity.
Run
(F9)
Creates a new Stocktake document based on the selections. The
IC Stocktake
form will open.

---

## IC Global Price Update

Source: https://accredo.co.nz/webhelp/ICGlobalPriceUpdate.htm

IC Global Price Update
Navigator > Tasks > Inventory Control >Update Prices > Global Price Update
Globally update prices for selected Products by a percentage or dollar amount. Select Products to update by applying a Product range,
filtering
on the Product file, selecting by Stock Group and selecting by Creditor. See the examples below for sample selections and their effects.
Update Method
Select from:
Percentage,
apply a percentage.
Amount,
specify a dollar amount.
Markup Only,
apply the markups from the product record.
Update By
If you have selected the Percentage method, type the percentage here; if you selected the Amount method, type the amount. This will update the prices selected in the Prices to Update field by the amount or percentage entered.
Update Type
Select from:
Query Run,
(default), new prices for each Product will be shown in a query window before updating. You will have the choice for each Product to edit, update or cancel.
Report Only,
report the effect of applying the selections made in the Price Update without actually changing the prices. If report destination is
Screen
select
Regenerate
from the Report Preview to return to the selection form with all selections retained.
Automatic,
proceed with the price update based on the selections.
Cost Prices to Update
For update by percentage or amount select the cost price(s) (if any) to be updated. If you use a query run, you can update other prices manually in the query window. If you update the Latest Cost Price for Products with a stock level of zero or less, the Average Cost Price will change to the new Latest Cost Price. After the update is complete, you can print a report of the price changes.
See examples below for sample selections and their effects.
Markup Basis
Defaults to the Markup Basis specified in IC Settings.
Note: If
Automatically
Apply Markups
in
IC Settings
is
Selected
Markup Basis cannot be changed and prices with markups cannot be updated directly, they will automatically update as the Markup Basis price changes.
Sell Prices
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise Fields
(Alt+F5)
Opens
Customise Fields
- you can customise fields visible in the grid.
Action
None,
no change to the sell price.
Update,
update the sell price by the specified percentage or amount.
Markup,
to recalculate the sell price, markup from the Markup Basis after prices are updated.
Code
The Price code.
Currency
The currency for the Price code.
Markup Price
If Markup Basis is Price code, the Price code that mark up will apply from.
Round Direction
Default from the Price Code settings. Specify the rounding direction used when calculating the price for a product where markups or global price update is used.
Round Unit
Defaults from the Price Code settings. If you type a value here, the newly calculated prices will be rounded to match the amount, for example, to round to the nearest dollar, enter 1.00.
Include Inactive
Selected
, include inactive products in the update.
Run
(F9)
Reprice and show the results.
Examples
Updating all Selling Prices by $1, where Selling Prices are not based on markups.
Update Method
=
Amount
Update By
=
1
Cost Prices to Update
= Select all that apply
Markup Basis
=
None
Sell Prices Action
=
None
Accredo will add $1 to the price types selected.
Recalculating Selling Prices to reflect previous global updates and changes in IC Product without having to open each (where
Apply Markups
option in
IC Settings
is
clear
).
Update Method
= (doesn't matter)
Update By
= (leave blank)
Cost Prices to Update
= (leave clear)
Markup Basis
= the Markup Basis in IC Settings
Sell Prices Action
= Set to
Markup
for all those that apply
Accredo will recalculate Selling Prices selected to reflect changes to the base price (Markup Basis) selected.
Updating Latest Cost Prices by 5% and then updating Selling Price to reflect this:
Update Method
=
Percentage
Update By
=
5%
Cost Prices to Update
= Select
Latest Cost
Markup Basis
=
Latest Cost
Sell Prices Action
=
Update
Accredo will recalculate Selling Price as follows:
(current) Latest Cost + 5% = (new) Latest Cost
(new) Latest Cost + Markup percentage for Selling Price (from Product record) = (new) Selling Price.

---

## IC Import Count

Source: https://accredo.co.nz/webhelp/ICImportCount.htm

IC Import Count
Navigator > Tasks > Inventory Control > Stocktake Processing > Import Count - OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Generate Counts
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake >
Generate Counts
For
Single
and
Additive
Stocktakes only, selected in
IC Settings - Stocktake tab
.
Imports and inserts a new count and lines. The count will be imported with a
Status
of
Counted
. Any lines with the same Product (and UOM code, if
UOM
is active) will be consolidated. This avoids having several lines where products have been counted individually with a scanner.
Store Person
The Store Person associated with the Count
Location
The Count Location.
Import Format
You can import stocktake quantities from a file, rather than keying them in manually. Defaults from
IC Settings - Stocktake tab
or
IC Location
.
The format of the file can be:
Standard
- use with tab delimited or comma delimited (.csv) files. format is:
Product Code, Quantity
Standard
with Bin
- use with tab delimited or comma delimited (.csv) files. format is:
Product Code, Quantity, Bin Code
Opticon
- standard Opticon laser terminal format.
UOM
- only valid for Additive Counts. File format is:
Product Code, UOM Code, UOM Quantity Counted
- OR -
Product Code, UOM Code, UOM Quantity Counted, Bin Code
Detailed
- only valid for Detailed Counts. File format is:
Product Code, UOM Code, UOM Quantity Counted
, Bin Code, Serial No, Lot No, Lot Date, Expiry Date
In all formats
Barcode
can be substituted for
Product Code
.
For non UOM leave UOM Code empty.
File Name
Select the file name and location to import from. Defaults from
IC Settings - Stocktake tab
.
Excel Worksheet
If the file entered in
File Name
is an Excel file, select the Excel Worksheet to be imported from.
Note: Do not use apostrophes (') in worksheet names, as this can cause problems.
Details
Enter details, if required, to be applied to the count header.
Open Count After Import
Selected
, the count will open in the
IC Stocktake Count
form after import.
Run
(F9)
Import the Count, based on the selections. A message box showing the Count ID Number, number of lines imported and number of errors will be displayed. If errors exist, you can select to print an error report.

---

## IC Insert Count

Source: https://accredo.co.nz/webhelp/ICInsertStocktakeCount.htm

IC Insert Count
Navigator > Tasks > Inventory Control > Stocktake Processing > Insert Count
For
Single
and
Additive
Stocktakes only, selected in
IC Settings - Stocktake tab
.
You can add a Stocktake Count. The Count will be added to the corresponding unposted Stocktake. If more than one Stocktake is available, you can select which Stocktake to add the count to.
Location
Enter the Location for the Count. (Accredo Saturn Only)
Count Lines
Select from:
None
- Will create a blank count.
Uncounted Lines
- Uncounted lines will be added.
All Lines
- All lines will be added.
Product - From / To
If you have selected to add lines to the count, you can select to filter by Product.
Buttons
Run
(F9)
Click to create a Count. If more than one unposted Stocktake for the Location  (in Accredo Saturn) is available, a list of Stocktakes will be shown in
IC Select Stocktake
. Select the stocktake to add the count to. Opens
IC Stocktake Count
.
In This Section
IC Select Stocktake

---

## IC Insert Products

Source: https://accredo.co.nz/webhelp/ICStocktakeForm_InsertProducts.htm

IC Insert Products
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Insert
Products
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake
Insert Products
Select products to add to the Stocktake.
Product From / To
Select a range of products to add to the stocktake, or leave blank to add all products.
Stock Group From / To
Select a range of stock groups to add to the stocktake, or leave blank to add products from all stock groups.
Creditor
Select a creditor for the stocktake, or leave blank to include all creditors.
Include Nil Quantity
Selected
, Products with nil quantities will be included in the stocktake.
Run
(F9)
Adds products based on selections to the stocktake.

---

## IC Label Designer

Source: https://accredo.co.nz/webhelp/ICLabelDesigner.htm

IC Label Designer
Navigator > Setup > Inventory Control >
Label Designer

---

## IC Link List

Source: https://accredo.co.nz/webhelp/ICLinkList.htm

IC Link List
Navigator > Maintain > Inventory Control >
Link List

---

## IC Manufacture - Links tab

Source: https://accredo.co.nz/webhelp/ICManufacture_Links.htm

IC Manufacture - Links tab
Navigator > Tasks > Inventory Control > Enter Manufactures >
Links tab

---

## IC Manufacture - Memos tab

Source: https://accredo.co.nz/webhelp/ICManufacture_Memos.htm

IC Manufacture - Memos tab
Navigator > Tasks > Inventory Control > Enter Manufactures >
Memos tab

---

## IC Manufacture Batch - Grid

Source: https://accredo.co.nz/webhelp/ICManufactureBatch_Grid.htm

IC Manufacture Batch - Grid
Navigator > Tasks > Inventory Control > Enter Manufacture Batch.
Displayed on the
IC Enter Manufacture Batch
form.
The Manufacture grid is populated when a Product is selected and a Quantity or UOM Quantity is entered.
Grid fields
Type
The Line Type select
Variable, Fixed
or
Narrative
.
Variable
Enter product code and quantity. Quantity of the component is extended by the quantity Manufactured.
Fixed
Enter product code and quantity. Quantity of the component is not extended by Quantity Manufactured. For example used where there is a fixed cost for setup regardless of number manufactured.
Narrative
Enter extended lines of text. Click
Narrative
(F2)
in the Description field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Product
The component Product code.
Location
The Location the Product is sourced from. Components from different locations can be used in a manufacture batch. (Accredo Saturn Only)
Description
Defaults to the description of the selected product (can be overwritten) / loads from Components for Narrative. Up to 60 characters are available on the selected line. For
Narrative
lines, for more characters, click
Narrative
(F2)
to open the
Narrative Editor
.
UOM Multiplier
(
UOM
Active Only)
The multiplier for the UOM Unit, set in
IC Units of Measure
. Read-only.
Serial No
For
Serial No
Purchase
tracked products if the quantity is 1 or -1 the Serial No may be entered, for other quantities enter Serial Nos in the Tracking tab.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
Quantity / UOM Quantity
The quantity used in the Batch Manufacture.
UOM Code
(
UOM
Active Only)
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Unit Cost Price / UOM Unit Cost Price
The Cost Price. When a Product code is entered, this is loaded with the appropriate Cost Price from the Product record. The UOM Cost Price is calculated as the
Cost Price
*
UOM Multiplier.
Cost Value
The cost value is calculated as the product of the Cost Price and the quantity entered.
Unit
The Unit the product is measured in.
Sub
This will be
selected
if the component product has parts of its own. Indicates that the product is a subassembly.
Location
The Location the Product is sourced from. Components from different locations can be used in a manufacture batch.
Note: Not recommended if
IC Integration Basis
is
Perpetual
and Locations are for different Branches or Departments.
(Accredo Saturn Only)
Quantities
Customise the grid to include quantity information for the component.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see the batch line details.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort list
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved on
Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Product quantities
(Ctrl+Q)
Opens
Product Quantity
showing quantities at each location (in Accredo Saturn). Product Quantities lookup provides a quick overview of stock availability and pending stock movements as you enter stock transfers, and allows juggling stock 'on the fly'.
Manufacture Component
Available for parts that themselves can be manufactured. Unlike single
Manufactures
, Manufacture Batches do not automatically manufacture sub-assemblies. This opens a new IC Manufacture Batch window for the component.
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
(Alt+F5)
Opens
Customise Fields
- you can customise fields visible in the totals panel.
UOM Code
(
UOM
Active Only)
The UOM Code of the selected Product.
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
Commit / UOM Commit
Quantity of the selected product committed to a job.
Transit / UOM Transit
Quantity of the selected product in transit. (Accredo Saturn Only)
See Also
IC Enter Manufacture Batch

---

## IC Manufacture Batch - Links tab

Source: https://accredo.co.nz/webhelp/ICManufactureBatch_Links.htm

IC Manufacture Batch - Links tab
Navigator > Tasks > Inventory Control > Enter Manufacture Batch >
Links tab
See Also
IC Enter Manufacture Batch

---

## IC Manufacture Batch - Memos tab

Source: https://accredo.co.nz/webhelp/ICManufactureBatch_Memos.htm

IC Manufacture Batch - Memos tab
Navigator > Tasks > Inventory Control > Enter Manufacture Batch >
Memos tab
See Also
IC Enter Manufacture Batch

---

## IC Manufacture Batch List

Source: https://accredo.co.nz/webhelp/ICManufactureBatchList.htm

IC Manufacture Batch List
Navigator > Maintain > Inventory Control > Manufacture Batch List
Click
to make selections, and use the
lookups
.
Selections
Period
Select a period to view for:
Period
- Select a single period in the
From
selection.
Year
- Displays batches for the current year.
All Periods
- All batches are displayed.
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
Default is Range of Periods with From Period set to First Available period for IC or period of first Current Batch whichever is earlier, and To Period set to Last Available period for IC.
Selection
Select to show batches that are:
Unposted
Open
Posted
Deleted
All Batches
(excludes Deleted batches)
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Manufactures
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Manufactures
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Batch
The Manufacture Batch identifier.
Product
The product being manufactured.
Description
Product description.
Date
Date of the manufacture batch.
UOM Code
(
UOM
Active Only)
UOM Code for the manufacture batch.
Quantity / UOM Quantity
Quantity being manufactured in the batch.
Details
Details entered for the batch.
Status
Post status of the manufacture batch.
Location
Location of the manufacture batch. (Accredo Saturn Only)
Period
Period the manufacture batch occurs in.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a manufacture batch.
Delete
(F3)
Delete the manufacture batch. Only available for saved, unposted batches, when the user has permission.
Open Details
(F12)
Opens Batch data entry. View the details for the
Manufacture Batch
including all lines. You can edit an unposted batch.
Print
(Ctrl+P)
Print the IC Manufactures List. You can save as an Excel worksheet or PDF file and send as an email attachment.
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
The Transaction Batch list to reload changes other Users may have made.
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
Post selected
(
Alt+T
)
Post the selected manufacture batch.
Post all up to current period
(
Alt+A
)
Post all manufacture batches up to the selected period.
Find
(Ctrl+F)
Find a batch using the Batch ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.
Button
Batch
(Alt+B)
Locate a Batch by the Batch ID.
In This Section
IC Find Manufacture Batch ID
See Also
Inventory Control - Maintain

---

## IC Manufacture Sheet Designer

Source: https://accredo.co.nz/webhelp/ICManufactureDesigner.htm

IC Manufacture Sheet Designer
Navigator > Setup >Inventory Control > Manufacture Sheet Designer
You can design your own Manufacture Sheet, or open and modify an existing manufacture sheet. To design a manufacture sheet quickly, start with an existing layout, save it with a different name, then modify it. Sample manufacture sheets are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
The IC Manufacture Sheet Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code.
Name
Iterators filter records that are shown in the report. Available Iterators are:
Lines
- Lines in the IC Batch Manufacture.
Tracking
- iterates through the tracking detail for the batch line.
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Product Sheet Designer in addition to the standard
objects
are:
ComponentLine
Details of the component lines in the manufacture.
Location
Details of the manufacture location.
ManufactureHead
Fields from the Manufacture head record.
ManufactureProduct
Fields from the Manufacture Product record.
Product
Fields from the Product record.
A sample IC Manufacture Sheet is provided with the Accredo Server Install, and is also available on the Accredo website. The Sample IC Manufacture Sheet is:
ICManufacture.pfd
- standard IC Manufacture Sheet.
To use documents downloaded from the website, ensure your document designer is the latest version.

---

## IC Memo Designer

Source: https://accredo.co.nz/webhelp/ICMemoDesigner.htm

IC Memo Designer
Navigator > Setup > Inventory Control > IC
Memo Designer

---

## IC Memo List

Source: https://accredo.co.nz/webhelp/ICMemoList.htm

IC Memo List
Navigator > Maintain > Inventory Control >
Memo List

---

## IC Memo Reports - Add Layout

Source: https://accredo.co.nz/webhelp/ICMemoReports.htm

IC Memo Reports - Add Layout
Navigator > Reports > Inventory Control > Memo Reports > Add Layout
See
Memo Report
.

---

## IC Pending Usage for UOM

Source: https://accredo.co.nz/webhelp/ICPendingUsageforUOMCode.htm

IC Pending Usage for UOM
Navigator > Setup > Inventory Control > Units of Measure >
UOM Code Usage Query button
(Ctrl+Q)
>
Pending Transaction Query
Displays IC Products for all Pending Transactions using the selected UOM Code.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
(F12)
Open details of the selected document.
Print Report
(Ctrl+P)
Print a pending usage report of products pending using the selected UOM Code.
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
Grid Fields
Product Code
IC Product Code.
Description
Description for the product code.
Source Module
The source module for the transaction.
Location
Shows the location of the stock. (Accredo Saturn Only)
Party Code
The Customer, Creditor or Job code for the document.
Document
The type of document containing the pending usage.

---

## IC Price List Copy

Source: https://accredo.co.nz/webhelp/ICPriceListCopy_Selections.htm

IC Price List Copy
Navigator > Tasks > Inventory Control > Update Prices > Price List Copy
Selling Prices can be copied from one Price list to another to apply an update by a percentage or an amount, and rounded to the required nearest amount. Markup percentages that derive the Sell Price based on a selected Markup basis can also be calculated.
When you copy to a Price List that currently contains pricing, a confirmation message will appear. You can copy between Price Lists in the same currency or between base currency and another currency. You will be prompted for an exchange rate.
Selection Fields
Product - From / To
Select the products to be updated.
Stock Group
Select a stock group to be updated.
Creditor
Select the creditor to be updated.
Price List - From / To
Select the price lists to update.
Update Method
Select to update by a
Percentage
or fixed
Amount
.
Update By
Specify the percentage or amount to update by.
Rounding Direction
Specify the rounding direction used when calculating the price for a product where markups or global price update is used.
Rounding Unit
Specify the unit when calculating the price for a product where markups or Global Price Update is used, for example, to round to the nearest dollar, enter
1.00
.
Markup Basis
Select the markup basis for markup percentages to calculate prices.
None
Markup percentages are not used in calculating IC Selling Prices but can be used for markups in JC when
Sell Price Basis
in
JC Settings
is
Markup
.
Standard
Markup percentages are applied to the standard cost to calculate the Selling Price.
Latest
Markup percentages are applied to the latest cost to calculate the Selling Price.
Average
Markup percentages are applied to the average cost to calculate the Selling Price.
Price Code
Markup percentages are applied to the Selling Price for the Price code specified in
Default Markup Price Code
in
IC Settings - Prices tab
.
Markup Price List
If Price Code is selected above, select the Markup Price List.
Include inactive
Include inactive records in the update.
Run
(F9)
Update the price lists. The IC Price List Copy report window is displayed. See
Report Selections Form

---

## IC Price Update Query

Source: https://accredo.co.nz/webhelp/ICPriceUpdateQuery.htm

IC Price Update Query
Navigator > Tasks > Inventory Control > Update Prices > Supplier Cost Update >
Query Run
Navigator > Tasks > Inventory Control > Update Prices > Reprice from Components >
Query Run
Navigator > Tasks > Inventory Control > Update Prices > Global Price Update >
Query Run
Updated prices are shown in the right hand fields. Prices can be manually edited.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise Fields
(Alt+F5)
Opens
Customise Fields
- you can customise fields visible in the grid.
Show all Sell Prices / Hide Unchanged Sell Prices
(Ctrl+H)
Toggle between showing only the prices that will change, and showing all sell prices.
Buttons
Update
(F9)
Accept updated prices for the Product.
Skip
(Esc)
Do not update the current product prices. Move to the next product.

---

## IC Print Basic Stocktake

Source: https://accredo.co.nz/webhelp/ICPrintBasicStocktake.htm

IC Print Basic Stocktake
Navigator > Reports > Inventory Control > Print Counts
Available for
Basic
Count Type
Stocktakes only.
See also
Report Selections Form
.
Report File Name
The Report File Name specifies the file that defines the Basic Stocktake layout.
Set a default report file name from Navigator > Setup > Company Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IC Stocktake Designer
.
Product - From / To
Select a product or range to print the Basic Stocktake for.
Stock Group - From / To
Select a stock group or range to print the Basic Stocktake for.
Creditor
Select to print the Basic Stocktake for a specific Creditor.
Period
Period to print the basic stocktake for.
Location
Location to print the basic stocktake for.  (Accredo Saturn Only)

---

## IC Print Bin Labels

Source: https://accredo.co.nz/webhelp/ICReports_BinLabel.htm

IC Print Bin Labels
Navigator > Reports > Inventory Control > Bin Labels
You can print labels previously designed using
Label Designer
.
Default report file names can be set from Navigator > Setup > Company > Reporting >
Document Defaults
.
See also
Report Selections Form
.
Location
Select the Location to print Bin Labels for. (Accredo Saturn Only)
Report File Name
The file that defines the bin labels layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
Label Designer
.
Bin Code - From / To
You can select a range of bins, or use the Filter button to filter bins.
Display Inactive
Selected
, displays active and inactive bins.
Number of Label Copies
The number of copies for each label.
Start From Label
On sheet feed labels, you can start printing a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.

---

## IC Print Counts

Source: https://accredo.co.nz/webhelp/ICPrintCounts.htm

IC Print Counts
Navigator > Reports > Inventory Control > Print Counts
See also
Report Selections Form
.
Stocktake ID
Select the Stocktake ID to print count sheets for.
Report File Name
The Report File Name specifies the file that defines the Count sheet document layout.
Set a default report file name from Navigator > Setup > Company Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IC Count Designer
.

---

## IC Print Manufacture Sheets

Source: https://accredo.co.nz/webhelp/ICManufactureSheets.htm

IC Print Manufacture Sheets
Navigator > Reports > Inventory Control > Print Manufacture Sheets
Manufacture Sheets can be printed individually from Navigator > Tasks > Inventory Control >
Enter Manufacture Batch
.
See also
Report Selections Form
.
Report File Name
The Report File Name specifies the file that defines the Product sheet layout.
Set a default report file name from Navigator > Setup > Company Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IC Manufacture Sheet Designer
.
Location
Location to print the manufacture sheet for.  (Accredo Saturn Only)
Product - From / To
Select a product to print manufacture sheets for, or leave blank to print all products.
Post Status
Select to print batches with post status of:
Unposted
Open
- OR -
Posted
.
Period
Select to print batches within a:
Period
Year
All Periods
- OR -
Range of Periods
From / To Period
Select a period to print when when
Period
is selected above, or a period To and From when
Range of Periods
is selected.
See Also
Inventory Control - Reports

---

## IC Print Stocktake Sheet

Source: https://accredo.co.nz/webhelp/ICPrintStocktakeSheet.htm

IC Print Stocktake Sheet
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Print Stocktake Sheet
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake >
Print Stocktake Sheet
Print Stocktake Sheets for the stocktake. Default report file names can be set from
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IC Stocktake Designer
.
See also
Report Selections Form
.

---

## IC Print Transfers

Source: https://accredo.co.nz/webhelp/ICTransfers.htm

IC Print Transfers
Accredo Mercury holds stock at a single location. Stock transfers between locations are only available for Accredo Saturn.
Navigator > Reports > Inventory Control > Print Transfers
See also
Report Selections Form
.
Report File Name
The Report File Name specifies the file that defines the Transfer document layout.
Set a default report file name from Navigator > Setup > Company Reporting >
Document Defaults
.
The
Filter & Sort
button is useful to select the locations to print.
Click
Open In Designer
to open the selected file in the
IC Transfer Designer
.
Source Location
Select a source location to print transfers for.
Transit Location
Select a transit location to print transfers for.
Destination Location
Select a destination location to print transfers for.
Dispatch Status
Select unposted and / or posted.
Receipt Status
Select unposted and / or posted.

---

## IC Product - Activity tab

Source: https://accredo.co.nz/webhelp/ICProducts_Activity.htm

IC Product - Activity tab
Navigator > Maintain > Inventory Control > Products > Activity tab
You can view details of stock activity, values shown are for information only, and cannot be edited. Current Period to date and current year to date quantity are shown. Figures are shown in the base currency.
Accredo Saturn Only: Activity reflects the sum across all locations. Choose a location from the lower left
Location
Lookup. Select all Locations, click
All Locations
.
See also
IC Products - Product tab
.
Activity
Opening Stock
The stock quantity on hand at the start of the Current Period and current year.
- Sales
Quantities sold (on invoices or issues in IC).
+ Receipts
Quantities receipted into stock.
- Usage
Quantities of components used in manufacturing, components in sales of Kitsets and quantities of products used on Jobs in JC.
+ Manufactured
Quantities produced by manufacturing from components.
+ Adjustments
Adjustments to stock levels for both month and year to date including updates from stocktake.
+ Transfers
Quantities transferred between locations. (Accredo Saturn Only)
= Closing Stock
The stock quantity on hand.
Values
Cost Value
The change in stock value for the items due to all transactions, for month and year to date.
Sales Value
The total value sold, both month and year to date.
Cost Of Sales
The cost of sales (issues and usages), based on the costing basis chosen at the time of the sales (standard, latest or average), for month and year to date.
Revaluation
The
revaluation
amounts for the product.
Gross Margin
The gross margin (%) earned on sales for month and year to date, that is, (Value Sold - Cost of Sales) / Value Sold x 100.
Latest Activity
Sold
Date of the last recorded sale.
Used
Date of the last recorded usage of the product.
Receipted
Date of the last recorded Stock Receipt.
Manufactured
Date the product was last manufactured.
Stocktake
Date the product was last counted.
Sales and Valuation History Grid
Shows sales quantities, costs, values, and movement, for the current financial year to date, the most recent 13 months, or all periods in Accredo. The first period for each year is highlighted yellow. The
Last History
period is shown for Inactive records.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Opens the form view for Product Balances Line for the selected period.
Print
(Ctrl+P)
Print the Balances report, or save as an Excel worksheet, or PDF file to send.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Balances are reloaded to reflect changes other Users may have made.
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Open budget
(Alt+U)
Opens
IC Product Budget
for the selected Product.
Revalue Product
(Alt+R)
Revalue
the selected Product.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Grid Fields
Period
The period the row reflects.
Sales
Quantity sold (on invoices or issues in IC) in the period.
Value
Sales value for the period.
Cost
Cost of sales for the period.
Margin
Margin Percentage for the period.
Opening
Opening Stock Quantity for the period.
Opening Value
Opening Stock Value for the period.
Inwards Quantity
Quantity moved Inwards for the period.
Inwards Value
Value of movements Inwards for the period.
Outwards Quantity
Quantity moved Outwards for the period.
Outwards Value
Value of movements Outwards for the period.
Closing Quantity
Closing Stock Quantity for the period.
Closing Value
Closing Stock Value for the period.
Revaluation Value
Revaluation value for the period.

---

## IC Product - Image tab

Source: https://accredo.co.nz/webhelp/ICProducts_Image.htm

IC Product - Image tab
Navigator > Maintain > Inventory Control > Products > Image tab
Select an image file to associate with the Product. The image can be printed on Invoices or custom reports. The Image tab scales an image to fit the available space.
See also
IC Products - Product tab
.
You can set the root Images folder in
Company Settings
this may be an Images folder under the System, or in your Company data folder or a nominated folder which is accessible to all users.
Image Path
The directory path or URL of the image. File types are supported are:
Extension
File Type
*.jpg, *.jpeg
JPEG Image File
*.bmp
Bitmaps
*.ico
Icons
*.emf
Enhanced Metafiles
*.wmf
Metafiles
*.tiff
Tagged Image File Format
Note: Accredo stores a link to the file path, not the file itself.
Selecting a file from a white listed path automatically replaces any
environment variables
.
File Name
Read-only, the name of the file uploaded.
Image Type
File
, the default. Image path point to a file on the network, defaulting to the Images folder.
Web
, Image path is a Web URL.
Dimensions
Read-only, the image file dimensions.
Size
Read-only, the image file size.
Image Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Display Image Normal Size
(Ctrl+/)
View the image at normal size.
Fit Image to Available Space
(Ctrl+*)
Fits the image to the available space.
Zoom In to Image
(Ctrl+=)
Zoom in on the image.
Zoom Out from Image
(Ctrl+-)
Zoom out from the image.
Print Image
(Ctrl+G)
Print the image.
Open File Location
Opens Windows File Explorer at the location of the image file.

---

## IC Product - Information tab

Source: https://accredo.co.nz/webhelp/ICProducts_Information.htm

IC Product - Information tab
Navigator > Maintain > Inventory Control > Products > Information tab
The
icon in the tab indicates that information has been entered,
indicates the tab is currently empty.
Product information can be:
Customised into a product report layout.
Designed into product sheets, and shown on the sample Product Sheet design.
Designed into invoices, packing slips and other documents.
Included in word lookups.
Spell check can be run.
See also
IC Products - Product tab
.
Narrative
Select to insert a
Global Narrative
.
Click the
Insert / Replace
(Ctrl+I)
button to toggle between
Insert
and
Replace.
When the button shows
Insert
, selecting a Global Narrative will insert the Global Narrative text in the Narrative Editor.
When the button shows
Replace,
selecting a Global Narrative will replace the text in the Narrative Editor with the Global Narrative text.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Spell Check
(F7)
Activates Accredo spell check. Spelling is also checked as you type, right-click words for suggested corrections. Spell check options and dictionaries are set in
Company Settings - Spellcheck tab
.
Print
(Ctrl+P)
Print the narrative record.
Save global narrative
Save as a
Global Narrative
.
Product Information
You can enter unlimited lines of text. Lines can be printed on the report and may be included in word lookups. Lines will print on product sheets and are accessible from Invoice Designer.

---

## IC Product - Links tab

Source: https://accredo.co.nz/webhelp/ICProducts_Links.htm

IC Product - Links tab
Navigator > Maintain > Inventory Control > Products >
Links tab

---

## IC Product - Locations Tab

Source: https://accredo.co.nz/webhelp/ICProducts_Locations.htm

IC Product - Locations Tab
Locations are only available for Accredo Saturn.
Navigator > Maintain > Inventory Control > Products > Locations tab
See also
IC Products - Product tab
.
Location UOM
Available when
UOM
is
Active
or
Pending
. Select the UOM to display quantities for each location in.
Initially set to the
Base UOM
,
Sale UOM
,
Purchase UOM
or
Manufacture UOM
for the Product according to the
UOM Enquiry Default
specified in
User Preferences
.
All locations are shown in the grid. You can edit the following grid fields:
Bin Code
For
bin tracked
locations, the default bin for the product for inwards stock movements, e.g. Receipts.
For locations that are not bin tracked the bin code indicates the expected bin for the product in the warehouse.
This can also be entered from
IC Product Bin
or updated during stocktakes
.
When
Coded Bin Lookup
is selected in
IC Settings
(recommended), you can click
Open
(
Shift+F12
) to open
IC Bin
form.
Minimum Quantity
The minimum quantity for the location. View totals for all locations on the
Quantity tab
.
Maximum Quantity
The maximum quantity for the location. The Maximum Quantity cannot be less than the Minimum Quantity. View total for all locations on the
Quantity tab
.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view for product location information.
Print
(Ctrl+P)
Opens IC Product Location Report, see
Report Selections Form
.
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
Show / Hide Inactive Locations
(Ctrl+H)
Show (default) or hide inactive locations.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Product - Memos tab

Source: https://accredo.co.nz/webhelp/ICProducts_Memos.htm

IC Product - Memos tab
Navigator > Maintain > Inventory Control > Products >
Memos tab
For each Account File you can specify a default Memo type. You can also set an Account File as the default for
Enter Memos
.

---

## IC Product - Product tab

Source: https://accredo.co.nz/webhelp/ICProducts.htm

IC Product - Product tab
Navigator > Maintain > Inventory Control > Products > Product tab
Select Product
Select the product code. Search for a product using the
Accredo Lookups
.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Enter edit mode, to edit the product details.
Insert
(F4)
Click to add a new product.
Duplicate
(Shift+F4)
Duplicates the opened product.
Delete
(F3)
If active documents or transactions exist for the record, or if the product is on an unposted stocktake, delete will not be allowed.
Print Product Sheet
(Ctrl+P)
Prints a Product Sheet report, using
IC Print Product Sheets
.
Print Label
(Ctrl+L)
Prints labels for the current product, using
IC Product Labels
.
Hide / Show Prices
(Ctrl+H)
Show or hide the Cost Prices panel and Sell Prices grid. Allows hiding sensitive information. To hide by default use an
OnOpen
script.
Product Quantities
(Ctrl+Q)
Opens
IC Product Quantity
showing quantities at each location (Accredo Saturn Only), to view stock availability and pending stock movements. Allows juggling stock 'on the fly'.
Product Tracking Quantities
Opens
IC Product Tracking Quantities
for the product.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Product Tab
Product Code
A unique alpha numeric code of up to 28 characters. Data can only be entered when inserting new products.
Valid characters for new Product Codes are A-Z, 0-9 by default. Other characters to allow may be specified in
IC Settings Misc tab
.
Description
Further product description. This is printed on documents by default.
Details
Further product details.
Alternate Code
Alternate alpha numeric code.
Bar Code
The default bar code for the product. Other bar codes can be added from the
Suppliers/Bar Codes tab
.
Creditor
The default Creditor code the product is purchased from. Other suppliers can be added from the
Suppliers/Bar Codes tab
.
Comment
Further comments.
Stock Group
The
Stock Groups
closing stock and stock on hand values for this item to be attributed to. These are also commonly used for grouping inventory reports. Required.
Expense Code
The
AP Expense Code
for the product. This will override the default expense code on PO Orders and AP Shipments.
Category 1
Category 2
Categories for Products. Categories can be added from
Categories 1&2
, or click
Open Category
(Shift+F12)
on the Lookup. Labels can be replaced in
IC Settings
.
Non-Diminishing
Clear,
stock quantities increase and decrease as Sales, Receipts and Credits are processed. Use when this is a stock item to maintain quantities of.
Selected
, sales figures are recorded, but no stock quantities are maintained. A common example is labour. If you do not require stock control, this can apply to all products.
Kitset Products are a combination of items sold as a single unit. The Kitset contents are defined from
IC Components
. Stock quantities are not maintained for Kitsets, they must be set up as non-diminishing. Depending on the Component mode at the time of invoicing, a sale can be recorded against the Kitset item and the components used (Manual Component mode) or a sale can be recorded against the components (Automatic Component mode).
Records can be changed from diminishing to non-diminishing only if there are no pending transfers (Accredo Saturn Only) or pending manufactures. Records can be changed from non-diminishing to diminishing if there are no pending allocation where the product is a kitset (see the
Quantities tab
).
Manually Costed
Usually, when invoices are posted, the current Cost Price is used to calculate the cost of sales.
Selected,
the Cost Price is entered on the invoice or job transaction, may be edited, and is not updated at the time of posting or repricing. This is for items with a Cost Price that can vary later, but at the present time, the exact cost is known for entering a sales order, invoice or job transaction.
Note: Kitsets cannot be manually costed.
Back Order
Selected
, the item can be back ordered in OE.
Clear
, the item cannot be back ordered.
Note: Back-ordering for Non-Diminishing products is further controlled by the
OE Setting
to
Allow Back Orders of Non Diminishing Products
, and for Manual Kitsets and their components by the
IN Setting
to
Supply Whole Manual Kitsets
.
Weight / Volume
These fields can be used in combination with a
script
to calculate freight on sales orders and invoices.
Note: For Automatic Kitset products, the Weight and Volume on IN Invoice and OE Orders will be calculated from the component lines, and these fields will not be used.
Commission (%)
Only applies if IN installed and you require commission figures for sales people. The commission percentage of the net price invoiced (or profit), accumulates against the Sales Person code specified on an invoice. To set the commission basis, see AR
Settings
.
Note: For Automatic Kitset products, if any of the component Products have a Commission % set, the Commission % of each of the products will be used. You can manually change these.
Base UOM Code
Only available if UOM Status is set to
Pending
or
Active
in
IC Units of Measure
.
The base stock unit, all quantities for
Other UOM Codes
are calculated from this unit.
For Products with a
Base UOM Code
, the decimals are set by the UOM Code.
Unit
The stock and selling unit shown on reports and printed invoices when UOM Status is set to
None
in
IC Units of Measure
, or the Product does not have a
Base UOM Code
specified.
For
Units
(where the Product does not have a Base UOM), the number of decimal places for quantities can be set in
Decimals
. For example, if you sell a Product with a unit of metres, you will require 2 decimal places for 0.25 of a metre.
Component Mode
None
- Components not in use.
Manufacture
- for
Diminishing
products only, product can be Manufactured from components.
Automatic Kitset
- for
Non-Diminishing
products only. When product is selected on a Sales Order or Invoice the Components are expanded. It is the components which are sold at their sell prices.
Manual Kitset
- for
Non-Diminishing
products only. When product is selected on a Sales Order or Invoice components are expanded as Usages. It is the Kitset product which is sold at the kitset selling price.
Open
(Shift+F12)
opens
IC Components
where you can add or edit components.
Discontinued
Selected,
discontinued products are excluded from Generate Purchase Order.
A
PO Setting
controls whether discontinued products can be selected on purchase orders. Discontinued products may be automatically made inactive once all quantities are zero during End of Period or Year, see
IC Settings
.
Inactive
A product can be inactive if there are no Stock Quantities, (Quantities tab) and the product Value is zero (Activity tab). Inactive records cannot participate in transactions. Mark superseded or no longer stocked products inactive. Inactive products are hidden from view but their financial information and history is retained for reports. Inactive records can be opened, click
Show Inactive Records
(Ctrl+I)
on the Select Product
Lookup
.
Clear
, products are re-activated.
Cost Prices
Cost Prices can be made unavailable using Cost Price permission (set in
Users, Groups and Roles
). All Cost Prices can be edited.
Standard Cost
A Cost Price for valuation and pricing where fluctuation with latest or average cost is not allowed, for example, an importer not requiring valuation to fluctuate with exchange rate differences.
Latest Cost
The most recent Cost Price entered for a Stock Receipt or calculated for a Manufacture.
Average Cost
A weighted average Cost Price of the stock item taking into account all receipted / manufactured stock and inwards stock adjustments. It is recalculated when Receipt transactions or Manufacture transactions are posted, the calculation is as follows,
((Quantity in stock prior to the receipt * Average cost prior to the receipt) + (Quantity receipted * Cost Price for receipt)) / Quantity in stock after receipt is posted = New Average Cost.
If the quantity in stock prior to the receipt is negative, or the calculated Average is not within reasonable bounds for the stock held, the Average cost is reset to the Cost Price for the receipt or manufacture (that is, the Latest cost).
The Latest and Average costs of non-diminishing products can be excluded  from updating when Receipts are posted by clearing the Update Non Diminishing Costs selection in
IC Settings
.
Discount Code
Define the discounts to apply to products and customers during invoicing. Click
Open Discount Schedule
to see the
Discount Schedule
.
Note: For Automatic Kitset products, if any of the component Products have a Discount Code set, the Discount Codes of each of the products will be used. You can manually change these.
Sell Prices Grid
See
IC Sell Prices Grid
.
GST Code
The rate of GST charged can vary from Product to Product (particularly for businesses providing both taxable supplies and some exempt financial services). Select the code as defined in
GST Codes & Rates
. The Product
GST Code
selected takes priority over the
Sales Group
GST Code.
Tracking
See
IC Product - Tracking
.
Note: Tracking panel is hidden if IC > Products > Tracking permission is set to None.
Tax
Select a default GST Code for the Product in the base Tax Regime.
If the company has more than one active Tax Regime, you can set a default
Override GST Code
for the product in other Tax Regimes.
Lower Options
Location
Shows the product location.  (Accredo Saturn Only)
Components
Click to open
IC Components
for the product.
Components Of
This button will be available if there are components associated with the product. Opens
IC Product Component Of
for the product.
In This Section
IC Product - Tracking
IC Sell Prices Grid
IC Product - Information tab
IC Product - UOM tab
IC Product Validation Failures
IC Product - Supplemental tab
IC Product - Quantity tab
IC Product - Locations Tab
IC Product - Image tab
IC Product - Links tab
IC Product - Memos tab
IC Product - Activity tab
IC Product - Graph tab
IC Product - Transactions tab

---

## IC Product - Quantity tab

Source: https://accredo.co.nz/webhelp/ICProducts_Quantity.htm

IC Product - Quantity tab
Navigator > Maintain > Inventory Control > Products > Quantity tab
Choose a location from the lower left
Location
lookup to show quantities. To select all locations, click
All Locations
. (Accredo Saturn Only)
See also
IC Products - Product tab
.
Quantity UOM
(
UOM
Active Only)
Available when
UOM
is
Active
or
Pending
. Select the UOM to display quantities in.
Initially set to the
Base UOM
,
Sale UOM
,
Purchase UOM
or
Manufacture UOM
for the Product according to the
UOM Enquiry Default
specified in
User Preferences
.
Note: Quantities will be rounded down to be displayed with the number of decimals of the selected
UOM
.
Quantities
In Stock
Stock currently on hand.
- Allocated
Allocated stock includes:
Stock allocated in Sales Orders and Invoices that have not been posted from OE and / or IN.
Stock in unposted JC Batches.
Positive manufactures with pending usages.
Negative manufactures (dis-assemblies) pending manufacture.
- Transfer Out
Stock quantity transferred out of the selected location.
Stock allocated in Sales Orders and Invoices that have not been posted from OE and / or IN. Also includes unposted JC Batches. (Accredo Saturn Only)
= Available
Stock available for sale, that is, In Stock less Allocated.
+ Variance
The quantity from pending adjustments due to stocktake variance, credit write offs, and other adjustments.
+ Transfer In
The quantity being
transferred
into the selected location.  (Accredo Saturn Only)
+ On Order
The quantity ordered from suppliers.
+ Shipped
The quantity on Shipments not yet receipted.
- Back Order
The quantity on back order for Customers.
- Committed
Stock On Order or Shipped that is already committed to a Job.
+ Returned
The quantity pending inwards from credits, including negative manufactures pending usages.
+ In Production
The quantity currently in pending manufacture.
= Theoretical
The theoretical quantity in stock if all Sales Orders and outstanding Invoices were supplied and processed, all Back-orders fulfilled, all orders received from suppliers, all stock In-transit received, all quantities returned and quantities in production considered, and an update from stocktake completed.
Bin Code
The location of the product in the warehouse. (Accredo Mercury Only)
Minimum Maximum
Minimum and maximum quantities to be held in stock. If the quantity in stock falls below the minimum level a quantity is calculated and can be included on the Product, Product by Location and Stock Sales and Valuation report layouts. You can generate a Purchase Order to bring stock to the maximum level by using the
Generate Order
button on the
PO Enter Purchase Order
form. Minimum Quantity and Maximum Quantity are only relevant for diminishing items. See
Re-Order Report
for details of how these fields are used.
Accredo Saturn Only: The fields on this tab are read-only; to edit these values, refer to the
Locations tab
. Accredo Mercury Only:The Maximum Quantity cannot be below the Minimum Quantity.
Rec. Reorder
The Recommended Reorder amount is calculated as follows:
If
Theoretical
stock <
Minimum Qty
, then
Rec Reorder
=
Maximum Qty
less
Theoretical
.
If UOM is used, the Rec. Reorder quantity will be rounded up to the next UOM if necessary.
Accredo Saturn Only: Maximum and minimum quantities are entered on the
Locations
tab.
Pending Stock Movements Grid
View details of pending stock movement for each Product.
Period
Select the date range to show stock movements for.
Motion
Select the type of pending stock movement, or select
All Pending
to see all.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens the related document to be viewed.
Print
(Ctrl+P)
Print the Stock Movement report, or save as an Excel worksheet, or PDF file to send.
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
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Grid Fields
Quantity In
The Product quantity to be entered into stock.
Quantity Out
The Product quantity to be removed from stock.
Balance
The balance of stock available.
Source
The source module of the document.
Class
The type of stock movement.
Location
The Location of the stock. (Accredo Saturn Only)
Date
The pending date of the stock movement.
Party Code
The Customer, Creditor or Job code (left blank for stock transfers).
Document
The type of document the stock movement originated from.
Effective Date
Dependant on the movement
Source
and
Class
:
Source
Class
Effective Date is:
AP
Shipped
ReceiptDate for the Shipment line.
OE
Allocation or Back Order
DateSupplied from the order line if specified.
DeliveryDate from the order header if DateSupplied is blank.
DocumentDate (OrderDate) from the order header if DeliveryDate and DateSupplied are blank.
IN
Allocation
DateSupplied from the invoice line if specified.
DeliveryDate from the invoice header if DateSupplied is blank.
DocumentDate (InvoiceDate) from the invoice header if DeliveryDate and DateSupplied are blank.
IC
Transfer in Transit
Dispatch date or Receipt date from the transfer header.
PO
Order on order
DateExpected from the PO order line if specified.
DateRequired from the PO order header if DateExpected is blank.
JC
Batch Allocation
TransactionDate from the batch line.

---

## IC Product - Supplemental tab

Source: https://accredo.co.nz/webhelp/ICProducts_Suppliers.htm

IC Product - Supplemental tab
Navigator > Maintain > Inventory Control > Products > Supplemental tab
Link suppliers and bar codes to a product. Set Job defaults for a product. You can also associate a customer with a bar code and have several suppliers and bar codes for the same product, or customers that require a bar code.
See also
IC Products - Product tab
.
Supplier grid
Creditor Code
Enter suppliers to the Supplier grid tab by clicking in the Creditor code field.
Supplier Cost
The most recent cost from the supplier. Set the default Cost Price and Discount to use in PO Purchase Orders and AP Shipments in
AP Settings - Shipments tab
.
Supplier Discount
The most recent discount from the supplier.
Vendor Code
Add the Vendor code if it differs. If a Vendor code is added, the Vendor Code field in Purchase Order lines is populated with that code.
Lead Time
Lead Time Unit
Defaults for Lead Time may be set per
Creditor
. Set Lead Time here if a different lead time applied for this product.
The Lead Time and Lead Time Unit (Days, Weeks or Months) are used to calculate the Date Expected on Purchase Order lines.
Additional Cost
This amount will be used as the default additional cost for AP Shipments for this Creditor and Product if additional costs are Manually Apportioned. The Additional Cost is updated when a Shipment is posted. The last entered Additional Cost is displayed.
Date Of Last Receipt
The most recent receipt date from the supplier.
Comment
Type a note regarding when or why to use this supplier, for example, "only if urgent", "only for a certain Customer", or "only if other suppliers cannot supply".
Supplier Cost Date
The date Supplier Cost was last updated. For foreign suppliers, this is the date Supplier Cost Bs (base currency) and Exchange rate relate to.
Supplier Standard Cost
The usual cost from the supplier. Price books are typically imported to this price. Set the default Cost Price and Discount to use in PO Purchase Orders and AP Shipments in
AP Settings - Shipments tab
.
Supplier Standard Discount
The usual discount from the supplier.
Minimum Order Quantity
The minimum order quantity that the Supplier will accept for the Product.
Creditor Inactive
Indicates if the Creditor for the Cost record is Inactive. Inactive records are hidden by default.
When you post an AP Shipment receipt for the product, Accredo adds the supplier to the Supplier grid for the product, updates the Supplier Cost, Vendor code, Additional Cost, Date of Last Receipt, Supplier Cost Date, Exchange Rate and Supplier Cost Bs for the supplier.
If you specify a default supplier, you can select or filter products on lookups and reports, and generate Purchase Orders containing only products where the supplier is the default supplier. To specify a default supplier on the Product tab, select the supplier Creditor code. The supplier details will be added to the Supplier grid as the default supplier the first time you post an AP Shipment receipt for this product. Or on the Suppliers/Bar Codes tab, select the supplier, click
Set as Default
(Ctrl+B),
click again to turn off the default status. The default supplier details will appear in bold on the grid, and their Creditor code will be selected in the Creditor field on the Product tab.
Fields
Duty
The import duty percent applicable, this figure appears as the default in the
Duty (%)
field of
AP Shipment
lines.
Lead Time
(Deprecated) A numerical field that can be used to assist in forecasting order requirements. This has been superseded by per Creditor Lead Time defaults and the Supplier grid (above) Lead Time values which override the defaults if set.
JC Tran Type
If set this is the default JC Transaction Type for the product when used for a job transaction.
Cost Centre
If set this is the default
JC Cost Centre
for the product when used for a job transaction.
Component
If set this is the default
JC Component
for the product when used for a job transaction.
Bar code grid
Bar Code
Must be unique. Scan or type the bar code number in the bar code grid.
Creditor Code
You can (but are not required to) associate a bar code with a Creditor code, for example, if different suppliers supply the same Product with different bar codes.
Customer Code
You can (but are not required to) associate a bar code with a Customer code, for example, if a customer has their own bar coding system.
Comment
For example a note regarding when or why to use this bar code, or information that can be useful in scripting.
UOM Code
You can (but are not required to) associate a bar code with a UOM code, for example, if you have a different bar code for a box of a product than for a single item.
To specify a default bar code on the Product tab, add the bar code to be added to the Bar code grid as the default code when the product is saved. Or select the bar code on the Suppliers/Bar Codes tab, click
Set as Default
(Ctrl+B)
on the Bar code grid toolbar (click again to turn off the default status). The default bar code will appear bold, and is updated in the
Bar code
field on the Product tab. This will be the default code for printing labels and documents.
Grid Toolbars
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view for product supplier or bar code information.
Insert
(F4)
Click to add a new supplier or bar code.
Delete
(F3)
Delete the selected supplier or bar code.
Print
(Ctrl+P)
Opens IC Product Cost Report or IC Product Bar Code Report, see
Report Selections Form
.
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
Set as Default
(Ctrl+S)
Set the row currently selected as the default supplier or bar code.
Hide / Show Inactive Suppliers
(Ctrl+H)
Hide or show inactive suppliers.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Product - Tracking

Source: https://accredo.co.nz/webhelp/ICProducts_Tracking.htm

IC Product - Tracking
Navigator > Maintain > Inventory Control > Products > Products tab >Tracking
Set tracking options for diminishing products which are Lot tracked (also know as Batch tracked or Expiration tracked) and/or Serial tracked.
Access to these fields requires IC > Products > Tracking permission in addition to the IC Product permission.
Lot Tracking
Lot Nos
Selected
, product is lot tracked.
Clear
, (default), product is not lot tracked.
Valid characters for Lot numbers are 0 to 9 and A to Z. To allow other characters see
Lot  No Special Characters
in
IC Settings - General tab
.
Lot No Length
(Optional) If set Lot Nos will be required to be this length when entered.
Supply Single Lot
Selected
, when determining Lots to supply only Lots which fulfill the entire quantity will be considered, e.g. when a single dye lot is required for colour matching.
Clear
, more than one lot may be selected to supply.
Expiry Date
Selected
, product is Expiry date tracked. Expiry dates are required on receipt and evaluated on supply.
Clear
, (default), product is not expiry date tracked.
Minimum Expiry
Minimum Expiry Unit
If Expiry Date Tracked, specify the minimum number of days, weeks, months or years prior to expiry required when determining product to supply.
The date the minimum expiry period is tested against is :
Date Supplied
if specified in IN Line or OE Line.
Falling back to
Delivery Date
if specified in IN Header or OE Header.
Falling back to
Document Date
or
Transaction Date
.
Generate Lot Nos
None
, (default), Lot No must be entered.
Expiry Date
, Lot No is generated from Expiry Date in YYYYMMDD format.
Lot Date
, Lot No is generated from Lot Date  in YYYYMMDD format.
Serial Tracking
Serial Nos
None
, (default), product is not serial tracked.
Sale
, product is serial tracked at point of sale, usage or return but not while in stock.
Purchase
, product is serial tracked for all transactions.
Valid characters for Serial numbers are 0 to 9 and A to Z. To allow other characters see
Serial No Special Characters
in
IC Settings - General tab
.
Note: Serial tracked products must have all quantities in whole numbers, and Serial No is entered for each unit.
Serial No Length
(Optional) If set Serial Nos will be required to be this length when entered.
Tracking History
Retain Tracking years
Number of years of tracking history to retain for the product.
Tracking for lots or serial numbers is pruned automatically during IC End of Period as it falls outside the years to retain.
Turning on Tracking for Products with Quantities
Negative stock is not allowed for tracked products.
Tracking fields may selected or cleared subject to user permissions. When selected any current quantities in stock must be positive, and for Serial Nos must be whole numbers, quantities are considered as initially an Unspecified Lot No and Unspecified Serial Nos. Product tracking cannot be turned on while the product is on a Dispatched but not Receipted Stock Transfer. (Saturn Only)
Perform a
Detailed
Stocktake per location for the product to enter required Lot No or Serial No breakdown.
When tracking options are cleared (or reduced) all related tracking information including tracking history is removed.

---

## IC Product - Transactions tab

Source: https://accredo.co.nz/webhelp/ICProducts_Transactions.htm

IC Product - Transactions tab
Navigator > Maintain > Inventory Control > Products > Transactions tab
Lists transactions relating to the product.
Accredo Saturn Only: Choose a Location from the lower left
Location
lookup to show transactions for a specific location. To select all locations, click
All Locations
.
See also
IC Products - Product tab
.
Selection
Period
Transactions entered in the selected Period are shown, Current Period is the default.
Last Period
Transactions entered in the period prior to the Current Period are shown.
Year
Transactions for the current financial year are shown.
Last Year
Transactions for the previous financial year are shown.
Full Year
Transactions for the current period last year through to the last available IC period are shown.
All Periods
All transactions are shown.
Range of Periods
Activates the
From
and
To
period controls. Select a continuous range of periods to view.
Opening
Displays the opening balance for the Balance column, as at the period selections.
Grid toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a transaction.
Open Details
(F12)
View and edit details for the transaction.
Drill down
(Shift+F12)
View the source document. You can also double-click to open the source document.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Print
(Ctrl+P)
Print a report of the grid information.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Refresh
(F5)
Transactions are reloaded to reflect changes other Users may have made.
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Find
(Ctrl+F)
Find a transaction using the Transaction ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Product - UOM tab

Source: https://accredo.co.nz/webhelp/ICProducts_Units.htm

IC Product - UOM tab
Navigator > Maintain > Inventory Control > Products > UOM tab
Displays the Base UOM (Unit of Measure) and Other UOMs, with their multipliers and decimals. Only available if UOM Status is set to
Pending
or
Active
in
IC Units of Measure
.
See also
IC Products - Product tab
.
Base UOM
Base UOM
Enter or select the
Base UOM
for the product. The
Base UOM
must be set as a
Base
in
IC Units of Measure
and must have a multiplier of
1
.
Click
Open Units of Measure
(Shift+F12) to open
IC Units of Measure
.
Multiplier
The multiplier for the
Base UOM.
This will always be
1
.
UOM Decimals
The number of decimals set for the
Base UOM
in
IC Units of Measure
.
Comment
Add information per UOM per Product.
Base UOM Grid Toolbar
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
Other UOM
Other UOM
Enter or select other UOM codes for the Product from the same
UOM Group
as the
Base UOM
. Other UOMs can be applied to the product.
Click
Open Units of Measure
(Shift+F12) to open
IC Units of Measure
.
Note:  If
UOM Groups
are used
Other UOMs
are limited to the UOM Group of the
Base UOM
.
Multiplier
The multiplier for the Other UOM set in
IC Units of Measure
. If the UOM does not have a
Fixed Multiplier
, this can be edited.
UOM Decimals
The number of decimals set for the UOM in
IC Units of Measure
.
Other UOM Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert an Other UOM.
Delete
(F3)
Delete the selected Other UOM from the list.
Note: If the Other UOM is being used for the Product in a pending transaction or as a component, Delete will be unavailable.
Print
(Ctrl+P)
Opens
IC Product Other UOM Report
, see
Report Selections Form
.
Customise Fields
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Default Other UOM
(Ctrl+D)
Adds all the Other UOMs in the Base UOM Group. Only available if the Other UOM list is empty.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Default UOMs
Default Sale UOM
Set the UOM code which will apply when the Product is entered in IN Invoice and OE Sales Order lines.
Default Purchase UOM
Set the UOM code which will apply when the Product is entered in PO Purchase Order and AP Shipment lines.
Default Manufacture UOM
Set the UOM code which will apply when the Product is entered for Manufacture in an IC Manufacture Batch or Transaction.

---

## IC Product Batch Labels

Source: https://accredo.co.nz/webhelp/ICReports_BatchLabel.htm

IC Product Batch Labels
Navigator > Reports > Inventory Control > Product Batch Labels - OR -
Navigator > Tasks > Invoicing System > Enter Invoice >
Print Product Labels
(Alt+U)
button
An alternative to
Product Labels
, you can select the Products and Count you require labels for.
You can print labels previously designed using
Label Designer
.
Accredo Saturn Only: Optionally, select a Location Code to print Location specific information.
Default report file names can be setup from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
Label Designer
.
See also
Report Selections Form
.
Product Grid Toolbar
Select Product codes, Count and Bar Codes of labels to print.
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line in the grid.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Delete
(F3)
Removes the record from the grid.
Sort
(Ctrl+F2)
Sort the list.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Ctrl+I)
Import a tab delimited or CSV file listing labels to print.
Format is Product Code, Count, Source Module, Source Document ID, Source Line ID, Custom 1, Custom2, UOM Code, Barcode. Only Product Code is required, remaining columns are optional with place holders required if a later field is to be specified. Count defaults to 1 if not specified.
Export
(Ctrl+E)
Export contents of the grid to a tab delimited file, same columns as the import format.
Start from label
On sheet feed labels, you can start printing a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.
Product Grid Fields
Note: You can click
Customise Fields (Alt+F5) to show any of these fields in the grid.
Product Code
The product to print labels for.
Count
The number of labels to print for the product.
When
Print Product Labels
is selected from a document the count is set to the quantity from the document line.
Barcode
The default barcode is populated, other barcodes may be selected to print if the product has multiple barcodes.
If
UOM
is enabled and a UOM Code is associated with the selected barcode it is selected with the barcode.
Custom 1 / Custom 2
Text entered in these fields may be printed on the labels.
Description
The Product description.
Lot No
If the product is
Lot No
tracked a Lot No to print may be selected.
Serial No
If the Product is
Serial No
tracked a Serial No to print may be selected.
Source Document ID
Source Line ID
Source Module
When
Print Product Labels
is selected from a document these fields are populated, allowing information from the source document and line to be printed on the labels.
UOM Code
The UOM Code for the label if
UOM
is enabled.

---

## IC Product Bin

Source: https://accredo.co.nz/webhelp/ICBinLocations.htm

IC Product Bin
Navigator > Maintain > Inventory Control > Product Bins
You can bulk edit Bin Codes for a selected range of Products and Location, for
Bin Tracked
Locations this is setting the default bin for inwards stock. (in Accredo Saturn). Make selections then click Run to list bin codes.
Maximum and Minimum Quantities for the Products and Location (in Accredo Saturn) may also be edited subject to the Product > Quantities permission.
Selections Form
Location
Select a location to show bin codes for. (Accredo Saturn Only)
Product From / To
Select a product or range.
Stock Group From / To
Select a stock group or range.
Creditor
Select a creditor to show bin codes for.
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
Show the list of bin codes.
Bin codes are shown for the selections in a live edit grid. You can edit the bin code for products.
Bin Codes Form
Code
The Product code.
Description
The Product description.
Unit
The Unit for the Product.
Bin Code
The Bin Code for the product. You can edit the Bin Code here.
In Stock
The quantity of the product in stock at the location selected (in Accredo Saturn).
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Print
(Ctrl+P)
Print the grid, save it to an Excel worksheet or PDF file.
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
Find
(Ctrl+F)
Find
a Product using the Product ID.
In This Section
IC Find Bin Code

---

## IC Product Component Of

Source: https://accredo.co.nz/webhelp/ICViewComponentOf.htm

IC Product Component Of
Navigator > Maintain > Inventory Control > Component Of
or Navigator > Maintain > Inventory Control > Products > Product tab >
Component Of
button
Displays a list of products the selected product is a component of.
Grid
Product Code
The product code of the product.
Description
The description of the product.
Inactive
Shows if the product is Inactive.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens the selected product in a new window.
Drill down
(Shift+F12)
Opens
Components
for the selected product. You can also double-click to open the Components form.
Print
(Ctrl+P)
Print the list, save it to an Excel worksheet or PDF file.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reload changes other Users may have made.
Show/Hide Inactive
(Ctrl+H)
Show or hide inactive products.

---

## IC Product Labels

Source: https://accredo.co.nz/webhelp/ICReports_Label.htm

IC Product Labels
Navigator > Reports > Inventory Control > Product Labels
You can print labels previously designed using
Label Designer
.
Default report file names can be set from Navigator > Setup > Company > Reporting >
Document Defaults
.
See also
Report Selections Form
.
Location
Optionally, select the Location to print Product Labels for. You can use the Filter button to only print labels for selected locations. (Accredo Saturn Only)
Report File Name
The file that defines the product labels layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
Label Designer
.
Product - From / To
You can select a range of products, or use the Filter button to filter products.
Display Inactive
Selected
, displays active and inactive products.
Number of Label Copies
The number of copies for each label.
Start From Label
On sheet feed labels, you can start printing a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.

---

## IC Product List

Source: https://accredo.co.nz/webhelp/ICProductList.htm

IC Product List
Navigator > Maintain > Inventory Control > Product List
Click
to make selections, and use the
lookups
.
Selections
Display Inactive
Inactive records are hidden from view with financial information and history retained for reporting.
Selected,
Inactive records are shown.
Clear,
Inactive records are hidden from view.
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Products
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Products
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Product Code
A unique alpha numeric code of up to 28 characters. Data can only be entered when inserting new products.
Description
Further product description.
Stock Group
The Stock Group closing stock and stock on hand values for this item to be attributed to. Also commonly used for grouping inventory reports. These are setup from Navigator > Maintain > Inventory Control >
Stock Groups
.
Creditor Code
The default Creditor code the product is purchased from.
Standard Cost
A Cost Price for valuation and pricing where fluctuation with latest or average cost is not allowed, for example, an importer not requiring valuation to fluctuate with exchange rate differences.
Latest Cost
The current Cost Price entered for a Stock Receipt.
Average Cost
A weighted average Cost Price of the stock item taking into account all receipted stock. It is recalculated when Receipt transactions are posted, the calculation is as follows:
((Quantity in stock prior to the receipt * Average cost prior to the receipt) + (Quantity receipted * Cost Price for receipt)) / Quantity in stock after receipt is posted = New Average Cost
If the quantity in stock prior to the receipt is negative, the Average cost is reset to the Cost Price for the receipt (that is, the Latest cost).
Category 1, Category 2
For Products. Categories can be added from Navigator > Maintain > Inventory Control >
Categories 1&2
. Labels can be replaced in
IC Settings
.
Minimum Quantity, Maximum Quantity
Minimum and maximum quantities to be held in stock. If the quantity in stock falls below the minimum level a quantity is calculated and can be included on the Product, Product by Location (Accredo Saturn Only) and Stock Sales and Valuation report layouts. You can generate a Purchase Order to bring stock to the maximum level by using the
Generate Order
button on the
PO Enter Purchase Order
form. Minimum Quantity and Maximum Quantity are only relevant for diminishing items. See
Re-Order Report
for details of how these fields are used. The fields on this tab are read-only; to edit these values, refer to the
Locations tab
(Accredo Saturn) or
Quantity tab
(Accredo Mercury).
Quantity on Order
The quantity ordered from suppliers.
Quantity Allocated
Stock allocated in Sales Orders and Invoices that have not been posted from OE and / or IN. Also includes unposted JC Batches.
Quantity on Back Order
The quantity on back order for Customers.
Quantity in Stock
Stock currently on hand.
Quantity Committed
Stock On Order or Shipped that is already committed to a Job.
Date of Last Manufacture
Date the product was last manufactured.
Quantity Shipped
The quantity on Shipments not yet receipted.
Selling Prices 1-9
Prices, Currency Codes Markups and Margins for Price lists mapped to
Price Mapping
numbers 1 through 9.
Note: Margins are calculated for base currency prices only from valuation cost.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Opens
IC Product
to insert a new Product.
Open Details
(F12)
Opens the product in
IC Product
, where you can view or edit details.
Print
(Ctrl+P)
Print the list, save it to an Excel worksheet or PDF file.
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
Reloads the list with changes other Users may have made.
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
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Footer
Record Count
The total number of records shown in the list. Click
to refresh the total number.

---

## IC Product Quantities

Source: https://accredo.co.nz/webhelp/ICProductQuantities.htm

IC Product Quantities
Navigator > Maintain > Inventory Control > Product Quantities
Also launches from documents when the
Product Quantities
(Ctrl+Q)
button is clicked from a Product grid toolbar. You can enquire on details of quantities on order, back order, allocated or in-transit and product stock levels at all locations (in Accredo Saturn). This is typically used when checking when quantities on order from a supplier are expected, or entering a sales order to find a location with available stock (in Accredo Saturn).
Quantities tab
Shows quantities and other details for each location (in Accredo Saturn).
UOM Code
(
UOM
Active Only)
Select the UOM to display quantities in.
Initially set to the
Base UOM
,
Sale UOM
,
Purchase UOM
or
Manufacture UOM
for the Product according to the
UOM Enquiry Default
specified in
User Preferences
.
Allocated, Back Ordered, On Order, Shipped, Committed, In Transit (Accredo Saturn Only), In Production, Returned, Variation tabs
These tabs provide information on pending stock movements. From the tabs you can open the originating document for each pending stock movement. For example, you can drill down to view an order and change dates, or drill down to a transfer document and edit it to juggle stock at various locations (in Accredo Saturn).
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
F12)
Open the document and locate the relevant line.
Print
(Ctrl+P)
Print a report of the information.
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
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
See Also
Inventory Control - Maintain

---

## IC Product Reports - Add Layout

Source: https://accredo.co.nz/webhelp/ICProductReports.htm

IC Product Reports - Add Layout
Navigator > Reports > Inventory Control > Product Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
Comparison reports can be run at any period and automatically include records that were active in the selected period, derived from transactions and balances. Valuation reports contain data from the current period or end of time and only report values that are currently active. Valuation reports are typically faster to run than comparison reports.
Accredo will check if product revaluations are required, and will prompt you to revalue if necessary.
See also
Report Selections Form
.
Layouts
Bar Codes
Shows Bar codes by product. You can report bar codes for a given Customer or Creditor, Range of Products or all bar codes. Supplier fields on the Report band are populated from the default Supplier (
Creditor Code
on the
IC Product tab
) if one is specified.
Component Of
Shows the finished products that items are components of, that is, it is the opposite view to the component report below.
Components
Shows the components, quantities, cost price and extended cost for manufactured stock items and Kitsets. Select a Product range and Selling Price from the
Selections
button, when you add a layout.
The manufactured item or Kitset Product code and description are printed followed by the components. Cost prices shown will be standard, latest or average depending on the valuation basis specified in
IC Settings
.
Group Sales and Valuation
A group summarised version of the Stock Sales and Valuation Report. This shows the current values and doesn't show previous periods. To see previous periods use the
Product Balances
report.
Location Balances
Reports product by location balances as at selected period. (Accredo Saturn Only)
No Activity
Reports products with no activity of selected types  since a specified date.
Price Code List
Report on prices for all or a selected Price Code.
Include Price Code and group by Price Code or Product Code if reporting for more than one Price Code.
Price List
Report on prices by
Price No mapping
for products.
SellingPrice1 - 9 are the list prices, Sell1 - 9 the discounted prices if a Customer Discount Code is selected.
Product
Provides information from the Product record. You can report on Products and Stock Groups, for Creditors and Locations (in Accredo Saturn) as at the current date and period. You can customise in period to date and year to date figures. Product information and supplier details can be customised in, by selecting Customise, then using the Report, Information and Supplier tabs. Supplier fields on the Report band are populated from the default Supplier (
Creditor Code
on the
IC Product tab
) if one is specified.
If
Ignore Minimum Quantity
is
Selected
, minimum quantities will not be considered when calculating reorder quantities.
Reorder quantities are calculated consolidated by product if location is not specified.  (Accredo Saturn Only)
Note: The report includes a number of calculated fields relating to stock value:
Closing Value Period To Date = Closing (Quantity) Period To Date * Valuation Cost
Stock Value = Quantity In Stock * Valuation Cost
Value Standard = Quantity In Stock * Standard Cost
Value Latest = Quantity In Stock * Latest Cost
Value Average = Quantity In Stock * Average Cost
Product and Location Detail
Report on quantities in stock, on order, and allocated, and can be summarised by product or location.
If
Ignore Minimum Quantity
is
Selected
, minimum quantities will not be considered when calculating reorder quantities.
Reorder quantities are calculated per location  (Accredo Saturn Only)
Product Balances
Select data from the Product table and the balances table to provide information on quantities, values, and sales, as at the end of a selected period. You can report on one or more product and / or Stock Group, for a given or all creditors and locations (in Accredo Saturn). If a location is specified, quantities are shown for the location.
Quantities are shown as at the end of the selected period. When reporting for the Current period you are prompted to revalue if there are any pending
revaluations
since these are not included in stock value, revaluation prior to reporting is recommended.
Note: Unit Cost = Closing Value / Closing Quantity
Closing Value = Opening Value + Movement value (i.e. cost value from transactions) + Revaluation value
Product by Locations
A master report showing the quantities for each location in the detail band. Supplier fields on the Report band are populated from the default Supplier (
Creditor Code
on the
IC Product tab
) if one is specified. (Accredo Saturn Only)
Product Links
Report on links for products.
Sales and Usage
Shows quantities, cost and value sold for period and year to date. Stock usages (that is, components of invoiced Kitsets or manufactured items and usages in JC) are included in the figures. The report is useful to see real stock usages (as opposed to just sold items). The report can be run as at any period.
Sales Budget
Shows 12 period budget figures from the period selected back.
Total is the total of budgets from earliest period included to the reporting period.
Sales Budget Comparison
Contains budget and activity figures for the selected period and year to date. Percentages compare budgets with the activity. This report can be run at the end of any period.
Sales Comparison
Contains quantities and values sold for period and year to date including comparisons with the same period last year and total up to the same period last year. The percentages show current sales as a percentage of last year sales, that is, a percentage greater than 100% indicates an increase in sales. The report can be run at any period.
Stock Group Comparison
A group summarised version of the Sales Comparison Report above.
Stock Sales and Valuation
Produces a report of products to detail stock values, sales and cost of sales. Totals are shown as a summary of the inventory system. Stock is valued on the basis of the In Stock (that is, closing stock) quantity. If you integrate IC with the GL this report shows the stock value which is used for the transfer to the GL. This will be standard, latest or average depending on the
IC Settings
. Supplier fields on the Report band are populated from the default Supplier (
Creditor Code
on the
IC Product tab
) if one is specified. This shows the current values and doesn't show previous periods.
Supplier Price List
Report on supplier costs by product.
Thirteen Period Sales
Print a report of up to 13 months sales (by quantity) for each Product. You can report on sales only, usages only or both for selected Products, Stock Groups, Creditors, Locations (in Accredo Saturn) and Periods.
UOM Report
Lists the UOMs available for each Product.
UOM Quantities
Reports the quantities for products with the selected UOM Code. You can select to filter this by a particular Location (in Accredo Saturn). Displays the information available on the
IC Products - Quantity
tab when a Quantity UOM is selected.

---

## IC Product Sheet Designer

Source: https://accredo.co.nz/webhelp/ICProductSheetDesigner.htm

IC Product Sheet Designer
Navigator > Setup >Inventory Control > Product Sheet Designer
You can design your own product sheets or open and modify an existing product sheet design. To design a product sheet quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
The IC Product Sheet Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code.
Name
Iterators filter records that are shown in the report. Available Iterators are:
Components
- Components of the Product
UOMs
- UOMS available for the Product
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Product Sheet Designer in addition to the standard
objects
are:
Component
Fields from the Component record.
Product
Fields from the Product record.
UOM
Fields from the UOM record.
Sample IC Product Sheets are provided with the Accredo Server Install. Sample IC Product Sheets include:
ICProductSheet.pfd
- standard IC Product Sheet
ICProductWithComponentsSheet.pfd
- IC Product Sheet showing components of products
To use documents downloaded from the website, ensure your document designer is the latest version.

---

## IC Product Sheets

Source: https://accredo.co.nz/webhelp/ICProductSheets.htm

IC Product Sheets
Navigator > Reports > Inventory Control > Print Product Sheets
Product Sheets can be printed individually from Navigator > Maintain > Inventory Control >
Products
.
See also
Report Selections Form
.
Report File Name
The Report File Name specifies the file that defines the Product sheet layout.
Set a default report file name from Navigator > Setup > Company Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
IC Product Sheet Designer
.
Product - From / To
Select a product or range to print Product sheets for.

---

## IC Product Tracking Query

Source: https://accredo.co.nz/webhelp/ICProductTrackingQuery.htm

IC Product Tracking Query
Navigator > Maintain > Inventory Control > Product Tracking Query
Also launches from documents when the
Product Quantities
(Ctrl+Q)
button is clicked from a Product grid toolbar. You can enquire on details of quantities on order, back order, allocated or in-transit and product stock levels at all locations (in Accredo Saturn). This is typically used when checking when quantities on order from a supplier are expected, or entering a sales order to find a location with available stock (in Accredo Saturn).
Quantities tab
Shows quantities and other details for each location (in Accredo Saturn).
Allocated, Back Ordered, On Order, Shipped, Committed, In Transit (Accredo Saturn Only), In Production, Returned tabs
These tabs provide information on pending stock movements. From the tabs you can open the originating document for each pending stock movement. For example, you can drill down to view an order and change dates, or drill down to a transfer document and edit it to juggle stock at various locations (in Accredo Saturn).
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
F12)
Open the document and locate the relevant line.
Drill Down
(Shift +F12)
Drill Down.
Print
(Ctrl+P)
Print a report of the information.
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
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
See Also
Inventory Control - Maintain

---

## IC Product Tree

Source: https://accredo.co.nz/webhelp/ICStockTree.htm

IC Product Tree
Navigator > Maintain > Inventory Control > Product Tree
View a product range in the Product Tree. Expand or collapse a Stock Group, Product or list of components. View the selected value, cost and quantity figures from the Stock Group or Product record. Click a product to open
IC Product
to edit or view more details.
Selections
Tree View
Select from the following,
Stock Group
Stock Groups are the first level of data to be shown.
Product
Products are the first level of data to be shown (that is, Stock Groups are not included in the tree).
Inactive
Include
inactive records
in the tree.
From / To
To view:
All Stock Groups or Products
, leave these fields blank.
A Stock Group or Product
, select the same Stock Group or Product in both fields using the Lookup.
A range of Stock Groups or Products
, select the first Stock Group or Product in the
From...
field, and the last Stock Group or Product in the
To...
field.
Transactions
Select the period to view data for:
Period
Activity from transactions for the selected period are shown.
Year
Activity from transactions for the current year are shown.
All Periods
Activity from all transactions are shown.
Range of Periods
Select a range of periods to appear in the Period From/Period To Lookups.
Selections remain applied as you select different Products or Stock Groups.
Location
Select a Location to view data for. To view details for Products at all locations, leave this blank.  (Accredo Saturn Only)
Tree View
Groups/Products field
Information is arranged in fields. The Product Tree is arranged as follows if
Tree View
Stock Group View
is selected:
Stock Group CODE - Description
Product CODE - Description
Component CODE - Description
Component CODE - Description
Component CODE - Description
If
Tree View
Product View
is selected, the Stock Group level above is absent. Click a product to open
IC Product
to edit and view more details.
Other fields
The default fields shown can be changed using
Customise
(Alt+F5)
button.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Detail
(F12)
Opens the window for the selected Product or Stock Group.
Print
(Ctrl+P)
Print the tree, save it to an Excel worksheet or PDF file.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.

---

## IC Product Usage for UOM

Source: https://accredo.co.nz/webhelp/ICProductUsageforUOMCode.htm

IC Product Usage for UOM
Navigator > Setup > Inventory Control > Units of Measure >
UOM Code Usage Query button
(Ctrl+Q)
>
Product Query
Displays all IC Products using the selected UOM Code.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
(F12)
Open details of the selected product in
IC Product
.
Print Report
(Ctrl+P)
Print a product usage report of products using the selected UOM Code.
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
Grid Fields
Product Code
IC Product Code.
Description
Description for the product code.
Base UOM Code
Base UOM Code for the Product.
Inactive
Shows whether the Product is Inactive.

---

## IC Product Validation Failures

Source: https://accredo.co.nz/webhelp/ProductValidationFailures.htm

IC Product Validation Failures
Navigator > Maintain > Inventory Control > Products >
Save
button
Validation failures related to Units of Measure (UOM) or Product tracking changes are shown here.
UOM
If a Product has existing figures using decimals, you cannot change to a UOM with less decimals if the figures cannot be represented. Similarly, if a Product is a component of another product that has the Product quantity in decimals, the new UOM must have the same or more decimals.
See
IC Units of Measure
to check the number decimals for each UOM.
Serial Nos
In Stock and all pending quantities must all be whole numbers for Serial No tracking to be turned on.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
(F12)
Open the Product that has the validation failure.
Print
(Ctrl+P)
Print the IC UOM Validation Results, see
Report Selections Form
.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Customise
Fields
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.

---

## IC Receipt Batch List

Source: https://accredo.co.nz/webhelp/ICReceiptBatchList.htm

IC Receipt Batch List
Navigator > Maintain > Inventory Control > Receipt Batch List
This option available if
Allow IC Sourced Receipts
is selected in
IC Settings
.
Click
to make selections, and use the
lookups
.
Selections
Period
Select a period to view for:
Period
- Select a single period in the
From
selection.
Year
- Displays batches for the current year.
All Periods
- All batches are displayed.
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
Default is Range of Periods with From Period set to First Available period for IC or period of first Current Batch whichever is earlier, and To Period set to Last Available period for IC.
Selection
Select to show batches that are:
Unposted
Open
Posted
Deleted
All Batches
(excludes Deleted batches)
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Receipts
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Receipts
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Batch
The Receipt Batch identifier.
Details
Details entered for the batch.
Date
Date of the receipt batch.
Status
Post status of the receipt batch.
Location
Location of the receipt batch. (Accredo Saturn Only)
Period
Period the receipt batch occurs in.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a receipt batch.
Delete
(F3)
Delete the receipt batch. Only available for saved, unposted batches, when the user has permission.
Open Details
(F12)
Opens Batch data entry. View the details for the
Receipt Batch
including all lines. You can edit an unposted batch.
Print
(Ctrl+P)
Print the IC Receipts List. You can save as an Excel worksheet or PDF file and send as an email attachment.
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
The Receipt Batch list to reload changes other Users may have made.
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
Post selected
(
Alt+T
)
Post the selected receipt batch.
Post all up to current period
(
Alt+A
)
Post all receipt batches up to the selected period.
Find
(Ctrl+F)
Find a batch using the Batch ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.
Button
Batch
(Alt+B)
Locate a Batch by the Batch ID.
In This Section
IC Find Receipt Batch ID

---

## IC Report Period

Source: https://accredo.co.nz/webhelp/ICReportDesignerPeriod.htm

IC Report Period
Navigator > Setup > Inventory Control > Statement Designer > View > Reporting Period
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
IC Transfer Designer

---

## IC Reprice from Components

Source: https://accredo.co.nz/webhelp/ICRepriceComponents.htm

IC Reprice from Components
Navigator > Tasks > Inventory Control > Update Prices > Reprice from Components
Re-calculate Cost and Selling Prices for Manufactured and Manual Kitset items from the component Cost and Selling Prices so you can update a price on a Manufactured item if a single component increases in cost. Choose Products to reprice by applying a Product range, filtering on the Product file, selecting by Stock Group and by Creditor. Repricing from components does not apply to
Automatic Kitset
lines, as these do not have their own price.
Update Type
Select from:
Query Run,
(default), new prices for each Product will be shown in a query window before updating. You will have the choice for each Product to edit, update or cancel.
Report Only,
report the effect of applying the selections made in the Price Update without actually changing the prices. If report destination is
Screen
select
Regenerate
from the Report Preview to return to the selection form with all selections retained.
Automatic,
proceed with the price update based on the selections.
Cost Prices to Update
Select cost prices repricing applies to. If using a query run, prices can be updated manually.
Markup Basis
Select the basis to mark up by. Defaults to the Markup Basis specified in IC Settings.
If
Automatically Apply Markups
is
Selected
in
IC Settings
, this is set to the Default Markup Basis and cannot be changed.
Sell Prices
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise Fields
(Alt+F5)
Opens
Customise Fields
- you can customise fields visible in the grid.
Action
None,
no change to the sell price.
Update,
update the sell price to the sum of the component prices multiplied by the component quantities.
Markup,
re-calculate the sell price by marking up from the Markup Basis price after prices are updated.
Code
The Price code.
Currency
The currency for the Price code.
Markup Price
If Markup Basis is Price code - the Price code that this Price code is marked up from.
Round Direction
Default from the Price Code settings. Specify the rounding direction used when calculating the price for a product where markups or global price update is used.
Round Unit
Defaults from the Price Code settings. If you type a value here, the newly calculated prices will be rounded to match the amount, for example, to round to the nearest dollar, enter 1.00.
Include Inactive
Selected
, include inactive products in the update.
Run
(F9)
Reprice and show the results.

---

## IC Revalue Stock on Hand

Source: https://accredo.co.nz/webhelp/ICRevalueStockOnHand.htm

IC Revalue Stock on Hand
Navigator > Tasks > Inventory Control > Revalue Stock On Hand
You can Revalue Stock on Hand many times during a period. Stock on Hand revaluation occurs automatically when an
IC End Of Period
is performed, or on demand when this option is selected. The IC Balances will be updated and a GL Batch will be created if integration to GL is available.
Stock on Hand value is calculated for diminishing products (those you hold stock for) as:
Closing Stock Quantity Current Period * Valuation Cost (from Product at time of revaluation) = Closing Stock Value Current Period
Revaluation is calculated as:
Closing Stock Value - Opening Stock Value - Movement Value (from transactions) = Revaluation
Any changes to Closing Stock Value due to revaluations will not reflect in the balances until Stock on Hand is revalued.
We recommend you revalue stock on hand before reporting IC Balances for the current period.
Before reporting IC Balances for the Current Period, Revalue Stock on Hand
If the
Integrate to GL
option in
IC Settings - Integration tab
is set to
Summarised
or
Detailed
, Revaluation will create a GL batch. This transfers the change in Stock on Hand due to revaluations since the previous revaluation, between the Stock on Hand in the balance sheet, and the Closing Stock in the trading account. The GL Accounts are specified for each
Stock Group
.
What causes revaluations?
Revaluations for Stock on Hand cover any changes to stock value which are not included in the Movement value for the period (that is, sum of cost of transactions for diminishing stock items). There is not a specific event that triggers creating revaluations, it is a calculation per Product and Location (in Accredo Saturn). The following will all give rise to revaluations:
Valuing on Latest cost.
Editing Cost Prices, including edits that happen automatically when updating from AP Shipment invoices.
Rounding where Prices are stored to more decimal places than Amounts.
Posting transactions into a prior or future Period at a different cost from the cost at End Of Period for that period.
What about negative stock?
If you have selected
Allow Negative Stock
in
IC Settings - General tab
, tab then you may have negative In Stock quantities when stock is valued. Negative quantities are valued in the same way as positive quantities and reduce total stock value.
When stock is revalued how does it reflect the changing value due to shifts in exchange rates?
All of IC – other than Selling Prices and Supplier Cost prices – is handled in base currency. Revaluation does not alter the cost at which stock is being valued, it simply ensures stock is valued at the cost specified.
Exchange rates on receipts (AP Shipments) are used for calculating the base currency cost which will be applied to the IC Receipt transaction and flow into their Latest Cost and Average cost calculation.
Manufacture transactions which also flow into the Latest Cost and Average cost calculation all occur in base currency at the sum of the valuation costs on the components.
To change the valuation of your Inventory the valuation costs would need to change. Valuation cost is the cost price selected as your
Valuation Basis
in
IC Settings
.
To update Cost Prices, recalculate Supplier Cost prices in base currency, and update sell prices to reflect changes in exchange rates, you can use the options under
Update Prices
to do this in bulk. Each can be done for a range of Products, a selected Supplier or a Stock Group.
Changing cost prices will result in a revaluation in the current period when you select Revalue Stock on Hand.
See Also
Inventory Control - Tasks

---

## IC Select Products

Source: https://accredo.co.nz/webhelp/ICBinMovementSelect.htm

IC Select Products
Bin tracking is only available for Accredo Saturn Stock Locations.
Navigator > Tasks > Inventory Control > Bin Processing > Bin Movement >
Add Products from Bin
Generate lines to be added lines to the
Put-Away
bin movement.Saturn only.
Enter selections, then click
Run
to generate the lines.
Move From Bin
Select the bin the products are to be moved (Put-Away) from, defaults from the Bin in the batch header.
Move To Bin
Select the bin the products are to be moved to, or leave blank to move to the
default bin
for the product and location.
Product From / To
Select a range of products for the bin movement, or leave blank to include all products in the bin.
Click
Filter / Sort
(Ctrl+F2)
to filter the products.

---

## IC Select Stocktake

Source: https://accredo.co.nz/webhelp/ICSelectStocktake.htm

IC Select Stocktake
Navigator > Tasks > Inventory Control > Stocktake Processing > Insert Count >
Run
button
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Quantities >
Run
button
IC Select Stocktake opens if there is more than one unposted Stocktake  for the location (in Accredo Saturn) that Count or Quantities could be added to.
Grid toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Buttons
Select
(F9)
Add the Count or Quantities to the selected Stocktake.

---

## IC Sell Prices Grid

Source: https://accredo.co.nz/webhelp/ICSellPricesGrid.htm

IC Sell Prices Grid
Navigator > Maintain > Inventory Control > Products > Products tab > Sell prices grid
The grid shows a line for each Price code, setup from Navigator >
Setup > Company > Configuration > Price Lists
.
The Price codes can be retail, trade, or wholesale.
See also
IC Products - Product tab
.
Price UOM
(
UOM
Active Only)
UOM Price
will be displayed for the UOM selected. Defaults to the
Default Sale UOM
.
Grid Columns
Code
The Price List Code for the price. Price Codes are set up in
Price Lists
.
Price
Each product can have a Selling Price for each Price code. When Customers are setup in AR, set the Price code for Invoicing. The Selling Price is transferred to the invoices generated in IN and to the Sales Order entered in OE (possibly subject to an adjustment or a discount from the
Discount Schedule
). For Special Pricing options such as contract pricing or date based specials use
Special Pricing
.
Markup
Shows the markup from cost price for the Price Code.
Selected,
set Markup Percentages for calculation of Selling Prices. Set the Markup Basis and choose to Apply Markups from
IC Settings
. Selling Price options are calculated as follows,
None
No markup calculations are used.
Standard
Sell Price n = Standard Cost + Markup n % x Standard Cost.
Latest
Sell Price n = Latest Cost + Markup n % x Latest Cost.
Price Code
Sell Price x + Markup n % x Sell Price x (Sell Price x is the Markup Price code selected under IC Settings).
Markups can be negative (a discount percentage), use this when setting markups on Price codes, for example, you can use the retail Price code as the Markup Price code, and calculate trade and wholesale Selling Prices using a negative markup.
Name
Shows the Price List Name from
Price List
.
UOM Price
The price per
Price UOM
selected.
Margin
For Base Currency sell prices, the effective margin percentage.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Print Report
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Markup Prices
(Ctrl+M)
Applies the Markup percentage to the markup basis Cost Price or Price Code to determine the Selling Price.
Special Pricing Information
(Ctrl+4)
Opens Special Pricing Price Query (if available), you can query the results of a rule applied to a line. If a Special Price is applied, the rule reference displays with other information depending on the Special Pricing script.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Settings - Display Labels tab

Source: https://accredo.co.nz/webhelp/ICSettings_DisplayLabels.htm

IC Settings - Display Labels tab
Navigator > Setup > Inventory Control > Settings > Display Labels tab
Set the display labels for the categories and custom fields.
Name
The name of the custom or category field, and where it is used.
Label
Enter the label you wish to be used for the custom or category field. If no label is entered, the field
Name
will be displayed.

---

## IC Settings - First Period on Perpetual Integration / First Period on Periodic Integration

Source: https://accredo.co.nz/webhelp/ICSettings_Integration_PeriodForChange.htm

IC Settings - First Period on Perpetual Integration / First Period on Periodic Integration
Navigator > Setup > Inventory Control > Settings > Integration tab > change
Integration Basis >
Save
(
F9
)
When you change
Integration Basis
, select the first period to start the change from.
Any Transfers to GL for the selected period or later will be reset. Any IC sourced GL batches on or after the Period previously transferred should be unposted and deleted.
Note: That this only applies to Inventory Control so any processing already done in Accounts Payable for Stock Purchases on or after the period will require manual adjustment to use the correct GL Account.
See also
Perpetual and Periodic Inventory Control Integration
.
Period
Select the first period for Perpetual Integration.
Buttons
Edit
(F11)
Enter edit mode.
OK
(F9)
Set the first period for Perpetual Integration.
Cancel
(Esc)
Discard changes and close the form.
See Also
IC Settings - Integration tab

---

## IC Settings - General tab

Source: https://accredo.co.nz/webhelp/ICSettings.htm

IC Settings - General tab
Navigator > Setup > Inventory Control > Settings > General tab
Valuation Basis
Stock can be valued on Standard, Latest or Average cost. The valuation basis has the following effects:
All stock values including those shown during stock queries and printed on inventory reports are calculated using the specified Cost Price.
Issues and Credits entered in IC, and Invoices and Credits entered in IN, use the specified Cost Price to calculate cost of sales. The cost of sales is dependent on the valuation basis. Changing the valuation basis will not immediately affect the current cost of sales, as this is calculated from the applicable Cost Price at the time of sale.
Allow Negative Stock
Clear,
you cannot post transactions that cause the quantity in stock to become negative, for example, stock must be receipted before it can be sold. You can enter sales orders or invoices that exceed the quantity in stock but you cannot post the invoices until sufficient stock is available. We do not recommend allowing negative stock.
Note: Regardless of this setting negative stock in not allowed for
Serial No
or
Lot No
tracked products or
Bin Tracked
locations (Saturn).
Allow IC Sourced Receipts
Clear
, default if AP installed, receipting via shipments only, recommended.
Selected,
default if AP not installed. Receipt transactions may be entered from IC.
Note: Do not Allow IC Sourced Receipts when
Integration Basis
is
Perpetual
since Receipts need a matching Purchase invoice in AP to clear the Stock Purchases Clearing account.
Allow IC Sourced Issues and Credits
Clear
, default if IN installed, issues and credits via IN invoices and credits only, recommended.
Selected,
default if IN not installed, Issue and Credit transactions may be entered from IC.
Allow IC Manufacturing
Clear
, default, IC Manufacturing is not available.
When
Allow IC Manufacturing
is cleared unposted Manufacturing data and Diminishing Components are cleared.
Selected,
IC Manufacturing is available. Enables Components for Diminishing Products and Manufacture Batches.
Note: Requires the Manufacturing Extension in Subscription systems.
Allow IC Manufacture Transactions
Setting not available if
Allow IC Manufacturing
is not
Selected
.
Clear
, default, IC Manufactures are processed only via IC Manufacture Batch.
Selected,
IC Manufacture transactions may be entered provided no tracking is required.
Coded Bins
Selected,
default and recommended. Bins are coded records per location. Required for bin tracked locations (Saturn).
Clear,
bins are free text with no lookup.
Post Zero Quantity Lines
Select the action to take when posting an IC batch with zero quantity lines. Select from:
No Prompt
Prompt Delete Selected
Prompt Delete Unselected
Allow Edit For Posted Documents
Selected,
posted batches can be edited, where the User has permission.
Clear,
posted batches cannot be edited.
Generate Outward Tracking
Selected,
(default and recommended) for
tracked products
and tracked
Locations
(Saturn only)
tracking detail
is
generated
for outward movements.
Clear,
no outward tracking is generated.
Generate From Bin With ... Quantity Available
Smallest,
(default and recommended) for tracked
Locations
generated
outward tracking will select from bins with smallest quantities within a Bin Priority. Effect is to preferentially minimise "orphan" quantities and number of bins used for the product.
Greatest,
generated outward tracking will select from bins with greatest quantities within a Bin Priority.  (Saturn only)
Serial No Special Characters
Allow Space
A-Z and 0-9 are allowed by default. Any other characters required for serial numbers may be specified. Comma is not allowed.
Selected,
spaces are allowed in serial numbers.
Clear,
(default) spaces are not allowed.
Lot No Special Characters
Allow Space
A-Z and 0-9 are allowed by default. Any other characters required for lot numbers may be specified. Comma is not allowed.
Selected,
spaces are allowed in lot numbers.
Clear,
(default) spaces are not allowed.
New Product Defaults
Non-Diminishing
Selected
, Non-Diminishing appears when adding products. Sales figures are recorded but no stock quantities are maintained for Non-diminishing products. The common example is labour, but this can apply to all products.
Back Order
Selected,
Back Order is selected when adding products. Back Order must not be selected for products that cannot be back ordered.
Manually Costed
Selected,
new products will be manually costed.
See
Navigator > Maintain > Inventory Control > Products
Lead Time Unit
Set default for Lead Time Unit.
Days, Weeks, Months
.
Required
Weight
Selected
, non-zero weight is required for IC Products.
Volume
Selected
, non-zero volume is required for IC products.
Creditor
Selected
, a Default Creditor is required for IC products. (Available when AP is installed.)
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
IC Settings - Prices tab
IC Settings - Stocktake tab
IC Settings - Misc tab
IC Settings - Period tab
IC Settings - Display Labels tab
IC Settings - Memos tab
IC Settings - Integration tab
IC Settings - Links tab
IC Settings - Words tab

---

## IC Settings - Integration tab

Source: https://accredo.co.nz/webhelp/ICSettings_Integration.htm

IC Settings - Integration tab
Navigator > Setup > Inventory Control > Settings > Integration tab
See also
IC Settings - General tab
.
Integrate to General Ledger
Determines how to integrate IC to the GL.
Summarised
- will integrate to the GL by producing batches which transfer Transaction Type totals only for each Product by Branch and Department codes (in Accredo Saturn) specified for Stock Groups.
Detailed
- will integrate to the GL by producing batches that transfer on a transaction by transaction basis to the GL codes specified.
Not integrated
- if you do not want to integrate to the GL.
We recommend
Summarised
rather than
Detailed
. It is simpler to retain the history in IC and summarise information in the GL. Integration between IC and GL is handled by the creation of Transaction Batches on demand. Batches will be placed in the list of unposted GL Batches. To perform the integration procedure you must post those batches.
If you change from
Not integrated
to
Summarised
or
Detailed
, you will be prompted for a Period to start the integration from. If transactions before the period that have not been transferred to GL exist, they will be marked as Transferred to GL without creating a GL batch. This process can take some time.
Integration Basis
Select the basis for integrating to the General Ledger:
Perpetual
- Stock Purchases go into
Stock on Hand
, and when stock is sold, the cost value of the stock is journaled between
Stock On Hand
and
Cost of Sales
to give an accurate
Cost of Sales
for direct comparison with Sales. Non-diminishing cost of sales is journaled between
Expense Recovery
and
Cost of Sales
.
This is the default setting for new companies.
Periodic
- The
Cost of Sales
in the financial reports is calculated as
Opening Stock
plus
Stock Purchases
less
Closing stock
.
Cost of Sales
journals are processed for non-diminishing products between the
Purchase Expense
and the
Closing Stock
Accounts for the stock group. At End of Period the
Closing Stock
becomes the
Opening Stock
for the next period.
This is a simple model, but
Cost of Sales
may vary from the actual value of goods sold in the period if stock is not purchased and on-sold promptly.
See
Perpetual and Periodic Inventory Control Integration
for more information.
If you change from Periodic to Perpetual, you will be prompted to select the
First Period on Perpetual Integration
.
Note:
GL Accounts in Settings are the defaults for new
IC Stock Groups
. The accounts specified on Stock Groups are the ones used when transferring to GL.
GL Stock on Hand Account
The GL account used for the Balance Sheet side of all IC Diminishing Stock Transactions and Revaluations regardless of Integration Basis.
For Perpetual Basis
GL Cost of Sales Account
The account used for Issues (Sales), Credits, Kitset Usages and Job Usages. For example, Chart of Accounts 2100.000 Cost of Sales.
GL Stock Purchases Account
The account used for Receipts, and for AP Shipment Invoice lines relating to diminishing Products. For example, Chart of Accounts 9950.000 Purchases Clearing Account.
GL Stock Adjustments Account
The account used for Adjustments due to posted stocktake variances and other adjustment transactions. For example, Chart of Accounts 2200.000 Inventory Adjustment Account.
GL Stock Write Offs Account
The account used for Adjustments due to write-offs from IN Credits. For example, Chart of Accounts 2200.000 Inventory Adjustment Account.
GL Stock Revaluation Account
The account used for
Revaluations
. For example, Chart of Accounts 2300.000 Inventory Revaluation Account.
GL Stock Manufactures Account
The account used for Manufactures and Manufacture Usages. A single account is used rather than per Stock Group to ensure these clear.
GL Stock Transfers Account
The account used for Transfers. A single account is used rather than per Stock Group to ensure these clear.(Saturn only)
GL Expense Recovery Account
The account used in place of Stock On Hand account for Non-Diminishing Manufacture Usages, e.g. Labour Cost for a Manufacture, and for Non Diminishing Issues, Credits, Kitset Usages and Job Usages. There is no default account number for this. An example would be Labour Recovery as used in the Accredo Demo Data.
For Periodic Basis
GL Closing Stock Account
The default account for Closing Stock in the trading account section of the GL. When you transfer to the GL, increases in the stock value will credit this account, and decreases in stock value will debit this account.
GL Transfer Out Account
The default account used to create journal transactions, transferring the cost of products between Branches and Departments. When you transfer IC Transfer transactions to the GL, the account for the Branch and Department associated with the location is debited with the value of the stock dispatched. (Accredo Saturn Only)
GL Transfer In Account
The default account used to create journal transactions, transferring the cost of products between Branches and Departments. When you transfer IC Transfer transactions to the GL, the account for the Branch and Department associated with the location is credited with the value of the stock received.
For example, if you purchase items from a central warehouse then distribute them to a number of retail outlets, you can transfer the cost of the purchases to the retail outlet. Journal transactions are only created where the Transfer In an Transfer Out accounts are specified for the Stock Group. (Accredo Saturn Only)
Note: If you change Integration GL Accounts, on
Save
you will be prompted to apply the Integration GL Account changes to any
Stock Groups
that have matching GL Accounts.
In This Section
IC Settings - First Period on Perpetual Integration / First Period on Periodic Integration
Perpetual and Periodic Inventory Control Integration
See Also
IC Settings - General tab

---

## IC Settings - Links tab

Source: https://accredo.co.nz/webhelp/ICSettings_Links.htm

IC Settings - Links tab
Navigator > Setup > Inventory Control > Settings > Links tab
For each Account you can specify the default Link path within the Links folder. This path will be resolved and used as the default path for the
Link File
dialog and the
AddFileLink
function when adding links for the Account.
Link paths can reference fields in the Account File and the ModuleCode inside <> tags. If PeriodID is a field in the account file PeriodName and PeriodEndDate may also be used inside tags. Date fields in link paths format as YYYYMMDD.
e.g. <ModuleCode>\<ProductCode>
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

## IC Settings - Memos tab

Source: https://accredo.co.nz/webhelp/ICSettings_Memos.htm

IC Settings - Memos tab
Navigator > Setup > Inventory Control > Settings > Memos tab
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
Set the selected memo as the default for IC memos.

---

## IC Settings - Misc tab

Source: https://accredo.co.nz/webhelp/ICSettings_Misc.htm

IC Settings - Misc tab
Auto Select
IC Product List
IC Transaction List
IC Transfer
(in Accredo Saturn)
IC Memo List
IC Link List
IC Stocktake List
IC Tracking Log
IC Manufacture Batch List
IC Adjustment Batch List
IC Receipt Batch List
IC Bin Count List
(Saturn)
IC Bin Movement List
(Saturn)
Selected,
Auto Select for the list is selected by default.
Clear
, Auto Select is unselected for the list. This is recommended where there is a large number of records or the network is slow.
Product and Location Codes (Locations Saturn only)
Product Code /
Location Code
Special Characters
A-Z and 0-9 are allowed by default. Any other characters required for product codes may be specified. Comma is not allowed.
Allow Space
Selected,
spaces are allowed in codes.
Clear,
(default) spaces are not allowed.
Report Codes with Invalid Chars
Reports any Active Codes which do not comply with the current valid character settings.
Note: Codes may be Aliased to comply with changed valid character settings if desired but this is not required, settings apply to new codes only.

---

## IC Settings - Period tab

Source: https://accredo.co.nz/webhelp/ICSettings_Period.htm

IC Settings - Period tab
Navigator > Setup > Inventory Control > Settings > Period tab
See also
IC Settings - General tab
.
Current Period
Choose the Current Period before you enter transactions. After transactions have been entered, this can only be changed by using the End Of Period option.
First Available Period
The earliest period that can be posted to. Must be earlier than than or equal to Current Period.
Last Available Period
The latest period that can be posted to. Must be later than than or equal to Current Period.
First History Period
The earliest period history is retained for.
Retain Years History
The number of years to store history for. The minimum is
1
, which includes the current and last years' data. This setting is used when you
prune history
.
Actual Years of History
The number of years of history actually stored.
Advance First Available At End Of Period
Selected
, the
First Available Period
will be automatically advanced during an End Of Period process.
Advance Last Available At End Of Period
Selected
, the
Last Available Period
will be automatically advanced during an End Of Period process.
Last EOP User
The user who ran the last End Of Period.
Last EOP Performed
The date the last End of Period was run.
IC Last Recovered
The date the most recent IC
file recovery
was performed.
Inactivate Discontinued Products
Determine when discontinued products are made inactive,
Manual
- discontinued products are not made inactive except when manually edited.
At EOP
- discontinued products which can be made inactive will be made inactive at End of Period.
At EOY
- discontinued products which can be made inactive will be made inactive at End of Year.
Note: Available periods, i.e. the range of periods between First Available Period and Last Available Period must all be status Open. The periods available to a User are further limited by the
User Settings
for
Prior and Future Periods allowed for Posting
.

---

## IC Settings - Prices tab

Source: https://accredo.co.nz/webhelp/ICSettings_Prices.htm

IC Settings - Prices tab
Navigator > Setup > Inventory Control > Settings > Prices tab
See also
IC Settings - General tab
.
Markup Basis
Set the markup basis for markup percentages to calculate Selling Prices.
None
Markup percentages act as memo fields in IC (that is, they are not used in calculating Selling Prices) but can be used for markups in JC.
Standard
Markup percentages are applied to the standard cost to calculate the Selling Price.
Latest
Markup percentages are applied to the latest cost to calculate the Selling Price.
Average
Markup percentages are applied to the average cost to calculate the Selling Price.
Price Code
Markup percentages are applied to the Selling Price for the Price code specified in
Default Markup Price Code.
When you change to
Price Code
basis, on Save, you will be prompted to apply the Default Markup Price Code to all Price Lists without a Markup Price Code, which are not a source for Markups.
Default Markup Price Code
This is required when the
Markup Basis
is
Price Code
. Select the default Price Code.
Automatically Apply Markup
Selected,
Selling Prices will be calculated on the specified Markup Percentage when a price with that Markup Basis changes.
Clear,
Selling Prices will be calculated on the specified Markup Percentage:
When
Markup prices
(
Ctrl+M
) is clicked in
IC Selling Prices & Markups grid
.
During a
Global Price Update
when a Markup basis and
Markup
have been selected for Selling Prices.
During a
Reprice from Components
when a Markup basis and
Markup
have been selected for Selling Prices.
Stamp Modified on Sell Price Update
Selected,
the Modified Date, Time and User Code for the product will update when Selling Prices are updated from Global Price Updates, Reprice from Components, Copy Price List, Price Book Import, and Automatic Markups.
Clear,
will not update.
Stamp Modified on Cost Price Update
Selected,
the Modified Date, Time and User Code for the product will update when Cost Prices are updated from AP Shipments, IC Receipts, IC Manufactures, Global Price Updates, Reprice from Components and Price Book Import.
Clear,
will not update.
Update Non Diminishing Costs
Selected,
the Latest and Average cost for Non Diminishing Products will update when Receipts are posted.
Clear,
will not update.
Price Mapping
You can map up to 9 Price codes. Selling Prices and Markups for mapped Price codes are replicated into the IC Product file as SellingPrice1-9 and MarkupPercent1-9. They will be available for filtering and sorting Product records, can be customised into product lookups, and allow backwards compatibility for existing scripts and EDI import and export routines from versions prior to 2.5.

---

## IC Settings - Stocktake tab

Source: https://accredo.co.nz/webhelp/ICSettings_Stocktake.htm

IC Settings - Stocktake tab
Navigator > Setup > Inventory Control > Settings > Stocktake tab
See also
IC Settings - General tab
.
Count Type
Select the default type of Count from:
Basic
- A simple stocktake with no Count options available. With this default type, the Enter Quantities option is available in the Navigator.
Single
- One count will be done per Product and Location.
Additive
- Several counts can be done for each Product and Location. This includes support for
UOM
.
Detailed
- Counts include Serial No and Lot No and Bin code for bin tracked locations (Saturn)detail.
Note: Options relating to Counts below will be unavailable when
Basic
is selected.
Count type default can be set per
Location
.  (Saturn)
Include Nil Quantity
Selected
, Products with Nil quantities will be included in the stocktake by default. Defaults to
Clear
.
Generate Counts
Selected
, Count Lines and a Count Header will be created for the stocktake by default.
Click
Default sort order for generated counts
to set a default Count sort order.
Counts Per
Select fields to produce counts per. Counts will be grouped by the fields selected. Click
Edit
(F2)
to add fields.
Number of Counts
Enter the default Number of Counts to be created when a new stocktake is generated.
For
Additive
and
Detailed
Stocktakes, the number of counts will be created with all products for the stocktake. For Single
Stocktakes,
products will be split evenly between the number of counts.
Copy Expected to Counted
For
Single
Counts only, when Counts are generated, the Expected quantity will be copied to the Counted quantity.
Import Format
You can import stocktake quantities from a file, rather than keying them in manually. Select the default file format. The format of the file can be:
Standard
- use with tab delimited or comma delimited (.csv) files. format is:
Product Code, Quantity
Standard
with Bin
- use with tab delimited or comma delimited (.csv) files. format is:
Product Code, Quantity, Bin Code
Opticon
- standard Opticon laser terminal format.
UOM
- only valid for Additive Counts. File format is:
Product Code, UOM Code, UOM Quantity Counted
- OR -
Product Code, UOM Code, UOM Quantity Counted, Bin Code
Detailed
- only valid for Detailed Counts. File format is:
Product Code, UOM Code, UOM Quantity Counted
, Bin Code, Serial No, Lot No, Lot Date, Expiry Date
In all formats
Barcode
can be substituted for
Product Code
.
For non UOM leave UOM Code empty.
File Name
Select the default file name and path to import from.
Post Nil Variance Transactions
Selected
, when a Stocktake is Posted, an adjustment transaction will be posted for all products in the stocktake, including those with a nil variance.
Clear
, when a Stocktake is Posted, adjustment transactions will only be posted for products in the stocktake with a variance.
Post to First Available if Period Not Available
Selected
, when a Stocktake is Posted, if the Stocktake period is earlier than IC First Available Period, adjustment transactions will be posted to the First Available Period.
Clear
, Stocktake period must be available when a Stocktake is Posted.

---

## IC Settings - Words tab

Source: https://accredo.co.nz/webhelp/ICSettings_Words.htm

IC Settings - Words tab
Navigator > Setup > Inventory Control > Settings > Words tab
You can enter information to be included in the index for Word Lookups
.
See also
IC Settings - General tab
.
Break Characters
Characters in addition to spaces that denote ends of words (for example, colon, semi-colon, dash). A space is considered a break character.
Note: Tab characters are displayed as Â».
Ignore Characters
Characters to ignore (for example, parentheses, dashes). It is important to cover characters used in phone numbers correctly. For example, if you store phone numbers (09)373-5961 and:
dashes and parentheses are both ignored; you can look up 093735961.
dashes and parentheses are considered break characters; you can look up 09 or 373 or 5961, but not the whole number.
dashes are ignored and parentheses are considered break characters, you can look up 09 or 3735961.
Minimum Length
The minimum number of characters that make a word.
Any Word
Determines the state of the checkbox when
Word Lookup
is opened.
Partial Word
Determines the checkbox state when
Word Lookup
is opened.
Ignore Words
Ignores words that appear too often (for example, the, and, PO, Box, Ltd).
Product Lookup Fields
Products can be word indexed to be located from a Product Lookup control. Default fields indexed are
Description
and
Details
. Other text fields may be selected to be indexed.
Vendors code
can be selected as a Product Lookup Field to include in word indexes for Products for easy location of Products by Vendor code.
You can include
BarCode
as a Product Lookup Field to include all bar codes for products in the word indexes.
Product Sort Order
Select a field to order Product lookup results by, if blank results are ordered by Product Code.
Location Lookup Fields
Products can be word indexed to be located from a Product Lookup control. Default field indexed is
LocationName.
Other text fields may be selected to be indexed. (Accredo Saturn Only)
Location Sort Order
Select a field to order Location lookup results by. If
blank,
results are ordered by Location Code. (Accredo Saturn Only)
Grid Toolbars
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new word or field.
Delete
(F3)
Delete the selected word or field.
Export
(Ctrl+E)
Exports the list of words as a text file, you can import the same words for another module or Company.
Import
(Ctrl+I)
Imports a list of previously exported words as a text file, saving time when adding the same or similar words for several Modules or a Company. A sample list of words to ignore is provided with the file name,
IgnoreWords.txt
.
Rebuild Words
(Ctrl+R)
Rebuilds the index, including new fields and settings.

---

## IC Single Count

Source: https://accredo.co.nz/webhelp/ICSingleCount.htm

IC Single Count
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Single Count
Available when the
Count Type
in
IC Settings - Stocktake tab
is
Single
.
Available when the
Count Type
for one or more Locations in
IC Stock Locations
is
Single
. ( Accredo Saturn.)
For
Single
Count Stocktakes first Generate the Stocktake with the Products to be counted.
Location
Select the location for the stocktake. (Accredo Saturn Only)
Run
(F9)
The selected records appear in
IC Single Count - Enter Quantities
.
If there is more than one Unposted Stocktake available, you will be prompted to select the Stocktake to add to.
In This Section
IC Single Count - Enter Quantities

---

## IC Single Count - Enter Quantities

Source: https://accredo.co.nz/webhelp/ICSingleCountEnterQuantities.htm

IC Single Count - Enter Quantities
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Single Count >
Run
(F9)
button
Available when the
Count Type
in
IC Settings - Stocktake tab
is
Single
.
Available when the
Count Type
for one or more Locations in
IC Stock Locations
is
Single
. ( Accredo Saturn.)
IC Single Count Enter Quantities grid is live - information is saved as you move off each field.
The form will open with the products for the selected stocktake loaded with the
Expected
figures recorded when the stocktake was generated.
IC Enter Quantities grid
Code, Description, Unit
Product details from the product record.
Quantity Expected
The number of items recorded as in-stock when the Stocktake was generated. If transactions are posted to the period after the stocktake is generated and you want to update expected quantities this can be done from the
Stocktake
form using
Reload Expected Quantities
.
Quantity Counted
Enter the counted quantity.
Variance
The difference between the
Expected
and
Counted
figures above. This is updated when you enter an quantity in the
Counted
field and move off the field.
Counted
Becomes
Selected
when a figure is entered in the number
Counted
column, or when the
Mark Counted
or
Mark All Counted
buttons are clicked.
Note: Where Quantity Expected = Quantity Counted only lines marked Counted are added to the Stocktake Count.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Print
(Ctrl+P)
Print the IC Stocktake Report.
Filter & Sort
(Ctrl+F2)
Clear
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
Find
(Ctrl+F)
Find
a product using the Product Code.
Mark Counted
(
F4
)
Mark the selected product as
Counted
.
Mark Uncounted
(
F3
)
Mark the selected product as
Uncounted
.
Mark All Counted
(
Shift+F4
)
Mark all products as
Counted
.

---

## IC Stock Group

Source: https://accredo.co.nz/webhelp/ICStockGroups.htm

IC Stock Group
Navigator > Maintain > Inventory Control > Stock Groups
Add, edit or delete Stock Groups and specify GL Accounts for closing stock and stock on hand for each Stock Group. You can make Stock Groups inactive. Stock Groups are identified by unique codes of up to 8 characters that can include both letters and numbers. Stock Groups have these main uses:
GL Account codes specified on Stock Groups are used to determine postings to the GL of stock movement and revaluation.
IC Integration
Settings control the
Integration Basis
and hence which accounts are required.
If GL Accounts mapped to Stock Groups are changed, this can result in a re-grouping batch where it will journal any previously transferred stock from the old GL accounts to the new GL accounts.
You can analyse the most productive (and unproductive) Stock Groups.
Stock Groups can be used as selection criteria on IC reports, the reports can be selected for ranges of groups.
IC reports can be grouped by Stock Group.
Grid Fields
Code
The unique code for the Stock Group. This cannot be edited once a Stock Group is created. Stock Group
0000
is the default Group code that is used to analyse products when the Stock Group is unspecified.
Stock Group Name
The name that will appear on reports and lookup controls.
Default UOM Code
(
UOM
Pending or Active)
The Default UOM Code for products in the Stock Group.
Inactive
You cannot post transactions for products associated with inactive Stock Groups. Check for products associated with the Stock Group and re-assign them before making a Stock Group inactive. To do this, filter on StockGroupCode in IC Product. If there are a number of products associated with the Stock Group, you can use a script to re-assign them. Inactive Stock Groups are shown in grey in the grid.
GL Stock on Hand
The account used for the Balance Sheet side of all IC Diminishing Stock Transaction and Revaluations regardless of Integration Basis.
For Perpetual Basis Integration
GL Cost of Sales
The account number of the Cost of Sales account in the GL, used for Issues (Sales), Credits, Kitset Usages and Job Usages.
GL Purchases
The account number of the Purchases account in the GL, used for Receipts, Transfers (Saturn only), Manufactures and Manufacture Usages, and for AP Shipment Invoice lines relating to diminishing Products.
GL Adjustments
The account number of the Stock Adjustments account in the GL, used for Adjustments due to posted stocktake variances and other adjustment transactions.
GL Write Offs
The account used for Adjustments due to write-offs from IN Credits.
GL Revaluation
The account number of the Stock Revaluation account in the GL, used for
Revaluations
.
GL Expense Recovery
The account number of the Expense recovery account in the GL, used in place of Stock On Hand account for Non-Diminishing Manufacture Usages, e.g. Labour Cost for a Manufacture, and for Non Diminishing Issues, Credits, Kitset Usages and Job Usages.
For Periodic Basis Integration
GL Closing Stock
The account number of the Closing Stock account in the trading account section of the GL. When you transfer to the GL, increases in the stock value will be credited to this account (a decrease in stock value would result in a debit).
GL Transfer Out
Used to create journal transactions, transferring the cost of products between Branches and Departments. When you transfer
IC Transfer
transactions to the GL, account for the Branch and Department associated with the location is debited with the value of the stock dispatched. (Accredo Saturn Only)
GL Transfer In
Used to create journal transactions, transferring the cost of products between Branches and Departments. When you transfer
IC Transfer
transactions to the GL, account for the Branch and Department associated with the location is credited with the value of the stock received. For example, if you purchase items from a central warehouse, then distribute them to a number of retail outlets, you can transfer the cost of the purchases to the retail outlet. Journal transactions are only created where the transfer in and transfer out accounts are specified for the Stock Group. (Accredo Saturn Only)
Grid Fields
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
Access grid fields in Form view for each line on the grid. Groups can be entered or edited in the form or on the grid. To view more fields use the scroll buttons or resize the window.
Insert
(F4)
Enter additional Stock Group codes and information.
Delete
Delete Stock Group codes and information - only available if there are no Transactions related to the Stock Group.
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
Reloads changes other Users may have made.
Default GL Accounts
(Ctrl+D)
Sets the GL Accounts for the selected group to the default GL Accounts set in
IC Settings - Integration tab
.
Note: If the default accounts are blank, existing accounts will not be overwritten.
Apply Default UOM Code
(Alt+U)
(
UOM
Pending or Active)
Opens the
IC Apply Default UOM - Stock Group
window. Applies the
Default UOM
for the selected Stock Group to the
Base UOM
for selected Products in the Stock Group.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
In This Section
IC Apply Default UOM - Stock Group

---

## IC Stock Locations

Source: https://accredo.co.nz/webhelp/ICStockLocations.htm

IC Stock Locations
Accredo Mercury holds stock at a single location. Stock locations are only available for Accredo Saturn.Accredo Saturn only, Accredo Mercury holds stock at a single location.
Navigator > Setup > Inventory Control > Stock Locations
Setup Stock Locations including Branch, Department and delivery addresses. New Locations can be added, or existing Locations edited, inactivated or deleted.
If Branches and\or Departments mapped to IC Locations are changed, this can result in a re-grouping batch which will journal any previously transferred stock from the old Branch and Department for the location to the new. The Branch and Department are recorded in the ICQTY (IC Quantities)
table
to show the current branch and department recording stock in the GL.
Code
Enter a unique alpha numeric code of up to 8 characters.
Valid characters for new Location Codes are A-Z, 0-9 by default. Other characters to allow may be specified in
IC Settings Misc tab
.
Name
The Location name associated with the code.
Branch
A
Branch
code for the Location must be specified.
Dept
A
Department
code for the Location must be specified.
Delivery Address
The
delivery address
appears on Purchase Orders for the Location, and can be edited.
Deliver To
Allow deliveries for a Location, or
Purchase Orders
and
Receipts
will not be saved for the Location. You can clear the Deliver To and Sell From fields for Transit Locations (used in
Stock Transfers
).
Sell From
Selected,
allows sales from this Location.
Clear,
Sales Orders
,
Invoices or Credits
are not saved for the Location. You can clear the Deliver To and Sell From fields for Transit Locations (used in
Stock Transfers
).
Bin Tracked
Selected,
track products by Bin for this Location.
Coded Bins
must be selected in
IC Settings
and negative stock is not allowed for a tracked location (overrides the
Allow Negative Stock
setting).
When
Bin Tracked
is selected tracking data is updated, stock will initially be in the Bin specified for the
Product and Location
or the
0000
Unspecified bin. Bin Tracking cannot be selected if any
Quantity In Stock
for the location is negative.
Note: Bin tracking requires the Warehouse Management Extension in Subscription systems.
Clear,
Location is not bin tracked.
When
Bin Tracked
is cleared tracking data is cleared.
Count Type
Select the default type of Stocktake Count from:
Basic
- A simple stocktake with no Count options available. With this default type, the Enter Quantities option is available in the Navigator. Not available for
Bin Tracked
Locations.
Single
- One count will be done per Product and Location.
Additive
- Several counts can be done for each Product and Location. This includes support for
UOM
.
Detailed
- Counts include detail of Serial No, Lot No and Bin code for
Bin Tracked
locations.
Custom 1 & Custom2
Two custom fields are provided for scripting, custom reporting, or other purposes. Labels can be replaced in
IC Settings
.
Inactive
Set the selected location to Inactive. Maximum and Minimum Quantities will be set to zero.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Opens IC Location form view showing all visible fields in the customised grid, and additional fields not visible by default on the grid.
Insert
(F4)
You can insert additional Locations.
Delete
(F3)
Delete Locations, available if no other records refer to the Location code.
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

---

## IC Stock Transfers - Links tab

Source: https://accredo.co.nz/webhelp/ICStockTransfers_Links.htm

IC Stock Transfers - Links tab
Navigator > Tasks > Inventory Control > Enter Transfers >
Links tab

---

## IC Stock Transfers - Memos tab

Source: https://accredo.co.nz/webhelp/ICStockTransfers_Memos.htm

IC Stock Transfers - Memos tab
Navigator > Tasks > Inventory Control > Enter Transfers >
Memos tab

---

## IC Stocktake - Counts tab

Source: https://accredo.co.nz/webhelp/ICStocktakeForm_CountsTab.htm

IC Stocktake - Counts tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
> Counts tab - OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake > Counts tab
Lists all the Counts for the stocktake. Counts can be opened and edited without changing the stocktake.
See also
IC Stocktake - Products tab
.
Counts tab
Count
The ID number for the Count.
Details
Details for the Count.
Store Person
The Store Person associated with the Count.
Count Status
The status of the count, as
Confirmed
or
Unconfirmed
.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Add a new stocktake Count. Opens IC Stocktake Count.
Delete
(F3)
Delete the selected Count. Only available for Counts with
Status
of
Unconfirmed
.
Open
(F12)
Open to view and edit details in the IC Stocktake Count form.
Print Count Sheet
(Ctrl+P)
Print a Count Sheet for the selected Count row.
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
Mark as confirmed
(Alt+A)
Change the
Count Status
for the selected Count to
Confirmed
.
Find Count by Count ID
(Ctrl+F)
Find
a Count using the Count ID.
In This Section
IC Find Stocktake Count

---

## IC Stocktake - Links tab

Source: https://accredo.co.nz/webhelp/ICStocktake_Links.htm

IC Stocktake - Links tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Links tab
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake >
Links tab

---

## IC Stocktake - Memos tab

Source: https://accredo.co.nz/webhelp/ICStocktake_Memos.htm

IC Stocktake - Memos tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
>
Memos tab
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake >
Memos tab

---

## IC Stocktake - Products tab

Source: https://accredo.co.nz/webhelp/ICStocktakeForm_ProductsTab.htm

IC Stocktake - Products tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
> Products tab - OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake > Products tab
Lists all products in the Stocktake.
Period
The Period for the stocktake. Select from available periods.
Date
Date for the stocktake. The Date must be in the Period selected.
Details
Details for the stocktake.
Reference
Reference for the stocktake.
ID
Stocktake document ID.
Location
Location for the stocktake. (Accredo Saturn Only)
Post Status
The status of the Stocktake. You can change between
Counted
and
Uncounted
. If the Post Status is set to
Counted
, all lines must also be set to
Counted
. If the Stocktake has been posted, this will show
Posted
, and cannot be edited.
Count Type
The type of Count:
Single
- One count will be done per Product and Location.
Additive
- Several counts can be done for each Product and Location.
Detailed
- For tracked Products Serial No and/or Lot No detail must be included in the counts. For Bin tracked Locations Bin code must be included in the counts.  Tracking detail for the stocktake is generated when the stocktake is marked Counted.
Basic
- A simple stocktake with no Count options available.
Locations, Saturn Only.
Note:
Additive
and
Detailed
include support for
UOM
if enabled.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Enter edit mode.
Delete
(F3)
Sets the
Status
of the Stocktake to
Deleted
. Only available for stocktakes with
Status
of
Unposted
. You will need to confirm to delete, as this cannot be undone.
Print
(Ctrl+P)
Print the IC Stocktake Report. By default, only lists products with variances. You can select
Include Nil Variances
to include all products.
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
Generate Counts
(Alt+G)
Opens
IC Generate Counts
, to generate counts.
Print Count Sheets
(Alt+R)
Print count sheets for all counts. Opens
IC Count Sheets
.
Import Count
(Ctrl+I)
Opens
IC Import Count
, to import counts.
Reload Expected Quantities
(Alt+X)
Asks you to
confirm
, then if confirmed, expected quantities will be updated to match In Stock Quantities as at the end of the Stocktake period.
Note: This will load quantities as at the end of Stocktake Period, not as at the Stocktake Date.
This button is permission controlled, see
Users, Groups and Roles - Permissions tab
.
Insert Products
(Alt+N)
Add products to the stocktake. Opens
IC Insert Products
. Each Product can only be included in one Stocktake per Period, per Location (in Accredo Saturn). The Expected Quantity is loaded from the balance record when a product is added.
Delete Uncounted Products
(Alt+D)
Available when editing, removes all products that are not on any Count lines. You will be prompted to confirm.
Unpost
(Alt+U)
Available when the stocktake is within the available period window for IC. This contras the adjustment transactions and sets the stocktake and counts to
Unposted
.
Print Stocktake Sheet
Available for
Single
and
Additive
Stocktake
Count Types
. Print stocktake sheet. Opens
IC Stocktake
.
Print Log
View the
Print Log
(requires Read access Permission for Company > Settings).
Buttons
Uncounted / Counted
Changes the
Post Status
of the Stocktake from
Counted
to
Uncounted
or from
Uncounted
to
Counted
. When a stocktake is set as
Counted
, Variances are recorded. If you change a
Counted
stocktake to
Uncounted
, variances are removed.
All Products for the Stocktake must be included in a Count, and all Counts must be
Confirmed
before a Stocktake can be set to
Counted
.
Once
Counted
Tracking requirements for Posting are calculated for:
Lot tracked products
Serial Purchase tracked products
Bin Tracked locations < Saturn only.)
If variance is zero then tracking detail is assumed to be unchanged and not required. For
Detailed
Stocktakes full tracking is calculated, for other Stocktakes
tracking
must be specified where there is a variance.
Post
(Alt+T)
Post the stocktake. Only available if the stocktake
Status
is
Counted
. Posting a stocktake will post adjustments for all stocktake lines with variances, and updates product quantities, and move the Stocktake to History. Once posted, Stocktakes cannot be edited.
Save
(F9)
Saves changes to the Stocktake.
Cancel
(Esc)
Discards all changes.
Product Tab
Product Code
The Product Code.
Description
The Product Description.
Location
Location of the product. (Accredo Saturn Only)
UOM Code (
UOM
Active only)
UOM code for the Product.
Counted / UOM Quantity
The quantity counted.
Variance
The difference between the quantity Counted and the quantity expected.
Count Lines
The number of Counts the product is included in, for the Stocktake.
Line Status
Whether the product is
Counted
or
Uncounted
.
Expected
The Expected Quantity, calculated as Opening Stock plus Movement (posted transactions) for the Stocktake Period, at the time the stocktake was generated.
Closing Quantity
The closing stock quantity.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Delete
(F3)
Delete the selected Product from the Stocktake. Only available if the
Line Status
is
Uncounted
.
Open
(F12)
Open to view and edit Product details in the
IC Product
form.
Drill Down
(Shift+F12)
If the product has one Count Line, opens the
IC Stocktake Count
for the stocktake. If the product has more than one Count Line, opens a list of Count Lines for the Product that can be drilled down to the
IC Stocktake Count
form. You can also double-click to activate this. Not available in Edit mode.
Print Stocktake Lines
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
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Find
(Ctrl+F)
Find
a Product using the Product Code.
Totals Panel
Customise
Opens
Customise Fields
, you can customise the fields visible in the totals panel.
Total Weight
(UOM not active only)
The total weight of products in the stocktake.
Total Volume
(UOM not active only)
The total volume of products in the stocktake.
Quantity Over
The sum of the Quantity Variance greater than zero.
Quantity Under
The sum of the Quantity Variance less than zero.
In This Section
IC Stocktake - Counts tab
IC Stocktake - Links tab
IC Stocktake - Memos tab
IC Generate Counts
IC Print Stocktake Sheet
IC Count Sheets
IC Insert Products
Confirm Reload Expected Quantities

---

## IC Stocktake Count - Counts tab

Source: https://accredo.co.nz/webhelp/ICStocktakeCount.htm

IC Stocktake Count - Counts tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Edit Count >
Open
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
> Counts tab >
Insert
or
Open
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake > Counts tab >
Insert
or
Open
Use the Counts tab to enter quantities counted in a stocktake. When the count is complete, set the
Count Status
to
Confirmed
by clicking the
Confirmed
button.
Period
The Period for the stocktake. Select from available periods.
Date
Date for the stocktake. The Date must be in the Period selected.
ID
Stocktake document ID.
Location
Location for the stocktake.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Enter edit mode.
Insert
(F4)
Insert a new Count for the same Stocktake.
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
Delete Nil Lines
(Alt+D)
Available when editing, removes all products with nil Counts. You will be prompted to confirm. For Counts with
Single
count type, both the Counted and the Expected Quantity must be Nil, to be deleted.
This is useful when entering in an All Lines count.
Print Count Sheet
(Ctrl+P)
Prints a count sheet for the Count.
Copy Expected to Counted
(Alt+E)
Available for
Single
Stocktakes only.
Copies the
Expected Amount
to the Count for each Product.
Print Log
View the
Print Log
(requires Read access Permission for Company > Settings).
Counts Tab
Details
Optional description for the Stocktake Count.
Count ID
The Stocktake Count ID number.
Store Person
The Store Person associated with the Count.
Count Type
The type of count from the Stocktake:
Single
- One count will be done per Product and Location.
Additive
- Several counts can be done for each Product and Location.
Detailed
- Several counts can be done for each Product and Location. For
Lot No
tracked or
Serial No
Purchase
tracked products full detail by Lot No and Serial No must be included in the counts. For Bin tracked Locations full detail by Bin must be included in the counts. Tracking detail for the stocktake is generated from the detail when the stocktake is marked counted.
Locations, Saturn Only.
Note:
Additive
and
Detailed
include support for
UOM
if required.
Custom 1, Custom 2
Custom fields, for information only. You can change the labels for these fields in
IC Settings - Display Labels tab
.
Count Status
The status of the count, as
Counted
,
Uncounted
or
Posted
.
Grid Fields
Product code
The Product Code. Only Active Diminishing products are available.
Description
The Product Description.
UOM Code
(
UOM
Active Only)
The UOM Code for the Product.
When the
Count Type
is
Single
, this is the Base UOM Code. When the
Count Type
is
Additive
or
Detailed
, this defaults to the Base UOM Code but can be changed to an Other UOM Code.
UOM Quantity Counted (
UOM
Active Only)
The quantity of the product counted in the UOM Code specified. i.e. The Quantity Counted * UOM Multiplier.
Quantity Counted
The quantity of the product counted.
Bin Code
For
Counts
at a Bin tracked Location:
The Bin the count line is for, tracking adjustments will generate using this information when the Stocktake is marked
Counted.
(Saturn only)
For all other Counts:
The Bin code from the Product and Location record. Changes to the Bin code are written back to the record on Save.
Serial No
(Detailed Count type only)
Required for
Serial No
Purchase
tracked products, lines must have a Quantity Counted of 1. Tracking adjustments will generate using this information when the Stocktake is marked
Counted.
Lot No
(Detailed Count type only)
Required for
Lot No
tracked products. Tracking adjustments will generate using this information when the Stocktake is marked
Counted.
Lot Date /
Expiry Date
(Detailed Count type only)
Displayed for existing Lot No's, must be supplied if required for new Lot Nos.
Counted
Set true when a Quantity Counted is entered. Select to indicate Product counted and zero found as opposed to zero because not counted yet.
Stocktake Expected
The quantity expected in the stocktake.
Stocktake Variance
The difference between the quantity counted and the quantity expected for the Stocktake.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Add a new product to the Stocktake Count. Inserts a line in the grid.
Move
(Shift+Up) (Shift+ Down)
Move the selected line.
Delete
(F3)
Delete the selected line from the Count.
Print
(Ctrl+P)
Print a report of the information in the grid.
Sort List
(Ctrl+F2)
Select the sort criteria in
Sort - Contact
. The sort criteria will be retained on Save.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Find
(Ctrl+F)
Find
the next count line for a Product by entering or selecting the Product Code.
Stock Levels
Customise
Opens
Customise Fields
, you can customise the fields visible in the stock levels panel.
UOM Code
(
UOM
Active Only)
The UOM Code for the Product.
In Stk / UOM In Stk
Quantity of the selected product in stock on hand.
Alloc / UOM Alloc
Quantity of the selected product currently allocated to customers.
Avail / UOM Avail
Quantity of the selected product available for sale.
Buttons
View Stocktake
(Alt+V)
Open the parent
IC Stocktake
for the Count.
Confirm / Unconfirm
Toggles the
Count Status
of the Count between
Confirmed
and
Unconfirmed
.
Save
(F9)
Saves changes to the Stocktake Count.
Cancel
(Esc)
Discards all changes.
In This Section
IC Stocktake Count - Links tab
IC Stocktake Count - Memos tab
IC Find Product

---

## IC Stocktake Count - Links tab

Source: https://accredo.co.nz/webhelp/ICStocktakeCount_Links.htm

IC Stocktake Count - Links tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Count >
Open
>
Links tab
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
> Counts tab >
Insert
or
Open
>
Links tab
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake > Counts tab >
Insert
or
Open >
Links tab

---

## IC Stocktake Count - Memos tab

Source: https://accredo.co.nz/webhelp/ICStocktakeCount_Memos.htm

IC Stocktake Count - Memos tab
Navigator > Tasks > Inventory Control > Stocktake Processing > Enter Count >
Open
>
Memos tab
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Generate Stocktake >
Run
> Counts tab >
Insert
or
Open
>
Memos tab
- OR -
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List >
Open
Stocktake > Counts tab >
Insert
or
Open
>
Memos tab

---

## IC Stocktake Designer

Source: https://accredo.co.nz/webhelp/ICStocktakeDesigner.htm

IC Stocktake Designer
Navigator > Setup >Inventory Control > Stocktake Designer
You can design your own Stocktake Report, or open and modify an existing stocktake report design. To design a stocktake report quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
The IC Stocktake Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code.
Name
Iterators filter records that are shown in the report. Available Iterators are:
Lines
- Lines in the IC Stocktake.
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Stocktake Designer in addition to the standard
objects
are:
Product
Fields from the Product record.
Quantities
Details of product quantities.
StocktakeHead
Fields from the Stocktake Header record.
StocktakeLine
Fields from the Stocktake Line record.
A sample IC Stocktake is provided with the Accredo Server Install, and is also available on the Accredo website. The Sample IC Stocktake is:
ICBasicStocktake.pfd
- standard IC Stocktake.
To use documents downloaded from the website, ensure your document designer is the latest version.

---

## IC Stocktake Import

Source: https://accredo.co.nz/webhelp/ICStocktakeProcessing_Import.htm

IC Stocktake Import
Navigator > Tasks > Inventory Control > Stocktake Processing > Import Stocktake
For
Basic
Stocktakes only, selected in
IC Settings - Stocktake tab
.
You can import stocktake quantities from a file instead of entering them manually in
IC Enter Quantities
. This is useful when stocktaking has been done using a bar code scanner that generates an output file.
Location
Select the location of the stocktake. (Accredo Saturn Only)
Import Format
You can import stocktake quantities from a file, rather than keying them in manually via Enter Quantities. The format of the file can be:
Standard
- use with tab delimited or comma delimited (.csv) files. format is:
Product Code, Quantity
Standard
with Bin
- use with tab delimited or comma delimited (.csv) files. format is:
Product Code, Quantity, Bin Code
Opticon
- standard Opticon laser terminal format.
In all formats
Barcode
can be substituted for
Product Code
.
File Name
Select the file name and location of the import file.
Period
Select the period for the stocktake.
Run
(F9)
IC Stocktake Import will open. Select
report selections
for the report showing the results of the import.

---

## IC Stocktake List

Source: https://accredo.co.nz/webhelp/ICStocktakeList.htm

IC Stocktake List
Navigator > Tasks > Inventory Control > Stocktake Processing > Stocktake List
Selections
Location
Select from the
Lookup
.
Show All
(Ctrl+A)
shows all selected documents for all locations. Defaults to the User Default Location set in
User Settings
. (Accredo Saturn Only)
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
Current/History
Select the type of documents to be displayed, from:
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
The default value is set in
IC Settings Misc tab
.
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Stocktakes
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Stocktakes
(F9)
Click to apply selections, filters and sorts to the grid.
Grid Fields
Stocktake
The stocktake number.
Details
Details of the stocktake.
Status
The status of the stocktake, as
Uncounted
,
Counted,
Posted
or
Deleted
.
Period
The Period for the stocktake.
Document Date
The date that adjustment transactions will be posted for the Stocktake.
Count Type
The type of Count:
Single
- One count will be done per Product and Location.
Additive
- Several counts can be done for each Product and Location.
Detailed
- For tracked Products Serial No and/or Lot No detail must be included in the counts. For Bin tracked Locations Bin code must be included in the counts.  Tracking detail for the stocktake is generated when the stocktake is marked Counted.
Basic
- A simple stocktake with no Count options available.
Locations, Saturn Only.
Note:
Additive
and
Detailed
include support for
UOM
if enabled.
Reference
The reference applied to the stocktake.
Location Name
The name of the stocktake location. Defaults to the User Location, if set, or
blank
otherwise. (Accredo Saturn Only)
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Choose from:
Generate Stocktake
- Generates a new Stocktake. Opens
IC Generate Stocktake
.
Insert Stocktake
- Creates a Stocktake with no products. This is useful for stocktakes done progressively with counts imported. Opens
IC Stocktake
.
This is only available for Locations where the
Stocktake Count Type
is not
Basic
. (in Accredo Saturn) This is not available when the default
Stocktake Count Type
is
Basic
.
Delete
(F3)
Sets the
Status
of the Stocktake to
Deleted
. Only available for stocktakes with
Status
of
Unposted
. You will need to confirm to delete, as this cannot be undone.
Open
(F12)
Open to view and edit details in the
IC Stocktake
form.
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
Create List View
(Alt+L)
Save the current list state as a
List View
.
Find
(Ctrl+F)
Find
a stocktake using the Stocktake ID.
Post Selected
(Alt+T)
Post the selected stocktake.
Post all up to current period
(Alt+A)
Post all stocktakes up to the current period.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.
Buttons
Stocktake
(Alt+S)
Find
a Stocktake by entering the Count ID of a Count contained in the Stocktake.
In This Section
IC Find Stocktake
IC Find Stocktake ID
See Also
IC Stocktake Processing

---

## IC Stocktake Processing

Source: https://accredo.co.nz/webhelp/ICStocktakeProcessing.htm

IC Stocktake Processing
Navigator > Tasks > Inventory Control > Stocktake Processing
You can:
Generate a new stocktake document.
Print blank stocktaking forms.
Enter physical stocktake figures.
Print a report of calculated stocktake variances.
Import stocktake figures.
Update stocktake variance figures to in stock figures.
Options available depend on the selected Stocktake Count Type in
IC Settings - Stocktake tab
.
Options available depend on the selected Stocktake Count Types for your in Stock Locations. In Accredo Saturn.
Basic
Count
Enter Basic Count
Import Stocktake
Single
Count
Enter Single Count
Single
,
Additive
or
Detailed
Counts
Generate Stocktake
IC Insert Count
Import Count
Edit Count
In This Section
IC Stocktake List
IC Generate Stocktake
IC Stocktake - Products tab
IC Stocktake Count - Counts tab
IC Basic Count
IC Single Count
IC Insert Count
IC Import Count
IC Edit Count
IC Stocktake Import

---

## IC Stocktake Reports - Add Layout

Source: https://accredo.co.nz/webhelp/ICStocktakeReports.htm

IC Stocktake Reports - Add Layout
Navigator > Reports > Inventory Control > Stocktake Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Stocktake Forms
Print a report listing products with space to enter stocktake quantities on the printed report. You can customise the report to sort it by Bin Code. Supplier fields on the Report band are populated from the default Supplier (
Creditor Code
on the
IC Product tab
) if one is specified.
Stocktake Status
Report on all available Stocktakes. Shows the status and amounts of all products in the Stocktake for the selected period and optionally per location (in Accredo Saturn).

---

## IC Store Persons

Source: https://accredo.co.nz/webhelp/ICStorePersons.htm

IC Store Persons
Navigator > Maintain > Inventory Control > Store Persons
Store Persons can be used for picking and tracking and can be set in IC Counts.
Code
A unique code to identify the Store Person.
Store Person Name
Name of the Store Person.
Role
Job title of the Store Person. This can be included in reports and documents.
Phone Nos
Store person telephone numbers. If Accredo is setup to interface with the
telephone system
, click
to dial.
Note: You can change the labels of the phone no fields in
Company Settings - Display Labels
.
Email Address
The Store Person email address. Click
to create a
Mail Message
(Ctrl+M).
Comment
A 30 character field for reference.
Inactive
You can make a Store Person inactive.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
Access grid fields in Form view for each line on the grid. Store Person can be entered or edited in the form or on the grid. To view more fields use the scroll buttons or resize the window.
Insert
(F4)
Allows new records to be inserted and gives access to the
Code
field. Codes entered will sort alphabetically (or as specified if a sort has been added).
Delete
(F3)
If transactions exist for the record, delete will not be available.
Customise
(Alt+F5)
Opens
Customise Fields
, select the fields to be visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Add / Remove as Company Contact
(Alt+P)
Add or remove the Store Person as a
Company Contact
.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Supplier Cost Update

Source: https://accredo.co.nz/webhelp/ICSupplierCostUpdate_Selections.htm

IC Supplier Cost Update
Navigator > Tasks > Inventory Control > Update Prices > Supplier Cost Update
Update supplier costs by a percentage or fixed amount, also revalue the base currency Supplier Cost at a given exchange rate.
Creditor
Select the Creditor (Supplier) to update costs for.
Currency
The currency of the Creditor, read-only.
Rate Type
Defaults to the Rate Type for Purchases, read-only if currency is Base.
Date
Will default to the end date of the current IC period, required.
Exchange Rate
If
Use Exchange Rate Table
is selected from
FX Settings
, the rate is fetched from the Exchange Rates Table based on Currency Code, Rate Type and Date.
Product From/To
Stock Group
Restriction on Products to update, optional.
Update Method
Choose between Percentage, Amount and Revaluation.
If
Revaluation
, the Supplier Cost Base will be reconverted from Supplier Cost at the Exchange Rate.
Update By
If you selected the Percentage method, type the percentage here; if you selected the Amount method, type the amount. This will update the prices selected in the
Cost Prices to Update
fields by the amount or percentage entered.
If you selected Revaluation, this will be read-only.
Update Type
Select from:
Query Run -
(default), new prices for each Product will be shown in bold in a query window before updating. You will have the choice for each Product to edit, update or cancel.
Report Only -
report the effect of applying the selections made in the Price Update without actually changing the prices.
If report destination is
Screen
select
Regenerate
from the Report Preview to return to the selection form with all selections retained.
Automatic -
proceed with the price update based on the selections.
Cost Prices to Update
Select the prices to update. If you selected
Update Method
Revaluation
, only Supplier Cost Base is checked. If the
Supplier Standard Cost
is Selected, the
Supplier Standard Cost Date
will also be updated.
Include Inactive
Selected
, include inactive products in the update.
Run
(F9)
Reprice and show the results.

---

## IC Tracking Reports - Add Layout

Source: https://accredo.co.nz/webhelp/ICTrackingReports.htm

IC Tracking Reports - Add Layout
Navigator > Reports > Inventory Control > Tracking Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Bin by Product Tracking
For bin tracked locations only. Report by Bin the Products and quantities which are held in the bin. (Accredo Saturn only)
Product by Bin Tracking
For bin tracked locations only. Report by Product the Bins in which stock is located and the quantities per bin. (Accredo Saturn only)
Product Tracking
Report quantities for tracked products by Lot No and / or Serial No.  For bin tracked locations may optionally include bin detail. (in Accredo Saturn)
Tracked Serial not Specified
Report quantities for Serial Tracked products where Serial No's have not been specified.
Serial Tracked
Sale
this will be all in stock quantities and quantities are expected.
Serial Tracked
Purchase
will only report quantities where serial numbers have not (yet) been specified e.g. when tracking has been turned on for a product but a specifying adjustment or detailed stocktake has not been performed yet.
Tracking Transaction Detail
Report tracking detail for a selected Product. This is the same information which can be queried under the
Product Tracking Query
.

---

## IC Transaction List

Source: https://accredo.co.nz/webhelp/ICTransactionList.htm

IC Transaction List
Navigator > Maintain > Inventory Control > Transaction List
View and open IC Transactions over a range of Products and Periods.
Click
Lookup
(F2)
buttons to make selections and use the
lookup
.
Click
to apply filters to selections.
Selections
Product
Limit transactions displayed to a selected Product. Clear the selection to display transactions for all Products.
Selection
Select a period to view transactions for:
Period
- Select a single period in the
From
selection. Defaults to Current Period.
Last Period
-  the period prior to the Current Period.
Year
- Transactions for the current financial year.
Last Year
- Transactions for the previous financial year.
Full Year
- Transactions for the year preceding the Current Period.
All Periods
- All transactions.
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
Date From
Date To
Date range updates automatically for the period range selected but may be limited further within that range.
Transactions
Select the types of transactions to display from:
Issue
Credit
Receipt
Adjustment
Transfer
(Saturn only)
Usage
Manufacture
Click
Select All
(
Shift+F4
) to select all Types.
Click
Unselect All
(
Shift+F3
) to clear all Types.
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Transactions
to apply selections, filters and sorts to the list.
The default value is set in
IC Settings Misc tab
.
Select Transactions
(F9)
Click to apply selections, filters and sorts to the list.
Default ordering is by Period and Transaction ID.
Grid toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a transaction.
Open
(F12)
View the details for the transaction.
Drill down
(Shift+F12)
View the source document. You can also double-click a line to drill down to source or open the transaction if drill down is not available.
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
Find a transaction using the Transaction ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Footer
Record Count
The total number of records shown in the list. Click
to refresh the total number.

---

## IC Transaction Reports - Add Layout

Source: https://accredo.co.nz/webhelp/ICTransactionReports.htm

IC Transaction Reports - Add Layout
Navigator > Reports > Inventory Control > Transaction Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Cross Branch Sales
Reports on Issue and Credit transactions where the product has been sourced from a location belonging to a different branch than the Sales invoice or credit. (Accredo Saturn Only)
Pending Stock Motion
Reports on pending stock movements by class, up to a selected period. Pending stock movements represent unposted IC transactions on documents and batches in other modules. See also
IC Products - Quantity tab
.
Product Sequence
Sorts and groups transactions by product. Select a range of Product codes and select Period, Current year, All periods or a Range of periods. A
Filter & Sort
can be added to both the Product band and to the Transactions band within each product. The report shows an opening balance, transactions for the selected period and a running stock balance. Only products with an opening balance or transactions within the periods selected are shown. Supplier fields on the Report band are populated from the default Supplier (
Creditor Code
on the
IC Product tab
) if one is specified.
Transaction Links
This report shows the links associated with IC transactions for a range of periods.
Transaction Sequence
Print a list of transactions. Select Period, Current Year, All Periods or a Range of Periods. The report lists transactions within the period they were posted.
Untransferred Transactions
Produces a report of transactions that have not been transferred to the General Ledger.

---

## IC Transactions

Source: https://accredo.co.nz/webhelp/ICTransactions.htm

IC Transactions
Navigator > Tasks > Inventory Control > Enter Transactions
You can enter transactions in IC and view and edit them if they are opened from a
transaction list
grid. Edit is available for transactions entered via the transaction form which have not been transferred to the GL.
You can enter:
Adjustments to stock levels.
And if enabled for IC sourced entry in
IC Settings
:
Stock Issues (Sales) - usually posted from IN Invoices.
Stock Credits (Stock Returns) - usually posted from IN Credits.
Stock Receipts (Goods Inwards) -  usually posted from AP Shipments.
Transaction tab
See
Issue / Credit
,
Receipt
or
Adjustment
transactions for a list of fields for each transaction type on the Transaction tab.
Tracking Tab
The
tracking
detail for the transaction.
Toolbar
Select a Transaction type from the drop-down. The window changes to reflect the data required for that transaction type. The additional toolbar options are:
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Click to edit the saved transaction, see below.
Insert
(F4)
Click to show the drop down menu again and add another transaction.
Duplicate
(Shift+F4)
Duplicate the new transaction defaults to the System Date and System Period.
Duplicate Contra
, reverses the original transaction. The original date and period are retained if they are available for processing, otherwise the System Date and System Period are used to duplicate the transaction.
Drill down
(Shift+F12)
View the source document (only if the transaction is sourced from another document, for example, a Purchase Order).
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
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Buttons
Save
(F9)
Completes the transaction, updates the product. If a message appears stating that the record is locked, edit in the other window. If the message "
Locked - Retrying
" appears, another User has a required record locked. You can wait for the User to finish (Accredo will save when it is able to gain access) or click
Cancel.
Cancel
(Esc)
Cancels the transaction entry.
Editing Transactions
Transactions entered in IC that have not be transferred to the General Ledger can be edited immediately.
Note: The Cost Value Exclusive, showing the effect on Stock Valuation, is recorded in the ICTRAN (IC Transactions)
table
. For Issues and Credits, Cost Of Sales Exclusive, showing the effect on Sales Value, is also recorded in ICTRAN. For IN sourced Usage transactions there is no Cost Of Sales, as the stock movement occurs with the usage.
In This Section
IC Transactions - Issue/Credit
IC Transactions - Receipt
IC Transactions - Adjustment
IC Transactions - Links tab
IC Transactions - Memos tab

---

## IC Transactions - Adjustment

Source: https://accredo.co.nz/webhelp/ICTransactionsAdjustment.htm

IC Transactions - Adjustment
Navigator > Tasks > Inventory Control > Enter Transactions
See also
IC Enter Transactions
.
You can adjust stock levels to reflect stock shrinkage. Updating from a
Stocktake
generates appropriate adjustment transactions. See also
Batch Adjustments
for entering adjustments in a batch.
Transaction tab
Product Code
The product this transaction affects.
Location
The location to be updated for the transaction. (Accredo Saturn Only)
Branch Department
Available for
Perpetual Integration
only, read-only for
Periodic Integration
.These fields are default from the Location. (Accredo Saturn Only)
Date
The date of the transaction (default, the date of the previous transaction), or the System Date. It can be changed but must be within the date range for the period selected.
Reference
By default, the transaction reference number is retained over a series of transactions.
Source Type
For transactions posted from Documents or Batches the source type for the transaction.
Unit /
UOM Code
If
UOM
is not active, the Product Unit is shown.
If
UOM
is Active, you can select from UOM Codes available for the product.
Quantity
The quantity of items. This should be a positive figure unless you are reversing a previous transaction or correcting an error. For adjustments, a positive number increases and a negative number decreases the quantity in stock.
If
UOM
is active, this is the quantity in the selected UOM. The quantity in the Base UOM is shown, calculated as the
UOM Quantity * UOM Multiplier
.
Serial No
For
Serial No
Purchase
tracked products if the quantity is 1 or -1 the Serial No may be entered, for other quantities enter Serial Nos in the Tracking tab.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
UOM Multiplier
(
UOM
Active Only)
The multiplier of the selected UOM Code. Read-only.
Cost Price
The cost price of the product.
If
UOM
is active, this is the Cost Price of the product in the selected UOM. The cost price in the Base UOM is also shown.
Cost Value
The cost value is calculated as the product of the Cost Price (standard, average or latest depending on the stock valuation basis) and the quantity entered. If the Cost Prices are GST inclusive, GST is first deducted, that is, the cost value is GST exclusive.
GL Account
Account Name
Available for
Perpetual Integration
only and requires IC > Transactions > GL Account permission.
The GL Account for the transaction. If no Account is entered, the GL Adjustment Account of the Stock Group will be used.
Quantities
Information only. The fields are the same as those on the Quantity tab of IC Products. The In Stock and Available quantities will update when the transaction is posted. The values shown are for the selected location (in Accredo Saturn).
Tracking Tab
The
tracking
detail for the transaction.
Effect of the transaction
The Adjustments Quantity and Quantity in Stock (and Available) are increased by the quantity entered. Quantity in Stock is reduced by prefixing a minus sign to the quantity. Adjustments have no effect on sales, cost of sales or gross margins.

---

## IC Transactions - Issue/Credit

Source: https://accredo.co.nz/webhelp/ICTransactionsIssue.htm

IC Transactions - Issue/Credit
Navigator > Tasks > Inventory Control > Enter Transactions > Issue / Credit
You can enter issues and credits relating to inventory. Issues and credits can be entered when
Allow IC Sourced Issues and Credits
is
Selected
is selected in
IC Settings
, if IN is installed use IN Invoices and Credits for Issues and Credits.
See also
IC Enter Transactions
.
Transaction tab
Product Code
The product this transaction affects.
Location
The location to be updated for the transaction.
If Issue (Sale) or Credit is
selected
, and the Sell From option in IC Stock Location is
clear
for a location, that location will not be available. (Accredo Saturn Only)
Branch Department
These fields are read-only as they are determined from the Location. (Accredo Saturn Only)
Date
The date of the transaction (default, the date of the previous transaction), or the System Date. It can be changed but must be within the date range for the period selected.
Reference
For example the invoice (or credit note) number for an issue or credit. By default, the transaction reference number is retained over a session of transactions.
Source Type
For transactions posted from Documents or Batches the source type for the transaction.
Unit /
UOM Code
If
UOM
is not active, the Product Unit is shown.
If
UOM
is Active, you can select from UOM Codes available for the product.
Quantity
The quantity of items. This should be a positive figure unless you are reversing a previous transaction or correcting an error.
If
UOM
is active, this is the quantity in the selected UOM. The quantity in the Base UOM is shown, calculated as the
UOM Quantity * UOM Multiplier
.
Serial No
For
Serial No
tracked products if the quantity is 1 or -1 the Serial No may be entered, for other quantities enter Serial Nos in the Tracking tab.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
UOM Multiplier
(
UOM
Active Only)
The multiplier of the selected UOM Code. Read-only.
Cost Price
The cost price of the product.
If
UOM
is active, this is the Cost Price of the product in the selected UOM. The cost price in the Base UOM is also shown.
Cost Value
The cost value is calculated as the product of the Cost Price (standard, average or latest depending on the stock valuation basis) and the quantity entered. If the Cost Prices are GST inclusive, GST is first deducted, that is, the cost value is GST exclusive.
Price Code
The default Price code from Company Price Lists is used, (can be changed).
Selling Price
The Selling Price for the Price code specified. The Selling Price can be changed by editing this.
If
UOM
is active, this is the Selling Price in the selected UOM. The Selling Price in the Base UOM is also shown.
Sales Value
The sales value is the Selling Price selected multiplied by the quantity. If the Selling Price is GST inclusive, GST is first deducted, that is, the sales value GST exclusive.
Customer Code
The customer code for the transaction.
Order No
The customer Order Number for the Transaction.
Quantities
Information only. The fields are the same as those on the Quantity tab of IC Products. The In Stock and Available quantities will update when the transaction is posted. The values shown are for the selected location (in Accredo Saturn).
Tracking Tab
The
tracking
detail for the transaction.
Effect of Transactions
Increases Sales Quantity and reduces the Quantity in Stock (and available) by the quantity entered. The value sold is increased by the sales value, and the cost of sales is increased by the cost value. The gross margin and last sale date are also updated.
A credit transaction is the reverse of an issue transaction, the sales quantity is decreased by the quantity entered, and Quantity in Stock (and Available) are increased. Value sold and cost of sales are also decreased in accordance with the sales value and cost value respectively. The gross margin is also updated. Last sale date is not affected.
If you use IN to generate sales invoices, the options for issues and credits will rarely be used. If analysis of sales, such as by Sales Groups is required, then sales must be entered through IN.

---

## IC Transactions - Links tab

Source: https://accredo.co.nz/webhelp/ICTransactions_Links.htm

IC Transactions - Links tab
Navigator > Tasks > Inventory Control > Enter Transactions >
Links tab

---

## IC Transactions - Memos tab

Source: https://accredo.co.nz/webhelp/ICTransactions_Memos.htm

IC Transactions - Memos tab
Navigator > Tasks > Inventory Control > Enter Transactions >
Memos tab

---

## IC Transactions - Receipt

Source: https://accredo.co.nz/webhelp/ICTransactionsReceipt.htm

IC Transactions - Receipt
Navigator > Tasks > Inventory Control > Enter Transactions > Receipt
You can enter receipts relating to inventory. Receipts can be entered when
Allow IC Sourced Receipts
is
Selected
in
IC Settings
, if AP is installed use
AP Shipments
for Receipting.
See
IC Enter Transactions
.
Transaction tab
Product Code
The product this transaction affects.
Location
The location to be updated for the transaction.
If Receipt is
selected
, and the Deliver To option in
IC Stock Location
is
clear
for a location, that location will not be available. (Accredo Saturn Only)
Branch Department
These fields are read-only as they are determined from the Location. (Accredo Saturn Only)
Date
The date of the transaction (default, the date of the previous transaction), or the System Date. It can be changed but must be within the date range for the period selected.
Reference
For example the packing slip number for a receipt. By default, the transaction reference number is retained over a series of transactions.
Source Type
For transactions posted from Documents or Batches the source type for the transaction.
Unit /
UOM Code
If
UOM
is not active, the Product Unit is shown.
If
UOM
is Active, you can select from UOM Codes available for the product.
Quantity
The quantity of items. This should be a positive figure unless you are reversing a previous transaction or correcting an error. For adjustments, a positive number increases and a negative number decreases the quantity in stock.
If
UOM
is active, this is the quantity in the selected UOM. The quantity in the Base UOM is shown, calculated as the
UOM Quantity * UOM Multiplier
.
Serial No
For
Serial No
Purchase
tracked products if the quantity is 1 or -1 the Serial No may be entered, for other quantities enter Serial Nos in the Tracking tab.
For other Products the field is not available except where Allow Serial No on Non-Serial Lines has been selected in
Company Settings
.
UOM Multiplier
(
UOM
Active Only)
The multiplier of the selected UOM Code. Read-only.
Cost Price
The cost price of the product.
If
UOM
is active, this is the Cost Price of the product in the selected UOM. The cost price in the Base UOM is also shown.
This defaults to the Latest Cost in the Product file. If the Latest Price is zero, it defaults to the Valuation Cost. This can be amended to reflect a new Cost Price.
Cost Value
The cost value is calculated as the product of the Cost Price (standard, average or latest depending on the stock valuation basis) and the quantity entered. If the Cost Prices are GST inclusive, GST is first deducted, that is, the cost value is GST exclusive.
Creditor Code
The Creditor code for the transaction.
Order No
The Order No for the transaction.
Quantities
Information only. The fields are the same as those on the Quantity tab of IC Products. The In Stock and Available quantities will update when the transaction is posted. The values shown are for the selected location (in Accredo Saturn).
Selling Prices
These are read-only fields showing Selling Prices from
IC Products - Product tab
.
Tracking Tab
The
tracking
detail for the transaction.
Effect of the transaction
The receipts month and year to date and the Quantity in Stock (and Available) are increased by the quantity entered. The latest cost is updated with the value entered. A new weighted average cost is calculated on the basis of the previous average cost, quantity in stock, the quantity received and the new Cost Price. If the previous quantity in stock was zero (or less) the average cost will be set to the latest cost. If you have AP and use Shipments, the option for Receipts will rarely be used.
Hint: To enter goods returned to a supplier you can enter a negative receipt - enter the receipt with a negative quantity.

---

## IC Transfer Designer

Source: https://accredo.co.nz/webhelp/ICTransferDesigner.htm

IC Transfer Designer
Transfers and the Transfer Designer are available for Accredo Saturn only.
Navigator > Setup > Inventory Control > Transfer Designer
A transfer document can be included with transferred items to allow easy checking of quantities and other details. You can design your own transfer documents or open and modify an existing transfer document design. To design a transfer document quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
The IC Transfer Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Usually a transfer document consists of:
Header band
showing details of the source, in-transit and / or destination locations,
Repeating Detail band
showing product codes, descriptions, quantities sent and received, and
Footer band
with space for a signature and date.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code.
Name
Iterators filter records the shown in the report. Available Iterators are:
Lines
- Lines on the IC Transfer
Outwards Tracking
- iterates through the tracking detail for the transfer line and source location
Inwards Tracking
- iterates through the tracking detail for the transfer line and destination location
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Transfer designer in addition to the standard
objects
are:
DestinationLocation
Fields from the Destination Location in the transfer header.
itLines
Properties from the Lines iterator.
Product
Fields from the Product (for the Product on the line).
SourceLocation
Fields from the Source Location in the transfer header.
TransferHead
Fields from the transfer header.
TransferLine
Fields from the transfer line.
TransitLocation
Fields from the Transit Location in the transfer header.
A sample IC Transfer is provided with the Accredo Server Install, and is also available on the Accredo website. The sample IC Transfer is:
ICTransfer.pfd
- standard IC Transfer
To use documents downloaded from the website, ensure your document designer is the latest version.
In This Section
IC Report Period

---

## IC Transfer List

Source: https://accredo.co.nz/webhelp/ICTransferList.htm

IC Transfer List
Accredo Mercury holds stock at a single location. Stock transfers between locations are only available for Accredo Saturn.
Navigator > Maintain > Inventory Control > Transfer List
Access transfer documents for viewing and processing. The Outward grid shows Transfer transactions based on the
Source Location
. The Inward grid shows Transfer transactions based on the
Destination Location
. Select the period, the type of transfer documents, and different locations while retaining selections.
Selections
Current/History
Select the type of documents to be displayed, from:
Current
History
Both Current and History
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Transfers
to apply selections, filters and sorts to the list.
Display Deleted
Selected,
deleted documents are shown in
History
.
Clear,
(default) deleted documents are not shown.
The default value is set in
IC Settings Misc tab
.
Select Transfers
(F9)
Click to apply selections, filters and sorts to the list.
Outward / Inward
Source / Destination Location
Select from the
Lookup
.
Show All
(Ctrl+A)
shows all selected documents for all locations. Defaults to the User Default Location set in
User Settings
.
Period
Select the period to view documents for.
Period
Documents entered in the selected Period only are shown.
Year
Documents for the current year are shown.
All Periods
All documents are shown.
Range of Periods
Select a range of periods to appear in the From and To Lookups.
You can select different locations while retaining the above selection.
Store Person
You can filter the list by selecting a Store Person.
Grid Toolbars
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new transfer, see
IC Enter Stock Transfers
.
Delete
(F3)
Delete the Transfer document. Only unposted transfers can be deleted. Delete is not available for transfer documents where dispatch or Receipt transactions have been posted.
Open Details
(F12)
Opens
IC Enter Stock Transfers
to view transfer details. Transfers can be edited and posted. Incomplete and historic transfers can be viewed.
Print
(Ctrl+P)
Print the Transfer List, or save as an Excel worksheet, or PDF file to send.
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
See Also
Inventory Control - Maintain

---

## IC Transfer Reports - Add Layout

Source: https://accredo.co.nz/webhelp/ICTransferReports.htm

IC Transfer Reports - Add Layout
Transfers are only available in Accredo Saturn.
Navigator > Reports > Inventory Control > Transfer Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Transfer
Lists transfer header and line information. You can specify locations and the dispatch and receipt statuses. The
Current/ History
selection is to allow optimised scanning of the transfer files. A transfer is current if it is not deleted and is unposted. A transfer is historic if it is deleted or posted. You can specify the period or a range of periods from which to select transfers.
Transfer Links
This report shows the links associated with IC transfers for a range of periods.

---

## IC Transfer to GL

Source: https://accredo.co.nz/webhelp/ICTransferToGeneralLedger.htm

IC Transfer to GL
Navigator > Tasks > Inventory Control > Transfer to GL
Transfer summary or detailed journals through to the GL. This will generate Transaction Batches for the GL to allow you to easily keep the GL up to date. You are asked for the latest period to transfer up to. Batches are created for the specified period and all prior periods where there has been transaction activity that affects the GL. You can only select periods up to the latest period available for processing. Batches created can be
Summarised
or
Detailed
as specified in the
Integrate to General Ledger
option in
IC Settings
.
The
Revalue Stock on Hand
option also creates a GL Batch for the Current Period for any change to Stock value which is not directly due to a transaction.
Summarised
The batch created will Debit the stock on hand account in the balance sheet and Credit the closing stock account in the trading account with the increase in stock value since the last transfer. Separate lines in the batch are created for each Transaction Type for each Product by Branch and Department. If the stock value has decreased, the stock on hand account will be credited and the closing stock account debited.
Detailed
The batch created will have separate entries for each transaction entered in IC, that is, for each transaction it Debits and Credits the relevant stock on hand and closing stock accounts.
The GL Accounts are specified for each
Stock Group
despite Summarised or Detailed being selected. The transfer also checks if a GL Account has changed since last transfer and if so, journals
ClosingStock
and
StockOnHand
between the appropriate accounts. This batch is created in the Current Period (even if transfer is not up to Current Period) - this is considered the most likely assumption as to when the GL Accounts changed. You can do this many times, it will always transfer up to at least the period specified the previous time.

---

## IC Units of Measure

Source: https://accredo.co.nz/webhelp/ICUnitsOfMeasure.htm

IC Units of Measure
Navigator > Setup > Inventory Control > Units of Measure
Setup Units of Measure (UOM) for Inventory Control. This allows you to enter products in convenient units (such as boxes or packs) and have the system do the conversion work. When UOM Status is Active, UOM can be used for products.
The code
EA
(Each) is included by default in new companies.
UOM Status
Determines whether UOM is used.
None
, all UOM fields and options other than this form are unavailable.
Pending
, UOM Tab is available so UOMs can be set up and validated. A
Default UOM
Code is required.
Active
, UOM is available for all documents and transactions.
Warning: If you turn off UOM (that is, change UOM from
Active
to
None
), you will be prompted to back up your data, as UOM Codes will be removed from all affected products, documents and transactions. If you experience power or other failure during processing, restore the backup and turn off UOM again.
UOM Required
Selected
, a Base UOM is required for all products.
Use Strict UOM Quantities
Clear
, the constraint tying UOM to Base decimals is relaxed. This means rounding may occur, as the
UOM Quantity * UOM Multiplier = BaseQuantity (rounded)
will no long have to be able to return exactly the original UOM Quantity for
BaseQuantity / UOM Multiplier
.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit the Units of Measure.
Insert
(F4)
Insert additional UOM.
Delete
(F3)
Delete UOM, available if no other records refer to the UOM.
Print
(Ctrl+P)
Print a report of the information in the grid. See
Report Selections Form
.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
UOM Code Usage Query
(Ctrl+Q)
Product Query
- Displays the Products using the selected UOM. See
IC Product Usage for UOM Code
.
Pending Transaction Query
- Displays Pending Transactions using the selected UOM. See
IC Pending Usage for UOM Code
.
Set as default
Sets / Unsets the selected UOM as the
Default UOM applied
when new
Stock Groups
are added. Toggle the
Set As Default
button to turn the default UOM on and off.
If set the
Default UOM
is shown in bold. The
Default UOM
must have a Fixed Multiplier of 1.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Fields
Code
A unique code of up to 8 characters that can include both letters and digits.
Name
The UOM name associated with the code.
Description
Description of the Unit of Measure.
Group Code
The type of Unit of Measure. See
IC UOM Groups
.
Decimals
The number of decimal places allowed for the UOM.
The
Decimals
plus the number of decimal places in the
Multiplier
cannot be greater than the
Base UOM
Decimals
. This is so that quantities calculated as
UOM Quantity * UOM Multiplier
can always be expressed in Base UOM decimals without rounding.
Multiplier
When used as an
Other UOM
the value to multiply the
Base UOM
by.
Leave empty for a variable
Multiplier
which is specified in the Other UOM on a Product.
e.g. With a
Base UOM
for a Group
TIME
of
HOUR
; the multiplier for the UOM
DAY
may then be
8
(hours).
When used as
Base UOM
the
Multiplier
is set to
1
in the
Product UOM
regardless of the
Multiplier
specified here.
If
Use Strict UOM Quantities
is
Selected
then the number of decimal places in the
Multiplier
plus the
Decimals
cannot be greater than the
Base UOM
Decimals
. This is so that quantities calculated as
UOM Quantity * UOM Multiplier
can always be expressed in Base UOM decimals without rounding.
Base
Selected
, the UOM may be used as a
Base UOM
.
Unselected
, the UOM may not be used as a
Base UOM
.
Defaults to
Selected
when a
UOM
Multiplier
is set to
1.
May be selected for UOM codes with any multiplier or none.
Multiplier
will automatically set to
1
when used as
Base UOM
for a Product.
Fixed Multiplier
Selected
, the
Multiplier
is fixed and cannot be changed for
Other UOM
on a Product.
Unselected
, the
Multiplier
is variable and  will be set per Product for
Other UOM
.
This is calculated and read-only. When a
Multiplier
is set,
Fixed Multiplier
is set to
Selected
. To have a variable multiplier, leave the
Multiplier
field
blank
.
Add'l Weight
Additional weight for the UOM. For example, a
PALLET
UOM may have its own weight, to be added to the product weight. Additional Weight must be expressed in the Base UOM for Group
WEIGHT
.
Add'l Volume
Additional volume for the UOM. For example, a
BOX
UOM may have its own volume, to be added to the product volume. Additional volume must be expressed in the Base UOM for Group
VOLUME
.
Inactive
Select this or press the
Space Bar
while in the field. Lines for inactive UOM Groups are shown in grey. Inactive UOMs cannot be selected, and will not appear in the UOM selections for products.
Buttons
Save
(F9)
Save changes.
Cancel
(Esc)
Discard changes and close the form.
Note: UOM is a data entry convenience, and does not recognise the configuration of stock held. It recognises the quantity of stock in the base UOM, and performs calculations from this. For example, if you have 3m of timber in stock, UOM does not recognise if this is three separate 1m lengths, or one 3m length. You can set up separate IC Products to represent different configurations.
In This Section
IC Product Usage for UOM
IC Pending Usage for UOM

---

## IC UOM Groups

Source: https://accredo.co.nz/webhelp/ICUOMGroups.htm

IC UOM Groups
Navigator > Setup > Inventory Control > UOM Groups
Setup groups of Units of Measure (UOM). UOM Groups are used to categorise similar types of UOM, for example days and hours would both be categorised as Time.
Code
A unique code of up to 8 characters that can include both letters and digits.
Name
The UOM group name associated with the code.
Inactive
Select this or press the
Space Bar
while in the field. Lines for inactive UOM Groups are shown in grey. Inactive UOM Groups cannot be selected, and will not appear in the UOM screen.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert additional UOM Groups.
Delete
Delete UOM Groups, available if no other records refer to the UOM Group.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
Reloads changes other Users may have made.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## IC Update Prices

Source: https://accredo.co.nz/webhelp/ICUpdatePrices.htm

IC Update Prices
Navigator > Tasks > Inventory Control > Update Prices
Update Product Pricing in bulk.
Supplier Cost Update
Reprice from Components
Global Price Update
Price List Copy
Prices can also be imported using
Price Book Import
or
Data Interchange
.
In This Section
IC Supplier Cost Update
IC Reprice from Components
IC Global Price Update
IC Price Update Query
IC Price List Copy

---

## Inventory Control

Source: https://accredo.co.nz/webhelp/InventoryControl.htm

Inventory Control
The Inventory Control (IC) module lets you manage products and stock levels.
IC can be operated stand alone to keep track of stock levels, or can be integrated with Accounts Receivable (AR) via Invoicing System (IN) and optionally Order Entry (OE) to form a sales invoicing system for sales analysis. Usually sales are entered in IN and stock receipts are entered in Accounts Payable (AP). Use IC to:
Track stock levels.
Transfer stock values to the GL.
Track inventory levels at multiple locations.  (Accredo Saturn Only)
Transfer stock between locations.  (Accredo Saturn Only)
Track quantities, values and costs of sales.
Produce price code, sales and stock reports.
Provide a file of products and services for easy transfer of descriptions, units, prices, discounts, GST rates and sales categories (Sales Groups) to computer generated invoices.
Perform detailed stocktaking across multiple locations. (Accredo Saturn Only)
Record serial or lot numbers.

---

## Inventory Control - Maintain

Source: https://accredo.co.nz/webhelp/InventoryControl_Maintain.htm

Inventory Control - Maintain
Navigator > Maintain > Inventory Control
In This Section
IC Product - Product tab
IC Product List
IC Transaction List
Gift Vouchers
IC Stock Group
IC Store Persons
IC Component
IC Product Component Of
IC Transfer List
IC Manufacture Batch List
IC Adjustment Batch List
IC Receipt Batch List
IC Bins
IC Categories
IC Product Tree
IC Product Quantities
Product Tracking Quantities
IC Product Tracking Query
IC Product Bin
IC Bin Tracking Quantities
IC Memo List
IC Link List
IC Budgets

---

## Inventory Control - Reports

Source: https://accredo.co.nz/webhelp/ICReports.htm

Inventory Control - Reports
Navigator > Reports > Inventory Control
See also
Report Selections Form
.
In This Section
IC Product Reports - Add Layout
IC Transaction Reports - Add Layout
IC Stocktake Reports - Add Layout
IC Tracking Reports - Add Layout
IC Transfer Reports - Add Layout
IC Memo Reports - Add Layout
IC Product Labels
IC Product Batch Labels
IC Product Sheets
IC Print Bin Labels
IC Bin Batch Labels
IC Print Basic Stocktake
IC Print Counts
IC Print Transfers
IC Print Manufacture Sheets
See Also
Inventory Control

---

## Inventory Control - Setup

Source: https://accredo.co.nz/webhelp/InventoryControl_Setup.htm

Inventory Control - Setup
Navigator > Setup > Inventory Control
In This Section
IC Settings - General tab
IC Change Tracking Log
IC Stock Locations
IC Units of Measure
IC UOM Groups
Alias Lot Nos
Merge Lot Nos
Alias Serial Nos
IC Memo Designer
IC Label Designer
IC Bin Label Designer
IC Transfer Designer
IC Product Sheet Designer
IC Count Designer
IC Stocktake Designer
IC Manufacture Sheet Designer

---

## Inventory Control - Tasks

Source: https://accredo.co.nz/webhelp/InventoryControl_Tasks.htm

Inventory Control - Tasks
Navigator > Tasks > Inventory Control
In This Section
IC Transactions
IC - Tracking Tab or Panel
IC Enter Manufactures
IC Enter Manufacture Batch
IC Enter Adjustment Batch
IC Enter Receipt Batch
IC Enter Stock Transfers
IC Enter Memos
IC Stocktake Processing
IC Update Prices
IC Bin Processing
IC Revalue Stock on Hand
IC Transfer to GL
IC End Of Period

---

## MB Script: IC Product Quantities by Location Pivot Table

Source: https://accredo.co.nz/webhelp/MBScriptICProductPivotTable.htm

MB Script: IC Product Quantities by Location Pivot Table
The following is the entire script for the
MB Tutorial: IC Product Quantities by Location Pivot Table
. Refer to the tutorial for information on how to use this script.
SQL = "SELECT ICProd.ProductCode " & _
"      ,ICPROD.Description " & _
"      ,ICQTY.LocationCode " & _
"      ,ICQTY.QuantityAvailable " & _
"FROM   ICPROD " & _
"        JOIN ICQTY  ON ICPROD.ProductCode=ICQTY.ProductCode " & _
"WHERE  ICProd.NonDiminishing = False " & _
"AND  ICProd.ProductCode BETWEEN :FromCode AND :ToCode " & _
"Order By ICProd.ProductCode , ICQty.LocationCode "
'Report Selections
Dim scForm as Object
scForm = CreateObject("Accredo.ScriptedForm")
scForm.Caption = "Locations Cross Tab Selections"
Dim FromCodeControl as Object
Dim ToCodeSibling as Object
FromCodeControl = scForm.InputCode("FromCode","ICPROD", "Product - From", "", False, False, True)
scForm.SetValue("FromCode", "")
ToCodeSibling = scForm.InputCode("ToCode","ICPROD", "Product - To", "", False, False, True)
ToCodeSibling.DittoSibling = FromCodeControl
scForm.SetValue("ToCode", "")
Do
If Not scForm.Execute Then
Abort("Report cancelled by user.")
Else
FromCode = scForm.GetValue("FromCode")
ToCode = scForm.GetValue("ToCode")
Exit Do
End If
Loop
If FromCode = "" And ToCode = "" then
FromCodeSelect = False
Else
FromCodeSelect = True
End If
'Default empty selection to start/end
If FromCode = "" Or ToCode = "" then
ICPROD = OpenTable("ICPROD")
ICPROD.IndexName = "Product"
If FromCode = "" Then
ICPROD.First
FromCode = ICPROD.ProductCode
End If
If ToCode = "" Then
ICPROD.Last
ToCode = ICPROD.ProductCode
End If
End If
Dim tblQty as Object
tblQty = ExecuteSQL(SQL,FromCode,ToCode)
Dim tblPivot as Object
tblPivot = PivotTable(tblQty, "ProductCode;Description", "LocationCode", "Sum(QuantityAvailable)", True)
TotalFields = tblPivot.Fields.Count
tblPivot.Fields.Item("ProductCode").DisplayWidth = 20
tblPivot.Fields.Item("Description").DisplayWidth = 40
tblPivot.Fields.Item(TotalFields - 1).DisplayLabel = "Total|Available"
For x = 2 to TotalFields - 2
CurrentLabel = tblPivot.Fields.Item(x).DisplayLabel
tblPivot.Fields.Item(x).DisplayLabel = Replace(CurrentLabel, "QuantityAvailable", "|Quantity|Available")
tblPivot.Fields.Item(x).DisplayWidth = 10
Next x
For x = 2 to TotalFields - 1
tblPivot.Fields.Item(x).total = True
Next x
Dim Report as Object
Report = CreateREport(tblPivot, "IC Quantity by Location")
Report.Destination = "Screen"
Report.Run

---

## MB Script: IC Products and Prices Pivot Table

Source: https://accredo.co.nz/webhelp/MCScriptICProductsPricesPivotTable.htm

MB Script: IC Products and Prices Pivot Table
The following is the entire script for the
MB Tutorial: IC Products and Prices Pivot Table
. Refer to the tutorial for information on how to use this script.
Dim tblCOPRICE as Object
tblCOPRICE = OpenTable("COPRICE")
tblCOPRICE.IndexName = "Line"
'Report Selections
Dim scForm as Object
scForm = CreateObject("Accredo.ScriptedForm")
scForm.Caption = "Report Selections"
Dim ProductFromControl as Object
Dim ProductToSibling as Object
ProductFromControl = scForm.InputCode("ProductFrom","ICPROD", "Product - From", "", False, False, True)
scForm.SetValue("ProductFrom", "")
ProductToSibling = scForm.InputCode("ProductTo","ICPROD", "Product - To", "", False, False, True)
ProductToSibling.DittoSibling = ProductFromControl
scForm.SetValue("ProductTo", "")
Do
If Not scForm.Execute Then
scForm.ShowStatusHint("Cancelled")
Abort("", True)
Else
ProductFrom = scForm.GetValue("ProductFrom")
ProductTo = scForm.GetValue("ProductTo")
Exit Do
End If
Loop
'Default empty selection to start/end
If ProductFrom = "" Or ProductTo = "" then
ICPROD = OpenTable("ICPROD")
ICPROD.IndexName = "Product"
If ProductFrom = "" Then
ICPROD.First
ProductFrom = ICPROD.ProductCode
End If
If ProductTo = "" Then
ICPROD.Last
ProductTo = ICPROD.ProductCode
End If
End If
Dim SQL as String
SQL = "SELECT   ICPROD.ProductCode " & _
"        ,ICPROD.Description " & _
"        ,ICPROD.SalesGroupCode " & _
"        ,ICPROD.StockGroupCode " & _
"        ,ICSELL.PriceCode " & _
"        ,ICSELL.Price " & _
"        ,COPRICE.LineNo " & _
"FROM   ICPROD " & _
"       INNER JOIN ICSELL  ON ICPROD.ProductCode=ICSELL.ProductCode " & _
"       INNER JOIN COPRICE ON COPRICE.PriceCode=ICSELL.PriceCode " & _
"Where  ICProd.ProductCode Between :ProductFrom and :ProductTo " & _
"ORDER BY ICPROD.ProductCode " & _
"        ,COPRICE.LineNo "
Dim tblPrices as Object
tblPrices = ExecuteSQL(SQL,ProductFrom,ProductTo)
'BrowseDataset(tblPrices)
Dim tblPivot as Object
tblPivot = PivotTable(tblPrices, "ProductCode;Description;SalesGroupCode;StockGroupCode", "LineNo", "Sum(Price)",False)
'DocumentObject(tblPivot)
TotalFields = tblPivot.Fields.Count
tblPivot.Fields.Item("ProductCode").DisplayWidth = 20
tblPivot.Fields.Item("Description").DisplayWidth = 40
For x = 4 to TotalFields - 1
Dim tblCOPRICE as Object
tblCOPRICE = OpenTable("COPRICE")
tblCOPRICE.IndexName = "Line"
'Report Selections
Dim scForm as Object
scForm = CreateObject("Accredo.ScriptedForm")
scForm.Caption = "Report Selections"
Dim ProductFromControl as Object
Dim ProductToSibling as Object
ProductFromControl = scForm.InputCode("ProductFrom","ICPROD", "Product - From", "", False, False, True)
scForm.SetValue("ProductFrom", "")
ProductToSibling = scForm.InputCode("ProductTo","ICPROD", "Product - To", "", False, False, True)
ProductToSibling.DittoSibling = ProductFromControl
scForm.SetValue("ProductTo", "")
Do
If Not scForm.Execute Then
scForm.ShowStatusHint("Cancelled")
Abort("", True)
Else
ProductFrom = scForm.GetValue("ProductFrom")
ProductTo = scForm.GetValue("ProductTo")
Exit Do
End If
Loop
'Default empty selection to start/end
If ProductFrom = "" Or ProductTo = "" then
ICPROD = OpenTable("ICPROD")
ICPROD.IndexName = "Product"
If ProductFrom = "" Then
ICPROD.First
CurrentLabel = tblPivot.Fields.Item(x).DisplayLabel
If tblCOPRICE.FindExact(val(CurrentLabel)) then
tblPivot.Fields.Item(x).DisplayLabel = tblCOPRICE.PriceCode
End If
tblPivot.Fields.Item(x).format = "0.00"
Next x
'BrowseDataset(tblPivot)
Dim Report as Object
Report = CreateReport(tblPivot, "IC Products and Prices")
Report.Destination = "Screen"
Report.Run
See Also
MB Tutorial: IC Products and Prices Pivot Table

---

## MB Tutorial: IC Product Quantities by Location Pivot Table

Source: https://accredo.co.nz/webhelp/MBTutorialICProductQtyByLocnPivotTable_1.htm

MB Tutorial: IC Product Quantities by Location Pivot Table
This tutorial shows you how to produce a report on IC Product quantities by location. You can use MaxBasic to create a Pivot Table with this information, then format the table.
To begin, create a SQL query to extract the data. Go to Navigator > Setup > SQL Query Builder.
Select the
ICPROD
(IC Products) and
ICQTY
(IC Quantities) tables. These will be joined by the
ProductCode
fields.
Click to select the following fields:
ICPROD.ProductCode
ICPROD.Description
ICQTY.LocationCode
ICQTY.QuantityAvailable
The fields selected will be displayed in the grid at the bottom of the SQL Query Builder form.
Go to the SQL tab. The SQL code will be displayed. Add these lines to the end of the SQL code:
WHERE  ICProd.NonDiminishing = False
AND  ICProd.ProductCode BETWEEN :FromCode AND :ToCode
Order By ICProd.ProductCode , ICQty.LocationCode
This will only select products that are diminishing (kitsets will not be included), and will allow you to input a range of Product Codes to select from. It will also order the results by the Product Code, then Location Code.
Go to the SQL for Script tab. This contains the query in a format that can be inserted into a script. Copy the text in this tab.
Go to Accredo > Script > Script Editor to open the Script Editor.
Type the following in the Script Editor:
SQL =
Then Paste the SQL Query into the window, on the same line as
SQL =
. You now have the SQL query so it can be used by the MaxBasic code. The script will look like this:
SQL = "SELECT ICPROD.ProductCode " & _
"      ,ICPROD.Description " & _
"      ,ICQTY.LocationCode " & _
"      ,ICQTY.QuantityAvailable " & _
"FROM   ICPROD " & _
"       INNER JOIN ICQTY  ON ICPROD.ProductCode=ICQTY.ProductCode " & _
"       WHERE  ICProd.NonDiminishing = False " & _
"AND  ICProd.ProductCode BETWEEN :FromCode AND :ToCode " & _
"Order By ICProd.ProductCode , ICQty.LocationCode "
You can now add the code to create a scripted form, to input the Product Code range. The caption will be
Locations Cross Tab Selections
. Type the following after the SQL Query:
'Report Selections
Dim scForm as Object
scForm = CreateObject("Accredo.ScriptedForm")
scForm.Caption = "Locations Cross Tab Selections"
Add controls to let the user input the From and To Product Codes:
Dim FromCodeControl as Object
Dim ToCodeSibling as Object
FromCodeControl = scForm.InputCode("FromCode","ICPROD", "Product - From", "", False, False, True)
scForm.SetValue("FromCode", "")
ToCodeSibling = scForm.InputCode("ToCode","ICPROD", "Product - To", "", False, False, True)
ToCodeSibling.DittoSibling = FromCodeControl
scForm.SetValue("ToCode", "")
Add code to run the scripted form, and get the input From and To Product Codes:
Do
If Not scForm.Execute Then
Abort("Report cancelled by user.")
Else
FromCode = scForm.GetValue("FromCode")
ToCode = scForm.GetValue("ToCode")
Exit Do
End If
Loop
If FromCode = "" And ToCode = "" then
FromCodeSelect = False
Else
FromCodeSelect = True
End If
'Default empty selection to start/end
If FromCode = "" Or ToCode = "" then
ICPROD = OpenTable("ICPROD")
ICPROD.IndexName = "Product"
If FromCode = "" Then
ICPROD.First
FromCode = ICPROD.ProductCode
End If
If ToCode = "" Then
ICPROD.Last
ToCode = ICPROD.ProductCode
End If
End If
Add code to execute the SQL Query above, using the input From and To Product Codes, and capture the results in a table.
Dim tblQty as Object
tblQty = ExecuteSQL(SQL,FromCode,ToCode)
Add code to create a pivot table based on the table created above. The ProductCode and Description fields will not be pivoted. The LocationCode will be pivoted, and the sum of the QuantityAvailable will be used as the pivot value field. The final parameter
True
sets the pivot table to contain row totals. See also
PivotTable
:
Dim tblPivot as Object
tblPivot = PivotTable(tblQty, "ProductCode;Description", "LocationCode", "Sum(QuantityAvailable)", True)
Add code to set the display width and labels for fields in the pivot table:
TotalFields = tblPivot.Fields.Count
tblPivot.Fields.Item("ProductCode").DisplayWidth = 20
tblPivot.Fields.Item("Description").DisplayWidth = 40
tblPivot.Fields.Item(TotalFields - 1).DisplayLabel = "Total|Available"
Add code to change the display for fields with a QuantityAvailable label to Quantity|Available, so the label will be displayed over two lines:
For x = 2 to TotalFields - 2
CurrentLabel = tblPivot.Fields.Item(x).DisplayLabel
tblPivot.Fields.Item(x).DisplayLabel = Replace(CurrentLabel, "QuantityAvailable", "|Quantity|Available")
tblPivot.Fields.Item(x).DisplayWidth = 10
Next x
Add code to have the fields display a total:
For x = 2 to TotalFields - 1
tblPivot.Fields.Item(x).total = True
Next x
Finally, add a report to display the pivot table:
Dim Report as Object
Report = CreateREport(tblPivot, "IC Quantity by Location")
Report.Destination = "Screen"
Report.Run
Click
Save...
(Ctrl+S)
to save the script.
Click
Run
(Alt+R)
to test the script. The pivot table containing IC Product Quantities by Location is shown as a report.
The entire script for this tutorial is at
MB Script: IC Product Quantities by Location Pivot Table
. You can cut and paste this script into the script editor to create this report.
See Also
Module Tutorials

---

## MB Tutorial: IC Products and Prices Pivot Table

Source: https://accredo.co.nz/webhelp/MBTutorialICProductsPricesPivotTable_1.htm

MB Tutorial: IC Products and Prices Pivot Table
This tutorial shows you how to produce a report on IC Product prices. You can use MaxBasic to create a Pivot Table with this information, then format the table.
Go to Accredo > Script > Script Editor to open the Script Editor.
To begin, open the
COPRICE
table. Enter the following code:
Dim tblCOPRICE as Object
tblCOPRICE = OpenTable("COPRICE")
tblCOPRICE.IndexName = "Line"
Create a scripted form to input the report selections.The caption will be
Report Selections
. Enter the following code:
'Report Selections
Dim scForm as Object
scForm = CreateObject("Accredo.ScriptedForm")
scForm.Caption = "Report Selections"
Dim ProductFromControl as Object
Dim ProductToSibling as Object
ProductFromControl = scForm.InputCode("ProductFrom","ICPROD", "Product - From", "", False, False, True)
scForm.SetValue("ProductFrom", "")
ProductToSibling = scForm.InputCode("ProductTo","ICPROD", "Product - To", "", False, False, True)
ProductToSibling.DittoSibling = ProductFromControl
scForm.SetValue("ProductTo", "")
Add code to run the form:
Do
If Not scForm.Execute Then
scForm.ShowStatusHint("Cancelled")
Abort("", True)
Else
ProductFrom = scForm.GetValue("ProductFrom")
ProductTo = scForm.GetValue("ProductTo")
Exit Do
End If
Loop
Add code to default the Product From and Product To if they are not entered:
'Default empty selection to start/end
If ProductFrom = "" Or ProductTo = "" then
ICPROD = OpenTable("ICPROD")
ICPROD.IndexName = "Product"
If ProductFrom = "" Then
ICPROD.First
ProductFrom = ICPROD.ProductCode
End If
If ProductTo = "" Then
ICPROD.Last
ProductTo = ICPROD.ProductCode
End If
End If
Create a SQL query to extract the data. Go to Navigator > Setup > SQL Query Builder.
Select the ICPROD (IC Products) and ICSELL (IC Sell Price) and COPRICE (CO Price List) tables. ICPROD and ICSELL will be joined by the
ProductCode
field. ICSELL and COPRICE will be joined by the
PriceCode
field.
Select the following fields:
ICPROD.ProductCode
ICPROD.Description
ICPROD.SalesGroupCode
ICPROD.StockGroupCode
ICSELL.PriceCode
ICSELL.Price
COPRICE.LineNo
Go to the SQL tab. The SQL code will be displayed. Add these lines to the end of the SQL code:
Where  ICProd.ProductCode Between :ProductFrom and :ProductTo
ORDER BY ICPROD.ProductCode
,COPRICE.LineNo
This will allow you to input a range of Product Codes to select from. It will also order the results by the Product Code, then Line No.
Go to the SQL for Script tab. This contains the query in a format that can be inserted into a script. Copy the text in this tab.
Type the following in the Script Editor:
SQL =
Then Paste the SQL Query into the window. You now have the SQL query so it can be used by the MaxBasic code.
Add code to execute the SQL Query above, using the input From and To Product Codes, and capture the results in a table.
Dim tblPrices as Object
tblPrices = ExecuteSQL(SQL,ProductFrom,ProductTo)
Add code to create a pivot table based on the table created above. The ProductCode, Description Sales Group Code and Stock Group Code fields will not be pivoted. The Line No will be pivoted, and the sum of the Price will be used as the pivot value field. The final parameter
False
sets the pivot table to not contain row totals. See also
PivotTable
:
Dim tblPivot as Object
tblPivot = PivotTable(tblPrices, "ProductCode;Description;SalesGroupCode;StockGroupCode", "LineNo", "Sum(Price)",False)
Add code to set the display width and labels for fields in the pivot table:
TotalFields = tblPivot.Fields.Count
tblPivot.Fields.Item("ProductCode").DisplayWidth = 20
tblPivot.Fields.Item("Description").DisplayWidth = 40
For x = 4 to TotalFields - 1
CurrentLabel = tblPivot.Fields.Item(x).DisplayLabel
If  tblCOPRICE.FindExact(val(CurrentLabel)) then
tblPivot.Fields.Item(x).DisplayLabel = tblCOPRICE.PriceCode
End If
tblPivot.Fields.Item(x).format = "0.00"
Next x
Finally, add a report to display the pivot table:
Dim Report as Object
Report = CreateREport(tblPivot, "IC Products and Prices")
Report.Destination = "Screen"
Report.Run
Click
Save...
(Ctrl+S)
to save the script.
Click
Run
(Alt+R)
to test the script. The pivot table containing IC Product Quantities by Location is shown as a report.
The entire script for this tutorial is at
MB Script: IC Products and Prices Pivot Table
. You can cut and paste this script into the script editor to create this report.
See Also
Module Tutorials

---

## Merge Bin Codes

Source: https://accredo.co.nz/webhelp/MergeBinCodes.htm

Merge Bin Codes
Use Merge Codes.
(Accredo Saturn Only, in Mercury use Merge Codes)
Navigator > Setup > Company > Utilities > Merge Bin Codes
You can merge two Bin Codes records into one. The effect on the data is:
Description
,
Custom 1
and
Custom 2
fields on the
From Bin Code
will be deleted.
Products in the
From Bin Code
will be moved to the
To Bin Code.
The Bin Code record with the
To Code
will be retained in the masterfile data. The
From Code
record will be deleted.
Warning: You will be prompted to back up your data before running this utility, as this utility restructures Accredo data files. If you experience power or other failure during posting, restore the backup and perform the Merge again.
A log is appended to the
Error Log
. Each merge is appended to an
Alias.csv
file in the data directory as a change log. Use this when integrating with a third party application to identify the merged records.
Selections
Location
Select the location to display Bin Codes for.
Fields
From Code
Select an existing code from the list of codes. To include inactive records click
Show Inactive Records
(Ctrl+I)
.
Note: For
Bin Tracked
locations bins with a
Bin Count
in progress cannot be merged.
To Code
Select an existing code, that the
From Code
will be changed to.
From Description
To Description
The descriptions for the codes. Read-only.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of bin codes to be merged. This can save time from entering codes individually. The import file must be a text file with one line per code change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From code
Alpha
16
To code
Alpha
16
Additional fields will be ignored by the import. Only lines in which the From code and To code differ, and a match for the codes is found are imported. When you import you are prompted with the Merge Importing report selections, this report shows the records that have been imported into the grid and error messages for lines which are not imported. If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Click
Post
(
Alt+T
) to merge the imported selections.
Buttons
Print
(Ctrl+P)
Print the Summary of Merge Bin Codes report. See
Report Selections Form
.
Post
(Alt+T)
Post the changes.
See Also
Utilities

---

## Merge Lot Nos

Source: https://accredo.co.nz/webhelp/MergeLot.htm

Merge Lot Nos
Navigator > Setup > Company > Utilities > Merge Lot Nos
Select the product code. Search for a product using the
Accredo Lookups
.
Merge Lot Nos to combine mis-entered Lot Nos. This will update data and history to the to Lot number and dates. When you Merge Lot Nos, a log of the changes is appended to the File Recovery
Error Log
, and recorded in the
CO Alias and Merge Log
. This is useful when you are integrating a third party application that will need to consider aliased records.
Selections
Product
Select the product to alias Lot No's for.
Fields
From Lot No,
From Lot Date,
From Expiry Date
Enter or select an existing Lot No from the list of Nos. Lot Date and Expiry Date will be displayed.
To Lot No,
To Lot Date,
To Expiry Date
Enter or select an existing Lot No to merge the From Lot No into. The Lot Date and Expiry Date of the To Lot are retained.
Note: Any resulting change to the Expiry Date does not re-visit any existing supply decisions.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a line.
Move up / Move down
(Shift+Up)
(Shift+Down)
Move a line up or down the grid.
Delete
(F3)
Delete a line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Import
(Alt+I)
Import a list of Lot Nos to be changed. This can save time from entering Lot Nos individually. The import file must be a text file with one line per change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From Lot No
Alpha
16
To Lot No
Alpha
16
Additional fields will be ignored by the import. Only lines in which both  the From Lot No and the To Lot are found and differ are imported. When you import you may be prompted with the Merge Importing report selections, this report shows any error messages for lines which are not imported.  If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
See Also
Inventory Control - Setup

---

## Product Tracking Quantities

Source: https://accredo.co.nz/webhelp/ICProductTrackingQuantities.htm

Product Tracking Quantities
Navigator > Maintain > Inventory Control > Product Tracking Quantities
Also launches from tracking toolbar on documents and batches, and from the Product toolbar when the
Product Tracking Quantities
button is clicked.
You can enquire on details of quantities by serial no and /or lot no on order, back order, allocated or in-transit and product stock levels for tracked products. For bin tracked locations you can enquire on detail of quantities by bin. (in Accredo Saturn).
Quantities tab
UOM Code
(
UOM
Active Only)
Select the UOM to display quantities in.
Initially set to the
Base UOM
,
Sale UOM
,
Purchase UOM
or
Manufacture UOM
for the Product according to the
UOM Enquiry Default
specified in
User Preferences
.
Lot  and Bin Quantities
Shows quantities by Lot No and bin if location is bin tracked, for each location (locations and bin tracking in Accredo Saturn only).
Serial Nos
Shows Serial Numbers in stock or pending for Serial tracked Products.
Allocated, Back Ordered, On Order, Shipped, Committed, In Transit (Accredo Saturn Only), Returned, Variation tabs
These tabs provide information on pending stock movements at the tracking detail level. From the tabs you can open the originating document and line for each pending stock movement.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
F12)
Open the document and locate the relevant line.
Print
(Ctrl+P)
Print a report of the information.
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
Calculate Totals / Clear Totals
(Alt+=)
Toggle on/off total calculation for the list fields where
Total
is selected in grid customisation.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
See Also
Inventory Control - Maintain

---

## Serial No Picker

Source: https://accredo.co.nz/webhelp/SerialNoPicker.htm

Serial No Picker
Click
Serial Nos below the tracking grid to open the Serial No Picker for outward movements of Purchase Serial No tracked products. The Serial No Picker provides a list of available Serial Nos to select from. Lot Nos are shown if the product is Lot Tracked and Bin Codes for Bin Tracked locations (Saturn only).
Product Code
The product the tracking is for.
Location
The location the tracking is for. (Accredo Saturn Only)
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Select All
(
Shift+F4
)
Select Serial Nos from the start of the list to complete all tracking lines.
Unselect All
(
Shift+F3
)
Clear selected Serial Nos.
Buttons
OK
(F9)
Apply the selected Serial Nos to the tracking grid.
Cancel
(Esc)
Cancel the Serial No selection.

---

## SF Script: Select Multiple Products on Invoice

Source: https://accredo.co.nz/webhelp/SFScriptSelectMultipleProductsOnInvoice.htm

SF Script: Select Multiple Products on Invoice
The following is the entire script for the
SF Tutorial: Select Multiple Products on Invoice
. Refer to the tutorial for information on how to use this script.
Dim frmINInvoice1 as Object
frmINInvoice1 = GetTriggerObject
If IsNull(frmINInvoice1) Then frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) Or frmINInvoice1.ClassName <> "INInvoiceEntryForm" Then Error "Wrong form class for script"
Dim ctrlWords as Object
Dim ctrlAny as Object
Dim ctrlPartial as Object
Dim tblLookup as Object
Public strProdWords as String
Public boolAnyWords as boolean
Public boolPartWords as boolean
If IsNull(boolAnyWords) Then boolAnyWords = ApplicationSetting("IC\WordAnyWords")
If IsNull(boolPartWords) Then boolAnyWords = ApplicationSetting("IC\WordPartialMatch")
Sub OnLookup(LookupWords as String, AnyWords as boolean, PartialWords as Boolean)
Dim tblLookupResult as Object
tblLookupResult = WordLookup("ICPROD",LookupWords,AnyWords,PartialWords)
tblLookup.Empty
tblLookupResult.First
Do Until tblLookupResult.EOF
tblLookup.Append
CopyFieldsByName(tblLookupResult,tblLookup)
tblLookup.Save
tblLookupResult.Next
Loop
tblLookup.First
tblLookupResult = nothing
End Sub
Sub OnButtonClick(Sender as Object)
OnLookup(ctrlWords.Value,ctrlAny.value,ctrlPartial.Value)
End Sub
' create template memtable
Dim tblTemp as Object
tblTemp = WordLookup("ICPROD","",False,False)
Dim Builder as Object
Builder = CreateObject("Accredo.MemoryTableBuilder")
Builder.Clone(tblTemp)
Builder.AddField("Selected","Quantity")
tblLookup = Builder.CreateTable
'DocumentObject(tblLookup)
tblLookup.Fields.Item("Selected").Index = 0
tblLookup.Fields.Item("Selected").DisplayWidth = 10
' Selection Dialog using Scripted Form Object
Dim scForm1 as Object
scForm1 = CreateObject("Accredo.ScriptedForm")
scForm1.Caption = "Product Lookup"
ctrlWords = scForm1.InputBox("Words","Words")
scForm1.SetValue("Words",strProdWords)
ctrlAny = scForm1.InputBoolean("Any","Any Word")
scForm1.SetValue("Any",boolAnyWords)
ctrlPartial = scForm1.InputBoolean("Partial","Partial Word")
scForm1.SetValue("Partial",boolPartWords)
Dim btnLookup as Object
btnLookup = scForm1.InputButton(2106,addressof(onButtonClick), "&Lookup")
Dim ProdGrid as Object
ProdGrid = scForm1.InputGrid("ProductList", "",tblLookup, 500,885)
ProdGrid.InputNumber("Selected")
Do
If scForm1.Execute Then
scForm1.BringtoFront
tblLookup.First
Do Until tblLookup.EOF
If tblLookup.Selected <> 0 then
frmINInvoice1.Line.Next
If not frmINInvoice1.Line.EOF then
'step to the end of any kitset
Do Until frmINInvoice1.Line.LineType = "Product" or frmINInvoice1.Line.LineType = "Narrative" or frmINInvoice1.Line.EOF
frmINInvoice1.Line.Next
Loop
If not frmINInvoice1.Line.EOF then
frmINInvoice1.Line.Insert
Else
frmINInvoice1.Line.Append
End If
Else
frmINInvoice1.Line.Append
End If
frmINInvoice1.Line.ProductCode = tblLookup.ProductCode
frmINInvoice1.Line.QuantitySupplied = tblLookup.Selected
End If
tblLookup.Next
Loop
strProdWords = scForm1.GetValue("Words")
boolAnyWords = scForm1.GetValue("Any")
boolPartWords = scForm1.GetValue("Partial")
Exit Do
Else
Abort("",True)
End If
Loop

---

## SF Tutorial: Select Multiple Products on Invoice

Source: https://accredo.co.nz/webhelp/SFTutorialSelectProductsOnInvoices_2.htm

SF Tutorial: Select Multiple Products on Invoice
This tutorial will show you how to create a scripted form to let you search for Products, then select multiple products and add them to an Invoice.
Open the
Script Editor
to create a script, by clicking
Record Script
(
Alt+F1
) then
Stop Recording
(
Alt+F1
) on the main toolbar. Alternatively, go to Accredo > Script > Script Editor.
First, enter the following code to ensure the code will be called from the IN Invoice Entry Form.
Dim frmINInvoice1 as Object
frmINInvoice1 = GetTriggerObject
If IsNull(frmINInvoice1) Then frmINInvoice1 = GetActiveObject
If IsNull(frmINInvoice1) or frmINInvoice1.ClassName <> "INInvoiceEntryForm" Then Error "Wrong form class for script"
Enter the following code to declare variables required:
Dim ctrlWords as Object
Dim ctrlAny as Object
Dim ctrlPartial as Object
Dim tblLookup as Object
Public strProdWords as String
Public boolAnyWords as boolean
Public boolPartWords as boolean
If IsNull(boolAnyWords) Then boolAnyWords = ApplicationSetting("IC\WordAnyWords")
If IsNull(boolPartWords) Then boolAnyWords = ApplicationSetting("IC\WordPartialMatch")
Create a Memory Table using the
Wordlookup
function. This will create a memory table to store the products selected, and the quantity of each product. Use the following code:
' create template memtable
dim tblTemp as Object
tblTemp = WordLookup("ICPROD","",False,False)
dim Builder as Object
Builder = CreateObject("Accredo.MemoryTableBuilder")
Builder.Clone(tblTemp)
Builder.AddField("Selected","Quantity")
tblLookup = Builder.CreateTable
tblLookup.Fields.Item("Selected").Index = 0
tblLookup.Fields.Item("Selected").DisplayWidth = 10
Create the scripted from to display and capture the products:
' Selection Dialog using Scripted Form Object
Dim scForm1 as Object
scForm1 = CreateObject("Accredo.ScriptedForm")
scForm1.Caption = "Product Lookup"
Set up the scripted form with options for
Any Word
and
Partial Word
, similarly to the standard Accredo
Word Lookup
:
ctrlWords = scForm1.InputBox("Words","Words")
scForm1.SetValue("Words",strProdWords)
ctrlAny = scForm1.InputBoolean("Any","Any Word")
scForm1.SetValue("Any",boolAnyWords)
ctrlPartial = scForm1.InputBoolean("Partial","Partial Word")
scForm1.SetValue("Partial",boolPartWords)
Add a
Lookup
button to the form, similarly to the standard Accredo
Word Lookup
:
Dim btnLookup as Object
btnLookup = scForm1.InputButton(2106,addressof(onButtonClick), "&Lookup")
Add the code to perform the lookup when the button is clicked. First, add a OnButton Click Sub routine. Add this code at the start of the script, before the main code.
Sub OnButtonClick(Sender as Object)
OnLookup(ctrlWords.Value,ctrlAny.value,ctrlPartial.Value)
End Sub
Add a OnLookup Sub routine to perform the lookup. Again, add this code at the start of the script, before the main code.
Sub OnLookup(LookupWords as String, AnyWords as boolean, PartialWords as Boolean)
Dim tblLookupResult as Object
tblLookupResult = WordLookup("ICPROD",LookupWords,AnyWords,PartialWords)
tblLookup.Empty
tblLookupResult.First
Do Until tblLookupResult.EOF
tblLookup.Append
CopyFieldsByName(tblLookupResult,tblLookup)
tblLookup.Save
tblLookupResult.Next
Loop
tblLookup.First
tblLookupResult = nothing
End Sub
Add a grid to display the products found:
Dim ProdGrid as Object
ProdGrid = scForm1.InputGrid("ProductList", "",tblLookup, 500,885)
ProdGrid.InputNumber("Selected")
You now have the code to display the scripted form. Next, add the code to run the form. Start with a loop to contain the form. Code in the following steps will go into this loop, between the Do and Loop, and will be indented.
Do
'<following code goes here>
Loop
Write the code to execute the form. This goes after the
Do
, and before the
Loop
statements above. Code in the following steps will go into the If - Then section.
If scForm1.Execute Then
'<following code goes here>
Else
Abort("",True)
End If
Add code to loop through the memory table created previously (tblLookup) and add all selected products to the Invoice. Add this code between the
If
and
Else
statements added in the previous step.
scForm1.BringtoFront
tblLookup.First
Do Until tblLookup.EOF
If tblLookup.Selected <> 0 Then
frmINInvoice1.Line.Next
If not frmINInvoice1.Line.EOF Then
'step to the end of any kitset
Do Until frmINInvoice1.Line.LineType = "Product" or frmINInvoice1.Line.LineType = "Narrative" or frmINInvoice1.Line.EOF
frmINInvoice1.Line.Next
Loop
If not frmINInvoice1.Line.EOF Then
frmINInvoice1.Line.Insert
Else
frmINInvoice1.Line.Append
End If
Else
frmINInvoice1.Line.Append
End If
frmINInvoice1.Line.ProductCode = tblLookup.ProductCode
frmINInvoice1.Line.QuantitySupplied = tblLookup.Selected
End If
tblLookup.Next
Loop
strProdWords = scForm1.GetValue("Words")
boolAnyWords = scForm1.GetValue("Any")
boolPartWords = scForm1.GetValue("Partial")
Exit Do
Save the script.
Go to Accredo Toolbar >
Add Shortcut
.
Add a shortcut button to the
InInvoiceEntryForm
toolbar, linked the the saved script. Select a Glyph for the button.
You can now go to the IN Invoice Form, and click the button added to search for products, then enter products found in multiple quantities.
The entire script for this tutorial is at
SF Script: Select Multiple Products on Invoice
. You can cut and paste this script into the script editor to create this function.
See Also
MaxBasic Tutorials

---

## UOMDecimals - MacBasic Function

Source: https://accredo.co.nz/webhelp/UOMDecimalsFunction.htm

UOMDecimals - MacBasic Function
UOMDecimals(UOM Code: String): Number
Returns the number of decimals places used to display UOM quantities for the specified UOM Code.
UOMDecimals function syntax has these named arguments:
Parameter
Description
UOM Code
Required. The UOM Code to return the decimal places for.

---

