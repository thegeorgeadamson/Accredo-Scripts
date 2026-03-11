# Data Interchange (DI)

> Import/export wizards, DI setup, data interchange

**Sections:** 12

---

## Quick Reference

- [Accredo Data Interchange (DI)](#accredo-data-interchange-di)
- [Data Interchange](#data-interchange)
- [Data Interchange - Reports](#data-interchange---reports)
- [Data Interchange - Setup](#data-interchange---setup)
- [Data Interchange - Tasks](#data-interchange---tasks)
- [Diagnostics](#diagnostics)
- [Diagnostics - Machine tab](#diagnostics---machine-tab)
- [Dim statement](#dim-statement)
- [directory](#directory)
- [Discount Schedule](#discount-schedule)
- [EDI Exporting](#edi-exporting)
- [EDI Importing](#edi-importing)

---

## Accredo Data Interchange (DI)

Source: https://accredo.co.nz/webhelp/AccredoDataInterchange.htm

Accredo Data Interchange (DI)
Accredo Data Interchange (DI) can be accessed by the following paths:
Navigator > Setup > Data Interchange > Import Designer
Navigator > Setup > Data Interchange > Export Designer
Navigator > Tasks > EDI Importing
Navigator > Reports > EDI Exporting
You can use the Accredo DI (Data Interchange) module to create customised file import and export functions. DI integration can be fully automated using MaxBasic scripting. We recommend only advanced Accredo Users with programming skills use the DI module.
The DI Module can be used to develop customised file import or export functions to:
Exchange information such as invoices, purchase orders and other transactions between two or more Accredo systems, or between Accredo and other systems.
Import updates to Accredo files.
Read information contained in Accredo databases from other applications, such as Microsoft Excel and Access using the OLEDB /ODBC driver.
Access to Accredo data via OLEDB/ODBC is read only. To write back to the database from another application, use DI and the Accredo data objects to maintain data validity. To read information in Accredo databases from other applications the DI module must be installed in the relevant Accredo database, along with the OLEDB/ODBC driver on the Accredo Installation Media or downloaded from the Accredo website. See
Install OLEDB/ODBC Drivers
.
The following require the DI module:
OLEDB /ODBC for read only access
EDI import and export
COM scripting via the Accredo Data Objects, for writing or reading directly to or from Accredo.
See Also
Installation Options

---

## Data Interchange

Source: https://accredo.co.nz/webhelp/DataInterchange.htm

Data Interchange
You can use Data Interchange to integrate applications or databases.
File Exporting exports data from records in single files (raw data). EDI Exporting takes data from more than one file to create export records. For example, exporting an invoice will typically export an Invoice header followed by a number of Invoice lines. Not all data in the files can be directly imported or exported. For example, Customer account balances cannot be directly imported as they are a consequence of the customer transactions.
You can:
Import data from files created by third party applications or data exported from another Accredo system.
Transfer masterfiles from one Company to another without bringing across transactions.
Import transactions, for example, invoices from other systems.
Transfer information to a spreadsheet or other software package for analysis, and re-import.
Use
OLEDB/ODBC
to access Accredo data files.
Use data level scripting, that is, manipulating data objects in Accredo independently of a user interface.
Access external programs (for example, Excel) using
COM
and script data objects in Accredo for read and write.
In This Section
Importing & Exporting Overview
Setup AccredoDB OLEDB/ODBC driver
COM (Component Object Model)
Data Interchange - Tasks
Data Interchange - Reports
Data Interchange - Setup

---

## Data Interchange - Reports

Source: https://accredo.co.nz/webhelp/DataInterchange_Reports.htm

Data Interchange - Reports
Navigator > Reports>
EDI Exporting
Navigator > Reports>
File Exporting
In This Section
EDI Exporting
File Exporting - Definition tab

---

## Data Interchange - Setup

Source: https://accredo.co.nz/webhelp/DataInterchange_Setup.htm

Data Interchange - Setup
Navigator > Setup > Data Interchange
In This Section
Price Book Designer
Import Designer - Definition tab
Export Designer

---

## Data Interchange - Tasks

Source: https://accredo.co.nz/webhelp/DataInterchange_Tasks.htm

Data Interchange - Tasks
Navigator > Tasks > Price Book Import
Navigator > Tasks > EDI Importing
In This Section
EDI Price Book Import
EDI Importing

---

## Diagnostics

Source: https://accredo.co.nz/webhelp/Diagnostics.htm

Diagnostics
Accredo > File > Diagnostics
Machine tab
Provides details of the computer and operating system, including the search path and location of temporary folders and handles in use.
The
Mail
(Alt+M)
button can be used to email diagnostics information for support.
Click
Refresh
(
Alt+R)
to refresh information.
Click
Set Server Path to System Path
to reset the
COM Server Path
.
See
Diagnostics - Machine tab
.
Memory tab
Provides details of the memory used. Select
Auto Refresh
(Alt+A)
to refresh the data approximately every 5 seconds, or click
Refresh
(
Alt+R)
to refresh manually.
FastMM tab
Provides detailed memory use information for Accredo troubleshooting.
Files tab
Lists all the open files, including files in the System folder and the Company data folder.
File Name
The path and name of each open data file.
Excl
Selected
, the file is open exclusively.
Defeat
Selected
, the file has a Defeat oplock applied.
Read
Selected
, the file is read-only.
Locks
Defines locks applied to the open file.
The lower panel shows the number of open files and locks applied. Select
Auto Refresh
(Alt+A)
to refresh the data approximately every 5 seconds, or click
Refresh
(
Alt+R)
to refresh manually.
Stats tab
Shows statistics for file activity in the current session. The lower panel shows the number of read and write bytes across all files. Click
Reset
(Alt+E)
to clear and start accumulating from zero.
The
Mail
(Alt+M)
button can be used to email diagnostics information for support.
Select
Auto Refresh
(Alt+A)
to refresh the data approximately every 5 seconds, or click
Refresh
(
Alt+R)
to refresh manually.
Cache tab
Shows details of the cache. Select
Auto Refresh
(Alt+A)
to refresh the data approximately every 5 seconds, or click
Refresh
(
Alt+R)
to refresh manually.
Printers tab
Lists all the printers visible to Accredo and highlights the default Accredo printer. Click
Refresh
(
Alt+R)
to refresh.
Tables tab
Lists active tables and the modules that own them.
Modules tab
Lists all active Accredo modules.
The
Mail
(Alt+M)
button can be used to email Modules information for support.
Click
Refresh
(
Alt+R)
to refresh.
Forms tab
Lists all open Accredo forms.
The
Mail
(Alt+M)
button can be used to email Forms information for support.
Click
Refresh
(
Alt+R)
to refresh.
TAPI tab
Lists TAPI diagnostics for all visible TAPI objects.
8087 CW tab
Displays the state of the 8087 floating point unit for Accredo troubleshooting. Click
Refresh
(
Alt+R)
to refresh.
SYSTEM.CFG
Displays the
System.cfg
.
In This Section
Diagnostics - Machine tab
See Also
File Menu

---

## Diagnostics - Machine tab

Source: https://accredo.co.nz/webhelp/Diagnostics_Machine.htm

Diagnostics - Machine tab
Accredo > File > Diagnostics > Machine tab
The Diagnostics Machine tab provides details of the computer and operating system, including the search path and location of temporary folders.
Client User
The logged in Windows user.
Client Name
The Windows PC name.
Client OS
The operating system the client is running on.
Server Name
The server location.
Server OS
The operating system the server is running on.
Server Path
The location of the Accredo server.
COM Server Path
The location of the COM server.  Click
Set Server Path to System Path
to set the
COM Server Path
to the current system path.
COM Exe (32 bit)
The location of the COM 32-bit exe file. Click
Set COM exe to this exe
to set the COM exe.
COM Exe (64 bit)
The location of the COM 64-bit exe file.
Terminal Server
The Remote Desktop Host running.
Command line
The command line used to run Accredo.
PATH
The paths used by the application.
TMP
TMP temporary directory.
TEMP
TEMP temporary directory.
Windows Temp
Windows temporary directory.
PID
Proportional Integral Derivative controller.
Stack
The stack number.
User Handles
The User Handles currently in use.
There are three different Windows limits on allocating User Handles - a per process 10,000 limit, a global 32,700 limit and also a total size limit in the User heap. Exhaustion of any of these can cause Windows error 1158.
GDI Handles
The GDI (Graphics Device Interface) handles currently in use.
Kernel Handles
The Kernel handles currently in use.
Screen PPI
Screen Pixels Per Inch (PPI), measures pixel density.
Monitor PPI
Monitor Pixels Per Inch (PPI), measures pixel density.
Loading PPI
Loading Pixels Per Inch (PPI), measures pixel density.
DPI Level
Dots Per Inch (DPI) level.
Refresh
Refresh the
Stack
and
Handles.
Mail
(Alt+M)
Creates a mail message containing diagnostic information. This can be used for support.
See Also
Diagnostics

---

## Dim statement

Source: https://accredo.co.nz/webhelp/MBDimStatement.htm

Dim statement
Declares variables and allocates storage space.
Syntax
Dim name [As type] [, name [As type] ... ]
or
Private name [As type] [, name [As type] ... ]
or
Array form: Dim name[ [lower To] upper ] [As type]
Dim statement syntax has these named arguments:
Parameter
Description
Varname
Name of the variable. Follows standard variable naming conventions.
Subscripts
Optional. Dimensions of an array variable. Only single dimension arrays are supported. The subscripts argument uses the following syntax:
[lower To] upper or just upper Examples:
Dim A[5] As Number ' indices 1..5
Dim B[0 To 9] As Number ' indices 0..9
When not explicitly stated in lower, the lower bound of an array is 1.
Type
Data type of the variable. Can be Boolean, Number, Date, String or Object.
Usage
Use the Dim statement to declare the data type of a variable. For example, the following statement declares a variable as a Number:
Dim NumberOfEmployees AS Number
You can also use a Dim statement to declare a variable as an Object. The following declares a variable for a new instance of a form (this is commonly used in automation and scripting):
Dim Form1 AS Object
You can declare multiple variables in one line. The following will declare three string variables:
Dim Str1 as String, Str2 as String, Str3 as String
If you don't specify a data type or object type, the variable is Variant by default. The following will declare three variables, but only the last will be created as a String type. The other two will be of type Variant.
Dim Str1, Str2, Str3 as String
You can also mix types on a single line, for example:
Dim Str1 as String, Num 1 as Number, Obj1 as Object
See Also
MaxBasic Statements

---

## directory

Source: https://accredo.co.nz/webhelp/90.htm#o5518

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

## Discount Schedule

Source: https://accredo.co.nz/webhelp/CompanyDiscountSchedule.htm

Discount Schedule
Navigator > Setup > Company > Configuration > Discount Schedule
The Discount Schedule is available with AR, IC or JC.
You can set Discount Codes for
Customers
and
Products
. The Discount Schedule is based on the combination of Customer and Product discount codes, and the corresponding Discount is set in the grid. The default Discount Code for new customers and new products is
zero.
When you are setting up discounts, use the Discount Schedule to enter discount percentages for the Customer Discount Code and Product Discount Code. For example, if the discount for Customer Discount Code
1
and Product Discount Code
2
is 5%, enter
5
in the Discount Schedule grid in
Row 1
(Customer Discount Code 1),
Column 2
(Product Discount Code 2).
The Price Code and Discount are applied at invoicing. If AR and IC are installed, you can use the Discount Schedule for large numbers of Price codes when pricing changes. Discount codes for both customers and products range from
0
-
99.
Discount Codes
The discount for the Selling Price is based on the
Discount Mode
. With
Explicit
discounting, all manual Invoice lines will be treated as having a Product Discount code of
zero.
Note: If you have IC, it is important that no discounts are entered in the zero row and zero column of the Discount Schedule to avoid unexpected discounts applying to new products or customers. If you do not have IC, you can use the first field of Discount Schedule (Product Discount code
0
) for Customers.
The Discount Schedule applies to the Selling Price of a Product based on the
Customer
Price Code
.
If you do not have a discount structure and have only one Price code, you do not need the Discount Schedule, as all customers are charged the Selling Price from IC.
Discount Mode
Indicates how discounted prices are shown on orders and invoices:
Explicit,
the discount appears on the invoice, the price shown is the Selling Price from IC.
Implicit,
the discount does not appear on the invoice, the Selling Price will be less the discount in Discount Schedule.
Discount Mode is selected in
IN Settings
.
Print
(Ctrl+P)
Print the Company Discount Schedule report.
See Also
Configuration

---

## EDI Exporting

Source: https://accredo.co.nz/webhelp/EDIExporting.htm

EDI Exporting
Navigator > Reports > EDI Exporting
You can export data from the Accredo data files. EDI Export allows effective exporting of business objects. In this way it differs from File Exporting in that it allows exporting of the data from records in single files (that is, raw data). In many cases EDI Export takes data from more than one file to create export records. For example, exporting an Invoice will export an Invoice header followed by a number of Invoice lines.
Output
Select whether to export to an
Excel worksheet
or a
Text File
.
Excel Worksheet
Available for
Excel worksheets
, the name of the Sheet to export to.
Export Definition
The file that defines the data format for export. The export definitions are written in
MaxBasic
code, and can be generated using the
EDI Export Wizard
.
Output Folder
The folder the file will be output to. Remembers the previous output folder within a session.
File Name
The file name that specifies where the output from the export will go.
Append to existing file
Selected
- adds the exported records to the file specified under file name.
Clear
- the file will be overwritten.
Buttons
Open in Designer
Open the selected Export Definition in the
Script Editor
.
Reset to Default
Resets the Output folder to the SavedOutput folder in the Accredo System folder or Company Data folder depending on
Use Private Output
in
Company settings
.
Sample Export Routines
Accredo provides a number of sample file exporting routines. These are located in
AccredoDirectory
\Scripts\EDIExports\SampleExports
. Corresponding import routines are located in
AccredoDirectory
\Imports\EDIImports\SampleImports
. After you have run a sample export routine, you can use the corresponding import routine to import the file created. Go to Navigator > Tasks > EDI Importing to import the file.

---

## EDI Importing

Source: https://accredo.co.nz/webhelp/EDIImporting.htm

EDI Importing
Navigator > Tasks > EDI Importing
You can import data into Accredo data files into Accredo masterfiles. Importing data can make changes to the data files, so we recommend taking a backup of data files prior to running an import.
EDI Definition
Import definitions use
MaxBasic
code and are set up in
Import Designer
to provide access to data objects.
Sample import definitions are available on the Accredo installation media in the
EDIFormats
folder.
Click
Open In Designer
to open the selected file in the
Import Designer
.
Import File
The file name and path to the data to be imported.
Clear successfully imported
Selected,
removes successfully imported records from the import file when importing transactions, invoices, sales or purchase orders, to avoid duplication if a file is re- imported.
Also makes identifying error records easier on masterfile imports.
Not available for Excel files.
Make backup
Selected,
makes a copy of the import file before the import. Recommended if you are clearing successfully imported records.
The backup copy has the original import file name with the extension ".BAK". Previous backups of the import files will be renamed to increment the backup number ".BAK" to ".BK1", ".BK1" to ".BK2", through to ".BK8" to ".BK9"; the oldest backup previously ".BK9" will drop off.
Not available for Excel files.
Excel Worksheet
If the import file is an Excel Workbook, you can specify a Sheet Name or Sheet Number.
If not specified, the Worksheet specified from the EDI Import definition file will be accessed, if this is not found, the first Worksheet will appear.
Sample Import Routines
Accredo provides a number of sample file importing routines. These are located in
AccredoDirectory
\Imports\EDIImports\SampleImports
. Corresponding export routines are located in
AccredoDirectory
\Scripts\EDIExports\SampleExports
.  To run a corresponding sample export routine, go to Navigator > Reports > EDI Exporting. Run the export routine to create a data file. You can then import the file created using the import routine.

---

