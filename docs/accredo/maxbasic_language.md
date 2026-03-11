# MaxBasic Language & Scripting

> Statements, operators, events, memory tables, input grids, data objects, script editor, debugging

**Sections:** 73

---

## Quick Reference

- [AddField - Memory Table Builder Method](#addfield---memory-table-builder-method)
- [AddIndex - Memory Table Method](#addindex---memory-table-method)
- [Append - Memory Table Method](#append---memory-table-method)
- [ApplyOrder - Memory Table Method](#applyorder---memory-table-method)
- [Automated Data Objects](#automated-data-objects)
- [Automated Form common Properties and Methods](#automated-form-common-properties-and-methods)
- [Automated Forms](#automated-forms)
- [Automated Reports](#automated-reports)
- [Cancel - Memory Table Method](#cancel---memory-table-method)
- [CancelRange - Memory Table Method](#cancelrange---memory-table-method)
- [Clear - Memory Table Builder Method](#clear---memory-table-builder-method)
- [ClearFields - Memory Table Builder Method](#clearfields---memory-table-builder-method)
- [ClearIndexes - Memory Table Builder Method](#clearindexes---memory-table-builder-method)
- [Clone - Memory Table Method](#clone---memory-table-method)
- [CloneField - Memory Table Builder Method](#clonefield---memory-table-builder-method)
- [Command Line Scripts](#command-line-scripts)
- [Command Line Scripts](#command-line-scripts)
- [CopyTable - Memory Table Method](#copytable---memory-table-method)
- [CreateDefaultEditors - Input Grid Method](#createdefaulteditors---input-grid-method)
- [CreateTable - Memory Table Builder Method](#createtable---memory-table-builder-method)
- [Delete - Memory Table Method](#delete---memory-table-method)
- [Edit - Memory Table Method](#edit---memory-table-method)
- [Empty - Memory Table Method](#empty---memory-table-method)
- [Find - Memory Table Method](#find---memory-table-method)
- [FindExact - Memory Table Method](#findexact---memory-table-method)
- [First - Memory Table Method](#first---memory-table-method)
- [Geocode Script Editor](#geocode-script-editor)
- [Geocode Script Editor Objects](#geocode-script-editor-objects)
- [GetFieldDomain - Memory Table Method](#getfielddomain---memory-table-method)
- [GetPropertyValue - Memory Table Builder Method](#getpropertyvalue---memory-table-builder-method)
- [GetPropertyValue - Memory Table Method](#getpropertyvalue---memory-table-method)
- [Input Button - Input Grid Method](#input-button---input-grid-method)
- [InputBoolean - Input Grid Method](#inputboolean---input-grid-method)
- [InputBox - Input Grid Method](#inputbox---input-grid-method)
- [InputCode - Input Grid Method](#inputcode---input-grid-method)
- [InputCustomCode - Input Grid Method](#inputcustomcode---input-grid-method)
- [InputDate - Input Grid Method](#inputdate---input-grid-method)
- [InputInteger - Input Grid Method](#inputinteger---input-grid-method)
- [InputList - Input Grid Method](#inputlist---input-grid-method)
- [InputNumber - Input Grid Method](#inputnumber---input-grid-method)
- [InputPeriod - Input Grid Method](#inputperiod---input-grid-method)
- [Insert - Memory Table Method](#insert---memory-table-method)
- [Last - Memory Table Method](#last---memory-table-method)
- [LoadFromCSV - Memory Table Method](#loadfromcsv---memory-table-method)
- [LoadFromExcel - Memory Table Method](#loadfromexcel---memory-table-method)
- [LoadFromFile - Memory Table Method](#loadfromfile---memory-table-method)
- [MaxBasic Date Operators](#maxbasic-date-operators)
- [MaxBasic Debugger](#maxbasic-debugger)
- [MaxBasic Operators](#maxbasic-operators)
- [MaxBasic String Operators](#maxbasic-string-operators)
- [MaxBasic Variables](#maxbasic-variables)
- [Next - Memory Table Method](#next---memory-table-method)
- [PP Script Editor](#pp-script-editor)
- [Prev - Memory Table Method](#prev---memory-table-method)
- [PropertyType - Memory Table Method](#propertytype---memory-table-method)
- [Refresh - Memory Table Method](#refresh---memory-table-method)
- [Save - Memory Table Method](#save---memory-table-method)
- [SaveToCSV - Memory Table Method](#savetocsv---memory-table-method)
- [SaveToExcel - Memory Table Method](#savetoexcel---memory-table-method)
- [SaveToFile - Memory Table Method](#savetofile---memory-table-method)
- [Script Editor](#script-editor)
- [Script Editor - Context Menu](#script-editor---context-menu)
- [Script Editor - Shortcut keys](#script-editor---shortcut-keys)
- [SetPropertyValue - Memory Table Method](#setpropertyvalue---memory-table-method)
- [SetRange - Memory Table Method](#setrange---memory-table-method)
- [SetRangeEnd - Memory Table Method](#setrangeend---memory-table-method)
- [SetRangeStart - Memory Table Method](#setrangestart---memory-table-method)
- [Sort - Memory Table Method](#sort---memory-table-method)
- [SP Script Editor](#sp-script-editor)
- [StartFormUpdates - Memory Table Method](#startformupdates---memory-table-method)
- [StopFormUpdates - Memory Table Method](#stopformupdates---memory-table-method)
- [SwapDown - Memory Table Method](#swapdown---memory-table-method)
- [SwapUp - Memory Table Method](#swapup---memory-table-method)

---

## AddField - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MBAddField_1.htm

AddField - Memory Table Builder Method
method
AddField(Name: String, Domain: String[, Type: String, Size: Number, Required: Boolean, CurrCodeFieldName: String]): Object
AddField method adds a new field to the table definition. Available for Memory Table Builder objects, Form Designer Memory Tables and Form Designer Graphs.
AddField method syntax has these named arguments:
Parameter
Description
Name
Required. Name of the field. Must be a valid
MaxBasic variable
.
Domain
Required. Pre-defined domain name for field.
Type
Optional Pre-defined type for field.
Size
Optional. Maximum size for string fields.
Required
Optional. Determines whether the field is required or optional in the table.
Curr Code Field Name
Optional. Name of CurrencyCode field.
See Also
Form Designer Graph Methods

---

## AddIndex - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBAddIndex_1.htm

AddIndex - Memory Table Method
method
AddIndex(Name: String, Fields: String[, Unique: Boolean, Descending: Boolean, CaseInsensitive: Boolean])
AddIndex method adds a new index to a Memory Table definition.
You can specify the index ordering by using +'s and -'s before each field to specify its sort order (+ is the default if nothing is specified). If the order is specified for the first field of the index only this ordering will apply to all parts of the index.
AddIndex method syntax has these named arguments:
Parameter
Description
Name
Required. Name for the index. Must be a valid MaxBasic identifier.
Fields
Required. List of fields to include in the index, each field separated by a semi-colon (;).
Unique
Optional. Ensure that no set of fields exists more than once in the index.
Descending
Optional. Sort the index in descending order.
Case Insensitive
Optional. Ignore case when sorting alphabetic characters.
For example:
tblTable.AddIndex("AreaCode", "-SalesArea;+CustCode", True)
See Also
Form Designer Table Methods

---

## Append - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBAppend_1.htm

Append - Memory Table Method
method
Append
Append methods appends a record to a Memory Table or Table, at the end of the table.
For example:
Table.Append
Table.CustomerCode = "ASHENG"
Table.TotalAmount = 15
Table.Save
Will add a line to the table
Table
.
See also the StringList Object
Append
method.
See Also
Form Designer Table Methods

---

## ApplyOrder - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBApplyOrder_1.htm

ApplyOrder - Memory Table Method
method
ApplyOrder(Order: Array of Variant)
The ApplyOrder method orders records in a Memory Table in order of the array supplied.
ApplyOrder method syntax has these named arguments:
Parameter
Description
Order
Required. An array of variants, specifying the order for records in the table.
For example, to reverse the line order for JC Job Estimates:
Dim JCData as Object
JCData = CreateObject("Accredo.JCJobData")
JCData.IndexName = "Job"
count = JCData.Estimate.RecordCount
dim lines[count] as Number
for line = 1 to UBound(lines)
lines[line] = count + 1 - line
next
JCData.Edit
JCData.Estimate.ApplyOrder(lines)
JCData.Save
See Also
Form Designer Table Methods

---

## Automated Data Objects

Source: https://accredo.co.nz/webhelp/AutomatedDataObjects.htm

Automated Data Objects
APAllocateTransactionsData
Variable Name: datAPAlloc
APBudgetData
APCategory1Data
Variable Name: datAPCat1
APCategory2Data
Variable Name: datAPCat2
APContactData
APCostCodeData
APCreditorData
Variable Name: datAPCred
APCreditorGroupData
APExpenseBudgetData
APExpenseData
Variable Name: datAPExp
APMemoData
APRevalueForeignBalancesData
Variable Name: datAPReval
APSHCategory1Data
Variable Name: datAPSHCat2
APSHCategory2Data
Variable Name: datAPSHCat2
APShipmentsData
Variable Name: datAPShipment
APTransactionData
Variable Name: datAPTran
ARAllocateTransactionsData
Variable Name: datARAlloc
ARBudgetData
ARCategory1Data
Variable Name: datARCat1
ARCategory2Data
Variable Name: datARCat2
ARContactData
ARCustomerData
Variable Name: datARCust
ARCustomerGroupData
ARMemoData
ARRevalueForeignBalancesData
Variable Name: datARReval
ARSalesAreaBudgetData
ARSalesAreaData
Variable Name: datARArea
ARSalesGroupBudgetData
ARSalesGroupData
Variable Name: datARAnl
ARSalesPersonBudgetData
ARSalesPersonData
Variable Name: datARPers
ARTransactionData
Variable Name: datARTran
BASReturnData
CBAnalysisBudgetData
CBAnalysisData
Variable Name: datCBAnl
CBAutomaticPaymentData
CBBankAccountData
Variable Name: datCBBank
CBBankingItemsData
CBBankingSummaryData
Variable Name: datCBSum
CBCategory1Data
Variable Name: datCBCat1
CBCategory2Data
Variable Name: datCBCat2
CBMemoData
CBRevalueForeignBalancesData
Variable Name: datCBReval
CBRuleData
CBStatementData
CBTransactionData
Variable Name: datCBTran
COAddressData
COBankingMediaData
COBranchData
COContactData
COCTCategory1Data
Variable Name: datCOCTCat1
COCTCategory2Data
Variable Name: datCOCTCat2
CODepartmentData
Variable Name: datCODept
CODiscountData
CODocDefaults
COFileUploadExtensionData
COFXCurrencyData
COFXCurrencyRateTypeData
COFXExchangeRateLimitsData
COFXExchangeRatesData
COLinkCategory1Data
Variable Name: datCOLKCat1
COLinkCategory2Data
Variable Name: datCOLKCat2
COMemoData
COMOCategory1Data
Variable Name: datCOMOCat1
COMOCategory2Data
Variable Name: datCOMOCat2
CONarrativeData
CORecoveryLogData
COScriptShortcutData
COTablesData
COTaxRegimeData
COTrackFieldData
COUserData
FAAssetBookData
FAAssetData
FAAssetGroupData
Variable Name: datFAGroup
FAAssetLocationData
Variable Name: datFALocn
FACategory1Data
Variable Name: datFACat1
FACategory2Data
Variable Name: datFACat2
FAChangeDepreciationData
FADepreciationDefaultsData
FAMemoData
FAOpeningValuesData
FATransactionData
Variable Name: datFATran
GenericReturnData
GLAccountData
Variable Name: datGLAcct
GLAccountReconciliationData
GLBatchData
GLBudgetCodeData
GLBudgetData
GLCategory1Data
Variable Name: datGLCat1
GLCategory2Data
Variable Name: datGLCat2
GLMemoData
GLSudsidiaryData
GLTransactionData
GSMemoData
GSTCodesData
GSTReturnData
GSTTransactionData
ICAdjustmentBatchData
ICBinCountData
ICBinData
ICBinMovementData
ICBudgetData
ICCategory1Data
Variable Name: datICCat1
ICCategory2Data
Variable Name: datICCat2
ICComponentData
ICGenerateStocktakeData
Variable Name: datICStocktake
ICLocationData
Variable Name: datICLocn
ICManufactureBatchData
ICManufactureData
ICMemoData
ICProductBinData
ICProductData
Variable Name: datICProd
ICReceiptBatchData
ICStockGroupData
Variable Name: datICGroup
ICStocktakeCountData
ICStocktakeData
ICStorePersonData
ICTransactionData
ICTransferData
ICUOMData
ICUOMGroupData
INCategory1Data
Variable Name: datINCat1
INCategory2Data
Variable Name: datINCat2
INInvoiceData
INMemoData
INShipperData
JCBatchData
JCBudgetData
JCCategory1Data
Variable Name: datJCCat1
JCCategory2Data
Variable Name: datJCCat2
JCComponentData
Variable Name: datJCComp
JCCostCentreData
Variable Name: datJCCost
JCDisbursementData
JCInvoiceAmountsData
JCJobData
Variable Name: datJCJob
JCJobGroupData
JCJobPersonData
JCMemoData
JCTimesheetData
JCTransactionData
Variable Name: datJCTran
OEMemoData
OEOrderData
POAuthorisationData
Variable Name: datPOAuth
POCategory1Data
Variable Name: datPOCat1
POCategory2Data
Variable Name: datPOCat2
POMemoData
POOrderData
PPEnquiryData
PPRuleData
PPWhatData
PPWhereData
PPWhoData
SPEnquiryData
SPRuleData
SPWhatData
SPWhereData
SPWhoData
SYUserData

---

## Automated Form common Properties and Methods

Source: https://accredo.co.nz/webhelp/AutomatedFormProperties.htm

Automated Form common Properties and Methods
Some common Properties and Methods available in Automated Forms are:
ActiveProperty
For Masterfile Maintenance forms that have a Code selection at the top, you can reset focus to the Code selection by using the
ActiveProperty
property as follows:
ActiveProperty=""

---

## Automated Forms

Source: https://accredo.co.nz/webhelp/AutomatedForms.htm

Automated Forms
AccredoMailer - Mail Editor
APAllocateTransactionsForm - AP Allocate Transactions
Variable Name: frmAPAlloc
APAllocationQueryForm - AP Allocation Query
APApprovalForm - AP Approve for Payment
APApproveForPaymentForm - AP Approve for Payment
APBatchEmailResultsForm - AP Batch Email Results
APBudgetForm - AP Creditor Budget
APCategories1GridForm -  AP Creditor Categories 1
Variable Name: frmAPCat1
APCategories2GridForm - AP Creditor Categories 2
Variable Name: frmAPCat2
APChangedOrderListForm - Order Lines Changed
APContactEditForm - AP Contacts
APContactListForm - AP Contact List
APCostCodeForm - AP Cost Code
APCreditorBatchEmailForm - AP Batch Email
APCreditorForm - AP Creditor
Variable Name: frmAPCred
APCreditorGroupForm - AP Creditor Group
APCreditorListForm - AP Creditor List
APElectronicForm - AP Electronic Payments
APEmailRemittanceResultsForm - AP Email Remittance Results
APEmailShipmentResultsForm - AP Email Shipment Results
APExpenseBudgetForm - AP Expense Budget
APExpenseCodeForm - AP Expense Code
Variable Name: frmAPExp
APExpenseCodeGridForm - AP Expense Code Grid
APGeneratedPaymentsForm - AP Generated Payments
APGenerateForm - AP Generate Payments
APGeneratePaymentsForm - AP Generate Payments
APHideTransactionsForm - AP Hide Transactions
Variable Name: frmAPInactivateTran
APLinkListForm - AP Link List
APMemoEditForm - AP Memo
APMemoListForm - AP Memo List
APRevalueForeignBalancesForm - AP Revalue Foreign Balances
Variable Name: frmAPReval
APRevalueForeignShipmentsForm - AP Revalue Foreign Shipments
APSettingsForm - AP Settings
APSHCategories1GridForm -  AP Shipment Categories 1
Variable Name: frmAPSHCat1
APSHCategories2GridForm - AP Shipment Categories 2
Variable Name: frmAPSHCat2
APShipmentEntryForm - AP Shipment
Variable Name: frmAPShipment
APShipmentListForm - AP Shipment List
APShipmentsRevalResultsForm - AP Revalue Foreign Shipments Results
APTrackingLog - AP Change Tracking Log
APTransactionForm - AP Transaction
Variable Name: frmAPTran
APTransactionListForm - AP Transaction List
ARAllocateTransactionsForm - AR Allocate Transactions
Variable Name: frmARAlloc
ARAllocationQueryForm - AR Allocation Query
ARBatchEmailResultsForm - AR Batch Email Results
ARBudgetForm - AR Customer Budget
ARCategories1GridForm -  AR Categories 1
Variable Name: frmARCat1
ARCategories2GridForm - AR Categories 2
Variable Name: frmARCat2
ARContactEditForm - AR Contacts
ARContactListForm - AR Contact List
ARCustomerBatchEmailForm - AR Batch Email
ARCustomerForm - AR Customer
Variable Name: frmARCust
ARCustomerGroupForm - AR Customer Group
ARCustomerListForm - AR Customer List
AREmailStatementResultsForm - AR Email Statement Results
ARGenerateOverdueInterest - AR Generate Overdue Interest
ARHideTransactionsForm - AR Hide Statement Transactions
Variable Name: frmARInactivateTran
ARLinkListForm - AR Link List
ARMemoEditForm - AR Memo
ARMemoListForm - AR Memo List
ARRevalueForeignBalancesForm - AR Revalue Foreign Balances
Variable Name: frmARReval
ARSalesAreaBudgetForm - AR Sales Area Budget
ARSalesAreaForm - AR Sales Area
Variable Name: frmARArea
ARSalesAreaGridForm - AR Sales Area Grid
ARSalesGroupBudgetForm - AR Sales Group Budget
ARSalesGroupForm - AR Sales Group
Variable Name: frmARAnl
ARSalesGroupGridForm - AR Sales Group Grid
ARSalesPersonBudgetForm - AR Sales Person Budget
ARSalesPersonForm - AR Sales Person
Variable Name: frmARPers
ARSalesPersonGridForm - AR Sales Person Grid
ARSettingsForm - AR Settings
ARTrackingLog - AR Change Tracking Log
ARTransactionForm - AR Transaction
Variable Name: fmARTran
ARTransactionListForm - AR Transaction List
CBAnalysisBudgetForm - CB Analysis Budget
CBAnalysisCodeForm - CB Analysis Code
Variable Name: frmCBAnl
CBAnalysisCodeGridForm - CB Analysis Code Grid
CBAutomaticPaymentForm - CB Automatic Payment
CBBankAccountForm - CB Bank Account
Variable Name: frmCBBank
CBBankAccountListForm - CB Bank Account List
CBBankingItemsEntryForm - CB Banking Item
CBBankingItemsListForm - CB Banking Items List
CBBankingSummaryForm - CB Banking Summary
Variable Name: frmCBSum
CBBankingSummaryListForm - CB Banking Summaries
CBCashFlowQueryForm - CB Cash Flow Query
CBCategories1GridForm - CB Categories 1
Variable Name: frmCBCat1
CBCategories2GridForm - CB Categories 2
Variable Name: frmCBCat2
CBEnterTransactionForm - CB Transaction
Variable Name: frmCBTran
CBEnterTransferForm - CB Transfer
CBExportElectronicPaymentsForm - CB Export Electronic Payments
CBLinkListForm - CB Link List
CBMemoEditForm - CB Memo
CBMemoListForm - CB Memo List
CBRevalueForeignBankAccountsForm - CB Revalue Foreign Bank Accounts
Variable Name: frmCBReval
CBRuleForm - CB Rules
CBRulesListForm - CB Rules List
CBSettingsForm - CB Settings
CBStatementEditForm - CB Bank Reconciliation
CBStatementListForm - CB Bank Statements
CBTrackingLog - CB Change Tracking Log
CBTransactionListForm - CB Transaction List
COAliasBinCodesForm - Alias Bin Codes
COAliasCodesForm - Alias Codes
COAliasDeliveryCodesForm - Alias Delivery Codes
COAliasMergeLog - CO Alias and Merge Log
COBankAccountChangeListForm - CO Bank Account Change List
COBankingMediaForm - Banking Media
COBatchEmailForm - CO Batch Email
COBatchEmailResultsForm - CO Batch Email Results
COBranchForm - Branch
COChangeTaxBasisForm - CO Change Tax Basis
COContactEditForm - CO Contacts Edit
COContactListForm - CO Contact List
COCtCategories1GridForm - CO Contact Categories 1
Variable Name: frmCOCtCat1
COCtCategories2GridForm - CO Contact Categories 2
Variable Name: frmCOCtCat2
CODecimalsForm - Decimals
CODeliveryAddressForm - Delivery Address
CODepartmentForm - Department
Variable Name: frmCODept
CODetailsForm - Company Details
CODisplay - Company Display
CODocDefaultsForm - Document Defaults
COFileUploadExtensionForm - CO File Upload Extension
COForexSettingsForm - FX Settings
COFXEnterRatesForm - FX Exchange Rates
COFXExchangeRatesForm - FX Exchange Rate
COLinkCategories1GridForm - CO Link Categories 1
Variable Name: frmCOLKCat1
COLinkCategories2GridForm - CO Link Categories 2
Variable Name: frmCOLKCat2
COLinkListForm - CO Link List
COLinkListForm - frmLinksOnList
COLinksList - Links on CO  - GLOBAL
COMailSettingsForm - Company Mail Settings
COMemoChangeUser - Change Memo Target User
COMemoEditForm - CO Memo
COMemoListForm - CO Memo List
COMergeBinCodesForm - Merge Bin Codes
COMergeCodesForm - Merge Codes
COMoCategories1GridForm - CO Memo Categories 1
Variable Name: frmCOMOCat1
COMoCategories2GridForm - CO Memo Categories 2
Variable Name: frmCOMOCat2
CONarrativeEdit - Global Narrative Editor
CONarrativeList - Global Narrative List
COOptimiseDatabaseForm - CO Optimise Tables
COPeriodForm - Periods
COPriceListForm - Price List
COPringLog - Print Log
COProvisioningEmailResultsForm - Provisioning Email Results
COPruneHistoryForm - CO Prune History
COPrunePrintLogForm - CO Prune Print Log
COPruneTrackingForm - CO Prune Tracking
COReportLayoutsForm - Report Layouts
COScriptEventForm - Script Events
COScriptShortcutEditForm - Script Shortcut Editor
COScriptShortcutForm - Shortcut List
COSettingsForm - Company Settings
COSettingsLog - CO Settings Log
COTaxRegimeForm - CO Tax Regime Settings
COTrackingForm - Change Tracking
COTrackingLog - CO Change Tracking Log
COUOMGroupsForm - IC UOM Group
COUserAccessTimesForm - User Access Times
COUserForm - CO Users, Groups and Roles
COYearForm - Years
CustomTableEditorForm - Custom Maintenance
EDIImport - EDI Importing
EDIPriceBookImport - EDI Price Book Import
FAAssetForm - FA Asset
FAAssetListForm - FA Asset List
FABookForm - FA Book
FACategories1GridForm - FA Categories 1
Variable Name: frmFACat1
FACategories2GridForm - FA Categories 2
Variable Name: frmFACat2
FAChangeDepreciationForm - FA Change Depreciation
FACopyDepreciationForm - Copy Depreciation
FADepreciationDefaultsBookForm - FA Depreciation Defaults - Book
FAGenerateDepreciationForm - FA Generate Depreciation
FAGroupForm - FA Asset Group
FALinkListForm - FA Link List
FALocationForm - FA Asset Location
Variable Name: frmFALocn
FAMemoEditForm - FA Memo
Variable Name: frmFAMemo
FAMemoListForm - FA Memo List
FAOpenBookForm - Open Book
FAOpeningValuesForm - FA Opening Asset Values
FAPreviewDepreciationForm - FA Preview Depreciation
FASettingsForm - FA Settings
FATrackingLog - FA Change Tracking Log
FATransactionForm - FA Transaction
Variable Name: frmFATran
FATransactionListForm - FA Transaction List
FXCurrenciesForm - FX Currency
FXExchangeRateLimitsForm - FX Exchange Rate Limits
FXRateTypesForm - FX Rate Type
GLAccountantExportForm - GL Export to Accountants System
GLAccountForm - GL Account
Variable Name: frmGLAcct
GLAccountListForm - GL Account List
GLAccountReconciliationForm - GL Account Reconciliation
Variable Name: frmGLAccountReconciliation
GLBatchEditForm - GL Transaction Batch
GLBatchExportForm - GL Export Transaction Batches
GLBatchImportForm - GL Import Batch
GLBatchTransactionForm - GL Transaction Batches
GLBatchTransactionForm - GL Transaction Batches
GLBudgetCodeForm - GL Budget Code
GLBudgetForm - GL Budget
GLCategories1GridForm - GL Categories 1
Variable Name: frmGLCat1
GLCategories2GridForm - GL Categories 2
Variable Name: frmGLCat2
GLCompareChartsOfAccountsData - GL Compare Charts of Accounts
GLCompareResultsForm - GL Chart of Account Comparison Results
GLCopyBudget - GL Budget Copy
GLImportSubsidiariesData - GL Import from Subsidiaries
GLLinkListForm - GL Link List
GLMemoEditForm - GL Memo
GLMemoListForm - GL Memo List
GLMYOBAOExportForm - GL Export to MYOB Accountants Office
GLReconciliationListForm - GL Reconciliation List
GLSettingsForm - GL Settings
GLSubsidiaryForm - GL Subsidiary Company Edit
GLTrackingLog - GL Change Tracking Log
GLTransactionListForm - GL Transaction List
GSLinkListForm - GST Link List
GSMemoEditForm - GST Memo
GSMemoListForm - GST Memo List
GSTEnterTransactionForm - GST Transaction
GSTReturnForm - GST Complete Return
GSTReturnListForm - GST Return List
GSTTransactionsListForm - GST Transaction List
ICAdjustmentBatchForm - IC Adjustment Batch
ICAdjustmentBatchListForm - IC Adjustment Batch List
ICAliasLotForm - Alias Lot Nos
ICAliasSerialForm - Alias Serial Nos
ICBinCodeForm - IC Bin - AKL
ICBinCountForm - IC Bin Count
ICBinCountListForm - IC Bin Count List
ICBinForm - IC Bin - AKL
ICBinLocnMatrixForm - IC Product Bins
ICBinLocnSelectionForm - IC Product Bins
ICBinMatrixForm - IC Product Bins
ICBinMovementForm - IC Bin Movement
ICBinMovementListForm - IC Bin Movement List
ICBinTrkQtyForm - IC Bin Tracking Quantities
ICBudgetForm - IC Product Budget
ICCategories1GridForm -  IC Categories 1
Variable Name: frmICCat1
ICCategories2GridForm -  IC Categories 2
Variable Name: frmICCat2
ICComponentForm - IC Component
ICComponentOfForm - 1.8MWARDROBE Component Of
ICCountEditForm - IC Stocktake Count
ICCountImport - IC Import Count
ICEditCountForm - IC Edit Count
ICEnterTransactionForm - IC Transaction
ICGenerateBinCountForm - IC Generate Bin Count
ICGenerateStocktakeForm - IC Generate Stocktake
ICGlobalPriceUpdateForm - IC Global Price Update
ICInsertCountForm - IC Insert Count
ICLinkListForm - IC Link List
ICLocationForm - IC Stock Location
ICManufactureBatchForm - IC Manufacture Batch
ICManufactureBatchListForm - IC Manufacture Batch List
ICMemoEditForm - IC Memo
Variable Name: frmICMemo
ICMemoListForm - IC Memo List
ICMergeLotForm - Merge Lot Nos
ICPriceListCopy - IC Price List Copy
ICProdTrkQueryForm - IC Product Tracking Query
ICProductBinForm - IC Product Bins
ICProductForm - IC Product
Variable Name: frmICProd
ICProductListForm - IC Product List
ICProductQtyForm - IC Product Quantities
ICProductTrkQtyForm - IC Product Tracking Quantities
ICRepriceFromComponentsForm - IC Reprice from Components
ICSettingsForm - IC Settings
ICStockGroupForm - IC Stock Group
Variable Name: frmICGroup
ICStocktakeEditForm - IC Stocktake
ICStocktakeListForm - IC Stocktake List
ICStocktakeMatrixForm - IC Basic Count - Enter Quantities -
ICStocktakeSingleForm - IC Single Count - Enter Quantities -
ICStockTransferForm - IC Stock Transfers
ICStorePersonForm - IC Store Person
Variable Name: frmICPerson
ICSupplierCostUpdate - IC Supplier Cost Update
ICTrackingLog - IC Change Tracking Log
ICTransactionListForm - IC TransactionList
ICTransferListForm - IC Transfer List
ICUnitsOfMeasureForm - IC Units of Measure
INCategories1GridForm -  IN Categories 1
Variable Name: frmINCat1
INCategories2GridForm - IN Categories 2
Variable Name: frmINCat2
INChargesForm - IN Charges
INEmailInvoiceResultsForm - IN Email Invoice Results
INInvoiceEntryForm - IN Invoice
INInvoiceListForm - IN Invoice List
INInvoiceRevalResultsForm - IN Revalue Foreign Invoices Results
INLinkListForm - IN Link List
INMemoEditForm - IN Memo
INMemoListForm - IN Memo List
INPostingResultsForm - IN Post Invoices Results
INPostInvoicesForm - IN Post Invoices
INRepriceInvoicesForm - IN Reprice Invoices
INRevalueForeignInvoicesForm - IN Revalue Foreign Invoices
INSettingsForm - IN Settings
INShipperForm - IN Shipper
INTrackingLog - IN Change Tracking Log
JCBatchTransactionEntryForm - JC Transaction Batch
JCBatchTransactionForm - JC Batch List
JCBudgetForm - JC Job Budget
JCCategories1GridForm -  JC Categories 1
Variable Name: frmJCCat1
JCCategories2GridForm - JC Categories 2
Variable Name: frmJCCat2
JCComponentGridForm - JC Component
Variable Name: frmJCComp
JCCostCentreGridForm - JC Cost Centre
Variable Name: frmJCCost
JCDisbursementForm - JC Disbursement Batch
JCEnterTransactionsForm - JC Transaction
Variable Name: frmJCTran
JCInvoiceAmountsForm - JC Job Invoicing
JCJobForm - JC Job
Variable Name: frmJCJob
JCJobGroupForm - JC Job Group
JCJobListForm - JC Job List
JCJobPersonForm - JC Job Person
Variable Name: frmJCPerson
JCLinkListForm - JC Link List
JCMemoEditForm - JC Memo
Variable Name: frmJCMemo
JCMemoListForm - JC Memo List
JCRepriceBatchesForm - JC Reprice Batches
JCRepriceEstimatesForm - JC Reprice Estimates
JCSettingsForm - JC Settings
JCShowInvoicesForm - JC Transaction Invoice Query
JCTimesheetTransactionEntryForm - JC Timesheet Batch
JCTrackingLog - JC Change Tracking Log
JCTransactionListForm - JC Transaction List
OECustomerBackOrdersForm - OE Customer Back Orders
OEFulfillBackOrdersForm - OE Fulfill Back Orders
OEFulfillResultsForm - OE Fulfill Back Orders Results
OEGenerateInvoicesForm - OE Generate Invoices
OEGenerateResultsForm - OE Generate Invoices Results
OELinkListForm - OE Link List
OEMemoEditForm - OE Memo
OEMemoListForm - OE Memo List
OEOrderRevalResultsForm - OE Revalue Foreign Orders Results
OERepriceSalesOrdersForm - OE Reprice Sales Orders
OERevalueForeignOrdersForm - OE Revalue Foreign Orders
OESalesOrderEntryForm - OE Order
OESalesOrderListForm - OE Sales Order List
OESettingsForm - OE Settings
OETrackingLog - OE Change Tracking Log
POAuthorMatrixForm - PO Authorisation Codes
Variable Name: frmPOAuth
POCategories1GridForm -  PO Categories 1
Variable Name: frmPOCat1
POCategories2GridForm - PO Categories 2
Variable Name: frmPOCat2
POLinkListForm - PO Link List
POMemoEditForm - PO Memo
POMemoListForm - PO Memo List
POOrderEmailResultsForm - PO Email Purchase Order Results
POOrderListForm - PO Order List
POOrderRevalResultsForm - PO Revalue Foreign Orders Results
POPurchaseOrderEntryForm - PO Order
PORepricePurchaseordersForm - PO Reprice Purchase Orders
PORevalueForeignOrdersForm - PO Revalue Foreign Orders
POSettingsForm - PO Settings
POTrackingLog - PO Change Tracking Log
POViewOrdersForm - AP View Orders
POViewShipmentsForm - frmPOViewShipments
PPInactivateRules - PP Inactivate Rules
PPQueryForm - PP Price Query
PPRuleBatchChange - PP Batch Update/Duplicate Rules
PPRuleEdit - PP Rule
PPRuleEditForm - PP Rule
PPRuleList - frmPPRuleList
PPRuleListForm - PP Rule List
PPSelectRuleForm - PP Select Rules
PPSettingsForm - PP Settings
PPTrackingLog - PP Change Tracking Log
PPWhatGridForm - PP What
PPWhereGridForm - PP Where
PPWhoGridForm - PP Who
SPInactivateRules - SP Inactivate Rules
SPQueryForm - SP Price Query
SPRuleBatchChange - SP Batch Update/Duplicate Rules
SPRuleEdit - SP Rule
SPRuleEditForm - SP Rule
SPRuleList - frmSPRuleList
SPRuleListForm - SP Rule List
SPSelectRuleForm - SP Select Rules
SPSettingsForm - SP Settings
SPTrackingLog - SP Change Tracking Log
SPWhatGridForm - SP What
SPWhereGridForm - SP Where
SPWhoGridForm - SP Who
SYAuditLog - SY Audit Log
SYImportCoUsersForm - Import CO Users to System
SYProvisioningSettingsForm - WS Client Provisioning Settings
SYPruneAuditLog - SY Prune Audit Log
SYSettingsForm - System Settings
SYTokenMaintenance - SY Email Token Maintenance
SYUserForm - SYS Users
SYUserListForm - SYS User List
SYUserSettingsLogForm - System Settings Log
SYWebServiceSettingsForm - WS Monitor Settings
TDCustomTablesForm - TD Table Register
TDTableDesignerForm - TD Table Designer
UTMemoList - Global Memos
UTMemoList - Memos

---

## Automated Reports

Source: https://accredo.co.nz/webhelp/AutomatedReports.htm

Automated Reports
AP Invalid Char Report - CO Invalid Chars
APAdditionalCostsReport - AP Additional Costs Report
APAgedBalancesReport - AP Aged Balances
APAgedTransactionsReport - AP Aged Transactions Report
APAllocationSequenceReport - AP Allocation Sequence
APAllocQueryReport - AP Allocation Query
APAllocScreenReport - AP Allocation
APApprovalReport - AP Approvals
APBudgetComparisonReport - AP Purchases Budget Comparison Report
APBudgetReport - AP Purchases Budget Report
APContactLinkReport - AP Contact Links
APContactReport - AP Contact Report
APCreditorBatchLabels - AP Creditor Batch Labels
APCreditorLabels - AP Creditor Labels
APCreditorLinkReport - AP Creditor Links
APCreditorReport - AP Creditor Report
APCreditorSheetReport - AP Creditor Sheets
APElectronicBankingReport - AP Electronic Payments
APEMailGeneratedRemittanceReport - AP Email Remittance Advices
APEMailRemittanceAdvicesReport - AP Email Remittance Advices
APEmailShipmentReport - AP Email Shipments
APExchangeVariationReport - AP Exchange Variation Report
APExchangeVariationSequenceReport - AP Exchange Variation Sequence Report
APExpenseBudgetComparisonReport - AP Expense Budget Comparison Report
APExpenseBudgetReport - AP Expense Budget Report
APExpenseComparisonReport - AP Expense Comparison Report
APExpenseDetailedReport - AP Expense Analysis Detail Report
APExpenseDissectionReport - AP Expense Analysis Sequence Report
APExpenseSummaryReport - AP Expense Analysis Report
APGenerateReport - AP Generate Payments
APGstAuditReport - AP GST Audit Report
APGSTCodeDetailedReport - AP GST Code Detailed Report
APGstDiscountsReport - AP GST Discounts Report
APGstPaymentsReport - AP GST Payments Report
APGstReconciliationReport - AP GST Payments Reconciliation Report
APLedgerTotalsReport - AP Ledger Totals
APMemoDesignedReport - AP Memos
APMemoExtraReport - AP Memo Report
APMemoReport - AP Memo Report
APPaymentDueReport - AP Payment Due Report
APPaymentDueTransactionsReport - AP Payment Due Transactions Report
APPrintShipmentsReport - AP Shipments
APPurchasesComparisonReport - AP Purchases Comparison Report
APRemittanceAdvicesReport - AP Remittance Advices
APRevaluationRatesReport - AP Revaluation Rates Report
APRevaluationReport - AP Revaluation Report
APShipmentLinkReport - AP Shipment Links
APShipmentReport - AP Shipment Report
APShipmentsReport - AP Shipment Status Report
APTranAllocatedReport - AP Allocated Transactions
APTranCredSequenceReport - AP Transaction List (Account Sequence)
APTransactionLinkReport - AP Transaction Links
APTranSequenceReport - AP Transaction List (Transaction Sequence)
APTranUnallocatedReport - AP Unallocated Transactions Report
APTranUntransferredReport - AP Untransferred Transactions
APUnallocatedPaymentsReport - AP GST Unallocated Payments Report
AR Invalid Char Report - AR Invalid Chars
ARAddressReport - AR Address
ARAgedBalancesDaysReport - AR Days Aged Balances
ARAgedBalancesMonthlyReport - AR Monthly Aged Balances
ARAgedBalancesReport - AR Aged Balances Sql Join
ARAgedTransactionsDaysReport - AR Aged Transactions Days
ARAgedTransactionsDueDateReport - AR Aged Transactions Days
ARAgedTransactionsMonthlyReport - AR Aged Transactions Monthly
ARAgedTransactionsReport - AR Aged Transactions Report
ARAllocationSequenceReport - AR Allocation Sequence
ARAllocQueryReport - AR Allocation Query
ARAllocScreenReport - AR Allocation
ARAreaBudgetComparisonReport - AR Sales Area Budget Comparison Report
ARAreaBudgetReport - AR Sales Area Budget Report
ARBudgetComparisonReport - AR Sales Budget Comparison Report
ARBudgetReport - AR Sales Budget Report
ARCommissionReport - AR Commission Report
ARContactLinkReport - AR Contact Links
ARContactReport - AR Contact Report
ARCustomerBatchLabels - AR Customer Batch Labels
ARCustomerLabels - AR Customer Labels
ARCustomerLinkReport - AR Customer Links
ARCustomerReport - AR Customer Report
ARCustomerSheetReport - AR Customer Sheets
AREMailStatementReport - AR Email Statements
ARExchangeVariationReport - AR Exchange Variation Report
ARExchangeVariationSequenceReport - AR Exchange Variation Sequence Report
ARGenerateOverdueInterestReport - AR Generate Overdue Interest
ARGroupBudgetComparisonReport - AR Sales Group Budget Comparison Report
ARGroupBudgetReport - AR Sales Group Budget Report
ARGstAuditReport - AR GST Audit Report
ARGSTCodeDetailedReport - AR GST Code Detailed Report
ARGstDiscountsReport - AR GST Discounts Report
ARGstPaymentsReport - AR GST Payments Report
ARGstReconciliationReport - AR GST Payments Reconciliation Report
ARLedgerTotalsReport - AR Ledger Totals
ARMemoDesignedReport - AR Memos
ARMemoExtraReport - AR Memo Report
ARMemoReport - AR Memo Report
ARPersBudgetReport - AR Sales Person Budget Report
ARPersonBudgetComparisonReport - AR Sales Person Budget Comparison Report
ARReceiptsDueReport - AR Receipts Due Report
ARReceiptsReport - AR Receipts
ARRevaluationRatesReport - AR Revaluation Rates Report
ARRevaluationReport - AR Revaluation Report
ARSalesAreaComparisonReport - AR Sales Area Comparison Report
ARSalesAreaSummaryReport - AR Sales Area Report
ARSalesComparisonReport - AR Sales Comparison Report
ARSalesGroupComparisonReport - AR Sales Group Comparison Report
ARSalesGroupDetailedReport - AR Sales Group Detail Report
ARSalesGroupDissectionReport - AR Sales Group Sequence Report
ARSalesGroupSummaryReport - AR Sales Group Report
ARSalesPersonComparisonReport - AR Sales Person Comparison Report
ARSalesPersonSummaryReport - AR Sales Person Report
ARStatementReport - AR Statements
ARTranAllocatedReport - AR Allocated Transactions
ARTranCustSequenceReport - AR Transaction List (Account Sequence)
ARTransactionLinkReport - AR Transaction Links
ARTranSequenceReport - AR Transaction List (Transaction Sequence)
ARTranUnallocatedReport - AR Unallocated Transactions Report
ARTranUntransferredReport - AR Untransferred Transactions
ARUnallocatedReceiptsReport - AR GST Unallocated Receipts Report
CBAnalysisCodesBudgetComparisonReport - CB Analysis Codes Budget Comparison Report
CBAnalysisCodesBudgetReport - CB Analysis Codes Budget Report
CBAnalysisDetailedReport - CB Analysis Report (with Transaction Detail)
CBAnalysisSequenceReport - CB Analysis Sequence Report
CBAnalysisSummaryReport - CB Analysis Report (Summarised)
CBAutomaticPaymentsReport - CB Automatic Payments Report
CBBalanceReport - CB Bank Account Balances
CBBankAccountLinkReport - CB Bank Account Links
CBBankingItemsReport - CB Banking Items
CBBankingSummaryBankReport - CB Banking Summary (Bank Copy)
CBBankingSummaryOfficeReport - CB Banking Summary (Office Copy)
CBBankReport - CB Bank Account Report
CBCashAnalysisSequenceReport - CB Cash Analysis Sequence
CBCashFlowBudget - CB Cash Flow Period and Year to Date
CBCashFlowByAccountClassReport - CB Cash Flow Cross Tab
CBCashFlowReport - CB Cash Flow Cross Tab
CBCashFlowYTDReport - CB Cash Flow Period and Year to Date
CBExchangeVariationReport - CB Exchange Variation Report
CBExchangeVariationSequenceReport - CB Exchange Variation Sequence Report
CBExpenseComparisonReport - CB Expense Comparison Report
CBExpenseDetailedReport - CB Expense Analysis Report (with Transaction Detail)
CBExpenseSummaryReport - CB Expense Analysis Report (Summarised)
CBGstAuditReport - CB GST Audit Report
CBGSTCodeDetailedReport - CB GST Code Detailed Report
CBIncomeComparisonReport - CB Income Comparison Report
CBIncomeDetailedReport - CB Income Analysis Report (with Transaction Detail)
CBIncomeSummaryReport - CB Income Analysis Report (Summarised)
CBMemoDesignedReport - CB Memos
CBMemoExtraReport - CB Memo Report
CBMemoReport - CB Memo Report
CBReconciliationReport - CB Reconciliation Report
CBReconciliationStatementReport - CB Reconciliation Report for Statement
CBRevaluationRatesReport - CB Revaluation Rates Report
CBRevaluationReport - CB Revaluation Report
CBSummaryReport - CB Summary
CBTranAccountSequenceReport - CB Transaction List (Account Sequence)
CBTransactionLinkReport - CB Transaction Links
CBTranSequenceReport - CB Transaction List (Transaction Sequence)
CBTranStatementReport - CB Bank Statement
CBTranUnreconciledReport - CB Unreconciled Transactions List
CBTranUntransferredReport - CB Untransferred Transactions
CBUnbankedItemsReport - CB Unbanked Items Report
CBUnmatchedStatementReport - CB Unmatched for Bank Statement
CBUnrecStatementReport - CB Unreconciled Transactions for Statement
CO Invalid Char Report - CO Invalid Chars
COBankAccountChangesReport - CO Bank Account Change
COCompanyContactReport - CO Contact Report
COMemoDesignedReport - CO Memos
COMemoExtraReport - CO Memo Report
COMemoReport - CO Memo Report
COPhoneListReport - CO Phone List Report
COTrackingLog - CO Tracking Log
COUserExtraReport - CO User Report
COUserReport - CO User Report
EDIExportReport - EDI Exporting
FAActivityDetail - FA Detail Activity Schedule
FAAssetActivity - FA Activity Schedule
FAAssetBatchLabels - FA Asset Batch Labels
FAAssetLabels - FA Asset Labels
FAAssetLinkReport - FA Asset Links
FAAssetReport - FA Asset Report
FAAssetSchedule - FA Depreciation Schedule
FAAssetValues - FA Asset Values
FABookComparison - FA Book Comparison
FABookComparisonDetail - FA Detail Book Comparison
FADefaultDepnApplyBook - FA Apply Default Depreciation -
FADefaultDepnApplyGroup - FA Apply Default Depreciation -
FADepnScheduleDetail - FA Detail Depreciation Schedule
FAGeneratedDepreciationReport - FA Generated Depreciation
FAGenerateReport - FA Generated Depreciation
FAMemoDesignedReport - FA Memos
FAMemoExtraReport - FA Memo Report
FAMemoReport - FA Memo Report
FAPreviewedDepreciationReport - FA Previewed Depreciation
FATranAccountSequenceReport - FA Transaction List (Account Sequence)
FATransactionLinkReport - FA Transaction Links
FATranSequenceDetailReport - FA Transaction List (Transaction Sequence Detail)
FATranSequenceReport - FA Transaction List (Transaction Sequence)
FATranUntransferredReport - FA Untransferred Transactions
FEExportReport - FE File Exporting
FRErrorReport - CO Recovery Log Report
FXExchangeRatesReport - FX Exchange Rate Report
GLAccountLinkReport - GL Account Links
GLAccountReconciliation - GL No title
GLBatchLinkReport - GL Batch Links
GLBatchSequenceReport - GL Batch Sequence
GLBudgetCopyReport - GL Budget Changes
GLBudgetDetailReport - GL Budget Detail Report
GLBudgetReport - GL Budget Report
GLChartOfAccountsReport - GL Chart of Accounts
GLDesignedReport - GL Financial Report
GLLedgerReconciliationReport - GL Ledger Reconciliation
GLMemoDesignedReport - GL Memos
GLMemoExtraReport - GL Memo Report
GLMemoReport - GL Memo Report
GLMYOBAOExportReport - GL MYOB Accounts Office Export
GLSubsidiaryReport - GL Import from Subsidiary
GLTranAccountSequenceDetailReport - GL Transaction List (Account Sequence Detailed)
GLTranAccountSequenceReport - GL Transaction List (Account Sequence)
GLTranBatchesExtraReport - GL Transaction Batch Report
GLTranBatchesReport - GL Transaction Batch Report
GLTranSequenceReport - GL Transaction List (Transaction Sequence)
GLTrialBalanceDetailReport - GL Trial Balance Detailed
GLTrialBalanceReport - GL Trial Balance
GSTCodeDetailedReport - GST Code Detailed Report
GSTDetailedReport - GST Detailed Report
GSTDiscounts - GST Discount
GSTMemoDesignedReport - GST Memos
GSTReconcilationReport - GST Basis Reconcilation
GSTTranPeriodReport - GST Transaction Period
GSTTranSequenceReport - GST Transaction List (Transaction Sequence)
GSTUnreportedTransactionsReport - GST Unreported Transactions
IC Invalid Char Report - IC Invalid Chars
ICAdjustmentBatchReport - IC Adjustment Batch Report
ICBatchAdjustmentReport - IC Batch Adjustments
ICBatchReceiptReport - IC Transaction Batch
ICBatchReceiptReport - IC Batch Receipts
ICBatchTransferReport - IC Stock Transfers
ICBinBatchLabelBases - IC Bin Batch Labels
ICBinByProductTrackingReport - IC Bin By Product
ICBinCountReport - IC Bin Count Report
ICBinLabels - IC Bin Labels
ICBinMovementReport - IC Bin Movement Report
ICBudgetReport - IC Sales Budget Report
ICComponentMaintenanceReport - IC Component Maintenance Report
ICComponentOfReport - IC Components Of Report
ICComponentReport - IC Components Report
ICCycleCheckReport - IC Invalid Components Report
ICGroupComparisonReport - IC Stock Group Comparison Report
ICGroupSalesAndValuationReport - IC Group Sales and Valuation Report
ICLocationBalancesReport - IC Location Balances Report
ICLocationQuantities - IC Location Quantities
ICManufactureBatchReport - IC Manufacture Batch Report
ICManufactureReport - IC Manufacture Report
ICManufactureSheetReport - IC Manufacture Sheets
ICMemoDesignedReport - IC Memos
ICMemoExtraReport - IC Memo Report
ICMemoReport - IC Memo Report
ICPendingStockMotionReport - IC Pending Stock Motion
ICPriceChangeReport - IC Price Changes
ICPriceCodeListReport - IC Price Code List
ICPriceListCopyReport - IC Price Changes
ICPriceListReport - IC Price List
ICPrintCountsReport - IC Count Sheets
ICPrintTransfersReport - IC Transfers
ICProductBalancesReport - IC Product Balances Report
ICProductBarCodeReport - IC Product Bar Code Report
ICProductBatchLabels - IC Product Batch Labels
ICProductByBinTrackingReport - IC Product By Bin
ICProductLabels - IC Product Labels
ICProductLinkReport - IC Product Links
ICProductLocationDetailReport - IC Product and Location Detail Report
ICProductLocationReport - IC Product by Locations
ICProductNoActivityReport - IC No Activity
ICProductReport - IC Product Report
ICProductSheetReport - IC Product Sheets
ICProductTrackingReport - IC Product Tracking Report
ICProductUnspecifiedReport - IC Tracked Serial Not Specified Report
ICReceiptBatchReport - IC Receipt Batch Report
ICSalesAndUsageReport - IC Sales and Usage Report
ICSalesAndValuationReport - IC Stock Sales and Valuation Report
ICSalesBudgetComparisonReport - IC Sales Budget Comparison Report
ICSalesComparisonReport - IC Sales Comparison Report
ICStocktakeFormsReport - IC Stocktake Forms
ICStocktakeReport - IC No title
ICStocktakeStatusReport - IC Stocktake Status
ICSupplierPriceListReport - IC Supplier Price List
ICThirteenPeriodSalesReport - IC Thirteen Period Sales Report
ICTrackingTransactionDetailReport - IC Tracking Transaction Detail
ICTranCrossBranchSalesReport - IC Cross Branch Sales List
ICTranProductSequenceReport - IC Transaction List (Product Sequence)
ICTransactionLinkReport - IC Transaction Links
ICTranSequenceReport - IC Transaction List (Transaction Sequence)
ICTransferLinkReport - IC Transfer Links
ICTransferReport - IC Transfer Report
ICTranUntransferredReport - IC Untransferred Transactions
ICUomQuantitiesReport - IC UOM Quantities Report
ICUomReport - IC UOM Report
INAllocationReport - IN Allocation Report
INDocumentLinkReport - IN Invoice Links
INEMailInvoiceReport - IN Email Invoices
INEMailPrintedInvoiceReport - IN Email Printed Invoices
INInvoiceLabels - IN Invoice Labels
INInvoiceReport - IN Invoice Report
INInvoiceStatusReport - IN Invoice Status Report
INInvoiceTotalsReport - IN Invoice Totals
INMemoDesignedReport - IN Memos
INMemoExtraReport - IN Memo Report
INMemoReport - IN Memo Report
INPickingReport - IN Invoice Picking Report
INPrintCashInvoiceReport - IN Invoices
INPrintInvoiceReport - IN Invoices
INPrintPackingSlipReport - IN Packing Slip
INPrintQuoteReport - IN Quotes
INRepriceReport - IN Invoice Reprice Report
INReprintInvoicesReport - IN Reprint Invoices
INShippingReport - IN Shipping
JC Invalid Char Report - CO Invalid Chars
JCBalancesReport - JC Job Balances
JCBatchLinkReport - JC Batch Links
JCBatchReport - JC Batch Report
JCBudgetComparisonReport - JC Job Budgets Comparison Report
JCBudgetReport - JC Job Budget Report
JCDisbursementReport - JC Batch Disbursement Report
JCInvoiceAmounts - JC Invoice Amounts
JCJobAndEstiReport - JC Job and Estimates Report
JCJobBatchLabels - JC Job Batch Labels
JCJobEstiReport - JC Job Estimates Report
JCJobLabels - JC Job Labels
JCJobLinkReport - JC Job Links
JCJobReport - JC Job Report
JCJobSheetReport - JC Job Sheets
JCJobStatusReport - JC Job Status
JCMemoDesignedReport - JC Memos
JCMemoExtraReport - JC Memo Report
JCMemoReport - JC Memo Report
JCQuoteReport - JC Job Quotations
JCRepriceBatchesReport - JC Batches Reprice Report
JCRepriceReport - JC Estimates Reprice Report
JCTimeSheetReport - JC Batch Timesheet Report
JCTranJobInvoiceDetailReport - JC Job Invoice Detail
JCTranJobInvoicesReport - JC Job Invoices
JCTranJobSequenceReport - JC Transaction List (Job Sequence)
JCTransactionLinkReport - JC Transaction Links
JCTranSequenceReport - JC Transaction List (Transaction Sequence)
JCUnpostedTranReport - JC Unposted Transaction List
JCWIPDetailReport - JC Work In Progress Detail
JCWIPReport - JC Work In Progress
JCWipTranType - JC Work In Progress by Transaction Type
OEAllocationReport - OE Allocation Report
OEBackOrdersReport - OE Back Order Report
OEConfirmationReport - OE Confirmations
OEEMailConfirmationReport - OE Email Confirmations
OEMemoDesignedReport - OE Memos
OEMemoExtraReport - OE Memo Report
OEMemoReport - OE Memo Report
OEOrderLabels - OE Order Labels
OEOrderLinkReport - OE Order Links
OEOrderReport - OE Order Report
OEOrderStatusReport - OE Order Status Report
OEPackingSlipReport - OE Packing Slips
OEPickingReport - IN Invoice Picking Report
OERepriceReport - OE Order Reprice Report
OEShippingReport - OE Shipping
POEmailOrdersReport - PO Email Purchase Orders
POGenerate - PO Generate
POLineVariationReport - PO Line Variation Report
POMemoDesignedReport - PO Memos
POMemoExtraReport - PO Memo Report
POMemoReport - PO Memo Report
POOrderLabels - PO Order Labels
POOrderLinkReport - PO Order Links
POOrderReport - PO Order Report
POOrderStatusReport - PO Order Status Report
POOrderTotalsReport - PO Order Totals Report
POOrderVariationReport - PO Variation Report
POPrintPurchaseOrderReport - PO Purchase Orders
POPrintQuotationRequestsReport - PO Quotation Requests
PORepriceReport - PO Purchase Order Reprice Report
POStockOnOrderReport - PO Stock On Order Report
PPRuleEditReport - PP Rule Maintenance
PPRuleListReport - PP Rule List
RecoveryStatusReport - CO Recovery Status Report
SPRuleEditReport - SP Rule Maintenance
SPRuleListReport - SP Rule List
TDCustomisationReport - TD Table Customisation Report
TDDataDictionaryReport - TD Data Dictionary Report
UTCustomReport -  Custom Report
UTDiscountScheduleReport - CO Discount Schedule
UTFileStatisticsReport - CO File Statistics
UTGridListReport -  Grid List Report
UTMemoExtraReport - CO Memo Report
UTMemoReport - CO Memo Report
UTNarrativeReport - CO Narrative Report
UTScriptShortcutsReport - CO Script Shortcuts

---

## Cancel - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBCancel.htm

Cancel - Memory Table Method
method
Cancel
Cancel method cancels any changes in a Memory Table or Table not saved.
For example:
tblMemoryTable1.Cancel
See Also
Memory Tables

---

## CancelRange - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBCancelRange_2.htm

CancelRange - Memory Table Method
method
CancelRange
CancelRange method cancels the range that has been set. Available for Data Combos, Surrogate Data Combos, Period Lookup Combos, Memory Tables and Tables.
For example:
tblTable1.CancelRange
See Also
Form Designer Table Methods

---

## Clear - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MBClear.htm

Clear - Memory Table Builder Method
method
Clear
This clears all fields and index definitions.
See Also
MemoryTableBuilder Object

---

## ClearFields - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MBClearFields.htm

ClearFields - Memory Table Builder Method
method
ClearFields
This clears all field definitions.
For example:
tblMemoryTable1.ClearFields
See Also
MemoryTableBuilder Object

---

## ClearIndexes - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MBClearIndexes.htm

ClearIndexes - Memory Table Builder Method
method
ClearIndexes
This clears all index definitions.
See Also
MemoryTableBuilder Object

---

## Clone - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBClone.htm

Clone - Memory Table Method
method
Clone (Table: Object)
Clone method creates a clone of another table by copying the field and index definitions, and linking to the original table. Any changes to the original table will apply to the cloned table. Use the
Refresh
method to refresh the Clone table after changes are made.
Clone method can be used for Memory Tables and for Tables in Form Designer.
Clone method syntax has these named arguments:
Parameter
Description
Table
Required. The table to be cloned.
Note: To Copy a memory table without linking to the original table, use the CopyTable method.
For example:
Dim NewTable as Object
NewTable = ExistingTable.Clone
See Also
Memory Tables

---

## CloneField - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MBCloneField.htm

CloneField - Memory Table Builder Method
method
CloneField(Table: Object, SourceFieldName: String[, DestinationFieldName: String]): Object
This copies a specified field from another table. If DestinationFieldName is not specified then SourceFieldName is used.
CloneField method syntax has these named arguments:
Parameter
Description
Table
Required. The table containing the field to be cloned.
Source Field Name
Required. The field to be cloned.
Destination Field Name
Optional. The name of the field to clone the Source Field to. If not provided, Source Field Name is used.
See Also
MemoryTableBuilder Object

---

## Command Line Scripts

Source: https://accredo.co.nz/webhelp/CommandLineScripts.htm

Command Line Scripts
This example shows you how to setup a script to logon to Accredo, perform an operation (such as an EDI export, import or both), and log out again. This example logs in as the Accredo user, exports a contact list using File Exporting and logs out.
If not Login("ABC Holdings", "ACCREDO", "ACCREDO") then Error "Login failed"
Dim Form1 as Object
Form1 = CreateObject("Accredo.FEExportReport")
Form1.Load("ContactList.pfa")
Form1.Run
Form1 = Nothing
If not Logout Then Error "Logout failed"
Save the above script as
ContactList.pfs
.
To run the script as a command line script, use the following command line:
AccredoSaturn.exe /s ContactList.pfs
The output from the Print statement (if any) will be sent to the null device.
If you want to capture the output from the script, use:
AccredoSaturn.exe /s ContactList.pfs > ContactLog.txt
Any Print statements or exceptions when running a command line script are sent to the standard output (StdOut) so that users can use AccredoSaturn for command line extraction of information, and to debug scripts to see what they are doing.

---

## Command Line Scripts

Source: https://accredo.co.nz/webhelp/MBScriptsCommandLine.htm

Command Line Scripts
In addition to
script shortcuts
and
script events
, you can run Accredo
scripts
from the command line. This is useful for initial processing to occur on startup or for driving Accredo from third party applications.
For example, to run
ScriptName.pfs
, the syntax used could be:
Accredo.exe [/m] /s ScriptName.pfs OutputFile.txt
Parameter
Description and Use
/m
Minimises the application so processing is done without visual feedback. This only works for scripts that do not involve form manipulation. It is useful when dealing with data objects to perform imports or exports of data from the system, where no visual feedback is required.
/s
Specifies the name of the script to execute, then closes the application. The script is located relative to the Scripts directory under the system path (AccredoSaturn or AccredoMercury) unless a fully specified path is used.
/o
Specifies the name of the script to execute, leaving the application open. The script is located relative to the scripts directory under the System path (AccredoSaturn or AccredoMercury) unless a fully specified path is used.
OutputFile.txt
(Optional) Script output will be sent to the standard output unless the output file is specified.
Command Line Syntax
For example:
Accredo.exe /s FilePath/FileName.pfs Output.txt
This will produce output in the file specified. Windows does not support output redirection in Explorer shortcuts so the alternative syntax is used.
Explorer Shortcut Syntax
For example:
Accredo.exe /s FileName.pfs Output.txt
/a
(Optional) Output will be appended to output.txt rather than overwriting, which is the default.
/X n
Sets a forced exit after a specified amount of time. The script will exit after
n
minutes (where
n
is a positive integer). This is only valid for command line scripts. A stack trace will be captured into the diag.log if the forced exit is triggered.
For example, to force exit after ten minutes:
Accredo.exe /s FileName.pfs /X 10
/LOCKTIMEOUT
LockTimeOut sets the number of milliseconds that the application will wait to obtain a lock. This can avoid global deadlocks for records.
See
Command Line and Config File Switches
for a full list of switches available.
Script Log location
In the Properties for Windows Shortcuts, there is a
Start in:
field. The Script Log will be located in the path specified in the
Start In:
field.
See also
Guarded File
.
Log in
When a command line script starts to execute, if you are not logged into a Company, you must login to the Company as a User before Accredo objects are created (see
Login function
). Once logged in, the script will be in the same environment as if you had logged in manually via the User interface. Once script processing is complete, you can use the
Logout function
(not mandatory).
Sample Command Line Script
const CompanyCode = "DEMO"
const UserCode = "ACCREDOUSER"
const Password = "USERPASSWORD"
If not Login(CompanyCode, UserCode, Password) then Error "Login failed"
' play script here
If not Logout Then Error "Logout failed"

---

## CopyTable - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBCopyTable.htm

CopyTable - Memory Table Method
method
CopyTable (Table: Object)
CopyTable method copies the field and index definitions from another table. CopyTable method can be used for Memory Tables.
CopyTable method syntax has these named arguments:
Parameter
Description
Table
Required. The table to be cloned.
For example:
Dim NewTable as Object
NewTable = ExistingTable.CopyTable
See Also
Memory Tables

---

## CreateDefaultEditors - Input Grid Method

Source: https://accredo.co.nz/webhelp/MBCreateDefaultEditors_1.htm

CreateDefaultEditors - Input Grid Method
method
CreateDefaultEditors
Create default editors for each read-write field in the table, based on the field types as defined in the table.
See Also
Form Designer Component Methods

---

## CreateTable - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MBCreateTable.htm

CreateTable - Memory Table Builder Method
method
CreateTable: Object
This creates a new memory table object with the definitions in this MemoryTableBuilder object.
See Also
MemoryTableBuilder Object

---

## Delete - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBDelete_1.htm

Delete - Memory Table Method
method
Delete
Deletes the current line of the Memory Table or Table.
For example:
tblMemoryTable1.Delete
will delete the current row from tblMemoryTable1.
See also StringList Object
Delete
method.
See Also
Form Designer Table Methods

---

## Edit - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBEdit_1.htm

Edit - Memory Table Method
method
Edit
Edit method makes the Memory Table or Table available for editing.
For example:
tblMemoryTable1.Edit
See Also
Form Designer Table Methods

---

## Empty - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBEmpty.htm

Empty - Memory Table Method
method
Empty
Empty method empties all data from a Memory Table.
For example:
tblMemoryTable1.Empty
See Also
Memory Tables

---

## Find - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBFind_1.htm

Find - Memory Table Method
method
Find (Value1: Variant[, Value2: Variant, Value 3: Variant, Value4: Variant]): Boolean
Find method finds a record in the Memory Table or Table closest matching to Values 1 - 4. Returns
True
if a matching record is found, or
False
if no record is found.
Find method syntax has these named arguments:
Parameter
Description
Value 1
Required. The first value to search the table for.
Value 2, Value 3, Value 4
Optional. Additional values to search the table for.
Note: Use Find to find the closest match, and use
FindExact
to find an exact match.
See Also
Form Designer Table Methods

---

## FindExact - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBFindExact.htm

FindExact - Memory Table Method
method
FindExact (Value1: Variant[, Value2: Variant, Value 3: Variant, Value4: Variant]): Boolean
FindExact method finds a record in a Memory Table or Table exactly matching to Values 1 - 4. Returns True if a matching record is found, or false if no record is found.
FindExact method syntax has these named arguments:
Parameter
Description
Value 1
Required. The first value to search the table for.
Value 2, Value 3, Value 4
Optional. Additional values to search the table for.
Note: Use FindExact to find an exact match, and use
Find
to find the closest match.
See Also
Memory Tables

---

## First - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBFirst_1.htm

First - Memory Table Method
method
First
First method goes to the first record in a Memory Table or Table.
For example:
tblMemoryTable1.First
See Also
Form Designer Table Methods

---

## Geocode Script Editor

Source: https://accredo.co.nz/webhelp/COGeoScriptEditor.htm

Geocode Script Editor
Navigator > Setup > Company > Scripts > Geocode Script Editor
Use the Geocode Script Editor to edit Geocode scripts, such as scripts for the Company.OnMap and Company.OnGeoCode
script events
.
The Geocode Script Editor includes the Context object, available under the Objects menu, which contains properties for the context in which the script is triggered to return latitude and longitude. The Context object may be documented from the Automated menu, select
Automated > Context > Document Context
.
Enter
MaxBasic
code, or the value of an expression property, or select an item from a menu to insert in Code Editor at the pointer position. You can construct statements and expressions. Code Editor in Report Designer is a modal window. The code "belongs" to the band property or the expression being edited.
See also
Script Editor
and
Script Editor Shortcut Keys
. To access the Code Editor
Context Menu
, right-click in the script editor window, or press
Shift+F10
. You can insert Automated code snippets in the Code Editor, see
Automated Snippets
.
Sample Geocode Scripts are available in the
AccredoDirectory
\Scripts\COGeocodeContext
directory. You can use these as a starting point for developing Geocode scripts.
Drop down menus
Operators
(Alt+O)
Lists
MaxBasic operators
.
Objects
(Alt+J)
Lists the
objects
and components available from the code. Components placed in the report will appear here. When you select a property it will appear in the code. The Context object is specific to the Geocode Script Editor.
Functions
(Alt+F)
Lists the
functions
available. When you select a function that expects arguments, parentheses and commas for the arguments are shown with the pointer at the first argument, for example,
InStr(|, )
Help for a function, detailing the arguments, is available from the final option in the menu, or by pressing
F1
or selecting from the context menu (right click) with the cursor positioned in the function name in the editor.
Components
(Alt+C)
Lists properties of the
components
available.
Automated
(Alt+A)
Lists
Automated
objects. Documentation for an object is available from the final option in the menu.
Procedures
(Alt+E)
Lists
Function
and
Sub
procedures  imported into, the script. Use
Ctrl+E
to open the
Procedure List
in a separate window.
Help
(Alt+H)
Access resources including descriptions, documentation and sample code.
Snippet
(Alt+T)
Insert a code
Snippet
. Snippets are listed alphabetically, and the first line of each snippet is displayed.
Editor buttons
Check Code
(Alt+C)
Checks the code compiles correctly, without running the script.
Set/Clear Breakpoint
(Alt+B)
Set a code
breakpoint
on the current line. Click again to toggle to clear the breakpoint. You can also click to the right of a line to set or clear a breakpoint.
Hover the mouse over a breakpoint, then right-click to make a breakpoint unavailable, or access the
Breakpoint Properties
.
If a condition has been set for a breakpoint, it will be shown when you hover over the breakpoint.
Print
(Ctrl+P)
Print the code. This can be helpful when writing scripts.
Capture Status Hints
Selected
, you can capture status hints when the script is Run. This is useful for checking the effect of a script.
Add Shortcut
(Alt+D)
Select to:
Add Shortcut
- add the script as a
Shortcut
on the Accredo toolbar and / or  the Navigator
Add Script Event
- attach the script to a
Script Event
View Script Events
- view all
Script Events.
This can be useful for ascertaining whether a script event already exists.
Check and Save
(Alt+K)
Check the code compiles correctly then save the script.
Load...
(Alt+L)
Load an existing script to select the code, run, print or edit.
Save...
(Ctrl+S)
Once saved, you can
run the script
, or setup a
script shortcut
or
script event
.
In This Section
Geocode Script Editor Objects

---

## Geocode Script Editor Objects

Source: https://accredo.co.nz/webhelp/GeocodeScriptEditorObjects.htm

Geocode Script Editor Objects
Navigator > Setup > Company > Scripts > Geocode Script Editor >
Objects
button
You can use standard MaxBasic
objects
.
Some of the objects available in Geocode Script Editor include:
Company
Details of the Company including the Company name and address.
Context
Details of the Context, including the address, latitude and longitude.
System
System details including the session type.
System User
Values for the current System User including User name and Settings.
User
Values for the current Company User including User name and Settings.

---

## GetFieldDomain - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBGetFieldDomain.htm

GetFieldDomain - Memory Table Method
method
GetFieldDomain(FieldName: String): String
GetFieldDomain method returns the domain of a field named in FieldName in a Memory Table or Table.
GetFieldDomain method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field in a table to return the domain for.
For example:
tblTable1.GetFieldDomain("CustomerCode")
will return the Domain of field CustomerCode.
See Also
Memory Tables

---

## GetPropertyValue - Memory Table Builder Method

Source: https://accredo.co.nz/webhelp/MTBGetPropertyValue.htm

GetPropertyValue - Memory Table Builder Method
method
GetPropertyValue(PropertyName: String): Variant
GetPropertyValue method returns the value of the property or MaxBasic variable named in PropertyName.
GetPropertyValue method syntax has these named arguments:
Parameter
Description
Property Name
Required. Name of the Property to return the value for.
For example:
btnButton1.GetPropertyValue("Caption")
will return the Caption of button component btnButton1.
See also the MaxBasic Script Function
GetPropertyValue
and the Scripted Form
GetPropertyValue
method and the Memory Table
GetPropertyValue
method..
See Also
MemoryTableBuilder Object

---

## GetPropertyValue - Memory Table Method

Source: https://accredo.co.nz/webhelp/MTGetPropertyValue.htm

GetPropertyValue - Memory Table Method
method
GetPropertyValue(PropertyName: String): Variant
GetPropertyValue method returns the value of the property or MaxBasic variable named in PropertyName.
GetPropertyValue method syntax has these named arguments:
Parameter
Description
Property Name
Required. Name of the Property to return the value for.
For example:
btnButton1.GetPropertyValue("Caption")
will return the Caption of button component btnButton1.
See also the MaxBasic Script Function
GetPropertyValue
, the Memory Table Builder
GetPropertyValue
method and the Scripted Form
GetPropertyValue
method.
See Also
Memory Tables

---

## Input Button - Input Grid Method

Source: https://accredo.co.nz/webhelp/IGInputButton.htm

Input Button - Input Grid Method
method
InputButton(Glyph: String/Number, OnClick: SubStatement, Caption: String)
Define a button control on an input grid that runs a Sub Statement when clicked.
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
See also Scripted Form
InputButton
method.
See Also
InputGrid Object

---

## InputBoolean - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputBooleanIGMethod.htm

InputBoolean - Input Grid Method
method
InputBoolean(FieldName: String)
Define a radio button control in an input grid that allows selection of boolean (yes/no) values.
InputBoolean method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
See also Scripted Form
InputBoolean
method and MaxBasic
InputBoolean
method.
See Also
InputGrid Object

---

## InputBox - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputBoxIGMethod.htm

InputBox - Input Grid Method
method
InputBox(FieldName: String)
Define a single line text edit control in an input grid that allows input of arbitrary text.
InputBox method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
See also MaxBasic
InputBox
function and Scripted Form
InputBox
method.
See Also
InputGrid Object

---

## InputCode - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputCodeIGMethod.htm

InputCode - Input Grid Method
method
InputCode(FieldName: String, CodeType: String[, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean, AllowEmpty Boolean, UseExactMatch: Boolean])
Define a Lookup control in an input grid that allows input of a code from a specified master record.
InputCode method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of field to display this editor for.
Code Type
Required. String expression used to select the type of code to be entered.
Filter
Optional. Filter expression for limiting available master file codes.
Filter Button Visible
Optional. Determines if the filter button is available on the control. Defaults to
True
.
Allow Inactive
Optional. Determines if Display Inactive Records button is available on the control. Defaults to
False
.
Allow Empty
Optional. Determines if the Lookup can be cleared after a value has been selected. Defaults to
False.
Use Exact Match
Optional. Determines if the Lookup can accept and return values not in the code list. Defaults to
True
.
See also MaxBasic
InputCode
function and Scripted Form
InputCode
method.
See Also
InputGrid Object

---

## InputCustomCode - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputCustomCodeIGMethod.htm

InputCustomCode - Input Grid Method
method
InputCustomCode(ControlName: String, TableName: String[, Filter: String, FilterButtonVisible: Boolean, AllowEmpty: Boolean, UseExactMatch: Boolean])
Define a Lookup control in an input grid that allows input of the primary code from a specified custom table or memory table.
InputCustomCode method syntax has these named arguments:
Parameter
Description
Control Name
Required. Name of field to display this editor for.
Table Name
Required. Custom table or memory table object to select code to display in the Lookup.
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
when the form is running.
See also MaxBasic
InputCustomCode
function and Scripted Form
InputCustomCode
method.
See Also
InputGrid Object

---

## InputDate - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputDateIGMethod.htm

InputDate - Input Grid Method
method
InputDate(FieldName: String)
Define a date edit control in an input grid that allows input of a date.
InputDate method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
See also MaxBasic
InputDate
function and Scripted Form
InputDate
method.
See Also
InputGrid Object

---

## InputInteger - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputIntegerIGMethod.htm

InputInteger - Input Grid Method
method
InputInteger(FieldName: String)
Define a spin edit control in an input grid that allows input of integer values.
InputInteger method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
See also MaxBasic
InputInteger
function and Scripted Form
InputInteger
method.
See Also
InputGrid Object

---

## InputList - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputListIGMethod.htm

InputList - Input Grid Method
method
InputList(FieldName: String, Value1: String [, Value2: String ...])
Define a combo edit control in an input grid that allows selection from a defined set of values.
InputList method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
Value 1
Required. The first value in the list.
Value 2 ...
Optional. Additional values in the list.
See also MaxBasic
InputList
function and Scripted Form
InputList
method.
See Also
InputGrid Object

---

## InputNumber - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputNumberIGMethod.htm

InputNumber - Input Grid Method
method
InputNumber(FieldName: String)
Define a number edit control in an input grid that allows input of arbitrary numbers.
InputNumber method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
See also MaxBasic
InputNumber
function and Scripted Form
InputNumber
method.
See Also
InputGrid Object

---

## InputPeriod - Input Grid Method

Source: https://accredo.co.nz/webhelp/InputPeriodIGMethod.htm

InputPeriod - Input Grid Method
method
InputPeriod(FieldName: String)
Define a period combo control in an input grid that allows input of financial periods.
InputPeriod method syntax has these named arguments:
Parameter
Description
Field Name
Required. Name of the field to display this editor for.
See also MaxBasic
InputPeriod
function and Scripted Form
InputPeriod
method.
See Also
InputGrid Object

---

## Insert - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBInsert.htm

Insert - Memory Table Method
method
Insert
Insert method inserts a record at the current line of the Memory Table or Table.
For example:
tblMemoryTable1.Insert
See Also
Memory Tables

---

## Last - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBLast_1.htm

Last - Memory Table Method
method
Last
Last method goes to the last line of the Memory Table or Table.
For example:
tblMemoryTable1.Last
See Also
Form Designer Table Methods

---

## LoadFromCSV - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBLoadFromCSV_1.htm

LoadFromCSV - Memory Table Method
method
LoadFromCSV(Filename: String[, HasHeader: Boolean, RecordTerminator: Variant, FileType: Integer])
LoadFromCSV method populates a Memory Table from a CSV file.
LoadFromCSV method syntax has these named arguments:
Parameter
Description
File Name
Required. Name of the delimited file to load from.
Has Header
Optional. Set to
True
when the file contains a header line. Defaults to
False
.
RecordTerminator
Optional. The character to signify the end of the record.
File Type
Optional. Integer.
0 - ANSI
1 - UTF16_LE
2 - UTF16_BE
3 - UTF8
4 - UTF8BOM
If this parameter is not specified, then encoding will be auto detected from the file.
For example:
MemTable.LoadFromCSV(FileName: String[, HasHeader: Boolean])
See Also
Form Designer Table Methods

---

## LoadFromExcel - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBLoadFromExcel.htm

LoadFromExcel - Memory Table Method
method
LoadFromExcel(Filename: String, Sheet: Variant[, StartFromCol: String, StartFromRow: Number, LastCol: String, LastRow: Number])
LoadFromExcal method populates a Memory Table from an Excel file.
LoadFromExcel method syntax has these named arguments:
Parameter
Description
File Name
Required. Name of the Excel file to load from.
Sheet
Required. The Excel worksheet name or number to load from.
Note: Do not use apostrophes (') in worksheet names, as this can cause problems.
Start From Col
Optional. The column to start load from. Defaults to column "A".
Start From Row
Optional. The row to start load from. Defaults to Row 1.
Last Col
Optional. The last column in the Excel file to import.
Last Row
Optional. The last row in the Excel file to import.
For example:
MemTable.LoadFromExcel(FileName: String, Sheet: Variant[, StartFromCol: String, StartFromRow: Number, LastCol: String, LastRow: Number])
See Also
Memory Tables

---

## LoadFromFile - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBLoadFromFile_1.htm

LoadFromFile - Memory Table Method
method
LoadFromFile(Filename: String, Delimiter: Variant[, HasHeader: Boolean, Quoted: Boolean, RecordTerminator: Variant, FileType: Integer])
LoadFromFile method populates a Memory Table from a delimited file.
LoadFromFile method syntax has these named arguments:
Parameter
Description
File Name
Required. Name of the delimited file to load from.
Delimiter
Required. The delimiter character or number. If a number is used, the valid values are:
0
= CSV, no headers
1
= CSV, with headers
2
= Tab delimited, no headers
3
= Tab delimited, with headers
Has Header
Optional. Set to
True
when the file contains a header line. Defaults to
False
.
Quoted
Optional. This is ignored when the Delimiter is a number.
When
True
, reads string values in quotes. Defaults to
False
.
RecordTerminator
Optional. The character to signify the end of the record.
File Type
Optional. Integer.
0 - ANSI
1 - UTF16_LE
2 - UTF16_BE
3 - UTF8
4 - UTF8BOM
If this parameter is not specified, then encoding will be auto detected from the file.
See also the Stringlist Object
LoadFromFile
method.
For example:
MemTable.LoadFromFile(FileName: String, Delimiter: String(1) or Number[, HasHeader: Boolean])
See Also
Form Designer Table Methods

---

## MaxBasic Date Operators

Source: https://accredo.co.nz/webhelp/MBDateOperators.htm

MaxBasic Date Operators
Operator
Syntax
Description
+
expr1 + expr2
Date addition. If one of the operands is a date and the other a number, this returns a date by adding the number of days to the given date.
See Also
MaxBasic Operators

---

## MaxBasic Debugger

Source: https://accredo.co.nz/webhelp/MBDebugger.htm

MaxBasic Debugger
MaxBasic Debugger appears when a breakpoint is hit. You can go to the next line, drill down to a function, view code, and abort.
Step Into
(F7)
If you are on a line that calls a function, click to drill into that function. Otherwise break on the next line.
Step Over
(F8)
Break on the next line.
Continue
(F9)
Continue script.
Script Editor
View code in Script Editor.
Abort
Abort the script.
In This Section
MB Debugger - Variables tab
MB Debugger - Watch List tab
MB Debugger - Breakpoint List tab
MB Debugger - Call Stack tab
MB Debugger - Output Log tab
MB Debugger - Event Log tab

---

## MaxBasic Operators

Source: https://accredo.co.nz/webhelp/MaxBasicOperators.htm

MaxBasic Operators
An operator manipulates one or two expressions to yield a new value as part of a larger expression. Operators are defined in certain ways for certain types, and the result is always of a certain type (or undefined in cases that cause exceptions, such as divide by zero). Compound expressions are built from simpler
expressions
by combining with operators.
MB Operator Precedence
The order that operators are applied in expressions can be controlled with the use of parentheses (). Sub-expressions inside parentheses are evaluated first. Where an expression or sub-expression contains more than one operator, operator precedence determines the order of expression evaluation. Where operators have equal precedence, expressions are evaluated left to right. The following table lists the operators in decreasing order of precedence:
Operator
^
Unary -
*, /
\
Mod
+, -
&
=, <, >, <=, >=, <>
Not
And
Or
Xor
Eqv
Imp
In This Section
MaxBasic Arithmetic Operators
MaxBasic Comparison Operators
MaxBasic Boolean Operators
MaxBasic String Operators
MaxBasic Date Operators

---

## MaxBasic String Operators

Source: https://accredo.co.nz/webhelp/MBStringOperators.htm

MaxBasic String Operators
Operator
Syntax
Description
&
expr1 & expr2
String concatenation. The operands are concatenated together as strings. If the operands are not strings, they are first converted to strings. If both operands are null, the result is null. If only one operand is null, the result is the other operand.

---

## MaxBasic Variables

Source: https://accredo.co.nz/webhelp/MaxBasicVariables.htm

MaxBasic Variables
A variable is a name that refers to a value (for example, number, date, or string). The value of a variable can change as the program runs. Variables are defined by using them on the left side of an
assignment
statement (how they attain their initial value), or by explicitly declaring them in a
Dim
statement. Once a variable has been defined, it can be used in expressions.
Naming Variables
Variable names must comprise of letters of the alphabet (A-Z), numeric digits (0-9) or the underscore character (_). Names must start with a letter or the underscore (not a digit). Variable names are not case sensitive - you can use a mixture of upper and lower case letters. The following are examples of valid variable names:
X_1XY3
RetainedEarnings
Total
Variable names must not be keywords of MaxBasic (for example, function names such as Int, Abs, or Str). The following are not valid variable names:
1_XY
Next
Retained Earnings
A&B
See Also
MaxBasic

---

## Next - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBNext_1.htm

Next - Memory Table Method
method
Next
Next method goes to the next row in a Memory Table or Table.
For example:
tblMemoryTable1.Next
See Also
Form Designer Table Methods

---

## PP Script Editor

Source: https://accredo.co.nz/webhelp/PPScriptEditor.htm

PP Script Editor
Navigator > Setup > Purchase Pricing > Pricing Script Editor
The Pricing script determines how PP rules are collected, selected, applied and ranked. The pricing script provided sorts rules by priority and effective price, then chooses the lowest price at the highest priority. A default script
PPDefault.pfs
is provided with Accredo.
The PP Script Editor is a version of the MaxBasic
Script Editor
. You can use it to create a new script, or modify the provided script.
The PP Script Editor includes the Context object, available under the Objects menu, which contains properties for the context in which the script is triggered to return a price. The Context object may be documented from the Automated menu, select
Automated > Context > Document Context
.
For example, you can rank and select PP Rules according to the business process or write information back to custom TD fields in the context object.
Within the script editor, to cancel writeback of Purchase Pricing, use a silent
Abort
statement.
Important: If you edit the provided
PPDefault.pfs
script or one of the other example scripts, save it under a different file name, as the provided scripts are overwritten when an Accredo server install is performed.
The
Pricing Script
file set in
PP Settings
will be executed whenever a price is returned if
Apply Purchase Pricing
is selected and in
PP Price Query
when the
Query
(F9)
button is clicked.
Purchase Pricing Context Object
The Purchase Pricing Context object appears in the Objects menu in the PP Script Editor, and may be documented from the Automated menu (Automated > Context > Document Context).
The Context object is used to Collect Purchase Pricing rules matching the properties of the Context and then to return pricing values after evaluation.
When a pricing decision is triggered the Context.Initial... properties return the starting point before Purchase Pricing rules are evaluated, e.g. in a PO Order the prices and discount that would apply if there is no purchase pricing.
Rules are collected using Context.Collect then evaluated.
After evaluating Purchase Pricing the Context.Purchase... properties are set to return the values from the context. Context.PurchaseMessage can be set to return a status hint.
Context sub objects can be located on different records and Context.Collect called to collect rules that apply the record. Set Context.UpdateDependantTables set True to apply the change to related sub objects.
For an example see the
PPDefaultWithBillTo.pfs
script which is provided, this first collects rules for the Creditor, then if the Creditor has a BillToAccountCode locates the BillToCreditor to collect rules applying to that Creditor. If UpdateDependentTables is set True then locating the BillToAccountCode would also update APCategory1, APCategory2, CreditorGroup, etc to the ones from the BillToAccountCode creditor record.
Note: For
Manually Costed
Products if
Use Cost Prices for Manually Costed Products
is
Unselected
in
AP Settings
the Cost Price passed to the PP Context is the Cost Price from the line not re-read from the Supplier Cost Product.

---

## Prev - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBPrev.htm

Prev - Memory Table Method
method
Prev
Prev method goes to the previous row in a table.
For example:
tblMemoryTable1.Prev
See Also
Memory Tables

---

## PropertyType - Memory Table Method

Source: https://accredo.co.nz/webhelp/MTPropertyType.htm

PropertyType - Memory Table Method
method
PropertyType(PropertyName: String): String
Returns the type of the property.
PropertyType method syntax has these named arguments:
Parameter
Description
Property Name
Required. Name of the property to return the type from.
For example:
btnButton1.PropertyType("Caption")
will return "String", as the Caption is a string.
See also the Memory Table Builder PropertyType method and the Scripted Form
PropertyType
method.
See Also
Memory Tables

---

## Refresh - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBRefresh_1.htm

Refresh - Memory Table Method
method
Refresh
Refreshes the data in a Memory Table or Table.
For example:
tblMemoryTable1.Refresh
will refresh the data in tblMemoryTable1
See Also
Form Designer Table Methods

---

## Save - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSave_1.htm

Save - Memory Table Method
method
Save
Save the current line of the Memory Table or Table.
For example:
tblMemoryTable1.Save
will save the current row of tblMemoryTable1.
See Also
Form Designer Table Methods

---

## SaveToCSV - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSaveToCSV.htm

SaveToCSV - Memory Table Method
method
SaveToCSV(Filename: String[, HasHeader: Boolean, RecordTerminator: Variant, FileType: Integer])
SaveToCSV method saves a Memory Table to a CSV file.
SaveToCSV method syntax has these named arguments:
Parameter
Description
File Name
Required. Name of the delimited file to save to.
Has Header
Optional. Set to
True
when the file contains a header line. Defaults to
False
.
RecordTerminator
Optional. The character to signify the end of the record.
File Type
Optional. Integer.
0 - ANSI
1 - UTF16_LE
2 - UTF16_BE
3 - UTF8
4 - UTF8BOM
If this parameter is not specified, the default type is ANSI.
For example:
MemTable.SaveToCSV(FileName: String[, HasHeader: Boolean, RecordTerminator: Variant])
See Also
Memory Tables

---

## SaveToExcel - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSaveToExcel.htm

SaveToExcel - Memory Table Method
method
SaveToExcel(Filename: String, [WithHeaders: Boolean, Sheet: Variant, StartFromCol: String, StartFromRow: Number, EndColumn: String, EndRow: Number])
SaveToExcel method saves a Memory Table to an Excel file.
SaveToExcel method syntax has these named arguments:
Parameter
Description
File Name
Required. Name of the Excel file to save to.
With Headers
Optional. When
True
, a header line will be included. Defaults to
False
.
Sheet
Optional. The Excel worksheet name or number to save to.
Note: Do not use apostrophes (') in worksheet names, as this can cause problems.
Start From Col
Optional. The column to start save to. Defaults to column "A".
Start From Row
Optional. The row to start save to. Defaults to Row 1.
End Column
Optional. The column to end save to.
End Row
Optional. The row to end save to.
Note: You can use the End Column and End Row parameters to overwrite existing data in a worksheet. Data in the sheet will be cleared up to the End Column and End Row.
For example:
MemTable.SaveToExcel(FileName: String[, WithHeaders: Boolean, Sheet: Variant, StartFromCol: String, StartFromRow: Number, EndColumn: String, EndRow: Number])
See Also
Memory Tables

---

## SaveToFile - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSaveToFile_1.htm

SaveToFile - Memory Table Method
method
SaveToFile(Filename: String, Delimiter: Variant, HasHeader: Boolean, Quoted: Boolean[, RecordTerminator: Variant])
SaveToFile method saves a Memory Table to a delimited file. If a number is used as the Delimiter, it specifies the file format. If a character is used as the Delimiter, it defines the delimiter character.
For example:
MemTable.SaveToFile(FileName: String, Delimiter: Number of String(1), HasHeader: Boolean, Quoted: Boolean[, RecordTerminator: Variant, FileType: Integer])
SaveToFile method syntax has these named arguments:
Parameter
Description
File Name
Required. Name of the delimited file to save to.
Delimiter
Required. The delimiter character or format number.
If a number is used, the format is defined. The valid number values are:
0 = CSV, no headers
1 = CSV, with headers
2 = Tab delimited, no headers
3 = Tab delimited, with headers
If a character is used, the character will be the delimiter character in the file, and the following fields are regarded.
Has Header
Required when the Delimiter is a character, ignored when the Delimiter is a number.
When
True
, a header line will be included. Defaults to
False
.
Quoted
Required when the Delimiter is a character, ignored when the Delimiter is a number.
When
True
, writes string values in quotes. Defaults to
False
.
RecordTerminator
Optional. The character to signify the end of the record.
File Type
Optional. Integer.
0 - ANSI
1 - UTF16_LE
2 - UTF16_BE
3 - UTF8
4 - UTF8BOM
If this parameter is not specified, the default type is ANSI.
For Example:
MemTable.SaveToFile("c:\tmp\Test1.csv", 1)
Creates a CSV output file with a header row.
MemTable.SaveToFile("c:\tmp\Test1.csv", "|", True, True)
MemTable.SaveToFile("c:\tmp\Test1.csv", chr(124), True, True)
Both these examples create a CSV output file using the pipe character (|) as a delimiter, with a header row and string values enclosed in quotes.
See also the StringList Object
SaveToFile
method.
See Also
Form Designer Table Methods

---

## Script Editor

Source: https://accredo.co.nz/webhelp/ScriptEditor.htm

Script Editor
Accredo > Script > Script Editor
Script editing and customisation are recommended for Users with programming skills. Code shown in Script Editor is MaxBasic automation code. To access MaxBasic code in Script Editor, you can either:
Record a script
Type the code directly,
Load an existing script - OR -
Use the drop down menus shown below.
To show Line Numbers in the Script Editor, go to Accredo > File > System > Users >
Preferences tab
, and select
Show line numbers in editors
. If line numbers are shown, they are included when a script is printed.
To access the Script Editor
Context Menu
, right-click in the script editor window, or press
Shift+F10
.
You can insert Automated code snippets in the Script Editor, see
Automated Snippets
.
Drop down menus
Operators
(Alt+O)
Lists
MaxBasic operators
.
Objects
(Alt+J)
Lists the
objects
and components available in the code. When you select a property it will appear in the code.
Functions
(Alt+F)
Lists available
MaxBasic functions
. When you select a function that expects arguments, parentheses, parameters and commas for the arguments are shown with the pointer at the first argument, for example,
InStr(|String1: String, String2: String)
. This shows that the
Instr
function requires two string arguments, one before and one after the comma.
Typing the function name in the editor followed by # will also expand the arguments for the function.
Help for a function, detailing the arguments, is available from:
The final option in the menu,
Pressing
F1
- OR -
Selecting from the context menu (right-click) with the cursor positioned in the function name in the editor.
Automated
(Alt+A)
Lists
Automated
objects. Documentation for each object is available from the final option in the menu. You can insert the code to Dim and Create an object by clicking on it.
Typing an Automated object name in the editor followed by # will also Dim and Create the Object..
Procedures
(Alt+E)
Lists
Function
and
Sub
procedures defined in the script.
For a full list of all Procedures including imported ones press
Ctrl+E
or select from the context menu (right-click) to open the
Procedure List
in a separate window.
Help
(Alt+H)
Access resources including descriptions, documentation and sample code.
Snippet
(Alt+T)
Insert a code
Snippet
. Snippets are listed alphabetically, and the first line of each snippet is displayed.
Typing a Snippet name  in the editor followed by # will also expand the snipped code.
Editor buttons
Check Code
(Alt+C)
Checks the code compiles correctly, without running the script.
Breakpoint
(Alt+B)
Set a code
breakpoint
on the current line. Click again to toggle to clear the breakpoint. You can also click to the right of a line to set or clear a breakpoint.
Hover the mouse over a breakpoint, then right-click to make a breakpoint unavailable, or access the
Breakpoint Properties
.
If a condition has been set for a breakpoint, it will be shown when you hover over the breakpoint.
Run
(Alt+R)
Runs the script. To run a script when Script Editor is closed, press
Alt+F3
or click
on the Accredo toolbar, or setup a
script shortcut
. To terminate a running script, press
Alt+F1
. The line and character at which the script was terminated will be displayed.
Print
(Ctrl+P)
Print the code. This can be helpful when writing scripts.
Capture Status Hints
Selected
, you can capture status hints when the script is Run. This is useful for checking the effect of a script.
Add Shortcut
(Alt+D)
Select to:
Add Shortcut
- add the script as a
Shortcut
on the Accredo toolbar and / or  the Navigator.
Add Script Event
- attach the script to a
Script Event
.
View Script Events
- view all
Script Events.
This can be useful for ascertaining whether a script event already exists.
Check and Save
(Alt+K)
Check the code compiles correctly then save the script.
Encoding
File encoding for the script is displayed.
Default File Encoding may be changed in
System Settings - Encoding
.
Saving a file will use the selected encoding.
Load...
(Alt+L)
Load an existing script to select the code, run, print or edit.
Click the drop down to view a list of recently saved/loaded scripts.
Scripts are either .pfs text files, or .pfz encrypted files which are decrypted on load.
Save...
(Ctrl+S)
Once saved, you can
run the script
, or setup a
script shortcut
or
script event
.
Scripts may be saved as .pfs files which are plain text, or .pfz files which are encrypted.
Note: Saving (and encrypting) and Loading (and decrypting) encrypted scripts in the script editor requires Write permission for Company > Scripts > Encrypted, in addition other scripting permissions.
In This Section
Script Editor - Shortcut keys
Script Editor - Context Menu
Procedure List
Breakpoint Properties
Automated Snippets
Import / Export Designer Code Editor
Encrypted Scripts

---

## Script Editor - Context Menu

Source: https://accredo.co.nz/webhelp/ScriptEditor_ContextMenu.htm

Script Editor - Context Menu
Accredo > Script > Script Editor > Right-click - OR - (
Shift+F10
)
Right-click or press
Shift+F10
in the
Script Editor
or
Code Editor
window to access the Context Menu.
Goto Line
(Ctrl+G)
Prompts for the line (and column) to go to. Enter the line to go to, then the character to go to in brackets. For example
1(10)
will go to Line: 1, Char: 10.
Procedure List
(Ctrl+E)
Opens the
Procedure List
.
Use Syntax Highlighting
Highlight text in different formats based on the category of the text's purpose in the script or code.
Show Line Numbers
Display line numbers on the left of the window.
Find Text
(Ctrl+F)
Opens the
Find
window, to allow you to search for text.
Find Again
(F3)
Repeat the previous
Find
command.
Replace Text
(Ctrl+H)
Opens the
Replace
window, to allow you to replace text.
Comment Text
(Ctrl+')
Inserts a comment character (') at the start of the line or selected lines. Lines are set to comment lines.
Uncomment Text
(Shift+Ctrl+')
Removes the comment character (') from the start of the line or selected lines. Lines are no longer set as comment lines.
Indent Text
(Shift+Ctrl+I)
Indent the line or selected lines.
Unindent Text
(Shift+Ctrl+U)
Unindent the line or selected lines.
Help
Function
If the cursor is on a MaxBasic function name, this option is made available. Open the Help for the selected Function.
Select All
(Ctrl+A)
Select all text.
Add Snippet
(Ctrl+O)
Add the selected text to the Snippet Manager. Opens the
Snippet Code Editor
.
Open Source
(Ctrl+Enter)
Available for functions
Imports
,
CreateCustomForm
,
PlayScript
,
EDIImport
,
EDIExport
,
CreateSalesAnalysisReport
,
CreatePurchaseAnalysisReport
and
CreateJobAnalysisReport
.
For Imports, with the cursor in the file name, this will open the file in  a new script editor or form designer as relevant.
For example, for
Imports("filename.pfs"
), this will open the filename in a new script editor.
For example, for
CreateCustomForm("testform.pfd")
, this will open the form in Form Designer.
Set Bookmark
(Ctrl+Shift +
number
)
You can add bookmarks to your script. Select the number from the menu, or press
Ctrl+Shift+
(
number
), with a number from 0 to 9. For example, press
Ctrl+Shift+1
to set Bookmark 1.
You can return to the bookmark by pressing
Ctrl+(number
. To clear a bookmark, go to the bookmark, then press
Ctrl+Shift+(number)
again.
Note: You cannot use the number pad for bookmarks, as other accelerator key functions use the number pad.
Note: Windows sometimes sets
Ctrl+Shift+0
as a shortcut for switching between input languages. If this has been assigned, it will need to be cleared from the Control Panel for the
Ctrl+Shift+0
bookmark shortcut to work.
Goto Bookmark
(Ctrl+
number
)
Available when a bookmark has been set. Select the bookmark from the menu, or press
Ctrl+(number)
to return to the numbered bookmark.
Goto Declaration
(F12)
With focus on a user function name will locate to the function declaration. Note: The function being navigated to must be in the same script file.
Format Code
Available when no text is selected. Apply auto formatting -  blank line between functions/subroutines, two space indentation, line continuation indentation and function / statement capitalisation.
Undo
(Ctrl+Z)
Undo the last single keystroke or editing operation.
Redo
(Ctrl+Y)
Re-do the last single keystroke or editing operation.
Cut
(Ctrl+X)
Cut selected text or figures.
Copy
(Ctrl+C)
Copy selected text or figures.
Paste
(Ctrl+V)
Paste previously cut or copied text or figures.

---

## Script Editor - Shortcut keys

Source: https://accredo.co.nz/webhelp/ScriptEditorFunctionKeys.htm

Script Editor - Shortcut keys
Expand using # (hash key)
Type a
MaxBasic Function
name,
Automation Object
name or a
Snippet
name followed by # (the hash key) to expand the Function parameters, Dim and Create the Object or insert the Snippet code respectively.
Common Shortcuts
Indent text
Ctrl+Shift+I
Unindent text
Ctrl+Shift+U
Comment text
Ctrl+'
Uncomment text
Ctrl+Shift+'
Go to line (and column)
Ctrl+G
Find
Ctrl+F
Find again
F3
Replace
Ctrl+H
Terminate a running script
Alt+F1
Procedure List
Ctrl+E
Set or Clear Breakpoint
Alt+B
Go to bookmark 0 to 9
Ctrl+0 to Ctrl+9
Set or Clear bookmark 0 to 9
Ctrl+Shift+0 to Ctrl+Shift+9
Scroll up
Ctrl+Up
Scroll down
Ctrl+Down
Display Context Menu
Shift+F10
Add Snippet
Ctrl+0
Open Source
Ctrl+Enter
Selecting and Editing text
Drag text between editors using
Ctrl
to switch from move to copy.
Undo
Ctrl+Z
or Alt+Backspace
Redo
Ctrl+Y
or Alt+Shift+Backspace
Cut
Ctrl+X
or Shift+Delete
Copy
Ctrl+C
or Ctrl+Insert
Paste
Ctrl+V
or Shift+Insert
Select all
Ctrl+A
Delete last word
Ctrl+Backspace
Delete to end of word
Ctrl+T
Delete to end of line
Ctrl+Shift+Y
Line break
Ctrl+M
or Enter
Insert line
Ctrl+N
Delete line
Ctrl+D

---

## SetPropertyValue - Memory Table Method

Source: https://accredo.co.nz/webhelp/MTSetPropertyValue.htm

SetPropertyValue - Memory Table Method
method
SetPropertyValue(PropertyName: String, Value: Variant)
This sets the value of the property or MaxBasic variable named in PropertyName to the Value.
SetPropertyValue method syntax has these named arguments:
Parameter
Description
Property Name
Required. Name of the Property to set the value for.
Value
Required. The value to set Property Name to.
For example:
tblMemoryTable1.SetPropertyValue("Inactive", "True")
will set the value of a boolean Inactive property to
True
.
tblMemoryTable1.SetPropertyValue("Reference", "ORD 1234")
will set the value of a string Reference property to "ORD 1234".
See also the Memory Table Builder SetPropertyValue method and the Scripted Form
SetPropertyValue
method.
See Also
Memory Tables

---

## SetRange - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSetRange.htm

SetRange - Memory Table Method
method
SetRange (Value1: Variant[, Value2: Variant, Value 3: Variant, Value4: Variant])
SetRange method sets a range on indexed values within a Memory Table or Table. Moves to the first record in the range.
SetRange method syntax has these named arguments:
Parameter
Description
Value 1
Required. Values for the first record in the range.
Value 2, Value 3, Value 4
Optional. Additional values to add to the range.
See Also
Memory Tables

---

## SetRangeEnd - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSetRangeEnd.htm

SetRangeEnd - Memory Table Method
method
SetRangeEnd (Value1: Variant[, Value2: Variant, Value 3: Variant, Value4: Variant])
SetRangeEnd method sets the ending values for a range on indexed values, within a Memory Table or Table.
SetRangeEnd method syntax has these named arguments:
Parameter
Description
Value 1
Required. Values for the last record in the range.
Value 2, Value 3, Value 4
Optional. Additional values to add to the range end.
See Also
Memory Tables

---

## SetRangeStart - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSetRangeStart_2.htm

SetRangeStart - Memory Table Method
method
SetRangeStart (Value1: Variant[, Value2: Variant, Value 3: Variant, Value4: Variant])
SetRangeStart method sets the the starting values for a range on indexed values, within a Memory Table or Table.
SetRangeStart method syntax has these named arguments:
Parameter
Description
Value 1
Required. Values for the first record in the range.
Value 2, Value 3, Value 4
Optional. Additional values to add to the range start.
See Also
Form Designer Table Methods

---

## Sort - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSort_1.htm

Sort - Memory Table Method
method
Sort(SortFields: String)
Sort method sorts a Memory Table by fields listed in SortFields.
You can specify the sort ordering by using +'s and -'s before each field to specify its sort order (+ is the default if nothing is specified). If the order is specified for the first field of the index only this ordering will apply to all parts of the index.
For example:
Builder.Sort("-SalesArea;+CustCode")
Sort method syntax has these named arguments:
Parameter
Description
SortFields
Required. List of fields to include in the index, each field separated by a semi-colon (;).
See also the StringList Object
Sort
method.
See Also
Form Designer Table Methods

---

## SP Script Editor

Source: https://accredo.co.nz/webhelp/SPScriptEditor.htm

SP Script Editor
Navigator > Setup > Special Pricing > Pricing Script Editor
The Pricing script determines how SP rules are collected, selected, applied and ranked. The pricing script provided sorts rules by priority and effective price, then chooses the lowest price at the highest priority. A default script
SPDefault.pfs
is provided with Accredo.
The SP Script Editor is a version of the MaxBasic
Script Editor
. You can use it to create a new script, or modify the provided script.
The SP Script Editor includes the Context object, available under the Objects menu, which contains properties for the context in which the script is triggered to return a price. The Context object may be documented from the Automated menu, select
Automated > Context > Document Context
.
For example, you can rank and select SP Rules according to the business process, write information back to custom TD fields in the context object or disallow Special Pricing if an account is not paid in full by the due date.
Within the script editor, to cancel writeback of Special Pricing, use a silent
Abort
statement.
Important: If you edit the provided
SPDefault.pfs
script or one of the other example scripts, save it under a different file name, as the provided script is overwritten when an Accredo server install is performed.
The
Pricing Script
file set in
SP Setting
s will be executed whenever a price is returned if
Apply Special Pricing
is selected and in
SP Price Query
when the
Query
(F9)
button is clicked.
Special Pricing Context Object
The Special Pricing Context object appears in the Objects menu in the SP Script Editor, and may be documented from the Automated menu (Automated > Context > Document Context).
The Context object is used to Collect Special Pricing rules matching the properties of the Context and then to return special pricing values after evaluation.
When a pricing decision is triggered the Context.Initial... properties return the starting point before Special Pricing is evaluated, e.g. in an IN Invoice the prices and discount that would apply if there is no special pricing.
Rules are collected using Context.Collect then evaluated.
After evaluating Special Pricing the Context.Special... properties are set to return the values from the context. Context.SpecialMessage can be set to return a status hint.
Context sub objects can be located on different records and Context.Collect called to collect rules that apply the record. Set Context.UpdateDependantTables set True to apply the change to related sub objects.
For an example see the
SPDefaultWithBillTo.pfs
script which is provided, this first collect rules for the customer, then if the Customer has a BillToAccountCode locates the BillToCustomer to collect rules applying to that customer. If UpdateDependentTables is set True then locating the BillToAccountCode would also update ARCategory1, ARCategory2, CustomerGroup, etc to the ones from the BillToAccountCode customer record.
See Also
Special Pricing - Settings

---

## StartFormUpdates - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBStartFormUpdates_1.htm

StartFormUpdates - Memory Table Method
method
StartFormUpdates
StartFormUpdates method starts a grid being updated. For Memory Tables bound to a grid on a form, this starts the grid being automatically updated. This is used in conjunction with the
StopFormUpdates
method, so grids don't redraw line by line when refreshing an entire grid.
For example:
Table.StopFormUpdates
Try
' Do stuff
Finally
Table.StartFormUpdates
End
See Also
Form Designer Table Methods

---

## StopFormUpdates - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBStopFormUpdates_1.htm

StopFormUpdates - Memory Table Method
method
StopFormUpdates
StopFormUpdates method stops form updates. For Memory Tables bound to a grid on a form, this stops the grid being automatically updated. This is used in conjunction with the
StartFormUpdates
method, so grids don't redraw line by line when refreshing an entire grid.
For example:
Table.StopFormUpdates
Try
' Do stuff
Finally
Table.StartFormUpdates
End
See Also
Form Designer Table Methods

---

## SwapDown - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSwapDown.htm

SwapDown - Memory Table Method
method
SwapDown
SwapDown method moves the current record down one position in a Memory Table.
For example:
tblMemoryTable1.SwapDown
See Also
Memory Tables

---

## SwapUp - Memory Table Method

Source: https://accredo.co.nz/webhelp/MBSwapUp.htm

SwapUp - Memory Table Method
method
SwapUp
SwapUp method moves the current record up one position in a Memory Table.
For example:
tblMemoryTable1.SwapUp
See Also
Memory Tables

---

