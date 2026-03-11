# Sales Processing (SP)

> Sales reps, commissions, sales analysis and reports

**Sections:** 35

---

## Quick Reference

- [Sales Analysis](#sales-analysis)
- [SP Batch Duplicate](#sp-batch-duplicate)
- [SP Batch Update](#sp-batch-update)
- [SP Change Tracking Log](#sp-change-tracking-log)
- [SP Inactivate Rules](#sp-inactivate-rules)
- [SP Inactivated Rules](#sp-inactivated-rules)
- [SP Populate Selection](#sp-populate-selection)
- [SP Price List - Fields tab](#sp-price-list---fields-tab)
- [SP Price List - Output Selections tab](#sp-price-list---output-selections-tab)
- [SP Price List - Selections tab](#sp-price-list---selections-tab)
- [SP Price List Designer](#sp-price-list-designer)
- [SP Price List Designer - Comment tab](#sp-price-list-designer---comment-tab)
- [SP Price List Designer - Report Preferences tab](#sp-price-list-designer---report-preferences-tab)
- [SP Price List Designer - Users tab](#sp-price-list-designer---users-tab)
- [SP Price Query](#sp-price-query)
- [SP Reports - Add Layout](#sp-reports---add-layout)
- [SP Rule](#sp-rule)
- [SP Rule - Rules & Breaks grids](#sp-rule---rules--breaks-grids)
- [SP Rule Form](#sp-rule-form)
- [SP Rule List](#sp-rule-list)
- [SP Rule List - Designed](#sp-rule-list---designed)
- [SP Rule List Designer](#sp-rule-list-designer)
- [SP Select Rules](#sp-select-rules)
- [SP Settings](#sp-settings)
- [SP Tutorial: Manage SP Rules](#sp-tutorial-manage-sp-rules)
- [SP Who, What, Where grids](#sp-who-what-where-grids)
- [Special Data Object Properties](#special-data-object-properties)
- [Special Pricing](#special-pricing)
- [Special Pricing - Maintain](#special-pricing---maintain)
- [Special Pricing - Reports](#special-pricing---reports)
- [Special Pricing - Settings](#special-pricing---settings)
- [Special Pricing - Tasks](#special-pricing---tasks)
- [Special Pricing & GST](#special-pricing--gst)
- [SpellCheck](#spellcheck)
- [spreadsheet](#spreadsheet)

---

## Sales Analysis

Source: https://accredo.co.nz/webhelp/SalesAnalysis.htm

Sales Analysis
Navigator > Reports > Sales Analysis
Design reports to analyse invoices and orders. These can be grouped, sorted and summarised using
Analysis Report Designer
.
Once you have designed reports they can be saved and added to the Navigator or
Report List
.
In This Section
SA Analysis Report Designer

---

## SP Batch Duplicate

Source: https://accredo.co.nz/webhelp/SPRuleList_BatchDuplicate.htm

SP Batch Duplicate
Navigator > Setup > Special Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
>
Batch Duplicate
button - OR -
Navigator > Maintain > Special Pricing > [Saved Rule List] >
Batch Duplicate
button
Duplicate all Special Pricing Rules in a list, by selecting new values for the duplicate rules.
Fields displayed are based on selection set for the Rule List in in
SP Rule List Designer
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

## SP Batch Update

Source: https://accredo.co.nz/webhelp/SPRuleList_BatchUpdate.htm

SP Batch Update
Navigator > Setup > Special Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
>
Batch Update
button - OR -
Navigator > Maintain > Special Pricing > [Saved Rule List] >
Batch Update
button
Once a rule list has been created, you can update Special Pricing rules in a batch, by selecting values to update for all rules in a list.
Fields displayed are based on selection set for the Rule List in in
SP Rule List Designer
.
When changes are made to fields, the Selection button beside the field is ticked. Selected fields will be updated on save.
Save
(F9)
Apply the values in all the
Selected
fields to all Special Pricing rules in the rule list.
Cancel
(Esc)
Cancel all changes.

---

## SP Change Tracking Log

Source: https://accredo.co.nz/webhelp/SpecialPricingTrackingLog.htm

SP Change Tracking Log
Navigator > Setup > Special Pricing >
Change Tracking Log
See Also
Special Pricing - Settings

---

## SP Inactivate Rules

Source: https://accredo.co.nz/webhelp/SPInactivateRules_Selections.htm

SP Inactivate Rules
Navigator > Tasks > Special Pricing > Inactivate Rules
Inactivate Special Pricing Rules which have expired or have Inactive criteria.
Selections
Customer
Select a Customer to limit Special Pricing Rules to inactivate, or leave blank to inactivate selected rules for all Customers.
Product
Select a Product to limit Special Pricing Rules to inactivate, or leave blank to inactivate selected rules for all Products.
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
Apply or clear further filters on SP fields to limit rules to inactivate. The button changes to indicate if a filter and sort is applied.
Button
Run
(F9)
Inactivate rules meeting the criteria specified. Displays the Inactivated Rules.
In This Section
SP Inactivated Rules
See Also
Special Pricing - Tasks

---

## SP Inactivated Rules

Source: https://accredo.co.nz/webhelp/SPInactivatedRules.htm

SP Inactivated Rules
Navigator > Tasks > Special Pricing > Inactivate Rules >
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
SP Rule Form
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
Bypass
Selected,
the rule will bypass the Minimum Margin set in
SP Settings
.
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
SP Rule
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
See Also
SP Inactivate Rules

---

## SP Populate Selection

Source: https://accredo.co.nz/webhelp/SPPopulateSelection.htm

SP Populate Selection
Navigator > Maintain > Special Pricing > Select Rules >
Run
>
Populate Grid
(Ctrl+G
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

## SP Price List - Fields tab

Source: https://accredo.co.nz/webhelp/SPPriceList_Fields.htm

SP Price List - Fields tab
Navigator > Reports > Special Pricing > Price List Designer > Fields tab
Select the fields to include on the report.
See also
SP Price List Designer
.
Field Name
Select fields from those available in the drop-down menus, from the Product and the Special Price.
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
If UOM is Pending or Active, you can select a UOM Code for Special Price fields. If a UOM Code is specified, prices returned will be UOM Prices. If Quantity Breaks are available and a UOM Code is specified, Quantities returned will be UOM Quantities. If a product does not have the UOM Code specified, nothing will be returned.
Quantity
If you use quantity breaks, enter a quantity you want a price for. The quantity is only available if the field selected is from the SP rule. If you do not use quantity breaks, the Quantity field is unavailable for fields.
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

## SP Price List - Output Selections tab

Source: https://accredo.co.nz/webhelp/SPPriceList_Output.htm

SP Price List - Output Selections tab
Navigator > Reports > Special Pricing > Price List Designer > Output Selections Tab
Set the output defaults for the report.
Set the default destination for the report.
Enter the report title and any comments to be printed at the top of the report.
Specify the report destination and some fixed text to print on the report.
See also
SP Price List Designer
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

## SP Price List - Selections tab

Source: https://accredo.co.nz/webhelp/SPPriceList_Selections.htm

SP Price List - Selections tab
Navigator > Reports > Special Pricing > Price List Designer > Selections tab
Use the Selections tab to define the records to include in the report and the selections available when the report is run.
See also
SP Price List Designer
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
To include a selection in the report selections toggle
to
next to the selection.
What
Select a range of Products or Stock Groups to obtain a Price List. If no Special Price applies, the regular price is used. The Price List will show prices for all Products in the selected range. You can
filter
the list.
When
Effective Date
and
Currency
selections are always included in report selections. Dates saved in the report definition are handled as an offset from the System Date.
Who
Select a Customer or Job and Price Code for the Price list. When you select a Customer or Job,
Who
selections populate from Customer dimensions (for example, Sales Area or AR Category) or Job (for example, Job Group or JC Category).
Who
selections are based on dimensions setup in the
Who grid
.
If Invoicing dimensions are available (for example, IN Category), select the relevant criteria as these are independent of the Customer and Job records. If selections are left blank, rules depending on that criteria will be ignored. For example, if you do not specify an IN Category 1, rules where IN Category 1 is one of the Who criteria will be ignored.
Where
Where
selections  are based on dimensions setup in the
Where grid
.
Filter Report
The report may be filtered, for example filter on SpecialPriceApplied to only report records where the customer receives a special price.

---

## SP Price List Designer

Source: https://accredo.co.nz/webhelp/SPPriceList_Designer.htm

SP Price List Designer
Navigator > Reports > Special Pricing > Price List Designer
The Price List Designer separates the design and running of price list reports. Use the Price List Report Designer to create price list reports based on special pricing rules.
Access requires permission for the Designer and Control permission for Reports.
You can add designed reports to a Report List or the Navigator.
Price list reports are designed for a Customer and a range of Products.
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
to the SP Designer and SP Reports.
In This Section
SP Price List - Selections tab
SP Price List - Fields tab
SP Price List - Output Selections tab
SP Price List Designer - Report Preferences tab
SP Price List Designer - Users tab
SP Price List Designer - Comment tab

---

## SP Price List Designer - Comment tab

Source: https://accredo.co.nz/webhelp/SPPriceList_Comment.htm

SP Price List Designer - Comment tab
Navigator > Reports > Special Pricing > Price List Designer > Comment tab
See also
SP Price List Designer
.
You can annotate Price List definitions. View the purpose, document filter, or selection changes for the Price List.
This is for documenting the Price List definition - do not confuse it with the Report Comment on the Output Selections tab, which is printed on the Price List.

---

## SP Price List Designer - Report Preferences tab

Source: https://accredo.co.nz/webhelp/SPPriceList_ReportPreferences.htm

SP Price List Designer - Report Preferences tab
Navigator > Reports > Special Pricing > Price List Designer > Report Preferences tab
Select formatting options for the report.
See also
SP Price List Designer
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

## SP Price List Designer - Users tab

Source: https://accredo.co.nz/webhelp/SPPriceList_Users.htm

SP Price List Designer - Users tab
Navigator > Reports > Special Pricing > Price List Designer > Users tab
Reports are available to all users with permissions by default. You can enter a list of Users or Groups to make the report available to only the users listed.
See also
SP Price List Designer
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

## SP Price Query

Source: https://accredo.co.nz/webhelp/SPPriceQuery.htm

SP Price Query
Navigator > Maintain > Special Pricing > Price Query
View Special Pricing results for a customer. SP Price Query also opens when you select
Special Pricing Information
(Ctrl+4)
from Order lines, Invoice lines, Job Estimates and Job transactions. This is useful for:
Testing the results of a new rule.
Querying the results of a rule applied during document or transaction entry.
Providing information to a customer.
Note:
Where
criteria are only available in Accredo Saturn.
Who, What, Where Details sections
Enter data to base a query on. When you select
Special Pricing Information
(Ctrl+4)
, the fields populate data from the document or transaction, and you can view
Pricing Results
.
Who
If Special Pricing is applied in
SP Settings
for:
IN
and
OE
, the Customer field is available in the Who section.
JC
, the Job field is available in the Who section.
Select a code in one of the fields to obtain a result when you click
Query
(F9). Other fields available in the Who section are based on dimensions in the
Who grid
.
When you select a customer or job,
Who
criteria populates from the customer (for example, Sales Area, AR Category) or job (for example, Job Group, JC Category).
If Invoicing dimensions are available (for example, IN Category), select the relevant criteria as these are independent of the Customer and Job records.
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
. If Where dimensions are available, (for example, Branch, Department or Location), select the criteria as these are independent of the customer, job and product records. You can leave
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
Default Sales UOM
.
Quantity
- enter the number of items to query if you use Quantity Breaks.
Date
- enter the date to query if you use Start and End dates for Special Pricing.
Currency
- Read-only, based on the Customer details.
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
to show the SP prices. The Pricing Script set in
SP Settings
will be executed. Pricing Scripts can be edited in the
SP Pricing Script Editor
.
Pricing Results grid fields are:
Initial:
Sell / UOM Sell
Discount %
Cost / UOM Cost
When a Customer or Job and a Product code is entered, shows:
The Selling Price and Discount for the selected Customer or Job on the selected product.
The Cost Price of the product.
If the product is Manually Costed, or the special pricing relates to JC and IC Cost Prices are not Enforced, this will be the cost price from the context to preserve any edit made to the cost price.
These are the initial prices before the special pricing is applied. If
UOM
is
Active
or
Pending
, the UOM figures are shown.
Special:
Sell / UOM Sell
Discount %
Cost / UOM Cost
This shows the "winning" special prices that will be applied. The fields show the Special Selling Price, Discount and Cost Price if the result rule shown in the Rules grid were applied for the selected customer or job on the selected product.
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
Shows all prices considered for the pricing decision, including the initial price, ranked according to priorities applied by the SP Script. The result rule is at the top of the list of active rules. The initial price is at the bottom of the list, and does not have a Rule ID.
For information on the fields, see
SP Rule
.
If a rule is dimmed and there is a tick in the
Disallow
field, it has been disallowed because the margin is below that specified in
Special Pricing Settings
, and the rule has not been setup to bypass the minimum margin in
SP Rule
. Disallowed rules can appear above the result rule in the list, depending on their ranking.
Message
Shows a status hint when the rule is applied during document or transaction entry.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens
SP Rule
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

## SP Reports - Add Layout

Source: https://accredo.co.nz/webhelp/SPReports.htm

SP Reports - Add Layout
Navigator > Reports > Special Pricing > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Rule List
List the Special Pricing rules setup in
SP Rule
. Select options to filter by rule types, dates or Reference.

---

## SP Rule

Source: https://accredo.co.nz/webhelp/SPRuleMaintenance.htm

SP Rule
Navigator > Maintain > Special Pricing > Select Rules >
Run
(F9)
See also
SP Rule - Rules & Breaks grids
.
Criteria entered in
SP Select Rules
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
Duplicate rules in the Rules grid to edit and save. For example, you can use this to add similar Special Pricing for customers who are not part of a group.
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
Customer -
specify a
Who
Type
of
Customer
, select the Customer
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
, the select the individual
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
SP Settings
, one pair of fields is available; if set to
2
, a second pair of fields will be available.
Where fields are only shown if Where types are made available in the
SP Where grid
.
Warning: If a Special Pricing rule is added that does not require a
Who
dimension (for example, monthly Product specials), or the Price code is not explicit in the
Who
dimension, you can include Price List as a
Who
dimension and create rules for GST inclusive and exclusive pricing. See
Special Pricing & GST
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
SP Select Rules
. You can use this to filter when loading rules or to identify new rules. For example, you could enter
Contract
in this field for contract pricing rules.
Comment
Add up to 60 characters, use a filter in SP Select Rules to select rules by comment.
Rule Type
Select the rule type from:
Fixed
- Special Price = the Amount and Discount percentage.
Cost Relative
- Special Price = Cost Price plus the Amount and / or the Markup Percentage. If both an Amount and Markup Percentage are entered, the Amount is added first, then the Markup Percentage is applied.
Sell Relative
- Special Price = Sell Price less the Amount and / or the Discount Percentage. If both an Amount and Discount Percentage are entered, the Amount is subtracted first, then the Discount Percentage is applied.
This defaults from
SP Settings
.
Base Cost
Select the Base Cost to use when calculating a
Cost Relative
price, from:
Valuation Cost
- (default), use the cost specified in the Valuation Basis field in IC Settings.
Standard Cost
- use the Standard cost. Use if costs fluctuate to offer guaranteed pricing. If selected, reset standard costs often.
Latest Cost
- use the Latest cost.
Average Cost
- use the Average cost.
This defaults from
SP Settings
.
Base Sell
The base Selling Price Code default when calculating a
Sell Relative
price. Select a Price code or leave blank to use the Price code from the Customer record.
This defaults from
SP Settings
.
Priority
Determines priority if more than one rule applies to a transaction line.
1
is highest priority,
9
is lowest. Default is set to the highest priority from Who, What, Where criteria selected in the Header. If two or more rules share the same priority, the lowest price applies. You can modify this by creating a script based on the default (SPDefault.pfs) in
SP Script Editor
. If a priority is not set and the lowest price must apply, leave the priority for all rules set to
9.
Hint: You can reserve priority
1
for a rule to override all others (for example, contract pricing, when no other discounts or specials apply).
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
Duplicate a set of rules for one Customer and apply them to another Customer.
Make a group of Active rules Inactive, or make a group of Inactive rules active.
Change the
End date
for a group of rules.
Populate grid
(Ctrl+G)
Opens the
SP Populate Selection
form. The grid will be populated with one new line for each Code specified. Use the
From
and
To
fields to select a range of Codes, or use the
Filter
(F2)
button to select Codes.
For example, you can use this to offer a Special Price for:
Customers who spent more than a certain dollar value in the previous month.
A large number of different Products that are not part of a group.
Buttons
Print
(Ctrl+P)
Print an SP Rule Edit  report of the information in the grid(s).
Save
(F9)
Save changes to the rules.
Cancel
(Esc)
Cancel the edit without saving changes.
Rules and Breaks grids
See
SP Rule - Rules & Breaks grids
.
In This Section
SP Rule - Rules & Breaks grids
SP Populate Selection

---

## SP Rule - Rules & Breaks grids

Source: https://accredo.co.nz/webhelp/SpecialPricingRules_Grid.htm

SP Rule - Rules & Breaks grids
Navigator > Maintain > Special Pricing > Select Rules >
Run
> Rules & Breaks grids
See also
SP Rule
.
Rules will match the criteria selected from
SP Select Rules
. New rules added during the session are also shown. If you setup
Quantity Breaks
in
SP Settings
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
Special Price = the Amount and Discount percentage.
Cost Relative -
Special Price = Cost Price plus the Amount or the Markup Percentage. If both an Amount and Markup Percentage are entered, the Amount is added first, then the Markup Percentage is applied.
Sell Relative -
Special Price = Sell Price less the Amount or the Discount Percentage. If both an Amount and Discount Percentage are entered, the Amount is subtracted first, then the Discount Percentage is applied.
Default values are set in
SP Settings
.
Note: A Cost Relative Rule must have either an Amount or a Percentage specified or Bypass Minimum Margin selected to be saved.
Base Cost
Select the Base to use Cost when calculating a Cost Relative price from:
Valuation Cost -
(default), use the cost specified in the
Valuation Basis
field in IC Settings.
Standard Cost -
use the Standard cost. Use if costs fluctuate to offer guaranteed pricing. If selected, reset standard costs often.
Latest Cost
- use the Latest cost.
Average Cost -
use the Average cost.
Default values are set in
SP Settings
.
Base Sell
The base Selling Price when calculating a Sell Relative price. Select a Price code or leave blank to use the Price code from the Customer record.
Default values are set in
SP Settings
.
Bypass
Selected,
the rule will bypass the Minimum Margin set in
SP Settings
.
Currency
The currency the rule is applied in.
Amount / Percentage
The amount or percentage applied. The table shows the results of a selection based on Rule Type.
Rule Type
Amount
Percentage
Fixed
Enter the Special Price. If Amount is
blank,
the usual price is used.
Enter the percentage (discount) to deduct from the special price in the Amount field. For a Product giveaway, leave the Amount field blank, enter 100% in this field.
Cost Relative
Enter the Amount (Markup) to add to the specified Base Cost.
Enter the Percentage (Markup) to add to the Base Cost. If an Amount and Percentage are entered, the Amount is added first, then the Markup Percentage is applied.
Sell Relative
Enter the amount (Discount) to subtract from the specified Sell Price.
Enter the Percentage (Discount) to deduct from the Sell Price. If an Amount and Percentage are entered, the amount is subtracted first, then the discount percentage applied.
When Quantity Breaks is selected, and rows are added to the Breaks Grid, the Amount and Percentage fields will be unavailable. Enter Amounts and Percentages in the Breaks Grid.
Effective Price.
The Price the specified Customer will pay for the specified Product from the specified Branch, Department or Location (Accredo Saturn Only). This is calculated by applying the Rule Type, Amount and Percentage. This will only be calculated if the rule includes a Product Code.
If you use Quantity Breaks (set in
SP Settings
), this field is also available on the Breaks grid.
Hint: you can compare this with the standard Effective Price in the Information Panel see below.
Effective Margin
Profit margin based on the Rule Type, Amount and / or Percentage specified previously, that is, what you will make on each Product sold for the
Effective Price.
This figure only calculates if the rule includes a Product code. If you use Quantity Breaks (set in
SP Settings
), this field is also available on the
Breaks
grid.
Hint: it can be useful to compare this amount with the Effective Margin in the Information Panel see below.
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
SP Settings
).
Prompt for Delete Line On/ Off
(Shift+F3)
Toggle on and off to specify whether to confirm deletes. The default state is set in
Users, Groups and Roles - Preferences tab
.
Information panel
The standard prices for the Product (and Customer) are shown, where a Product has been selected. You can compare Special Pricing entered with standard prices.
Cost
The current valuation cost of the specified Product.
Sell
The standard Sell Price for the Product, if a Customer is specified.
Discount
The standard discount that applies to the specified Product if a Customer is specified.
Effective Price
The standard price the specified Customer would pay for the specified Product.
Effective Margin
The standard profit margin for the Product.
Breaks grid
This displays when
Quantity Breaks
is selected in
SP Settings
.
You can apply different prices for a single rule using Quantity breaks, depending on the quantity of items sold. The Breaks grid shows quantity breaks for the rule row selected (highlighted) in the Rules grid.
Set different pricing breaks based on Quantity, using the Amount and Percentage fields.
UOM Code
(
UOM
Active or Pending)
The UOM Code for the Product that must be used to qualify for the special price. If a UOM Code is entered for a Break, UOM Codes must be entered for all Breaks for the Rule.
Warning: Only enter a
UOM Code
if you want the Break to apply only when that
UOM Code
is specified on the line. If you want a Break to apply based on quantities, regardless of the UOM Code, leave this field blank.
Min Quantity
The minimum number of Products which must be purchased to qualify for the special price.
Hint: If only one quantity break is required, customise the Min Quantity field into the Rules grid, to work in one grid rather than two.
Amount / Percentage / Effective Price / Effective Margin
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

## SP Rule Form

Source: https://accredo.co.nz/webhelp/SPRuleForm.htm

SP Rule Form
Navigator > Setup > Special Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
>
Insert
(F4)
- OR -
Navigator > Setup > Special Pricing > Rule List Designer > [Make Selections] >
Run
(F9)
> [Select Rule] >
Open
(F12)
or Double-Click - OR -
Navigator > Maintain > Special Pricing > [Saved Rule List] >
Insert
(F4)
- OR -
Navigator > Maintain > Special Pricing > [Saved Rule List] >
Open
(F12)
or Double-Click
Opens a Special Pricing Rule in the Rule Form.
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
The standard prices for the Product are shown, where a Product has been selected. You can compare Special Pricing entered with standard prices.
Cost
The current valuation cost of the specified Product.
Sell
The standard Sell Price for the Product, if a Customer is specified.
Discount
The standard discount that applies to the specified Product if a Customer is specified.
Effective Price
The standard price the specified Customer would pay for the specified Product.
Effective Margin
The standard profit margin for the Product.
Breaks grid
This displays When
Quantity Breaks
is selected in
SP Settings
.
You can apply different prices for a single rule using Quantity breaks, depending on the quantity of items sold. The Breaks grid shows quantity breaks for the rule selected in the Rules grid.
Set different pricing breaks based on Quantity, using the Amount and Percentage fields.
Min Quantity
The minimum number of Products which must be purchased to qualify for the special price.
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

## SP Rule List

Source: https://accredo.co.nz/webhelp/SPRuleList_Form.htm

SP Rule List
Navigator > Maintain > Special Pricing > Rule List
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
SP Rule
where it may be edited.
Selections
Who, What, Where
You can have 1 or 2
Who
and
What
criteria rows, set in
SP Settings
.
Select from Types set in the
Who, What, Where grids
, or leave blank to select all rules.
Where fields are only shown if Where types are made available in the
SP Where grid
.
When
Start and End dates apply a rule for a limited time, (for example, weekly, monthly specials). Specify the start and end dates to show rules for, or leave blank to show all rules.
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
SP Settings
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
SP Rule
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
SP Rule
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

## SP Rule List - Designed

Source: https://accredo.co.nz/webhelp/SPRuleList_Designed.htm

SP Rule List - Designed
Navigator > Setup > Special Pricing > Rule List Designer >
Run
(F9)
Make selections in the SP Rule List Designer tabs then click
Run
, to view special pricing rules matching the criteria. Selections available are dependent on options set in
SP Rule List Designer
for the rule list. Only rules matching the selections are displayed.
To view saved rule lists, go to:
Navigator > Setup > Special Pricing > Rule List Designer > Load > [Select Rule List file] >
Run
(F9)
- OR -
Navigator > Maintain > Special Pricing > [Saved Rule List]
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
SP Rule Form
.
Delete
(F3)
Deletes the selected rule.
Open
(F12)
Open to view and edit, or double click to view and edit a Rule. Displays the rule in
SP Rule Form
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
SP Rule Form
SP Batch Update
SP Batch Duplicate

---

## SP Rule List Designer

Source: https://accredo.co.nz/webhelp/SPRuleDesigner.htm

SP Rule List Designer
Navigator > Setup > Special Pricing > SP Rule List Designer
Use the SP Rule List Designer to create lists of SP Rules, and add and maintain SP Rules. You can use SP Lists to maintain sets of Special Pricing rules. You can save the lists as definition files, then add them to the Navigator for viewing.
Note:
Where
criteria is only available in Accredo Saturn.
See also the
SP Tutorial: Manage SP Rules
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
For
Sell Relative
rules, select a
Base Sell
for the rules.
Who, What, Where
Select criteria for the rules.
List Maintenance Title
The caption for the Special Pricing List.
Allow Bypass Minimum Margin
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
Selections will appear in the Rule List. If you lock a selection (From Code / To Code must be the same or Code specified for a single selection) it will not appear when the list is Run, only rules for the specified code can load, be edited or inserted.
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
This becomes available when a Rule List definition has been saved. The default location for Rule Lists is Navigator > Maintain > Special Pricing > [List Maintenance Title].
Run
(Alt+R)
Runs the
SP Rule List
and confirms the rules load as expected.
Load...
(Alt+L)
Load an existing Rule List from file.
Save...
(Ctrl+S)
Saves the Rule List definition. The default file location is:
AccredoSaturn\Forms\SPRule
AccredoMercury\Forms\SPRule
In This Section
SP Rule List - Designed
SP Tutorial: Manage SP Rules

---

## SP Select Rules

Source: https://accredo.co.nz/webhelp/SPRuleSelection.htm

SP Select Rules
Navigator > Maintain > Special Pricing > Select Rules
Select criteria to view rules for, or leave the
Who
,
What, Where
and
When
fields blank to show all rules. Rules will be shown in
SP Rule
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
SP Settings
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
Start and End dates apply a rule for a limited time, (for example, weekly, monthly specials). Specify the start and end dates to show rules for, or leave blank to show all rules.
Selections and buttons
Reference
When entered, returns Rules with a matching Reference. For example, enter "
Contract
" in the Reference field for contract pricing rules.
Include Rules
Select the rules to load. Clearing both selections will open the SP Rule form with no rules loaded if you are entering new rules rather than editing existing ones.
You can load Inactive rules to base new rules on, reinstate later, or to maintain a Special Pricing history.
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
SP Rule
.
In This Section
SP Rule
See Also
Special Pricing - Maintain

---

## SP Settings

Source: https://accredo.co.nz/webhelp/SPSettings.htm

SP Settings
Navigator > Setup > Special Pricing > Settings
Select to turn Special Pricing on or off and set defaults.
Apply Special Pricing
Selected
, makes Special Pricing active in IN, OE and JC. You can leave Special Pricing inactive, setup rules, then make it active when the rules are entered and tested. See
How Special Pricing works
for more detail.
The default is inactive (
Clear
).
Minimum Margin
Set the minimum margin. This can be overridden for a specific rule.
Default Rule Type
Specify the default Rule Type to appear in
SP Rule
:
Fixed -
Special Price = the Amount and Discount percentage.
Cost Relative -
Special Price = Cost Price plus the Amount and / or the Markup Percentage. If both an Amount and Markup Percentage are entered, the Amount is added first, then the Markup Percentage is applied.
Sell Relative -
Special Price = Sell Price less the Amount and / or the Discount Percentage. If both an Amount and Discount Percentage are entered, the Amount is subtracted first, then the Discount Percentage is applied.
Default Base Cost
Select the default Base Cost when calculating a Cost Relative price, from:
Valuation Cost -
(default), use the cost specified in the
Valuation Basis
field in IC Settings.
Standard Cost -
use the Standard cost. Use if costs fluctuate to offer guaranteed pricing. If selected, reset standard costs often.
Latest Cost
- use the Latest cost.
Average Cost -
use the Average cost.
Note: For
Manually Costed
Products and for Job Costing transactions when the
Enforce IC Cost Price
setting is not selected, the Cost Price passed to the SP Context is the Cost Price from the line or transaction, not re-read from the Product Record.
Default Base Sell
The base Selling Price Code default when calculating a Sell Relative price. Select a Price code or leave blank to use the Price code from the Customer record.
Who Criteria Count
The maximum number of Who criteria to apply to SP rules. Set the smallest number to reduce the amount of processing required for a rule.
1
(default) is usually adequate. Select up to
2
Who criteria, for example, to apply rules to Customers in a Buying group and in a specific Sales Area.
What Criteria Count
The maximum number of What criteria to apply to SP rules. Set the smallest number to reduce the amount of processing required for a rule.
1
(default) is usually adequate. Select up to
2
What criteria, for example, to apply rules to Products in a Stock Group and from a specific Creditor.
Use Quantity Breaks
Selected
, displays the Breaks grid in
SP Rule
and
SP Rule Form
. If Quantity Breaks are used you can specify different prices for a single rule depending on the quantity of items sold. If Quantity Breaks are not used you can specify a Special Price for each rule regardless of the quantity of items sold.
Apply on Manual Cost Changes
Selected
, for
Manually Costed
Products and for Job Costing transactions when the
Enforce IC Cost Price
setting is not selected, changing Cost Price will trigger Pricing. Select this option if you have Cost Relative pricing rules which apply to Manually Costed Products or Jobs.
Cost Relative Inclusive Sell Prices
Selected,
for Cost Relative Rules, if the Context Sell Price Basis is Inclusive, then GST is added to the Effective Price using the GST Code for the Product. This means you can use one cost relative rule to return the same effective price regardless of whether the Context is working with Inclusive or Exclusive Sell Prices.
Sell Relative Mixed Basis Prices
Selected,
for Sell Relative Rules, if the Context Sell Price Basis differs from the GST Basis for the Price Code in the Rule, e.g. Customers price list is Inclusive and Price Code specified in the special price rule is Exclusive, or vice versa, then GST is automatically added / deducted. This means you can use one sell relative rule to return the same effective price regardless of whether the Context is working with Inclusive or Exclusive Sell Prices.
This is designed to work with the standard SPDefault.pfs script. If your Pricing Script has been modified to handle mixed basis, do not select this option.
Allow Inactive Criteria
Selected,
allows inactive Criteria codes for Active Rules when saving Special Pricing rules.
Unselected
, saving an Active Rule with Inactive Criteria is prevented.
Note: Since Rules with Inactive Criteria will never be collected, it is recommended that this should be Unselected after any Rules with Inactive Criteria are identified and
Inactivated
.
Pricing Script
Select the definition file for the Special Pricing script to determine how it is collected, ranked and applied.
The default Pricing Script is
SPDefault.pfs
. This ranks rules by priority, and chooses the lowest price. Use
SP Script Editor
to edit a script or create a custom definition.
To add a Bill To Customer to the Who grid, use the provided script
SPDefaultWithBillTo.pfs
.
Auto Select
SP Tracking Log
SP Rule List
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

## SP Tutorial: Manage SP Rules

Source: https://accredo.co.nz/webhelp/SPTutorialManageSPRules.htm

SP Tutorial: Manage SP Rules
This tutorial will show you how to manage your Special Pricing rules using Rule Definitions, which can be added to the Navigator for easy viewing and maintenance. This tutorial can be run on the Accredo Demo data. It will create a simple SP Rule Definition for contract pricing for the customer ASHENG.
Note:
Where
criteria is only available in Accredo Saturn.
Go to Navigator > Setup > Special Pricing > Rule List Designer.
Set the
Who Type 1
as
Customer
, and the
What Type 1
as
Product
.
Note: You can select which fields to make available for SP Rules from the
SP Who, What Where Grids
.
Enter a
List Maintenance Title
, such as
Asheng Contract Sept
.
Click to
Select
Auto Select Rules
, so the rules will be automatically be selected when the definition is run.
Go to the Selections tab.
In the Who panel, select
ASHENG
in the Customer
From
and
To
fields, to only apply the pricing to this customer.
In the What panel, select a range of Products, such as
From
1.8MWARDROBE,
To
BLANKBOX
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
). Any rules that meet the criteria on the Selections tab will be shown in the SP Rule List.
To add a new rule, click
Insert
(
F4
). The
SP Rule
window will open.
Enter a
Start Date
and
End Date
for when the Rule will be applied, such as
1 Sept
to
30 Sept
.
In the Breaks section, enter an Amount as the special price to be applied for this Product for this Customer between the dates entered above, such as
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
You can continue adding rules for more products. When you have finished, close the SP Rule window.
The new rules are shown in the SP Rule List window. Close the SP Rule List window.
In the SP Rule List Designer, click
Save...
(
Ctrl+S
) to save the Rule Definition File. Enter a file name, such as
Asheng Contract Sept
.
Click
Add to Navigator...
(
Alt+N
).
The Script Shortcut Editor window opens. By default the Rule List is added to the Navigator under Maintain > Special Pricing. Click
Save
(
F9
).
Close the SP Rule List Designer window.
Go to Navigator > Maintain > Special Pricing >  Your Rule List will be available. Select your Rule List. It will open in SP Rule List.
You can use this to make review Rules and to make any changes.

---

## SP Who, What, Where grids

Source: https://accredo.co.nz/webhelp/SPWhoWhatWhere.htm

SP Who, What, Where grids
Navigator > Setup > Special Pricing > Who, What, Where grids
Setup the Types of criteria available in setting Special Pricing rules in the Who, What, Where dimensions. For example, if Special Pricing relates to products for specific customers, make
Customer
criteria available in the
Who
dimension and
Product
criteria available in the
What
dimension. You can turn criteria off and on as needed.
Some criteria are determined by others, for example, when you select a Customer in the
Who
dimension, the Sales Area, Sales Person, Price Code, Discount and AR Categories are determined by the customer record. Other criteria such as Invoice Categories and Job Categories are independent of the Customer record and are not affected, as they relate to the invoice or job.
Special Pricing is not applied to Auto Kitset lines. To apply Special Pricing to Product groups, setup Manual Kitsets from
IC Component
.
Note:
Where
criteria is only available in Accredo Saturn.
Specify criteria and priority for the following Special Pricing dimensions:
Who grid
Select customer or job-related criteria to specify rules for.
What grid
Select product-related criteria to specify rules for.
Where grid
Select branch, location or department criteria to specify rules for.
Note: If no Where criteria are made available, the Where fields will not be shown in SP Select Rules and SP Rule.
Fields
Type
Lists the available criteria Types, that can be selected when setting Special Pricing rules.
Available
Only Available criteria Types will be available when setting Special Pricing rules in
SP Rule
.
We recommend you enable only the SP Criteria you need in order to add the rules you require.
Default Priority
Setup criteria Priority to determine which rule takes precedence if more than one rule applies to a Transaction line. For example, you can make rules relating to Contract Customers a higher priority than rules relating to monthly product specials).
1
is the highest priority,
9
lowest. Priorities can be changed from their defaults in
SP Rule
.
If two or more rules are tied at the same priority, the lowest price is applied (default). You can modify this by creating a script based on the default in
SP Pricing Script Editor
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
SP Rule
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
See Also
Special Pricing - Settings

---

## Special Data Object Properties

Source: https://accredo.co.nz/webhelp/SpecialDataObjectProperties.htm

Special Data Object Properties
Some data objects have properties which require clarification:
AllowInactive
A boolean property, default false. Set True to disable inactive join checking for Active records, e.g. on JCJobData when setting JobStatus to Complete and saving the record prior to Inactivating a Job if the save is failing due to inactive categories, contacts, customer etc.
InactiveAllowed
A calculated boolean property on masterfile data objects. Returns a value based on the information directly available, e.g. For JCJobData is the saved JobStatus Complete, it does not guarantee that making a record Inactive would succeed, it indicates that is worth trying to make the record inactive and further validation across related records will occur on save. We recommend using a
Try Catch
statement and reporting the Code and Error if Inactivating fails.

---

## Special Pricing

Source: https://accredo.co.nz/webhelp/SpecialPricing.htm

Special Pricing
Use Special Pricing (SP) to setup and track pricing structures outside the standard Accredo Price codes and discount schedule, including:
Contract pricing and discounts.
Buying groups.
Staff discounts.
Monthly, weekly, regular specials.
Supplier specials.
Quantity breaks.
Agreed one-off prices.
Cost prices for Manually Costed Products.
Setting up Special Pricing
Who, What, Where
dimensions and criteria.
Special Pricing rules apply as each line of a document is entered or repriced. A message appears when a special price is applied, and you can view the pricing rule. You can also use the
Discount Schedule
to setup the
Discount Mode
for order and invoice information.
Special Pricing rules apply in Job Costing if Pricing Mode iin
JC Settings
is set to Selling Price.

---

## Special Pricing - Maintain

Source: https://accredo.co.nz/webhelp/SpecialPricing_Maintain.htm

Special Pricing - Maintain
Navigator > Maintain > Special Pricing
In This Section
SP Select Rules
SP Rule List
SP Price Query

---

## Special Pricing - Reports

Source: https://accredo.co.nz/webhelp/SpecialPricing_Reports.htm

Special Pricing - Reports
Navigator > Reporting > Special Pricing
In This Section
SP Price List Designer
SP Reports - Add Layout

---

## Special Pricing - Settings

Source: https://accredo.co.nz/webhelp/SpecialPricing_Settings.htm

Special Pricing - Settings
Navigator > Settings > Special Pricing
In This Section
SP Settings
How Special Pricing Works
SP Change Tracking Log
SP Who, What, Where grids
SP Script Editor
SP Rule List Designer

---

## Special Pricing - Tasks

Source: https://accredo.co.nz/webhelp/SpecialPricing_Tasks.htm

Special Pricing - Tasks
Navigator > Tasks > Special Pricing
In This Section
SP Inactivate Rules

---

## Special Pricing & GST

Source: https://accredo.co.nz/webhelp/SpecialPricingAndGST.htm

Special Pricing & GST
If you have both GST Inclusive and GST Exclusive
Price codes
, GST on Special Prices is determined by the Price code for each document (Invoice, Order or Job) in which Special Pricing is applied. If the Price code is GST Inclusive, Special Pricing will include GST. If the Price code is GST Exclusive, Special Pricing will exclude GST. This can have a significant effect on prices and margins, as shown in the example below, where the special price of an item is $300.00 and the Cost Price is $248.00.
Cost Price
Special (net)
GST
Special (gross)
Profit
Margin
Price List Inclusive
$248.00
$260.87
$39.13
$300.00
$12.87
4.9%
Price List Exclusive
$248.00
$300.00
$45.00
$345.00
$52.00
17.3%
Warning: to avoid altering the prices by a significant amount, consider the effect that a different GST basis can have on Special Pricing.
If you add a Special Pricing rule that does not require a Who dimension (for example, monthly Product specials), or the Price code is not explicit in the Who dimension, you can include Price Code as a Who dimension and create separate rules for GST inclusive and exclusive pricing. If you change the Price code on an Invoice, Order or Job; change the default Price code for a Customer; or change the GST basis for a Price code; adjust Special Pricing rules accordingly.

---

## SpellCheck

Source: https://accredo.co.nz/webhelp/MBSpellCheck.htm

SpellCheck
method
SpellCheck
Available for Memos. Activate the Spell Check on the memo.
For example:
eMemo1.SpellCheck
See Also
Form Designer Memo Methods

---

## spreadsheet

Source: https://accredo.co.nz/webhelp/90.htm#o5594

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

