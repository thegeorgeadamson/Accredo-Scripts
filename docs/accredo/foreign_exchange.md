# Foreign Exchange (FX)

> Multi-currency, exchange rates, realised/unrealised gains

**Sections:** 29

---

## Quick Reference

- [Company Settings - Currency Format tab](#company-settings---currency-format-tab)
- [Exchange Rates](#exchange-rates)
- [Foreign Exchange](#foreign-exchange)
- [Foreign Exchange - Add Layout](#foreign-exchange---add-layout)
- [Foreign Exchange - Exchange Rate Required](#foreign-exchange---exchange-rate-required)
- [Foreign Exchange - Maintain](#foreign-exchange---maintain)
- [Foreign Exchange - Reports](#foreign-exchange---reports)
- [Foreign Exchange - Save Exchange Rate](#foreign-exchange---save-exchange-rate)
- [Foreign Exchange - Setup](#foreign-exchange---setup)
- [Foreign Exchange - Tasks](#foreign-exchange---tasks)
- [Foreign Exchange Calculations](#foreign-exchange-calculations)
- [Foreign Exchange Functions](#foreign-exchange-functions)
- [FX Add Currency](#fx-add-currency)
- [FX Currency](#fx-currency)
- [FX Enter Exchange Rates](#fx-enter-exchange-rates)
- [FX Exchange Rate - Exchange Rates tab](#fx-exchange-rate---exchange-rates-tab)
- [FX Exchange Rate Limits](#fx-exchange-rate-limits)
- [FX Rate Type](#fx-rate-type)
- [FX Settings](#fx-settings)
- [FX Tutorial: Foreign Currency and Cash Book](#fx-tutorial-foreign-currency-and-cash-book)
- [FX Tutorial: Foreign Currency and General Ledger](#fx-tutorial-foreign-currency-and-general-ledger)
- [FX Tutorial: Foreign Currency Job Costing](#fx-tutorial-foreign-currency-job-costing)
- [FX Tutorial: Foreign Currency Purchasing](#fx-tutorial-foreign-currency-purchasing)
- [FX Tutorial: Foreign Currency Reporting](#fx-tutorial-foreign-currency-reporting)
- [FX Tutorial: Foreign Currency Sales](#fx-tutorial-foreign-currency-sales)
- [FX Tutorial: Setup Foreign Currency](#fx-tutorial-setup-foreign-currency)
- [FX Tutorial: Toolbar Shortcut for Exchange Rates Website](#fx-tutorial-toolbar-shortcut-for-exchange-rates-website)
- [FX Tutorials](#fx-tutorials)
- [Realised and Unrealised Balances](#realised-and-unrealised-balances)

---

## Company Settings - Currency Format tab

Source: https://accredo.co.nz/webhelp/CompanySettings_CurrencyFormat.htm

Company Settings - Currency Format tab
Navigator > Setup > Company > Configuration > Settings > Currency Format tab
See also
Company Settings - General tab
.
Set defaults for the way amounts are structured in Accredo. The defaults can be overridden later.
Context
Currency Format can be set for the following contexts in Accredo:
Forms,
determines how currency will be displayed for Currency, Amount and Price edits on forms, grids and calculators. It determines how amounts are shown in forms when you are using Accredo.
Reports,
determines how currency will be displayed for Amounts, FX Amounts and Prices on report layouts including Sales Analysis, Job Analysis and Purchase Analysis reports, and as the default for Custom reports. It determines how amounts are displayed on Accredo reports.
Financial Reports,
determines default formatting for currency for General Ledger Financial reports.
Documents,
determines default currency formatting for documents.
MaxBasic,
determines default currency formatting when the
FormatNumber
function is used. It determines how amounts are structured by any scripting or code.
We recommend leaving the
MaxBasic
default for Currency Symbol False, Negative Format Leading and Grouping None and being explicit with a
Format string
if you require a different output.
Currency Symbol
Select whether to display the currency symbol for each context type. Defaults to
unselected
. It is recommended that the currency symbol is displayed for all contexts except MaxBasic.
Negative Format
Select for each context the type of format for displaying negative values. For example, for Financial Reports, you may want to see negative amounts as bracketed.
Grouping
This determines the way thousands and decimals are grouped for amounts. Different currencies group thousands and apply decimals to amounts in different ways. For example:
Swiss Franc uses an apostrophe as a grouping symbol.
US dollar uses a comma as a grouping symbol.
You can select to use the grouping standards for the base currency (
Base
), foreign currency (
Currency
) or no formatting (
None
).
It is unusual to select
Currency
for any context other than for Documents, as you may want Documents sent out to show amounts in the format of the foreign currency.
It is recommended the Grouping for MaxBasic be set to
None
, so amounts can be processed as numbers. For example, when MaxBasic exports amounts to a CSV file, amounts can be exported as numbers rather than strings.

---

## Exchange Rates

Source: https://accredo.co.nz/webhelp/ExchangeRateInput.htm

Exchange Rates
When figures need to be recalculated, you may be prompted for exchange rates.
Fields
Period
The Period the rate is valid in.
Date
The date the rate is used.
Grid Fields
Currency Code
Currency Code for the row. All active currencies other than the Base currency are listed.
Rate Type
The type of rate to use.
Exchange Rate
The exchange rate to use.
Buttons
Save Rates
Save back to Exchange Rate Maintenance for the date specified in the
Date
field.
Run
(F9)
Calculate amounts based on rates entered.
Cancel
(
Esc
)
Close the form and discard all changes.
See Also
Global Tools

---

## Foreign Exchange

Source: https://accredo.co.nz/webhelp/ForeignExchange.htm

Foreign Exchange
AR, IN, OE, AP, PO, CB, SP, are multi-currency, analysis is base only - sales groups, areas, people, expense and income analysis.
GL and FA remain base currency only.
JC is base currency for costs, FX and base for sell on transactions, estimates and jobs; Analysis and WIP are all in base currency, but you can quote/invoice foreign customers.
IC is base currency except for Supplier Costs and Sell prices.
GST Return base only.
The following modules support foreign currency:
Accounts Receivable, Invoicing System, Order Entry.
Inventory Control - Sell Prices and Supplier Costs.
Accounts Payable, Purchase Orders.
Cash Book module is required to turn on Foreign Sales, Purchases or Bank Accounts.
Job Costing - Sell prices and Invoicing..
Non-Foreign currency modules:
Fixed Assets.
General Ledger - Module Batches, unrealised and realised exchange variations transfer to GL in base currency.
Amount and Price fields are the foreign currency fields. Base currency fields have
Bs
as a suffix. Base currency fields can be customised into grids and report layouts as necessary. If Foreign Exchange is not available then the Amount and Price fields are the same as those with a
Bs
suffix.
In This Section
Foreign Exchange - Maintain
Foreign Exchange - Tasks
Foreign Exchange - Reports
Foreign Exchange - Setup
Foreign Exchange Calculations
Foreign Exchange - Exchange Rate Required
Foreign Exchange - Save Exchange Rate
FX Tutorial: Setup Foreign Currency

---

## Foreign Exchange - Add Layout

Source: https://accredo.co.nz/webhelp/FXReports.htm

Foreign Exchange - Add Layout
Navigator > Reports > Foreign Exchange > Add Layout
You can add and customise layouts. Once you have added a layout, it becomes a report and will be available from the appropriate Reports folder.
See also
Report Selections Form
.
Layouts
Exchange Rates
Report exchange rates by currency and rate type over a date range.

---

## Foreign Exchange - Exchange Rate Required

Source: https://accredo.co.nz/webhelp/EnterExchangeRate.htm

Foreign Exchange - Exchange Rate Required
When there is no valid exchange rate set for a Currency and Date, Accredo will prompt to enter the Exchange Rate details.
Currency
Select the Currency.
Rate Type
Select the Rate Type.
Date
Enter the effective date for the exchange rate.
Exchange Rate
Enter the exchange rate for that date.

---

## Foreign Exchange - Maintain

Source: https://accredo.co.nz/webhelp/ForeignExchange_Maintain.htm

Foreign Exchange - Maintain
Navigator > Maintain > Foreign Exchange > Exchange Rate Maintenance
In This Section
FX Exchange Rate Limits
FX Exchange Rate - Exchange Rates tab

---

## Foreign Exchange - Reports

Source: https://accredo.co.nz/webhelp/ForeignExchange_Reports.htm

Foreign Exchange - Reports
Navigator > Reports > Foreign Exchange
In This Section
Foreign Exchange - Add Layout

---

## Foreign Exchange - Save Exchange Rate

Source: https://accredo.co.nz/webhelp/SaveExchangeRate.htm

Foreign Exchange - Save Exchange Rate
When the Save Exchange Rate button is selected, Accredo will prompt to enter the Exchange Rate details to be saved.
Currency
Select the Currency.
Rate Type
Select the Rate Type.
Date
Enter the effective date for the exchange rate.
Exchange Rate
Enter the exchange rate for that date.
Expiry Date
Enter the expiry date for the exchange rate.

---

## Foreign Exchange - Setup

Source: https://accredo.co.nz/webhelp/ForeignExchange_Setup.htm

Foreign Exchange - Setup
Navigator > Tasks > Foreign Exchange > Setup
In This Section
FX Settings
FX Currency
FX Rate Type

---

## Foreign Exchange - Tasks

Source: https://accredo.co.nz/webhelp/ForeignExchange_Tasks.htm

Foreign Exchange - Tasks
Navigator > Tasks > Foreign Exchange > Tasks
In This Section
FX Enter Exchange Rates

---

## Foreign Exchange Calculations

Source: https://accredo.co.nz/webhelp/ForeignExchangeCalculations.htm

Foreign Exchange Calculations
Unrealised Gain / Loss on Exchange
The Total Unrealised Gain / Loss on exchange for FX transactions that are not
Fixed Rate
is calculated as the
UnallocatedAmount (FX) / Revaluation Exchange Rate, less the UnallocatedAmountBs,
calculated at the transaction exchange rate.
As the unallocated amount is reduced by allocation, the Unrealised Gain / Loss is reduced accordingly. When a transaction is fully allocated total Unrealised Gain / Loss for the transaction is zero.
Realised Gain / Loss on Exchange
Realised Gain / Loss for a transaction is calculated during allocation as
DebitAllocationAmountBs less CreditAllocationAmountBs
.
Realised Gain / Loss occurs in the period of the allocation and is assigned to one of the transactions in the allocation based on a rule. Fixed rate transactions may incur Realised Gain / Loss.
Invoices and Credits take the Gain / Loss over Payments, Receipts and Journals, where both transactions for an allocation are from the same grouping (for example, Invoices and Credits being the first group, and Receipts, Payments, Journals the second), the earlier transaction takes the Gain / Loss.
Unrealised Revaluation Reserve
Unrealised Revaluation Reserve is the
Bank Account Balance or Exchange Rate used on Revalue Bank accounts, less Bank Account Balance BS
before Revaluation.
Unrealised variation is cleared when the bank account balance goes to zero.

---

## Foreign Exchange Functions

Source: https://accredo.co.nz/webhelp/ForeignExchangeFunctions.htm

Foreign Exchange Functions
Function
Description
ConvertBaseToFX
Converts a base amount to an FX amount.
ConvertFXToBase
Converts an FX amount to a base amount.
CurrencyOf
Returns the currency code of a currency value.
GetBaseCurrency
Returns the currency code for the base currency.
GetExchangeRate
Returns the exchange rate for a currency code, rate type and date. Requires
Exchange Rate Table
.
GetLowerRateLimit
Returns the lower exchange rate limit for a currency code.
GetUpperRateLimit
Returns the upper exchange rate limit for a currency code.
IsCurrency
Returns true for currency values.
MakeCurrency
Returns a currency value for an amount and currency code.
SetExchangeRate
Sets the exchange rate for a currency code, rate type and date with optional expiry date. Requires
Exchange Rate Table
.
SetRateLimits
Sets Lower and Upper rate limits for a Currency.
In This Section
ConvertBaseToFX - MaxBasic Function
ConvertFXToBase - MaxBasic Function
CurrencyOf - MaxBasic Function
GetBaseCurrency - MaxBasic Function
GetExchangeRate - MaxBasic Function
GetLowerRateLimit - MaxBasic Function
GetUpperRateLimit - MaxBasic Function
IsCurrency - MaxBasic Function
MakeCurrency - MaxBasic Function
SetExchangeRate - MaxBasic Function
SetRateLimits - MaxBasic Function
See Also
MaxBasic Functions

---

## FX Add Currency

Source: https://accredo.co.nz/webhelp/FXCurrencies_AddCurrency.htm

FX Add Currency
Navigator > Settings > Foreign Exchange > Currencies >
Insert
(F4)
Add foreign currencies and set rate limits.
Currency
Type the currency code, or select a currency code from the list.
Minimum Rate
Specify the minimum acceptable rate for the currency. This must be greater than zero. (Required)
Maximum Rate
Specify the maximum acceptable rate for the currency. This must be greater than zero. (Required)
Buttons
OK
(F9)
Accept changes.
Cancel
(Esc)
Discard changes and close the form.

---

## FX Currency

Source: https://accredo.co.nz/webhelp/FXCurrencies.htm

FX Currency
Navigator > Setup > Foreign Exchange > Currencies
Insert the Currencies for Customers, Creditors and Bank Accounts. A full ISO Currency table is provided. Add only the currencies you work in. Currencies may be made inactive, but not deleted once they have been added. If Importing from Subsidiaries in the GL, base currency for all subsidiary companies must be added as a currency.
Currency Code
Displays all currency codes added for the company. Click
to insert a new currency from the list.
Name
The name of the currency.
GL Unrealised
GL Realised
GL Reserve
GL accounts for exchange variations, defaults from:
Navigator > Setup > FX > Settings (can be changed).
Cost Prices
You can specify the number of decimal places for Cost Prices for the currency up to 6 decimal places.
Sell Prices
You can specify the number of decimal places for Sell Prices for the currency up to 6 decimal places.
Amount
Decimal places for the currency. Read-only.
Decimal Symbol
Usually a period but can be changed per currency.
Grouping Symbol
The thousands separator. Usually a comma but can be changed per currency.
Symbol
The currency symbol. Can be changed. For example, you may wish to change the symbol for AUD from
$
to
AUD$
.
Symbol Position
You can change the symbol position.
Inactive
You can make currencies inactive.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to form view to see the FX Currency details.
Insert
(F4)
Insert a FX currency. Opens
FX Add Currency
.
Print
(Ctrl+P)
Print a report of FX Currencies or save as an Excel Worksheet or PDF file to send by email.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other users may have made.
Restore Defaults
(Alt+R)
A currency can be reverted to the Accredo defaults for the currency.
In This Section
FX Add Currency

---

## FX Enter Exchange Rates

Source: https://accredo.co.nz/webhelp/FXExchangeRates.htm

FX Enter Exchange Rates
Navigator > Tasks > Foreign Exchange > Enter Exchange Rates
Enter or edit all rates for a date. Exchange rates for the Rate date, Currency code and Rate type are shown or entered in the cells.
Rate Date
Select the effective date for the rates you want to enter or edit.
Expiry Date
Optionally enter an expiry date for the rates. If an expiry date is not specified rates are effective until the effective date of the next rate for the same Currency Code and Rate Type.
Currency
Currency Code for the row. All active currencies other than the Base currency are listed.
Buy
The buy rate for the currency as from the Rate Date.
Sell
The sell rate for the currency as from the Rate Date.
Fin
The financial rate for the currency as from the Rate Date.
Edit
(F11)
Click to edit the exchange rates.

---

## FX Exchange Rate - Exchange Rates tab

Source: https://accredo.co.nz/webhelp/FXExchangeRateMaintenance_ExchangeRates.htm

FX Exchange Rate - Exchange Rates tab
Navigator > Maintain > Foreign Exchange > Exchange Rate > Exchange Rates tab
You can key in or import exchange rates for each currency that will be fetched by Accredo when entering transactions or documents. Accredo will check the transaction or document date and rate type then fetch the exchange rate for the day. If a rate is not specified for that day, it will fetch the rate closest to the date.
Currency
Select the Currency.
Rate Type
Select the Rate Type.
From Date
Select the start date to enter the exchange rates for.
To Date
Select the end date to enter the exchange rates for.
Grid Fields
Date
Enter the effective date for the exchange rate.
Exchange Rate
Enter the exchange rate for that date.
Reciprocal Rate
This is calculated as
1
divided by the exchange rate. If you adjust the reciprocal rate, the exchange rate is back calculated.
Expiry Date
If you are not entering exchange rates daily, you can key in a rate to be used from the date up to the expiry date. If the expiry date is not entered the rate remains valid till the next exchange rate effective date.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new line.
Delete
(F3)
Delete a selected line.
Print
(Ctrl+P)
Print a report for the grid.
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
Import From File
(Ctrl+I)
Import exchange rates from a file.
Export To File
(Ctrl+E)
Export exchange rates to a file.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
Exchange Rates Import Export File Format
The Import file must be a text file with one line per Exchange rate. The fields on the line may be separated by Tab characters (Tab delimited), or commas (CSV format).
The first line of the file must contain the version number
MER3.00
Field
Format
Size
Effective Date
Date
Exchange Rate
Numeric
Example
MER3.00
2/09/2008,0.8106
3/09/2008,0.8119
4/09/2008,0.8117
5/09/2008,0.8104
8/09/2008,0.8103
9/09/2008,0.8149
10/09/2008,0.8232
In This Section
FX Exchange Rate - Graph tab

---

## FX Exchange Rate Limits

Source: https://accredo.co.nz/webhelp/FXRateLimits.htm

FX Exchange Rate Limits
Navigator > Maintain > Foreign Exchange > Exchange Rate Limits
Enter and maintain upper and lower limits for exchange rate validation. Permission for editing and overriding rate limits is Foreign Exchange > Rate Limits.
NOTE: Exchange Rate Limits are required to eliminate errors that can occur with incorrect exchange rates.
Low/High From Date
Low/High To Date
use the calendar to select dates.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Zoom to Form view. View code details. Codes can be inserted, edited and deleted.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Grid Fields
Currency
The Currency code for the row.
Minimum
The minimum rate to allow. Must be greater than zero.
Maximum
The maximum rate to allow. Must be greater than zero.
Low
The lowest rate from the rate table over the date range specified.
High
The highest rate from the rate table over the date range specified.

---

## FX Rate Type

Source: https://accredo.co.nz/webhelp/FXRateTypeMaintenance.htm

FX Rate Type
Navigator > Setup > Foreign Exchange > Rate Types
Exchange Rate Types may be entered.
These are used to set the Default Rate Types, in
FX Settings
.
Rate Types are also used to look up rates in the
Exchange Rates table
, combined with the
Currency Code
and
Date.
Code
Code for the rate type.
Description
Description of the rate type.
Inactive
You can make rate types inactive.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a rate type in the grid.
Delete
(F3)
Delete the selected rate type.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other users may have made.

---

## FX Settings

Source: https://accredo.co.nz/webhelp/FXSettings_General.htm

FX Settings
Navigator > Setup > Foreign Exchange > Settings
Base Currency Code
Set when the Company is created or during data conversion (cannot be changed).
Allow Foreign Sales
Select if you sell to foreign customers (Accounts Receivable required).
Allow Foreign Purchases
Select if you purchase from foreign creditors (Accounts Payable required).
Allow Foreign Bank Accounts
Select if you operate foreign bank accounts. (Cash Book required).
Use Exchange Rate Table
Selected,
(default)
Exchange Rate table
will look up the exchange rate.
If an Exchange Rate is required the rate will be looked up in the Exchange Rate table based on Currency Code,
Rate Type
and Date. It is important to regularly
Enter Exchange Rates
if the Exchange Rate table is used.
Clear,
Exchange Rates must be entered manually.
Revalue Fixed Rate Transactions
Selected,
unallocated Fixed rate transactions in Accounts Receivable and Accounts Payable will be included in Revalue Foreign balances and generate unrealised exchange variations.
Clear,
Fixed rate transactions are excluded from revaluation and do not create unrealised exchange variation.
Default Rate Types
Default Selling
Default Rate type used in AR, IN, and OE and for IC and JC Sell Prices. Defaults to
SELL
. This is the buy rate from the bank.
Default Purchasing
Default Rate type used in AP, PO and for Supplier costs in IC. Defaults to
BUY
. This is the sell rate from the bank.
Default Financial
Default Rate type used in CB. Defaults to
FIN
.
Default Average
Default Rate type used for converting Income and Expense account classes when importing GL Batches from subsidiaries in a different base currency. Defaults to
FIN
.
Add Rate types from Navigator > Setup > Foreign Exchange >
Rate Types
.
Default General Ledger Integration
Foreign balances are revalued for an accurate picture of current business commitments and their worth if repatriated. See
Foreign Exchange Calculations.
Unrealised Gain/Loss Account
Specify the GL account for this. AR and AP unallocated transaction revaluations result in journals between this account (Expense account in Cost of Sales section of Chart Of Accounts) and Sundry Debtors or Sundry Creditors from Customer and Creditor group respectively.
Realised Gain\Loss Account
Specify the GL account for this. Realised Gain Loss is an Expense account in Cost of Sales section of Chart Of Accounts. Realised Gain Loss in AR and AP occurs on allocation. Realised Gain Loss is attributed to an item in the allocation pair based on the following rules:
Invoices and Credits take the Gain\Loss over Payments, Receipts and Journals, where both transactions for an allocation are from the same grouping (for example, Invoices and Credits being the first group, and Receipts, Payments, Journals the second), the earlier transaction takes the Gain\Loss.
Realised Gain\Loss from AR or AP results in journals between Realised Gain\Loss (Expense account in Cost of Sales section of Chart Of Accounts) and Sundry Debtors and Creditors, and reverses Unrealised Gain Loss (if any) between Unrealised Gain\Loss and Sundry Debtors and Creditors.
Realised Gain Loss in CB
- occurs when AR sourced unbanked foreign currency items are banked to a base currency bank account. Any difference between the sum of the AR receipts converted to Base and the deposit amount is realised gain/loss on the AR transactions. Results in journals as follows:
DR GL Account from Bank Account Transaction Amount.
CR AR Clearing.
CR or DR Realised Gain\Loss.
Unrealised Variation Reserve Account
Specify the GL account for this. CB bank balance revaluations result in journals between Unrealised Revaluation Reserve (Capital account under Asset Revaluation Reserve in Chart Of Accounts) and the GL account for Bank Account.
Buttons
Edit
(F11)
Enter edit mode.
Save
(F9)
Saves any changes.
If you have any Exchange Rates without Rate Limits, you will be asked to add rate limits now. Click
Yes
and the
FX Exchange Rate Limits
form will be displayed.
NOTE: Exchange Rate Limits are required to eliminate errors that can occur with incorrect exchange rates.
Cancel
(Esc)
Closes without saving changes.

---

## FX Tutorial: Foreign Currency and Cash Book

Source: https://accredo.co.nz/webhelp/FXTutorialForeignCurrencyAndCashBook_1.htm

FX Tutorial: Foreign Currency and Cash Book
You can transfer funds between Bank Accounts in different currencies. If you are using the Rates Table the Exchange Rate will be retrieved but can be overridden. If you are not using the Rates Table you will need to enter an Exchange Rate.
Banking Receipts into a Foreign Bank Account
Realised Variations Dissections will occur when you bank foreign AR Receipts into a Bank Account of a different currency if the Exchange Rate differs between the Banking Items and the Banking Summary. These journals go into the Cash book Batch.
The GL Account used here is mapped from the Analysis Code selected in the
Realised Variation Code
field in Cash Book Settings > Integration Tab.
Realised Variations
During the Revaluation process the net movements of the Period are compared with the Bank Account Opening Balances, and Realised Variations are calculated when the funds move towards zero. This is done by going to Navigator > Tasks > CB > Revalue Foreign Balances.
Revalue Foreign Balances is required as part of the End of Period Update process, but you can Revalue as often as you wish.
In Cash Book, Bank Account Balances are Revalued, not Transactions.
You can customise to show the
Variation Realised Bs
field in the CB Bank Account Maintenance, Balances tab.
Variation Realised Bs Calculation
To calculate Variation Realised Bs, first an Opening Rate must be calculated, to be used when backing out Opening Unrealised Variations.
The
Opening Rate
calculation is:  PeriodOpeningBalance / (PeriodOpeningBalanceBs - OpeningUnrealisedVariationBs)
Then Accredo checks the Opening Balance against the Closing Balance and if both balances are in funds, any Withdrawal Activity will result in a Realised Variation Bs.
The
Realised Variation Bs
calculation is: (WithdrawalActivity / OpeningRate) – WithdrawalActivityBs
If the Opening and Closing balances are both in overdraft, any Deposit Activity will result in a Realised Variation Bs.
The
Realised Variation Bs
calculation is: (DepositActivity / OpeningRate) – DepositActivityBs
If the Opening Balance starts in overdraft but ends in funds, a
Realised Against Opening Bs
must be calculated first.
The
Realised Against Opening Bs
calculation is: - (PeriodOpeningBalance / Opening Rate)+((PeriodOpeningBalance / WithdrawalActivity)*WithdrawalActivityBs)
The
Realised Variation Bs
calculation in this situation is:  RealisedAgainstOpening +((OpeningBalance +WithdrawalActivity) / (DepositActivity / DepositActivityBs)-((OpeningBalance +WithdrawalActivity) \ WithdrawalActivity)*WithdrawalActivityBs)
Alternatively if the Opening Balance starts in funds but ends in overdraft, a
Realised Against Opening Bs
must be calculated first.
The
Realised Against Opening Bs
calculation for this situation is: - (PeriodOpeningBalance / Opening Rate)+((PeriodOpeningBalance / DepositActivity)*DepositActivityBs)
The
Realised Variation Bs
calculation is:  RealisedAgainstOpening +((OpeningBalance +DepositActivity) / (WithdrawalActivity / WithdrawalActivityBs)-((OpeningBalance +DepositActivity) / DepositActivity)*DepositActivityBs)
Unrealised Variations
Unrealised Variations are also calculated when Bank Accounts are Revalued.
You can customise to show the
Variation Unrealised Bs
in the CB Bank Account Maintenance, Balances tab.
Unrealised Variation Bs Calculation
The
Unrealised Variation Bs
calculation is: (Period Closing Balance/ Revaluation Exchange Rate)-(PeriodClosingBalanceBs Before Revaluation+VariationRealisedBs).
If the Bank Account has already been Revalued during the month, the Variations are deducted from the Period Closing Balance Bs before being recalculated.
Transfer to General Ledger
Navigator > Tasks > Cash Book > Transfer to General Ledger
When you transfer to General Ledger for Cash Book, Accredo creates a separate Cash Book Exchange Variation batch.
To reconcile your GL Realised Gain Loss on Exchange and GL Unrealised Revaluation Reserve with CB sourced Transactions, use: Navigator > Reports > Cash Book > Account Reports > Exchange Variation Sequence.
This report lists the exchange variations in the period order they were calculated in.  You can filter on Variation Type = U for Unrealised Variations, and Variation Type=R for Realised Variations, or you can group the report by Variation Type.
See Also
FX Tutorials

---

## FX Tutorial: Foreign Currency and General Ledger

Source: https://accredo.co.nz/webhelp/FXTutorialForeignCurrencyAndGL.htm

FX Tutorial: Foreign Currency and General Ledger
All figures in the General Ledger are stored in Base Currency.
Import from Subsidiaries
Navigator > Tasks > General Ledger > Import from Subsidiaries
If you import from a a subsidiary company with a different Base currency, you will be prompted for an Exchange Rate for Income / Expense Accounts, and an Exchange Rate for Asset / Liability / Capital Accounts. Batches will be converted based on the rates entered.
See Also
FX Tutorial: Setup Foreign Currency

---

## FX Tutorial: Foreign Currency Job Costing

Source: https://accredo.co.nz/webhelp/FXTutorialForeignCurrencyJC_1.htm

FX Tutorial: Foreign Currency Job Costing
You can create a Job for a Foreign Customer. If you are not using the Rates Table, you will be prompted for an Exchange Rate. If you are using the Rates Table the Exchange Rate will be retrieved from Rates Table based on the Date Entered.
The Exchange Rate is used to calculate the Base Amount for the Job Estimate, and is used on the Job Invoices if the Rates is Fixed. If you have organised Forward Cover, you should fix the rate.
If you are using the Rates Table, and want to revalue your Job Estimate, enter a date in the
Date Valued
field on the Job Maintenance form. The Exchange Rate will be re-retrieved from the Rates Table for that date.
The Costs on Jobs are stored in Base Currency, but the Sell Prices are stored in both Base and Foreign Currency.
See Also
FX Tutorials

---

## FX Tutorial: Foreign Currency Purchasing

Source: https://accredo.co.nz/webhelp/FXTutorialForeignCurrentyPurchasing.htm

FX Tutorial: Foreign Currency Purchasing
When you enter transactions or documents for foreign Creditors, the Exchange Rate field will be available.
If you selected
Use Exchange Rate Table
in Foreign Exchange Settings, Accredo will retrieve the exchange rate based on the Transaction or Document Date, Rate Type and Currency code.  You can override the Exchange Rate retrieved. You can also save the rate back to your exchange rate table by clicking the Save Exchange Rate button (depending on your User Permissions).
If you are not using the Exchange Rate Table, you must key in the Exchange Rate. The rate you enter will be remembered while the form is open and will be used for subsequent transactions or documents in the same currency.
Forward Cover
If you have arranged Forward Cover, you can enter the given
Exchange Rate
and click the
Fix Exchange Rate
(
Ctrl+F
) button.
Fixing a rate means it will not be updated and will be excluded from Revaluations. When an Invoice with a Fixed Rate is paid, Accredo will warn if the Payment Exchange Rate does not match when manually allocating a payment or receipt.
Non-Fixed Exchange Rates
If you do not fix the Exchange Rate and you are using the Rates Table, the Exchange Rate will be updated from the Rates Table each time any of the Rate Type, Currency Code or Transaction or Document Date are changed. It will also be updated when the document is posted or a revaluation is performed.
Exchange Rates on Purchase Orders and Shipments can be optionally revalued. See
PO Revalue Foreign Orders
and
AP Revalue Foreign Shipments
.
Unallocated Transactions which are not fixed must be revalued at End of Period, and an Unrealised Variation will then be created.  See
AP Revalue Foreign Balances
.
Paying Foreign Creditors from a Bank Account in their currency
If you deal with overseas Creditors regularly, you can set up a bank account in their currency to pay from. When you enter the Payment, enter the Exchange Rate. The Bank Account will default from the Creditor's Creditor Group.
Paying Foreign Creditors from Base or other currency Bank Account
If you are paying your Creditor from a bank account in a different currency and you know the amount taken from your Bank Account then:
Enter the amount you are paying the Creditor in their currency in the
Gross
field.
Enter the amount the bank advises will be deducted from your Bank Account in the
Banking Amount
field.
If the bank will charge you for the transaction, enter the
Bank Charges
.
Accredo will automatically calculate the
Exchange Rate
from the
Gross
and
Banking Amount
fields.
If you don't know the amount that will be taken from your Bank Account:
Unselect the
Bank Through
check box, to create an Unbanked Banking Item.
When the amount deducted is known, enter this on the CB Banking Summary.
Prepayment Deposits at Fixed Rate
Often Foreign Creditors will require a pre-payment before they ship the goods, so the Payment will be entered before the Invoice.  If you have Forward Cover and have to enter a pre-payment deposit Payment, followed by a Payment for the Balance of the Invoice when the goods arrive, you may have two payments with different Exchange Rates.  When it comes time to enter the Invoice, to minimise the Exchange Variation you can calculate the Exchange Rate to use. The calculation is the Sum of the Base Amount of the Payments Divided by the FX Amount on the Invoice.
Foreign Exchange Variations
Realised Variations
When the Exchange Rate on a Payment differs from the Exchange Rate on the Invoice(s) which the Payment is allocated against, a Realised Variation is calculated in the Allocation Period and any Unrealised Variation is reversed.
The Realised Variation shows against the Invoice.  You can customise to show the
Variation Realised Bs
in the AP Creditor Transaction tab.
Invoices and Credits take the Gain or Loss over Payments and Journals, where both transactions for an allocation are from the same grouping (for example, Invoices and Credits being the first group, and Payments and Journals the second). The earlier transaction takes the Gain / Loss.
Variation Realised Bs Calculation
Realised Gain/Loss for a transaction is calculated during allocation as DebitAllocationAmountBs less CreditAllocationAmountBs.
Unrealised Variations
Unrealised Variations are calculated when Unallocated Foreign Exchange Transactions that are not fixed are revalued.
Go to Navigator > Tasks > Accounts Payable > Revalue Foreign Balances.
Enter the exchange rates, then click
Run
(
F9
).
Revalue Foreign Balances is required as part of the End of Period Update process, but you can Revalue more often.
You can customise to show the
Variation Unrealised Bs
in the AP Creditor Transaction tab.
Unrealised Variation Bs Calculation
The Unrealised Gain / Loss on exchange for FX transactions that are not Fixed is calculated as the UnallocatedAmount (FX) / Revaluation Exchange Rate, less the UnallocatedAmountBs, calculated at the transaction exchange rate.
As the unallocated amount is reduced by allocation, the Unrealised Gain / Loss is reduced accordingly. When a transaction is fully allocated total Unrealised Gain / Loss for the transaction is zero.
Revalue Foreign Orders
Go to Navigator > Tasks > Purchase Orders > Revalue Foreign Orders.
You can optionally Revalue Foreign Unprocessed Purchase Orders that are not fixed.
The Revaluation date is then written to the Valuation Date on the Orders.
Revalue Foreign Shipments
Go to Navigator > Tasks > Accounts Payable> Revalue Foreign Shipments.
You can optionally Revalue Unposted Shipments if you are using the Rates Table.
AP Transfer to GL
Go to Navigator > Tasks > Accounts Payable > Transfer to General Ledger.
Select the Period to transfer up to, then click OK.
When you transfer to the General Ledger, Accredo will create a separate Accounts Payable Exchange Variation batch. This is shown in the GL Batches Transferred results screen. you can double-click this batch or click
Open
(
F12
) to see the transactions in the batch.
If you are integrating to GL from AP on a Detailed Basis (selected in AP Settings - Integration tab), you can select a line in the Batch then click
Drill Down
(
Shift+F12
) to open the originating Transaction.
You can reconcile the Realised and Unrealised Gain Loss on Exchange with AP sourced Transactions in the GL.
Go to Navigator > Reports > Accounts Payable > Transaction Reports > Exchange Variation Sequence.
This report lists the exchange variations in the period order they were generated in, so it will include Transactions from prior periods that were Revalued in the selected period.
You can customise the report to show only Unrealised or Realised transactions.
Go to Navigator > Reports > Accounts Payable > Transaction Reports > Exchange Variation Sequence. Click Options > Customise.
Click
Filter/Sort
(
Ctrl+F2
).
Set:
Field Name
:
VariationType
Op
:
=
Criteria
:
U
(for Unrealised Variations) or
R
(for Realised Variations)
Click
Save
(
F9
).
Click
One Time
(
F9
).
Click
Run
(
F9
).
Viewing Base Currency Balances
When you are viewing Balances for a Foreign Currency Creditor, such as on the Creditor Balances tab, you will see a tab for the Base Currency (such as
NZD
) and a tab for the Foreign Currency (such as
AUD
). Toggle between the tabs to view Balances in the Base Currency and the Foreign Currency.
Viewing Variations
When you are viewing Transactions for a Foreign Currency Creditor, such as on the Creditor Transaction tab, you can customise to show the
Variation Unrealised Bs
,
Variation Realised Bs
and the
Variation Bs
(Total Variation). Where there is a variation, you can click
Show variations
to show all variations for the transaction.
See Also
FX Tutorial: Setup Foreign Currency

---

## FX Tutorial: Foreign Currency Reporting

Source: https://accredo.co.nz/webhelp/FXTutorialForeignCurrencyReporting.htm

FX Tutorial: Foreign Currency Reporting
Trial Balance and Exchange Variation Reports
All report layouts will report foreign currency figures by default.
You can import Aged Trial Balance Reports and Exchange Variation Reports that are customised for Foreign Sales and Purchases and are grouped by Customer / Creditor Group.
The Exchange Variation Reports for AR and AP show all Invoices, Credits and Journals entered in the period selected where a variation has occurred.  Variations can be Unrealised or Realised.  Unrealised Variations are from Revaluations, Realised Variations are from Allocations.
Go to Navigator > Setup > Company > Reporting > Report Layouts.
Click
Import Layout
(
Ctrl+I
).
Open the Foreign Currency Folder.  Click one on of the Reports, then press
Ctrl+A
to select all the report. Then click
Open
. The Reports will be added to your list of Report Layouts.
You can customise base currency figures into your reports where relevant. You may want to edit the display labels for base currency values to use your Base currency code (such as
NZD
or
AUD
) rather than the "Bs" abbreviation.
Reports that include more than one Currency will need to be customised to group by Currency Code or by Customer / Creditor Group. If you see "FX Mixed" on a report, this means there are values for more than one currency in the column. Accredo recognises that it cannot add different currencies together. If you group by Currency, you will get a sub-total per currency. You can also select the Bs (base) fields and total these. They will show the base equivalent of the foreign amounts, and these can be totalled.
Other Reports
Some AR, AP and CB FX Reports you may wish to add are:
Exchange Variation Sequence Report
Go to Navigator > Reports > Accounts Receivable / Accounts Payable / Cash Book > Transaction Reports > Add Layout > Exchange Variation Sequence. This report lists the exchange variations in the period order they were generated in, so will include Transactions from prior periods that were Revalued or allocated in the selected period.
Revaluation Rates Report
Go to Navigator > Reports > Accounts Receivable / Accounts Payable / Cash Book > Transaction Reports > Add Layout > Revaluation Rates. This report list the rates used to Revalue Foreign Balances for the period.
Exchange Variation Report
Go to Navigator > Reports > Cash Book > Account Reports > Add Layout > Exchange Variation. This report shows Variations for the month as a result of Revaluing  the Bank Account Balance and from the movement of funds.
See Also
FX Tutorial: Setup Foreign Currency

---

## FX Tutorial: Foreign Currency Sales

Source: https://accredo.co.nz/webhelp/FXTutorialForeignCurrencySales_1.htm

FX Tutorial: Foreign Currency Sales
When you enter transactions or documents for foreign Customers, the Exchange Rate field will be available.
If you selected
Use Exchange Rate Table
in Foreign Exchange Settings, Accredo will retrieve the exchange rate based on the Transaction or Document Date, Rate Type and Currency code.  You can override the Exchange Rate retrieved. You can also save the rate back to your exchange rate table by clicking the Save Exchange Rate button (depending on your User Permissions).
If you are not using the Exchange Rate Table, you must key in the Exchange Rate. The rate you enter will be remembered while the form is open and will be used for subsequent transactions or documents in the same currency.
Forward Cover
If you have arranged Forward Cover, you can enter the given
Exchange Rate
and click the
Fix Exchange Rate
(
Ctrl+F
) button.
Fixing a rate means it will not be updated and will be excluded from Revaluations. When an Invoice with a Fixed Rate is paid, Accredo will warn you if the Payment Exchange Rate does not match during the allocation process.
Non-Fixed Exchange Rates
If you do not fix the Exchange Rate and you are using the Rates Table, the Exchange Rate will be updated from the Rates Table each time any of the Rate Type, Currency Code or Transaction or Document Date are changed. It will also be updated when the document is posted or a revaluation is performed.
Exchange Rates on Purchase Orders and Shipments can be optionally revalued. See
OE Revalue Foreign Orders
and
IN Revalue Foreign Invoices
.
Unallocated Transactions which are not fixed must be revalued at End of Period, and an Unrealised Variation will then be created.  See
AR Revalue Foreign Balances
.
Receipting Funds from Foreign Customers into a Bank Account in their currency
If you deal with overseas Customers regularly, you can set up a bank account in their currency to pay into. When you enter the Receipt, enter the Exchange Rate if you are not using the Rates Table. The Bank Account will default from the Creditor's Creditor Group.
Receipting Funds from Foreign Customers into Base or other currency Bank Account
If you are entering a Receipt into a bank account in a different currency and you know the amount that will go into your Bank Account then:
Enter the amount being paid in their currency in the
Gross Amount
field.
Enter the amount that will go into your bank account in the
Banking Amount
field.
If the bank will charge you for the transaction, enter the
Bank Charges
.
Accredo will automatically calculate the
Exchange Rate
from the
Gross Amount
and
Banking Amount
fields.
If you don't know the amount that will go into your Bank Account:
Unselect the
Bank Through
check box, to create an Unbanked Banking Item.
When the amount entered is known, enter this on the CB Banking Summary.
Foreign Exchange Variations
Realised Variations
When the Exchange Rate on a Receipt differs from the Exchange Rate on the Invoice(s) which the Receipt is allocated against, a Realised Variation is calculated in the Allocation Period and any Unrealised Variation is reversed.
The Realised Variation shows against the Invoice.  You can customise to show the
Variation Realised Bs
in the AR Customer Transaction tab.
Invoices and Credits take the Gain or Loss over Receipts and Journals, where both transactions for an allocation are from the same grouping (for example, Invoices and Credits being the first group, and Receipts and Journals the second). The earlier transaction takes the Gain / Loss.
Variation Realised Bs Calculation
Realised Gain/Loss for a transaction is calculated during allocation as DebitAllocationAmountBs less CreditAllocationAmountBs.
Unrealised Variations
Unrealised Variations are calculated when Unallocated Foreign Exchange Transactions that are not fixed are revalued.
Go to Navigator > Tasks > Accounts Receivable / Revalue Foreign Balances.
Enter the exchange rates, then click
Run
(
F9
).
Revalue Foreign Balances is required as part of the End of Period Update process, but you can Revalue more often.
You can customise to show the
Variation Unrealised Bs
in the AR Customer Transaction tab.
Unrealised Variation Bs Calculation
The Unrealised Gain / Loss on exchange for FX transactions that are not Fixed is calculated as the UnallocatedAmount (FX) / Revaluation Exchange Rate, less the UnallocatedAmountBs, calculated at the transaction exchange rate.
As the unallocated amount is reduced by allocation, the Unrealised Gain / Loss is reduced accordingly. When a transaction is fully allocated total Unrealised Gain / Loss for the transaction is zero.
Revalue Foreign Orders
Go to Navigator > Tasks > Order Entry > Revalue Foreign Orders.
You can optionally Revalue Foreign Unprocessed Purchase Orders that are not fixed.
The Revaluation date is then written to the Valuation Date on the Orders.
Revalue Foreign Invoices
Go to Navigator > Tasks > Invoicing System >  Revalue Foreign Invoices
You can optionally Revalue Unposted Invoices if you are using the Rates Table. Revaluation will occur automatically when Invoices are posted.
AR Transfer to GL
Go to Navigator > Tasks > Accounts Receivable > Transfer to General Ledger.
Select the Period to transfer up to, then click OK.
When you transfer to the General Ledger, Accredo will create a separate Accounts Receivable Exchange Variation batch. This is shown in the GL Batches Transferred results screen. you can double-click this batch or click
Open
(
F12
) to see the transactions in the batch.
If you are integrating to GL from AR on a Detailed Basis (selected in AR Settings - Integration tab), you can select a line in the Batch then click
Drill Down
(
Shift+F12
) to open the originating Transaction.
You can reconcile the Realised and Unrealised Gain Loss on Exchange with AR sourced Transactions in the GL.
Go to Navigator > Reports > Accounts Receivable > Transaction Reports > Exchange Variation Sequence.
This report lists the exchange variations in the period order they were generated in, so it will include Transactions from prior periods that were Revalued in the selected period.
You can customise the report to show only Unrealised or Realised transactions.
Go to Navigator > Reports > Accounts Receivable > Transaction Reports > Exchange Variation Sequence. Click Options > Customise.
Click
Filter/Sort
(
Ctrl+F2
).
Set:
Field Name
:
VariationType
Op
:
=
Criteria
:
U
(for Unrealised Variations) or
R
(for Realised Variations)
Click
Save
(
F9
).
Click
One Time
(
F9
).
Click
Run
(
F9
).
Viewing Base Currency Balances
When you are viewing Balances for a Foreign Currency Customer, such as on the Customer Balances tab, you will see a tab for the Base Currency (such as
NZD
) and a tab for the Foreign Currency (such as
AUD
). Toggle between the tabs to view Balances in the Base Currency and the Foreign Currency.
Viewing Variations
When you are viewing Transactions for a Foreign Currency Customer, such as on the Customer Transaction tab, you can customise to show the
Variation Unrealised Bs
,
Variation Realised Bs
and the
Variation Bs
(Total Variation). Where there is a variation, you can click
Show variations
to show all variations. for the transaction.
See Also
FX Tutorials

---

## FX Tutorial: Setup Foreign Currency

Source: https://accredo.co.nz/webhelp/FXTutorialSetupForeignCurrency_1.htm

FX Tutorial: Setup Foreign Currency
This tutorial explains how to set up foreign currencies in Accredo. The Cash Book (CB) Module is required for foreign currency.
Go to Navigator > Setup > Foreign Exchange  > Settings.
The
Base Currency
is set based on the Company's Country selected when the Company was created, and cannot be changed. Amounts shown on screen or in reports with a Bs after the name are in the Base currency.
Click
Edit
(
F11
).
Select the Foreign Exchange settings:
Allow Foreign Sales
- select if you sell to foreign Customers (AR).
Allow Foreign Purchases
- select if you buy from foreign Creditors (AP).
Allow Bank Accounts
- select if you have foreign Bank Accounts (CB).
Use Exchange Rate Table
- select if you want exchange rates to be retrieved from an Exchange Rate Table. Rates are retrieved based on CurrencyCode, Rate Type and Date. We recommend using an Exchange Rate Table if you do regular FX transactions. If you do FX transactions infrequently, you can unselect this and enter rates  when prompted.
Revalue Fixed Rate Transactions
- select if you want unallocated fixed rate transactions in AR and AP to be included in the Revaluation of Foreign Balances.
If you are using an Exchange Rate Table, select the Default Rate Types. The defaults available are:
BUY
- Purchasing Rate (Purchases).
FIN
- Financial Rate (Accounts).
SELL
- Selling Rate (Sales).
The defaults can be changed in
FX Rate Type
. The defaults are used for:
Default Selling
- used for Foreign Sales. This is the Buy Rate from the bank.
Default Purchasing
- used for Foreign Purchases. This is the sell rate from the bank.
Default Financial
- used in CB.
Default Average
- used for converting Income and Expense account classes when importing GL Batches from subsidiaries in a different base currency.
The Default General Ledger Integration accounts are used when you add a currency. These are related to the company Chart of Accounts. Consult with your accountant to set the correct accounts for your Chart of Accounts. See
FX Settings
for more details.
Click
Save
(
F9
).
To add Foreign Currencies, go to Navigator > Setup > Foreign Exchange > Currencies.
Click
Insert
(
F4
). Select the
Currency
to add, and set a
Minimum Rate
and
Maximum Rate
. These are used to prevent data entry errors such as decimal place errors. You can also specify decimal places for Cost and Sell Prices. You cannot remove currencies once added, but you can set them to Inactive.
OK
(
F9
). Repeat for each currency required.
Entering Exchange Rates
If you are using an Exchange Rate Table, you can enter the Exchange Rates. Go to Navigator > Task > Foreign Exchange > Enter Exchange Rates. Click
Edit
(
F11
). Enter an expiry date and the rates. Click
Save
(
F9
).
See Also
FX Tutorials

---

## FX Tutorial: Toolbar Shortcut for Exchange Rates Website

Source: https://accredo.co.nz/webhelp/FXTutorialShortcutRatesWebsite_1.htm

FX Tutorial: Toolbar Shortcut for Exchange Rates Website
You can set up a toolbar shortcut to access an Exchange Rate website.
Go to Accredo > Script > Script Editor.
Enter or copy and paste the following code:
Dim Shell as Object
Shell = CreateObject("Shell.Application")
URL = "Add your URL Here"
Shell.ShellExecute(URL)
Change the
"Add your URL Here"
to the URL for your exchange rate website, still enclosed in double quotations. For example, you may want to access the Foreign Exchange Rates website for your bank.
Click
Save...
(
Ctrl+S
). Save the script as
ExchangeRates.Pfs
.
Click Add
Add Shortcut
(
Alt+D
).
Click the Glyph button and choose a glyph.
Select
Available on Toolbar
. Enter t Button Hint such as
Today's Exchange Rate
.
Click
Save
(
F9
).
You can now click the button added to the Accredo toolbar to quickly access current exchange rates.
See Also
FX Tutorials

---

## FX Tutorials

Source: https://accredo.co.nz/webhelp/FXTutorials.htm

FX Tutorials
In This Section
FX Tutorial: Setup Foreign Currency
FX Tutorial: Add Foreign Bank Accounts and Price Lists
FX Tutorial: Add Foreign Customers and Creditors
FX Tutorial: Foreign Currency and Cash Book
FX Tutorial: Foreign Currency and General Ledger
FX Tutorial: Foreign Currency Job Costing
FX Tutorial: Foreign Currency Purchasing
FX Tutorial: Foreign Currency Reporting
FX Tutorial: Foreign Currency Sales
FX Tutorial: Toolbar Shortcut for Exchange Rates Website

---

## Realised and Unrealised Balances

Source: https://accredo.co.nz/webhelp/16284.htm

Realised and Unrealised Balances
Foreign Bank Account Revaluation
Realised and Unrealised Variation
When a foreign Bank Account is revalued, the system calculates two amounts in base currency:
Variation Realised
– the FX effect on the portion of the period’s movement that moves the account towards a zero balance.
Variation Unrealised
– the FX effect required to revalue the remaining closing foreign balance at the valuation exchange rate, after realised variation has been applied.
This approach ensures that:
FX on amounts that are effectively
settled/consumed
(reducing exposure to foreign currency) is treated as
realised
, and
FX on the balance still held (remaining exposure) is treated as
unrealised
.
How the system decides whether deposits or withdrawals drive the realised calculation
The system compares:
the
opening balance sign
(positive, zero, or negative), and
the direction of the
net period movement
(net deposit or net withdrawal)
to decide whether the “towards zero” portion is represented by
withdrawals
or
deposits
for that period.
Practical interpretation:
If the opening balance is
positive (in credit)
, a net
withdrawal
moves the balance towards zero.
realised variation is calculated against
withdrawals
(the “towards zero” portion).
If the opening balance is
negative (overdraft)
, a net
deposit
moves the balance towards zero.
realised variation is calculated against
deposits
(the “towards zero” portion).
If the opening balance is zero, the first movement is away from zero (an exposure is being created).
realised variation is calculated using the side that represents the “towards zero” component within that period’s activity (typically the first “spend/settle” leg, when both deposits and withdrawals exist in the same period).
In other words: the realised calculation is anchored to the activity that represents
reducing exposure
, and that depends on whether you started in credit, overdraft, or zero.
Calculation sequence
The system always calculates in this order:
Variation Realised
Determine which portion of the period’s activity moves the account towards zero.
this portion is used to calculate
Variation Realised
.
Variation Unrealised
Revalue the closing foreign currency balance at the valuation exchange rate.
Subtract the base currency balance after including Variation Realised.
The remaining difference is Variation Unrealised.
Unrealised variation is therefore always calculated after realised variation. If a foreign bank account’s closing balance is zero, any unrealised variation remaining is cleared (because there is no foreign currency position left to revalue).
Worked Example – Zero Opening Balance Account
This example shows how Variation Realised and Variation Unrealised are calculated when a foreign Bank Account starts the period with a zero balance.
Scenario
Bank account currency: USD
Period opening balance: USD 0.00
Deposit USD 1,000.00 at exchange rate 0.75
Withdrawal USD 750.00 at exchange rate 0.65
Revaluation exchange rate: 0.80
Transactions
FX Amount
Rate
Base Currency Amount
Period Opening Balance
0
0
Deposit
1,000.00
0.75
1,333.33
Withdrawal
- 750.00
0.65
-1,153.85
Period Closing Balance
250.00
179.48
Revaluation Rate
0.80
Interpreting the movement
The account starts at zero.
The deposit moves the balance away from zero, creating a foreign currency exposure.
The withdrawal moves the balance back towards zero, reducing that exposure.
Because deposits are greater than withdrawals, the net effect is a deposit and the closing balance is USD 250.00.
The portion of activity that moves towards zero (the withdrawal) gives rise to realised variation.
The remaining balance (USD 250) represents foreign currency still held and will be valued through unrealised variation.
Current Rate
Because the opening balance is not greater than zero, the withdrawal exchange rate is used as the current rate.
Current Rate
= Withdrawal Activity Ã· Withdrawal Activity (Base Currency)
= -750 Ã· -1,153.85
=
0.65
Opening Activity
Opening Activity
= Minimum of (â Period Opening Balance) and Deposit Activity
= Min(0, 1,000)
=
0
Current Activity
Current Activity
= Minimum of (â Withdrawal Activity) and (Deposit Activity â Opening Activity)
= Min(750, 1,000)
=
750
This represents the portion of the period’s activity that moves the balance towards zero.
Current Activity (Base Currency)
Current Activity (Base Currency)
= Ratio(Current Activity, Deposit Activity â Opening Activity)
Ã (Deposit Activity Base Currency â Opening Activity Base Currency)
= (750 Ã· 1,000) Ã 1,333.33
=
1,000.00
Variation Realised (Base Currency)
Current Realised
= (Current Activity Ã· Current Rate) â Current Activity (Base Currency)
= (750 Ã· 0.65) â 1,000
=
153.85
Variation Realised
=
153.85
Variation Unrealised (Base Currency)
Period Closing Balance (Base Currency) before revaluation
= Opening Balance + Deposits + Withdrawals
= 0 + 1,333.33 â 1,153.85
=
179.48
Variation Unrealised
= (Period Closing Balance Ã· Revaluation Rate)
â (Closing Balance before Revaluation + Variation Realised)
= (250 Ã· 0.80) â (179.48 + 153.85)
=
â20.83
Worked Example – Positive Opening Balance Account
This example shows the same calculation where the account starts the period with a positive opening balance.
Scenario
Opening balance: USD 250.00
Opening balance (Base Currency): NZD 312.50
Opening unrealised: NZD â20.83
Deposit USD 1,700.00 at exchange rate 0.75
Withdrawal USD 1,250.00 at exchange rate 0.65
Revaluation exchange rate: 0.80
Transactions
FX Amount
Rate
Base Currency Amount
Period Opening Balance
250.00
312.50
Period Opening Unrealised
-20.83
Deposit
1,700.00
0.75
2,266.67
Withdrawal
-1,250.00
0.65
-1,923.08
Period Closing Balance
700.00
875.00
Revaluation Rate
0.80
Interpreting the movement
The account opens with a positive balance.
Withdrawals move the balance towards zero.
Deposits move the balance away from zero.
Although
deposits are greater than withdrawals
and the closing balance increases, part of the withdrawals still represent movement
towards zero
and therefore give rise to
realised variation
.
The remaining increase in balance is valued as
unrealised variation
.
Opening Rate
Opening Rate
= Period Opening Balance Ã· (Opening Balance Base Currency â Opening Unrealised)
= 250 Ã· (312.50 â â20.83)
=
0.75
Current Rate
Because the opening balance is positive, the deposit exchange rate is used.
Current Rate
= Deposit Activity Ã· Deposit Activity (Base Currency)
= 1,700 Ã· 2,266.67
=
0.75
Opening Activity
Opening Activity
= â1 Ã Minimum of (Opening Balance, Withdrawal Activity Ã â1)
= â1 Ã Min(250, 1,250)
= â250
This represents the portion of withdrawals that reduce the opening balance (movement towards zero).
Current Activity
Current Activity
= â1 Ã Minimum of (Deposit Activity, (Withdrawal Activity â Opening Activity) Ã â1)
= â1 Ã Min(1,700, 1,000)
= â1,000
Opening and Current Activity (Base Currency)
Opening Activity (Base Currency)
= Ratio(Opening Activity, Withdrawal Activity) Ã Withdrawal Activity (Base Currency)
= (â250 Ã· â1,250) Ã â1,923.08
=
â384.62
Current Activity (Base Currency)
= Ratio(Current Activity, Withdrawal Activity â Opening Activity)
Ã (Withdrawal Activity Base Currency â Opening Activity Base Currency)
= (â1,000 Ã· â1,000) Ã â1,538.46
=
â1,538.46
Variation Realised (Base Currency)
Opening Realised
= (Opening Activity Ã· Opening Rate) â Opening Activity (Base Currency)
= (â250 Ã· 0.75) + 384.62
=
51.29
Current Realised
= (Current Activity Ã· Current Rate) â Current Activity (Base Currency)
= (â1,000 Ã· 0.75) + 1,538.46
=
205.13
Variation Realised
= 51.29 + 205.13
=
256.41
Variation Unrealised (Base Currency)
Period Closing Balance (Base Currency) before revaluation
= 312.50 + 2,266.67 â 1,923.08
=
656.09
Variation Unrealised
= (700 Ã· 0.80) â (656.09 + 256.41)
=
â37.50
Summary
Realised variation
is calculated on the portion of activity that moves the balance towards zero.
Unrealised variation
is calculated afterwards to revalue the remaining balance.
Whether deposits or withdrawals drive the realised calculation depends on the
sign of the opening balance
and the
net movement for the period
.

---

