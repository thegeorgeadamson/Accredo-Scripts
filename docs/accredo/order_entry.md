# Order Entry (OE)

> Sales orders, back orders, order confirmation, picking, packing

**Sections:** 45

---

## Quick Reference

- [OE Change Tracking Log](#oe-change-tracking-log)
- [OE Email Confirmations](#oe-email-confirmations)
- [OE Email Confirmations Results](#oe-email-confirmations-results)
- [OE Enter Memos](#oe-enter-memos)
- [OE Enter Sales Orders](#oe-enter-sales-orders)
- [OE Find Document by Order No](#oe-find-document-by-order-no)
- [OE Find Packing Slip Number](#oe-find-packing-slip-number)
- [OE Fulfill Back Orders](#oe-fulfill-back-orders)
- [OE Fulfill Back Orders Query](#oe-fulfill-back-orders-query)
- [OE Fulfill Back Orders Results](#oe-fulfill-back-orders-results)
- [OE Insufficient Query](#oe-insufficient-query)
- [OE Label Designer](#oe-label-designer)
- [OE Link List](#oe-link-list)
- [OE Memo Designer](#oe-memo-designer)
- [OE Memo List](#oe-memo-list)
- [OE Memo Reports - Add Layout](#oe-memo-reports---add-layout)
- [OE Order Labels](#oe-order-labels)
- [OE Order Line Fields](#oe-order-line-fields)
- [OE Order Reports - Add Layout](#oe-order-reports---add-layout)
- [OE Packing Slip Designer](#oe-packing-slip-designer)
- [OE Packing Slip/Confirmation Email Designer](#oe-packing-slip-confirmation-email-designer)
- [OE Print Confirmations](#oe-print-confirmations)
- [OE Print Packing Slips](#oe-print-packing-slips)
- [OE Report Period](#oe-report-period)
- [OE Reprice Sales Orders](#oe-reprice-sales-orders)
- [OE Reprice Sales Orders Results](#oe-reprice-sales-orders-results)
- [OE Revalue Foreign Orders](#oe-revalue-foreign-orders)
- [OE Revalue Foreign Orders Results](#oe-revalue-foreign-orders-results)
- [OE Sales Order List](#oe-sales-order-list)
- [OE Sales Orders - Charges tab](#oe-sales-orders---charges-tab)
- [OE Sales Orders - Header tab](#oe-sales-orders---header-tab)
- [OE Sales Orders - Lines tab](#oe-sales-orders---lines-tab)
- [OE Sales Orders - Links tab](#oe-sales-orders---links-tab)
- [OE Sales Orders - Memos tab](#oe-sales-orders---memos-tab)
- [OE Settings - General tab](#oe-settings---general-tab)
- [OE Settings - Links tab](#oe-settings---links-tab)
- [OE Settings - Memos tab](#oe-settings---memos-tab)
- [OE Settings - Misc tab](#oe-settings---misc-tab)
- [OE View Related Orders](#oe-view-related-orders)
- [OEM](#oem)
- [Order Entry](#order-entry)
- [Order Entry - Maintain](#order-entry---maintain)
- [Order Entry - Reports](#order-entry---reports)
- [Order Entry - Setup](#order-entry---setup)
- [Order Entry - Tasks](#order-entry---tasks)

---

## OE Change Tracking Log

Source: https://accredo.co.nz/webhelp/OrderEntryTrackingLog.htm

OE Change Tracking Log
Navigator > Setup > Order Entry >
Change Tracking Log
See Also
Order Entry - Setup

---

## OE Email Confirmations

Source: https://accredo.co.nz/webhelp/OEEmailConfirmations.htm

OE Email Confirmations
Navigator > Reports > Order Entry > Email Confirmations
You can batch email confirmations from Orders. Confirmations can be emailed individually from Enter Sales Orders. Batch emailing applies only to orders with un-generated invoices. Historic orders cannot be batch emailed. To email a confirmation for a Historic order, go to the
OE Sales Order List
, open the Order, then click
Print Confirmation
.
When an Order is emailed as a confirmation, its print status changes to "Confirmed" from "Unprinted". For batch emailing, by default, orders are printed by Packing Slip number, followed by orders for which packing slip numbers have not been allocated, then by Customer code. Orders that have not been allocated a packing slip number will be allocated the next available computer generated number, prior to printing. Options on the selection screen depend on if you are printing individually or in a batch, see
Report Selections Form
.
Once a Confirmation has been emailed, the Packing Slip (P/Slip) Number and Customer Code on the Order cannot be changed unless
OE Settings
allow.
Confirmation email is only generated for customers with a packing slip email address. If
Email Contact
is selected on the Order, the contact email address is used. An email is created with the confirmation attached.
Selections tab
Options depend on individual or batch, and if the order has been printed previously, see
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
All string fields are enclosed in double quote marks (" ").
Excel XLSX File
Excel XLSX file.
Column and row positions for formats other than pdf are specified explicitly in the Confirmation document design.
Report File Name
Specifies the file that defines the Confirmation layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
OE Packing Slip Designer
.
Customer - From / To
Select a customer or a range of customers to email confirmations for.
Date - From / To
Select range of order dates to email confirmations for.
Print For
Determines the orders and order lines to include. The default value is set in
Settings
.
Full Orders
Include orders when all items for the Order have been supplied in full.
Full Lines
Include only Order lines that have been supplied in full. An Order is included if at least one line has been supplied in full.
All Lines
Include all orders and Order lines, irrespective of whether lines have been supplied in full.
See also
Settings
for an option to print only supplied lines.
Print Status
Select orders based on print status, defaults to
Unprinted.
Up to Period
Select the period to email orders up to.
Branch
Select the Branch.
Clear,
Confirmations will be emailed for all. (Accredo Saturn Only)
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
- One email will be sent per email address. If there is more than one confirmation, each will be a separate attachment.
Customer and Email
- One email will be sent per email address per Customer Code. If there is more than one confirmation, each will be a separate attachment.
The default value is set in
OE Settings Misc tab
.
Consolidate Attachments
Selected
, one attachment if produced for all confirmations on an email.
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
OE Packing Slip/Confirmation Email Designer
.
Attachments tab
You can add one or more attachments to be emailed with each email.
In This Section
OE Email Confirmations Results

---

## OE Email Confirmations Results

Source: https://accredo.co.nz/webhelp/OEEmailOrderResults.htm

OE Email Confirmations Results
Navigator > Reports > Order Entry > Email Confirmations >
Run
Lists emailed orders and those that were not emailed due to error.
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
Total number of orders that were not emailed due to errors.
Gross Errors
Total amount of the orders that were not emailed.
Records
Total number of orders successfully emailed.
Gross Success
Total amount of the orders successfully emailed.

---

## OE Enter Memos

Source: https://accredo.co.nz/webhelp/OEEnterMemos.htm

OE Enter Memos
Navigator > Tasks > Order Entry >
Enter Memos
Defaults for inserting Memos, Alarms and Reminders are set in
OE Settings - Memos tab
.

---

## OE Enter Sales Orders

Source: https://accredo.co.nz/webhelp/OEEnterOrders_Header.htm

OE Enter Sales Orders
Navigator > Tasks > Order Entry > Enter Sales Orders
Enter orders and back-order stock. Print a packing slip, and generate an invoice. Use Standing orders for repeat orders.
See also
OE Sales Orders - Header tab
for fields on the Header tab.
Sales Order Document types
Order
Stock items included are allocated from stock on
Save.
Items can be entered on back-order if there is insufficient stock available. Back-orders can be fulfilled when stock becomes available and an invoice generated from orders.
Standing Order
Use Standing Orders to create templates for Orders. Items are not allocated from stock for Standing Orders. When an Order is duplicated from a Standing Order, items will be allocated from stock or back-ordered.
Hint: To use a Standing Order for many customers, click
Duplicate
(Shift+F4)
and change the Customer code.
Toolbar
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
Select a document type from the drop-down, to create a duplicate document. You can duplicate documents as different types.
Delete
(F3)
Delete the document. Only available for saved, unposted documents, when the user has permission.
Drill down
(Shift+F12)
View the source document, only available if the order is saved and sourced from another document.
Print Packing Slip
(Ctrl+P)
Print as a packing slip. In Edit mode, the Order is saved first. Packing Slips can also be
batch printed
.
Once a Packing Slip has been printed, the
Packing Slip (P/Slip) Number
and
Customer Code
cannot be changed unless
OE Settings
allow.
Print Label
(Ctrl+L)
Print
labels
for the current order. The number of labels defaults to the total of the quantities in the Shippers grid in the
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
View on screen what the printed version of the document will look like. This does not change the print status.
Reprice
(Alt+R)
When details in the Header tab are changed, changes will apply to new Order lines, but not to existing Order lines. Use the
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
to update the order line Description based on the current description for the product. Select
Sales Group
to update the order line Sales Group codes based on the current Sales Group for the product.
If you use
Special Pricing
, select
Selling Price
and
Discount
to include all Special Pricing rules. Re-pricing does not affect
Automatic Kitset
lines, but is applied to all the component lines that comprise the Automatic Kitset.
See also
Reprice Orders
for re-pricing bulk orders.
Delete Nil Lines
(Alt+D)
Available when editing. A line is considered to be nil if the quantity ordered, quantity supplied, quantity back ordered, extended cost and extended amount are zero, that is lines containing just a description are considered to be nil. Often this is used when duplicating a Standing Order, entering quantities supplied, then deleting lines not being supplied.
Mark Historic
(Alt+T)
Available for Standing Orders only.
Changes standing order from current to history. The Post Status is changed to Processed. The Standing Orders can be viewed in
OE Sales Order List
when you select
History
documents.
Orders move to history when printed and posted or deleted.
Refresh Weight and Volume
(Alt+W)
If the weight and / or volume of a Product changes, existing lines on orders are not automatically updated. Click
Refresh Weight and Volume
to re-calculate weight and volume from current Product Weight and Volume figures for all lines.
Print Product Labels
(Alt+U)
Print
IC Product Batch Labels
for Diminishing products, manual kitsets and Supplied quantities (rounded up to nearest whole number). Product Label design is set in
Document Defaults
.
Recalculate Supply
(Alt+C)
Recalculates Ordered, Supply and Back Order figures for all lines on the order as if the Order Quantities were re-entered.
Generate Invoice
(Alt+N)
Available for Orders only.
Saves the order and generates an invoice, see
Generate Invoices
for batch generating. This is useful when entering an order where some stock can be supplied and some is on back order and you want to invoice immediately for available stock.
If you are generating invoices per customer or order,
OE Select Invoice
opens if there are saved unposted invoices that can be appended to. This is determined by
OE Setting
for
Generate Invoices Per
.
If some lines remain on back order after generation behavior depends on
Order Generation Basis
in
OE Settings
.
Note: Net negative value supplies will generate as a credit.
Generate and Print Invoice
(Alt+I)
Available for Orders only.
You can enter an order, access back ordering, invoice if stock is available, and print the invoice for dispatch with the goods. Or you can print in a batch after the invoices for the day have been generated. The generated invoice will be available for posting to AR and can be edited and printed prior to posting.
Quote from Order
(Alt+Q)
Available for Orders only.
Creates a new Quote in
IN Enter Invoices
based on the current Sales Order.
Mark as Processed
(Alt+P)
Available for Orders only, marks the Order as
Processed
, zeroing any un invoiced Supply or Back Order quantities and hence Allocations and Back Order quantities relating to the Order in Inventory Control.
Manual Packing Slip
Available for Orders only. Only available if the order has a
Packing Slip No
and the
Print Status
is not
Printed
. This sets the
Print Status
to
Manual
. This is useful when a computer printed document is not required and
Order Completion Basis
in
OE Settings
is
Printed and Processed
.
Print Confirmation
(Alt+F)
Print as a confirmation. In Edit mode, the Order is saved first. Confirmations can also be
batch emailed
or
printed
.
Once a Confirmation has been printed, the
Packing Slip (P/Slip) Number
and
Customer Code
cannot be changed unless
OE Settings
allow.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Form Fields
Period
Defaults to the System period. You can select another period for the order.
Document type
Shows the type (Order or Standing Order) and Packing Slip Number. Read-only.
ID
An allocated number that identifies the order. Read-only.
Order
Shows
OE Generation Basis
for the Document:
Packing Slip
- Packing Slip basis.
Back Order
- Back Order basis.
Currency and Regime
The
Currency code
and
Tax regime
for the document.
Customer code
Select the Customer Code before entering details. The Customer Name, Currency and Tax Regime are displayed.
Defaults from the customer including Price List, GST code, and Delivery Address will be applied. If the Customer code is changed, new defaults will be applied to new lines added.
Note: If the Customer is changed, defaults will not be applied to existing Lines in the order. Accredo attempts to preserve existing pricing. Use the
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
Order Totals
Customise
Opens
Customise Fields
, you can customise the fields visible in the totals panel.
Net
The order total for supplied quantities excluding GST and charges entered on the Charges tab. The Exclusive Amount.
Charges
Shows the GST Exclusive total of the charges entered on the Charges tab.
GST
The GST total on both the net amount and the charges.
Gross
Total so far, including
Invoice rounding
.
Margin
The percentage margin on the order total so far, calculated as:
100*(Exclusive Amount - Exclusive Cost) / Exclusive Amount
.
Total Weight
Total weight for Quantity Supplied for the Order.
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
Total volume for Quantity Supplied for the Order.
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
Total Weight Ordered
Total weight for Quantity Ordered for the Order.
Total Volume Ordered
Total volume for Quantity Ordered for the Order.
Buttons
Order List
(Alt+L)
Opens
Order List
and selects the document.
View Invoice
(Alt+V)
Links the order to the generated invoice.
Related Orders
(Alt+O)
Opens
Order List
with the selected Customer code.
Back Orders
(Alt+B)
Opens
Document Back Orders
, showing back orders for the order and Customer.
Number and Save
(Alt+A)
Allocates the next packing slip number from the automatic sequence and saves the sales order.
Save
(F9)
Saves the order and assigns an ID Number. Saved orders can be printed as packing slips in a batch, for fulfilling (if containing back ordered items), for invoice generation or editing.
If the Order was generate from a Quote, the Quote
Post Status
will be set to
Posted
.
Cancel
(Esc)
Cancels any changes.
In This Section
OE Sales Orders - Header tab
OE Sales Orders - Lines tab
OE Sales Orders - Charges tab
OE Sales Orders - Links tab
OE Sales Orders - Memos tab
OE Select Invoice
OE View Related Orders

---

## OE Find Document by Order No

Source: https://accredo.co.nz/webhelp/FindOrderNo.htm

OE Find Document by Order No
Navigator > Maintain > Order Entry > Sales Order List >
Order
(Alt+O)
Enter a Customer Code and Order Number to find a document.
The Order Number is the OE
Order No
.

---

## OE Find Packing Slip Number

Source: https://accredo.co.nz/webhelp/OEFindPackingSlip.htm

OE Find Packing Slip Number
Navigator > Maintain > Order Entry > Sales Order List >
Number
(Alt+N)
Enter a Packing Slip Number to find a document. The packing Slip Number is the OE
P/Slip Number
.
You can also:
Click
Find
(
Ctrl+F
) in the OE Sales Order List to search for a document using the unique Document ID assigned to documents by Accredo.
Click
Order
(Alt+O)
in the OE Sales Order List to search for a document using the Order Number.
See Also
OE Sales Order List

---

## OE Fulfill Back Orders

Source: https://accredo.co.nz/webhelp/OEFulfillBackOrders_SelectionForm.htm

OE Fulfill Back Orders
Navigator > Tasks > Order Entry > Fulfill Back-orders
You can allocate available stock to back-orders. After back-orders have been fulfilled, they become available for packing slips and invoices. Customer and product selections and filters on orders allow you to be selective and prioritise products or customers. If you accept the defaults without applying filters or sorts, back-orders will be fulfilled in customer sequence and stock allocated to fulfill back-order quantities until stock runs out or the run is completed. The filter on orders (Fulfill for) can be sorted on, so you can select orders to fulfill or sort orders (for example, by date).
Hint: To fulfill back-orders for a product by fulfilling the oldest orders first; sort orders by date and specify the product in From/To selections.
Customer From / To
Product From / To
Select the customers and products to fulfill back-orders for, or leave blank to select all customers and products.
Fulfill for
Determines the orders and lines to be included. The default is set from Navigator > Setup > Order Entry >
OE Settings
> General tab.
Full Orders
Fulfill Back-order only when all back ordered items can be supplied in full.
Full Lines
Fulfill Back-orders only for lines where the quantity back ordered can be supplied in full.
All Lines
Fulfill all Order lines where stock is available. This includes partially supplying lines where there is insufficient stock to fully supply.
Show Non-Supplied Lines
For a query run, use this to show each back order, and back order lines that are not fulfilled. Use this with fulfill full lines or fulfill all lines above. If you select a range of products or apply a
Filter & Sort
on products, this will only show non supplied lines for products within the selection criteria.
Default Delivery Date
The date will be entered into the
Delivery Date
field on all fulfilled orders.
Note: Delivery Date can be required, see
OE Settings
. If products are
Expiry
tracked and delivery date is not set the document date is used to calculate
Minimum Expiry
for determining available quantities and generated tracking.
Up To Period
Limit fulfilling orders up to and including the period selected, usually to avoid fulfilling forward orders.
Query Run
Selected,
Fulfill Back Orders Query
is opened for each back-order that can be fulfilled, you can confirm or edit quantities fulfilled, (default). Once you have selected each order, the
Fulfill Back-orders Results
list will appear.
Clear,
back-orders are fulfilled on the basis of the selections without further input and the
Fulfill Back-orders Results
list will appear.
Branch
Select a Branch code to fulfill Back-orders for a single branch. (Accredo Saturn Only)
Run
(F9)
The results of fulfill back orders are displayed.
In This Section
OE Fulfill Back Orders Query
OE Fulfill Back Orders Results

---

## OE Fulfill Back Orders Query

Source: https://accredo.co.nz/webhelp/OEFulfillBackOrders_Query.htm

OE Fulfill Back Orders Query
Navigator > Tasks > Order Entry > Fulfill Back Orders >
Query Run
Selected
> Run
OE Fulfill Back Orders Query opens for each back-order that can be fulfilled. Order details, Customer code, Order date and number will appear. A grid of back-order lines to be fulfilled is shown. A supply quantity for the full amount of the back-order if there is sufficient stock available is shown.
You can edit quantities supplied by over-typing the default with the quantity to supply; the balance will remain on back-order. To leave the full quantity on back-order, type
zero (0)
in the Supply field. Enter a supplied quantity for a non-supplied line, for example, if you have received an item that has not yet been entered into stock.
Customer Code
Displays the Customer Code and Customer Name for the back-order.
Order Date
Date ordered.
Order No
The Order Number.
Document ID
The Document ID of the order.
Packing Slip No
The Packing Slip Number of the order.
Grid
Supplied
Enter the quantity on back order to be supplied.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Move up
(Shift+Up)
Move down
(Shift+Down)
Move the line up or down.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Charges Grid
Description
The Description of the IN Charge. Charges are setup in
IN Charges
.
Charge
Enter the charge for each charge type.
GST Code
The GST Code for the charge.
Buttons
Update
(F9)
Update the order with the Supplied quantities.
Skip
(Esc)
Skip the current order.

---

## OE Fulfill Back Orders Results

Source: https://accredo.co.nz/webhelp/OEFulfillBackOrders_FulfillResults.htm

OE Fulfill Back Orders Results
Navigator > Tasks > Order Entry > Fulfill Back Orders >
Run
After fulfilling Back Orders, Fulfill Back Orders Results will open listing fulfilled and unfulfilled (due to error) orders. If a Customer's Credit limit is exceeded during batch processing, an error message will appear and the Order will not be processed. Depending on
permissions
, you can override the credit limit when manually fulfilling an order.
Fields
- contain information from the selection form and are read-only.
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
Total number of back orders that were not fulfilled due to errors.
Gross Errors
Total amount of the back orders that were unprocessed.
Records
Total number of back orders successfully fulfilled.
Gross Success
Total amount of the back orders successfully fulfilled.
Packing Slips
(Alt+P)
Use to print packing slips for fulfilled orders shown in the grid, with the options of printing packing slips for full orders only, full lines only or all orders.
Close
(Esc)
Close the Results form.

---

## OE Insufficient Query

Source: https://accredo.co.nz/webhelp/OEInsufficientQuery.htm

OE Insufficient Query
Navigator > Tasks > Order Entry > Enter Sales Orders > Lines tab > Ordered Amount Entered
When there is insufficient stock available to supply the quantity ordered, you can select the action to take.
You can set the default selection or turn off this prompt in
OE Settings - General tab
.
Action
Effect
Back Order
Back Order the entire quantity ordered.
Supply
Supply the entire quantity ordered, going into negative stock available.
Available
Supply the available quantity and disregard the balance of the ordered quantity.
Partial Supply
Supply the available quantity and Back-order the balance of the ordered quantity.

---

## OE Label Designer

Source: https://accredo.co.nz/webhelp/OELabelDesigner.htm

OE Label Designer
Navigator > Setup > Order Entry >
Label Designer

---

## OE Link List

Source: https://accredo.co.nz/webhelp/OELinkList.htm

OE Link List
Navigator > Maintain > Order Entry >
Link List

---

## OE Memo Designer

Source: https://accredo.co.nz/webhelp/OEMemoDesigner.htm

OE Memo Designer
Navigator > Setup > Order Entry > OE
Memo Designer

---

## OE Memo List

Source: https://accredo.co.nz/webhelp/OEMemoList.htm

OE Memo List
Navigator > Maintain > Order Entry >
Memo List

---

## OE Memo Reports - Add Layout

Source: https://accredo.co.nz/webhelp/OEMemoReports.htm

OE Memo Reports - Add Layout
Navigator > Reports > Order Entry > Memo Reports > Add Layout
See
Memo Report
.

---

## OE Order Labels

Source: https://accredo.co.nz/webhelp/OEReports_Label.htm

OE Order Labels
Navigator > Setup > Order Entry
These labels are used to print customer details for dispatch. Print Sales Order labels you have designed using
Label Designer
.
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
Type, Post Status and Print Status
Select documents to print labels for. You can filter on the Order header, for example, to select an order by Customer Order number.
Branch
This is useful to print labels for all (or selected) orders at a Branch. (Accredo Saturn Only)
Number of label copies
You can specify the number of copies you want for each label. For details on how to design labels that print different information on different copies, see
Label Designer
.
Start from label
Typically on sheet feed labels, you can start printing at a label other than the first one on the page (because part of the page of labels has been used). You can specify the label to start at.

---

## OE Order Line Fields

Source: https://accredo.co.nz/webhelp/OEOrderLineFields.htm

OE Order Line Fields
Navigator > Tasks > Order Entry > Enter Sales Orders > Lines Tab >
Zoom or
Customise Fields
Field Name
Description
Type
Select
Product
,
Narrative
or
Sticky Narrative
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
.
Product
For entering Product items. These can be products held in IC but need not be as all details can be entered manually.
Narrative
Enter extended lines of text, such as a detailed description of a job. Click
Narrative
(F2)
in the
Description
field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Sticky Narrative
A special type of narrative line that is linked with the line above. When invoices are generated, these lines will be transferred to the invoice only if the line above is also, that is, the order contains some supplied items. These lines are also only printed on packing slips if the line they are linked to is printed. Ordinary narrative lines are always transferred during invoice generation. Sticky narrative lines can attach narration to a Product line.
Auto Kitset
Gets the list of components on the order. When posted, the components on the following lines are sold, not the product on the Auto Kitset line. Special Pricing is not applied to Auto Kitset lines. To apply Special Pricing to a group of products, you must use a Manual Kitset.
Component
Lines below an Auto Kitset line. These products are recognised as sold when the order is posted.
Manual Kitset
The product is manufactured on the fly from the usage lines below and then sold.
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
to open
Narrative Editor
.
UOM Code
(
UOM
Active Only)
These are obtained from the Product record. They can be used (in a script) for apportioning freight and other costs across different Products. Only available when
UOM
is
Active
.
UOM Ordered
(
UOM
Active Only)
The quantity of the UOM ordered. If the UOM has a
Multiplier
of more than
1
, the
Ordered
will be calculated as the
UOM Ordered * UOM Multiplier
.
Ordered
The quantity ordered. When a product is selected, this defaults to the value specified in
Settings
(often
0
).
If
UOM
is
Active:
Ordered
is calculated as the
UOM Ordered * UOM Multiplier.
Ordered
is not shown in the grid by default.
If
UOM
is not Active,
Ordered
is entered.
UOM Supplied
(
UOM
Active Only)
The quantity of the UOM supplied. If the UOM has a
Multiplier
of more than
1
, the
Supplied
will be calculated as the
UOM Supplied * UOM Multiplier
.
Supplied
The quantity supplied will default to the quantity ordered if sufficient stock is available.
If
UOM
is
Active:
Supplied
is calculated as the
UOM Supplied * UOM Multiplier.
Supplied
is not shown in the grid by default.
If
UOM
is not Active,
Supplied
can be entered.
UOM Back Order
(
UOM
Active Only)
The quantity of the UOM on back order. If the UOM has a
Multiplier
of more than
1
, the
Back Order
will be calculated as the
UOM Back Order * UOM Multiplier
.
Back Order
The quantity to be placed on back-order, based on the
Default If Insufficient Stock
option in
OE settings
.
If
UOM
is
Active:
Back Order
is calculated as the
UOM Back Order * UOM Multiplier.
Back Order
is not shown in the grid by default.
If
UOM
is not Active,
Back Order
can be entered.
Unit
The unit for the product (for example, Each or Doz) usually printed on the invoice. If a UOM Code is entered, shows the UOM Code Description. If no UOM Code exists, this can be entered.
Price
Price per the Discount Mode in the
Discount Schedule
. If the Discount Mode is:
Explicit,
shows the Sell Price for the item before a discount, the discount appears in the
Disc%
field.
Implicit,
shows the discounted price, discount not in the
Disc%
field.
For
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
Price * UOM Multiplier
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
The GST code for the line. If a GST Override has been specified for the Customer, that will be the default. Otherwise, the GST is the default GST code for the Product, or if the line does not have a Product code, the GST for the Sales Group. It is unusual to need to change this code manually.
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
.
Amount
The extended line amount. You cannot enter in this field; it is calculated as
QuantitySupplied x SellingPrice - EnteredDiscount
. Read-only.
Alternate Code
The alternate code from the product record, read-only.
Group Name
The name of the Sales Group specified in the Group field. Read-only.
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
Bin Code from the product record. Read-only.
Branch
The branch the sale on the line is analysed to when processing the Order. (Accredo Saturn Only)
Comm Amount
The amount of commission attached to this line, usually calculated from the commission percentage applied to the price or the gross profit on the line, based on the
Commission Basis
. If commission is based on profit, it can be recalculated during Order posting (when the latest Cost Price is available).
Comment
30 character text field.
Commission %
Commission percentage applicable to this line. By default it is loaded from the Product record.
Commission Amount BS
The commission amount in the Base Currency. Read-only.
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
The cost price in the Base Currency. Read-only.
Currency Code
Currency code for the sales order. Read-only.
Custom 1
Custom 2
These fields can be used to add information to be stored with sales orders, and printed on documents. To change the field names, select customise on the line grid and change the Display Label.
Date Supplied
Date the product line was supplied.
Dept
The Department the line is analysed to. (Accredo Saturn Only)
Eff. Sell Price
Effective selling price. Read-only.
Eff. Sell Price Bs
Effective selling price in the Base Currency. Read-only.
EnteredAmountBs
Entered amount in the Base Currency. Read-only.
Excl Amount
The Selling Price, excluding GST, less applicable discounts, of all the supplied items in the Order line. Read-only.
Exclusive Amount Bs
Exclusive amount in the Base Currency. Read-only.
Excl Amt Ordered
Exclusive amount ordered. For back orders, this is calculated as the exclusive amount of the
(Quantity Ordered - Quantity Invoiced)
. Read-only.
Excl Amount Ordered Bs
Exclusive amount ordered in the Base Currency. Read-only.
Exclusive Cost Bs
Exclusive Cost in the Base Currency. Read-only.
Exclusive Cost Ordered
Exclusive Cost Ordered, calculated as
CostPrice * QuantityOrdered
. Read-only.
Exclusive Ordered Cost Bs
Exclusive Cost Ordered in the Base Currency, calculated as
CostPriceBs * QuantityOrdered
. Read-only.
Ext Cost
Extended cost value for the line. It is calculated as
QuantitySupplied * CostPrice
. Read-only.
Extended Volume
If UOM is Active, this is calculated as
(Volume * UOM Quantity)+UOM Additional Volume
.
If UOM is not Active, this is calculated as the
Volume * Quantity
.
UOM Additional Volume
is setup in
IC Units of Measure
.
Extended Weight
If UOM is Active, this is calculated as
(Weight * UOM Quantity)+UOM Additional Weight
.
If UOM is not Active, this is calculated as the
Weight * Quantity
.
UOM Additional Weight
is setup in
IC Units of Measure
.
GL Account Code
You can override the GL Account associated with the Sales Group. For example, if you sell a fixed asset you can use a Miscellaneous Sales Group and override the GL Account with the GL Asset code, adding a narration to explain this. If a GL Account code is:
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
(all GST). See
GST Line Calculations
for calculation details.
GST Amount Bs
GST Amount in the Base Currency. Read-only.
GST Amount Ordered BS
GST Amount Ordered in the Base Currency. Read-only.
GST Amt Ordered
GST Amount on the products ordered. Read-only.
Invoiced
Quantity invoiced on the order line. Read-only.
Line Break
Used for lines imported from the
Narrative editor
. Indicates whether to include a line break when invoices are printed.
Line Number
Shows the current line number on the order. Read-only.
Line ID
Identifier for the line. Read-only.
Line Space
Used for lines imported from the
Narrative Editor
. Indicates whether to include a line space when invoices are printed.
Line Status
Shows the current line status.
Lines can be:
Unprocessed,
the line has not yet been fully supplied and invoiced.
Processed,
the line has been supplied and invoiced. Updated automatically when fully supplied and invoiced but may be selected for a partially invoiced line if no further supply will be made.
Cancelled,
the line has been cancelled and will not be supplied.
Deleted
, the Order has been deleted.
Setting Line Status to Processed or Cancelled zeroes any Quantity Supplied or Back Ordered and removes the line from IC Pending Transactions and quantities.
See
OE Settings - Misc tab
for settings controlling Line behavior on Generate.
Location
The product supply location, only needed for lines with a Product code. (Accredo Saturn Only)
Margin
The percentage gross margin for the line, calculated as:
100 * (ExclusiveAmount - ExclusiveCost) / ExclusiveAmount.
Read-only.
Hint: see
permissions
on access to commissions, cost and Selling Prices.
Markup (%)
The percentage Markup for the line, calculated as:
Markup = ((SellPrice * (100-Discount%)/100) - CostPrice) * 100 / CostPrice.
SellPrice (before discount) = CostPrice * (100 + Markup%) / (100 - Discount%).
Note: If the Sell Price is GST inclusive, the GST is not deducted before the calculation, that is, Markup includes GST.
Hint: See Permissions on restricting access to Commissions, Cost and Selling Prices.
Narration
Type a narration to explain the reason for overriding the GL Account code, for example
Fixed Asset Sale
. This can be customised into the grid.
Product Details
Details from the product record. Read-only.
Selling Price Bs
The selling price in the Base Currency.
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
Cost Price * UOM Multiplier
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
Price * UOM Multiplier
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
Usage Cost
Usage cost. Read-only.
Usage Cost Bs
Usage cost in the Base Currency. Read-only.
Usage Cost Ordered
Usage Cost Ordered. Read-only.
Usage Cost Ordered Bs
Usage Cost Ordered in the Base Currency. Read-only.
Volume
For Automatic Kitsets, this is the sum of the Volume of the component lines. For other products, this is the Product Volume from the Product record. Read-only.
Weight
For Automatic Kitsets, this is the sum of the Weight of the component lines. For other products, this is the Product Weight from the Product record. Read-only.
Tracking Panel
Show Tracking
Hide Tracking
(Ctrl+T)
Show or hide the
tracking
detail for the current line.
See Also
OE Sales Orders - Lines tab

---

## OE Order Reports - Add Layout

Source: https://accredo.co.nz/webhelp/OEReports.htm

OE Order Reports - Add Layout
Navigator > Reports > Order Entry > Order Reports > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Allocation
Produces reports for stock allocated against unprocessed Sales Orders. See also
Invoice Allocation Reports
. You can specify ranges of customers and / or products and the required Post Status. Customise this layout to group by customer or product. To customise and add grouping, place the number
1
in the
Group
field for
CustomerCode
and
CustomerName
or for
ProductCode
and
Description.
After the report layout has been saved, you can access the customisation from Selections Form >
Options
> Customise.
Customer Grouping,
reports on allocated Stock Grouped by customer. Customer allocation reports are sorted by customer, then within a customer. Allocated quantities and amounts are sub-totalled for each customer. Grand totals for all allocated quantities and values appear at the end of the report.
Product Grouping,
reports on allocated Stock Grouped by Product. Product allocation reports are sorted by product, then customer, then within a customer. Allocated quantities and amounts are sub-totalled for each product. Grand totals for all allocated quantities and values appear at the end of the report.
Back Orders
Similar to Allocation reports except it reports on stock on back-order (rather than stock allocated on Current-orders). The same selections are available and the same comments regarding grouping apply.
Order
Produces a report which lists Order header and lines information. You can also show order banking line information. You can specify a range of customers and / or products, and their required Post Status. You can specify the period or a range of periods. The Current/History selection is to allow optimised scanning of the Order files. An order is,
Current,
if it is not deleted, and not processed.
Historic,
if it is deleted or processed.
Order Links
This report shows the links associated with orders for a range of periods.
Picking
Report tracking detail for selected current documents. With selections for range of Customers, Products, Packing Slip No, Invoice No and Bin Codes.
Shipping
Shows the shipper assigned to each order.
Status
Produces a report that lists orders. Select types of documents, and specific post and print statuses. The Current/History selection is to allow optimised scanning of the Order files. An order is current if it is not deleted and is not processed. An Order is historic if it is deleted or processed. Select orders that belong to a period or period range.

---

## OE Packing Slip Designer

Source: https://accredo.co.nz/webhelp/OEPackingSlipDesigner.htm

OE Packing Slip Designer
Navigator > Setup > Order Entry > Packing Slip/Confirmation Designer
Use the Packing Slip designer to design layouts for packing slips and order confirmations. You can design your own documents or open and modify existing designs. To design a packing slip or confirmation quickly, start with an existing layout, save it with a different name, then modify it. Sample reports are installed with the Accredo server install.
Note: If you modify reports that are provided with Accredo it is important to save them with different names, as when Accredo updates are installed, the reports can be overwritten.
Packing Slips produced from Invoices entered in IN can be designed in
IN Invoice Designer
.
The OE Packing Slip Designer is based on the
Report Designer
and has similar functionality. Full report design facilities including
MaxBasic
are available.
Usually a packing slip consists of a:
Header band
showing customer details and packing slip number.
Repeating Detail band
showing order lines, and
Footer band
for totals.
An additional
Back Order
band to print summary information for all back-orders is also available.
Iterators are available to create sub-sets of records. Iterators can be applied to Bands to filter records shown in a band. Iterator objects allow setting of the
SortBy
property in the
BeforeReport
code. For example, you can filter the Supply iterator to exclude Usage, or you can sort by Bin Code.
Name
Iterators filter records the shown in the report. Available Iterators are:
Supply
- iterates through the order lines.
BackOrder
- iterates through products on back-order for this customer.
Shipping
- iterates through the shipping lines on the order.
Bank
- iterates through the banking lines on the order.
Tracking
- iterates through the tracking detail for the order line.
Bands
The Bands in the report to apply the iterator to.
Sort Order
Optionally select fields to sort records in the iterator.
Filter
Optionally select fields to further filter the iterator.
Objects available in the Packing slip designer in addition to the standard
objects
are:
BackOrder
Fields from the Back-order summary records.
Contact
Fields from the Customer Contact records. If a contact has been specified, this object is populated with the information associated with the document. If no contact is specified, this object is populated with the primary contact information (if specified).
Customer
Fields from the Customer record.
DeliveryAddress
Fields from the delivery address records.
itBackOrder
Properties of the Back Order iterator.
itSupply
Properties of the Supply iterator.
OrderHead
Fields from the Order header record.
OrderLine
Fields from the Order line records.
Product
Fields from the product specified in the Order line.
ProductQty
Fields from the quantity for the product specified in the Order line.
Functions available in addition to the standard
MaxBasic functions
are:
ChargeName (Charge)
Returns the name of the
Charge
specified by the parameter charge which must be in the range
1-4.
Sample OE Packing Slips are provided with the Accredo Server Install, and are also available on the Accredo website. Sample OE Packing Slips include:
OEPackingSlip.pfd
- standard OE Packing Slip.
OEPackingSlipPriced.pfd
- OE Packing Slip that includes product prices.
OEConfirmation.pfd
- standard OE Order Confirmation.
OEConfirmationPriced.pfd
- OE Order Confirmation that includes product prices.
To use documents downloaded from the website, ensure your document designer is the latest version.
In This Section
OE Report Period

---

## OE Packing Slip/Confirmation Email Designer

Source: https://accredo.co.nz/webhelp/OEPackingSlipEmailDesigner.htm

OE Packing Slip/Confirmation Email Designer
Navigator > Setup > Order Entry > Packing Slip/Confirmation Email Designer
You can design your own confirmations and packing slip emails or open and modify an existing email design. To design a confirmation or packing slip email quickly, start with an existing email design and modify it, ensuring you save it with a different file name. Select the default email design in
Document Defaults
.
Use Packing Slip and Confirmation Email Designs when you
Email Confirmations
or Packing Slips.
HTML Body tab
Enter the email text for HTML Emails. See
HTML Email Editor
.
Plain Text Body tab
Enter the email text for plain text emails.
Preview
(Alt+P)
Display a preview of what the email will look like. A current Packing Slip must be available.
Load...
(Alt+L)
Load an existing Packing Slip Email to use for designing different emails.
Save...
(Ctrl+S)
Save the current email as a HTML file. You can reload the file in the designer to refine or create a new email.

---

## OE Print Confirmations

Source: https://accredo.co.nz/webhelp/OEPrintConfirmations.htm

OE Print Confirmations
Navigator > Reports > Order Entry > Print Packing Slips
Batch print or reprint confirmations from orders. Confirmations can be printed individually from Enter Sales Orders. Batch printing applies only to orders for with un-generated invoices. Historic orders cannot be batch printed. To print a confirmation for a Historic order, go to the
OE Sales Order List
, open the Order, then click
Print Confirmation
.
When an Order is printed as a confirmation, its print status changes to "Confirmed" from "Unprinted". For batch printing, by default, orders are printed by Packing Slip number, followed by orders for which packing slip numbers have not been allocated, then by Customer code. Orders that have not been allocated a packing slip number will be allocated the next available computer generated number, prior to printing. Options on the selection screen depend on if you are printing individually or in a batch, see
Report Selections Form
.
Once a Confirmation has been printed, the Packing Slip (P/Slip) Number and Customer Code on the Order cannot be changed unless
OE Settings
allow.
Additional selections
Report File Name
The Report File Name specifies the file that defines the Confirmation layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
OE Packing Slip Designer
.
Customer - From / To
Select a customer or a range of customers to print confirmations for.
Date - From / To
Select range of order dates to print confirmations for.
Print Status
Select orders based on print status, defaults to
Unprinted.
Print For
Determines the default used to select the orders and Order lines to include. The default value is set in
Settings
.
Full Orders
Include orders when all items for the Order have been supplied in full.
Full Lines
Include only Order lines that have been supplied in full. An Order is included if at least one line has been supplied in full.
All Lines
Include all orders and Order lines, irrespective of whether lines have been supplied in full.
See also
Settings
for an option to print only supplied lines.
Up to Period
Select a period to print confirmations up to.
Branch
Select the Branch.
Clear,
Confirmations will be emailed for all. (Accredo Saturn Only)
Exclude Email Customers
Selected
, invoices for customers with an email address in the
Packing Slips
field on the
Customers - Contacts tab
, will not be printed.
Confirmation Message
If you use the standard Accredo OEConfirmation design, you can add a short text message by creating or editing a text file called OEPConfirmation.txt located in the sub folder Reports\OEPackingSlip of Accredo. This file can be created or edited using any text editor. Comprehensive or conditional messages can be achieved using Packing Slip Designer.

---

## OE Print Packing Slips

Source: https://accredo.co.nz/webhelp/OEPrintPackingSlips.htm

OE Print Packing Slips
Navigator > Reports > Order Entry > Print Packing Slips
Batch print or reprint packing slips from orders. Packing slips can be printed individually from Enter Sales Orders. Batch printing applies only to orders for with un-generated invoices. Historic orders cannot be batch printed. To print a packing slip for a Historic order, go to the
OE Sales Order List
, open the Order, then click
Print
(Ctrl+P)
.
When an Order is printed as a packing slip, its print status changes to "Printed". For batch printing, by default, packing slips are printed by Packing Slip number, followed by orders for which packing slip numbers have not been allocated, then by Customer code. Orders that have not been allocated a packing slip number will be allocated the next available computer generated number, prior to printing. Options on the selection screen depend on if you are printing individually or in a batch, see
Report Selections Form
.
Once a Packing Slip has been printed, the Packing Slip (P/Slip) Number and Customer Code on the Order cannot be changed.
Additional selections
Report File Name
The Report File Name specifies the file that defines the Packing Slip layout.
Set a default report file name from Navigator > Setup > Company > Reporting >
Document Defaults
.
Click
Open In Designer
to open the selected file in the
OE Packing Slip Designer
.
Customer - From / To
Select a customer or a range of customers to print packing slips for.
Date - From / To
Select a date or a range or dates to print packing slips for.
Print Status
Select orders based on print status, defaults to
Unprinted.
Print For
Determines the default used to select the orders and Order lines to include. The default value is set in
Settings
.
Full Orders
Include orders when all items for the Order have been supplied in full.
Full Lines
Include only Order lines that have been supplied in full. An Order is included if at least one line has been supplied in full.
All Lines
Include all orders and Order lines, irrespective of whether lines have been supplied in full.
See also
Settings
for an option to print only supplied lines.
Up to Period
Select a period to print packing slips up to.
Branch
Select the branch to print packing slips for. (Accredo Saturn Only)
Packing Slip Message
If you use the standard Accredo Packing Slip design, you can add a short text message by creating or editing a text file called OEPackingSlip.txt located in the sub folder Reports\OEPackingSlip of Accredo. This file can be created or edited using any text editor. Comprehensive or conditional messages can be achieved using Packing Slip Designer.

---

## OE Report Period

Source: https://accredo.co.nz/webhelp/OEReportDesignerPeriod.htm

OE Report Period
Navigator > Setup > Order Entry > Statement Designer > View > Reporting Period
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
OE Packing Slip Designer

---

## OE Reprice Sales Orders

Source: https://accredo.co.nz/webhelp/OERepriceOrders.htm

OE Reprice Sales Orders
Navigator > Tasks > Order Entry > Reprice Sales Orders
Update changed Cost and Selling Price for Current-orders, Back-orders and Standing-orders. You can update the Cost and Selling Price contained on unprocessed and open orders, Back-orders and Standing-orders to reflect current pricing. Discount, GST code, Product description and Sales Group can also be updated. To reprice a single Order, select the Order from the Sales Order List to access Enter Sales Orders.
Customer - From / To
Useful if you need to reprice orders for specific Customers.
Product - From / To
Used when updated pricing is only applied to some products. It is common to reprice Standing-orders to bring them up to date. Repricing is not applied to Automatic Kitset lines, but is applied to all of the Component lines which make up the Automatic Kitset.
Type
Select the type of documents to be repriced from,
Order -
Orders which have not been invoiced.
Back Order
- Orders which have been partially invoiced. (Packing slip count > 1).
Standing Order
Update
You can specify if the unit Cost Price is to be updated to reflect current costings. This is often used when orders are entered before the Cost Prices of the items are precisely known (for example, forward orders).
Re-pricing is not applied to Automatic Kitset lines, but is applied to all the Component lines that comprise the Automatic Kitset.
Cost prices are not updated for
Manually Costed
Products.
If you use Special Pricing, you must select both Selling Price and Discount to include consideration of all Special Pricing rules in repricing. If you use implicit discounting and repricing results in a zero price.
Special Pricing of zero will be applied unless disallowed under Special Pricing rules.
Zero prices in IC will not be applied.
If you select
GST code
, the GST rates will be loaded and re-applied for each code. This is useful if the rate of GST has changed and you have unprocessed Invoices in Accredo. New GST calculations will also be applied if GST basis (Inclusive/Exclusive) has changed for the Price code. This would be an unusual situation unless the basis had been incorrectly set in the first instance.
Selections default from
IN Settings - Reprice tab
.
Branch
Applies repricing to orders for a single Branch. (Accredo Saturn Only)
Run
(F9)
The number of documents repriced is returned, and you can print a report of the documents.
In This Section
OE Reprice Sales Orders Results

---

## OE Reprice Sales Orders Results

Source: https://accredo.co.nz/webhelp/OERepriceSalesOrderResults.htm

OE Reprice Sales Orders Results
Navigator > Tasks > Order Entry > Reprice Sales Orders >
Run
Lists repriced sales orders and those that were not processed due to error.
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
Total number of sales orders that were not repriced due to errors.
Gross Errors
Total amount of the sales orders that were unprocessed.
Records
Total number of sales orders successfully repriced.
Gross Success
Total amount of the sales orders successfully repriced.

---

## OE Revalue Foreign Orders

Source: https://accredo.co.nz/webhelp/OERevalueForeignOrders.htm

OE Revalue Foreign Orders
Navigator > Tasks > Order Entry > OE Revalue Foreign Orders
You can change the Valuation date and exchange rate to re-calculate base values on orders if the exchange rate is not
fixed
. You will be prompted for a Valuation date and exchange rate. Once revaluation is complete, a Results list will show the revalued orders.
If Exchange Rates table is in use, invoices generated from orders will automatically revalue based on the Invoice date.
Type
Select the types of orders to be revalued from,
Order -
Orders which have not been invoiced.
Back Order
- Orders which have been partially invoiced. (Packing slip count > 1).
Standing Order
Valuation Date
Enter the date for the revaluation.
Currencies
For each currency, enter the
Rate Type
and
Exchange Rate
for the revaluation.
Save Rates
Update foreign currency rates based on
Exchange Rates
entered.
Run
(F9)
Revalue unallocated Foreign Orders from revaluation period up to current period and update base currency balances for Foreign Creditors. Create Unrealised Variation records for each revalued transaction.
Cancel
(Esc)
Close the form and do not make any changes.
In This Section
OE Revalue Foreign Orders Results

---

## OE Revalue Foreign Orders Results

Source: https://accredo.co.nz/webhelp/OERevalueForeignOrdersResults.htm

OE Revalue Foreign Orders Results
Navigator > Tasks > Order Entry > Revalue Foreign Orders >
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

## OE Sales Order List

Source: https://accredo.co.nz/webhelp/OEOrderList.htm

OE Sales Order List
Navigator > Maintain > Order Entry > Sales Order List
Selections
Customer
Select from the
Lookup
. Click
to show selected documents for all customers.
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
Select the type of documents to display:
Order
Packing Slip
Standing Order
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
Select Orders
to apply selections, filters and sorts to the list.
The default value is set in
OE Settings Misc tab
.
Select Orders
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
If you selected Order or Standing Order, the selected document is inserted. If History or All Documents, choose a document type from the dropdown.
Delete
(F3)
Delete transfers to history, it is not deleted from the files, if unsure, open it first.
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
Footer
Record Count
The total number of records shown in the list. Click
to refresh the total number.
Number
(Alt+N)
Click to
find
a document by entering a Packing Slip Number.
Order
(
Alt+O
)
Click to
find
a document by entering a Customer Code and their Order Number.
In This Section
OE Find Packing Slip Number
OE Find Document by Order No

---

## OE Sales Orders - Charges tab

Source: https://accredo.co.nz/webhelp/OEEnterOrders_Charges.htm

OE Sales Orders - Charges tab
Navigator > Tasks > Order Entry > Enter Sales Orders > Charges tab
The Charges tab also contains the Shipping and Banking grids for Cash Sales.
Charges
Charges are useful for invoicing amounts you do not want to show against Sales Analysis categories (Sales Area and Sales Person). Charges entered on orders are transferred to the Invoice when it is generated. If back ordered items remain after an Invoice is generated, charges are not transferred to the Back-order.
Note that charges are not included in the Customer Sales Values calculations.
Description
Charge types,
Charge 1
,
Charge 2
and
Charge 3
, can be changed from Navigator > Setup > Invoicing System >
IN Charges
.
For example, you can setup one for freight and postage, one for insurance and one for miscellaneous charges. Charges are GST exclusive or inclusive as determined by the Price code for the order.
Charge
Amount of the charge.
GST Code
The GST code is set for the charge from Navigator > Setup > Invoicing System >
IN Charges
, unless this is overridden by a Customer's
GST Override
. You can change the GST code.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
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
A tracking address that can be used to store a tracking link. If the Order is converted to an Invoice, this will be carried through to the invoice.
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
Banking Grid
Details apply when you process an invoice as a cash sale. Banking details can be entered and saved with an order for processing once invoiced as a cash sale. Banking details can be entered and saved with quotes and will copy through to the order or invoice when the quote is accepted. Banking details entered and saved with a Sales Order are copied through to the invoice when generated. This can be used to record credit card payment details when the order is placed. The receipt allows for multiple payment types and split tender.
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
Save the Media code, Payer Name, Reference and Particulars details for the current line against the Customer record.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.

---

## OE Sales Orders - Header tab

Source: https://accredo.co.nz/webhelp/OEEnterOrders.htm

OE Sales Orders - Header tab
Navigator > Tasks > Order Entry > Enter Sales Orders > Header tab
See also
OE Enter Sales Orders
.
Order Date
The date the order was or will be invoiced. Defaults to the last order date entered, or the System Date if this is the first order of the session. The date can be changed, but must be within the range for the selected period.
Origination Date
The date the customer placed the order, useful for forward ordering and tracking.
Delivery Date
The date the order was or will be dispatched.
Blank
(default, can be edited). Note; the numeric keypad
+/-
keys will step the date backwards or forwards from the System Date.
Valuation Date
For Foreign Currency orders, the date the order was last revalued. The exchange rate will relate to the Valuation date entered, otherwise to the Order date, see
OE Revalue Foreign Orders
.
Rate Type
Exchange Rate
If
Use Exchange Rate Table
is selected from
FX Settings
, - the Rate is fetched from the Exchange Rates Table based on Currency code, Rate type and Date. You may lock the rate by clicking the
Fix Rate
button. Fixing means it can no longer be changed on this order and the order is excluded from Revaluations.
If not fixed the rate will be re-fetched from the rates table when Rate type, Currency code or Date are changed, and a rate based on the invoice date will be fetched when an invoice is generated.
Order Number
Customer Order number. If the customer has
Order No. Required
, an Order No. must be entered before an Order can be saved.
The
IN Setting
for
Order No Check
controls when a hint is displayed for repeating a Customer Order No.
Internal Ref
Can be printed on the packing slip for internal use, for example, reference to the Sales Order or Job number.
P/Slip Number
Allocated when Packing Slip No is empty:
On save if Always Number on Save is selected in
OE Settings
.
On Print of Confirmation or Packing Slip.
On Generate Invoice if Always Number on Generate is selected in
OE Settings
.
Click the
Number and Save
button to immediately allocate the next number and save.
If
Allow Manual Packing Slip Nos
is selected in
OE Settings
, you can allocate a number manually.
Note: If some lines remain on back order after generation the Packing Slip Number may be retained or cleared depending on and
Retain Packing Slip No On Generate
in
OE Settings
.
Internal Ref
Can be printed on the packing slip for internal use, for example, reference to the Sales Order or Job number.
Quotation Ref
The Quote number if the order is generated from a quote (can be edited).
Sales Person
Sales Person
Analysis code. Defaults from the Customer Sales Person code or User
Default Sales Person Code
, can be changed. If no Sales Person code is entered, the default is
0000.
Discount Code
The default discount code for the Customer.
Price Code, Basis
Changing the Price code (and the Customer code) after Order lines have been entered can result in re-calculation of the order if the GST basis for the Price List changes. This will default from the Customer but can be changed. Changing the Price code does not update pricing for lines that have already been entered. If you change the Price code, select the
Reprice
button to reprice the order lines.
Warning: the GST basis for
Special Pricing
is based on the Price code for the order. If you use Special Pricing and change the Price code to a different GST basis, this will affect prices and margins.
Comment
A 30 character comment transferred to generated invoices and the customer transaction on
POST.
Post Status
Order status can be changed to
Open
, or can be changed or as a result of processing options:
Unprocessed
,
invoice not generated, can be changed to open.
Open,
will not be generated, a warning will appear if you try to print a packing slip.
Processed,
invoice has been generated, orders can be viewed and reprinted, cannot be edited.
Deleted,
order has been deleted and moved to history.
Print Status
Orders can have the following status:
Unprinted,
packing slip and order confirmation have not been printed.
Confirmed,
order confirmation has been printed.
Printed,
packing slip has been printed.
View the
Print Log
(requires Read access Permission for Company > Settings).
Note: If some lines remain on back order after generation and
Order Generation Basis
in
OE Settings
is Packing Slip the
Print Status
on the Order resets to
Unprinted
.
Contact
You can associate a Contact with a Sales Order. If a primary contact has been specified, this will be the default contact for new Sales Orders.
Email Contact
Selected
, emails regarding the document will be sent to the Contact Email Address.
Unselected
, emails regarding the document will be sent to the
Email Document
Address specified for the Customer.
Branch Department
The default Branch and Department codes applied to new Order lines. If this is changed, the changes will be applied to all Lines that have not been manually changed. (Accredo Saturn Only)
Default Location
The default Location code applied to new Order lines. If
Sell From
in
IC Stock Location
is
clear
, the location will be unavailable. (Accredo Saturn Only)
Category 1
Category 2
Can be added from
Categories
under Maintain > Invoicing System, or click
Open Category
(Shift+F12)
on the Lookup. Labels can be replaced in
IN Settings
.
Custom 1
Custom 2
Do not affect processing unless incorporated by a User defined script. Labels can be replaced in
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
Increments for each invoice generation from the order.
Balances
The current aged balances for the customer account.
Credit Limit
Credit limit for a customer. If it appears red, it has been exceeded. Depending on
Permissions
you can override a Credit limit on processing an order. However, if the Credit limit is exceeded during batch processing, an error message appears and the order is not processed.
Delivery Instructions
Select a Delivery Code or enter a delivery address. Defaults from the Customer Code. You can edit the address or select another.
Filter/Sort
- apply a
Filter & Sort
to the list of delivery addresses. Press
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
The default Shipper code is stored in the Delivery Address and populated as Shipping lines are entered.

---

## OE Sales Orders - Lines tab

Source: https://accredo.co.nz/webhelp/OEEnterOrders_Lines.htm

OE Sales Orders - Lines tab
Navigator > Tasks > Order Entry > Enter Sales Orders > Lines tab
Order lines grid
When entering or editing order lines,
Ctrl+Enter
moves to the start of the next line.
The following fields are shown by default.
Zoom
to Form view, or select
Customise
(Alt+F5)
to view all
OE Order Line Field
, including the
GL Account Code
.
Line Type
Select
Product
,
Narrative
or
Sticky Narrative
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
.
Product
For entering Product items. These can be products held in IC but need not be as all details can be entered manually.
Narrative
Enter extended lines of text, such as a detailed description of a job. Click
Narrative
(F2)
in the
Description
field of a narrative line to open the
Narrative Editor
, then type a narrative or choose a global narrative.
Sticky Narrative
A special type of narrative line that is linked with the line above. When invoices are generated, these lines will be transferred to the invoice only if the line above is also (if the line above contains some supplied items). These lines are also only printed on packing slips if the line they are linked to is printed. Ordinary narrative lines are always transferred during invoice generation. Sticky narrative lines can be used to attach narration to a Product line.
Auto Kitset
Gets the list of components on the order. When posted, the components on the following lines are sold, not the product on the Auto Kitset line. Special Pricing is not applied to Auto Kitset lines. To apply Special Pricing to a group of products, you must use a Manual Kitset.
Component
Lines below an Auto Kitset line. These products are recognised as sold when the order is posted.
Manual Kitset
The product is manufactured on the fly from the usage lines below and then sold.
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
The UOM Code from the Product. If the Product has more than one UOM Code, you can select the code to use.
Ordered / UOM Ordered
The quantity ordered. When a product is selected, defaults to the
Default Order Line Quantity
value specified in
OE Settings
(often
0
).
Supplied / UOM Supplied
The quantity supplied. Will default to the quantity ordered if sufficient stock is available.
Back Order / UOM Back Order
The quantity to be placed on back-order. This is based on the
Default if Insufficient Stock
option in
OE Settings
.
Unit
The unit for the product (for example, Each or Doz) usually printed on the order. If a UOM Code is entered, shows the UOM Code Description. If no UOM Code exists, this can be entered.
UOM Selling Price
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
the Price shows the discounted price (Sell Price minus the discount). No discount shows in the
Disc%
field.
If using
Special Pricing
, Price shows the special price according to the rules above.
Disc %
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
GST code for the line. If a GST Override is specified for the customer it will be the default, otherwise it is the GST code from the Product or the Sales Group. The GST Code from the Product takes preference over the GST Code for the Sales Group. It is unusual to change this manually.
Group
The Sales Group the net sale on the line is analysed to when an invoice is generated and posted. If the line does not include a product from IC, type the appropriate Sales Group code or the amount will be analysed to unspecified group code
0000.
To avoid code
0000
, ensure
Allow Unspecified 0000 Sales Analysis Codes
is not selected in
AR Settings
. Search for a sales group using the
Accredo Lookups
.
Amount
The extended line amount. You cannot enter in this field; it is calculated as,
QuantitySupplied x SellingPrice - EnteredDiscount
. Read-only.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Access grid fields in Form view for each line on the grid. Order lines can be entered/edited in the form or on the grid. To view more fields use the scroll buttons or resize the window. See
OE Order Line Fields
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
Sort
(Ctrl+F2)
Sort ascending or descending on a field. Sort order is saved when the Order is saved.
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
(if IC is Installed).
Accredo Saturn Only: Shows quantities at each location, to view stock availability and pending stock movements. Allows juggling stock 'on the fly'.
Special Pricing Information
(Ctrl+4)
Opens
SP Price Query
. You can query the results of a rule applied to a line. If a Special Price is applied, the rule reference displays with other information, depending on the Special Pricing script.
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
The UOM Code for the selected Product.
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
OE Order Line Fields
OE Insufficient Query

---

## OE Sales Orders - Links tab

Source: https://accredo.co.nz/webhelp/OESalesOrders_Links.htm

OE Sales Orders - Links tab
Navigator > Maintain > Order Entry > Enter Sales Orders >
Links tab
See
OE Settings > Misc tab
for options to replicate links on creation of
Backorder from Order
,
Generate Invoice
and
Order From Quote
.

---

## OE Sales Orders - Memos tab

Source: https://accredo.co.nz/webhelp/OESalesOrders_Memos.htm

OE Sales Orders - Memos tab
Navigator > Maintain > Order Entry > Enter Sales Orders >
Memos tab
See
OE Settings > Misc tab
for options to replicate memos on creation of
Backorder from Order
,
Generate Invoice
and
Order From Quote
.

---

## OE Settings - General tab

Source: https://accredo.co.nz/webhelp/OESettings.htm

OE Settings - General tab
Navigator > Setup > Order Entry > Settings > General tab
Determine default settings including back-order, packing slip and invoice generation options. See also
Company Setup
and
IN Settings - General tab
.
Order Lines
Default Order Line Quantity
The default ordered quantity entered on an Order line when a product is selected. Typically it will be set to
zero
so stock availability will only be selected once the ordered quantity is entered. If the ordered quantity for the product is usually
1
, set the default to
1.
Default for Ordered Quantity
Determine the default when entering an Ordered Quantity,
Back Order
,
back order the full quantity ordered.
Supply
,
attempt to supply the full quantity ordered, if there is insufficient stock the action selected below will be followed.
Enforce Ordered Quantity
Selected,
the quantity supplied plus the quantity back ordered is forced to equal the quantity ordered on Order lines, provided the product is available for back-orders and the customer accepts back-orders.
Default If Insufficient Stock
Choose the default when entering an order if insufficient stock is available,
Back Order
,
back order the full quantity ordered.
Supply
,
supply the full quantity ordered, that is, go into negative stock available.
Available
,
supply the available quantity and disregard the balance of the ordered quantity.
Partial Supply
,
supply the available quantity and back-order the balance of the ordered quantity.
Prompt If Insufficient Stock
Selected,
will prompt for the next action on entering an order if insufficient stock is available. The default action selected above will be pre-selected.
Clear,
no prompt if insufficient stock available, the default action specified above will apply and you will receive a hint informing you there was insufficient stock.
Packing Slips and Confirmations
Packing Slip Print Option
Choose the default for orders and Order lines when printing
packing slips
(can override).
Full Orders
,
include orders when all items for the order can be supplied in full.
Full Lines
,
include only Order lines that can be supplied in full - an order is included if at least one line can be supplied in full.
All Lines
,
include all orders and Order lines, whether or not the line can be supplied in full.
Only Print Supplied Lines on Packing Slips
Selected,
Product lines on orders will only print on packing slips if the lines are fully or partly supplied.
Clear,
un-supplied lines are also printed - to show back-order quantities.
This is only relevant if
All Lines
is selected above.
Always Number On Save
Selected,
the next computer generated Packing slip number will be assigned immediately on
Save.
Do this if you require a Packing Slip number before the order is printed (to record it elsewhere).
Allow Manual Packing Slip Nos
Selected,
you can manually type the packing slip number on a sales order.
Clear,
the sales order is given the next available number when the packing slip is printed. This is the default for a new Company.
Always Number On Generate
Selected,
(default and recommended) the next computer generated Packing slip number will be assigned on
Generate Invoice
if not assigned previously.
Clear,
Packing slip numbers are not assigned on
Generate Invoice
.
Always Number On Confirmation
Selected,
(default) the next computer generated Packing slip number will be assigned on
Print Confirmation
if not assigned previously.
Clear,
Packing slip numbers are not assigned on
Print Confirmation
.
Retain Packing Slip No on Generate
Selected,
the packing slip number on a sales order is retained when an Invoice is generated as there are lines on back order. Packing slip count is incremented on Generate an may be printed with the Packing Slip No.
Clear,
the packing slip number on sales order is cleared when an Invoice is generated and there are lines on back order. This is the default for a new Company.
Basis for Fulfilling Back Orders
Choose the default used to select the orders and Order lines to fulfill when
Fulfilling Back Orders
(can override).
Full Orders
,
include orders when all items for the order can be supplied in full.
Full Lines
,
include only Order lines that can be supplied in full.
All Lines
,
include all Order lines which can be at least partially supplied.
Delivery Date Required for Fulfill
Selected,
when
Fulfill Back Orders
is Run, Delivery Date must be specified.
Clear
, Delivery date is optional for
Fulfill Back Orders
.
Generate Invoices
Order Generation Basis
Choose how Order documents will behave when an Invoice is generated and how lines left on back order are treated.
Packing Slip
,
(default), a Packing slip document is generated for the invoiced lines. If lines remain on back order the Order remains unprocessed and packing slip count is incremented. The Order and generated invoice lines are tightly linked, editing the invoice lines is constrained and changes to quantities invoices update back to the source order and packing slip.
Back Order
,
the Order is marked Processed and a new Back Order document is created for any lines on back order. Invoice lines are loosely linked to the source order and editing the invoice has no feedback to the original order. (This is the process which applied in earlier version of Accredo and the default when data is converted from earlier versions.)
Note:
Order Generation Basis can be changed while there are current orders. Any partially invoiced orders will be completed on the old generation basis, any orders which have not been invoiced at all will update to the new generation basis.
Generate for
Choose the default used to select the orders and Order lines to include when
Generating Invoices
(can override).
Full Orders
,
include orders when all items for the order can be supplied in full.
Full Lines
,
include only Order lines that can be supplied in full - an order is included if at least one line can be supplied in full.
All Lines
,
include all orders and Order lines, whether or not the line can be supplied in full.
Generate Invoice Per
Packing Slip
,
(default), new invoice for each source document.
Order
,
add to an Unprinted and Unposted or Held Open invoice with the same Source Order ID if found (prompt when generating from the OE Sales Order Entry form).
Customer
,
add to an Unprinted and Unposted or Held Open invoice for the same Customer if found (prompt when generating from the OE Sales Order Entry form).
See
OE Generate Invoices Per Order or Customer
for restrictions on generating invoices.
Generate For Order Date On Future Orders
Selected
, determine the date and period used when generating invoices from sales orders, when the Order date and Period entered are in the future relative to the Current-OE period.
Generate Credits
Selected,
(default) net negative supplies generate as Credit documents when on
Generate Invoice.
Clear
, net negative supplies generate and negative Invoice documents.
In This Section
OE Generate Invoices Per Order or Customer
OE Settings - Misc tab
OE Settings - Memos tab
OE Settings - Links tab

---

## OE Settings - Links tab

Source: https://accredo.co.nz/webhelp/OESettings_Links.htm

OE Settings - Links tab
Navigator > Setup > Order Entry > Settings > Links tab
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

## OE Settings - Memos tab

Source: https://accredo.co.nz/webhelp/OESettings_Memos.htm

OE Settings - Memos tab
Navigator > Setup > Order Entry > Settings > Memos tab
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
Set the selected memo as the default for OE memos.

---

## OE Settings - Misc tab

Source: https://accredo.co.nz/webhelp/OESettings_Misc.htm

OE Settings - Misc tab
Navigator > Setup > Order Entry > Settings > Misc tab
See also
OE Settings - General tab
.
Order Completion Basis
Processed Only,
(default) Orders become
Historic
when Post Status is set to Processed.
Both Printed and Processed,
Orders become historic when Post Status is set to Processed and Print Status is Printed.
Allow Edit for Posted Order
Selected,
posted Orders can be edited, where the User has permission.
Clear,
posted Orders cannot be edited.
Allow Customer Change After Print
Selected,
Customer can be changed after an Order has been printed.
Clear,
Customer cannot be changed after an Order has been printed.
Allow Packing Slip No change After Print
Selected,
Manual Packing Slip Numbers can be changed after packing slips are printed. This only applies if
Allow Manual Packing Slip Numbers
is selected (see above).
Clear,
Packing Slip Numbers cannot be changed after a Packing Slip has been printed.
Allow Back Orders of Non Diminishing Products
Selected,
Non-diminishing products can be back ordered.
Clear,
Non-diminishing products can not be included in back orders with the exception of non-diminishing components for
Manual Kitsets.
when
Supply Whole Manual Kitsets
is selected in
IN Settings
.
Complete Zero Supply On Generate
Selected
, Generate Invoice will succeed for orders with no supplied or back-ordered quantities. Order will be marked processed and historic. For example, this would be used where a record of the order is required, but the goods and invoice occur through a third party.
Clear
, (default) When Generate is selected for these orders, a 'Nothing to Generate' message will be shown and the order remains unprocessed.
Complete Zero Narrative On Generate
Applies to
Packing Slip
Order Generation Basis
only.
Selected
, Generate Invoice will mark Narrative Lines which do not have a quantity as
Processed
when the entire Order is not marked
Processed
because items remain on Backorder.
Clear
, (default) Generate Invoice only marks Narrative Lines without quantities as
Processed
when the entire order is marked
Processed
.
In all cases only Unprocessed Narrative lines are included on the generated Invoice.
Auto Select
OE Order List
OE Memo List
OE Link List
OE Tracking Log
Selected
, sets the default for Auto Select option on the OE List.
Clear,
(recommended) for large numbers of records and / or slow networks.
Replicate Links and Memos
Back Order from Order Links
Back Order from Order Memos
For Order Generation Basis
Backorder
.
Leave
, Memos / Links remain on the original order, no replication.
Copy,
Memos / Links remain on the original order, and are copied to the back order.
Move,
Memos / Links are moved from the original order to the backorder.
Order from Quote Links
Order from Quote Memos
For Orders created from IN Quotes.
Leave
, Memos / Links remain on the original quote, no replication.
Copy,
Memos / Links remain on the original quote, and are copied to the order.
Move,
Memos / Links are moved from the original quote to the order.
Invoice from Order Links
Invoice from Order Memos
For Invoice Generation.
Leave
, Memos / Links remain on the original order, no replication.
Copy,
Memos / Links remain on the original order, and are copied to the invoice.
Move,
Memos / Links are moved from the original order to the invoice.
Email
Exclude Email Customers
Selected
, if you batch print confirmations, excludes customers with a
Packing Slips
email address when printing confirmations. Confirmations will only be printed for customers with no
Packing Slips
email address.
Email Packing Slips Preferred
Selected,
when
Print Packing Slip
is selected from
OE Enter Sales Orders
, if a packing slip email address is available, (that is,
Email Contact
is selected and the Contact has an email address, or the Customer has a
Packing Slips
email address), the
Destination
field will be set to
Mail Message
not Printer.
Email Confirmations Preferred
Selected,
when
Print Confirmation
is selected from
OE Enter Sales Orders
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
- One email will be sent per email address. If there is more than one order, each will be a separate attachment.
Customer and Email
- One email will be sent per email address per Customer Code. If there is more than one order, each will be a separate attachment.
Consolidate Attachments
Selected,
one attachment containing all orders will be sent per email.

---

## OE View Related Orders

Source: https://accredo.co.nz/webhelp/OEViewRelatedOrders.htm

OE View Related Orders
Navigator > Tasks > Order Entry > Enter Sales Orders >
Related Orders
(
Alt+O
)
Lists all related documents for the sales order, depending on
Order Generation Basis
this may include Back Orders or Packing Slips.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open Details
(F12)
Open document to view and edit details.
Drill Up
(Shift+F11)
Available when the Invoice has been generated. Opens the Invoice.
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
, you can customise the fields visible in the grid. All fields from the Back Order line are available.
Refresh
(F5)
Reloads changes other Users may have made.

---

## OEM

Source: https://accredo.co.nz/webhelp/90.htm#o12741

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

## Order Entry

Source: https://accredo.co.nz/webhelp/OrderEntry.htm

Order Entry
Accounts Receivable (AR) and Invoicing System (IN) must be installed for Order Entry (OE). OE is usually used with Inventory Control (IC). Stock allocated figures are updated when an order is saved. Stock sales figures are not updated until invoices have been generated and posted to AR. You can:
Enter Customer orders, using AR Customer codes and IC Product codes.
Place items not available immediately on back-order.
Fulfill back-orders when stock becomes available.
Print packing slips for orders.
Generate invoices for orders.
Retain an order history for query, reprinting packing slips and
Sales Analysis
.

---

## Order Entry - Maintain

Source: https://accredo.co.nz/webhelp/OrderEntry_Maintain.htm

Order Entry - Maintain
Navigator > Maintain > Order Entry
In This Section
OE Sales Order List
OE Customer Back Orders
OE Memo List
OE Link List

---

## Order Entry - Reports

Source: https://accredo.co.nz/webhelp/OrderEntry_Reports.htm

Order Entry - Reports
Navigator > Reports > Order Entry
In This Section
OE Order Reports - Add Layout
OE Memo Reports - Add Layout
OE Print Confirmations
OE Print Packing Slips
OE Email Confirmations
OE Order Labels

---

## Order Entry - Setup

Source: https://accredo.co.nz/webhelp/OrderEntry_Setup.htm

Order Entry - Setup
Navigator > Setup > Order Entry
In This Section
OE Settings - General tab
OE Change Tracking Log
OE Packing Slip Designer
OE Label Designer
OE Memo Designer
OE Packing Slip/Confirmation Email Designer

---

## Order Entry - Tasks

Source: https://accredo.co.nz/webhelp/OrderEntry_Tasks.htm

Order Entry - Tasks
Navigator > Tasks > Order Entry
In This Section
OE Enter Sales Orders
OE Reprice Sales Orders
OE Fulfill Back Orders
OE Enter Memos
OE Generate Invoices
OE Revalue Foreign Orders

---

