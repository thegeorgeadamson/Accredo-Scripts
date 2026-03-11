# Purchase Orders & Processing (PO/PP)

> Purchase orders, goods receiving, purchase processing, suppliers

**Sections:** 66

---

## Quick Reference

- [PO Authorisation Codes](#po-authorisation-codes)
- [PO Categories](#po-categories)
- [PO Change Tracking Log](#po-change-tracking-log)
- [PO Email Purchase Orders](#po-email-purchase-orders)
- [PO Enter Memos](#po-enter-memos)
- [PO Enter Purchase Orders](#po-enter-purchase-orders)
- [PO Find Document Number](#po-find-document-number)
- [PO Label Designer](#po-label-designer)
- [PO Link List](#po-link-list)
- [PO Memo Designer](#po-memo-designer)
- [PO Memo List](#po-memo-list)
- [PO Memo Reports - Add Layout](#po-memo-reports---add-layout)
- [PO Order Labels](#po-order-labels)
- [PO Order Line Fields](#po-order-line-fields)
- [PO Order List](#po-order-list)
- [PO Order Reports - Add Layout](#po-order-reports---add-layout)
- [PO Print Purchase Orders](#po-print-purchase-orders)
- [PO Print Quotation Requests](#po-print-quotation-requests)
- [PO Purchase Order Designer](#po-purchase-order-designer)
- [PO Purchase Order Email Designer](#po-purchase-order-email-designer)
- [PO Purchase Orders - Enter Authorisation Code](#po-purchase-orders---enter-authorisation-code)
- [PO Purchase Orders - Generate](#po-purchase-orders---generate)
- [PO Purchase Orders - Header tab](#po-purchase-orders---header-tab)
- [PO Purchase Orders - Lines tab](#po-purchase-orders---lines-tab)
- [PO Purchase Orders - Links tab](#po-purchase-orders---links-tab)
- [PO Purchase Orders - Memos tab](#po-purchase-orders---memos-tab)
- [PO Reprice Purchase Orders](#po-reprice-purchase-orders)
- [PO Reprice Purchase Orders Results](#po-reprice-purchase-orders-results)
- [PO Revalue Foreign Orders](#po-revalue-foreign-orders)
- [PO Revalue Foreign Orders Results](#po-revalue-foreign-orders-results)
- [PO Settings - Display Labels tab](#po-settings---display-labels-tab)
- [PO Settings - General tab](#po-settings---general-tab)
- [PO Settings - Links tab](#po-settings---links-tab)
- [PO Settings - Memos tab](#po-settings---memos-tab)
- [PO Settings - Misc tab](#po-settings---misc-tab)
- [posting](#posting)
- [PP Batch Duplicate](#pp-batch-duplicate)
- [PP Batch Update](#pp-batch-update)
- [PP Change Tracking Log](#pp-change-tracking-log)
- [PP Inactivate Rules](#pp-inactivate-rules)
- [PP Inactivated Rules](#pp-inactivated-rules)
- [PP Populate Selection](#pp-populate-selection)
- [PP Price List Designer](#pp-price-list-designer)
- [PP Price List Designer - Comment tab](#pp-price-list-designer---comment-tab)
- [PP Price List Designer - Fields tab](#pp-price-list-designer---fields-tab)
- [PP Price List Designer - Output Selections tab](#pp-price-list-designer---output-selections-tab)
- [PP Price List Designer - Report Preferences tab](#pp-price-list-designer---report-preferences-tab)
- [PP Price List Designer - Selections tab](#pp-price-list-designer---selections-tab)
- [PP Price List Designer - Users tab](#pp-price-list-designer---users-tab)
- [PP Price Query](#pp-price-query)
- [PP Reports - Add Layout](#pp-reports---add-layout)
- [PP Rule](#pp-rule)
- [PP Rule - Rules & Breaks grids](#pp-rule---rules--breaks-grids)
- [PP Rule Form](#pp-rule-form)
- [PP Rule List](#pp-rule-list)
- [PP Rule List - Designed](#pp-rule-list---designed)
- [PP Rule List Designer](#pp-rule-list-designer)
- [PP Select Rules](#pp-select-rules)
- [PP Settings](#pp-settings)
- [PP Tutorial: Manage PP Rules](#pp-tutorial-manage-pp-rules)
- [PP Who, What, Where grids](#pp-who-what-where-grids)
- [Purchase Orders](#purchase-orders)
- [Purchase Orders - Maintain](#purchase-orders---maintain)
- [Purchase Orders - Reports](#purchase-orders---reports)
- [Purchase Orders - Setup](#purchase-orders---setup)
- [Purchase Orders - Tasks](#purchase-orders---tasks)

---

## PO Authorisation Codes

Source: https://accredo.co.nz/webhelp/POAuthorisationCodes.htm

PO Authorisation Codes
Navigator > Setup > Purchase Orders > Authorisation codes
You can edit, add or delete Authorisation codes and passwords and set purchase order authorisation limits. You can also control authorisation to issue purchase orders in the Company's name, and set limits on the value. First, you must setup Authorisation codes that can be password protected with an Order Limit. Having setup an Authorisation code, this must be entered before a purchase order can be saved (that is, before an Order number can be issued). If an Order Limit has been set for the Authorisation code entered, the order is checked to see that it complies with the limit before
Save.
Code
A unique 8 character code that identifies an Authorisation Account. This can be associated with a single person, or an area.
Name
The full name for an Authorisation Account can be printed on the purchase order. You can include a name and title, for example, J Smith, Marketing Manager.
Password
A password known only to authorised Users. This field cannot be viewed. To change a password, type the new password in the
Password
field. Before the new password is accepted you must enter the previous password (if one exists) and re-enter the new password. Users with Control
permission
for PO Authorisations can reset passwords without entering the previous password.
Hint: You can setup an Authorisation code which has no password but a specified Order Limit, for example, MISC for miscellaneous purchases with an Order Limit of $100.00
Order Limit
Specify a maximum Order Limit for this authorisation account per purchase order. Leave blank if you do not require a limit. Order Limits are checked against the Order total excluding GST. Order Limits are checked on an order by order basis, not summed across all current-orders for an Authorisation code, that is, if the Order limit for an Authorisation code is $1000.00, they can raise as many orders as they want provided no purchase order exceeds $1000.00
If you use purchase orders with Authorisation codes and Order Limits, you must set permissions. You can remove the Authorisations
Control Permission
for purchase orders for most Users. Removing Control Permission prevents Users adding or deleting Authorisation codes, and hides the
Order Limit
field. On editing Authorisation codes - Users without permission can edit Authorisation codes but only to change the name or their password.
Role, Phone No,  Mobile No, Email Address, Comment
Add details for each person authorised to make purchases. These can be printed on purchase orders using
Purchase Order Designer
.
Inactive
Select this or press the
Space Bar
while in the
Inactive
field. Lines for inactive Authorisation Codes are shown dimmed. Inactive authorisation codes will not appear in lookups.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see Authorisation Code details.
Insert
(F4)
You can add, delete, edit and scroll each line. Changes are saved as you move off the field, and appear on the grid on
CLOSE
(you can enter additional codes).
Delete
(F3)
Delete codes.
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
Codes are reloaded with changes other Users may have made.

---

## PO Categories

Source: https://accredo.co.nz/webhelp/POCategories.htm

PO Categories
Navigator > Maintain > Purchase Orders >
Categories 1 & 2

---

## PO Change Tracking Log

Source: https://accredo.co.nz/webhelp/PurchaseOrdersTrackingLog.htm

PO Change Tracking Log
Navigator > Setup > Purchase Orders >
Change Tracking Log
See Also
Purchase Orders - Setup

---

## PO Email Purchase Orders

Source: https://accredo.co.nz/webhelp/POEmailOrders.htm

PO Email Purchase Orders
Navigator > Reports > Purchase Orders > Email Purchase Orders
Send Purchase Orders by batch email. An email is created for all unprocessed Purchase Orders that have an email address, based on selections, with the Purchase Order document attached.
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
Column and row positions for formats other than pdf are specified explicitly in the Purchase Order document design.
Report File Name
The file that defines the Purchase Order document.
Set a default report file name from
Document Defaults
.
Click
Open In Designer
to open the selected file in the
PO Purchase Order Designer
.
Creditor - From/To
Select one or a range of creditors to email purchase orders for.
Reprint
Selected
, includes purchase orders matching the criteria that have previously been emailed.
Period
Select the time period to email shipments for from:
Period
Year
All Periods
Range of Periods
From Period /
To Period
When a
Period
or
Range or Periods
is selected, select the Starting and Ending periods.
Currency
Select a currency to email purchase orders for.
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
If there is an error using SMTP you can log the conversation with the SMTP Server, after send the log can be printed to assist with configuring the SMTP Server. Log SMTP Sessions is not saved with the User's settings, it is available for the duration of the Email Shipments window only.
Request Read Receipt
You can request notification when an email message is opened by its recipient.
Consolidate Emails On
Select from:
None
- Emails are not consolidated.
Email
- One email will be sent per email address. If there is more than one purchase order, each will be a separate attachment.
Creditor and Email
- One email will be sent per email address per Creditor Code. If there is more than one purchase order, each will be a separate attachment.
The default value is set in
PO Settings Misc tab
.
Consolidate Attachments
Selected
, one attachment if produced for all purchase orders on an email.
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
The email template specified in
Document Defaults
is loaded.
You can create email templates in the
PO Order Email Designer
.
Attachments tab
You can add one or more attachments to be emailed with each email.
See Also
Purchase Orders - Reports

---

## PO Enter Memos

Source: https://accredo.co.nz/webhelp/POEnterMemos.htm

PO Enter Memos
Navigator > Tasks > Purchase Orders >
Enter Memos
Defaults for inserting Memos, Alarms and Reminders are set in
PO Settings - Memos tab
.

---

## PO Enter Purchase Orders

Source: https://accredo.co.nz/webhelp/POEnterOrders.htm

PO Enter Purchase Orders
Navigator > Tasks > Purchase Orders > Enter Purchase Orders
You can:
Enter purchase orders to place with suppliers and print a Purchase Order document for the order.
Generate order quantities from stock levels and minimum and maximum quantities.
Enter and print quote requests.
Setup standing purchase orders for regular purchases from suppliers.
Enter new purchase orders, quote requests and standing purchase orders to suppliers for subsequent printing and processing - also available from
Purchase Order List
.
See also
PO Purchase Order - Header tab
for a list of fields on the Header tab.
Purchase Order Document Types
Purchase Order
Stock items included on purchase orders have the On Order quantity updated when the order is saved so you can view up to date stock. Purchase orders can be printed immediately, saved for editing or held open.
Quotation Request
Request for a quote to supply, can be printed. Later you can accept this to produce a current purchase order.
Standing-order
Enter standing purchase orders against suppliers, that is, orders for repeat or contract purchases. Once you have setup a Standing order, use
Duplicate
to generate orders. Stock items included on Standing-orders do not update the On Order quantity, stock will be allocated when a Purchase Order is generated from the Standing order. The word
order
can include a Quote request and Standing-order in this and related help topics.
Menu buttons
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Click to edit the saved document.
Insert
(F4)
Select a document type from the drop-down menu to create a new document.
Duplicate
(Shift+F4)
Insert a new purchase order by duplicating the order. A drop-down menu opens, choose a document type.
Select a document type from the drop-down, to create a duplicate document. You can duplicate a document as a different type, for example a Standing Order as a Purchase Order.
Delete
(F3)
Delete the document. Only available for saved, unposted documents, when the user has permission.
Drill Up
(Shift+F11)
For Quotes, opens the Order created from the quote.
Drill down
(Shift+F12)
View the source document, only available if the Purchase Order is saved and sourced from another document.
Print Order / Save & Print Order Immediately
(Ctrl+P)
Print the purchase order or quote request. In edit mode, the Order is saved first. This is useful if you require the purchase order immediately. Opens
PO Print Purchase Orders
.
Print Label
(Ctrl+L)
Print labels for the current order.
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
When details in the Header tab are changed, changes will apply to new Order lines, but not to existing order lines. Use the
Reprice
option to update prices for all lines.
Re-pricing defaults to updating the current
Cost Price
and
GST Code
. These are based on the Creditor and Product.
Select
Description, Date Expected
or
Vendor Code
to update the order lines based on the current details for the product.
Select
JC Sell Price
and
JC Sell Discount
to update Sell Prices from Job Costing. (If SP is installed, either both or neither of these must be selected.)
See also
Reprice Purchase Orders
for re-pricing bulk purchase orders.
Order from Quote
(Alt+O)
Available for Quotation Requests only.
Creates a new PO Purchase Order based on the current quote.
Generate Order
(Alt+G)
In Edit mode, adds lines based on stock levels and minimum and maximum quantities. See
Purchase Order - Generate
.
Delete Nil Lines
(Alt+D)
Available when editing, deletes all nil product lines from the Purchase Order. A line is considered to be nil if the quantity, extended cost and extended amount are zero, that is lines containing just a description are considered to be nil. Often this is used when duplicating a Standing Order, entering quantities supplied, then deleting lines not being supplied.
Mark as Receipted
(Alt+I)
Available for purchase orders, marks all Unprocessed lines as
Receipted
, zeroing Outstanding Quantitities and hence On Order quantities relating to the Order in Inventory Control.
Mark as Processed
(Alt+P)
Available for purchase orders, marking them
Processed
and moving them to history.
Mark as Unprocessed
(Alt+N)
Reverses
Mark as Processed.
Mark Historic
(Alt+T)
Available for standing orders only.
Changes Standing Order from current to history. The Post Status is changed to Posted. The Standing Order can be viewed in
PO Order List
when you select
History
documents.
Refresh Weight and Volume
(Alt+W)
If the weight and / or volume of a Product changes, existing lines on Orders are not automatically updated. Click
Refresh Weight and Volume
to re-calculate weight and volume from current Product Weight and Volume figures for all lines.
Print Product Labels
(Alt+U)
Print
IC Product Batch Labels
for Diminishing products and quantities (rounded up to nearest whole number). Product Label design is set in
Document Defaults
.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Form Fields
Period
Defaults to the System period. You can select another period.
Document Type
Shows the Type (Order, Quotation or Standing Order). Read-only.
ID
An allocated number that identifies the order. Read-only.
Currency and Regime
The
Currency code
and
Tax regime
for the document.
Creditor Code
Select the Creditor Code before entering details. The Creditor Name, Currency and Tax Regime are displayed.
Defaults from the creditor including Expense Code and Delivery Address will be applied. If the Creditor code is changed, new defaults will be applied to new lines added.
Note: If the Creditor is changed, defaults will not be applied to existing Lines in the order. Accredo attempts to preserve existing pricing. Use the
Reprice
button if you wish to apply new defaults to existing lines.
Type
The Creditor Type.
Normal
- creditor with full functionality.
Prospect
- restricted to Request for Quote documents only.
One-time -
expected to be single invoice and payment.
Order Totals
Customise
Opens
Customise Fields
, you can customise the fields visible in the totals panel.
Net
The net amount is the total of the ordered items so far excluding GST.
GST
The total GST on the net amount.
Gross
The ordered total so far. The sum of the net amount and the GST.
Total Weight
Total weight for the Order.
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
Total volume for the Order.
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
Exchange Rate
The exchange rate for the Order.
Buttons
Order List
Opens
PO Order List
and selects the document.
Create Shipment
Click to create an AP Shipment based on the Purchase Order lines. The shipment is not saved immediately, there is a check that the shipments version of PO Order quantities matches the current PO Order state.
If there is a conflict, for example, if a second shipment has been generated from the purchase order, or it has been edited since the shipment was generated, a lists prompts with the conflicts. Select
Reload from Orders
to remove conflicting lines from the shipment and attempt to add lines from the purchase order(s) again.
The default Shipment Type (
Prompt
,
Shipment
,
Invoice Only
,
Receipt Only
) is set in
PO Settings - General tab
.
Opens
AP Enter Shipments
.
View Shipments
Available if there are shipments for the order. Displays the
AP Shipments
for the order.
Save
Saves the order and assigns an ID Number.
Cancel
Cancels any changes.
In This Section
AP Shipments for Purchase Orders
PO Purchase Orders - Header tab
PO Purchase Orders - Lines tab
PO Purchase Orders - Links tab
PO Purchase Orders - Memos tab
PO Purchase Orders - Generate
PO Purchase Orders - Enter Authorisation Code
See Also
Purchase Orders - Tasks

---

## PO Find Document Number

Source: https://accredo.co.nz/webhelp/POFindDocument.htm

PO Find Document Number
Navigator > Maintain > Purchase Order > Purchase Order List >
Number
(Alt+N)
Enter a Document Number to find a document. The Document Number is the PO
Order No
.
To search for a document using the unique Document ID assigned to documents by Accredo, click
Find
(
Ctrl+F
).
See Also
PO Order List

---

## PO Label Designer

Source: https://accredo.co.nz/webhelp/POLabelDesigner.htm

PO Label Designer
Navigator > Setup > Purchase Orders >
Label Designer

---

## PO Link List

Source: https://accredo.co.nz/webhelp/POLinkList.htm

PO Link List
Navigator > Maintain > Purchase Orders >
Link List

---

## PO Memo Designer

Source: https://accredo.co.nz/webhelp/POMemoDesigner.htm

PO Memo Designer
Navigator > Setup > Purchase Orders > PO
Memo Designer

---

## PO Memo List

Source: https://accredo.co.nz/webhelp/POMemoList.htm

PO Memo List
Navigator > Maintain > Purchase Orders >
Memo List

---

## PO Memo Reports - Add Layout

Source: https://accredo.co.nz/webhelp/POMemoReports.htm

PO Memo Reports - Add Layout
Navigator > Reports > Purchase Orders > Memo Reports > Add Layout
See
Memo Report
.

---

## PO Order Labels

Source: https://accredo.co.nz/webhelp/POReports_Label.htm

PO Order Labels
Navigator > Reports > Purchase Orders > Order Labels
See also
Report Selections Form
.
Report File Name
The file that defines the order labels layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
Label Designer
.
Creditor From / To
Use these fields to select a single creditor or a range of creditors, or leave blank to print labels for all creditors. Use
Filter & Sort
to select the orders to print labels for.
Number of label copies
You can specify the number of copies for each label. For details on how to design labels that print different information on different copies, see
Label Designer
.
Start from label
Typically on sheet feed labels, you can start printing at a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.

---

## PO Order Line Fields

Source: https://accredo.co.nz/webhelp/POOrderLineFields.htm

PO Order Line Fields
Navigator > Tasks > Purchase Orders > Enter Purchase Orders > Lines Tab >
Zoom or
Customise Fields
Note: Outstanding figures are zeroed when a line is flagged Processed, or when the whole Order is marked Processed.
Line Type
(Type)
Select
Product
or
Narrative
.
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
Product Code
(Product)
The Product code from IC (if IC is installed), or selecting a Product code loads a number of defaults: the Unit Cost, and Lead Time fields are loaded with the values from the
Product Suppliers tab
.
Description
Defaults to the description from a selected product (can be overwritten). Up to 60 characters are available on the selected line. For
Narrative
lines, for more characters click
Narrative
(F2)
to open the
Narrative Editor
.
Quantity Ordered
(Quantity)
The original quantity of the Product ordered on the Purchase Order.
If
UOM
is
Active:
Quantity Ordered
is calculated as the
UOM Quantity Ordered
*
UOM Multiplier.
Quantity Ordered
is not shown in the grid by default.
If
UOM
is not Active, the
Quantity Ordered
is entered.
Unit
The unit for the product (for example, Each or Doz) usually printed on the order. If a UOM Code is entered, shows the UOM Code Description. If no UOM Code exists, this can be entered.
Cost Price
(Price)
/ Cost Price Bs
(Price Bs)
The Cost Price for the item defaults to the Supplier Cost or Supplier Standard Cost on the Supplier tab of the Product record per
AP Shipments Settings
.
If there is no Supplier record for the product, the Cost Price will default to the Standard or Latest Cost  or none per
AP Shipments Settings
.
/
Cost Price
in the Base Currency.
Discount Percentage
The discount percentage to be applied. Defaults from the relevant
Supplier Cost
.
GST Code
(GST)
The GST code for the line. If the Creditor has a
GST Override
set, it will be the default, otherwise the GST code comes from the Product, for the Tax Regime of the document. If there is no Product Code, the GST code will come from the Expense analysis code. It is unusual to need to change this code manually.
ExpenseCode
(Exp Code)
The Expense Analysis code that the net purchase on the line is analysed to when the Purchase Order line is transferred to a shipment. This defaults from the
Product Expense Code
if set, otherwise to the
Expense Code
entered on the
Purchase Order header tab
.
Ordered Amount
(Amount)
/ Ordered Amount Bs
The extended line amount, calculated as
(Quantity Ordered x Cost Price) - Discount %.
Read-only.
/
Ordered Amount
in the Base Currency.
Vendors Code
(Vendor Code)
Retrieved from IC Product Supplier Record. May be edited subject to PO > Purchase Order > Vendor code permission. Vendor code is saved to the Supplier Record when the line is receipted.
Date Expected
Calculated from the
PO
Order Date
and the
Lead Time
from the
Product Suppliers tab
.
Branch Code
(Branch)
The branch the purchase is analysed to when processing. (Accredo Saturn Only)
Currency Code
Currency code for the purchase order. Read-only.
Custom 1
Custom 2
These fields can be used to add information to be stored with purchase orders, and printed on documents. To change the field names, go to
PO Settings - Display labels tab
and change the display labels.
Date Of Last Sale
Date the product was last sold from the product record. Read-only.
Date Of Last Sale or Usage
Date the product was last sold or used from the product record. Read-only.
Date Of Last Usage
Date the product was last used from the product record. Read-only.
Department Code
(Dept)
The department the purchase is analysed to when processing. (Accredo Saturn Only)
Effective Cost Price
/Effective Cost Price Bs
Effective cost price, calculated as the
Price - Discount %
.
/
Effective Cost Price
in the Base Currency.
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
You can override the GL Account associated with the Expense code (for example, if you purchase a fixed asset, use a Miscellaneous Expense code, but override the GL Account with the GL Asset code at the time of purchase, adding a narration to explain this). If a GL Account code is,
Entered,
will override the GL Account code mapped from the Analysis code on transfer to GL.
Not entered
, Accredo will use the default GL Account code mapped from the Analysis code on transfer to the GL.
This field can be customised into the grid and is not visible by default, and controlled by permissions.
Invoiced Amount
(Value Invoice)
/ Invoiced Amount Bs
Amount invoiced on posted Shipments. Read-only.
/
Invoiced Amount
in the Base Currency.
Line Break
Used for lines saved from the
Narrative Editor
. Indicates whether to include a line break when orders are printed.
Line ID
Unique identifier for the line. Read-only.
Line Number
Shows the current line number on the purchase order.
Line Space
Used for lines saved from the
Narrative Editor
. Indicates whether to include a line space when purchase orders are printed.
Line Status
Lines can be:
Unprocessed,
the line has not yet been fully receipted and invoiced on one or more shipments.
Receipted
, the line is not yet Processed no further delivery is expected.
Processed,
the line has been fully receipted and invoiced on one or more shipments. A purchase order will become Processed when there are no further unprocessed lines.
Selecting Processed for a line which is not fully receipted and invoiced indicates no further receipts or invoices are expected.
A line can not be set Processed while there are unposted shipments relating to the line.
Cancelled,
the line has been cancelled and will not be received on a Shipment. This is typically used where a supplier has advised that the goods cannot be supplied.
A line can not be cancelled once there are shipment lines relating to it.
Setting Line Status to Receipted, Processed or Cancelled zeroes outstanding quantities and amounts and removes the line from IC Pending Transactions and On Order quantities.
Location Code
(Location)
The location for the ordered products, only required for lines with a Product code. (Accredo Saturn Only)
Narration
Type a narration, for example, to explain the reason for overriding the GL Account code, for example
Fixed Asset Purchase
.
Ordered GST
/ Ordered GST Bs
Ordered GST amount. Read-only. See
GST Line Calculations
for calculation details.
/
Ordered GST
amount in the Base Currency.
Outstanding Amount Invoice
/ Outstanding Amount Invoice Bs
Amount outstanding for Invoice. Read-only.
i.e. Quantity Outstanding Invoice* Effective Cost Price.
Zeroed when the Line or Order is marked Processed.
/
Outstanding Amount Invoice
in the Base Currency.
Outstanding Amount Receipt
/ Outstanding Amount Receipt Bs
Amount outstanding for Receipt. Read-only.
i.e. Quantity Outstanding Receipt * Effective Cost Price.
Zeroed when the Line or Order is marked Processed.
/
Outstanding Amount Receipt
in the Base Currency.
Pending Invoice Amount
/ Pending Invoice Amount Bs
Value yet to be invoiced on unposted shipments. Read-only.
/
Pending Invoice Amount
in the Base Currency.
Quantity Invoiced
(Qty Invoice)
Quantity invoiced from posted invoices from shipments. Read-only.
Quantity Outstanding Invoice
Quantity outstanding for invoice. Read-only.
i.e. Quantity Ordered - Quantity Invoiced - Quantity Pending Invoice.
Zeroed when the Line or Order is marked Processed.
Quantity Outstanding Receipt
Quantity outstanding for Receipt. Read-only.
i.e. Quantity Ordered - Quantity Receipted - Quantity Shipped.
Zeroed when the Line or Order is marked Processed.
Quantity Pending Invoice
Quantity yet to be invoiced on unposted shipments. Read-only.
Quantity Receipted
(Qty Receipt)
Quantity receipted from posted receipts from shipments. Read-only.
Quantity Shipped
Quantity yet to be receipted on unposted shipments. Read-only.
Receipted Amount
/ Receipted Amount Bs
Receipted amount from posted receipts from shipments. Read-only.
/
Receipted Amount
in the Base Currency.
Shipped Amount
/ Shipped AmountBs
Value yet to be receipted on unposted shipments. Read-only.
/
Shipped Amount
in the Base Currency.
UOM Fields
Only available if UOM is active for Inventory.
Base UOM Code
The Base UOM Code for the Product.
UOM Code
These are obtained from the Product record. They can be used (in a script) for apportioning freight and other costs across different Products. Only available when
UOM
is
Active
.
UOM Quantity Ordered
The quantity of the UOM ordered on the Order. If the UOM has a
Multiplier
of more than
1
, the
Quantity Ordered
will be calculated as the
UOM Quantity Ordered
*
UOM Multiplier
.
UOM Cost Price
/ UOM Cost Price Bs
The UOM Price is calculated as the
Cost Price
*
UOM Multiplier
. This can be overwritten.
/ The
UOM Cost Price
in the Base Currency.
UOM Effective. Cost Price
/ UOM Effective. Cost Price Bs
Effective cost price per UOM.
UOM Effective. Cost Price
in the Base Currency.
UOM Multiplier
The multiplier for the UOM Code. Read-only.
UOM Supplier Standard Cost
(UOM Active Only)
Standard cost from the supplier for the UOM. Read-only.
Job Costing Fields
Only available with JC installed, only applicable if a
JobCode
is entered.
Comment
Only available with JC installed, only applicable if a
JobCode
is entered.
Comment for the JC transaction. See
JC Enter Transactions
.
Complete for WIP
Only available with JC installed, only applicable if a JobCode is entered.
Selected,
transaction will be excluded from WIP calculations when the shipment receipt is posted. The Period Complete for WIP for the transaction will be set to the Shipment Receipt PeriodID.
Clear,
does not set the period for WIP allowing the transaction to be included in WIP calculations.
Component Code
Only available with JC installed, only applicable if a JobCode is entered.
The component code for the JC transaction when receipting against the purchase order.
Cost Centre Code
Only available with JC installed, only applicable if a JobCode is entered.
The default cost centre code for JC transactions when receipting against the purchase order.
JC Fully Invoiced
Selected
, the JC transaction is marked fully invoiced for JC.
Clear
, the JC transaction is available to be invoiced. (Default)
JC Tran Type
Job costing transaction type.
Job Code
The Job Code for the transaction when receipting against the purchase order.
Markup (%)
This is calculated as:
((Unit Sell Price - Cost Price) / Cost Price) x 100.
This figure is used to update the Selling Price for the product on the Job specified on the Purchase Order line.
Sell Currency Code
Sell currency code for the Job.
Sell Discount Percentage
(Disc%)
The discount percent to be applied to the Sell Price.
Sell Exchange Rate
Sell exchange rate.
Sell Price
/ Sell Price Bs
Unit sell price for the JC Transaction.
/ The
Sell Price
in the Base Currency.
Sell Rate Type
Sell exchange rate type.
UOM Sell Price
/ UOM Sell Price Bs
(UOM Active Only)
Calculated as the
Sell Price
*
UOM Multiplier
.
/ The
UOM Sell Price
in the Base Currency.
Product Fields
From the product record. Read-only.
Alternate Code
The alternate code from the product record. Read-only.
Average Cost
The average cost of the product. Read-only.
Bar Code
The default bar code from the product record. Read-only.
Bin Code
Bin Code from the product record. Read-only.
Latest Cost
Latest cost from the Product record. Read-only.
Lead Time
From the product record. Read-only.
Details
(Product Details)
Details from the product record. Read-only.
Standard Cost
Standard cost of the product. Read-only.
Supplier Standard Cost
Standard cost from the supplier. Read-only.
Volume
Volume from the Product record.
Weight
Weight from the Product record.
See Also
PO Purchase Orders - Lines tab

---

## PO Order List

Source: https://accredo.co.nz/webhelp/POOrderList.htm

PO Order List
Navigator > Maintain > Purchase Orders > Purchase Order List
Selections
Creditor
Select from the
Lookup
.
shows all selected documents for all creditors.
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
Default is Range of Periods with From Period set to First Available period for AP or period of first Current Document whichever is earlier, and To Period set to Last Available period for AP.
Document
Select the type of documents to be displayed, from:
Order
Quotation
Standing Order
Authorisation
You can filter the list by selecting an Authorisation code.
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
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Orders
to apply selections, filters and sorts to the list.
The default value is set in
PO Settings Misc tab
.
Select Orders
(F9)
Apply selections, filters and sorts to the list.
Default ordering for selected records is Period ID, Document ID.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new purchase order. If you select Order, Standing-order or Quote request, the selected document is inserted. If you selected History or All Documents, select the appropriate Document type from the menu.
Delete
(F3)
Delete the selected purchase order. If unsure, open the purchase order first. Deleting a purchase order marks it as deleted and transfers it to history. It is not deleted from the files. Only purchase orders that have not been receipted or invoiced can be deleted. To transfer an order to history, set its
Post Status
to
Processed
.
Open
(F12)
Opens
Enter Orders
. You can view details and quote requests. Standing and incomplete purchase orders can be edited. Processed and historic purchase orders can be viewed.
Print
(Ctrl+P)
Print a report of the Sales Order list, or save it as a PDF file to send as an email attachment.
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
Mark Processed
(Ctrl+M)
Marks an Order as processed and transfers it to history.
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
a document by entering an Order Number.
In This Section
PO Find Document Number

---

## PO Order Reports - Add Layout

Source: https://accredo.co.nz/webhelp/POOrderReports.htm

PO Order Reports - Add Layout
Navigator > Reports > Purchase Orders > Order Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Line Variation Report
Reports on goods received not invoiced, and goods invoiced but not received. Shows the PO lines quantities and values that are received but not invoiced and invoiced but not received. You can group the report by GL Account, Expense Code, Creditor or Product, as desired.
Order
Lists Purchase Order header and lines information. You can specify ranges of creditors and / or products and the required Post Status. The
Current/History
selection is to allow optimised scanning of the Order files. You can specify the period or a range of periods from which to select purchase orders.
Order Links
This report shows the links associated with orders for a range of periods.
Order Status
Lists current purchase orders and totals. You can select Document types, and set a post and print status.
Order Totals
Print the totals for all purchase orders. Separate totals are shown for Ordered, Received, Not Received, Invoiced and Not Invoiced.
Order Variation
Reports on variations between the quantities and values ordered and quantities and values receipted against the purchase orders. The Sort for this report is by creditor, then Order number within a creditor. Variation quantity and value are sub-totalled for each order. Grand totals for all orders shown on the report appear at the end of the report. Only Order lines with a quantity or a value variation are reported.
Stock On Order
(IC installed). Reports Stock on order for current orders (those with Post Status "Entered" or "Open"). Only stock ordered using IC Product codes is reported, manual and narrative lines are not included.
You can specify ranges of creditors and / or products and their required Post Status. Customise this layout to group by order number, creditor or product, depending on the purpose of the report. To customise and add grouping, place the number
1
in the Group field for
Document No
and
Document Date
, or
CreditorCode
and
CreditorName,
or
ProductCode
and
Description
. After you save the report, you can access customisation options from Selections Form > Options > Customise.
Order No Grouping
- Reports on stock on order grouped by Order Number. By default, the Order Number stock on order reports are sorted by Document No, then Document Date. Outstanding on order quantities are sub-totalled for each Order Number. Grand totals for all outstanding on order quantities appear at the end of the report.
Creditor Grouping
- Reports on stock on order grouped by Creditor. By default, the Creditor stock on order reports are sorted by creditor then within a creditor. Outstanding on order quantities are sub-totalled for each creditor. Grand totals for all outstanding on order quantities appear at the end of the report.
Product Grouping
- Reports on stock on order grouped by Product. By default, the Product stock on order reports are sorted by product then creditor then order within a creditor. Outstanding on order quantities are sub-totalled for each product. Grand totals for all outstanding on order quantities appear at the end of the report.

---

## PO Print Purchase Orders

Source: https://accredo.co.nz/webhelp/POPrintPurchaseOrders.htm

PO Print Purchase Orders
Navigator > Reports > Purchase Orders > Print Purchase Orders
Purchase orders (including Standing purchase orders) can be printed individually from Enter Purchase Orders. For batch printing, the Print Purchase Orders option is available from Navigator > Reports tab. Batch printing applies to normal purchase orders only (not Standing purchase orders). When a purchase order is printed, it's print status changes to "Printed". For batch printing, by default, purchase orders are printed by Order number.
See also
Report Selections Form
.
Report File Name
Specifies the file that defines the Purchase Order layout.
To set a default report file name go to Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
PO Purchase Order Designer
.
Creditor - From
Creditor - To
Available when selected from the Reports menu to print multiple Purchase Orders.
Select a single or a range of creditors, or leave blank to print purchase orders for all creditors. Use
Filter & Sort
to select the purchase orders you want to print.
Reprint
Available when selected from the Reports menu to print multiple Purchase Orders.
Clear,
only unprinted orders are included.
Selected,
only orders that have been printed are included and the
Selection
option becomes available.
Selection
Available when selected from the Reports menu to print multiple Purchase Orders, when the
Reprint
is selected.
Select unposted (that is, incomplete) orders, orders unprocessed or completed during the Current Period, current year or in the entire order history. The Unposted or Period options are commonly used when it is necessary to reprint purchase orders due to a paper jam in the printer.
Exclude Email Creditors
Selected
, purchase orders for creditors with email addresses be excluded.
Print as Copy
When selected from the Reports menu to print multiple purchase orders, only available when
Reprint
is selected. Only available for Purchase Orders that have already been printed.
Selected
, prints Purchase Orders with "COPY ONLY" ADDED TO THE document name.
See Also
Purchase Orders - Reports

---

## PO Print Quotation Requests

Source: https://accredo.co.nz/webhelp/POPrintQuotationRequests.htm

PO Print Quotation Requests
Navigator > Reports > Purchase Orders > Print Quotation Requests
Quote requests can be printed individually from Enter Purchase Orders. For batch printing, the
Print Quote Requests
option is available from Navigator > Reports tab. When a quote request is printed, its print status changes to
Printed.
For batch printing, quote requests are printed by Creditor code.
See also
Report Selections Form
.
Report File Name
The Report File Name specifies the file that defines the Quote Request layout.
See
Document Defaults
to set a default report file name.
Click
Open In Designer
to open the selected file in the
PO Purchase Order Designer
.
Creditor From / To
Use these fields to select a single creditor or a range of creditors, or leave blank to print quote requests for all creditors. Use
Filter & Sort
to select the quote requests to print.
Reprint
Available for the
Batch
print option (it is selected for printing).
Selected
, only quote requests that have been printed previously are included.
Clear
, only previously unprinted quote requests are included.

---

## PO Purchase Order Designer

Source: https://accredo.co.nz/webhelp/POPurchaseOrderDesigner.htm

PO Purchase Order Designer
Navigator > Setup > Purchase Orders > Purchase Order Designer
Use the Purchase Order Designer to design your own purchase orders or open and modify an existing purchase order design. To design a purchase order quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install, and are also available on the Accredo website.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
The PO Purchase Order Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Usually a purchase order consists of:
Header band
showing details of the creditor and order number,
Repeating Detail band
for lines, and
Footer band
for totals.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code.
Name
Iterators filter records shown in the report. Available Iterators are:
Lines
- Lines on the Purchase Order.
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in addition to the standard
objects
are:
Author
Fields from the Authorisation code record.
Contact
Fields from the Creditor Contact records. If a contact has been specified, this object is populated with the information associated with the document. If no contact is specified, this object is populated with the primary contact information (if specified).
Creditor
Fields from the Creditor record.
itLines
Properties for the Lines iterator.
OrderHead
Fields from the Purchase Order header record.
OrderLine
Fields from the Purchase Order line records.
Product
Fields from the Product specified in the Purchase Order line.
ProductQty
Fields from the quantity for the Product specified in the Order line.
Report functions available in addition to the standard
MaxBasic functions
are:
CopyOrder
A Boolean function that returns True if
Print as Copy
is selected when reprinting Purchase Orders. This allows the words "Copy Only" or similar to be printed on copy Purchase Orders.
Sample PO Purchase Orders are provided with the Accredo Server Install, and are also available on the Accredo website. Sample PO Purchase Orders include:
POOrder.pfd
- standard PO Purchase Order.
POOrder_NoWrap.pfd
- PO Purchase Order without word-wrapped narrative lines.
To use documents downloaded from the website, ensure your document designer is the latest version.

---

## PO Purchase Order Email Designer

Source: https://accredo.co.nz/webhelp/POOrderEmailDesigner.htm

PO Purchase Order Email Designer
Navigator > Setup > Purchase Orders > Purchase Order Email Designer
You can design your own purchase order emails or open and modify a purchase order email design. To design a purchase order email quickly, start with an existing email design and modify it, ensuring you save it with a different file name. Select the default email design in
Document Defaults
.
Use Purchase Order Email Designs when you
Email Purchase Orders
.
HTML Body tab
Enter the email text for HTML Emails. See
HTML Email Editor
.
Plain Text Body tab
Enter the email text for plain text emails.
Preview
(Alt+P)
Display a preview of what the email will look like. A current Purchase Order must be available.
Load...
(Alt+L)
Load an existing Purchase Order Email to use for designing different emails.
Save...
(Ctrl+S)
Save the current email as a HTML file. You can reload the file in the designer to refine or create a new email.

---

## PO Purchase Orders - Enter Authorisation Code

Source: https://accredo.co.nz/webhelp/POEnterAuthorisationCode.htm

PO Purchase Orders - Enter Authorisation Code
Authorisation
When you set up
Authorisation codes
, they must be entered before a purchase order can be saved. You can enter an Authorisation code and password here, or if a code is required Accredo will request one before saving the order. If order limits have been set for the Authorisation codes Accredo will check the order complies before saving.
Password
Enter the password that applies to the Authorisation code (above).
Set status to Open and save unauthorised
Available if
Allow Unauthorised Open Orders
is selected in
PO Settings
. Saves order for later Authorisation with Post Status
Open
.

---

## PO Purchase Orders - Generate

Source: https://accredo.co.nz/webhelp/POGenerate_Selections.htm

PO Purchase Orders - Generate
Navigator > Tasks > Purchase Orders > Enter Purchase Orders >
Generate Order
button
Products that match the selections will be added to the current purchase order. Products marked as discontinued are excluded.
Product - From / To
Specify a product or range.
Creditor
The Creditor code is set to the Creditor code for the purchase order but this can be changed (or deleted).
Only where default supplier
Selected,
only products where the selected Creditor is the default supplier are added to the purchase order (default).
Clear,
all products are included if they are associated with the default supplier.
Ignore Minimum Quantity
Selected,
all items that have fallen below the maximum quantity will be included.
Clear,
only items that have fallen below the minimum quantity will be included.
Regardless of the selection the recommended reorder is calculated as the quantity required to get back to the maximum.
Location
If a Stock Location is selected, only quantities from that location are considered. If this is blank, quantities at all locations are considered. (Accredo Saturn Only)
The quantity to order is calculated as follows:
If
Ignore Minimum Quantity
Unselected:
Quantity to Order = Recommended Reorder (i.e. where Quantity Theoretical is less than Minimum Quantity)
If
Ignore Minimum Quantity
Selected
:
Quantity to Order = Maximum Quantity - Quantity Theoretical
If Quantity To Order > 0 then
If there is a Minimum Order Quantity in Supplier Costs that is greater than the calculated Quantity to Order then
Quantity to Order = Supplier Minimum Order Quantity
If
IC Units of Measure
is active and a Default Purchase UOM code has been set for the Product then
Round up Quantity to Order to a quantity in their Purchase UOM (expect that the minimum order quantity for the supplier would be set relative to default Purchase UOM so usually no further rounding is required).

---

## PO Purchase Orders - Header tab

Source: https://accredo.co.nz/webhelp/POEnterOrders_Header.htm

PO Purchase Orders - Header tab
Navigator > Tasks > Purchase Orders > Enter Purchase Orders > Header tab
See also
PO Enter Purchase Orders
.
Fields
Order Date
Defaults to the System Date.
Date Expected
The initial date expected for order lines, defaults from Order date based on Creditor
Lead Time
, can be changed and Order Lines which have not been received and match the old date expected will update to match.
Note: The numeric keypad +/- keys will step the date backwards or forwards, starting from the System Date if currently empty.
Date Required
Defaults to blank (can be edited). Note the numeric keypad +/- keys will step the date backwards or forwards from the System Date.
Valuation Date
For Foreign Currency orders, the date the order was last revalued. The exchange rate will relate to the Valuation date entered, otherwise to the Order date, see
PO Revalue Foreign Orders
.
Rate Type
Exchange Rate
If
Use Exchange Rate Table
is selected from Navigator > Setup > Foreign Exchange > Settings, the Rate is fetched from the Exchange Rates Table based on Currency code, Rate type and Date. You may lock the rate by clicking the
Fix Rate
button. Fixing means it can no longer be changed on this order and the order is excluded from Revaluations.
If not fixed the rate will be re-fetched from the rate table when Rate type, Currency code or Date are changed, and a rate based on the shipment date will be fetched when a shipment is generated.
Other Party Code
The code the creditor uses to refer to you.
Job
JC installed only. If the purchase order is for a Job, select the Job Code.
Accredo Saturn Only:  Branch, Department and Location for the Purchase Order will default from the Job.
Expense Code
Expense Analysis code
(default), the default Expense code for the creditor will be entered, (can be changed) and will be applied to all new lines. Expense codes can be overwritten. Search for an expense code using the
Accredo Lookups
.
Order Number/ Quotation Number
If
Allow Manual Order Numbers
in Navigator > Setup > Purchase Orders >
Settings
is:
Selected
, you can manually enter a PO number.
Clear
, a PO number is allocated from the PO Order number sequence, (or Quote number sequence) on
Save.
Internal Ref
Can be used as a reference, often on standing purchase orders.
Quotation Ref
Enter the suppliers quote reference number, or if the Order was generated from a Quote, this will be the Quote Reference.
Authorisation
When you set up
Authorisation codes
, they must be entered before a purchase order can be saved. You can enter an Authorisation code and password here, or if a code is required Accredo will request one before saving the order. If order limits have been set for the Authorisation codes Accredo will check the order complies before saving. If you have not set up Authorisation codes, ignore this field.
if
Allow Unauthorised Open Orders
is selected in
PO Settings
an order may be saved for authorisation later. Set Post Status
Open
to Save without Authorisation. Purchase Order No is not assigned and print is not available until authorised.
Password
Enter the password that applies to the Authorisation code (above). After the order is saved, if changes are made that affect the Gross amount, or if the Creditor, Status or Authorisation Code is changed, you will need to re-enter the password to save.
Change Password
- To change a Password, enter the existing password in the
Old Password
field (if one exists), enter the new password in the
New Password
and
Confirm Password
fields.
Comment
A 30 character comment transferred to generated purchase orders and the creditor transaction on POST.
Post Status
Status can be changed between Unprocessed and Open. Processed and Deleted occur as a result of processing options and cannot be changed. Order status can be,
Unprocessed
- not yet marked complete (receipted and invoiced). Standing-orders always have this status. Documents that are unprocessed can be edited.
Open
- an extended version of unprocessed status, prevents a Purchase Order from being batch printed or marked as
Processed
. A warning is also issued if trying to print a held open Purchase Order individually. An example of a possible use for this is where you raise a Purchase Order for a supplier which you add to progressively, then print at the end of the day or week.
Processed
- order has been fully receipted, invoiced or marked as processed, can be viewed and reprinted but not edited.
Deleted
- status for historic orders that have been deleted prior to being processed.
Print Status
Purchase Order status can be,
Unprinted
- Purchase Order (or Quote request) has not been printed.
Printed
- Purchase Order (or Quote request) has been printed - print status not changed.
View the
Print Log
(requires Read access Permission for Company > Settings).
Contact
Associate a contact with a Purchase Order. Will default to the primary contact specified for the Creditor, for new documents.
If Accredo is set to integrate with your telephone system using
TAPI
, press to dial the contact.
Email Contact
Selected
, emails regarding the document will be sent to the Contact Email Address.
Unselected
, emails regarding the document will be sent to the
Email Document
Address specified for the Creditor.
Branch Department
The Branch and Department codes that the Order is recorded against. If the Purchase Order was created from
JC Job
, these will default from the Job. If this is changed, the changes will be applied to all Lines that have not been manually changed. (Accredo Saturn Only)
Default Location
The Location code entered will be applied to all new Order lines. If the Deliver To option in
IC Stock Location
is not selected for a Location, it will not be available.
If the Purchase Order was created from
JC Job
, this will default from the Job. (Accredo Saturn Only)
Category 1
Category 2
Customised Categories can be added from
Categories
on the Maintain tab or
Open Category
(Shift+F12)
on the Lookup. Labels can be replaced in
PO Settings
.
Custom 1
Custom 2
Have no effect on the Purchase Order unless incorporated in a User defined script. Labels can be replaced in
PO Settings
.
Balances
These show the current aged balances for the Creditors account.
Delivery Instructions
Select a Delivery Code or enter a delivery address.
If JC is installed, and
Use Job Site Address
is Selected in
PO Settings
, and a
Job Code
is selected in the Job Defaults on the
Lines tab
, the address will default to the
Job Site Address
.
Accredo Saturn Only:  Otherwise, this will default from the Delivery Address code for the selected Location. If the Location does not have a Delivery Address code, the default from
PO Settings
is applied.Accredo Mercury Only: Otherwise, the default delivery address from
PO Settings
is applied. You can edit the address or select another.
Filter/Sort
- apply a
Filter & Sort
to the list of delivery addresses.
Save as a new delivery address
- opens New Delivery Address. Enter a code for the new delivery address.
Save delivery address
(Ctrl+D)
- provides a quick way to edit addresses without having to open the Customer form.
Job Site Address
- available when a Job Code is entered, reverts to the Job address.
Phone Nos
Customer telephone numbers. If Accredo is setup to interface with the
telephone system
, click
to dial.
Note: You can change the labels of the phone no fields in
Company Settings - Display Labels
.

---

## PO Purchase Orders - Lines tab

Source: https://accredo.co.nz/webhelp/POEnterOrders_Lines.htm

PO Purchase Orders - Lines tab
Navigator > Tasks > Purchase Orders > Enter Purchase Orders > Lines tab
Job Defaults panel (if Job Costing available)
Job
The Job code that will apply as new lines are inserted. Branch, Department and Location for the Purchase Order will default from the Job (in Accredo Saturn). If
Use Job Site Address
is Selected in
PO Settings
, the Delivery Address will default to the
Job Site Address
.
Type
The JC transaction type (Material, Disbursement or Time) that will apply to new lines as they are inserted.
Overridden if the product code selected for the line has
Job defaults
set.
Cost Centre
The Cost Centre code that will apply as new lines are inserted.
Overridden if the product code selected for the line has
Job defaults
set.
Component
The Component code that will apply as new lines are inserted.
Overridden if the product code selected for the line has
Job defaults
set.
Apply to all
(Ctrl+A)
Applies the selected Job Code, Cost Centre code or Component code to all Purchase Order lines.
Purchase Order lines grid
When entering or editing Purchase Order lines,
Ctrl+Enter
moves to the start of the next line.
The following fields are shown by default.
Zoom
to Form view, or select
Customise
(Alt+F5)
to view all
PO Order Line Fields
, including the
GL Account Code
.
Grid Fields
Type
Select from:
Product
- Enter product lines.
Narrative
- Enter extended lines of text, such as a detailed description of a job. Click
Narrative
(F2)
in the description field of a narrative line to open  the
Narrative Editor
, then type a narrative or choose a global narrative.
Product
The Product code from IC (if IC is installed), or selecting a Product code loads a number of defaults: the Unit Cost, and Lead Time fields are loaded with the values from the
Product Suppliers tab
.
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
The quantity ordered on the order. When a product is selected, defaults to the
Default Order Line Quantity
value specified in
PO Settings
(often
1
).
Unit
The unit for the product (for example, Each or Doz) usually printed on the order. If a UOM Code is entered, shows the UOM Code Description. If no UOM Code exists, this can be entered.
Price / UOM Price
The cost price is determined by the
Cost Price If No Supplier Cost
and
Cost Price If Supplier Cost
selected in
AP Settings - Shipments tab
.
The Cost Price for the item defaults to the Supplier Cost on the
Supplier tab
of the Product record. If there is no Supplier record for the product, the Cost Price will default to the Standard or Latest Cost determined by the
Cost Price If No Supplier Cost
and
Cost Price If Supplier Cost
selected in
AP Settings - Shipments tab
.
Discount
The discount percentage to be applied to the Amount. Defaults from the relevant
Supplier Cost
.
GST
The GST code for the line. If the Creditor has a
GST Override
set, it will be the default, otherwise the GST code comes from the Product, for the Tax Regime of the document. If there is no Product Code, the GST code will come from the Expense analysis code. It is unusual to need to change this code manually.
Exp Code
The Expense code the line will be analysed to when the order is transferred to a shipment. Defaults from the Product if set for the product, otherwise defaults from the Header tab.
Amount
The extended line amount, calculated as
(Quantity Ordered x Cost Price) - Discount %
. Read-only.
Vendor Code
Retrieved from IC Product Supplier Record. May be edited subject to PO > Purchase Order > Vendor code permission. Vendor code is saved to the Supplier Record when the line is receipted.
Date Expected
If
Lead Time
is specified in the
Product Suppliers tab
then calculated from the
PO
Order Date
and the Product
Lead Time,
otherwise from the PO Header
Date Expected
.
Grid toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Access grid fields in Form view for each line on the grid. Order lines can be entered/edited in the form or on the grid. To view more fields use the scroll buttons or resize the window. See
PO Order Line Fields
.
Insert
(F4)
Insert a new line.
Move Up
(Shift+Up)
Move Down
(Shift+Down)
Move the selected line.
Delete
(F3)
Delete the selected line.
Sort
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved when the order is saved.
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
Product Quantities
(Ctrl+Q)
Opens
IC Product Quantity
(if IC is Installed).
Accredo Saturn Only: Shows quantities at each location, to view stock availability and pending stock movements. Allows juggling stock 'on the fly'.
Special Pricing Information
(Ctrl+4)
Opens
SP Price Query
. You can query the results of a rule applied to a line. If a Special Price is applied, the rule reference displays with other information, depending on the Special Pricing script. Only available if the line has a Job Code and a Product selected.
Purchase Pricing Information
(Ctrl+S)
Opens
PP Price Query
. You can query the results of a rule applied to a line. If a Purchase Price is applied, the rule reference displays with other information, depending on the Purchase Pricing script.
Hide / Show Completed
(Ctrl+C)
Toggle on and off to hide and show status
Processed
and
Completed
lines on
Unprocessed
or
Open
orders. The default state is set in
Users, Groups and Roles - Preferences tab
.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Stock Levels
Customise
Opens
Customise Fields
, you can customise the
fields
visible in the stock levels panel.
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
In This Section
PO Order Line Fields

---

## PO Purchase Orders - Links tab

Source: https://accredo.co.nz/webhelp/POPurchaseOrders_Links.htm

PO Purchase Orders - Links tab
Navigator > Tasks > Purchase Orders > Enter Purchase Orders >
Links tab
See
PO Settings > Misc tab
for options to replicate links on
Order From Quote
.

---

## PO Purchase Orders - Memos tab

Source: https://accredo.co.nz/webhelp/POPurchaseOrders_Memos.htm

PO Purchase Orders - Memos tab
Navigator > Tasks > Purchase Orders > Enter Purchase Orders >
Memos tab
See
PO Settings > Misc tab
for options to replicate memos on
Order From Quote
.

---

## PO Reprice Purchase Orders

Source: https://accredo.co.nz/webhelp/PORepriceOrders.htm

PO Reprice Purchase Orders
Navigator > Tasks > Purchase Orders > Reprice Purchase Orders
Update the Cost Prices and other fields contained on unprocessed orders, quote requests and Standing-orders to reflect current values. This is for updating pricing on all (or a selection of) orders at a time. To reprice a single order, select the order from the Purchase Order List to open
Enter Purchase Orders
.
Creditor From / To
The Creditor selection can be useful if you need to reprice orders for specific creditors.
Product From / To
Product selection is used where updated pricing is only to be applied to specific products.
Type
Use to select document types, for example, to reprice Standing-orders to bring pricing up to date. Select from:
Order
Quotation
Standing Order
Update
Specify the fields to be updated:
Cost Price & Discount
GST Code
Date Expected
Vendor Code
Description
JC Sell Price
(available if JC is installed)
JC Sell Discount
(available if JC is installed)
Weight and Volume
Fields will be updated from current values. This can be used when orders are entered before the Cost Prices and other details of the items are precisely known (for example, forward orders).
The Unit Cost for the item is updated from the Unit Cost on the Supplier tab of the Product record. If there is no Supplier record for the product, the Cost Price will default to the Standard or Latest Cost set from
AP Settings - Shipments tab
.
Selections default from
AP Settings - Reprice tab
.
Note: If Special Pricing (SP) and Job Costing (JC) are installed, both
JC Sell Price
and
JC Sell Discount
must be either selected or unselected. You cannot select one of these and not the other.
Run
(F9)
Reprice selected orders. Displays the total number of orders repriced.
In This Section
PO Reprice Purchase Orders Results

---

## PO Reprice Purchase Orders Results

Source: https://accredo.co.nz/webhelp/PORepricePurchaseOrderResults.htm

PO Reprice Purchase Orders Results
Navigator > Tasks > Purchase Orders > Reprice Purchase Orders >
Run
Lists repriced sales orders and those that were not processed due to error.
Fields
- the fields contain information from the selection form and are read-only.
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
Total number of purchase orders that were not repriced due to errors.
Gross Errors
Total amount of the purchase orders that were unprocessed.
Records
Total number of purchase orders successfully repriced.
Gross Success
Total amount of the purchase orders successfully repriced.

---

## PO Revalue Foreign Orders

Source: https://accredo.co.nz/webhelp/PORevalueForeignOrders.htm

PO Revalue Foreign Orders
Navigator > Tasks > Purchase Orders > PO Revalue Foreign Orders
You can change the Valuation date and exchange rate to re-calculate base values on orders if the exchange rate is not
fixed
. You will be prompted for a Valuation date and exchange rate. Once revaluation is complete a Results list will show the revalued orders.
If Exchange Rates table is in use, shipments generated from purchase orders will automatically revalue based on the Shipment date.
Type
The type of Purchase Order to revalue. Select from
Orders
,
Quotations
and
Standing Orders
.
Valuation Date
Defaults to the last day of the Current Period (can be changed).
Currency Code
The Currency codes of all foreign creditors.
Rate Type
Defaults from
FX Settings
(can be changed).
Exchange Rate
If a revaluation has previously been performed for the valuation date, it loads the rates used. Otherwise rates are fetched from
Exchange Rate
based on the date or date closest to the Valuation Date, (can be changed). If no rates are found they will need to be entered.
Save Rates
Save back to FX Exchange Rate for the date specified in the
Valuation Date
field.
Run
(F9)
Revalue unallocated Foreign Orders from revaluation period up to current period.
Cancel
(Esc)
Close the form and do not make any changes.
In This Section
PO Revalue Foreign Orders Results

---

## PO Revalue Foreign Orders Results

Source: https://accredo.co.nz/webhelp/PORevalueForeignOrdersResults.htm

PO Revalue Foreign Orders Results
Navigator > Tasks > Purchase Orders > Revalue Foreign Orders >
Run
Lists revalued orders and those that were not processed due to error.
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
Total number of foreign orders that were not revalued due to errors.
Records
Total number of foreign orders successfully revalued.

---

## PO Settings - Display Labels tab

Source: https://accredo.co.nz/webhelp/POSettings_DisplayLabels.htm

PO Settings - Display Labels tab
Navigator > Setup > Purchase Orders > Settings > Display Labels tab
Set the display labels for the categories and custom fields.
Name
The name of the custom or category field, and where it is used.
Label
Enter the label you wish to be used for the custom or category field. If no label is entered, the field
Name
will be displayed.

---

## PO Settings - General tab

Source: https://accredo.co.nz/webhelp/POSettings.htm

PO Settings - General tab
Navigator > Setup > Purchase Orders > Settings > General tab
Next Order Number
The number allocated on
Save.
Defaults to blank, and must be set.
Next Quotation Number
Start the numbering sequence as each quote request is allocated a number on
Save.
Defaults to blank, and must be set.
Unique Order Numbers Required
Selected
, ensures manually generated Order numbers are not duplicated.
Allow Manual Order Numbers
Selected,
you can manually enter Order numbers and quote request numbers.
Allow Unauthorised Open Orders
Selected
, a purchase order can be saved without an Authorisation code if it's Post Status is
Open
and it does not have an Order number. Unauthorised Open orders cannot be printed or assigned an Order number. To authorise a saved order, a User with the correct permissions must change the Post status to Unprocessed, enter their valid Authorisation code and
Save.
Clear
, a purchase order must be authorised before it can be saved. Authorisation is required for purchase orders when at least one Authorisation code has been added from Navigator > Setup > Purchase Orders >
Authorisation codes
.
Allow Zero Value Orders
Selected
, zero-value Purchase Orders can be saved and Purchase Order numbers assigned for them.
Clear
, (default) Purchase Orders cannot be saved without a non-zero Ordered Amount. Does not apply to Request for Quotation and Standing Orders.
Allow Ordering Discontinued Products
Selected
, discontinued products may be ordered but warn with a status hint.
Clear
, (default) discontinued products can not be ordered and are filtered from Product Code look-ups.
Delivery Address
Accredo Saturn: Choose a Delivery Address to be used if the location on the PO Header does not have a Delivery Address code.
Accredo Mercury: Enter a Delivery Address.
Use Job Site Address
Available with JC only. When
Selected
, if a Job Code is selected in a PO Header, the Job Site Address will be used as the Delivery Address.
Create Shipment
Set the behaviour for the
Create Shipment
button on
Purchase Orders
.
Prompt
- (Default) Prompt the user to select the type of shipment.
Shipment
- Create a shipment with Invoice and Receipt.
Invoice Only
- Create an Invoice Only shipment.
Receipt Only
- Create a Receipt Only shipment.
Order Completion Basis
Determine when orders are marked as
Processed:
Both Invoice & Receipt,
receipted and invoiced.
Invoice Only,
invoiced but not necessarily receipted.
Receipt Only,
receipted but not necessarily invoiced.
None,
PO Orders are not
Completed
automatically, they can be completed manually from either the PO List or PO Order Entry.
Default Order Line Quantity
The default quantity entered on a Purchase Order line when a product is selected. Usually set to
zero
, or
1.
Create Shipment
Exclude Narrative Lines
Selected,
prevent Narrative lines with Quantity =
zero
from a PO being included on a shipment when the shipment is created.
Allow Edit for Posted Orders
Selected,
posted Orders can be edited, where the User has permission.
Clear,
posted Orders cannot be edited.
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
PO Settings - Misc tab
PO Settings - Display Labels tab
PO Settings - Memos tab
PO Settings - Links tab
See Also
Purchase Orders - Setup

---

## PO Settings - Links tab

Source: https://accredo.co.nz/webhelp/POSettings_Links.htm

PO Settings - Links tab
Navigator > Setup > Purchase Orders > Settings > Links tab
For each Account you can specify the default Link path within the Links folder. This path will be resolved and used as the default path for the
Link File
dialog and the
AddFileLink
function when adding links for the Account.
Link paths can reference fields in the Account File and the ModuleCode inside <> tags. If PeriodID is a field in the account file PeriodName and PeriodEndDate may also be used inside tags. Date fields in link paths format as YYYYMMDD.
e.g. <ModuleCode>\<CreditorCode>_<DocumentNo>_<DocumentDate>
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

## PO Settings - Memos tab

Source: https://accredo.co.nz/webhelp/POSettings_Memos.htm

PO Settings - Memos tab
Navigator > Setup > Purchase Orders > Settings > Memos tab
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
Set the selected memo as the default for PO memos.

---

## PO Settings - Misc tab

Source: https://accredo.co.nz/webhelp/POSettings_Misc.htm

PO Settings - Misc tab
Auto Select
PO Order List
PO Memo List
PO Link List
PO Tracking Log
Selected,
Auto Select for the list is selected by default.
Clear
, Auto Select is unselected for the list. This is recommended where there is a large number of records or the network is slow.
Replicate Links and Memos
Order from Request Links
Order from Request Memos
For Orders created from Requests for Quotation.
Leave
, Memos / Links remain on the original quote, no replication.
Copy,
Memos / Links remain on the original quote, and are copied to the order.
Move,
Memos / Links are moved from the original quote to the order.
Email
Exclude Email Creditors from Order Printing
Sets the default for
Exclude Email Creditors
on
Print PO Purchase Orders
.
Selected
, Purchase Orders for creditors with email addresses will be excluded from the print run.
Email Documents Preferred
Selected,
when Print is selected from PO Order Form, if:
an Email Address is specified for orders on the
AP Creditors - Contacts tab
- OR -
Email Contact
is
Selected
on the order, and the Contact has an Email Address,
then the default destination will be set to Mail message instead of Printer.
Consolidate Emails On
Select from:
None
- Emails are not consolidated.
Email
- One email will be sent per email address. If there is more than one order, each will be a separate attachment.
Creditor and Email
- One email will be sent per email address per Creditor Code. If there is more than one order, each will be a separate attachment.
Consolidate Attachments
Selected,
one attachment containing all orders will be sent per email.

---

## posting

Source: https://accredo.co.nz/webhelp/90.htm#o5582

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

## PP Batch Duplicate

Source: https://accredo.co.nz/webhelp/PPRuleList_BatchDuplicate.htm

PP Batch Duplicate
Navigator > Setup > Purchase Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
>
Batch Duplicate
button - OR -
Navigator > Maintain > Purchase Pricing > [Saved Rule List] >
Batch Duplicate
button
Duplicate all Purchase Pricing Rules in a list, by selecting new values for the duplicate rules.
Fields displayed are based on selection set for the Rule List in in
PP Rule List Designer
.
When changes are made to fields, the Selection button beside the field is ticked. Selected fields will be updated in the Duplicate Batch on save.
Save
(F9)
Create new rules by duplicating all rules in the Rule List, with the values in all the
Selected
fields updated.
Cancel
(Esc)
Cancel all changes.

---

## PP Batch Update

Source: https://accredo.co.nz/webhelp/PPRuleList_BatchUpdate.htm

PP Batch Update
Navigator > Setup > Purchase Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
>
Batch Update
button - OR -
Navigator > Maintain > Purchase Pricing > [Saved Rule List] >
Batch Update
button
Once a rule list has been created, you can update Purchase Pricing rules in a batch, by selecting values to update for all rules in a list.
Fields displayed are based on selection set for the Rule List in in
PP Rule List Designer
.
When changes are made to fields, the Selection button beside the field is ticked. Selected fields will be updated on save.
Save
(F9)
Apply the values in all the
Selected
fields to all Purchase Pricing rules in the rule list.
Cancel
(Esc)
Cancel all changes.

---

## PP Change Tracking Log

Source: https://accredo.co.nz/webhelp/PurchasePricingTrackingLog.htm

PP Change Tracking Log
Navigator > Setup > Purchase Pricing >
Change Tracking Log

---

## PP Inactivate Rules

Source: https://accredo.co.nz/webhelp/PPInactivateRules_Selections.htm

PP Inactivate Rules
Navigator > Tasks > Purchase Pricing > Inactivate Rules
Inactivate Purchase Pricing Rules which have expired or have Inactive criteria.
Selections
Creditor
Select a Creditor to limit Purchase Pricing Rules to inactivate, or leave blank to inactivate selected rules for all Creditors.
Product
Select a Product to limit Purchase Pricing Rules to inactivate, or leave blank to inactivate selected rules for all Products.
Inactive Criteria
Selected
, (default) Rules where any of the criterion is inactive or not found will be inactivated.
Expiry Date
If an
Expiry Date
is entered, any Rules with an
End Date
on or before the Expiry Date will be inactivated.
Filter Rule
(Ctrl+F2)
Clear Rule Filter
(Ctrl+F3)
Apply or clear further filters on PP fields to limit rules to inactivate. The button changes to indicate if a filter and sort is applied.
Button
Run
(F9)
Inactivate rules meeting the criteria specified. Displays the Inactivated Rules.
In This Section
PP Inactivated Rules

---

## PP Inactivated Rules

Source: https://accredo.co.nz/webhelp/PPInactivatedRules.htm

PP Inactivated Rules
Navigator > Tasks > Purchase Pricing > Inactivate Rules >
Run
(
F9
)
Displays a list of rules that were inactivated.
Note:
Where
criteria is only available in Accredo Saturn.
Double click a Rule or press
F12
to open the Rule in the
PP Rule Form
where it may be edited.
Fields
Who
What
Where
The Rule criteria.
Start Date
End Date
The Rule
Start
date and
End
date, if any.
Priority
The Rule application priority.
Reference
The Reference for the rule.
Rule Type
The Rule Type.
Reason
The reason the rule was inactivated.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens
PP Rule
showing the selected rule. The rule can be edited.
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
Button
Close
(Esc)
Close the Inactivated Rules form.

---

## PP Populate Selection

Source: https://accredo.co.nz/webhelp/PPPopulateSelection.htm

PP Populate Selection
Navigator > Maintain > Purchase Pricing > Select Rules >
Run
>
Populate Grid
(Ctrl+G)
button
Populate the grid with one line for each Code selected within a range.
Type From
Select the starting Value for the Type. You can use
Word Lookups
.
Type To
Select the ending Value for the Type. You can use
Word Lookups
.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
OK
(F9)
Add one line to the grid per Value in the selection.
Cancel
(Esc)
Discard changes. No lines will be added to the grid.

---

## PP Price List Designer

Source: https://accredo.co.nz/webhelp/PPPriceList_Designer.htm

PP Price List Designer
Navigator > Reports > Purchase Pricing > Price List Designer
The Price List Designer separates the design and running of price list reports. Use the Price List Report Designer to create price list reports based on purchase pricing rules.
Access requires permission for the Designer and Control permission for Reports.
You can add designed reports to a Report List or the Navigator.
Price list reports are designed for a Creditor and Products associated with the Creditor.
Buttons
Add To Navigator...
(Alt+N)
Add reports to the Navigator once saved by adding a shortcut to the Price List Report from the Navigator. The report may be run from the shortcut. Right click the shortcut to Edit the Shortcut, or Edit the Shortcut Source, this opens the report design in the Price List Report Designer.
Run
(F9)
Runs the report, allowing you to test your report definition. If you have made changes, you will be prompted to save the changes before running.
Load
Loads an existing report definition file to modify or use or as the basis for another report. To load a report, click
Load,
select a report definition file, click
Open.
Save...
Saves as a report definition file. Once a report definition file is saved, you can add it to the Navigator or to a report list, maintain it, or use it as the basis for another report.
Note: To access the Price List Designer you need full
Control access
to the PP Designer and PP Reports.
In This Section
PP Price List Designer - Selections tab
PP Price List Designer - Fields tab
PP Price List Designer - Output Selections tab
PP Price List Designer - Report Preferences tab
PP Price List Designer - Users tab
PP Price List Designer - Comment tab

---

## PP Price List Designer - Comment tab

Source: https://accredo.co.nz/webhelp/PPPriceList_Comment.htm

PP Price List Designer - Comment tab
Navigator > Reports > Purchase Pricing > Price List Designer > Comment tab
See also
PP Price List Designer
.
You can annotate Price List definitions. View the purpose, document filter, or selection changes for the Price List.
This is for documenting the Price List definition - do not confuse it with the Report Comment on the Output Selections tab, which is printed on the Price List.

---

## PP Price List Designer - Fields tab

Source: https://accredo.co.nz/webhelp/PPPriceList_Fields.htm

PP Price List Designer - Fields tab
Navigator > Reports > Purchase Pricing > Price List Designer > Fields tab
Select the fields to include on the report.
See also
PP Price List Designer
.
Field Name
Select fields from those available in the drop-down menus, from the Product and the Purchase Price.
Width
Display Width
The width of fixed length string fields is shown in the Width field. You can change the space allowed on the list to a different value in the Display Width fields. The Width and Display Width are measured in a standard character size (the digit
0
).
If you change the Display Width, consider,
reports are usually printed in a proportional font, the Display Width is only indicative of the number of characters that will fit.
if the number of characters in the Display Width is less than the number in the Width field, this can result in data being truncated on the list.
Display Label
The field heading that will be printed on the list for the field on this line.
Visible
Only selected fields will appear for the Price list. Click to toggle the value. Non-visible fields are available for filter and sort on the
Selections
tab, you can
Filter & Sort
the Price code using criteria you do not want shown.
UOM Code
If UOM is Pending or Active, you can select a UOM Code for Purchase Price fields. If a UOM Code is specified, prices returned will be UOM Prices. If Quantity Breaks are available and a UOM Code is specified, Quantities returned will be UOM Quantities. If a product does not have the UOM Code specified, nothing will be returned.
Quantity
If you use quantity breaks, enter a quantity you want a price for. The quantity is only available if the field selected is from the PP rule. If you do not use quantity breaks, the Quantity field is unavailable for fields.
Group
This field allows grouping to be added to Price codes. To group the list on a field, enter a digit (
1-9
) in this field. The number represents the grouping level -
1
is the outermost level of grouping. It is unusual to group more than one level, selecting
Group
involves putting
1
in this field for all the grouping fields. For example, to group by Stock Group, put a
1
in this field for
StockGroupCode
and
StockGroupName.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
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

---

## PP Price List Designer - Output Selections tab

Source: https://accredo.co.nz/webhelp/PPPriceList_Output.htm

PP Price List Designer - Output Selections tab
Navigator > Reports > Purchase Pricing > Price List Designer > Output Selections Tab
Set the output defaults for the report.
Set the default destination for the report.
Enter the report title and any comments to be printed at the top of the report.
Specify the report destination and some fixed text to print on the report.
See also
PP Price List Designer
.
Destination / Format / File Name / New Excel Workbook /Column Headers / Append to File
Set the defaults for the report selections. See
Report Selections Form
.
Report Title
The title to be printed at the top of the report.
Short Name
The default name to be used when the report is saved to a Disk File or Excel Worksheet.
Hide Filters, Hide Selections, Hide Sorting, Hide Report Definition
Selected,
hide options from being printed at the start of the report.
Report Comment
Comments to be printed in the selections area at the top of the report. This can be useful for documenting the purpose of the report. The
Comment tab
can be used for internal documentation on the report.

---

## PP Price List Designer - Report Preferences tab

Source: https://accredo.co.nz/webhelp/PPPriceList_ReportPreferences.htm

PP Price List Designer - Report Preferences tab
Navigator > Reports > Purchase Pricing > Price List Designer > Report Preference tab
Select formatting options for the report.
See also
PP Price List Designer
.
Report Options
Start new page on main group break
Only applies to reports grouped at the Master Band level.
Selected,
for reports where the Master band has a
Group
of
1
, a new page will be started for each group level 1. When the report
Destination
is
Excel worksheet
, a new worksheet will be started for each group level 1.
Include records with empty detail
Selected,
records are shown when there are no details for the record, and when no fields are visible and no filter is applied.
Unselected
, records with no details are not shown; records with no visible fields and no filter applied are not shown.
Totals only
Selected,
collapses the report to group level
1
or to totals only if no grouping. Only fields that are grouped or totalled appear on the report.
Label group totals
Selected,
for grouped reports display grouping fields in italics next to group totals to the limit of the space available.
Freeze Excel Headers
Selected,
when the report
Destination
is
Excel Workbook
or
Disk File
and
Format
is
Excel XLSX File
by default column headings will be frozen.
Double Spacing
Selected,
the detail level of the report will be double spaced.
Shade Alternate Rows
Selected,
alternate rows at the detail level of the report will be shaded, based on the
Report Row Shade
set in
Preferences - Display tab
.
Suppress Grand Totals
Selected,
no grand totals for the top level of grouping are printed.
Enable Clickable Fields
Selected,
fields in report layout printed to screen can respond to double-click (or
single-click
) to open source record.
Hide Filters,
Hide Sorting,
Hide Selections
Selected,
hide options from being printed at the start of the report.
Reporting Fonts
Select the font for each section. Click the relevant font button to open Windows fonts.
Restore Default Fonts
Restore fonts settings to their defaults.
Page Layout
Automatic
-
print in portrait orientation if the report will fit, otherwise print in landscape. If a report doesn't fit landscape, fonts will be scaled down.
Portrait or Landscape
-
print in the selected orientation. If a report is too wide to fit based on selected fonts and orientation, fonts will be scaled down.
Report Margins
Unless margins are set, reports will print close to the edge of the paper. This can make them hard to file in a ring binder. If data near the margins is missing, the wrong printer driver may be installed. You can temporarily increase the margins to fix this.

---

## PP Price List Designer - Selections tab

Source: https://accredo.co.nz/webhelp/PPPriceList_Selections.htm

PP Price List Designer - Selections tab
Navigator > Reports > Purchase Pricing > Price List Designer > Selections tab
Use the Selections tab to define the records to include in the report and the selections available when the report is run.
See also
PP Price List Designer
.
Note:
Where
criteria is only available in Accredo Saturn.
Select
What
,
When
,
Who, Where
dimensions for the Price list.
To include a selections in the report selections toggle
to
next to the selection.
What
Select a range of Products or Stock Groups to obtain a Price List. If no Purchase Price applies, the regular price is used.
The Price List will show prices for Product in the selected range.
Creditor is Default
Selected,
only Products where the Creditor Code is specified on the Product record are reported.
Unselected
, Products where the Creditor Code is specified on the Product record, and Products where there is a Supplier Cost record for the Creditor are reported.
You can
filter
the list.
When
Effective Date
and
Currency
selections are always included in report selections. Dates saved in the report definition are handled as an offset from the System Date.
Who
Select a Creditor for the Price list. When you select a Creditor,
Who
selections populate from Creditor dimensions (for example, Creditor Group or AP Category).
Who
selections are based on dimensions setup in the
Who grid
.
If PO Order dimensions are available (for example, PO Category 1), select the relevant criteria as these are independent of the Creditor record. If selections are left blank, rules depending on that criteria will not be collected. For example, if you do not specify a PO Category 1, rules where PO Category 1 is one of the Who criteria will be ignored.
Where
Where
selections  are based on dimensions setup in the
Where grid
.
Filter Report
The report may be filtered, for example filter on PurchasePriceApplied to only report records where the customer receives a Purchase price from a Rule.

---

## PP Price List Designer - Users tab

Source: https://accredo.co.nz/webhelp/PPPriceList_Users.htm

PP Price List Designer - Users tab
Navigator > Reports > Purchase Pricing > Price List Designer > Users tab
Reports are available to all users with permissions by default. You can enter a list of Users or Groups to make the report available to only the users listed.
See also
PP Price List Designer
.
User
The User, Group or Role. Enter the code or select from the drop-down menu.
Name
The User, Group or Role Name for the
User
code. Read-only.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a user row.
Delete
(F3)
Delete the user row.

---

## PP Price Query

Source: https://accredo.co.nz/webhelp/PPPriceQuery.htm

PP Price Query
Navigator > Maintain > Purchase Pricing > Price Query
View Purchase Pricing results for a Creditor. PP Price Query also opens when you select
Purchase Pricing Information
(Ctrl+S)
from PO Order lines or AP Shipment lines. This is useful for:
Testing the results of a new rule.
Querying the results of a rule applied during document entry.
Note:
Where
criteria are only available in Accredo Saturn.
Who, What, Where Details sections
Enter data to base a query on. When you select
Purchase Pricing Information
(Ctrl+S)
, the fields populate data from the document, and you can view
Pricing Results
.
Who
The Creditor Code and any other Who criteria are shown. Creditor must be specified to obtain a result when you click
Query
(F9). Other fields available in the Who section are based on dimensions in the
Who grid
.
When you select a Creditor,
Who
criteria populates from the Creditor (for example, Creditor Group, AP Category).
If Purchase Order dimensions are available (for example, PO Category), select the relevant criteria as these are independent of the Creditor.
What
Select a Product code to obtain a result for the query. Other fields available in the
What
section are based on the dimensions in the
What grid
. When you select a product, Accredo populates the remaining
What
criteria with information from the product (for example, Stock Group, IC Category).
Where
Fields available are based on dimensions in the
Where grid
. If Where dimensions are available, (i.e., Branch, Department or Location), select the criteria as these are independent of the Creditor and Product records. You can leave
Where
fields blank if the details are not relevant to the query.
Details
You can leave one or more fields blank if the details are not relevant to the query.
If
UOM
is
Active
or
Pending
, and the Product has one or more UOMs, you can select
UOM Code
, and
UOM Quantity,
and view the
UOM Multiplier
for the Product, if you use Quantity Breaks. The UOM Code defaults to the Product
Default Purchase UOM
.
Quantity
- enter the number of items to query if you use Quantity Breaks.
Date
- enter the date to query if you use Start and End dates for Purchase Pricing.
Currency
- Read-only, based on the Creditor details.
Rate Type
and
Exchange Rate
- for Base Currency, these are Read Only. For Foreign Currencies, you can select the Rate Type and Exchange Rate.
Pricing Results Fields >
Query
(F9)
Click
Query
(F9)
to show the PP prices. The Pricing Script set in
PP Settings
will be executed. Pricing Scripts can be edited in the
PP Pricing Script Editor
.
Pricing Results grid fields are:
Initial:
Cost / UOM Cost
Discount %
Cost Bs /
UOM Cost Bs
When a Creditor and a Product code are entered, shows:
The Cost Price and Discount for the selected Creditor for the selected product.
These are the initial prices before the Purchase pricing is applied. If
UOM
is
Active
or
Pending
, the UOM figures are shown.
Purchase:
Cost / UOM Cost
Discount %
Cost Bs /
UOM Cost Bs
This shows the "winning" Purchase prices that will be applied. The fields show the Purchase Cost Price and Discount if the result rule shown in the Rules grid was applied.
If
UOM
is
Active
or
Pending
, the UOM figures are shown.
Pricing Results Grid Toolbar
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
Rules Grid
Shows all prices considered for the pricing decision, including the initial price, ranked according to priorities applied by the PP Script. The result rule is at the top of the list of active rules. The initial price is in the list and does not have a Rule ID.
For information on the fields, see
PP Rule
.
If a rule is dimmed and there is a tick in the
Disallow
field, it has been disallowed by the pricing script. Disallowed rules can appear above the result rule in the list, depending on their ranking.
Rules returning zero cost are disallowed unless Bypass Zero Cost is selected for the rule.
Message
Shows as a status hint when the rule is applied during document or transaction entry.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens
PP Rule
showing the selected rule. The rule can be edited.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## PP Reports - Add Layout

Source: https://accredo.co.nz/webhelp/PPReports.htm

PP Reports - Add Layout
Navigator > Reports > Purchase Pricing > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Rule List
List the Purchase Pricing rules setup in
PP Rule
. Select options to filter by rule types, dates or Reference.

---

## PP Rule

Source: https://accredo.co.nz/webhelp/PPRuleMaintenance.htm

PP Rule
Navigator > Maintain > Purchase Pricing > Select Rules >
Run
(F9)
See also
PP Rule - Rules & Breaks grids
.
Criteria entered in
PP Select Rules
will display in the Header, and rules matching the criteria will load in the Rules grid.
Click to change the defaults, showing or hiding rows in the
Rules grid.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Add or edit rules shown in the Rules grid.
Duplicate
(Shift+F4)
Duplicate rules in the Rules grid to edit and save. For example, you can use this to add similar Purchase Pricing for Creditors who are not part of a group.
Delete All Rules
(F3)
Delete all rules shown in the Rules grid. You will be prompted to take a backup before running this option, as this cannot be reversed.
Alternatively, to retain a record of unused rules, you can set rules to
Inactive
(see below).
Inactivate Rules with Inactive Criteria
Set all rules in the grid with inactive or invalid criteria to Inactive.
Saving Active rules that include Inactive criteria will result in an error hint, 'Active rule has Inactive criteria'. This option may be selected to deal with all affected rules in the grid.
Delete Rules with Inactive Criteria
Delete all rules in the grid with inactive or invalid criteria. Deleted rules are not retained.
Saving Active rules that include Inactive criteria will result in an error hint, 'Active rule has Inactive criteria'. This option may be selected to deal with all affected rules in the grid.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Selections
Set defaults for new rules added in the Rules grid.
Note:
Where
criteria is only available in Accredo Saturn.
Who
What
Where
Setup criteria to add rules to the Rules grid. You can select a
Type
in the left box and a
Code
in the centre box. When a code is selected, the
Name
is displayed in the right box. Available Types are set in the
Who, What, Where grids
.
For example, to setup rules for a:
Creditor -
specify a
Who
Type
of
Creditor
, select the Creditor
Code
,
specify a
What
Type
in the Header, then select individual
What
Codes
in the grid.
Product -
specify a
Who Type
, specify a
What
Type
of
Product
, select the Product
Code
, then select the individual
Who Codes
in the grid.
If you select a
Product
, the
UOM Code
will default to the Base UOM for the Product, and will default the
UOM Multiplier
to
1
.
If Who and What Criteria Counts are set to
1
in
PP Settings
, one pair of fields is available; if set to
2
, a second pair of fields will be available.
Where fields are only shown if Where types are made available in the
PP Where grid
.
Start Date
End Date
You can set a
Start
date, an
End
date, both or neither.
Reference
Reference field for the rule. This can be used to search on in
PP Select Rules
. You can use this to filter when loading rules or to identify new rules. For example, you could enter
Contract
in this field for contract pricing rules.
Comment
Add up to 60 characters, use a filter in PP Select Rules to select rules by comment.
Rule Type
Select the rule type from:
Fixed
- Purchase Price = the Amount and Discount percentage.
Cost Relative
- Purchase Price = Cost Price less the Amount and / or the Discount Percentage. If both an Amount and Discount Percentage are entered, the Amount is subtracted first, then the Discount Percentage is applied.
This defaults from
PP Settings
.
Base Cost
Select the Base Cost to use when calculating a Cost Relative price.
Cost Relative rules rely on a
Supplier Cost
record existing and use either
Supplier Standard Cost
or
Supplier Cost
depending on the
Cost Basis
specified on the
Creditor
record.
If a Supplier Cost record is not found the rule will be Disallowed when the pricing decision is made.
Select from:
Cost -
use the base Cost without Discount
Discounted Cost
- use the base Cost after Discount
This defaults from
PP Settings
.
Priority
Determines priority if more than one rule applies to a transaction line.
1
is highest priority,
9
is lowest. Default is set to the highest priority from Who, What, Where criteria selected in the Header. If two or more rules share the same priority, the lowest price applies. You can modify this by creating a script based on the default (PPDefault.pfs) in
PP Script Editor
. If a priority is not set and the lowest price must apply, leave the priority for all rules set to
9.
Hint: You can reserve priority
1
for a rule to override all others (for example, contract pricing, when no other discounts or Purchases apply).
Inactive
Selected,
all rules in the grid will be inactive.
Clear,
(default) new rules added in the grid will be active.
You can set rules to
Inactive
individually in the
Rules grid
.
Show / Hide field
(Ctrl+H)
Toggle between showing and hiding the adjacent field in the Rules grid.
Apply to all
(Ctrl+A)
Apply criteria in the adjacent fields to the Rules grid. This will override existing values in the grid.
For example, you can use this to:
Make a group of Active rules Inactive, or make a group of Inactive rules active.
Change the
End date
for a group of rules.
Populate grid
(Ctrl+G)
Opens the
PP Populate Selection
form. The grid will be populated with one new line for each Code specified. Use the
From
and
To
fields to select a range of Codes, or use the
Filter
(F2)
button to select Codes.
For example, you can use this to enter a Purchase Price for:
A number of different Products that are not part of a group.
Buttons
Print
(Ctrl+P)
Print a PP Rule Edit report of the information in the grid(s).
Save
(F9)
Save changes to the rules.
Cancel
(Esc)
Cancel the edit without saving changes.
Rules and Breaks grids
See
PP Rule - Rules & Breaks grids
.
In This Section
PP Rule - Rules & Breaks grids
PP Populate Selection

---

## PP Rule - Rules & Breaks grids

Source: https://accredo.co.nz/webhelp/PurchasePricingRules_Grid.htm

PP Rule - Rules & Breaks grids
Navigator > Maintain > Purchase Pricing > Select Rules >
Run
> Rules & Breaks grids
See also
PP Rule
.
Rules will match the criteria selected from
PP Select Rules
. New rules added during the session are also shown. If you setup
Quantity Breaks
in
PP Settings
the grid opens with quantity breaks relating to the selected rule.
Note:
Where
criteria is only available in Accredo Saturn.
Rules grid
Who
What
Where
These fields are determined by the
Show in grid
buttons in the Header. Other fields can be customised in or out of the grid.
Where fields are only available if Where types are made available in the
SP Where grid
.
Rule Type
Select the Rule Type from:
Fixed -
Purchase Price = the Amount and Discount percentage.
Cost Relative -
Purchase Price = Cost Price less the Amount or the Discount Percentage. If both an Amount and Discount Percentage are entered, the Amount is subtracted first, then the Discount Percentage is applied.
Default values are set in
PP Settings
.
Note: A Cost Relative Rule must have either an Amount or a Percentage specified to be saved.
Base Cost
Select the default Base Cost when creating a Cost Relative rule.
Cost Relative rules rely on a
Supplier Cost
record existing and use either
Supplier Standard Cost
and
Supplier Standard Discount
or
Supplier Cost
and
Supplier Discount
depending on the
Cost Basis
specified on the
Creditor
record.
If a Supplier Cost record is not found the rule will be Disallowed when the pricing decision is made.
Select the default from:
Cost -
use the base Cost without Discount
Discounted Cost
- use the base Cost after Discount
Default values are set in
PP Settings
.
Bypass Zero Cost
Selected,
for a Cost Relative rule a 100% discount will not be disallowed.
Currency
The currency the rule is applied in.
Amount / Percentage
The amount or percentage applied. The table shows the results of a selection based on Rule Type.
Rule Type
Amount
Percentage
Fixed
Enter the Purchase Price. If Amount is
blank,
the usual price is used.
Enter the percentage (Discount) to deduct from the Purchase price in the Amount field. For a Product giveaway, leave the Amount field blank, enter 100% in this field.
Cost Relative
Enter the Amount (Discount) to subtract from the specified Cost Price.
Enter the Percentage (Discount) to deduct from the Cost Price. If an Amount and Percentage are entered, the amount is subtracted first, then the discount percentage applied.
When Quantity Breaks is selected, and rows are added to the Breaks Grid, the Amount and Percentage fields will be unavailable. Enter Amounts and Percentages in the Breaks Grid.
Effective Price
The Price the specified Creditor will charge for the specified Product from the specified Branch, Department or Location (Accredo Saturn Only). This is calculated by applying the Rule Type, Amount and Percentage. This will only be calculated if the rule includes a Product Code.
If you use Quantity Breaks (set in
PP Settings
), this field is also available on the Breaks grid.
Hint: you can compare this with the standard Supplier Effective Cost in the Information Panel, see below.
Start / End Date / Priority / Inactive / Reference / Comment
When adding rules the defaults for these fields are based on the content of the corresponding field in the Header. You can change each field, or
Apply to all
to apply the Header contents to all rules in the grid.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Opens the selected rule in Form view.
Insert
(F4)
Adds a new rule at the selected line.
Delete
(F3)
Deletes the selected rule.
Filter / Sort List
(Ctrl+F2)
Clear Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Note: If filter is applied while editing, bulk changes and Save applies to all loaded rules including any excluded from view by the filter.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Move to Breaks
(Ctrl+ Down)
Move focus to the
Breaks grid
. This is available if you use Quantity Breaks (set in
PP Settings
).
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Information panel
Where a Product has been selected, the initial cost and discount for the Product and Creditor are shown. You can compare Purchase Pricing entered with initial prices.
Cost
The current initial cost of the specified Product for the Creditor.
Discount
The current initial discount of the specified Product for the Creditor.
Effective Price
The initial cost after discount the specified Creditor would charge for the specified Product.
Currency
The currency for the price.
Breaks grid
This displays when
Quantity Breaks
is selected in
PP Settings
.
You can apply different prices for a single rule using Quantity breaks, depending on the quantity of items purchased. The Breaks grid shows quantity breaks for the rule row selected (highlighted) in the Rules grid.
Set different pricing breaks based on Quantity, using the Amount and Percentage fields.
UOM Code
(
UOM
Active or Pending)
The UOM Code for the Product that must be used to qualify for the Purchase price. If a UOM Code is entered for a Break, UOM Codes must be entered for all Breaks for the Rule.
Warning: Only enter a
UOM Code
if you want the Break to apply only when that
UOM Code
is specified on the line. If you want a Break to apply based on quantities, regardless of the UOM Code, leave this field blank.
Min Quantity
The minimum number of Products which must be purchased to qualify for the Purchase price.
Hint: If only one quantity break is required, customise the Min Quantity field into the Rules grid, to work in one grid rather than two.
Amount / Percentage / Effective Price
Once quantity breaks are entered for a rule the Amount, Percentage, Effective Price and Effective Margin fields on the Rules grid will be unavailable; you can add these using the Breaks grid.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Add a new line to the grid, for a new quantity break.
Delete
(F3)
Adds a new quantity break at the selected line.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Move to Rule
(Ctrl+Up)
Move focus to the
Rules grid.

---

## PP Rule Form

Source: https://accredo.co.nz/webhelp/PPRuleForn.htm

PP Rule Form
Navigator > Setup > Purchase Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
>
Insert
(F4)
- OR -
Navigator > Setup > Purchase Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
> [Select Rule] >
Open
(F12)
or Double-Click - OR -
Navigator > Maintain > Purchase Pricing > [Saved Rule List] >
Insert
(F4)
- OR -
Navigator > Maintain > Purchase Pricing > [Saved Rule List] >
Open
(F12)
or Double-Click
Opens a Purchase Pricing Rule in the Rule Form.
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
Add a new rule.
Duplicate
(Shift+F4)
Create a new rule duplicating the current rule.
Delete
(F3)
Deletes the current rule.
Information panel
The standard prices for the Product are shown, where a Product has been selected. You can compare Purchase Pricing entered with standard prices.
Cost
The current valuation cost of the specified Product.
Discount
The standard discount that applies to the specified Product if a Creditor is specified.
Effective Price
The standard price the specified Creditor would pay for the specified Product.
Effective Margin
The standard profit margin for the Product.
Breaks grid
This displays When
Quantity Breaks
is selected in
PP Settings
.
You can apply different prices for a single rule using Quantity breaks, depending on the quantity of items sold. The Breaks grid shows quantity breaks for the rule selected in the Rules grid.
Set different pricing breaks based on Quantity, using the Amount and Percentage fields.
Min Quantity
The minimum number of Products which must be purchased to qualify for the Purchase price.
Amount / Currency / Percentage / Effective Price / Effective Margin
Once quantity breaks are entered for a rule, enter Amounts in the Breaks grid.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Add a new line to the grid, for a new quantity break.
Delete
(F3)
Deletes the selected quantity break.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.

---

## PP Rule List

Source: https://accredo.co.nz/webhelp/PPRuleList_Form.htm

PP Rule List
Navigator > Maintain > Purchase Pricing > Rule List
Select criteria to view rules for, or leave the
Who
,
What, Where
and
When
fields blank to select all rules.
Note:
Where
criteria is only available for Accredo Saturn.
Click
to make selections, and use the
lookup
.
Double click a Rule or press
F12
to open the Rule in
PP Rule
where it may be edited.
Selections
Who, What, Where
You can have 1 or 2
Who
and
What
criteria rows, set in
PP Settings
.
Select from Types set in the
Who, What, Where grids
, or leave blank to select all rules.
Where fields are only shown if Where types are made available in the
PP Where grid
.
When
Start and End dates apply a rule for a limited time, (for example, weekly or monthly Promotions). Specify the start and end dates to show rules for, or leave blank to show all rules.
Reference
Enter a reference to filter the rules shown by reference.
Note: Rules may be filtered further using the Filter button on the Rules grid.
Include Rules
Select the rules to display.
Active
- Active rules are shown.
Inactive
- Inactive rules are shown.
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
selections, filters and sorts are not automatically applied.
The default value is set in
PP Settings
.
Select Rules
(F9)
Click to apply selections, filters and sorts to the list.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Open
PP Rule
to insert a new Rule, with selections defaulted to match the Rule List selections.
Delete
(F3)
Delete the selected Rule.
Deactivate
(Alt+D)
Make the selected Active Rule Inactive.
Activate
(Alt+A)
Make the selected Inactive Rule Active.
Open
(F12)
Opens
PP Rule
showing the selected rule. The rule can be edited.
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
Create List View
(Alt+L)
Save the current list state as a
List View
.
Find
(Ctrl+F)
Find
a rule using the Rule ID.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the list. Click
to refresh the total number.

---

## PP Rule List - Designed

Source: https://accredo.co.nz/webhelp/PPRuleList_Designed.htm

PP Rule List - Designed
Navigator > Setup > Purchase Pricing > Rule List Designer >
Run
(F9)
Make selections in the PP Rule List Designer tabs then click
Run
, to view Purchase pricing rules matching the criteria. Selections available are dependent on options set in
PP Rule List Designer
for the rule list. Only rules matching the selections are displayed.
To view saved rule lists, go to:
Navigator > Setup > Purchase Pricing > Rule List Designer > Load > [Select Rule List file] >
Run
(F9)
- OR -
Navigator > Maintain > Purchase Pricing > [Saved Rule List]
Start Date
End Date
Select dates to limit rules.
Display Inactive
Inactive records are usually hidden from view with financial information and history retained for reporting.
Selected,
Inactive records are shown.
Clear,
Inactive records are hidden from view.
Auto Select
Selected,
selections, filters and sorts will be immediately applied to the list.
Clear,
click
Select Rules
to apply selections, filters and sorts to the list.
Select Rules
(F9)
Apply selections, filters and sorts to the list.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Add a new rule using
PP Rule Form
.
Delete
(F3)
Deletes the selected rule.
Open
(F12)
Open to view and edit, or double click to view and edit a Rule. Displays the rule in
PP Rule Form
.
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
, you can customise the columns in the grid.
Note: Customisations are not available until the rule list has been saved.
Refresh List
(F5)
Updates rules listed with changes made by other users or in other forms.
Delete All
Deletes all rules displayed.
Batch Update
Opens
Batch Update
selections to make changes to all the Rules in the Rule List.
Batch Duplicate
Opens
Batch Duplicate
selections to duplicate to all the Rules in the Rule List.
In This Section
PP Rule Form
PP Batch Update
PP Batch Duplicate

---

## PP Rule List Designer

Source: https://accredo.co.nz/webhelp/PPRuleDesigner.htm

PP Rule List Designer
Navigator > Setup > Purchase Pricing > PP Rule List Designer
Use the PP Rule List Designer to create lists of PP Rules, and add and maintain PP Rules. You can use PP Lists to maintain sets of Purchase Pricing rules. You can save the lists as definition files, then add them to the Navigator for viewing.
Note:
Where
criteria is only available in Accredo Saturn.
See also the
PP Tutorial: Manage PP Rules
.
Definition tab
Rule
Select a
Type
for the rules.
For
Cost Relative
rules, select a
Base Cost
for the rules.
Who, What, Where
Select criteria for the rules.
List Maintenance Title
The caption for the Purchase Pricing List.
Allow Zero Cost
Selected
, can be selected when editing and inserting rules.
Auto Select Rules
Selected
, selection changes and Filter & Sorts will apply immediately.
Clear,
selection changes and Filter & Sorts will apply by clicking Select Rules after selections have been made.
Comment
Optionally annotate the rule list definition.
Selections tab
Who, What, Where
Selections will appear in the Rule List once Criteria have been selected. If you lock a selection (From Code / To Code must be the same or Code specified for a single selection) it will not appear when the list is Run, only rules for the specified code can load, be edited or inserted.
Click the
Lock Selection
button to lock the selected range. The button changes to
, the field will not appear when the rule list is run, and only rules for the selection can be inserted. Click the button again to unlock the selection.
Details
Specify values that match rules to load in the list and become defaults for rules inserted from the Rule List.
Select
Start Date Required
and
End Date Required
to require start date and end date to be set when new rules are created from the list.
The
Disallow Selection
button beside a field means the selection will be excluded from the Rule List and cannot be edited. Click the button to show a
, to allow the selection to be edited from the rule list.
If
Priority
is left
Clear
any rules added from the list will default to priority 9.
Buttons
Add to Navigator
(Alt+N)
This becomes available when a Rule List definition has been saved. The default location for Rule Lists is Navigator > Maintain > Purchase Pricing > [List Maintenance Title].
Run
(Alt+R)
Runs the designed
PP Rule List
and confirms the rules load as expected.
Load...
(Alt+L)
Load an existing Rule List from file.
Save...
(Ctrl+S)
Saves the Rule List definition. The default file location is:
AccredoSaturn\Forms\PPRule
AccredoMercury\Forms\PPRule
In This Section
PP Rule List - Designed

---

## PP Select Rules

Source: https://accredo.co.nz/webhelp/PPRuleSelection.htm

PP Select Rules
Navigator > Maintain > Purchase Pricing > Select Rules
Select criteria to view rules for, or leave the
Who
,
What, Where
and
When
fields blank to show all rules. Rules will be shown in
PP Rule
.
Note:
Where
criteria is only available for Accredo Saturn.
Who, What, Where
You can have 1 or 2
Who
and
What
criteria rows, set in
PP Settings
.
Select from Types set in the
Who, What, Where grids
, or leave blank to show all rules.
Where fields are only shown if Where types are made available in the
SP Where grid
.
If you...
Select a Type only...
Accredo will load rules with that Type specified. Rules without a value for that Type will not be shown.
Select a Type and a Code...
Accredo will only load rules that have that particular Code for the Type.
Select Type "
None
"...
Accredo will load rules without this Type specified.
Leave the Type and Code blank...
Accredo will load rules based on other dimensions (
Who
,
What,
Where
,
When
), disregarding this dimension. The Who 1 and What 1 name will be shown.
When
Start and End dates apply a rule for a limited time, (for example, weekly, monthly Purchases). Specify the start and end dates to show rules for, or leave blank to show all rules.
Selections and buttons
Reference
When entered, returns Rules with a matching Reference. For example, enter "
Contract
" in the Reference field for contract pricing rules.
Include Rules
Select the rules to load. Clearing both selections will open the PP Rule form with no rules loaded if you are entering new rules rather than editing existing ones.
You can load Inactive rules to base new rules on, reinstate later, or to maintain a Purchase Pricing history.
Filter / Sort Rule
(Ctrl+F2)
Clear Rule Filter / Sort
(Ctrl+F3)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Run
(F9)
Apply and load selections in
PP Rule
.
In This Section
PP Rule

---

## PP Settings

Source: https://accredo.co.nz/webhelp/PPSettings.htm

PP Settings
Navigator > Setup > Purchase Pricing > Settings
Select to turn Purchase Pricing on or off and set defaults.
Apply Purchase Pricing
Selected
, makes Purchase Pricing active in PO and AP. You can leave Purchase Pricing inactive, setup rules, then make it active when the rules are entered and tested. See
How Purchase Pricing works
for more detail.
The default is inactive (
Clear
).
Default Rule Type
Specify the default Rule Type to appear in
PP Rule
:
Fixed -
Purchase Price = the Amount and Discount percentage.
Cost Relative -
Purchase Price = Cost Price less the Amount and / or the Discount Percentage. If both an Amount and Discount Percentage are entered, the Amount is subtracted first, then the Discount Percentage is applied.
Default Base Cost
Select the default Base Cost when creating a Cost Relative rule.
Cost Relative rules rely on a
Supplier Cost
record existing and use either
Supplier Standard Cost
and
Supplier Standard Discount
or
Supplier Cost
and
Supplier Discount
depending on the
Cost Basis
specified on the
Creditor
record.
If a Supplier Cost record is not found the rule will be Disallowed when the pricing decision is made.
Select the default from:
Cost -
use the base Cost without Discount
Discounted Cost
- use the base Cost after Discount
Who Criteria Count
The maximum number of Who criteria to apply to PP rules. Set the smallest number to reduce the amount of processing required for a rule.
1
(default) is usually adequate. Select up to
2
Who criteria, for example, to apply rules to Creditors in a Buying group when a specific PO Category is selected.
What Criteria Count
The maximum number of What criteria to apply to PP rules. Set the smallest number to reduce the amount of processing required for a rule.
1
(default) is usually adequate. Select up to
2
What criteria, for example, to apply rules to Products in a Stock Group and with a specific IC Category.
Use Quantity Breaks
Selected
, displays the Breaks grid in
PP Rule
and
PP Rule Form
. If Quantity Breaks are used you can specify different prices for a single rule depending on the quantity of items purchased. If Quantity Breaks are not used you can specify a Purchase Price for each rule regardless of the quantity of items sold.
Allow Inactive Criteria
Selected,
allows inactive Criteria codes for Active Rules when saving Purchase Pricing rules.
Unselected
, saving an Active Rule with Inactive Criteria is prevented.
Note: Since Rules with Inactive Criteria will never be collected, it is recommended that this should be Unselected after any Rules with Inactive Criteria are identified and
Inactivated
.
Pricing Script
Select the definition file for the Purchase Pricing script to determine how it is collected, ranked and applied.
The default Pricing Script is
PPDefault.pfs
. This ranks rules by priority, and chooses the lowest price. Use
PP Script Editor
to edit a script or create a custom definition.
To add a Bill To Creditor to the Who grid, use the provided script
PPDefaultWithBillTo.pfs
.
Auto Select
PP Tracking Log
PP Rule List
Selected,
Auto Select for the list is selected by default.
Clear
, Auto Select is unselected for the list. This is recommended where there is a large number of records or the network is slow.
Buttons
Edit
(F11)
Enter edit mode.
Save
(F9)
Save changes.
Cancel
(Esc)
Discard changes.

---

## PP Tutorial: Manage PP Rules

Source: https://accredo.co.nz/webhelp/PPTutorialManagePPRules.htm

PP Tutorial: Manage PP Rules
This tutorial will show you how to manage your Purchase Pricing rules using Rule Definitions, which can be added to the Navigator for easy viewing and maintenance. This tutorial can be run on the Accredo Demo data. It will create a simple PP Rule Definition for contract pricing for the Creditor RIGHT.
Note:
Where
criteria is only available in Accredo Saturn.
Go to Navigator > Setup > Purchase Pricing > Rule List Designer.
Set the
Who Type 1
as
Creditor
, and the
What Type 1
as
Product
.
Note: You can select which fields to make available for PP Rules from the
PP Who, What Where Grids
.
Enter a
List Maintenance Title
, such as
Right Contract Sept
.
Click to
Select
Auto Select Rules
, so the rules will be automatically be selected when the definition is run.
Go to the Selections tab.
In the Who panel, select
RIGHT
in the Creditor
From
and
To
fields, to only apply the pricing to this Creditor.
Leave the What pane clear to select all Products associated with
RIGHT
.
In the Details panel, click the
Allow / Disallow Selection
button beside Reference. This means the Reference field will be available at run time. Enter a
Reference
such as
Contract
.
Click
Run
(
Alt+R
). Any rules that meet the criteria on the Selections tab will be shown in the PP Rule List.
To add a new rule, click
Insert
(
F4
). The
PP Rule form
will open.
Enter a
Start Date
and
End Date
for when the Rule will be applied, such as
1 Sept
to
30 Sept
.
In the Breaks section, enter an Amount as the Purchase price to be applied for this Product for this Creditor between the dates entered above, such as
$800.00
. If you want to use Quantity Breaks, add another line, and enter a
Min Quantity
and another
Amount
.
Click
Save
(
F9
) to save the Rule.
You can add another pricing rule. Click
Duplicate
(
Shift+F4
) to duplicate this rule and use it as a starting point.
Change the
Product
, for example to
BEDCABINET
. Change the
Amount
, such as to
$300.00
.
Click
Save
(
F9
) to save the Rule.
You can continue adding rules for more products. When you have finished, close the PP Rule window.
The new rules are shown in the PP Rule List window. Close the PP Rule List window.
In the PP Rule List Designer, click
Save...
(
Ctrl+S
) to save the Rule Definition File. Enter a file name, such as
Right Contract Sept
.
Click
Add to Navigator...
(
Alt+N
).
The Script Shortcut Editor window opens. By default the Rule List is added to the Navigator under Maintain > Purchase Pricing. Click
Save
(
F9
).
Close the PP Rule List Designer window.
Go to Navigator > Maintain > Purchase Pricing >  Your Rule List will be available. Select your Rule List. It will open in PP Rule List.
You can use this to add and review Rules and to make any changes.

---

## PP Who, What, Where grids

Source: https://accredo.co.nz/webhelp/PPWhoWhatWhere.htm

PP Who, What, Where grids
Navigator > Setup > Purchase Pricing > Who, What, Where grids
Setup the Types of criteria available in setting Purchase Pricing rules in the Who, What, Where dimensions. For example, Purchase Pricing typically relates to products for specific Creditors, make
Creditor
criteria available in the
Who
dimension and
Product
criteria available in the
What
dimension. You can turn criteria off and on as needed.
Some criteria are determined by others, for example, when you select a Creditor in the
Who
dimension, the Creditor Group is determined by the Creditor record. Other criteria such as Purchase Order Categories are independent of the Creditor record and are not affected, as they relate to the order or shipment.
Note:
Where
criteria is only available in Accredo Saturn.
Specify criteria and priority for the following Purchase Pricing dimensions:
Who grid
Select Creditor or document criteria to specify rules for.
What grid
Select product-related criteria to specify rules for.
Where grid
Select branch, location or department criteria to specify rules for.
Note: If no Where criteria are made available, the Where fields will not be shown in PP Select Rules and PP Rule.
Fields
Type
Lists the available criteria Types, that can be selected when setting Purchase Pricing rules.
Available
Only Available criteria Types will be available when setting Purchase Pricing rules in
PP Rule
.
We recommend you enable only the PP Criteria you need in order to add the rules you require.
Default Priority
Setup criteria Priority to determine which rule takes precedence if more than one rule applies to a document line. For example, you can make rules relating to Contract pricing a higher priority.
1
is the highest priority,
9
lowest. Priorities can be changed from their defaults in
PP Rule
.
If two or more rules are tied at the same priority, the lowest price is applied (default). You can modify this by creating a script based on the default in
PP Pricing Script Editor
. To apply the lowest price, set the Priority for all rules to
9.
Show Name
Selected
, the
Name
or
Description
field will appear beside the
Record Code
field on the Rules grid in
PP Rule
. This is useful for providing information to select the correct record.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
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
Reload changes other Users may have made.

---

## Purchase Orders

Source: https://accredo.co.nz/webhelp/PurchaseOrders.htm

Purchase Orders
Accounts Payable (AP) must be installed for Purchase Orders (PO). Stock-on-order figures are updated when a Purchase Order is saved. You can:
Enter purchase orders, using AP Creditor Codes and IC Product codes.
Print purchase orders.
Enter and print quote requests that can be accepted as purchase orders.
Track outstanding purchase orders.
Retain a history of purchase orders that can be accessed for query, reprinting and for
Purchase Analysis
.
Produce reports that include tracking quantity and value variations from the original purchase order.

---

## Purchase Orders - Maintain

Source: https://accredo.co.nz/webhelp/PurchaseOrders_Maintain.htm

Purchase Orders - Maintain
Navigator > Maintain > Purchase Orders
In This Section
PO Order List
PO Categories
PO Memo List
PO Link List

---

## Purchase Orders - Reports

Source: https://accredo.co.nz/webhelp/POReports.htm

Purchase Orders - Reports
Navigator > Reports > Purchase Orders
Report categories include:
Order Reports
Print Purchase Orders
Print Quote requests
Order Labels
Print Purchase Order labels using
Label Designer
. The Report File Name specifies the file that defines the label design layout. See
Document Defaults
to set a default report file name.
Number of label copies
- you can specify the number of copies you want for each label. For details on how to design labels that print different information on different copies, see the Label Designer.
Start from label
- typically on sheet feed labels, you can start printing at a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.
Order Totals Report
Reports on totals (excluding GST) of purchase orders and quote requests entered but not yet complete. Separate totals are shown for Unprocessed and Held Open.
In This Section
PO Order Reports - Add Layout
PO Memo Reports - Add Layout
PO Print Purchase Orders
PO Print Quotation Requests
PO Email Purchase Orders
PO Order Labels

---

## Purchase Orders - Setup

Source: https://accredo.co.nz/webhelp/PurchaseOrders_Setup.htm

Purchase Orders - Setup
Navigator > Setup > Purchase Orders > Settings
Maintain the fields that determine default settings for purchase orders, setting next computer supplied Purchase Order and quote request numbers. You can specify settings to determine the way PO operates. See also
Company Setup
and
AP Settings - Shipments tab
.
In This Section
PO Settings - General tab
PO Change Tracking Log
PO Authorisation Codes
PO Purchase Order Designer
PO Label Designer
PO Memo Designer
PO Purchase Order Email Designer

---

## Purchase Orders - Tasks

Source: https://accredo.co.nz/webhelp/PurchaseOrders_Tasks.htm

Purchase Orders - Tasks
Navigator > Tasks > Purchase Orders
In This Section
PO Enter Purchase Orders
PO Enter Memos
PO Reprice Purchase Orders
PO Revalue Foreign Orders

---

