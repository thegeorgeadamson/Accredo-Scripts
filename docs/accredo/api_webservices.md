# API & Web Services

> REST API, OData, web service functions/actions, OAuth, domain events

**Sections:** 82

---

## Quick Reference

- [{Object}/Print and {Object}/PrintSheet - Web Service Function](#object-print-and-object-printsheet---web-service-function)
- [About - Web Service Function](#about---web-service-function)
- [Accredo API Overview and Basics](#accredo-api-overview-and-basics)
- [Accredo API Technical Documentation](#accredo-api-technical-documentation)
- [AddPeriod - Web Service Function](#addperiod---web-service-function)
- [AP Web Service Actions and Functions](#ap-web-service-actions-and-functions)
- [AppName - Web Service Function](#appname---web-service-function)
- [AR Generate Overdue Interest Query](#ar-generate-overdue-interest-query)
- [AR Web Service Actions and Functions](#ar-web-service-actions-and-functions)
- [BaseCurrencyCode - Web Service Function](#basecurrencycode---web-service-function)
- [CB Web Service Actions and Functions](#cb-web-service-actions-and-functions)
- [Company - Web Service Function](#company---web-service-function)
- [Company Web Service Actions and Functions](#company-web-service-actions-and-functions)
- [CurrentPeriod - Web Service Function](#currentperiod---web-service-function)
- [Custom Tables via Web Service](#custom-tables-via-web-service)
- [DefaultBranchCode - Web Service Function](#defaultbranchcode---web-service-function)
- [DefaultDepartmentCode - Web Service Function](#defaultdepartmentcode---web-service-function)
- [DefaultLocationCode - Web Service Function](#defaultlocationcode---web-service-function)
- [Deleting a Web Service Token](#deleting-a-web-service-token)
- [Demo System Web Service Setup](#demo-system-web-service-setup)
- [Enum - Web Service Function](#enum---web-service-function)
- [FA Web Service Actions and Functions](#fa-web-service-actions-and-functions)
- [FieldDependency - Web Service Function](#fielddependency---web-service-function)
- [FirstUserPeriod - Web Service Function](#firstuserperiod---web-service-function)
- [GetExchangeRate - Web Service Function](#getexchangerate---web-service-function)
- [GetPrimaryKey - Web Service Function](#getprimarykey---web-service-function)
- [GetUserCompanyList - Web Service Function](#getusercompanylist---web-service-function)
- [GL Web Service Actions and Functions](#gl-web-service-actions-and-functions)
- [GST Web Service Actions and Functions](#gst-web-service-actions-and-functions)
- [GSTRate - Web Service Function](#gstrate---web-service-function)
- [IC Web Service Actions and Functions](#ic-web-service-actions-and-functions)
- [ICAvailable - Web Service Function](#icavailable---web-service-function)
- [Image - Web Service Function](#image---web-service-function)
- [IN Web Service Actions and Functions](#in-web-service-actions-and-functions)
- [JC Web Service Actions and Functions](#jc-web-service-actions-and-functions)
- [LastUserPeriod - Web Service Function](#lastuserperiod---web-service-function)
- [Live System Web Service Setup](#live-system-web-service-setup)
- [Memos via Web Service](#memos-via-web-service)
- [ModuleAvailable - Web Service Function](#moduleavailable---web-service-function)
- [OData Filter Editor](#odata-filter-editor)
- [OE Web Service Actions and Functions](#oe-web-service-actions-and-functions)
- [openapi.json - Web Service Function](#openapijson---web-service-function)
- [PeriodForDate - Web Service Function](#periodfordate---web-service-function)
- [PlayLayout - Web Service Function](#playlayout---web-service-function)
- [PlayScript / PlayReportScript - Web Service Function](#playscript---playreportscript---web-service-function)
- [PO Web Service Actions and Functions](#po-web-service-actions-and-functions)
- [Post - Web Service Function](#post---web-service-function)
- [PP Web Service Actions and Functions](#pp-web-service-actions-and-functions)
- [PPEnquiry - Web Service Function](#ppenquiry---web-service-function)
- [Printing via Web Service](#printing-via-web-service)
- [ReportLayout - Web Service Function](#reportlayout---web-service-function)
- [ScriptDoc - Web Service Function](#scriptdoc---web-service-function)
- [SP Web Service Actions and Functions](#sp-web-service-actions-and-functions)
- [SPEnquiry - Web Service Function](#spenquiry---web-service-function)
- [System Web Service Actions and Functions](#system-web-service-actions-and-functions)
- [SystemDate - Web Service Function](#systemdate---web-service-function)
- [SystemPeriod - Web Service Function](#systemperiod---web-service-function)
- [User - Web Service Function](#user---web-service-function)
- [Web Service](#web-service)
- [Web Service About](#web-service-about)
- [Web Service Actions and Functions](#web-service-actions-and-functions)
- [Web Service Basic Token Cache](#web-service-basic-token-cache)
- [Web Service Client Cache](#web-service-client-cache)
- [Web Service Company ID Cache](#web-service-company-id-cache)
- [Web Service Connection Cache](#web-service-connection-cache)
- [Web Service Functions in MaxBasic](#web-service-functions-in-maxbasic)
- [Web Service Header](#web-service-header)
- [Web Service Installation and Initial Configuration](#web-service-installation-and-initial-configuration)
- [Web Service Live Logging View](#web-service-live-logging-view)
- [Web Service Login](#web-service-login)
- [Web Service Menu](#web-service-menu)
- [Web Service Monitor](#web-service-monitor)
- [Web Service Response View](#web-service-response-view)
- [Web Service Server View](#web-service-server-view)
- [Web Service Settings - Balancing tab](#web-service-settings---balancing-tab)
- [Web Service Settings - Debugging tab](#web-service-settings---debugging-tab)
- [Web Service Settings - General tab](#web-service-settings---general-tab)
- [Web Service Settings - Logging tab](#web-service-settings---logging-tab)
- [Web Service Settings - Workers tab](#web-service-settings---workers-tab)
- [Web Service Token Cache](#web-service-token-cache)
- [Web Service User Cache](#web-service-user-cache)
- [Web Service Worker View](#web-service-worker-view)

---

## {Object}/Print and {Object}/PrintSheet - Web Service Function

Source: https://accredo.co.nz/webhelp/PrintWSFunction.htm

{Object}/Print and {Object}/PrintSheet - Web Service Function
{Object}/Print[(Destination=
String
,ReportFileName=
String
,Format=
String
,PrinterName=
String
,FileName=
String
,Intent=
String
,CashSale=
String
)]
{Object}/PrintSheet[(Destination=
String
,ReportFileName=
String
,Format=
String
,PrinterName=
String
,FileName=
String
,Intent=
String
)]
The Print and PrintSheet Web Service Functions print an object. You can optionally specify the Destination, Report File Name, Format, Printer Name, File Name and Intent.
Print can be used with the following objects:
APShipments
APTransaction - only Payment transactions
ARTransaction - only Receipt transactions
CBStatement
ICProduct
INInvoice
JCJob
OEOrder
POOrder
PrintSheet can be used with the following objects:
APCreditor
ARCustomer
Print function syntax has these named arguments:
Parameter
Description
Destination
Optional. Specify the print destination.
Report File Name
Optional. Specify the report file name.
Format
Optional. The printing format.
Printer Name
Optional. The name of the printer to print to.
File Name
Optional. The name to save the printed report.
Intent
Optional. Specify the delivery intent from
Inline
or
Attachment
. Defaults to Inline.
Cash Sale
Optional. Only available for IN Invoices. Can be set to
True
or
False
to print the invoice as a Cash Sale.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax to print the IN Invoice with Document ID
1
is:
Response = MakeCall("INInvoice('1')/Print(intent=attachment)")
See Also
Web Service Actions and Functions

---

## About - Web Service Function

Source: https://accredo.co.nz/webhelp/AboutWSFunction.htm

About - Web Service Function
About: String
About Web Service function returns details of the Company or System, including the OData Context, Operating System, System Version, System Path, Release, Product, Worker Start date and time and Worker Up Time.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("About")
You can also access this information through:
http://{
Server
}/odata4/v1/System/About
http://{
Server
}/odata4/v1/
{Company}
/About
See Also
Company Web Service Actions and Functions

---

## Accredo API Overview and Basics

Source: https://accredo.co.nz/webhelp/WSAPIOverviewBasics.htm

Accredo API Overview and Basics
The Accredo API is a Restful OData 4 JSON API and uses OAuth 2.0 for authorisation.
Details on the OData 4 specification can be found here:
https://www.odata.org
. To use the Accredo API, we recommend you read the OData basics to become familiar with the standard. A useful guide to OData 4 can be found at
OData Basic Tutorial
(http://www.odata.org/getting-started/basic-tutorial/).
The API service must be installed and configured on the client's server. A 64bit operating system is required.
A test system is available for developer testing at https://demo.accredo.co.nz
The API URL is: https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('demo')
Authorisation
The Accredo API uses OAuth 2.0 for authorisation, with an OAuth grant type of password.
For more information about OAuth 2.0, please see the specification here:
https://oauth.net/2/
Note:
UserName
for OAuth 2.0 can be either an Accredo System User Code or the unique email address for a System User.
The demo system details are as follows:
Client_id
: 3v7OstC8Bu6SESqM
Username
: demo
Password
: demo
The OAuth secret is not used, and scope is implied from the user being authenticated based on its Accredo permissions.
The OAuth endpoint is: https://demo.accredo.co.nz:6569/saturn/oauth2/v1/token
A sample request body posted to the token endpoint is:
{
"grant_type":"password",
"client_id":"3v7OstC8Bu6SESqM",
"username":"demo",
"password":"demo"
}
The response to this would be:
{
"access_token": "wQ2pJxukkQPTulD3",
"token_type": "bearer",
"expires_in": 3600,
"refresh_token": "ujRTfsCjlqww2Op3"
}
The OAuth access token can passed in the URL for a GET request, but for security it is recommended an authorization header be used instead. An authorization header is required for POST/PATCH/PUT/DELETE requests.
A full list of all our endpoints is available at:
https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('demo')/developerdoc?access_token=
This includes links to the metadata documentation for each of the endpoints, their properties and actions.
Common API Endpoints
The most commonly used Accredo API endpoints are:
/ARCustomerList
/ICProductList
/INInvoiceList
/OEOrderList
These return filterable lists for Customers, Products, Invoices, and Orders, the full records can then be found at their respective endpoints:
/ARCustomer('StringID')
/ICProduct('StringID')
/INInvoice(NumericID)
/OEOrder(NumericID)
More information on working with these OData endpoints, such as filtering and field selections can be found in the OData guide. Specifics such as available fields can be found in the API metadata.
Example API call
The following request will get the Customer record for the customer in our Demo system with code
ASHENG
, selecting the fields
CustomerCode
,
CustomerName,
and
CustomerGroupCode
.
GET
https://demo.accredo.co.nz:6569/saturn/odata4/v1/company('DEMO')/ARCustomer('ASHENG')?$Select=CustomerCode,CustomerName,CustomerGroupCode&access_token=
This will return the following JSON body:
{
"@odata.context" : "https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('DEMO')/$metadata#ARCustomer/$entity",
"@odata.id" : "https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('DEMO')/ARCustomer('ASHENG')",
"@odata.etag" : "1",
"@odata.editLink" : "https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('DEMO')/ARCustomer('ASHENG')",
"CustomerCode" : "ASHENG",
"CustomerName" : "Asheng Engineering Ltd",
"CustomerGroupCode" : "0000"
}
Many of the endpoints, i.e /INInvoice have expandable sub-objects like 'Line' for invoice lines.These are not returned by default when making a call to the endpoint and need to explicitly expanded. An example of this, is shown below. This requests an invoice, selecting the fields
CustomerCode
,
DocumentDate
,
GSTAmount
and
ExclusiveAmount
, and expands the Line sub-object, selecting the
ProductCode
,
QuantitySupplied
,
GSTAmount
and
ExclusiveAmount
.
GET
https://demo.accredo.co.nz:6569/saturn/odata4/v1/company('DEMO')/INInvoice(414)?$Select=CustomerCode,DocumentDate,GSTAmount,ExclusiveAmount&$Expand=Line($Select=ProductCode,QuantitySupplied,GSTAmount,ExclusiveAmount)&access_token=
This will return the following JSON body:
{
"@odata.`context": "https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('DEMO')/$metadata#INInvoice/$entity",
"@odata.etag": "10",
"CustomerCode": "SMITH",
"ExclusiveAmount": 7956.64,
"GstAmount": 1195.67,
"DocumentDate": "2019-09-28",
"
[email protected]
": "https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('DEMO')/$metadata#INInvoice(414)/Line",
"Line": [
{
"ProductCode": "SMLBOOKCASE",
"QuantitySupplied": 2,
"ExclusiveAmount": 849.87,
"GstAmount": 127.48
},
{
"ProductCode": "BEDSUITE",
"QuantitySupplied": 2,
"ExclusiveAmount": 0,
"GstAmount": 0
},
{
"ProductCode": "BEDCABINET",
"QuantitySupplied": 4,
"ExclusiveAmount": 1398.74,
"GstAmount": 209.81
},
{
"ProductCode": "DRESSTABLE",
"QuantitySupplied": 2,
"ExclusiveAmount": 1295.12,
"GstAmount": 194.27
},
{
"ProductCode": "STDCHEST",
"QuantitySupplied": 2,
"ExclusiveAmount": 1548.41,
"GstAmount": 232.26
},
{
"ProductCode": "QUEENBED",
"QuantitySupplied": 2,
"ExclusiveAmount": 2254.18,
"GstAmount": 338.13
},
{
"ProductCode": "STDBEDHEAD",
"QuantitySupplied": 2,
"ExclusiveAmount": 542.32,
"GstAmount": 81.35
},
{
"ProductCode": "OVALMIRROR",
"QuantitySupplied": 1,
"ExclusiveAmount": 68,
"GstAmount": 10.2
}
]
}
Selecting fields is not a requirement, but is useful for reducing the size of responses and only dealing with specific data you are interested in.
It is also possible to query the Accredo database tables directly via the /table_TableName endpoints, i.e /table_ICPROD for the ICPROD table which contains the product information. These endpoints do not have the combined sub-objects and are read-only. But they are useful for trying to request large volumes of data via the API.
Technical Documentation
Full technical documentation for the API is available from the topic here:
Accredo API Technical Documentation
.
Further Documentation
A full list of the available API endpoints can be found via the /DeveloperDoc endpoint. This contains links to each endpoint as well as endpoint metadata information.
Metadata is available to show both type and property data for endpoints.
/$metadata/$format=json
/$metadata/Types$format=json
/$metadata/Properties$format=json
/$metadata/Functions$format=json
/$metadata/Actions$format=json
And can request individual entities as :
/$metadata/Types('ARCUSTOMER')$format=json
/$metadata/Properties('ARCUSTOMER')$format=json
OpenAPI Documentation
We provide an endpoint to generate an OpenAPI 2.0 JSON file: /openapi.json.
Note: OpenAPI is not fully compatible with OData and there are differences between the generated documentation for OpenAPI and the correct query and parameter structure for OData. This endpoint is provided as a convenience only.

---

## Accredo API Technical Documentation

Source: https://accredo.co.nz/webhelp/WSAPITechicalDocumentation.htm

Accredo API Technical Documentation
The following links contain full technical documentation for the Accredo API. This includes a full listing of endpoints with their properties and actions, and valid call types.
Accredo Saturn Endpoints
Admin API Endpoints
OData API Endpoints
System API Endpoints
Accredo Mercury Endpoints
Admin API Endpoints
OData API Endpoints
System API Endpoints

---

## AddPeriod - Web Service Function

Source: https://accredo.co.nz/webhelp/AddPeriodWSFunction.htm

AddPeriod - Web Service Function
AddPeriod(PeriodID=
Number
,Offset=
Number
,[Financial=
Boolean
]): Number
AddPeriod Web Service Function adds Offset amount to PeriodID. Offset can be either positive or negative. The optional boolean parameter Financial is True by default, and restricts periods considered to Financial Periods only (excludes Adjustment periods). If specified as False then all periods including Adjustment periods are considered.
AddPeriod function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to be added to.
Offset
Required. Offset to be added to Period ID.
Financial
Optional. If True, only financial periods are considered. If False, all periods including adjustment periods are considered.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("AddPeriod(PeriodID=102,Offset=-12,Financial=True)")
See also the MaxBasic
AddPeriod
function and the SQL
AddPeriod
function.
See Also
Company Web Service Actions and Functions

---

## AP Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/APWebServiceActionsAndFunctions.htm

AP Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
APAllocateTransactions
Allocate payments and credits against invoices for a creditor.
APBudget
Returns budget details for AP Creditor Budgets.
APCategory1, APCategory2
Returns the AP categories set for the company.
APContact
Returns details for a specified AP Contact or for all AP Contacts.
APCostCode
Returns details for a specified Cost Code or for all Cost Codes.
APCreditor
Returns details for a specified Customer or for all Creditors.
APCreditor/
Printsheet
Print a Creditor Sheet.
APCreditorGroup
Returns details for a specified Creditor Group or for all Creditor Groups.
APCreditorList
Returns details for a specified Creditor or for all Creditors.
APMemo
Returns a memo for specified Memo ID or for all AP Memos.
APSHCategory1, APSHCategory2
Returns the AP Shipment categories set for the company.
APShipmentList
Returns details for a specified Shipment or for all Shipments.
APShipments
Returns details for a specified Shipment or for all Shipments.
APShipments/Post
Invoice
Posts the Invoice transaction for a Shipment to AP.
APShipments/PostReceipts
Posts the Receipt transactions for a Shipment to AP.
APShipments/
Print
Prints an AP Shipment for a given AP Shipment ID.
APTransaction
Returns details for a given AP Transaction ID or for all AP Transactions.
APTransaction/
Print
Prints an AP Transaction for a given AP Transaction ID. Only Payment transactions can be printed.
See Also
Web Service Actions and Functions

---

## AppName - Web Service Function

Source: https://accredo.co.nz/webhelp/AppNameWSFunction.htm

AppName - Web Service Function
AppName: String
App Name Web Service function returns the string
Mercury
or
Saturn
depending on the application running on the Web Service.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("Appname")
See also the MaxBasic
AppName
function and the SQL
AppName
function.
See Also
Company Web Service Actions and Functions

---

## AR Generate Overdue Interest Query

Source: https://accredo.co.nz/webhelp/ARGenerateOverdueInterest_Query.htm

AR Generate Overdue Interest Query
Navigator > Tasks > Accounts Receivable > Generate Overdue Interest >
Query Run
Transactions which are overdue are listed in the grid. You can select or unselect transactions to calculate overdue interest on.
Transaction Grid
Due Date
Due date for transactions.
Reference
Reference for the transaction.
Type
The type of transaction.
Overdue Amount
The amount which interest is calculated on. Unallocated less Hold.
Hold
The amount of the transaction on hold.
Unallocated Amount
The total outstanding for the transaction.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Select
(F4)
Select the transaction, recalculates to Overdue Amount.
Select All
(Shift+F4)
Select all transactions currently displayed, recalculates to Overdue Amount.
Unselect
(F3)
Unselect the transaction, zeroes the Overdue Amount.
Unselect All
(Shift+F3)
Unselect all transactions currently displayed, zeroes the Overdue Amounts.
Open
(F12)
View the details for the transaction in
AR Transactions
.
Drill down
(Shift+F12)
View the source document.
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
Memos
(F6)
Memos and alarms can be entered or edited. The button changes to indicate if memos and alarms are present. Opens
Memos On...
with a list of Memos.
Totals
Overdue Total
The total amount overdue which interest is calculated on.
Interest at ... %
The interest calculated at the percentage specified.
Rate Type
Type of exchange rate.
Exchange Rate
The exchange rate.
Buttons
Update
(F9)
Accept calculated Interest charge and save transaction.
Skip
(Esc)
Do not accept the calculated Interest charge. Move to the next customer.

---

## AR Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/ARWebServiceActionsAndFunctions.htm

AR Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
ARAllocateTransactions
Allocate receipts against outstanding invoices for a customer.
ARBudget
Returns budget details for AR Customer Budgets.
ARCategory1, ARCategory2
Returns the AR categories set for the company.
ARContact
Returns details for a specified AR Contact or for all AR Contacts.
ARCustomer
Returns details for a specified Customer or for all Customers.
ARCustomer/
Printsheet
Print a Customer Sheet.
ARCustomerGroup
Returns details for a specified Customer Group or for all Customer Groups.
ARCustomerList
Returns details for a specified Customer or for all Customers.
ARMemo
Returns a memo for specified Memo ID or for all AR Memos.
ARSalesArea
Returns details for a specified Sales Area or for all Sales Areas.
ARSalesAreaBudget
Returns budget details for AR Sales Area Budgets.
ARSalesGroup
Returns details for a specified Sales Group or for all Sales Groups.
ARSalesGroupBudget
Returns budget details for AR Sales Group Budgets.
ARSalesPerson
Returns details for a specified Sales Person or for all Sales People.
ARSalesPersonBudget
Returns budget details for AR Sales Person Budgets.
ARTransaction
Returns details for a given AR Transaction ID or for all AR Transactions.
ARTransaction/
Print
Prints an AR Transaction for a given AR Transaction ID. Only Receipt transactions can be printed.
See Also
Web Service Actions and Functions

---

## BaseCurrencyCode - Web Service Function

Source: https://accredo.co.nz/webhelp/BaseCurrencyCodeWSFunction.htm

BaseCurrencyCode - Web Service Function
BaseCurrencyCode: String
Base Currency Code Web Service function returns the Company Base Currency Code.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("BaseCurrencyCode")
See Also
Company Web Service Actions and Functions

---

## CB Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/CBWebServiceActionsAndFunctions.htm

CB Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
CBAnalysisBudget
Returns budget details for CB Analysis Budgets.
CBAutomaticPayment
Returns details for a specified Automatic Payment or for all Automatic Payments.
CBBankAccount
Returns details for a specified Bank Account or for all Bank Accounts.
CBBankingItems
Returns details for a specified Banking Item or for all Banking Items.
CBBankingSummary
Returns details for a specified Banking Summary or for all Banking Summaries.
CBBankList
Returns details for a specified Bank Account or for all Bank Accounts.
CBCategory1, CBCategory2
Returns the CB categories set for the company.
CBExpenseCode
Returns details for a specified CB Analysis Code or for all CB Analysis Codes.
CBMemo
Returns a memo for specified Memo ID or for all CB Memos.
CBRule
Returns details for a specified CB Rule or for all CB Rules.
CBRuleList
Returns details for a specified CB Rule or for all CB Rules.
CBStatement
Returns details for a specified CB Statement or for all CB Statements.
CBStatement/
Print
Prints a Statement for a given Statement ID.
CBTransaction
Returns details for a specified CB Transaction or for all CB Transactions.
See Also
Web Service Actions and Functions

---

## Company - Web Service Function

Source: https://accredo.co.nz/webhelp/CompanyWSFunction.htm

Company - Web Service Function
Company: String
Company Web Service function returns a JSON object containing the Company details.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("Company")
See Also
Company Web Service Actions and Functions

---

## Company Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/CompanyWebServiceActionsAndFunctions.htm

Company Web Service Actions and Functions
The following company actions can be performed via the Web Service.
This list some of the end points available. See the
Metadata Properties
link for a list of all end points for specific properties for each end point.
Function
Description
AddPeriod
Adds a given Offset number of periods to a given period, optionally excluding adjustment periods.
AppName
Returns Mercury or Saturn, depending on the application running the Web Service.
Autodoc
Returns the automated documentation for Action and Function end points.
BaseCurrencyCode
Returns the base currency code for the Company.
COAddress
Returns all the delivery addresses for the Company.
COBankingMedia
Returns all the Banking Media set in the Company.
COBranch
For Accredo Saturn, returns details of the branches in the Company.
CODepartment
For Accredo Saturn, returns details of the departments in the Company.
COFXCurrency
Returns details of the FX currencies set in the Company.
COCurrencyRateType
Returns details of the FX currency rate types set.
COLinkCategory1, COLinkCategory2, COMOCategory1, COMOCategory2
Returns the Link or Memo categories set for the company.
COMemo
Returns details of the Company memos.
Company
Returns the Company Details.
CONarrative
Returns narratives in the Global Narrative List.
CORecoveryLog
Returns details in the File Recovery Log Viewer.
COUser
Returns details of the company Users, Groups and Roles.
CurrentPeriod
Returns the current period for a given module.
CustomTable
Returns all records in a given custom table.
DefaultBranchCode
For Accredo Saturn, returns the Default Branch Code for the User.
DefaultDepartmentCode
For Accredo Saturn, returns the Default Department Code for the User.
DefaultLocationCode
For Accredo Saturn, returns the Default Location Code for the User.
Enum
Returns all Enum types and their available values.
ExecuteSQL
Executes an SQL Query script located on the host.
FieldDependency
Returns field dependencies for Documents, Document Template (Dot), Graph or Validation (Validate), for a given Entity.
FirstUserPeriod
Returns the first available period for a given Module, for a specified User.
GetExchangeRate
Returns the exchange rate for a given Currency Code, Rate Type and Date.
GetPrimaryKey
Returns the primary key of a given sub-object.
GetUserCompanyList
Returns a list of the companies available to the requesting user.
ICAvailable
Used to query stock availability.
Image
Returns an image from a given image path.
LastUserPeriod
Returns the last available period for a given Module, for a specified User.
ModuleAvailable
Returns True if the given module is available.
openapi.json
Returns a JSON OAS output containing endpoints.
PeriodForDate
Returns the period a given date occurs in.
PlayLayout
Run a report layout to a disk file.
PlayScript / PlayReportScript
Executes a MaxBasic script that exists on the host, in a given Output Style.
ReportLayout
Returns details of all report layouts.
Settings
Returns all the settings with their values for the company.
ScriptDoc
Returns the objects that can be scripted.
SystemDate
Returns the current system date.
SystemPeriod
Returns the current system period.
User
Returns the user details for the logged in user.
UserSettings
Returns the settings and permissions for the logged in user.
In This Section
About - Web Service Function
AddPeriod - Web Service Function
AppName - Web Service Function
BaseCurrencyCode - Web Service Function
Company - Web Service Function
CurrentPeriod - Web Service Function
DefaultBranchCode - Web Service Function
DefaultDepartmentCode - Web Service Function
DefaultLocationCode - Web Service Function
Enum - Web Service Function
FieldDependency - Web Service Function
FirstUserPeriod - Web Service Function
GetExchangeRate - Web Service Function
GetPrimaryKey - Web Service Function
GetUserCompanyList - Web Service Function
GSTRate - Web Service Function
ICAvailable - Web Service Function
Image - Web Service Function
LastUserPeriod - Web Service Function
ModuleAvailable - Web Service Function
openapi.json - Web Service Function
PeriodForDate - Web Service Function
PlayLayout - Web Service Function
PlayScript / PlayReportScript - Web Service Function
ReportLayout - Web Service Function
ScriptDoc - Web Service Function
SystemDate - Web Service Function
SystemPeriod - Web Service Function
User - Web Service Function
See Also
Web Service Actions and Functions

---

## CurrentPeriod - Web Service Function

Source: https://accredo.co.nz/webhelp/CurrentPeriodWSFunction.htm

CurrentPeriod - Web Service Function
CurrentPeriod(ModuleCode=
String
): Number
Current Period Web Service Function returns the current period ID for the Module.
CurrentPeriod function syntax has these named arguments:
Parameter
Description
Module Code
Required. Module to return the current period for.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("CurrentPeriod(ModuleCode=GL)")
See also the MaxBasic
CurrentPeriod
Function and the SQL
CurrentPeriod
function.
See Also
Company Web Service Actions and Functions

---

## Custom Tables via Web Service

Source: https://accredo.co.nz/webhelp/WSCustomTables.htm

Custom Tables via Web Service
There are a couple of important things to take note of if you are trying to access a Custom Table via the Web Service.
Table Naming
If a custom table name has any of the following characters or contains spaces that table will not be included in the metadata for the WebService -''#@$^!%&(),;.[]{}`~+=
We recommend table names contain only alphanumeric characters and underscores.
Tables Indexes
For Custom Tables to work correctly in the Webservice there has to be a single field that uniquely defines each row.
That field should be indexed and marked as Primary. The index should only include that field.
When the web service is 'handling' a custom table it will determine the identifier Field as follows:
Inspect the indexes to find one marked Primary, if it finds one it will use the first field in the Primary index, if it does not find a primary index it will use the first field.

---

## DefaultBranchCode - Web Service Function

Source: https://accredo.co.nz/webhelp/DefaultBranchCodeWSFunction.htm

DefaultBranchCode - Web Service Function
Branch Codes are only available in Accredo Saturn.
DefaultBranchCode: String
Default Branch Code Web Service function returns the default Branch Code for the current user.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("DefaultBranchCode")
See Also
Company Web Service Actions and Functions

---

## DefaultDepartmentCode - Web Service Function

Source: https://accredo.co.nz/webhelp/DefaultDepartmentCodeWSFunction.htm

DefaultDepartmentCode - Web Service Function
Department Codes are only available in Accredo Saturn.
DefaultDepartmentCode: String
Default Department Code Web Service function returns the default Department Code for the current user.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("DefaultDepartmentCode")
See Also
Company Web Service Actions and Functions

---

## DefaultLocationCode - Web Service Function

Source: https://accredo.co.nz/webhelp/DefaultLocationCodeWSFunction.htm

DefaultLocationCode - Web Service Function
DefaultLocationCode: String
Default Location Code Web Service function returns the default Location Code for the current user.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("DefaultLocationCode")
See Also
Company Web Service Actions and Functions

---

## Deleting a Web Service Token

Source: https://accredo.co.nz/webhelp/WSDeleteTokens.htm

Deleting a Web Service Token
When a user logs out of Web Services, you can use MaxBasic to delete the token.
The Http Delete method will return a Response Code of 204 for a successful deletion, or 401 if the token is not found or not the appropriate type.
The following example function will delete a given access Token.
Note: You can change
accesstokens
to
refreshtokens
to delete a refresh token.
const URL = "InsertURLAsStringHere"	'Note: Add required URL here
'For example "http://YOUR_AUTH0_DOMAIN/oauth/"
Function DeleteCall(Token as String)
Dim Http as Object
Http = CreateObject("Accredo.HttpRequest")
Dim FinalUrl as String
FinalUrl = URL & "accesstokens/" & Token
'  FinalUrl = URL & "refreshtokens/" & Token
FinalURL = URLEncode(FinalURL)
Http.URL = FinalURL
Http.ContentType = "application/json"
Dim Resp as String
Resp = Http.Delete
If Http.ResponseCode = 204 Then
Msgbox ("Token " & Token & " successfully deleted")
ElseIf Http.ResponseCode = 401 Then
Msgbox ("Token " & token & " not found or not appropriate type")
Else
Error ("Error making request. " & Http.ResponseCode & " - " & Http.ResponseText)
End If
End Function
See Also
Web Service

---

## Demo System Web Service Setup

Source: https://accredo.co.nz/webhelp/WSDemoServiceSetup.htm

Demo System Web Service Setup
Follow the instructions below to access an Accredo demo system via the Web Service. You must have the Web Service module installed.
Web Service Installation
See the
installation guide
for steps to install the service and perform the initial configuration.
Note: The server installation of the Accredo has OAuth2 enabled. The demo system does not which allows unauthenticated access to the data.
Testing the Web Service
If the Web Service has been configured successfully, try opening the following links in your browser.
http://localhost:6567/saturn/odata4/v1/company('demo')/developerdoc
http://localhost:6567/saturn/odata4/v1/company('demo')/ARCustomerList
http://localhost:6567/saturn/odata4/v1/company('demo')/ARCustomer('ASHENG')
http://localhost:6567/mercury/odata4/v1/company('demo')/developerdoc
http://localhost:6567/mercury/odata4/v1/company('demo')/ARCustomerList
http://localhost:6567/mercury/odata4/v1/company('demo')/ARCustomer('ASHENG')
See Also
Web Service

---

## Enum - Web Service Function

Source: https://accredo.co.nz/webhelp/EnumWSFunction.htm

Enum - Web Service Function
Enum[('EnumType as String')]: Object
Enum[?$Select=Value as String]: Object
Enum Web Services function returns a JSON object containing a set of Enum text values.
There are several ways to use the Enum function. See
Web Service Functions
for sample code to access Web Services.
To return all Enum values as a JSON object:
Response = MakeCall("Enum")
To return a list of available Enum Types as a JSON Object:
Response = MakeCall("Enum?$Select=EnumType")
To return the Enum values for a specified Enum Type, for example CompanyType,  as a JSON object:
Response = MakeCall("Enum('CompanyType')")
See Also
Company Web Service Actions and Functions

---

## FA Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/FAWebServiceActionsAndFunctions.htm

FA Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
FAAsset
Returns details for a specified FA Asset or for all FA Assets.
FAAssetBook
Returns details for a specified FA Asset Book or for all FA Asset Books.
FAAssetGroup
Returns details for a specified FA Asset Group or for all FA Asset Groups.
FAAssetList
Returns details for a specified FA Asset or for all FA Assets.
FAAssetLocation
Returns details for a specified FA Asset Location or for all FA Asset Locations.
FACategory1, FACategory2
Returns the FA categories set for the company.
FADepreciationDefaults
Returns depreciation default details for a specified FA Asset Book or for all FA Asset Books.
FAMemo
Returns a memo for specified Memo ID or for all FA Memos.
FATransaction
Returns details for a specified FA Transaction or for all FA Transactions.
See Also
Web Service Actions and Functions

---

## FieldDependency - Web Service Function

Source: https://accredo.co.nz/webhelp/FieldDependencyWSFunction.htm

FieldDependency - Web Service Function
FieldDependency/{Type}[(Entity=
String
)]: Object
Field Dependency Web Service Function returns field dependencies for Documents, Dots, Graphs or Validate.
Use one of the following types:
FieldDependency/Document
FieldDependency/Dot
FieldDependency/Graph
FieldDependency/Validate
FieldDependency function syntax has these named arguments:
Parameter
Description
Type
Required. Select from
Document
,
Dot
,
Graph
or
Validate
.
Entity
Optional. Enter an Accredo Data Type to return field dependencies for one entity.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("FieldDependency/Document(Entity=JCTRANSACTION)")
See Also
Company Web Service Actions and Functions

---

## FirstUserPeriod - Web Service Function

Source: https://accredo.co.nz/webhelp/FirstUserPeriodWSFunction.htm

FirstUserPeriod - Web Service Function
FirstUserPeriod(ModuleCode=
String
[, UserCode=
String
]): Number
First User Period Web Service function returns the first period in which the logged in User may post transactions in the specified module. If the UserCode is supplied, it returns the first available period for that user.
FirstUserPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the first user period for.
User Code
Optional. The User Code to return the first period for the module for.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("FirstUserPeriod(ModuleCode=GL,UserCode=Accredo)")
See also the MaxBasic
FirstUserPeriod
function and the SQL
FirstUserPeriod
function..
See Also
Company Web Service Actions and Functions

---

## GetExchangeRate - Web Service Function

Source: https://accredo.co.nz/webhelp/GetExchangeRateWSFunction.htm

GetExchangeRate - Web Service Function
GetExchangeRate(CurrencyCode=
String
,RateType=
String
,Date=
Date
]): Number
Get Exchange Rate Web Services function returns the Exchange Rate for a given CurrencyCode, Rate Type and Date. Returns zero if no rate found.
GetExchangeRate function syntax has these named arguments:
Parameter
Description
Currency Code
Required. The currency code to get the rate for.
Rate Type
Required. The type of exchange rate.
Date
Required. The effective date for the exchange rate. Date must be in the format YYYY-MM-DD.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("GetExchangeRate(CurrencyCode=AUD,RateType=SELL,Date=2018-01-01)")
See also the MaxBasic
GetExchangeRate
Function and the the SQL
GetExchangeRate
function.
See Also
Company Web Service Actions and Functions

---

## GetPrimaryKey - Web Service Function

Source: https://accredo.co.nz/webhelp/GetPrimaryKeyWSFunction.htm

GetPrimaryKey - Web Service Function
GetPrimaryKey(Entity=
String
): Object
Get Primary Key Web Service Function returns the primary key for an entity subobject.
GetPrimaryKey function syntax has these named arguments:
Parameter
Description
Entity
Required. Enter the entity in the form Entity.Subobject.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("GetPrimaryKey(Entity=JCTRANSACTION.Line)")
See Also
Company Web Service Actions and Functions

---

## GetUserCompanyList - Web Service Function

Source: https://accredo.co.nz/webhelp/GetUserCompanyListWSFunction.htm

GetUserCompanyList - Web Service Function
GetUserCompanyList: Object
Get User Company List returns a list of companies available to the requesting User.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("GetUserCompanyList")
See Also
Company Web Service Actions and Functions

---

## GL Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/GLWebServiceActionsAndFunctions.htm

GL Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
GLAccount
Returns details for a specified GL Account or for all GL Accounts.
GLAccountList
Returns details for a specified GL Account or for all GL Accounts.
GLBatch
Returns details for a specified GL Batch or for all GL Batches.
GLCategory1, GLCategory2
Returns the GL categories set for the company.
GLMemo
Returns a memo for specified Memo ID or for all GL Memos.
GLSubsidiary
Returns details for a specified GL Subsidiary or for all GL Subsidiaries.
GLTransaction
Returns details for a specified GL Transaction or for all GL Transactions.
See Also
Web Service Actions and Functions

---

## GST Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/GSTWebServiceActionsAndFunctions.htm

GST Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
GSTCodes
Returns details for a specified GST Code or for all GST Codes.
GSTRate
Returns rate details for a specified GST Code and Date.
GSTTransaction
Returns details for a specified GST Transaction or for all GST Transactions.
See Also
Web Service Actions and Functions

---

## GSTRate - Web Service Function

Source: https://accredo.co.nz/webhelp/GSTRateWSFunction.htm

GSTRate - Web Service Function
GSTRate[(GSTCode=
String
,Date=
Date
)]: Number
GST Rate Web Services function returns the current GST amount for a given GST Code and Date. If Code is empty, the rate for the default GST code is returned. If Date is not specified then the current Accounting System Date date is used.
GSTRate function syntax has these named arguments:
Parameter
Description
GST Code
Optional. The GST Code to return the rate for.
Date
Optional. The effective date to return the rate for. Date must be in the format YYYY-MM-DD.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("GSTRate(GSTCode=1,Date=2016-01-01)")
See also the MaxBasic
GSTRate
Function and the SQL
GSTRate
function.
See Also
Company Web Service Actions and Functions

---

## IC Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/ICWebServiceActionsAndFunctions.htm

IC Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
ICBudget
Returns budget details for IC Product Budgets.
ICCategory1, ICCategory2
Returns the IC categories set for the company.
ICComponent
Returns the component details for a given Product Code.
ICLocation
Returns details for a specified IC Location or for all IC Locations.
ICManufacture
Returns details for a specified Manufacture ID.
ICMemo
Returns a memo for specified Memo ID or for all IC Memos.
ICProduct
Returns details for a specified Product or for all Products.
ICProduct/
Print
Prints an IC Product for a given Product Code.
ICProductList
Returns details for a specified Product or for all Products.
ICStockGroup
Returns details for a specified Stock Group or for all Stock Groups.
ICStocktake
Returns details for a specified Stocktake or for all Stocktakes.
ICStocktakeCount
Returns details for a specified Stocktake Count or for all Stocktake Counts.
ICTransaction
Returns details for a given IC Transaction ID or for all IC Transactions.
ICTransfer
Returns details for a given IC Transfer or for all IC Transfers.
ICTransferList
Returns details for a given IC Transfer or for all IC Transfers.
ICUOMGroup
Returns details for a given UOM Group or for all UOM Groups.
See Also
Web Service Actions and Functions

---

## ICAvailable - Web Service Function

Source: https://accredo.co.nz/webhelp/ICAvailableWSFunction.htm

ICAvailable - Web Service Function
ICAvailable(SourceModule=
String
, SourceID=
Number
, LineID=
Number
, DocumentClass=
String
[, QuantitySupplied=
Number
, CustomerCode=
String
, UOMCode=
String
, QuantityOrdered=
Number
], AfterLines=
Number
): Object
IC Available Web Service Action returns the availability of stock.
ICAvailable function syntax has these named arguments:
Parameter
Description
SourceModule
Required. Module requesting the stock availability.
SourceID
Required. The document ID within the source module.
LineID
Required. The document Line number.
DocumentClass
Required. The class of document requesting the availability.
QuantitySupplied
Optional. The number supplied.
CustomerCode
Optional. The document customer code. Used to determine if back ordering is acceptable.
UOMCode
Optional The product UOM code.
QuantityOrdered
Optional. The number ordered.
AfterLines
Required. This is made up of:
LineID=
Number
(Required)
LineType=
String
(Required)
ProductCode=
String
(Required)
LocationCode=
String
(Required)
QuantitySupplied=
Number
(Required)
QuantityOrdered=
Number
(Optional)
QuantityBackOrdered=
Number
(Optional)
A sample request is:
{
"SourceModule":"IN",
"SourceID":-1,
"DocumentClass": "I",
"LineID":-1,
"QuantitySupplied":0,
"AfterLines":
[{"LineID":-1,"LineType":"A", "ProductCode":"BEDSUITE", "LocationCode":"CHCH", "QuantitySupplied":2}
]
}
The Results response returned contains an array of lines with the following:
Field
Description
LineID
Response line ID.
ProductCode
Product code.
LocationCode
Location of the product.
QuantitySupplied
Quantity of the product supplied.
QuantityAvailable
Quantity of the product available at the location.
Message
Any message returned regarding product quantities.
A sample response is:
{
"Results": [{
"LineID": 2461,
"ProductCode": "1.8MWARDROBE",
"LocationCode": "CHCH",
"QuantitySupplied": 17,
"QuantityAvailable": 2,
"Message": "Insufficient Product '1.8MWARDROBE'"
}]
}
See
Web Service Functions
for sample code to access Web Services.
See Also
Company Web Service Actions and Functions

---

## Image - Web Service Function

Source: https://accredo.co.nz/webhelp/ImageWSFunction.htm

Image - Web Service Function
Image(ImagePath=
String
[,Intent=
String
, FileName=
String
]): Object
Image Web Services function returns the Image specified in Image Path. You can optionally specify the Intent as inline or attachment.
Image function syntax has these named arguments:
Parameter
Description
Image Path
Required. The path of the image file.
Intent
Optional. Specify the delivery intent from
Inline
or
Attachment
. Defaults to Inline.
Filename
Optional. For Attachment images, specify the filename where the image will be saved.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("Image(ImagePath=picfile.jpg,Intent=Inline)")
See Also
Company Web Service Actions and Functions

---

## IN Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/INWebServiceActionsAndFunctions.htm

IN Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
INCategory1, INCategory2
Returns the IN categories set for the company.
INInvoice
Returns details for a specified Invoice or for all Invoices.
INInvoice/
Post
Posts an Invoice for a Bank Account, with options for Bank Through and Cash Sale.
INInvoice/
Print
Prints an IN Invoice for a given Invoice ID, with option to specify if it is a Cash Sale.
INInvoiceList
Returns details for a specified Invoice or for all Invoices.
INMemo
Returns a memo for specified Memo ID or for all IN Memos.
INShipper
Returns details for a specified IN Shipper or for all IN Shippers.
In This Section
Post - Web Service Function
See Also
Web Service Actions and Functions

---

## JC Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/JCWebServiceActionsAndFunctions.htm

JC Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
JCBatch
Returns details for a specified JC Batch or for all JC Batches.
JCBudget
Returns budget details for Job Budgets.
JCCategory1, JCCategory2
Returns the JC categories set for the company.
JCComponent
Returns details for a specified JC Component or for all JC Components.
JCCostCentre
Returns details for a specified JC Cost Centre or for all JC Cost Centres.
JCDisbursement
Returns details for a specified JC Batch or for all JC Batches.
JCInvoiceAmounts
Returns document details for a specified Job or for all Jobs.
JCJob
Returns details for a specified Job or for all Jobs.
JCJob/
Print
Prints a Job Sheet for a given JC Job Code.
JCJob/Quote
Prints a Quotation for a given JC Job Code.
JCJobGroup
Returns details for a specified Job Group or for all Job Groups.
JCJobList
Returns details for a specified Job or for all Jobs.
JCMemo
Returns a memo for specified Memo ID or for all JC Memos.
JCTimesheet
Returns details for a specified JC Batch or for all JC Batches.
JCDisbursement
Returns details for a specified JC Batch or for all JC Batches.
JCTransaction
Returns details for a given JC Transaction ID or for all JC Transactions.
See Also
Web Service Actions and Functions

---

## LastUserPeriod - Web Service Function

Source: https://accredo.co.nz/webhelp/LastUserPeriodWSFunction.htm

LastUserPeriod - Web Service Function
LastUserPeriod(ModuleCode=
String
[, UserCode=
String
]): Number
Last User Period Web Service function returns the last period in which the logged in User may post transactions in the specified module. If the UserCode is supplied, it returns the last available period for that user.
LastUserPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the last user period for.
User Code
Optional. The User Code to return the last period for the module for.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("LastUserPeriod(ModuleCode=GL,UserCode=Accredo)")
See also the MaxBasic
LastUserPeriod
function and the SQL
LastUserPeriod
function.
See Also
Company Web Service Actions and Functions

---

## Live System Web Service Setup

Source: https://accredo.co.nz/webhelp/WSLiveServiceSetup.htm

Live System Web Service Setup
Configuration Requirements
The Accredo Web Service module will need to be purchased and installed into the Accredo System and enabled for any companies you want to access.
A server running a 64 bit operating system (Windows Server 2016 or newer recommended).
Microsoft Internet Information Services installed - recommended.
A reverse proxy (example: Nginx server or appliance, or IIS server) - strongly recommended where external access is enabled.
Domain name for use with the Web Service - required for external access, recommended for internal only access.
Appropriate external and internal DNS entries for redirecting traffic to the Accredo Web Service.
Valid SSL certificate that matches your domain - required for external access, recommended for internal only access.
Your domain name will need to be configured to point at your Accredo server and the SSL certificate will need to be bound to the ports configured for the service. For ease of configuration, we recommend IIS (Microsoft Internet Information Services) be used to install the certificate and bind it to the Web Service ports.
Depending on whether you will be configuring mixed internal and external, or internal only access to the Web Service, you will need to configure the appropriate internal and/or external DNS entries so that the service is reachable with your domain.
For external use you will also need to ensure that web traffic is allowed though your network boundary in a secure manner. In this instance we strongly recommend the use of a reverse proxy server or other secure transport methods to help prevent unauthorised access to your server. Both Nginx as an appliance or server, or IIS as a server are suitable for use as a reverse proxy. When using a reverse proxy, you will need to ensure the X-Forwarded-Host header is being set and forwarding the external host to the web service, in IIS this is a Server Variable that is added to the inbound rewrite rule. Otherwise you need to configure the Web Service to rewrite this, see Step 3 below.
Accredo Business Software Ltd makes no recommendations on specific network configuration and you should consult with an experienced and qualified IT professional.
In this guide,
demo.accredo.co.nz
is used to represent the domain you will have set up for use with the Web Service.
Web Service Installation
See the
installation guide
for steps to install the service and perform the initial configuration.
Note: The server installation of the Accredo has OAuth2 enabled, while the demo system does not.
Note: If you intend to access the Accredo COM object via scripting triggered from the Web Service, you will need to change the AccredoSaturnWeb or AccredoMercuryWeb Windows Service to run as a Domain user with appropriate permission.
Windows Regional Settings
Ensure that date settings for the Windows system accounts are set to dd/MM/yyyy. You can do this by correctly setting the date format for the current user and then copying it to the system accounts:
Windows Control Panel > Region > Administrative Tab > Copy Settings > Check both check boxes > OK
Testing the Web Service
To access your own server, use the following links. Replace
demo.acredo.co.nz
with your domain, and
DEMO
with the Company Code of the Accredo company you are connecting to.
For Saturn:
https://demo.accredo.co.nz:6569/saturn/odata4/v1/company('demo')/developerdoc
For Mercury:
https://demo.accredo.co.nz:6569/mercury/odata4/v1/company('demo')/developerdoc
This should display an error message of "invalid access token". This means you are successfully able to communicate with the Web Service. The OAuth2 token end point will be located at:
For Saturn:
https://demo.accredo.co.nz:6569/saturn/oauth2/v1/token
For Mercury:
https://demo.accredo.co.nz:6569/mercury/oauth2/v1/token

---

## Memos via Web Service

Source: https://accredo.co.nz/webhelp/MemosViaWebService.htm

Memos via Web Service
You can read, create and write to memos via the Web Service. The following examples show how to manipulate Memos via the Web Service using MaxBasic code.
Retrieve a Memo
The following MaxBasic Code will print details of a Memo with Memo ID
1
from the Web Service, using a
GET
request to retrieve information. Enter the required URL for your target company in line 3.
Dim HTTPRequest as Object
HTTPRequest = CreateObject("Accredo.HttpRequest")
URL = "
ADD URL STRING HERE
"
EndPoint = "/ARMemo('1')?$Select=MemoID,AccountCode,Memo&$Expand=Memo"
Dim MyURL as String
MyURL = URL & Endpoint
HTTPRequest.URL = MyURL
HTTPRequest.ContentType = "application/json"
Dim Resp as string
Resp = HTTPRequest.Get
If HTTPRequest.ResponseCode = 200 or HTTPRequest.ResponseCode = 201 or HTTPRequest.ResponseCode = 202 Then
Dim Json as Object
If Resp <> "" Then
Json = ParseJSON(Resp)
Print JSONStringify(Json)
End If
End If
Create a Memo
The following MaxBasic Code will create a Memo via the Web Service, using a
POST
request. Enter the required URL for your target company in line 3.
Dim HTTPRequest as Object
HTTPRequest = CreateObject("Accredo.HttpRequest")
URL = "
ADD URL STRING HERE
"
EndPoint = "/ARMemo"
MemoObject = JSONCreateObject
MemoObject.AccountFile = "ARCUST"
MemoObject.AccountCode = "BOWEN"
MemoObject.Subject = "WS Test Full"
MemoObject.MemoType = "M"
MemoObject.Reference = "Another Test"
MemoTextObject = JSONCreateObject(MemoObject, "Memo")
MemoTextObject.Text = "Hello from Web Service"
Data = JSONStringify(MemoObject)
MyURL = URL & Endpoint
HTTPRequest.URL = MyURL
HTTPRequest.Post(Data)
Update a Memo
To update a Memo (or other entity) you will first need to ascertain the ETag for the memo record. The ETag shows the version of the record, like a record revision number. To retrieve an ETag for the Memo with Memo ID
1
, use the following MaxBasic Code. Enter the required URL for your target company in line 4.
Dim HTTPRequest as Object
HTTPRequest = CreateObject("Accredo.HttpRequest")
MemoID = 1
URL = "
ADD URL STRING HERE
"
EndPoint = "/ARMemo('" & MemoID & "')"
MyURL = URL & EndPoint
HTTPRequest.URL = MyURL
ReturnedBody = HTTPRequest.Get
If HTTPRequest.ResponseCode = 200 or HTTPRequest.ResponseCode = 201 or HTTPRequest.ResponseCode = 202 Then
JsonObject = ParseJSON(ReturnedBody)
etag = JsonObject["@odata.etag"]
End If
Once you have the ETag for a record, you can update the record using a
PATCH
request. The following MaxBasic Code will update the text in the Memo with Memo ID
1
, using the etag variable obtained. Enter the required URL for your target company in line 3.
Dim HTTPRequest as Object
HTTPRequest = CreateObject("Accredo.HttpRequest")
URL = "
ADD URL STRING HERE
"
EndPoint = "/ARMemo('1')"
obj = JSONCreateObject
obj2 = JSONCreateObject(obj, "Memo")
obj2.Text = "Hello from Web Service again"
Data = JSONStringify(obj)
MyURL = URL & Endpoint
HTTPRequest.URL = MyURL
HTTPRequest.SetRequestHeader("If-Match", etag)
HTTPRequest.PATCH(Data)
See Also
Web Service

---

## ModuleAvailable - Web Service Function

Source: https://accredo.co.nz/webhelp/ModuleAvailableWSFunction.htm

ModuleAvailable - Web Service Function
ModuleAvailable(ModuleCode=
String
): Boolean
Module Available Web Service function returns True if the module specified by ModuleCode is installed in the Company, or returns False.
ModuleAvailable function syntax has these named arguments:
Parameter
Description
Module Code
Required. The module code to be evaluated.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("ModuleAvailable(ModuleCode=IC)")
Modules codes available are:
AR
- Accounts Receivable
IC
- Inventory Control
IN
- Invoicing System
OE
- Order Entry
AP
- Accounts Payable
PO
- Purchase Orders
CB
- Cash Book
FA
- Fixed Assets
GL
- General Ledger
GST
- Goods and Service Tax
JC
- Job Costing
SP
- Special Pricing
SA
- Sales Analysis
PA
- Purchase Analysis
JA
- Job Analysis
DI
/
EDI
- Data Interchanges
RD
- Report Designer
FD
- Form Designer
TD
- Table Designer
FX
- Foreign Exchange
CO
- Company
See also the MaxBasic and SQL
ModuleAvailable
Function.
See Also
Company Web Service Actions and Functions

---

## OData Filter Editor

Source: https://accredo.co.nz/webhelp/ODataFilterEditor.htm

OData Filter Editor
Navigator > Setup > Company > Configuration > Mobile App Filtering >
Filter
Apply a filter to restrict rows in a table available to a mobile app.
Filter Tab
Any Selection
Selected,
a record need only match one of the conditions.
Clear
, a record must match all filter conditions.
Field Name
Enter or use the drop-down to select the fields in the data file for filtering.
Op
The Operator. When combined with search criteria, the operator defines a condition that a record must satisfy to be selected. Operators can be typed or selected from the drop-down. If this is blank and you enter selection criteria, the default operator is
=
(equal to). See
Operator Meanings and Rules
below.
Criteria
Values that the operator in the
Op
field are applied to. To search for records that have no entry for a field, use the operator
=
and leave the
Criteria
field blank. For some fields, criteria can be selected from a drop-down list.
You can use the
?
and
*
wildcard characters
. For alpha-numeric fields, upper and lower case are ignored.
For Date fields, all the numeric operators except
+-
can be used. To search for a date in relation to the System Date, enter
DATE
, followed by
+
or
-
, then the number of days before or after the System Date to search for. For example,
DATE-7
would be one week prior to the System Date.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert an item at the selected line.
Move
(Shift+Up) (Shift+ Down)
Select an item and move it higher or lower on the list.
Delete
(F3)
Delete the selected item.
Clear Filter
(Ctrl+F3)
Clear the selected filter.
Buttons
Save
(F9)
Save and exit the window.
Cancel
(Esc)
Discard changes and exit the window.
See also
Filter & Sort
.
See Also
Mobile App Filtering

---

## OE Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/OEWebServiceActionsAndFunctions.htm

OE Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
OEMemo
Returns a memo for specified Memo ID or for all OE Memos.
OEOrder
Returns details for a specified Order or for all Orders.
OEOrder/GenerateInvoice
Generate an Invoice for a given Order ID.
OEOrder/
Print
Prints an OE Order for a given Order ID.
OEOrderList
Returns details for a specified Order or for all Orders.
See Also
Web Service Actions and Functions

---

## openapi.json - Web Service Function

Source: https://accredo.co.nz/webhelp/openapi_json.htm

openapi.json - Web Service Function
The openapi.json endpoint returns generated OAS (OpenAPI Specification) metadata output. The output is in OAS Version 2 JSON format.
OAS is a standard format used to present web endpoints. The open source Swagger Editor can be used to view and test the file.
Note: OpenAPI is not fully compatible with OData and there are differences between the generated documentation for OpenAPI and the correct query and parameter structure for OData. This endpoint is provided as a convenience only.
See Also
Company Web Service Actions and Functions

---

## PeriodForDate - Web Service Function

Source: https://accredo.co.nz/webhelp/PeriodForDateWSFunction.htm

PeriodForDate - Web Service Function
PeriodForDate(Date=
Date
): Number
Period For Date Web Service function returns the Period ID of the period containing Date. If no period contains Date then 0 is returned. Date must be in the format
YYYY-MM-DD
.
PeriodForDate function syntax has these named arguments:
Parameter
Description
Date
Required. The Date to find the Period ID for. Date must be in the format YYYY-MM-DD.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("PeriodForDate(Date=2017-01-01)")
See also the MaxBasic
PeriodForDate
function and the SQL
PeriodForDate
function.
See Also
Company Web Service Actions and Functions

---

## PlayLayout - Web Service Function

Source: https://accredo.co.nz/webhelp/PlayLayoutWSFunction.htm

PlayLayout - Web Service Function
PlayLayout(ReportName=
String,
LayoutName=
String
[,FileName=
String
,Format=
String
,Selections=
String
]): Object
Play Layout Web Services function runs the report with ReportName using LayoutName to a disk file. Optionally specify a File Name for the report to be saved to, and optionally specify a file Format. You can also optionally specify other parameters that are valid for the report.
Use the
ScriptDoc
Endpoint to retrieve a list of available Reports.
PlayLayout function syntax has these named arguments:
Parameter
Description
Report Name
Required. The report to run.
Layout Name
Required. The layout for the report.
File Name
Optional. The name to save the report file as.
Format
Optional. The report format. Defaults to
Adobe PDF
. Select from:
Adobe PDF
CSV File
Tab Delimited File
Quoted CSV File
Excel XLSX File
Selections
Optional. Any other parameters valid for the report.
For example:
/playlayout(ReportName='ARCustomerReport',LayoutName='Customer',FileName='MyFileName.pdf',CustomerGroup='0000')
See Also
Company Web Service Actions and Functions

---

## PlayScript / PlayReportScript - Web Service Function

Source: https://accredo.co.nz/webhelp/PlayScriptWSFunction.htm

PlayScript / PlayReportScript - Web Service Function
PlayScript(ScriptFileName=
String
,OutputStyle=
String
,ScriptArgsn=
String
): Object - OR -
PlayReportScript(ScriptFileName=
String
,OutputStyle=
String
,ScriptArgsn=
String
): Object
Play Script and Play Report Script Web Services functions play a given script with a given output style and Script Argsn. PlayScript and PlayReportScript will only work for scripts with file extension
.pfs
, and scripts that exist on a relevant script path.
Use the
ScriptDoc
Endpoint to retrieve a list of available Reports.
All MaxBasic functions in scripts can be compiled. The
ScriptDoc
endpoint lists the functions available to the web service. Functions listed in the ScriptDoc output as
Not supported by Web Service
can be compiled, but will not be executed.
PlayScript and PlayReportScript functions syntax have these named arguments:
Parameter
Description
Script File Name
Required. The script to play.
Output Style
Required. Select from
List,
String
or
JSON.
Script Argsn
Required. The script arguments.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("PlayScript(ScriptFileName=AccredoScript.pfs,OutputStyle=List,ScriptArgsn=0)")
See also the MaxBasic
PlayScript
function.
See Also
Company Web Service Actions and Functions

---

## PO Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/POWebServiceActionsAndFunctions.htm

PO Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
POAuthorisation
Returns details for a specified PO Authorisation Code, or for all PO Authorisation Codes.
POCategory1, POCategory2
Returns the PO categories set for the company.
POMemo
Returns a memo for specified Memo ID or for all PO Memos.
POOrder
Returns details for a specified Order or for all Orders.
POOrder/CreateShipment
Create an AP Shipment for a given Order ID.
POOrder/CreateShipmentInvoiceOnly
Create an Invoice Only AP Shipment for a given Order ID.
POOrder/CreateShipmentReceiptOnly
Create a Receipt Only AP Shipment for a given Order ID.
POOrder/
Print
Prints an PO Order for a given Order ID.
POOrderList
Returns details for a specified Order or for all Orders.
See Also
Web Service Actions and Functions

---

## Post - Web Service Function

Source: https://accredo.co.nz/webhelp/PostWSFunction.htm

Post - Web Service Function
Post(CashSale=
Boolean
,BankThrough=
Boolean
,BankAccountCode=
String
)
The Post Web Service Function posts and invoice. Specify whether to post as a Cash Sale, whether to Bank Through, and the Bank Account to post to.
Post can be used with the following object:
INInvoice - INInvoice/Post
Post function syntax has these named arguments:
Parameter
Description
Cash Sale
Required. When
True
, will be posted as a Cash Sale.
Bank Through
Required. When
True
, Invoice will be automatically banked through.
Bank Account Code
Required. The bank account to post to.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("InInvoice/Post(CashSale=False,BankThrough=True,BankAccountCode=001)")
See Also
IN Web Service Actions and Functions

---

## PP Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/PPWebServiceActionsAndFunctions.htm

PP Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
P
PEnquiry
Returns pricing details for a specified Creditor, Product and Date.
PPRule
Returns rule details for a specified Rule ID or for all Rules.
PPWhat
Returns the What Grid details for a specified Type, or for all What Grid entries.
PPWhere
Returns the Where Grid details for a specified Type, or for all Where Grid entries.
PPWho
Returns the who Grid details for a specified Type, or for all Who Grid entries.
In This Section
PPEnquiry - Web Service Function
See Also
Web Service Actions and Functions

---

## PPEnquiry - Web Service Function

Source: https://accredo.co.nz/webhelp/PPEnquiryWSFunction.htm

PPEnquiry - Web Service Function
PPEnquiry(CreditorCode=
String
,ProductCode=
String
,DocumentDate=
Date
,Quantity=
Number
): Object
PP Enquiry Web Services function returns the pricing details for a given Creditor, Product, Date and Quantity.
PPEnquiry function syntax has these named arguments:
Parameter
Description
Creditor Code
Required. The creditor code to get the pricing for.
Product Code
Required. The product code to get the pricing for.
Document Date
Required. The effective date for the pricing. Date must be in the format YYYY-MM-DD.
Quantity
Required. The Quantity for the pricing.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("PPEnquiry(CreditorCode=RIGHT,ProductCode=T1MPLY,DocumentDate=2025-09-01,Quantity=10)")
See Also
PP Web Service Actions and Functions

---

## Printing via Web Service

Source: https://accredo.co.nz/webhelp/PrintingViaWebService.htm

Printing via Web Service
You can print objects via the Web Service.
Web Service PDF printing requires a local or available default printer. Attempting to Print to PDF Disk File via the Web Service will fail with an HTTP code 500 error if this condition is not met.
Setting a Default Web Service Printer
The default printer is configured through the Web Service Monitor inside the Accredo application.
Network Printers
By default, the Web Service does not recognise networked printers. To print to networked printers you can either:
1. Point a local queue to a network printer, by creating a local port with the relevant IP address of the printer. This is the preferred solution from a security perspective.
Use the Windows Add Printer wizard.
Add a Local Printer directly using manual settings, without adding automatically.
Create a New Port, using type
Standard TCP/IP Port
.
Enter the IP address of the printer, and the Port name.
2. Alternatively, you can change the account used.
Log into Web Services using an account that is a Domain User with access to network printers.

---

## ReportLayout - Web Service Function

Source: https://accredo.co.nz/webhelp/ReportLayoutWSFunction.htm

ReportLayout - Web Service Function
ReportLayout: Object
The
/ReportLayout
endpoint retrieves report layout information. This can be used with the PlayLayout endpoint.
Use
/ReportLayout?$Expand=Selections
to show the Selections sub-object for the layouts.
Use
/ReportLayout?$Select=ReportName,LayoutName
to retrieve just the ReportName and LayoutName for each report layout.
See Also
Company Web Service Actions and Functions

---

## ScriptDoc - Web Service Function

Source: https://accredo.co.nz/webhelp/ScriptDocWSFunction.htm

ScriptDoc - Web Service Function
ScriptDoc[(Type=
String
)]: Object
ScriptDoc returns a set of the Data Objects, Report and Functions available as endpoints. Use the Type parameter to return only Data Objects, Report or Functions. This can be used with the
PlayScript
Function.
All MaxBasic functions can be compiled by the
PlayScript
function. ScriptDoc lists the functions available to the web service. Functions listed in the ScriptDoc output as 'Not supported by Web Service' can be compiled, but will not be executed.
ScriptDoc function syntax has these named arguments:
Parameter
Description
Type
Optional. The Type to return. Select from:
Functions
DataObjects
Reports
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("scriptdoc(type='Functions')")
See Also
Company Web Service Actions and Functions

---

## SP Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/SPWebServiceActionsAndFunctions.htm

SP Web Service Actions and Functions
The following company actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
SPEnquiry
Returns pricing details for a specified Customer, Product and Date.
SPRule
Returns rule details for a specified Rule ID or for all Rules.
SPWhat
Returns the What Grid details for a specified Type, or for all What Grid entries.
SPWhere
Returns the Where Grid details for a specified Type, or for all Where Grid entries.
SPWho
Returns the who Grid details for a specified Type, or for all Who Grid entries.
In This Section
SPEnquiry - Web Service Function
See Also
Web Service Actions and Functions

---

## SPEnquiry - Web Service Function

Source: https://accredo.co.nz/webhelp/SPEnquiryWSFunction.htm

SPEnquiry - Web Service Function
SPEnquiry(CustomerCode=
String
,ProductCode=
String
,DocumentDate=
Date
,Quantity=
Number
): Object
SP Enquiry Web Services function returns the pricing details for a given Customer, Product, Date and Quantity.
SPEnquiry function syntax has these named arguments:
Parameter
Description
Customer Code
Required. The customer code to get the pricing for.
Product Code
Required. The product code to get the pricing for.
Document Date
Required. The effective date for the pricing. Date must be in the format YYYY-MM-DD.
Quantity
Required. The Quantity for the pricing.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("SPEnquiry(CustomerCode=ASHENG,ProductCode=BCDRAW,DocumentDate=2018-02-01,Quantity=10)")
See Also
SP Web Service Actions and Functions

---

## System Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/SystemWebServiceActionsAndFunctions.htm

System Web Service Actions and Functions
The following system actions can be performed via the Web Service.
See the
Metadata Properties
link for specific properties for each end point.
Function
Description
About
Returns information about the system running the Web Service.
DeveloperDoc
List the system end points available.
GetPrinterList
Returns a list of printers available on the system.
See Also
Web Service Actions and Functions

---

## SystemDate - Web Service Function

Source: https://accredo.co.nz/webhelp/SystemDateWSFunction.htm

SystemDate - Web Service Function
SystemDate: Date
System date Web Service function returns the current System Date, see
System Date & System Period
.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("SystemDate")
See also the MaxBasic
SystemDate
function and the SQL
SystemDate
function.
See Also
Company Web Service Actions and Functions

---

## SystemPeriod - Web Service Function

Source: https://accredo.co.nz/webhelp/SystemPeriodWSFunction.htm

SystemPeriod - Web Service Function
SystemPeriod: Number
System Period Web Service function returns the current System Period ID, see
System Date & System Period
.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("SystemPeriod")
See also the MaxBasic
SystemPeriod
function and the
SQL SystemPeriod
function.
See Also
Company Web Service Actions and Functions

---

## User - Web Service Function

Source: https://accredo.co.nz/webhelp/UserWSFunction.htm

User - Web Service Function
User: String
User Web Service function returns a JSON object containing the User details.
See
Web Service Functions
for sample code to access Web Services. Sample web service end point syntax is:
Response = MakeCall("User")
See Also
Company Web Service Actions and Functions

---

## Web Service

Source: https://accredo.co.nz/webhelp/WebService.htm

Web Service
The Accredo Web Service can be used to communicate with an Accredo company remotely via the web.
When a Company has the Web Service module installed, company data and functions can be accessed via the web service.
The Accredo Web Service can only be installed on a 64bit operating system.
In This Section
Accredo API Overview and Basics
Web Service Installation and Initial Configuration
Demo System Web Service Setup
Live System Web Service Setup
Configuring Access for Accredo Mobile Applications
Accredo API Technical Documentation
Web Service Functions in MaxBasic
Web Service Actions and Functions
Deleting a Web Service Token
Custom Tables via Web Service
Memos via Web Service
Printing via Web Service

---

## Web Service About

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_About.htm

Web Service About
Accredo > File > Web Service > Monitor > About> About
View the version and other current information for the Web Service.
See Also
Web Service Monitor

---

## Web Service Actions and Functions

Source: https://accredo.co.nz/webhelp/WebServiceActionsAndFunctions.htm

Web Service Actions and Functions
The following Web Service end points can be used to retrieve lists of Web Service Functions or Actions.
See
Web Service Functions in MaxBasic
for sample code to access Web Services.
The following will return a list of available Web Service functions in a JSON object:
Response = MakeCall("$metadata/functions?$format=json")
The following will return a list of available Web Service actions in a JSON object:
Response = MakeCall("$metadata/actions?$format=json")
You can also retrieve a list of End Points in a HTML document. In your browser enter your company URL followed by
/developerdoc
,
/$metadata
or
/autodoc
. For example:
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/developerdoc
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/autodoc
For a formatted list of endpoints use:
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata?$format=json
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata/Types?$format=json
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata/Actions?$format=json
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata/Functions?$format=json
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata/Properties?$format=json
The following will return a list of endpoints:
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/$metadata/Types?$format=json&$Select=Name,AccredoType
To get system details, enter:
http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/developerdoc
Actions
Actions are issued by POST calls, and usually have a persistent affect, meaning that they write to a table or change data. Parameters are contained in the body of the request as JSON. For example:
{ "Param1":"Value", "Param2":"Value" }
Functions
Functions are issued by GET calls, and usually do not have a persistent affect. Parameters for actions are included in the URL. For example:
ActionName(Param1='Value', Param2='Value')
Note: Some endpoints support both functions and actions. See the web service metadata for details of which endpoints this applies to. This is to allow functions with many parameters to be used as actions if URL character limits apply.
Using Web Service Actions
Some Web Service actions in the metadata are referred to without a slash, so they can be displayed in different software utilities.
For example, the Action
INInvoicePost
is the same as the
INInvoice/Post
action. You can identify actions that have the slash removed by:
After the Action name,
IsBound
is
True
.
The first parameter of the action matches the first part of the Action Name. For example, for INInvoicePost, the first parameter is INInvoice, so this matches.
Example use of the INInvoicePost action, where the
$ID
represents the Invoice ID:
Url: .....INInvoice(
$ID
)/Post
Body:
{ "BankThrough": false, "CashSale" : true, "BankAccountCode" : "NZCHEQUE" }
In This Section
System Web Service Actions and Functions
Company Web Service Actions and Functions
AR Web Service Actions and Functions
IC Web Service Actions and Functions
IN Web Service Actions and Functions
OE Web Service Actions and Functions
AP Web Service Actions and Functions
PO Web Service Actions and Functions
CB Web Service Actions and Functions
FA Web Service Actions and Functions
GL Web Service Actions and Functions
JC Web Service Actions and Functions
SP Web Service Actions and Functions
PP Web Service Actions and Functions
GST Web Service Actions and Functions
{Object}/Print and {Object}/PrintSheet - Web Service Function
See Also
Web Service

---

## Web Service Basic Token Cache

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_BasicTokenCacheView.htm

Web Service Basic Token Cache
Accredo > File > Web Service > Monitor > Cache > Basic Token Cache
View the basic token cache.
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Refresh Server
Sends a message to the web service to refresh the cache.
Fields
Token
The authorisation token for the user and IP address.
Expiry
The expiry date and time for the token.
User
The logged in user.
IP Address
The IP address the request comes from.
See Also
Web Service Monitor

---

## Web Service Client Cache

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_ClientCacheView.htm

Web Service Client Cache
Accredo > File > Web Service > Monitor > Cache > Client Cache
View the client cache.
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Refresh Server
Sends a message to the web service to refresh the cache.
Fields
Client ID
The unique client token.
Client Name
Name of the client.
See Also
Web Service Monitor

---

## Web Service Company ID Cache

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_CompanyIDCacheView.htm

Web Service Company ID Cache
Accredo > File > Web Service > Monitor > Cache > Company ID Cache
View the company ID cache.
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Refresh Server
Sends a message to the web service to refresh the cache.
Fields
Company ID
Company ID.
Company Code
Company Code.
Company Path
Location of the company files.
Company Limit
The Web User limit (if any) for the Company.
Token Count
The number of tokens extant for the Company.
Tokens
Lists the tokens extant for the Company.
Next Token Expiry
Date and time of next token expiry.
See Also
Web Service Monitor

---

## Web Service Connection Cache

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_ConnectionCacheView.htm

Web Service Connection Cache
Accredo > File > Web Service > Monitor > Cache > Connection Cache
View the connection cache.
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Refresh Server
Sends a message to the web service to refresh the cache.
Fields
User Code
The User that connected.
Company ID
The company the user connected to.
Authorised
A tick shows this is an authorised user in the company.
See Also
Web Service Monitor

---

## Web Service Functions in MaxBasic

Source: https://accredo.co.nz/webhelp/WebServiceFunctions.htm

Web Service Functions in MaxBasic
Selected functions are available over Web Services, where the Web Service module is installed, as End Points. You can use Web Service Functions to interact with a remote server.
See the End Points for each Module, for a list of functions available.
For information on setting the HTTP request header, see
Web Service Header
.
Web Service MaxBasic Example
The following MaxBasic code can be used to utilise Web Service functions. Add the
required URL
in the first line, and add the
required function
in the
Response =
line, second from the last.
const URL = "http(s)://{domain}:{port}/{serviceroot}/odata4/v1/company({company})/"
Function MakeCall(EndPoint as String) as Object
Dim Http as Object
Http = CreateObject("Accredo.HttpRequest")'
Dim FinalUrl as String
FinalUrl = URL & Endpoint
FinalURL = URLEncode(FinalURL)
Http.URL = FinalURL
Http.ContentType = "application/json"
Http.SetRequestHeader("format","odata.metadata=full")
Dim Resp as String
Resp = Http.Get
If Http.ResponseCode = 200 or Http.ResponseCode = 201 or Http.ResponseCode = 202 Then
Dim Json as Object
If Resp <> "" Then
Json = ParseJSON(Resp)
Else
Json = JSONCreateObject
End If
Return Json
Else
Error ("Error making request. " & Http.ResponseCode & " - " & Http.ResponseText)
End If
End Function
Dim Response as Object
'Add the required function here. For example:
Response = MakeCall("AddPeriod(PeriodID=306,OffSet=12,Financial=False)")
Print JSONStringify(Response)
See the individual Actions and Functions topics for available end points.
In This Section
Web Service Header
See Also
Web Service

---

## Web Service Header

Source: https://accredo.co.nz/webhelp/WebServiceHeader.htm

Web Service Header
The following odata parameters and preferences can be set when making calls to the Web Service.
odata.metadata
When making web service requests, the Web Service Header odata.metadata parameter should be set.
In the
Web Service MaxBasic Example
, this is set in the line:
Http.SetRequestHeader("format","odata.metadata=full")
This can be set to
none
,
minimal
or
full
. If this is not explicitly set it defaults to
minimal
.
For more information, see the OData format for
Controlling the Amount of Control Information in Responses
.
odata.maxpagesize
When dealing with large datasets, the odata.maxpagesize preference can be set to limit the number or records contained in a response collection.
The maximum number of responses that can be returned is set in
Web Service Settings
. Any maxpagesize set must be below or equal to the maximum number of responses set in the Web Service Settings.
In MaxBasic, the maxpagesize could be set as:
Http.SetRequestHeader("prefer","odata.maxpagesize=50")
This can also be set by specifying
&pagesize=n
in the URL, or
pagesize=n
in a header.
See Also
Web Service Functions in MaxBasic

---

## Web Service Installation and Initial Configuration

Source: https://accredo.co.nz/webhelp/WSInstallAndConfiguration.htm

Web Service Installation and Initial Configuration
Accredo Web Service Installation
See
Live System Web Service Setup
or
Demo System Web Service Setup
for specific installation requirements.
A 64 bit operating system is required to install the Accredo Web Service.
Download the
SetupSaturnWebService.exe
or
SetupMercuryWebService.exe
installer from the Accredo Website downloads section.
Run the installer and install into the same directory as the Accredo Server.
The web service installer will automatically open the necessary ports in the Windows firewall: 6569 and 6570 for SSL.
These ports can be changed using the
AccredoWebConfig64.exe
tool that is installed with the Web Service.
In this guide,
demo.accredo.co.nz
is used to represent the domain you will have set up for use with the Web Service.
Accredo Web Service Configuration Tool
The Web Service Configuration tool allows you to configure the initial settings for the service to run i.e service ports, reverse proxy settings. From here you can also Stop/Start and Pause/Resume the service.
Run the AccredoWebConfig64.exe tool in the installation directory. This will request Administrator rights.
In the Web Service Initial Configuration window, select the
Service,
either
AccredoSaturnWeb
or
AccredoMercuryWeb
.
Service Control tab
Add the
System Path
. This is the path of your Accredo System installation.
Service Root
: A URL segment parameter that allows the differentiation of multiple services running on a single server. Defaults to
Mercury
or
Saturn
.
The buttons here allow you to stop/start or pause/resume as well as delete the service from the Windows Registry.
Service Configuration Section
Allow Basic Auth:
Allow the use of Basic Authentication for the service for use with applications that do not support Oauth 2.0.
Ports:
Set the ports for SSL and Non-SSL access to the service.
Trusted IPs:
Set When using Non-SSL, you will need to whitelist the IP address of any client accessing the service.
Reverse Proxy:
On the Configuration tab you can add your reverse proxy details if your proxy is not forwarding through host headers. Host is the local IP address of the server the Web Service is installed on, Alias is your domain which is being forwarded from the reverse proxy.
Click
Update
and then on the Service Control tab click
Start
.
Accredo Application Configuration
Open Accredo Saturn or Accredo Mercury. Click
Cancel
on the Company List, as you need all companies closed.
Go to File > Web Service > Settings.
Click
Edit
.
Ensure
Use SSL
is
Selected
.
In the
Host
field, type
demo.accredo.co.nz
.
Set the
Machine name
to the name of the server.
Click
Save
.
Click
Test Connection
. A green icon will be shown beside the ports that connect successfully.
Go to File > System > Settings.
Click
Edit
.
Make sure that
Single Sign On
is
enabled
.
Set the
Web Sessions
to
1
or greater.
Click
Save
.
The Web Service Login form appears. Enter user details, then click
OK
.
The ACCREDO user password must be changed from its default to be used here. Otherwise create a new user with full permissions for the Web Service.

---

## Web Service Live Logging View

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_LiveLoggingView.htm

Web Service Live Logging View
Accredo > File > Web Service > Monitor > Logging > Live Logging View
View the live server and worker logging.
Options
Service Logging
Selected
, displays log information from the web service load balancer.
Worker Logging
Selected
, displays log information from the workers.
Display Disconnected
Selected
, displays disconnected logging information.
See Also
Web Service Monitor

---

## Web Service Login

Source: https://accredo.co.nz/webhelp/WebServiceLogin.htm

Web Service Login
Accredo > File > Web Service > Monitor
Log into web services. Enter details of the Web Service to log in.
When the logged in System User logs out, the Web Service will also be logged out.
Note: The ACCREDO Master User with password ACCREDO cannot be used to access the Web Service.
See Also
Web Service Monitor

---

## Web Service Menu

Source: https://accredo.co.nz/webhelp/WebServiceMenu.htm

Web Service Menu
Accredo > File > Web Service
This is available when the Web Service Module is Licenced.
In This Section
WS Monitor Settings
WS Client Provisioning Settings
Web Service Monitor
WS View Logs
Web Clients
See Also
File Menu

---

## Web Service Monitor

Source: https://accredo.co.nz/webhelp/WebServiceMonitor.htm

Web Service Monitor
Accredo > File > Web Service > Monitor
Use the Web Service Monitor to view cache, logging and state details and to view and edit Web Service Settings.
You can right-click on an option in a folder to open it in a separate floating window.
About
About
Cache
Basic Token Cache
Client Cache
Company ID Cache
Connection Cache
Token Cache
User Cache
Logging
Live Logging View
Settings
Settings
State
Response
Server
Worker
In This Section
Web Service Login
Web Service About
Web Service Basic Token Cache
Web Service Client Cache
Web Service Company ID Cache
Web Service Connection Cache
Web Service Token Cache
Web Service User Cache
Web Service Live Logging View
Web Service Settings - General tab
Web Service Settings - Balancing tab
Web Service Settings - Workers tab
Web Service Settings - Debugging tab
Web Service Settings - Logging tab
Web Service Response View
Web Service Server View
Web Service Worker View
See Also
Web Service Menu

---

## Web Service Response View

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_ResponseView.htm

Web Service Response View
Accredo > File > Web Service > Monitor > State > Response
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Grid
Shows details of current web service requests.
See Also
Web Service Monitor

---

## Web Service Server View

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_ServerView.htm

Web Service Server View
Accredo > File > Web Service > Monitor > State > Server
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Grid
Shows details of current web service server activity.
See Also
Web Service Monitor

---

## Web Service Settings - Balancing tab

Source: https://accredo.co.nz/webhelp/WebServiceSettings_Balancing.htm

Web Service Settings - Balancing tab
Accredo > File > Web Service > Monitor > Settings > Settings > Balancing tab
Fields
Max Requests Per Minute
The maximum number of total requests per minute that will be accepted. Any requests past this number will be rejected.
Worker Timeout Default
The default time out period in milliseconds for worker scripts. If a worker takes longer than this, it will respond with a time out. For a GET request, after the worker is terminated it will be retried once.
Worker Timeout Maximum
The maximum time out period in milliseconds for worker scripts. When a request contains a time out override, this is the maximum time it can be overridden to.
Worker Timeout Lock Timeout
The maximum total time amount of time in milliseconds a worker will wait for file locks. This must be less than or equal to the Worker Default Time Out.
See Also
Web Service Monitor

---

## Web Service Settings - Debugging tab

Source: https://accredo.co.nz/webhelp/WebServiceSettings_Debugging.htm

Web Service Settings - Debugging tab
Accredo > File > Web Service > Monitor > Settings > Settings > Debug tab
Fields
Beautify
Selected
, JSON debugging will be formatted, not shown in default JSON format.
Clear
, JSON debugging will be shown in standard JSON format.
Bypass OAuth
Selected
, access tokens are not required for requests. This is enabled for Demo systems only.
Bypass User
The User ID to be used when
Bypass OAuth
is selected.
Bypass Password
The password for the
Bypass User
.
Debugging
Selected
, debugging information will be added to logs.
Include Stats In Response
Selected
, extra Response statistical information will be included at the end of the JSON.
Include Stack Traces
Selected
, stack traces will be added to logs.
See Also
Web Service Monitor

---

## Web Service Settings - General tab

Source: https://accredo.co.nz/webhelp/WebServiceSettings.htm

Web Service Settings - General tab
Accredo > File > Web Service > Monitor > Settings > Settings > General tab
Fields
Default Printer
The default printer to use when printing and creating pdf disk files via the web service. Options available are generated from the machine web service running on.
Default Records per Response
The default number number of records in a set that will be returned. For large datasets this should be set to 2000.
Max Records per Response
The maximum number of records in a set that will be returned. Once the maximum is reached, following records can be returned in the next set. For large datasets this should be set to 2000.
Max Workers
The maximum number of worker processes that can be started. If
Blank
, the maximum allowed will be set to the server's CPU Core Count * 2. This is always capped to the number of web sessions allowed for the system.
Access Token Expiry (Mins)
The number of minutes before an Access Token will be expired.
Note that Outh2 tokens will be expired after a period of inactivity, whereas Basic tokens will exist for the entire duration regardless of inactivity.
Refresh Token Expiry (Hrs)
The number of hours before a Refresh Token will be expired.
Allow Basic Authorisation
Determines whether Basic Authorisation is allowed. Basic authorisation is not recommended for web or mobile access. Basic authorisation should only be used from apps when OAuth is not available, such as Microsoft BI or Excel. Select from:
No
- Basic Authorisation is not allowed.
Trusted Only
- Basic Authorisation is only allowed for IP addresses listed as Trusted IPs.
All
- Basic Authorisation is allowed.
Trusted IPs
The list of Trusted IPs is used when running Web Services without SSL. This lists the IPs that requests will be accepted from. These can either be an explicit IPV4 or IPV6 address, or can be a range using the CIDR notation in either IPV4 or IPV6.
Host / Alias
These are used when using a reverse proxy. The Host represents the Host/IP of the Web Service, and the Alias represents the Host/IP of the proxy server.
When a user makes a request to a proxy server (Alias) with IP address x.x.x.x, this then maps the request to where the Web Service exists on (Host) y.y.y.y. Normally when a response is made any references to the Host would be written out based on y.y.y.y, however when using a proxy server it is the address x.x.x.x that should be used. The Host/Alias relationship tells the Web Service that when it gets a request from Host y.y.y.y it will write any responses with the Alias x.x.x.x.
See Also
Web Service Monitor

---

## Web Service Settings - Logging tab

Source: https://accredo.co.nz/webhelp/WebServiceSettings_Logging.htm

Web Service Settings - Logging tab
Accredo > File > Web Service > Monitor > Settings > Settings > Logging tab
Options to save out logging for various response types from the Web Service.
We recommend only logging required for debugging purposes should be enabled and logging should be turned off when not required.
Logs may be loaded and viewed in the
WS Log File Viewer
.

---

## Web Service Settings - Workers tab

Source: https://accredo.co.nz/webhelp/WebServiceSetting_Workers.htm

Web Service Settings - Workers tab
Accredo > File > Web Service > Monitor > Settings > Settings > Workers  tab
Fields
Idle Restart (seconds)
If a worker has been sitting idle for this time and receives a request, it will be restarted.
Work Count Restart
After a worker has processed this number of requests, it will be restarted.
See Also
Web Service Monitor

---

## Web Service Token Cache

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_TokenCacheView.htm

Web Service Token Cache
Accredo > File > Web Service > Monitor > Cache > Token Cache
View the token cache.
Options
Token Type
Select the token type to view.
Token Scope
Select the token scope to view.
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Revoke Token
(F3)
Revoke the selected token.
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
Refresh list
(F5)
Refresh changes to current list.
Refresh Server
Sends a message to the web service to refresh the cache.
Fields
Token
The Token ID.
Token Type
Token Type can be:
A
- Access Token, used for making requests.
R
- Refresh Token, used to request a new set of tokens once an access token has expired. Creates a new Access token and a new Refresh token.
Token Scope
The Token Scope can be:
Blank
- the token is using a user licence.
Admin
- the token is not taking up a user licence.
Auth Type
The type of authorisation:
O
- OAuth2 authorisation.
B
- Basic authorisation.
Expiry
The time and date the token expires.
Client ID
The Client ID that was specified when the request was made.
User
User Code used to get the token.
Password
The encrypted password.
IP Address
For Basic Authorisation, the IP address of the user.
Created Date
Date the token was created.
Created Time
Time the token was created.
Last Used
The date and time the token was last used for a request successfully.
Attempted Last Use
The date and time the token was last used for a request unsuccessfully.
Rate Count Start
The date and time the rate count was last reset.
Rate Count
The number of requests made to the token since the Rate Count Start.
Token Msg
This will show
Rate Limit Exceeded
if the token usage has exceeded the allowed Maximum Requests Per Minute.
See Also
Web Service Monitor

---

## Web Service User Cache

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_UserCacheView.htm

Web Service User Cache
Accredo > File > Web Service > Monitor > Cache > User Cache
View the user cache.
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Refresh Server
Sends a message to the web service to refresh the cache.
Fields
User Code
The User ID.
See Also
Web Service Monitor

---

## Web Service Worker View

Source: https://accredo.co.nz/webhelp/WebServiceMonitor_WorkerView.htm

Web Service Worker View
Accredo > File > Web Service > Monitor > State > Worker
Options
Auto Refresh
Selected, the grid will automatically refresh.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
ESC
to close the expanded toolbar.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh list
(F5)
Refresh changes to current list.
Grid
Shows details of current web service workers running.
See Also
Web Service Monitor

---

