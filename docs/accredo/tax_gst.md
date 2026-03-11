# Tax & GST

> GST, tax codes, tax rates, tax returns, withholding tax

**Sections:** 36

---

## Quick Reference

- [Add and Setup an Other Tax Regime](#add-and-setup-an-other-tax-regime)
- [Find GST Return](#find-gst-return)
- [GST - Add Layout](#gst---add-layout)
- [GST - Maintain](#gst---maintain)
- [GST - Reports](#gst---reports)
- [GST - Setup](#gst---setup)
- [GST - Tasks](#gst---tasks)
- [GST Basis Setting (NZ)](#gst-basis-setting-nz)
- [GST Complete Return](#gst-complete-return)
- [GST Complete Return - Completing Returns](#gst-complete-return---completing-returns)
- [GST Complete Return - End of Period Not Complete](#gst-complete-return---end-of-period-not-complete)
- [GST Complete Return - GST Not Allocated](#gst-complete-return---gst-not-allocated)
- [GST Complete Return - Links tab](#gst-complete-return---links-tab)
- [GST Complete Return - Memos tab](#gst-complete-return---memos-tab)
- [GST Complete Return - Provisional tab](#gst-complete-return---provisional-tab)
- [GST Complete Return (NZ)](#gst-complete-return-nz)
- [GST Enter Memos](#gst-enter-memos)
- [GST Enter Transactions](#gst-enter-transactions)
- [GST Enter Transactions - Links tab](#gst-enter-transactions---links-tab)
- [GST Enter Transactions - Memos tab](#gst-enter-transactions---memos-tab)
- [GST Functions](#gst-functions)
- [GST Line Calculations](#gst-line-calculations)
- [GST Link List](#gst-link-list)
- [GST Memo Designer](#gst-memo-designer)
- [GST Memo List](#gst-memo-list)
- [GST Return Form - Source tab](#gst-return-form---source-tab)
- [GST Return List](#gst-return-list)
- [GST Transaction List](#gst-transaction-list)
- [GST Transfer to General Ledger](#gst-transfer-to-general-ledger)
- [GSTReturnForm and GSTReturnData](#gstreturnform-and-gstreturndata)
- [SQL GST Functions](#sql-gst-functions)
- [Tax Rates](#tax-rates)
- [Tax Regime Settings - Codes tab](#tax-regime-settings---codes-tab)
- [Tax Regime Settings - General tab](#tax-regime-settings---general-tab)
- [Tax Regime Settings - Integration tab](#tax-regime-settings---integration-tab)
- [Tax Regime Settings - Provisional tab](#tax-regime-settings---provisional-tab)

---

## Add and Setup an Other Tax Regime

Source: https://accredo.co.nz/webhelp/AddiAnOtherGSTRegime.htm

Add and Setup an Other Tax Regime
This example shows how to add and setup the AU regime to a company with NZ Base Regime.
When adding regimes, If the regime you require is not available, please contact Accredo.
We recommend taking a backup prior to setup.
Add AUD Currency
Navigator > Setup > Foreign Exchange > Currencies
All transactions for a Regime must be in the currency of the Regime. If the AUD currency has not already been added to the System you will need to add it and ensure it is available for Sales, Purchases, or Bank Accounts, depending on the AU Regime transactions you need to process.
Add Regime
Navigator > Setup > Goods and Services Tax > Tax Regimes
Click Insert, then select the
AU
tax regime. This adds the Regime and the default Tax Codes and saves it.
Note that regimes cannot be deleted once added, but they may be inactivated.
Edit the Regime and set the:
Tax Basis.
Tax Number to be printed on documents and submitted with returns.
Tax Return Months.
Next Tax Date.
Integration tab accounts – the assumption is you will want to track the other regime Tax separately, so you will need to add GL accounts.
Tax Codes
The
E
Exempt code is available for and shared by all regimes. Default codes for the Regime are automatically created when a regime is added. Codes created for Other Regimes have the Regime Code appended to the Code.
Base GST Code
For GST Codes in Other Regimes, the
Base GST Code
is the code that sales and purchases should report under in the Base Regime. This defaults to the Export Code in the Base Regime, which is
0
for NZ Base Regimes, or
X
for Other Base Regimes.
Map From GST Code
Other Regime GST Codes can be mapped from a Base Regime GST Code. For the
Default GST Code
in the Regime, this defaults to the Base Regime
Default GST Code
.
When a Document or Transaction is processed for the Other Regime and a product code or analysis code is selected, the GST Code for the regime is selected via the mapping unless an explicit override has been added to the product or analysis code.
Add or Edit Customer and Creditor Groups
Navigator > Maintain > Accounts Receivable > Customer Groups
Navigator > Maintain > Accounts Payable > Creditor Groups
Customer and Creditor Groups have a Regime Code, which in turn determines the GST Override Codes available. You can set the Regime Code for Groups in the currency of the Regime you have added, and this will be used for new Customers and Creditors added for the group. GST Override should be blank for Other Regimes.
Customer and Creditor Regime Codes
Navigator > Maintain > Accounts Receivable > Customers > Customer tab
Navigator > Maintain > Accounts Payable > Creditors > Creditor tab
The Regime for a Customer or Creditor may be changed provided all transactions are fully allocated and there are no unposted documents. Transactions cannot be unallocated if the current regime for the customer or creditor differs from the regime of the allocated transactions.
Changing the Regime will clear the GST Override Code if it was set.
GST Code mapping and overrides
GST Codes for other regimes are selected in the same way as for the base regime with an additional mapping via an override layer at the product or analysis code level. The Default GST Code for the regime will be overridden by Customer or Creditor GST Override if it is set.
Product GST Codes on Document lines
When a Product Code is selected, if an explicit Override for the Regime has been set for the Product and Regime, then that GST code will be used, otherwise the mapped GST code is used. Mapping works based on the Product GST Code for the base regime.
Note that GST Codes default from the Product on Purchase Orders and Shipments as well as on Sales Orders and Invoices.
Analysis GST Codes on Document lines and Transaction Dissections
If there is no Product Code and an Expense Code or Sales Group is selected, then if an explicit Override for the Regime has been set for the Analysis Code and Regime, that GST code will be used. Otherwise the mapped GST code is used. Mapping works based on the Analysis GST Code for the base regime.
Add any Product GST overrides needed for the AU Regime
Navigator > Maintain > Inventory Control > Products > Product tab > Tax group box
For example, a product which is Taxable for GST in NZ but is GST-free in AU would need an Override of FAU.
Add any Analysis GST overrides needed for the AU Regime
Navigator > Maintain > Accounts Receivable > Sales Groups > Account tab > Tax group box
Navigator > Maintain > Accounts Payable > Expense Codes > Account tab > Tax group box
Navigator > Maintain > Cash Book > Analysis Codes > Account tab > Tax group box
For example, an analysis code which is Taxable for GST in NZ but is Exempt GST in AU would need an Override of E.
Document designs for other regimes
The example documents installed with the Accredo 5 server install handle Other Regimes, using the TaxNoName and TaxNo of the regime. If you have customised documents from prior versions they will require updating.
Cash Book Transactions
Summaries, Banking Items and Transactions from AR and AP are all base Regime and Exempt GST.
CB Sourced Transactions and Bankings of CB sourced Banking Items may be entered for the Base Regime or for the Regime for the currency of the bank account.
GST Transactions
Select the regime the adjustment relates to.
GST Reporting
All GST reports have a Regime Code selection. Add layouts and set default selections as required.
Module GST Report layouts
Navigator > Reports > Accounts Receivable > GST Reports > Add layout
Navigator > Reports > Accounts Payable > GST Reports > Add layout
Navigator > Reports > Cash Book > GST Reports > Add layout
These reports are per module and are financial period based.
GST Report layouts
Navigator > Reports > Goods and Services Tax > Add Layout
These are across all modules and are GST Return based.
Generic Return Form
Navigator > Tasks > Goods and Services Tax > Generic Return Form
The Generic Return Form is used for Other Regimes (and for Base Regimes other than NZ and AU).
Complete the Return to prevent further GST affecting transactions or allocations being processed.
Reporting of Other Regime Transactions for your Base Regime
Other Regime transactions are reported for your base regime under the Base GST Code specified in the GST Codes for your Other Regime. For NZ Base Regime this will usually be code
0
- Zero-rated, and for AU Base Regime this will usually be code
X
- Export Sales.

---

## Find GST Return

Source: https://accredo.co.nz/webhelp/GSTReturnList_Find.htm

Find GST Return
Navigator > Maintain > Goods and Services Tax > GST Return List >
Find
(Ctrl+F)
Enter the Return ID to find a specific return.
OK
(
F9
)
Find the return and highlight it in the
GST Return List
.
Cancel
(
Esc
)
Cancel and close the window.
See Also
GST Return List

---

## GST - Add Layout

Source: https://accredo.co.nz/webhelp/GSTTransactionReports.htm

GST - Add Layout
Navigator > Reports > Goods and Services Tax > Add Layout
You can add and customise layouts. For example, you can customise to filter the transaction source module. Once a layout is added, it becomes a Report and will be available from the appropriate Reports folder.
Period selection selects the current GST Period range for GST reports.
See also
Report Selections Form
,
AP GST Reports
,
AR GST Reports
, and
CB GST Reports
.
Layouts
GST Basis Reconciliation
Reports the difference between Accruals and Cash basis as at the selected Return. This shows unpaid GST transactions from both AR and AP that are not yet reported on the Payments / Cash Basis for GST at the selected period. This Report is useful for reconciling the GST (Accrued) in the GL with the Payments / Cash basis reports. This report is also useful when switching GST basis as it reports the difference between Invoice / Non Cash (Accruals) and Payments / Cash basis GST at the selected period, so you can adjust the return. The report is grouped by Sales (AR) and Purchases (AP).
GST Code Detailed
Shows a detailed breakdown of transactions grouped by the GST code for the analysis lines. This report includes AR or AP and CB sourced information to give full GST detail. Summary details are shown in the base currency. You can customise the report to show foreign summary details.
GST Detailed
Shows a detailed breakdown of transactions sorted by the source type for the analysis lines. This report includes AR or AP and CB sourced information to give full GST detail. The GST Basis defaults to the basis for the Return. You can customise the report, so example to filter the source module.
GST Discounts
Reports Settlement Discount for AR and AP transactions for the return. This shows Invoice and Credit transactions from AR and AP that have been paid or partly paid (that is, allocated to a Payment/Receipt or Journal) that have a Discount. The GST details are based on the proportion of the Invoice (Credit) paid in each payment allocated against the Invoice. The report is grouped by Sales (AR) and Purchases (AP). This shows the detail behind the Discount Adjustments that are generated.
GST Transaction Period
Print a list of
GST Adjustment transactions
for a GST Return. Select the Period, current year, all periods or a range of periods. The report lists GST Adjustment transactions within the periods they were entered. This report can be selected for a period as a monthly transaction summary report for audit.
GST Transaction Sequence
Print a list of
GST Adjustment transactions
. Select the Return Date. The report lists transactions included in the Return.
GST Unreported Transactions
Shows all Payments and Receipts entered in the selected period or earlier which are not fully allocated as at the end of the selected period. If you are on Payments / Cash basis GST, these amounts will not be reflected in the GST Payments Report or the GST Return. The report is grouped by Sales (AR) and Purchases (AP).

---

## GST - Maintain

Source: https://accredo.co.nz/webhelp/GST_Maintain.htm

GST - Maintain
Navigator > Maintain > Goods and Services Tax
In This Section
GST Transaction List
GST Return List
GST Memo List
GST Link List

---

## GST - Reports

Source: https://accredo.co.nz/webhelp/GST_Reports.htm

GST - Reports
Navigator > Reports > Goods and Services Tax
In This Section
GST - Add Layout

---

## GST - Setup

Source: https://accredo.co.nz/webhelp/GST_Setup.htm

GST - Setup
Navigator > Setup > Goods and Services Tax
In This Section
Tax Regime Settings - General tab
Tax Rates
Change Tax Basis
GST Memo Designer
Add and Setup an Other Tax Regime

---

## GST - Tasks

Source: https://accredo.co.nz/webhelp/GST_Tasks.htm

GST - Tasks
Navigator > Tasks > Goods and Services Tax
In This Section
GST Enter Transactions
GST Transfer to General Ledger
GST Complete Return
BAS Return - Return tab
Generic Return

---

## GST Basis Setting (NZ)

Source: https://accredo.co.nz/webhelp/GSTBasisSettingNZ.htm

GST Basis Setting (NZ)
Navigator > Setup > Goods and Services Tax > Tax Regimes
You can complete a New Zealand GST Return Form using Accredo data. GST figures transfer to the GST Return Form as follows, depending on the GST Basis.
Invoice Basis GST
GST for the following modules transfers to the GST Return Form when a taxable transaction is entered:
AR
- GST on sales and income (Outputs).
AP
- GST on purchases and expenses (Inputs).
CB
- Outputs and Inputs.
Payments Basis GST
GST for the following modules transfers to the GST Return Form when receipt or payment is allocated against an invoice or credit:
AR
- GST on sales and income (Outputs).
AP
- GST on purchases and expenses (Inputs).
For CB, GST will transfer to the GST Return Form when a taxable transaction is entered.
Changing Tax Basis
Navigator > Setup > Goods and Services Tax > Change Tax Basis
You can change the tax basis. The Effective Date must be the end of an unposted tax return. The necessary adjustments will be calculated from the return prior to the change.
In This Section
GST Complete Return (NZ)
See Also
Periodic Tasks

---

## GST Complete Return

Source: https://accredo.co.nz/webhelp/GSTCompleteReturn.htm

GST Complete Return
Navigator > Tasks > Goods and Services Tax > GST Return Form > GST tab
Complete a GST Return for a base NZ Regime from data accumulated in CB, AR and AP. View the GST Return for the selected return date.
Figures are calculated on the Tax Basis (Invoice or Payments). All calculations produce a net GST Payable figure.
For Payments Basis regimes, figures are calculated based on allocation dates. For Payments basis, sales and purchases are not reported if the transaction is processed but not yet allocated. You can refer to the GST Unreported Transactions report or the GST Unallocated reports for each module.
Regime
The
Tax Regime
to submit the return for. This is the Base Regime.
Return
The end date of the tax return.
GST No
The company
GST Number
.
Basis
The
Tax Basis
for the return.
Start Date
Start date of the return.
End Date
End date for the return, this may differ from the return date if the
Regime Interval Unit
is
Periods
and the Period end does not align with the Return date.
Status
The Status of the return. This can be:
Unposted
- GST return has not been completed
Posted
-GST return has been completed
Final
Filing
The Filing Status of the return. This can be:
Unfiled
- return has not been accepted
Pending
- filed return has been reopened
Grossed Up column
This shows calculated figures for Taxable Supplies by grossing up the GST at the default GST rate for the end date of the return period. The Grossed Up figures are adjusted to handle negative taxable supplies and GST values as required by the IRD. These are the figures submitted when the return is filed. Where there are differences between Actual and Grossed Up figures, they are highlighted in
Bold
.
How to find Credit Adjustments
The figure in box 12 of the return is calculated from the total taxable purchases in box 11 (includes purchases analysed to GST code
0
- Zero-rated supplies) multiplied by 3, divided by 23. This calculated figure is compared with the actual GST analysed from the transactions. Any difference is reported as a Credit adjustment in box 13. This usually correctly represents:
Transactions analysed to GST code
G
- GST Only, for example, GST paid to Customs,
GST adjustments transactions
from Navigator > Tasks > Goods & Services Tax > Enter Transactions,
Rounding differences that will be minor.
This may also reflect analysis errors, for example, if an item has been analysed to GST code
0
- Zero-rated instead of analysed to GST code
E
- Exempt. To find what makes up these Credit adjustments, go to the Source tab and view AP, CB, and GST modules for figures in the adjustment field.
For Invoice Basis GST
- run a GST code detailed report for AP and / or CB for GST code
G
and
0
. Transactions reporting under GST code
G
are only for customs GST (or possibly for rounding where the GST code
G
was used). Transactions reporting under GST code
0
have more than likely been analysed with the wrong GST code. Items exempt of GST analyse to GST code
E
rather than
0
. Adjustment figures in the GST source module can be reported on by adding a Transaction Sequence layout under GST reports.
For Payments Basis GST
- if you have adjustments reporting under CB, run the CB GST Audit report as explained above. If you have adjustments reporting under AP, run the AP GST Payments report and Customise in Purchases All GST. Any transactions reported under Zero Rated Purchases have more than likely been analysed with the wrong GST code. Items exempt of GST analyse to GST Code
E
rather than
0
.
Note: Negative GST Adjustment figures in Box 13 (purchase and expenses) will be transferred to Box 9 (sales and income), as all adjustments submitted must be positive.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit the GST return. This is only available for
Provisional Type
of
Manual
or
Ratio
.
Print
(Ctrl+P)
Print a GST Form. This also shows adjustments and the source modules GST information was drawn from.
Refresh
(F5)
Reloads changes other Users may have made.
Insert CB Payment
Available for Completed returns with Tax to pay, when Cash Book Integration settings for the regime are completed. Inserts either a
CB Transaction
or an Electronic Payment Summary for the bank account specified, for the net GST, using values in the Tax Regime
Integration tab
. The Branch and Department of the GST Regime will be used. (Accredo Saturn Only)
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
Go to MyIR
Opens the Inland revenue MyIR website in the default browser.
Print Submission
Print an IRD Submission Report.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Buttons
Manually File
(
Alt+N
)
Set the GST Return Filing status to Manually Filed. This can be used for returns that have been filed externally from Accredo.
File
(
Alt+F
)
For Completed returns, select to File the return with the tax office. You will be prompted to print a Submission report after filing.
Note: Accredo is not creating the submission it effectively asks for the one the IRD has and fills it in. GST Return form type in Accredo must match the type of return the IRD has. If you get a "GST Return form type mismatch" error review your Provisional Type in
Tax Regimes Provisional tab
.
Filing requires the Data Interchange Module.
Filing is logged in the
Recovery Log
.
Re-Open
(
Alt+R
)
Re-open a completed GST return. This is only available for the most recent completed GST return, and when
Allow Return Reopening
has been selected in the
Tax Regime Settings
.
Adjust
(
Alt+A
)
Makes GST adjustments for Settlement discount, change of GST Rate, or change of GST Basis, which can be transferred to the GL prior to completing the GST Return. If the return is not completed at the time and further transaction requiring adjustments are processed, then
Adjust
can be selected again, or the adjustments will be automatically created when the return is completed.
Note: Tax basis change adjustment transactions are created with
Transferred to GL
set to
True
. This is because the timing of the change affects the timing of when tax is due to be filed or paid. It does not affect when it is applied to the GL, which is on an Invoice or Accruals bases.
Complete
(
Alt+P
)
Completes the GST Return.
This is only available for the latest GST Return. GST Figures as refreshed and a warning displayed if GST Payable has changed since the form was opened. Completing the GST Return locks the GST period for AR, AP and CB and prevents entering or editing transactions that have a net effect on GST for the Regime.
See
GST Return Form - Completing Returns
.
Save
(
F9
)
Save changes made. This is only available for
Provisional Type
of
Manual
or
Ratio
.
Cancel
(
Esc
)
Cancel changes without saving.
In This Section
GST Complete Return - Provisional tab
GST Return Form - Source tab
GST Complete Return - Links tab
GST Complete Return - Memos tab
GST Complete Return - End of Period Not Complete
GST Complete Return - GST Not Allocated
GST Complete Return - Completing Returns
GSTReturnForm and GSTReturnData

---

## GST Complete Return - Completing Returns

Source: https://accredo.co.nz/webhelp/GSTReturnForm_AcceptingReturns.htm

GST Complete Return - Completing Returns
Completing the return will:
Refresh the GST Return and warn if GST payable changes e.g. if GST affecting transactions for the period have been processed since the form was loaded.
Lock GST processing for the Regime to the end date of the return so that no further changes can be made. This is important to ensure the system will remain consistent with the figures you return.
Generate system created GST Adjustment transactions for settlement discount.
Generate system created GST Adjustment transactions for payments basis change of GST rate timing differences.
If adjustments are created, will prompt for transfer to GL.
See Also
GST Complete Return

---

## GST Complete Return - End of Period Not Complete

Source: https://accredo.co.nz/webhelp/GSTEOPNotComplete.htm

GST Complete Return - End of Period Not Complete
A GST Return Form cannot be completed until you have performed the:
AR End of Period Update
,
AP End of Period Update
, - AND -
CB End of Period Update
.

---

## GST Complete Return - GST Not Allocated

Source: https://accredo.co.nz/webhelp/GSTNotReported.htm

GST Complete Return - GST Not Allocated
You will be notified if you try to accept a GST return when you have any of the following:
Unposted IN Invoices / Credits,
Unposted AP Shipments,
Unallocated AR Receipts - OR -
Unallocated AP Payments.
For Payments (NZ) or Cash (AUS) Basis GST, GST on receipts and payments is reported in the period they are allocated. Unallocated receipts and payments will not be included in a GST (NZ) or BAS (AUS) Return. Unallocated receipts and payments are shown on the
GST Return Form - Source tab
. Select the relevant Source Module.

---

## GST Complete Return - Links tab

Source: https://accredo.co.nz/webhelp/GSTCompleteReturn_Links.htm

GST Complete Return - Links tab
Navigator > Tasks > Goods and Services Tax > GST Return Form >
Links tab
See Also
GST Complete Return

---

## GST Complete Return - Memos tab

Source: https://accredo.co.nz/webhelp/GSTCompleteReturn_Memos.htm

GST Complete Return - Memos tab
Navigator > Tasks > Goods and Services Tax > GST Return Form >
Memos tab
See Also
GST Complete Return

---

## GST Complete Return - Provisional tab

Source: https://accredo.co.nz/webhelp/GSTCompleteReturn_Provisional.htm

GST Complete Return - Provisional tab
Navigator > Tasks > Goods and Services Tax > Complete Return > Provisional tab
The Provisional Tab is only shown for NZ Base Regime companies, with a
Provisional Type
of Manual or Ratio.

---

## GST Complete Return (NZ)

Source: https://accredo.co.nz/webhelp/GSTCompleteReturn_NZ.htm

GST Complete Return (NZ)
Navigator > Tasks > Goods and Services Tax > GST Return Form
To prepare and print a GST Return Form for a New Zealand Company:
Select the date in the
Return
field. The dates are used on the printed form.
You can view and print GST Returns with past and future dates, but you can only
Complete
the return for the current return date.
View the figures on the
GST
tab. If you do not have
AR
,
AP
or
CB
installed, some or all fields may be blank.
For NZ Regimes with a Provisional Type of Manual or Ratio, the
Provisional
tab is shown. For Ratio basis, the provisional tax is calculated. For Manual basis, you can enter the instalment value, and any voluntary payments.
On the
Source
tab you can view the source figures by module. Incorrect figures will be due to incorrect data entry. Refer to the following reports to help locate and correct errors:
For Invoice Basis GST, refer to the
GST Code Detailed Report
in the relevant module for a view by GST code, or the
GST Audit Report
for a list of invoices containing GST.
For Payments Basis GST, refer to the
GST Code Detailed Report
in the relevant module for a view by GST code, or the
GST Payments Report
in the relevant module for a view of payments allocated against invoices during the GST period.
Note: The GST Return form cannot be edited. Adjustments must be entered as transactions from Navigator > Tasks > Goods and Services Tax > Enter Transactions.
You can click
Adjust
(
Alt+A
) to generate GST adjustments for Settlement discount, change of GST Rate or change of GST Basis before completing the return. You can select to transfer these to the GL. Adjustments are automatically created when the return is completed.
Click
Complete
(Alt+C)
.
Once a GST Return is completed, the
Status
for the GST Return changes from
Unposted
to
Posted.
Data will be locked for the relevant transactions in
AR
,
AP
and
CB.
We recommend you click
Print
(Ctrl+P)
to print a copy of the form. The printed GST Return form includes actual and grossed figures. Grossed figures that differ from the actual are shown in bold. Figures are grossed up on the GST Return form to ensure adjustments are positive amounts.
You can click
File
(
Alt+F
) to file the return electronically using the IRD's electronic gateway. You will be prompted for your IR-file login, and there must be a matching Return available to file.
You can click
Insert CB Payment
to create a CB Transaction or Electronic payments batch for your tax due. Set up details in the Tax Regime Integration tab.
See Also
GST Basis Setting (NZ)

---

## GST Enter Memos

Source: https://accredo.co.nz/webhelp/GSTEnterMemos.htm

GST Enter Memos
Navigator > Tasks > Goods and Service Tax >
Enter Memos
Defaults for inserting Memos, Alarms and Reminders are set in
Company Settings - Memos tab
.

---

## GST Enter Transactions

Source: https://accredo.co.nz/webhelp/GSTTransactions.htm

GST Enter Transactions
Navigator > Tasks > Goods and Services Tax > Enter Transactions
You can enter GST adjustment transactions. These are transactions that affect GST and transfer to the General Ledger but have no financial effect on sub ledgers.
For the "GST - New Zealand" tax regime the following GST Transaction types are available:
Sales Adjustment
-
increases the GST liability (for example, private use of business assets) and reports the GST Adjustment in Box 9, and the GST Amount in Box 10 on the return form.
Sales GST
- directly adjusts the Total GST Collected figure in Box 10 on the return form. Does not appear as an adjustment.
Sales Total + GST
- adjusts the Total GST Collected figure in Box 10 on the return form and is grossed up at the default GST rate into the Total taxable sales and income in Box 5 on the return form. Does not appear as an adjustment. These may be generated by the system if required for Settlement Discount adjustments.
Purchases Adjustment
-
decreases the GST liability and reports as a Credit GST Adjustment in Box 13, and the GST Amount in Box 14 on the return form.
Purchases GST
- directly adjusts the Total GST Credit figure in Box 14 on the return form. Does not appear as an adjustment.
Purchases Total + GST
- adjusts the Total GST Credit figure in Box 14 on the return form and is grossed up at the default GST rate into the Total taxable purchases and expenses in Box 11 on the return form. Does not appear as an adjustment. These may be generated by the system if required for Settlement Discount adjustments.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Click to edit the saved transaction.
Insert
(F4)
Insert a new GST Transaction.
Duplicate
(Shift+F4)
Duplicates the open transaction. When you select,
Duplicate,
the new transaction defaults to the System Date and System Period.
Duplicate Contra
, the original date and period are retained if available for processing, or the System Date and System Period are used.
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
Fields
Period
Select the period to post to. Defaults to the current System Period.
Transaction Type
The Transaction Type being entered (read-only).
ID
The Transaction ID (read-only).
Regime Code
The Tax Regime Code for the transaction. The Regime Name and Currency Code are displayed.
Date
The date of the transaction. Defaults to the date of the previous transaction, or the System Date.
Reference
A reference for the transaction.
Comment
This will be recorded against the transaction, usually to document the reason for the adjustment.
Narration
Additional information to be included in the GL journal when transferred to GL.
Rate Type
Exchange Rate
For Other Tax Regimes than the Base Regime, select the FX Rate Type.
If
Use Exchange Rate Table
is selected in
FX Settings
, the Rate is fetched from the
Exchange Rate Table
based on Currency Code, Rate Type and Date.
Click
Fix Exchange Rate
beside the Exchange Rate field to lock the Exchange Rate. When the rate is fixed, the rate cannot be changed on this transaction, and this transaction will be excluded from Revaluations. If not fixed, the rate will be re-fetched from the rate table when Rate type, Currency code or Invoice date are changed.
Branch
Department
The Branch and Department for the transaction. (Accredo Saturn Only)
GST Amount
The amount of GST. For NZ and Australian Regimes, the box on the
GST Return
that will be affected is shown.
GST Amount Bs
The amount of GST in the Base Currency.
Total Amount
The effect on taxable supplies or purchases. For NZ and Australian Regimes, the box on the
GST Return
that will be affected is shown. (Read-only)
Adjustment Amount
The amount of the GST adjustment. For NZ and Australian Regimes, the box on the
GST Return
that will be affected is shown. (Read-only)
GL Account Number
Account Name
The account in the GL for the other part of the transaction, and the Account Name. Sales adjustments will debit this account. and Purchase adjustments will credit it. GL accounts used for adjustments are setup in
GST Settings
.
In This Section
GST Enter Transactions - Links tab
GST Enter Transactions - Memos tab

---

## GST Enter Transactions - Links tab

Source: https://accredo.co.nz/webhelp/GSTEnterTransactions_Links.htm

GST Enter Transactions - Links tab
Navigator > Tasks > Goods and Services Tax > Enter Transactions >
Links tab
See Also
GST Enter Transactions

---

## GST Enter Transactions - Memos tab

Source: https://accredo.co.nz/webhelp/GSTEnterTransactions_Memos.htm

GST Enter Transactions - Memos tab
Navigator > Tasks > Goods and Services Tax > Enter Transactions >
Memos tab
See Also
GST Enter Transactions

---

## GST Functions

Source: https://accredo.co.nz/webhelp/GSTFunctions.htm

GST Functions
Function
Description
AddGST
Adds GST to an amount.
BusinessNo
Returns the Business Number format for a Tax Regime.
BusinessNoName
Returns the name of the Business Number for a Tax Regime.
DefaultGSTcode
Returns the default GST code.
GSTBasis
Returns the company GST basis.
GSTRate
Returns the GST Rate for Code.
GSTRegistered
Returns True if GST Settings GST Basis is Invoice or Payments, or False.
LastTaxDate
Returns the last tax date for a tax regime.
NextTaxDate
Returns the net tax date for a tax regime.
ReturnForDate
Returns the Tax Return ID for a given date in a tax regime.
SubtractGST
Subtracts GST from an amount.
TaxName
Returns the Tax Name for a Tax Regime.
TaxNo
Returns the format of the Tax Number for a Tax Regime.
TaxNoName
Returns the name of the Tax Number for a Tax Regime.
In This Section
AddGST - MaxBasic Function
BusinessNo - MaxBasic Function
BusinessNoName - MaxBasic Function
DefaultGSTCode - MaxBasic Function
GSTBasis - MaxBasic Function
GSTRate - MaxBasic Function
GSTRegistered - MaxBasic Function
LastTaxDate - MaxBasic Function
NextTaxDate - MaxBasic Function
ReturnForDate - MaxBasic Function
SubtractGST - MaxBasic Function
TaxName - MaxBasic Function
TaxNo - MaxBasic Function
TaxNoName - MaxBasic Function
See Also
MaxBasic Functions

---

## GST Line Calculations

Source: https://accredo.co.nz/webhelp/GSTLineCalculations.htm

GST Line Calculations
Within Accredo, GST amounts are calculated and rounded for the total document, going through each line.
The following example shows how GST is calculated and rounded for 4 product lines:
Line No
Price
GST Calculated
Amount Carried Over
Total
Rounded
GST Displayed
1
$0.03
$0.0045
2
$0.03
$0.0045
$0.0045
$0.009
$0.01
$0.01
3
$0.03
$0.0045
$0.001
$0.0055
4
$0.03
$0.0045
$0.0055
$0.01
$0.01
This ensures that GST is correctly calculated for the net amount of the entire document.

---

## GST Link List

Source: https://accredo.co.nz/webhelp/GSTLinkList.htm

GST Link List
Navigator > Maintain > Goods and Services Tax >
Link List
See Also
GST - Maintain

---

## GST Memo Designer

Source: https://accredo.co.nz/webhelp/GSTMemoDesigner.htm

GST Memo Designer
Navigator > Setup > Goods and Services Tax >
Memo Designer

---

## GST Memo List

Source: https://accredo.co.nz/webhelp/GSTMemoList.htm

GST Memo List
Navigator > Maintain > Goods and Services Tax >
Memo List
See Also
GST - Maintain

---

## GST Return Form - Source tab

Source: https://accredo.co.nz/webhelp/GSTReturnForm_Source.htm

GST Return Form - Source tab
Navigator > Tasks > Goods and Services Tax > GST Return Form > Source tab
The
Source
tab is a break down by Module of figures on the
Form
tab. This shows where figures on the
Form
tab have come from. Select the source module to view.
Totals by source module from the GST Detailed report on the matching GST Basis will match this.
This tab is useful if you suspect the figures shown on the
Form
tab are incorrect or incomplete. To locate a problem, refer to this tab to determine the source module at fault. You may find data has been incorrectly entered.
Sales Discount / Purchases Discount
If AR or AP Discount Adjustments is selected in
Tax Regime Integration
tab then Taxable Supplies for allocated Payment Discount is shown.
Sales GST Discount / Purchases GST Discount
If AR or AP Discount Adjustments is selected in
Tax Regime Integration
tab then GST Content for allocated Payment Discount is shown.
Sales Not Reported / Purchases Not Reported (Payments Basis Only)
These show the total value of receipts and payments processed in a period up to the final period for the return that have not yet been allocated. These receipts or payments will be reported when they are allocated.

---

## GST Return List

Source: https://accredo.co.nz/webhelp/GSTReturnList.htm

GST Return List
Navigator > Maintain > Goods and Services Tax > GST Return List
Access GST returns.
Selections
Regime
The
Tax Regime
of the returns.
Date Ending - From
Enter the earliest Return End Date to show returns for.
Date Ending - To
Enter the latest Return End Date to show returns for.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Open
(F12)
Opens the return in the tax Return Form.
Print
(Ctrl+P)
Print the GST Return List, save as an Excel worksheet, or PDF file and send as an email attachment.
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
Opens
Find GST Return
. Enter a Return ID to find that return.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Totals
Record Count
The total number of records shown in the Tables list. Click
to refresh the total number.
In This Section
Find GST Return
See Also
GST - Maintain

---

## GST Transaction List

Source: https://accredo.co.nz/webhelp/GSTTransactionList.htm

GST Transaction List
Navigator > Maintain > Goods and Services Tax > Transaction List
Access GST adjustment transactions.
Regime
The
Tax Regime
for the transaction.
Selection
Select the period range to show GST Transactions in, from:
Period,
A selected Period. Select the period in the
From
lookup.
All Periods
, All GST transactions are displayed.
Range of Periods
, Select a range of periods to display in the
From
and
To
lookups.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new GST adjustment transaction.
Open
(F12)
Opens
GST Transactions
. You can view details and edit the transaction if the GST period for the transaction is open and the transaction has not been transferred to GL.
Print
(Ctrl+P)
Print the GST Transaction List, save as an Excel worksheet, or PDF file and send as an email attachment.
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

## GST Transfer to General Ledger

Source: https://accredo.co.nz/webhelp/GSTTransferToGeneralLedger.htm

GST Transfer to General Ledger
Navigator > Tasks > GST > Transfer to General Ledger
You can create a Transaction Batch that keeps the GL up to date. You are asked for the latest period to transfer up to. Batches are created for the specified period and all prior periods where there has been transaction activity that affects the GL. You can only select periods up to the latest period available for processing. Batches created will have separate entries for each GST adjustment transaction entered in GST Enter Transactions, that is, for each transaction it Debits or Credits the relevant control accounts and specified adjustment accounts. The dates for the lines in the batch are the transaction dates. You can select this many times during a period. It will transfer up to at least the period specified the previous time.

---

## GSTReturnForm and GSTReturnData

Source: https://accredo.co.nz/webhelp/GSTReturnForm_PropertyMappings.htm

GSTReturnForm and GSTReturnData
The GSTReturnData is the data object underlying the GSTReturnForm(s).
The PropertyNames as they map to the NZ GST Return Form are documented below.
Actual
Grossed Up
Box 5
SalesTaxable
SalesTaxableGross
Box 6
SalesZeroRated
SalesZeroRated
Box 7
SalesNetTaxable
SalesNetTaxableGross
Box 8
SalesGstDivided
SalesGstIncludedGross
SalesGstAdjustments
SalesAdjustmentsDiff
Box 9
SalesAdjustments
SalesAdjustmentsGross
Box 10
SalesGstTotal
SalesGstTotal
Box 11
PurchasesTaxable
PurchasesTaxableGross
Box 12
PurchasesGstDivided
PurchasesGstIncludedGross
PurchasesGstAdjustments
PurchasesAdjustmentsDiff
Box 13
PurchasesAdjustments
PurchasesAdjustmentsGross
Box 14
PurchasesGstTotal
PurchasesGstTotal
Box 15
GstPayable
GstPayable

---

## SQL GST Functions

Source: https://accredo.co.nz/webhelp/SQLGSTFunctions.htm

SQL GST Functions
Function
Description
AddGST
Adds GST to an amount.
DefaultGSTCode
Return the default GST Code.
GSTBasis
Return the company GST basis.
GSTRate
Return the GST Rate for a Code.
GSTRegistered
Returns True if GST Settings GST Basis is Invoice or Payments, or False.
SubtractGST
Subtract GST from an amount.
In This Section
AddGST - SQL Function
DefaultGSTCode - SQL Function
GSTBasis - SQL Function
GSTRate - SQL Function
GSTRegistered - SQL Function
SubtractGST - SQL Function

---

## Tax Rates

Source: https://accredo.co.nz/webhelp/GSTRates.htm

Tax Rates
Navigator > Setup > Goods and Services Tax > Rates
GST Rates are used to calculate GST on orders, invoices and transaction analysis lines.
Select Code
Select
GST Code
from the
Lookup
.
Note: Rates can only be entered for Codes starting with a digit between
1
and
9
.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit the list of GST Rates and effective dates for the selected
GST Code
.
Insert
(F4)
Insert a new GST Rate and effective date.
Delete
(F3)
Delete GST Rate and effective date.
Print
(Ctrl+P)
Print a report of the list, or save it as a PDF file to send as an email attachment.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Buttons
Save
(F9)
Save changes.
Cancel
(Esc)
Discard changes and close the form.

---

## Tax Regime Settings - Codes tab

Source: https://accredo.co.nz/webhelp/TaxRegimeSettings_Codes.htm

Tax Regime Settings - Codes tab
Navigator > Setup > Goods and Services Tax > Tax Regimes > Codes tab
Tax codes are used to calculate Tax on orders, invoices and transaction analysis lines. Tax codes are selected when setting up
AR Sales Groups
,
AP Expense codes
and
CB Analysis codes
, and also apply when calculating Tax inclusive prices for Price Codes in IC.
Default codes are automatically created when a regime is added.
The New Zealand Base Regime has the following codes:
Code
Code Name
Description
0
Zero Rated
The GST Code used for exports.
1
GST
For goods and services that attract GST at the current GST rate.
G
GST Only
For goods and services that are All GST, for example, GST paid to customs.
E
Exempt GST
For services that don’t attract GST, such as wages. Includes payments of GST to the IRD. These are not shown on the GST Return.
The Australian Base Regime has the following codes:
Code
Code Name
Description
1
GST
For goods and services that attract GST at the current GST rate.
C
Customs GST
GST paid to Customs.
F
GST Free
GST free goods and services.
G
GST Only
GST adjustment code used to correct or amend previous transactions.
I
Input Taxed
Input taxed supplies and expenses.
X
Import / Export
The GST Code used for exports.
The X GST Code is used for exports in all Other Regimes.
E
Exempt GST
For services that don’t attract GST, such as wages. Includes payments of GST to the ATO. These are not shown on the BAS Return.
Codes must be unique within a company. If the Base Regime is NZ, then set NZ codes as above. If you have another regime, append the Regime Code to each code, except for
E
. For example, for an Australian other regime would have codes
1AU
,
CAU
,
FAU
, and so on, to distinguish them from the NZ codes. The Exempt Code
E
is available to all regimes. This does not need the regime code appended.
Every Regimes require an Export GST Code. For NZ Regimes this is
0
, as this is zero rated. For Australian and other Regimes this is
X
.
Grid Fields
GST Code
The Tax Code. This must be unique across all Tax Regimes, so we recommend appending the Regime Code to non-Base Regime GST codes. For example, for an Australian other Regime, the default rate would be
1AU
.
Note:
Rates
can only be added for Codes starting with a digit from
1
to
9
.
Description
Description of the tax code.
GST Filter
Determines the Account Class the Tax Code will be available on:
Purchases/Expense
- the GST code will be available on Expense or Asset Class Analysis codes.
All/General
- the GST code will be available on Asset, Expense, Income or Liability Class Analysis codes.
Sales/Income
- the GST code will available on Income or Liability Class Analysis codes.
Not Available
- GST codes cannot be deleted. You can set a GST Code to Not Available so it cannot be used.
Base GST Code
For GST Codes in other regimes, the GST Code to report under in the Base Regime. This is required for all Other Regime codes.
For the Exempt Code
E
, this will always map to
E
. Cannot be edited for the Base Tax Regime.
Other Regime Purchases are treated as Exempt in the Base Regime, so will map to
E
.
Map From GST Code
Other Regime GST Codes can be mapped from a GST Code in the base currency. When a Document or Transaction is processed for the Other Regime and a product code or analysis code is selected, the GST Code for the regime is selected via the mapping, unless an explicit override has been added.
For the Default Tax Code in the Regime, this defaults to the Base Regime Default Tax Code.
For the Exempt Code
E
, this will always map to
E
. Cannot be edited for the Base Tax Regime.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new GST Code. Codes must be unique, and must start with a digit between
1
and
9
. We recommend following the pattern of appending the Regime Code for non-base regimes.
Delete
(F3)
Delete the GST Code.
Print
(Ctrl+P)
Print a report of the list, or save it as a PDF file to send as an email attachment.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Maintain Rates
Opens
Tax Rates
. You cannot add rates for GST Codes starting with
0
or a letter.
Set As Default
Select the
Tax Code
(shown in bold) to be used on new Analysis groups, Invoice lines and products added to IC.
Tax Code
1
(default percentage) is used when calculating tax using the Accredo calculator.
The default code is shown on the
General tab
.

---

## Tax Regime Settings - General tab

Source: https://accredo.co.nz/webhelp/TaxRegimeSettings_General.htm

Tax Regime Settings - General tab
Navigator > Setup > Goods and Services Tax > Tax Regimes
Specify Tax Regimes available for the company.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit the tax regime fields.
Insert
(F4)
Insert a new Tax Regime. The drop-down list shows the tax regimes supported by Accredo. You must have the corresponding
currency
installed to add a regime. Once a Regime is added, it cannot be deleted, but it can be set to
Inactive
.
Currently supported Tax Regimes are:
Regime Code
Regime Name
Currency Code
AE
United Arab Emirates
AED
AU
Australia
AUD
CK
Cook Islands
NZD
FJ
Fiji
FJD
FR
France
EUR
GL
Great Britain
GBP
IE
Ireland
EUR
MX
Mexico
MXN
NZ
New Zealand
NZD
PG
Papua New Guinea
PGK
SG
Singapore
SGD
TO
Tonga
TOP
Fields
Tax Regime
Select the Tax Regime Code.
Regime Code
The Tax Regime Code. This is often the same as the country code. If the selected Regime is the
Base Regime
for the Company, this will be shown.
Regime Name
The Tax Regime name. This is often the same as the Country name.
Currency Code
Currency code of the Regime. Read Only.
Rounded
Selected
, GST returns will be rounded to whole currency units.
Tax Name
The name of the tax in the Regime. In New Zealand and Australia, this will be
GST
.
Tax Basis
Select from:
Invoice (Accruals)
Payments (Cash)
Not Registered
The Tax Basis affects the data presented in the Tax Return.
This cannot be changed here after transactions have been entered. See
Change Tax Basis
to change a Tax Basis after transactions exist.
Tax No
The Company's Tax number for the Regime. This is used on Documents and Tax Returns. In New Zealand, this will be the company GST No, and in Australia this will be the company ABN. This is required unless the
Tax Basis
is
Not Registered
.
Tax No Name
The name of Tax Numbers in the Regime. In New Zealand this is
GST No
, and in Australia this is
ABN.
Business No
The Company's Business Number for the Regime.
Business No Name
The name of Business Numbers in the Country. In New Zealand this is
NZBN
.
Default GST Code
The default GST Code. This can also be set on the
Codes tab
. This is set when the regime is added, and should not need to be changed.
Tax Return Count
The number of months or periods reported per Tax Return. This is used to create the Tax Return records for the regime.
Tax Return  Interval Unit
Unit for Tax Return Count.
Months
,
(default) Start and End dates for
GST Returns
will align with calendar months.
Periods
,
Start and End dates for
GST Returns
will align with financial periods. Select where
Periods
do not align with calendar months, and there is an arrangement with the tax office to report based on financial periods.
Note: Changing GST Regime Interval Unit from Month to Period or vice versa recalculates return dates for current and future GST Returns.
Last Tax Date
The date tax was last accepted.
Next Tax Date
The date of the next tax return.
Website
The website for the tax office. Click
Visit Web Site
(
Ctrl+W
) to open.
Last Filed Date
The date a tax return was last filed.
Last Transaction Date
The most recent date the Tax Basis or Tax Rate changed. Transactions occurring before this date are locked for allocation or unallocation.
Allow Return Reopening
Selected
, the most recent closed Tax Return can be re-opened.
Inactive
Selected
, the Tax Regime is inactive and cannot be selected. The Base Regime cannot be set to Inactive.
Buttons
Save
(F9)
Save changes.
Cancel
(Esc)
Discard changes and close the form.
In This Section
Tax Regime Settings - Integration tab
Tax Regime Settings - Codes tab
Tax Regime Settings - Provisional tab

---

## Tax Regime Settings - Integration tab

Source: https://accredo.co.nz/webhelp/TaxRegimeSettings_Integration.htm

Tax Regime Settings - Integration tab
Navigator > Setup > Goods and Services Tax > Tax Regimes > Integration tab
GL Tax Sales Income Account
Tax on transactions coded to Income, Liability or Capital Analysis  will be analysed to this account. This means:
The Tax component of most Invoices from AR will be Credited to this account.
The Tax component of most Credits from AR will be debited to this account.
The Tax component of appropriate transactions in the CB will affect this account.
Invoices and credits entered in AP will also affect this account if they are analysed to income, liability or capital Analysis codes.
GL Tax Sales Adjustment Account
Output adjustment
GST transactions
will credit this account. The account to be debited is specified when entering the adjustment.
GL Tax Purchases Expense Account
Tax on transactions coded to Expense or Asset Analysis codes will be analysed to this account. Typically this means:
The Tax component of most Invoices from AP will be debited to this account.
The Tax component of most Credits from AP will be Credited to this account.
The Tax component of appropriate transactions in the CB will affect this account.
Invoices and credits entered in AR will also affect this account if they are analysed to expense or asset Analysis codes.
GL Tax Purchases Adjustment Account
Input adjustment
GST transactions
will debit this account. The account to be credited is specified when entering the adjustment.
GL Reconciliation  Account
The GL Account to compare with the GST Payable/Refunded figure for completed GST Returns on the GL Ledger Reconciliation report. The Account may be either a Standard account or a Total Account and is optional.
GL Cash Basis Clearing Account
Cash Basis Clearing account is used when the GST Rate is changed and the
Tax Basis
is
Payments
for GST Transition Adjustments generated from the Return Form.
GL Rounding Adjustment Account
Rounding Adjustment Account is used when GST figures must be rounded to whole dollars for the BAS return form, and when rounding adjustments are generated from the Return Form.
GL Tax Adjustment Branch
GL Tax Adjustment Department
Adjustment Branch and Department are required for the CB Integration. These are used for tax adjustments created when the return is accepted. (Accredo Saturn Only)
AR Discount Adjustments
AP Discount Adjustments
Available for Invoice (Accruals) Tax Basis only.
Selected,
Accredo will automatically account for GST on AR Receipt / AP Payment Settlement discounts by creating GST Adjustments at the GST Return form, based on allocated settlement discount. Adjustment occurs in the allocation period. Allocations relating to Discount Adjustments are locked when the GST period is closed by accepting the return form.
Cash Book
Payment Type
The default CB payment type. Select from
Withdrawal
or
Electronic Payment
.
Payment Reference
A reference for payments. For Australian regimes, enter the Payment Reference Number (PRN).
Bank Account Code
The bank account to use for the tax regime.
Tax Analysis Code
Analysis code for tax for the regime.
Provisional Analysis Code
Analysis code for provisional tax for the regime. Only available for the NZ Base Regime.
See Also
Tax Regime Settings - General tab

---

## Tax Regime Settings - Provisional tab

Source: https://accredo.co.nz/webhelp/TaxRegimeSettings_Provisional.htm

Tax Regime Settings - Provisional tab
Navigator > Setup > Goods and Services Tax > Tax Regimes > Provisional tab
For the New Zealand Regime only, Provisional Tax may be filed with the GST Return. When the Provisional Type is Manual or Ratio, a Provisional tab will be included in the
GST Return Form
.
Provisional Type
Set the Provisional Type for the regime. Select from:
None
- don't include Provisional Tax with the GST Return. Provisional tab will not be shown. GST Return form submission is type 101A.
Manual
- Provisional Tax will be calculated manually and entered on the GST Return. GST Return form submission is type 103.
Ratio
- Accredo will calculate Provisional Tax using the Ratio method and the ratio provided by the IRD and entered below. GST Return form submission is type 103.
Provisional Return Months
The number of months between Provisional Tax payments.
Provisional Ratio
For
Ratio
Provisional Type
tax, the ratio used to calculate provisional tax.
Last Provisional Date
The end date of the last tax period which included Provisional Tax. This is read-only.
Next Provisional Date
The end date of the next Provisional Tax period. Must be a Month End date if the Regime Interval Unit in Company Settings is set to Months.

---

