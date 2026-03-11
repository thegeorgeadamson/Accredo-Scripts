# System Setup & Configuration

> Installation, company setup, users, security, preferences, customisation, UI

**Sections:** 80

---

## Quick Reference

- [Accelerator Keys](#accelerator-keys)
- [Accredo Backup & Restore](#accredo-backup--restore)
- [Accredo File Locations](#accredo-file-locations)
- [Accredo File Name Extensions](#accredo-file-name-extensions)
- [Accredo Installation](#accredo-installation)
- [Accredo Installer Options](#accredo-installer-options)
- [Accredo Keyboard Shortcuts](#accredo-keyboard-shortcuts)
- [Accredo Lookups](#accredo-lookups)
- [Accredo Main Menu](#accredo-main-menu)
- [Accredo Main Window](#accredo-main-window)
- [Accredo Mobile Applications](#accredo-mobile-applications)
- [Accredo Module Compatibility](#accredo-module-compatibility)
- [Accredo Module Integration](#accredo-module-integration)
- [Accredo ODBC Connector for Power BI](#accredo-odbc-connector-for-power-bi)
- [Accredo Qualified Support Person (QSP)](#accredo-qualified-support-person-qsp)
- [Accredo Security Application](#accredo-security-application)
- [Accredo Security Code](#accredo-security-code)
- [Accredo System Setup](#accredo-system-setup)
- [Accredo Training](#accredo-training)
- [Accredo VSS](#accredo-vss)
- [Accredo Website](#accredo-website)
- [Add and Delete Company Users](#add-and-delete-company-users)
- [Add Company User to System](#add-company-user-to-system)
- [Branches](#branches)
- [Change a Password](#change-a-password)
- [Configuring Access for Accredo Mobile Applications](#configuring-access-for-accredo-mobile-applications)
- [Customise Buttons](#customise-buttons)
- [Customise Fields](#customise-fields)
- [Customise Grids](#customise-grids)
- [Customise Layout - Preferences tab](#customise-layout---preferences-tab)
- [Customise Layout - Report tab](#customise-layout---report-tab)
- [Customise Layout - Users tab](#customise-layout---users-tab)
- [Customise Tab](#customise-tab)
- [Customise Tab Alignment](#customise-tab-alignment)
- [Customise Tab Move Components](#customise-tab-move-components)
- [Customise Toolbars](#customise-toolbars)
- [Decimals](#decimals)
- [default](#default)
- [Default Formats](#default-formats)
- [Departments](#departments)
- [Document Defaults](#document-defaults)
- [EDI Price Book Import](#edi-price-book-import)
- [Form Designer Memory Table Designer](#form-designer-memory-table-designer)
- [Form Designer Memory Table Designer - Keys tab](#form-designer-memory-table-designer---keys-tab)
- [Keyboard Shortcuts - Navigation](#keyboard-shortcuts---navigation)
- [Licensee Details & Accredo Security Code](#licensee-details--accredo-security-code)
- [Link a Server to Accredo ODBC Driver](#link-a-server-to-accredo-odbc-driver)
- [Merge Codes](#merge-codes)
- [Number Formats](#number-formats)
- [password](#password)
- [Preferences - Colour tab](#preferences---colour-tab)
- [Preferences - Display tab](#preferences---display-tab)
- [Preferences - General tab](#preferences---general-tab)
- [Preferences - System tab](#preferences---system-tab)
- [Preferences - Trouble-shooting tab](#preferences---trouble-shooting-tab)
- [Price Book Designer](#price-book-designer)
- [Price Book Designer - Before Import tab](#price-book-designer---before-import-tab)
- [Price Book Designer - Comment tab](#price-book-designer---comment-tab)
- [Price Book Designer - Definition tab](#price-book-designer---definition-tab)
- [Price Book Designer - For Each Record tab](#price-book-designer---for-each-record-tab)
- [Report Preferences](#report-preferences)
- [Script to Default Graph Fields](#script-to-default-graph-fields)
- [Status Bar](#status-bar)
- [SYS Users - Permissions tab](#sys-users---permissions-tab)
- [SYS Users - Preferences tab](#sys-users---preferences-tab)
- [System Login](#system-login)
- [System Settings - Passwords tab](#system-settings---passwords-tab)
- [System User Permission Strings](#system-user-permission-strings)
- [System User Permissions](#system-user-permissions)
- [Table Designer](#table-designer)
- [Table Designer - Reports](#table-designer---reports)
- [Table Designer Tutorials](#table-designer-tutorials)
- [TD Table Designer - Keys tab](#td-table-designer---keys-tab)
- [User Login](#user-login)
- [User Permission Strings](#user-permission-strings)
- [User Permissions](#user-permissions)
- [Users, Groups and Roles - Permissions tab](#users-groups-and-roles---permissions-tab)
- [Users, Groups and Roles - Preferences tab](#users-groups-and-roles---preferences-tab)
- [Using Events to set Batch Selection Defaults](#using-events-to-set-batch-selection-defaults)
- [Workstation Settings and Preferences](#workstation-settings-and-preferences)

---

## Accelerator Keys

Source: https://accredo.co.nz/webhelp/AcceleratorKeys.htm

Accelerator Keys
Accelerators are shortcut keys for program commands on a menu or toolbar and for commands that do not have a user-interface object associated with them.
An underscore below a letter on a Button name, or Menu option name indicates availability to use the letter in conjunction with the
Alt
key.
For example, for the
A
ccept button,
Alt+A
will activate
Accept.
Accelerator keys for selecting tabs
Accelerator keys are available for navigation to tabs, particularly on Masterfile maintenance and Document forms. Click
Alt+Underlined Letter
to move to a tab.
Compatibility
When adding key combinations for Script Shortcuts, ensure they are not the same as Accelerator keys already used on the same form.
See Also
Accredo Keyboard Shortcuts

---

## Accredo Backup & Restore

Source: https://accredo.co.nz/webhelp/AccredoBackupAndRestore_1.htm

Accredo Backup & Restore
Accredo > File > Backup Company
It is important to perform backups on a regular basis to protect your data from hardware failure or loss from software or security issues.
Before performing an Accredo backup, ensure sufficient drive space is available. Files are compressed to a temporary folder on the hard drive before being transferred to the specified backup destination.
If Accredo is run on a file server or Remote Desktop server it will be faster to run the backup directly from that server.
Backup Frequency
The frequency of your backups is dependent on your use of Accredo. Smaller companies or those processing less transactions may only require a weekly backup, whereas bigger companies may need to do backups daily or even hourly.
We recommend that backups be taken before performing tasks where an outcome may be uncertain, such as end of period processing or importing large amounts of data.
Backup Methods
For some sites, the Accredo built in backup feature will be adequate for taking manual backups as needed. The Backup Tool is available at Accredo > File >
Backup Company
. Backups taken using the Accredo backup tool should be made to a different location to the machine your data is stored on. This could be a USB flash drive or hard drive on a network location.
For larger sites or sites using Remote Desktop Services, in addition to manual backups, the use of mirrored drives and daily (or more frequently as required) automated system-wide backups are recommended.
Install the
Accredo VSS
writer and use the
Accredo VSS Backup
utility or a third-party backup solutions that supports volume snapshots, as this will allow backups to be seamlessly made while Accredo is in use.
Verify Backups
Verify Accredo backups to ensure the data has been recorded correctly. If a backup takes less time than usual, it may indicate a fault. We recommend you archive Accredo backups, including backups taken at the end of the previous two accounting periods.
Restore
To restore a company, go to Accredo > File >
Restore Company
.
See Also
Accredo Maintenance

---

## Accredo File Locations

Source: https://accredo.co.nz/webhelp/AccredoFileLocations.htm

Accredo File Locations
All files except the Accredo program, Help files and a few support files are located in the Accredo System folder (directory) and sub-folders
.
System folder:
Saturn System Folder defaults to \AccredoSaturn\
Mercury System Folder defaults to \AccredoMercury\
Contains System database files and Company menu.
All folders below are located in the System Folder, where indicated if Private option is selected in the
Company Settings
may be located in the Company data folder.
Folder
Typical Name
Contents
Private to Company option
Live
\Live
Empty Company data files for new Companies.
Data
\Data001
Company data folders - contain all data for a single Company. May be named as desired.
Dictionaries
\Dictionaries
Spell check dictionary files.
Use private Dictionaries folder.
Forms
\Forms
Custom designed forms.
Use private Customisation folders (includes all sub folders).
Special Pricing Rules
\Forms\SPRule
Special pricing rule files.
GL Chart
\GLCharts
GL Charts of Accounts.
Use private Customisation folders (includes all sub folders).
Images
\Images
Image files of various types, appearing in documents and reports.
Use private Images folder.
Imports
\Imports
Sub-folders containing import definition files.
Use private Customisation folders (includes all sub folders).
CB Imports
\Imports\CBImports
CB import definition files.
DI Imports
\Imports\EDIImports
DI import definition files.
PB Imports
\Imports\PBImports
PB import definition files.
Links
\Links
Links in Masterfiles.
Use private Links folder.
Reports
\Reports
Sub-folders containing report and definition files.
Use private Customisation folders (includes all sub folders).
Electronic Payments
\Reports\APElectronic
\Reports\CBElectronic
Electronic Payment export definition files.
Documents
\Reports\
[MODULEDocType]
Document files, such as labels, statements, and receipts.
Custom
\Reports\Custom
Custom designed report files.
Email Templates
\Reports\EmailTemplates
Email template files.
File Exporting
\Reports\FEExports
FE definition files.
GL Accountant
\Reports\GLAccountant
GL Accountant export definition files.
Financial Reports
\Reports\GLFinancial
GL Financial Report definition files and GL Financial Wizard definition files.
JC Reports
\Reports\JCReports
JA Analysis report definition files.
Labels
\Reports\Labels
Label layout files.
Layouts
\Reports\Layouts
Report layout files.
Purchase Analysis Reports
\Reports\PAReports
Purchase Analysis report definition files.
Sales Analysis Reports
\Reports\SAReports
Sales Analysis report definition files.
Special Pricing Rules
\Reports\SPRule
Special Pricing rule files.
SQL Queries
\Reports\SQLQueries
SQL Query files.
Scripts
\Scripts
Internal automation
script
files.
Use private Customisation folders (includes all sub folders).
EDI Exports
\Scripts\EDIExports
Data Interchange export definition files.
Geocode Scripts
\Scripts\ COGeocodeContext
Geocode script files.
Report Lists
\Scripts\ReportLists
Files containing lists of reports.
SP Context
\Scripts\SPContext
Special pricing script files.
Import Backups
\[Datannn]\Import
Backup copies of files imported to the Company data in [Datannn] using Accredo import functions.

---

## Accredo File Name Extensions

Source: https://accredo.co.nz/webhelp/AccredoFileNameExtensions.htm

Accredo File Name Extensions
Accredo Data Files
.adb
Table Designer custom data file
.adm
.adu
Dictionary file
.anx
Table Designer custom index file
.pdb
Accredo data file
.pnx
Accredo index file
Accredo Customisation Files
.pfa
Special Pricing Price List report definition file
.pfb
Electronic Payment export definition file
.pfc
Reserved for future use in character based report definition files
.pfd
Designed report or document definition file of FD Forms Definition file
.pfg
Accredo Accountant Export Definition file
.pfi
Import definition file including Price Books
.pfl
MaxBasic scripted report list file
.pfn
Report definition file for Sales Analysis, Job Costing Analysis or File Exporting
.pfp
Special Pricing rule list file
.pfq
SQL Query file
.pfs
MaxBasic automation script file
.pfy
Report layout file
Standard Windows Files
.csv
Comma separated values file
.html
HTML (HyperText Markup Language) document file or Email template
.log
Log file

---

## Accredo Installation

Source: https://accredo.co.nz/webhelp/AccredoInstallation.htm

Accredo Installation
This guide will take you through the process of installing Accredo business and accounting software on servers and workstations.
This guide is designed for use by network administrators, who have access to make changes on the company server. You do not need to read and understand this entire document to install Accredo. This document can also help experienced users perform advanced installations.
To find out more about Accredo software, refer to the
Accredo website
.

---

## Accredo Installer Options

Source: https://accredo.co.nz/webhelp/AccredoInstallerOptions.htm

Accredo Installer Options
The following options are available when installing Accredo:
Saturn / Mercury Demo Install
Install a 32 bit demonstration version and add a desktop shortcut. Also installs AccredoTeamViewer.exe.
Saturn / Mercury Demo 64bit Install
Install a 64 bit demonstration version and add a desktop shortcut. Also installs AccredoTeamViewer.exe.
Saturn / Mercury Client Install
Install the 32 bit Accredo Client (requires access to Accredo Server).
Saturn / Mercury Client 64bit Install
Install the 64 bit Accredo Client (requires access to Accredo Server).
Saturn / Mercury Server Install
Install Accredo for the first time, install a full release upgrade and add modules and Users.
Saturn / Mercury Server Update
Install an interim version update.
OLEDB/ODBC Driver Install
Install the 32 bit Accredo
OLEDB/ODBC Driver
to view Accredo data from other applications.
OLEDB/ODBC Driver 64bit Install
Install the 64 bit Accredo
OLEDB/ODBC Driver
to view Accredo data from other applications.
Miscellaneous
Contains the following options:
Client Fix
Server Fix
8.5" x 8" Paper
Browse
Open Windows Explorer and view the installation media contents.
Exit
Exit the installer.

---

## Accredo Keyboard Shortcuts

Source: https://accredo.co.nz/webhelp/AccredoKeyboardShortcuts.htm

Accredo Keyboard Shortcuts
Keyboard shortcuts reduce Accredo task time, we recommend familiarising yourself with the many Keyboard Shortcuts available.
Note: you need your functions keys activated on your keyboard to use the Accredo Keyboard Shortcuts.
Accelerator Keys
Keyboard Shortcuts - Navigation
Keyboard Shortcuts - Navigator
Keyboard Shortcuts - Buttons
Keyboard Shortcuts - Clipboard
In This Section
Accelerator Keys
Keyboard Shortcuts - Navigation
Keyboard Shortcuts - Navigator
Keyboard Shortcuts - Buttons
Keyboard Shortcuts - Editing and Clipboard

---

## Accredo Lookups

Source: https://accredo.co.nz/webhelp/AccredoLookups.htm

Accredo Lookups
Lookups contain a list of values that are in the database.
Each Lookup has a right-click context menu. You can right-click on any part of the lookup to see the options available.
Lookup
Opens a drop-down list where you can select a value.
Word Lookup
Click to access
Word Lookup
. You can enter words or partial words that will be searched. Searches use indexes set up in the Settings for the module. Columns shown are the fields
Customised
into the code, see below. To sort the results, click on the column headings.
Filter & Sort
You can
Filter
the list of records to show a smaller subset, or you can sort the list.
Show Inactive Records
Include inactive records in the list. You can make records inactive by selecting the checkbox in the master file for the record.
To display this button for Custom Tables, ensure the Table has
Indices
called Active
Master
(having as the first field a boolean named Inactive) and
Master
. For example,
ActiveProduct
and
Product
.
Note: For
AR Customers
and
AP Creditors
, toggling this will also toggle the
Show / Hide Inactive
button on the Contacts tab.
Links
Opens
Links On...
You can view links for the selected record. The Links button changes to indicate whether the record has:
No links
- OR -
Links present
Memos, Alarms & Reminders
Opens
Memos On...
. View, add, delete or edit memos and alarms. The Memos button changes to indicate whether the record has:
No memos
Memos, reminders or passive alarms
- OR -
Active alarms
Open Masterfile
Open the Master file associated with the value in the Lookup.
Customise
To access the Customise option, right-click the Lookup to see the context menu. You can
customise
fields shown in the lookup.
Fields selected will be shown as columns in the
Word Lookup
.
Note: If you leave the Memos On... or Links On... list open, they will synchronise with the Lookup selection, so if you select another record, they will show details for the selected record.
To select a value in a Lookup control, you can:
Type a value.
Click
to open a drop-down and select the value.
Press
F7
or
F8
to scroll backwards or forwards one at a time.
Press
Shift+F7 or Shift+F8
to select the first or last record.
Press
+
or
-
(numeric keypad) in a Period Lookup to move forward or backward a period.
Press
Ctrl+Up
or
Ctrl+Down
or
Ctrl++
or
Ctrl+-
(numeric keypad) in a Period Lookup to select the same period Last Year or Next Year.
Use
Up, Down, Page Up, Page Down, Home, End
to move to the record.
Click the scroll buttons (if showing).
Type the first letter of the code. A drop-down will appear. Set the key press delay in
Accredo preferences
.
Some Lookups have multiple indexes. For example, IC Product Codes are indexed on Description and Details by default. A drop-down list will show the primary index, but you can show the alternate index. Alternative indexes are not necessarily unique. To access an alternative index:
Press
Alt
and click
on the drop-down.
Press
Alt+F2
to show the alternative index when you open the drop-down.
Click the scroll buttons in the upper left corner of the drop-down to toggle indexes.
Press
Ctrl+Up
or
Ctrl+Down
when the drop-down is open to toggle indexes.
In This Section
Word Lookup
Word Lookup Settings
Phone Lookup
Email Lookup
See Also
Global Tools

---

## Accredo Main Menu

Source: https://accredo.co.nz/webhelp/AccredoMainMenu.htm

Accredo Main Menu
The Accredo Main Menu is displayed at the top of the Accredo Main Window, and is used to access standard Windows functions and global options, including
The Navigator
.
You can also use the
Global Toolbar
and Keyboard Shortcuts to quickly reach menu options.
The Accredo Main Menu contains drop-down menus:
File
The Accredo File menu contains commands relating to handling files. It gives options for managing system settings, companies, licensee details, printer settings, error log details and for viewing diagnostics.
Edit
Standard Windows options to Undo, Redo, Cut, Copy and Paste.
View
View Accredo features including the Navigator, Calculator, Calendar, User Information and Preferences.
Shortcut
You can add your own shortcuts to this menu. It contains the option to Add Shortcut.
Script
Contains tools and options for Scripting, Report Lists, SQL Query builder, Form Designer and Report Designer.
Window
Options to manage open windows.
Help
Options to access the Help, the Accredo website, Email and Support options and Licensee Statement details.
In This Section
File Menu
Edit menu
View Menu
Shortcut Menu
Script menu
Window Menu
Help Menu
See Also
Accredo Main Window

---

## Accredo Main Window

Source: https://accredo.co.nz/webhelp/Overview.htm

Accredo Main Window
Accredo is presented in an application window that can contain other child and floating windows, such as data entry forms and grids. You can:
Open many windows at a time.
Resize windows - Accredo will remember the sizes you set and use these when a window is opened again.
Switch windows between child and floating states.
Accredo software is based on standard Windows functions and settings and is designed for Microsoft's currently supported versions of the Windows operating system. The Accredo Manuals, Help Topics and other literature use basic Windows terminology. Accredo supports Windows user interface standards, including keyboard data entry.
Some information in Accredo is dependent on Windows settings. Accredo uses the Windows Regional Settings to determine the:
Number format
Time and Date format
Time zone
In This Section
Accredo Main Menu
Global Toolbar
Period Bar
Status Bar

---

## Accredo Mobile Applications

Source: https://accredo.co.nz/webhelp/AccredoMobileApplications.htm

Accredo Mobile Applications
The
Accredo Sales App
and the
Accredo Inventory App
are available from the Google Play store and the Apple App store.
If you have Web Services set up, you can use the apps to access your Accredo companies.
Set up for Mobile Applications
Add
Change tracking
for the App(s) you are using.
For the Mobile Sales App check that either all Prices are
mapped
or
Stamp Modified on Sell Price Update
is selected.
For the Mobile Inventory App check that Count Type is set to Additive (recommended) or Single in
IC Settings > Stocktake
.
Add
Mobile App Filtering
if desired. Note that Inactive Products are excluded automatically and some settings to restrict data are found in the Mobile App Settings.
Modules RequiredPermission form Users of Mobile Applications.
For the Sales App
AR, IN, IC. modules are required
OE is optional
Minimum permissions for Sales App Users:
AR Customers
Access - Read
Price List - Read
Credit Limit - Read
Discount Code - Read
Stop Credit - Read
IC Products - Read
IN Invoices - Write
OE Orders - Write (if OE is available)
SP Special Pricing (if SP is available)
Reports > Queries - Selected
Who - Read
What - Read
Where - Read (Saturn only)
For the Inventory app
IC module is required
Minimum permissions for Inventory App Users:
IC Products - Read
IC Counts Write
Accredo Sales App Demo
Install the
Accredo Sales App
on your device. Click
Demo System
to use the app with demo data.
Accredo Inventory App Demo
Install the
Accredo Inventory App
on your device. Click
Demo System
to use the app with demo data.
In This Section
Accredo App Reports
Accredo Sales App Geocoding

---

## Accredo Module Compatibility

Source: https://accredo.co.nz/webhelp/AccredoModuleCompatibility.htm

Accredo Module Compatibility
The following Modules are available in Accredo. Some Modules are dependent on each other. See the
Accredo Module Integration diagram
for module integration details.
AR
Accounts Receivable (IN recommended)
Manage customer and sales information; design statements and labels; email statements individually or in batches.
IC
Inventory Control
Stock movements, values, quantities and prices; design labels, bar codes, product sheets; import quantities; set Units of Measure; perform stocktakes.
IN
Invoicing System (AR required, IC recommended)
Design and print invoices, credit notes, quotes, packing slips and labels.
OE
Order Entry (IN, AR, IC required)
Print, email sales orders, back orders, forward orders, packing slips and manage stock.
AP
Accounts Payable
Manage creditors, payments, shipments, purchases; design cheques, shipment documents and labels; email remittances individually or in batches; export payment batches.
PO
Purchase Orders (AP required, IC recommended)
Design and print purchase orders and labels.
CB
Cash Book
Manage cashflow, receipts, payments, cash on hand, import and reconcile bank statements.
FA
Fixed Assets
Manage fixed assets and depreciation schedules; enter additions, revaluations, disposals, depreciation for each period.
GL
General Ledger (Required)
Design reports using the Financial Report Writer and Wizard.
GST
Goods and Services Tax (Required)
Manage GST transactions and complete GST returns.
JC
Job Costing (AR, IC, IN, AP, PO recommended)
Create invoices, quotes and estimates and monitor costs and profit.
SP
Special Pricing (AR, IC, IN required, JC recommended)
Pricing based on factors such as customer, product, date or combinations.
SA
Sales Analysis (AR, IN required, IC, OE recommended)
Product by customer, customer by product, consolidated or detailed reports.
PA
Purchase Analysis (AP, PO, required; IC, JC recommended)
Consolidated or detailed reports; filters make this a powerful purchasing, reporting and management tool.
JA
Job Analysis (JC required; AR, IC, IN, PO, AP recommended)
Detailed reporting on job information.
DI
Data Interchange
Integrate applications or databases for import and export.
RD
Report Designer
Build SQL queries and design reports using the wizard or code.
FD
Form Designer (DI required, TD, RD recommended)
Create forms to interact with data objects and custom tables.
TD
Table Designer (DI required, FD recommended).
Create tables for Data Interchange automation and custom reporting.
WS
Web Service (DI required)
Communicate with Accredo via the web.

---

## Accredo Module Integration

Source: https://accredo.co.nz/webhelp/AccredoModuleIntegration.htm

Accredo Module Integration
See
Accredo Module Compatibility
for acronyms and descriptions.

---

## Accredo ODBC Connector for Power BI

Source: https://accredo.co.nz/webhelp/AccredoPowerBIConnector.htm

Accredo ODBC Connector for Power BI
The AccredoODBC.mez file is installed with the Accredo ODBC/OLEDB Driver.
To use the Accredo ODBC Connect the AccredoODBC.mez file
needs to be copied to :
Documents\Power BI Desktop\Custom Connectors
Then Power BI needs to be set up to allow non certified Data connectors to be seen:
File > Options and Settings > Options > Security > Data Extensions
Select "Allow any extensions to load"
AccredoODBC will then appear in the list of Other data sources.

---

## Accredo Qualified Support Person (QSP)

Source: https://accredo.co.nz/webhelp/AccredoQualifiedSupportPerson.htm

Accredo Qualified Support Person (QSP)
Accredo Qualified Support People (QSP's) are trained and accredited by Accredo Business Software Limited to install Accredo and provide support and training. Your QSP can set up Accredo and is your contact for assistance.
Find your QSP's phone numbers and other details from Accredo > File > Licensee Details > QSP tab.
Email your QSP from Accredo > Help > Mail QSP.
If the
Mail QSP
option is unavailable, this can be set up as follows:
Go to Accredo > File > Licensee Details... > QSP tab
Click
Edit
(F11)
.
Enter the QSP details, including the email address.
Click
Save
(F9)
.
See Also
Further Assistance

---

## Accredo Security Application

Source: https://accredo.co.nz/webhelp/AccredoSecurityApplication.htm

Accredo Security Application
After you first install Accredo, complete the Accredo Security Application. Until the Licensee Details are entered, all Accredo reports will print with an
"Unsecured"
watermark, and you will not be able to perform an End Of Period.
Open the Accredo Client. If the
Licensee Details
window doesn't open, select Accredo > File > Licensee Details.
Click
Edit
(F11)
to edit the Licensee Details.
Complete all details on the
Address
tab.
Complete all details on the
Details
tab. Press
Ctrl+Page Up
or
Page Down
, or click on the tab to move to another tab.
Complete details on the
QSP
tab. When you enter the QSP name and email, a link is added to the help menu, so you can automatically email the QSP.
Click
Save
(F9)
. The Licensee Details are saved, and the
Print
(Ctrl+P)
and
Secure
(Alt+S)
buttons will become available.
Click
Print
(Ctrl+P)
to print the Accredo Security Application.
In the
Destination
field, select
Printer.
Accredo will print to the default printer for Windows. To select another printer, click
Printer Settings...
(Alt+P)
and select the required printer.
Click
Run
(F9)
.
The
Accredo Security Application
will print to the selected printer.
Sign the
Accredo Security Application
and post, email or fax it to Accredo (the address and fax number are on the form).
When you receive the Security code from Accredo, enter it in the system, see
Accredo Security Code
.
See Also
Accredo System Setup

---

## Accredo Security Code

Source: https://accredo.co.nz/webhelp/AccredoSecurityCode.htm

Accredo Security Code
After the
Accredo Security Application
is completed, Accredo will return a 6 digit security code.
Accredo will not allow you to perform an End of Period until the Accredo Security Code has been entered. To enter the security code:
Go to Accredo > File > Licensee Details.
Click
Secure
(Alt+S)
.
Enter the Security Code provided by Accredo Business Software Ltd.
Click
OK
.
If the Accredo Warning "Invalid security number" appears:
Click
Close.
Ensure the Security Code entered is correct and all information in the
Licensee Name
field of the
Licensee Details
window matches the information on the Accredo Security Application.
Repeat steps above.
If the warning appears again, contact Accredo Support or your Accredo QSP.
See Also
Accredo System Setup

---

## Accredo System Setup

Source: https://accredo.co.nz/webhelp/AccredoSystemSetup.htm

Accredo System Setup
First create a company before adding data and using Accredo.

---

## Accredo Training

Source: https://accredo.co.nz/webhelp/AccredoTraining.htm

Accredo Training
We recommend on-site training from your Accredo QSP when:
Accredo is installed
Accredo is updated
New staff are employed who will be using Accredo.
Because business processes and practices are different in every organisation, your QSP can tailor your training to your needs.
In addition to on-site training provided by your QSP, customised training courses facilitated by Accredo trainers can be provided for a minimum number of participants. To discuss options for customised training, contact your Accredo QSP.
See Also
Further Assistance

---

## Accredo VSS

Source: https://accredo.co.nz/webhelp/AccredoVSS.htm

Accredo VSS
The Volume Snapshot Service (VSS), also known as Volume Shadow Copy Service, is a technology included in Microsoft Windows that allows taking manual or automatic backup copies or snapshots of computer files or volumes, even when they are in use.
The Accredo VSS Writer is backup software that plugs into Windows VSS. It makes use of Windows VSS, so that VSS clients such as ShadowProtect can take consistent snapshots of Accredo while it is in use.
The Accredo VSS Writer can be asked to briefly "freeze", which will prevent writes while the Snapshot is taken, and then "thaw", which will allow writes. Taking a Snapshot on a server usually takes less than a minute (typically around 15 seconds) with time taken influenced mostly by writes which are currently in progress that must be completed before the Snapshot can be taken.
Use with The
Accredo VSS Backup
utility or a third-party backup solutions that supports volume snapshots, as this will allow backups to be seamlessly made while Accredo is in use.
Installing the Accredo VSS Writer
The SetupAccredoVSS.exe file is the installer. Install this on the Server where Accredo is installed.
The AccredoVSSWriter.ini file sets the configuration for the VSS service. In the ini file, the System path must point to the Accredo System it is managing. The ini file needs to be in the same directory as the installed exe file.
The correct version of the service must be installed to match the operating system, either 64 bit or 32 bit. The installer should detect and install the correct version automatically.
Running the Accredo VSS Writer
Start the VSS either from the Windows Services Manager or from the command line.
VSS Options:
Install - install the service.
Remove - remove the service.
Info - display information about the service.
Start - start the service.
Stop - stop the service.
Freeze - freeze the VSS Writer. Service must be running.
Thaw - thaw the VSS Writer. Service must be running.
The service links to the VSS structure that the backup clients will be talking to.
VSS Ini File
Output for the VSS Writer defaults to the .exe directory, with a file name of AccredoVSSWriter.Log, unless an output default file is specified in the .ini file.
A sample .ini file is:
[Config]
SystemPath = c:\Saturn400
// StopEventLogOutput controls whether messages get output to the Windows event log
StopEventLogOutput = FALSE
// Also write output messages to the OutputLog file
OutputLog = c:\data\VSSWriter.Log
// 0 = Critical only
// 1 = Important + Critical
// 2 = Information + Important + Critical
Verbosity = 2
// the maximum amount of time (milliseconds) to spend acquiring a Freeze/Thaw
FreezeAcquireTimeout = 60000
// If the VSS crashes, IncludeMiniDump will create a *.dmp file and add a stacktrace to the output log
IncludeMiniDump = TRUE
VSS Admin
Note that some VSS Admin tools do not involve writers when creating snapshots. This can be checked by running the VSS Admin lists shadows and checking that writers display in the attributes.
See Also
Accredo Maintenance

---

## Accredo Website

Source: https://accredo.co.nz/webhelp/AccredoWebsite.htm

Accredo Website
The
Accredo website
contains:
Help for modules.
Support documents providing tips for Users and information on issues and problems.
Information and applications for download and use.
Contact details for Accredo Business Software Ltd and Accredo QSP's.
See Also
Further Assistance

---

## Add and Delete Company Users

Source: https://accredo.co.nz/webhelp/AddAndDeleteCompanyUsers.htm

Add and Delete Company Users
Navigator > Setup > Company > Users > Users, Groups and Roles
To add a User to a Company:
Click
Insert
(F4)
. Select
User
.
Enter the following fields with the User's details:
Code,
the code for the User.
Name,
the name of the User.
Password.
Enter other fields if required.
Go to the Permissions tab
(Alt+P)
. If the User will be in a group, select the
Permission Group
. Otherwise, edit the individual permissions for the user.
If the User has Roles, go to the Roles tab
(Alt+R)
. Select the roles for the user.
Set options on the other tabs, if required.
Click
Save
(F9)
.
To delete Users from a Company,
Select the User to delete in the
Select User
field.
Click
Delete
(F3)
You will be asked if you have changed the Target User for any Reminders / Memos / Alarms assigned to the user. If you select
No
, you will be taken to the
Change Memo Target User
form. If you select
Yes
, you will be asked to confirm whether to delete the record.
If you confirm to delete the user details, user details are deleted and will no longer appear in the
Select User
list.
See Also
Users, Groups and Roles - User tab

---

## Add Company User to System

Source: https://accredo.co.nz/webhelp/COUsers_AddToSystem.htm

Add Company User to System
If SSO is enabled and the logged in user has system permissions.
Either saving a new Company User or selecting
Add User to System
from the toolbar prompts:
If the User code being added is not found at the system level:
User XXXX does not exist in System.
Add as a system user?
If
Selected
the user is replicated as a system user with the Company added to the users Companies tab. No system level permissions are granted to the new user.
If the User code being added is found at the system level:
User XXXX - Name exists in System.
Add to system user's company list?
If
Selected
the Company is added to the System user's Companies tab.

---

## Branches

Source: https://accredo.co.nz/webhelp/CompanyBranches.htm

Branches
Branches are only available for Accredo Saturn.
Navigator > Setup > Company > Configuration > Branches
Setup and maintain Branch codes and names.
Code
Enter a unique alpha numeric code of up to 8 characters.
Valid characters for new Branch Codes are A-Z, 0-9 by default. Other characters to allow may be specified in
Company Settings - Misc tab
.
Name
Enter a name.
Address
Enter an address.
Phone Nos
Customer telephone numbers. If Accredo is setup to interface with the
telephone system
, click
to dial.
Note: You can change the labels of the phone no fields in
Company Settings - Display Labels
.
Email Address
The contact email address. Click
to create a
Mail Message
(Ctrl+M).
Custom
Enter additional information for scripting, custom reporting, or other purposes. Labels can be replaced in
Company Settings
.
Inactive
Select this or press the
Space Bar
while in the
Inactive
field. Lines for inactive Branches are shown dimmed. Transactions cannot be posted, and will not appear in lookups for Branch codes outside the GL. Inactive Branches will still perform inside the GL.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Open Branch data in Form view to add, delete, edit and scroll. Move off the field to save changes, they will appear on
CLOSE
To edit the name select it and enter another. To change a Branch code, see
Merge Codes
.
Insert
(F4)
Click below the last Branch code in the grid, enter a code and name.
Delete
(F3)
To delete a Branch, select the line. You cannot delete a Branch if other records are linked, or if transactions have been analysed to it.
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
, you can customise the fields to appear in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Customise Toolbar
Customise Toolbar or right-click in the toolbar below the buttons to access the
Customise Toolbar Menu
.
See Also
Configuration

---

## Change a Password

Source: https://accredo.co.nz/webhelp/ChangeAPassword.htm

Change a Password
For System Users, passwords can be changed from System User form or from the System Login. For Company Users not linked to a System User, passwords can be changed from Users, Groups and Roles, or from the User Login (permission dependent).
To change a password from the User form:
For System Users, go to Accredo > File > System > Users.
For Company Users, go to Navigator > Setup > Company > Users > Users, Groups and Roles.
Select the User to change the password for. Click
Edit
(F11).
Enter the new password in the following fields:
Password
Confirm Password
Click
Save
(F9)
. The new password is saved and the fields cannot be edited.
To change a password from the
System Login
or
User Login
:
You can change a password when the User Login opens, when you start Accredo. You can also access User Login from Accredo > View > Company Login, or by clicking the User ID in the lower status bar at the bottom right of the Accredo window.
Click
Change Password
(Alt+C)
.
Enter the
User Code
,
Old
and
New Passwords
.
Click
OK
.
User Login
will open again, with a confirmation message.
See Also
Users, Groups and Roles - User tab

---

## Configuring Access for Accredo Mobile Applications

Source: https://accredo.co.nz/webhelp/WSMobileAppAccess.htm

Configuring Access for Accredo Mobile Applications
Mobile access to Accredo requires that the Accredo Web Service has been installed and configured correctly.
Mobile Application Provisioning
See:
Web Client Provisioning
Add a client for the appropriate Accredo app.
Accredo Application Configuration
If you are setting up one of the Accredo mobile apps, you will need to enable Change Tracking for the mobile apps that you are adding.
Navigator > Setup > Company > Configuration >
Change Tracking
Edit and select
Add Tables for Mobile App from the toolbar, select the relevant Accredo app you are adding and click save.

---

## Customise Buttons

Source: https://accredo.co.nz/webhelp/ButtonCustomisation.htm

Customise Buttons
Customise Toolbar  > Customise Buttons
or Right-click  in the toolbar to access the Customise Toolbar > Customise Buttons.
Customise button ordering and visibility for toolbar buttons including any added as
script shortcuts
.
Grid
Glyph
The glyph for the button as it appears on the toolbar.
Button Name
The Button Name as it appears in the Menu.
Visible
Controls visibility and availability for the button.
Toolbar and Menu
, the button is visible in the toolbar, available in the menu and via the keyboard shortcut.
Menu Only
, the button does not appear in the toolbar but is available in the menu and via the keyboard shortcut. Set less frequently used options to Menu Only.
Not Visible
, the button does not appear on the toolbar nor in the menu and cannot be triggered by the keyboard shortcut. Functionality is still script enabled.
Note: Insert and Delete buttons can not be set
Not Visible
.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Move record up/down
(Shift+Up) (Shift+Down)
Change the button position.
Print
(Ctrl+P)
Print a report of the information in the grid.
Customise Fields
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Sort Buttons
(Alt+O)
Sorts buttons with Toolbar and Menu visible buttons to the top, then Menu Only visible buttons, then Not Visible buttons and preserves ordering within those groups.
Refresh Button
(Alt+B)
Set the Visibility for the current row to the default.
Restore defaults
(Alt+R)
Restore the Visibility for all rows field settings to their defaults.
Buttons
Load
(Alt+L)
You can load a customisation saved for a User or Group, or a global customisation saved for All Users. Save, maintain, or use it as the basis for another customisation (see
Permissions
). If an option is unavailable, no customisation is saved for the User or Group.
Delete
(Alt+D)
To delete a customisation
,
select a customisation from the drop-down. If an option is unavailable, no customisation is saved for the User or User Group.
Apply
(Alt+A)
Closes the window and applies changes without saving. To save changes, re-open
,
click
Save.
Save
(Alt+S)
Select the User, Group, Role or
Global
from the drop-down.
List is ordered as follows: Global; Current User; Users or Groups with saved customisations; other Groups; other Users.
Close
(Esc)
Closes the window without applying changes.
Apply and Save
(F9)
Save a customisation for a User or User Group, or globally for All Users who do not have a customisation saved for a User or User Group, closes the window and applies the changes.
Select the User or User Group, or
Global
from the drop-down.
List is ordered as follows: Global; Current User; Users or Groups with saved customisations; other Groups; other Users.

---

## Customise Fields

Source: https://accredo.co.nz/webhelp/GridCustomisation.htm

Customise Fields
Click
Customise Fields
(Alt+F5)
, or right-click
on the Lookup then click
.
If you drag to change field width and position without opening
Customise Fields
, changes are not saved on
CLOSE
.
Field Name
Lists all the database fields available for the grid.
Note: For reference fields, an alternate Alpha field called
Reference
Alpha is available to allow alphanumeric sorting by the field. For example you can select the OE
OrderNoAlpha
or the AR
DocumentNoAlpha
field to sort alphabetically by OE Order No or AR Document No.
Visible
Only selected fields will appear. Click to toggle. When you open
Customise Fields
, all visible fields are listed first in the order they will appear in the grid. Non-visible fields are listed alphabetically below visible fields. To retain the non-alphabetical position of non-visible fields, select
Save non visible field settings
, This is useful for grids where Zoom is available. As all fields both visible and non-visible are available on Zoom, you can apply a position to additional fields not shown on the grid.
Display Label
The heading that shows at the top of the field if the field is
visible
Display Label will trim spaces at the end of the label. To save a label with space at the end, such as for alignment of a report label, use a non-breaking space.
For a non-breaking space hold down
Alt
while keying
0160
using the number pad.
Field Width
The width of the field in characters. The digit
0
is used as the standard width character. If the field contains all upper case characters, set it wider than the number of characters to see all the data in the field.
Total
Supports grid based reporting on numeric fields.
Selected,
a total will be added to reports based off the grid.
Label Width
For Data Panels, the width of the label in characters. The digit
0
is used as the standard width character. If the label contains all upper case characters, set it wider than the number of characters to see all the data in the field.
Row
For Data Panels, specify which row of the data panel the field is displayed in.
Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Move record up/down
(Shift+Up) (Shift+Down)
Change the field position.
Print
(Ctrl+P)
Print a report of the information in the grid.
Select/
Unselect all
(Shift+F4) (Shift+F3)
Select or clear all fields.
Sort fields
(Alt+O)
Sorts visible fields to the top in the order they were selected, then other fields alphabetically.
Refresh Field
(Alt+F)
Set the Display Label and Field Width for the current row to the default.
Restore defaults
(Alt+R)
Restore field settings to their defaults.
Import
(Ctrl+I)
Import grid customisation from a json file.
Export
(Ctrl+E)
Export grid customisation as a json file.
Buttons
Load
(Alt+L)
You can load a customisation saved for a User, Group, or Role, or a global customisation saved for All Users. Save, maintain, or use it as the basis for another customisation (see
Permissions
). If an option is unavailable, no customisation is saved for the User, Group or Role.
Delete
(Alt+D)
To delete a customisation
,
select a customisation from the drop-down. If an option is unavailable, no customisation is saved for the User or User Group.
Apply
(Alt+A)
Closes the window and sorts and applies changes without saving. To save changes, re-open
,
click
Save.
Save
(Alt+S)
Select the User, Group, Role or
Global
from the drop-down.
List is ordered as follows: Global; Current User; Users, Groups or Roles with saved customisations; other Groups and Roles; other Users.
Save non visible field
settings
Selected,
saves the position of all fields if the
Visible
field is selected or not, they will appear in the specified position in Zoom view.
Clear
, Zoom view will show visible fields in the position specified in
Customise Fields
, non-visible fields will appear alphabetically below the visible fields. Access to non-visible fields requires Company Zoom Permissions.
Close
(Esc)
Closes the window without applying changes.
Apply and Save
(F9)
Save a customisation for a User or User Group, or globally for All Users who do not have a customisation saved for a User or User Group, closes the window, sorts and applies the changes.
Select the User or User Group, or
Global
from the drop-down.
List is ordered as follows: Global; Current User; Users, Groups or Roles with saved customisations; other Groups and Roles; other Users.
See Also
Customise Grids

---

## Customise Grids

Source: https://accredo.co.nz/webhelp/CustomiseGrids.htm

Customise Grids
Most Accredo grids can be customised to show different information. You can:
Choose fields to show in the grid (and those to hide).
Change the Display Label (heading) for a field.
Change the field width.
Change the order of the visible fields.
Change the order of fields on the corresponding Zoom form (if available).
Set totals for grid-based reporting (if available).
Check that fields are visible on the grid.
Save customisations (see
permissions
) for a User, User Group, or globally for a Company.
Before opening
Customise Fields
, you can adjust field width and position:
Field width,
drag the right hand border of the field heading.
Field position,
drag the field.
You can view the main window as you make changes. Settings are retained when you open Customise Fields and save them. To access grid customisations:
Click
Customise
(
Alt+F5
) or right-click a field containing a drop-down, click
Customise
.
Make changes to the fields displayed.
Click
Apply
(Alt+A)
to save temporarily and go back to the main window to view the new settings. Changes will be lost when you close the main window - OR -
Click
Save
(Alt+S)
to save the changes - OR -
Click
Apply and Save
(F9)
to apply and save the changes.
In This Section
Customise Fields
See Also
Global Tools

---

## Customise Layout - Preferences tab

Source: https://accredo.co.nz/webhelp/ReportSelections_Preferences.htm

Customise Layout - Preferences tab
Navigator > Reports > [Module] > Add Layout > [Select Report] >
Options
button > Customise > Preferences tab
Global report default preferences are set in Navigator > Setup > Company > Reporting >
Report Preferences
.
Preferences can be changed on a one off basis from
Report Selections Form
>
Options
button
> Preferences.
Only options available for the layout are enabled. For Fixed Layout reports, some options are not available.
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
by default column headings will be frozen. See
Report tab
to set
Freeze Excel column
.
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
Include Created Modified in Footer
Selected,
shows the User code and date the layout was created, and last modified in Customise Layout.
Hide Filters,
Hide Selections,
Hide Sorting
Selected,
hide options from being printed at the start of the report.
Reporting Fonts
Select the font for each section. Click the relevant font button to open Windows fonts.
Align Title  AlignSelections
Select the alignment for the Report Title and Selections.
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
See Also
Customise Layout - Report tab

---

## Customise Layout - Report tab

Source: https://accredo.co.nz/webhelp/ReportCustomisation.htm

Customise Layout - Report tab
Navigator > Reports > [Module] > [Folder] > Add Layout >
Options
>
Customise
- OR -
Navigator > Reports > [Module] > [Folder] > Add Layout > Right-click >
Add Layout
,
Edit Layout
OR
Duplicate Layout
Reports can be customised to show different information. Information bands are shown in different tabs, depending on what is available to the individual report. Select fields in different tabs to be included in the report.
Use the
Preferences tab
to set design preferences, and the
Users tab
to set user access for the report.
Report options are dependent on
Permissions
. Access to customise report layouts is controlled as followed:
Access Permission
Layout Permission
Customisation permitted
None (0)
Any
None
Read (1)
Any
None
Write or Control (>1)
None (0)
None
Write or Control (>1)
Read (1)
One time customisation, cannot save.
Write or Control (>1)
Write (2)
Edit customisations for existing layouts. Cannot edit Users tab. Cannot Add or Delete.
Write or Control (>1)
Control (3)
Full customisation access. Can modify Users.
Fields
Layout Name
The name that will appear in the Navigator. Click
Selections
to set defaults for the
Report Selections Form
.
To show the report in a sub-folder in the Navigator, include the folder name followed by
\
then the report name. For example,
Stock\Stock Levels
will display the
Stock Levels
report in a
Stock
folder. Some examples are:
\LayoutName
will move the layout to the
Reports >
folder
\FolderA\LayoutName
will move the layout to
Reports > FolderA
folder
\AR\FolderB\LayoutName
will move the layout to the
Reports > AR > FolderB
subfolder
FolderC\LayoutName
will move the layout to subfolder
FolderC
in the report's current folder, such as
Reports > AR > Customer Reports > FolderC
Note: You cannot change the name or Selections defaults when you access Customise Layout from
Options
> Customise in the Report Selections Form.
Report Title
The title of the report that will appear on Report Selections Form and the printed report. When the Layout Name is changed the report title will update.
Short Name
The default name to be used when the report is saved to a Disk File or Excel Worksheet.
Selections
Click to set defaults for the
Report Selections
dialog when the report is opened.
Not available from Report Selections > Options > Customise.
Sort Order
The position in a
Navigator
folder, with lower number items shown before higher number items.
Display Navigator Item Ordering
(Ctrl+H)
will show or hide the order numbers on items in the Navigator.
Tab Order
Select the position of the tab, when a new Tab is added. For existing tabs, the order number is displayed.
Tab Name
Select or enter the Navigator tab for the shortcut to appear on. To add a new tab to the Navigator, enter a new tab name.
Filter / Sort Table
(Ctrl+F2)
Apply or clear a
Filter & Sort
. The button changes to indicate if a filter and sort is applied.
Table
For multi-table reports, determine the fields to appear that a Filter & Sort applies to. A table corresponds to a band. All tables available for a report can be customised. For single table reports, this is unavailable, as the table is selected.
Grid
To include an item select the
Visible
field. The selected field will appear left of the report.
Field Name
Lists the database fields available on the report layout for the selected table.
Display Label
The field heading to appear in a report, only appears if the field is marked visible.
Width
The width of the field in characters. The digit
0
is used as the standard width character. If the field contains all upper case characters and proportional fonts, set it wider than the number of characters to report all the data in the field.
Group
Add grouping to reports. To group the report on a field, enter a digit (
1-9
) in this field. The number represents the grouping level -
1
is the outermost level of grouping. It is unusual to group more than one level, to select grouping enter
1
in this field for all grouping fields, for example, to group an inventory report on Stock Group, enter a
1
in this field for
StockGroupCode
and
StockGroupName.
Group numbers must start from 1, and must be consecutive.
Freeze Excel
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
columns will be frozen at this column. See
Preferences tab
to
Freeze Excel Headers
.
Total
Only available for numeric fields.
Selected,
the field total is shown. Click to toggle the value.
Blank Zero
Select this beside the fields to display blank if the amount is zero.
Format
A string of characters that determines how the result of the expression is formatted on the printed report.
Domain
Field domain (read-only).
FX Code Field
For FX Fields, the FX Code Field (read-only).
Origin
Field location in the database.
Label Visible
Selected
, the field Display Label is shown in the report.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Move
(Shift+Up) (Shift+ Down)
Select a field name, click to order the list of fields. Move an item down the grid (further to the right of the Report). Click to move an item up the grid (further to the left of the report).
Print
(Ctrl+P)
Print a report of the information in the grid.
Select all
(Shift+F4)
Select all fields.
Unselect all
(Shift+F3)
Unselect all fields.
Sort fields
(Alt+O)
Moves selected fields to the top of the list in the order they were selected, and sorts the rest alphabetically.
Refresh field
(Alt+F)
Set the Display Label and Field Width for the current row to the default.
Restore Defaults
(Alt+R)
Restore field selections to the defaults for a new layout.
Buttons
Save
Save the customised layout with the Layout Name. Customisations will apply when the report is
Run
. If you edit an existing layout, this will overwrite the file.
Cancel
(Esc)
Cancels changes without saving and closes the window. If you use
Restricted Customise Layout,
this will retain the previously saved Report layout.
One Time
(F9)
You can preview the Report layout, (only in
Restricted Customise Layout
), saving the current session, and is available when you access Customise Layout from
Report Selections Form
>
Options
> Customise.
Closes Customise Layout while retaining changes for the report, click
Save.
Hint: Preview in
Report Preview
from Report Selections Form >
Options
>
Save.
In This Section
Customise Layout - Preferences tab
Customise Layout - Users tab
See Also
Global Tools

---

## Customise Layout - Users tab

Source: https://accredo.co.nz/webhelp/ReportSelections_Users.htm

Customise Layout - Users tab
Navigator > Reports > [Module] > Add Layout > [Select Report] >
Options
button > Customise > Users tab
Accredo reports are available to all Users by default.
Enter a list of Users or Groups to make the report available to only the users listed subject to Permissions.
Note: If a user has Control permission for the Module Reports it gives Access to all reports, and the user list is ignored.
User
The User Code or User Group code. Enter the User code or select from the drop-down menu.
Name
The User Name, from the User code. Read-only.
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
See Also
Customise Layout - Report tab

---

## Customise Tab

Source: https://accredo.co.nz/webhelp/TDCustomiseTab.htm

Customise Tab
You can customise the Custom tab from Navigator > Maintain > [Module] > [Masterfile] > Custom tab > Right-click > Customise.
You can edit and set values for component properties to adjust their appearance and behaviour. Properties associated with the selected component will appear.
Components can be set to Read Only. Note that this applies only at the form level. Component values can still be changed at the data level.
To edit the Custom tab name, find the
formname
.tabCustom component in the component drop-down list, and change the
Tab Caption
.
You can create tabs within the custom tab to organise your custom fields. To create a tab, select a field component to be included on the tab. Set the
Tab Name
for the field to the name you want to give the new tab.
Load
(Ctrl+L)
You can load a customisation saved for a User, User Group, or a global customisation saved for All Users. Save, maintain, or use it as the basis for another customisation, (
Permission
dependent). If an option is unavailable, no customisation is saved for the User or User Group.
Delete
(Ctrl+D)
To delete a customisation
,
select a customisation from the drop-down. If an option is unavailable, no customisation is saved for the User or User Group.
Apply
Closes the window and applies changes without saving. To save changes, re-open
,
click
Save.
Restore Defaults
(Alt+R)
Restore the default field settings.
Save
Select the User or User Group, or
Global
from the drop-down.
List is ordered as follows: Global; Current User; Users or Groups with saved customisations; other Groups and Roles; other Users.
Close
Closes the window without applying changes.
Apply and Save
(F9)
Save a customisation for a User or User Group, or globally for All Users who do not have a customisation saved for a User or User Group, closes the window and applies the changes.
Select the User or User Group, or
Global
from the drop-down.
List is ordered as follows: Global; Current User; Users or Groups with saved customisations; other Groups and Roles; other Users.
Customise Tab Context Menu
To access the Form Designer Context Menu, right-click in the Form Designer design window. Options available in the context menu are:
Bring To Front
Bring the component(s) to the front, in front of other components.
Send To Back
Send the component(s) to the back, behind other components.
Align...
Available when more than one component is selected. Opens the
Alignment
window to align the selected components to each other.
Select All
(
Ctrl+A
)
Select all components on the form.
Move...
Opens the
Move Components
window to move the component(s) by a set amount.
Note: Forms with a Custom tab have a scripted LoadCustomisation(UserCode: String) method which allows customisation saved for a User, Group or Role to be loaded. e.g. to have a field customised as Read Only in the UI but accessible during a form script event.
In This Section
Customise Tab Alignment
Customise Tab Move Components
See Also
Custom Tab

---

## Customise Tab Alignment

Source: https://accredo.co.nz/webhelp/CTAlignment.htm

Customise Tab Alignment
Navigator > Maintain > [Module] > [Masterfile] > Custom tab > Right-click > Customise [Select Component(s)] > Right-click >
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

## Customise Tab Move Components

Source: https://accredo.co.nz/webhelp/TDMoveComponents.htm

Customise Tab Move Components
Navigator > Maintain > [Module] > [Masterfile] > Custom tab > Right-click > Customise [Select Component(s)] > Right-click > Move...
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

## Customise Toolbars

Source: https://accredo.co.nz/webhelp/CustomiseToolbars.htm

Customise Toolbars
Customise Toolbar or Right-click  in the toolbar to access the Customise Toolbar Menu.
Menu
Add Shortcut
Add a new
shortcut
to the toolbar.
Add Script Event
Add a
Script Event
for the form.
View Script Events
View all
Script Events
for the Module.
Refresh Cached Scripts
Reloads cached script events.
Customise Buttons
Opens
Customise Buttons
, you can customise button visibility and order for the menu.
Refresh Toolbar
Reload toolbar e.g. where a shortcut has been added since the form was opened, or the logged in user is changed while the form is open.
In This Section
Customise Buttons
See Also
Global Tools

---

## Decimals

Source: https://accredo.co.nz/webhelp/CompanyDecimals.htm

Decimals
Navigator > Setup > Company > Configuration > Decimals
Set the number of decimal places for a variety of figures. Edit decimal options when you setup a Company for the first time.
Decimal places for:
Amounts
are determined by the Currency code for the amount.
Cost Prices
and
Selling Prices
can be set per currency, including your Base currency from Navigator > Setup > Foreign Exchange >
Currencies
.
Discounts (0-4)
Specify the decimal places for discounts on invoices set in the Discount Schedule.
Markups (0-4)
If you have IC installed and use mark-ups to calculate Selling Prices, you can set the number of decimal places for mark-up percentages.
Quantities (0-6)
Supply goods and control stock in whole units, or fractions of a unit. You can state quantities with up to six decimal places for an accuracy of 0.000001, for example, if you sell items in kilograms or litres.
Warning: To decrease the number of decimal places for Quantities, you will first need to deal explicitly with part quantities In Stock. Do this by entering an adjustment transaction or complete a stocktake to clear the part quantity and then update variances. Check there are no part quantities on Pending Stock Movements, and edit any pending documents as necessary.
Quantity Multipliers (0-8)
For
UOM
, the maximum number of decimal places accepted for UOM Multipliers. UOM Multipliers determine how many of the UOM to convert to the Base UOM.
Weights (0-6)
IC installed, determine the decimal accuracy for the Weight field.
Volumes (0-6)
IC installed, determine the decimal accuracy for the Volume field.
Tax Rates (0-4)
Specify the number of decimal places for the GST rate.
Depn Rates (0-4)
FA installed, specify the number of decimal places for Depreciation rates.
Exchange Rates (0-9)
Specify the number of decimal places for Exchange rates.
Duty Rates (0-2)
Specify the number of decimal places for Duty rates.
Interest Rates (0-9)
Specify the number of decimal places for Interest rates.
Amounts Max Digits
The maximum number of digits allowed for Amount figures. This includes digits both sides of the decimal point. For example, if this were set to
10
, and you allow
2
decimal places for Amounts in
Currencies
, the maximum amount allowed would be
99999999.99
(10 digits).
Setting this to
12
or lower can prevent bar codes accidentally being scanned in to Amount fields.
Prices Max Digits
The maximum number of digits allowed for Price figures. This includes digits both sides of the decimal point. For example, if this were set to
10
, and you allow
4
decimal places for Prices in
Currencies
, the maximum price allowed would be
999999.9999
(10 digits).
Setting this to
12
or lower can prevent bar codes accidentally being scanned in to Price fields.
Quantities Max Digits
The maximum number of digits allowed for Quantity figures. This includes digits both sides of the decimal point. For example, if this were set to
10
, and you allow
3
decimal places for
Quantities
, the maximum quantity allowed would be
9999999.999
(10 digits).
Setting this to
12
or lower can prevent bar codes accidentally being scanned in to Quantity fields.
Edit
(F11)
Enter edit mode.
Save
(F9)
Save changes.
Cancel
(Esc)
Discard changes and close the form.
See Also
Configuration

---

## default

Source: https://accredo.co.nz/webhelp/90.htm#o5516

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

## Default Formats

Source: https://accredo.co.nz/webhelp/MBDefaultFormats.htm

Default Formats
Unless a format string is specified, MaxBasic uses the following formatting.
Data Type
Default format
Dates
Windows short date format.
Times
Windows time format.
Monetary amounts and prices
Decimal places, grouping and currency symbols from
FX Currency
and, formatting per context from Company > Configuration > Settings >
Currency Format tab
.
Other numbers, for example, quantities, results of numeric expressions
Decimal
places for the domain or Windows number format if domain is not known.
See Also
MaxBasic Formatting

---

## Departments

Source: https://accredo.co.nz/webhelp/CompanyDepartments.htm

Departments
Departments are only available for Accredo Saturn.
Navigator > Setup > Company > Configuration > Departments
You can setup and maintain Departments and their codes.
Code
Enter a unique alpha numeric code of up to 8 characters.
Valid characters for new Branch Codes are A-Z, 0-9 by default. Other characters to allow may be specified in
Company Settings - Misc tab
.
Name
Enter a name for each Department.
Custom
Two custom fields are provided for scripting, custom reporting, or other purposes. Labels can be replaced in
Company Settings
.
Inactive
To make a Department inactive, click or press the
Space Bar
in the
Inactive
field. Lines for inactive Departments appear dimmed. You cannot post transactions for inactive Departments, and they will not be shown in lookups for Department codes outside the GL. Inactive Departments will still be active in the GL.
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Opens a separate window showing the Department data in Form view. You can add, delete, edit and scroll each Department. Changes are saved as you move off the field, and will appear on the grid. To change a Department code, see
Alias codes
.
Insert
(F4)
To add an additional Department, click below the last Department code in the grid, enter a code and name.
Delete
(F3)
Click in the line to be deleted. You cannot delete a Department if other records are linked to it, or if transactions have been analysed to it.
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
, you can customise the fields.
Refresh
(F5)
Reloads changes other Users may have made.

---

## Document Defaults

Source: https://accredo.co.nz/webhelp/CompanyDocumentDefaults.htm

Document Defaults
Navigator > Setup > Company > Reporting > Document Defaults
Setup the name of the document definition file and email template to use when printing or emailing documents and specify the default printer.
Accredo provides example documents and email templates. If you change these save with a different filename and change the default document / template, or select the files every time you print. You can specify a path name to the files, however if the files are located in the standard folder for the file type, the path will not be shown. When Accredo is looking for the file, it will search in the usual location under the Accredo database directory. If you specify the file name, it can be accessed from a computer running Accredo.
Type
Type of document.
Log
Available for some documents only.
Selected
, print events are logged with details of the user, date and time of printing and the destination. Print log can be accessed from the document or
CO Print Log
.
Document
The name of the document definition file for printing. You can change the default if you use custom documents.
PDF Document
The document definition file to be used when creating a PDF file. You can use this if you have a different document format for emailing.
Email Template
The default email template to be used for email messages.
Default Printer
The default printer for reports is configured from Accredo > File > Print Setup.
Documents can have their own default printers. For example, you may have a dedicated label printer. The printer selected applies only to the computer it is entered on, as each computer may have different printers set.
Bin
The paper source for the printer. The options available depend on the
Default Printer
selected.
Duplex
Select the printer duplex mode for the document from:
One side
- prints on one side of paper.
Long edge
- prints on both sides of paper, flips on long edge.
Short edge
- prints on both sides of paper, flips on short edge.
The default paths (sub-folders of the Accredo database directory) for documents are:
Type
Default Location
Default File Name
Default Email
Template File Name
AP Cheque
Reports\APRemit
APCheque.pfd
AP Creditor Batch Labels
Reports\APLabel
APLabelSample.pfd
AP Creditor Label
Reports\APLabel
APLabelSample.pfd
AP Creditor Sheet
Reports\APCredSheet
APCreditorSheet.pfd
AP Memo Report
Reports\APMemo
APMemo.pfd
AP Remittance Advice
Reports\APRemit
APRemit.pfd
APRemit.html
AP Shipment
Reports\APShipment
APShipment.pfd
APShipment.html
AP Shipment Product Labels
Reports\ICLabel
AR Customer Batch Labels
Reports\ARLabel
ARLabelSample.pfd
AR Customer Label
Reports\ARLabel
ARLabelSample.pfd
AR Customer Sheet
Reports\ARCustSheet
ARCustomerSheet.pfd
AR Memo Report
Reports\ARMemo
ARMemo.pfd
AR Receipt
Reports\ARReceipt
ARReceipt.pfd
ARReceipt.html
AR Statement
Reports\ARStatement
ARStatement.pfd
ARStatement.html
CB Memo Report
Reports\CBMemo
CBMemo.pfd
CO Memo Report
Reports\COMemo
COMemo.pfd
FA Asset Batch Labels
Reports\FALabel
FALabelSample.pfd
FA Asset Label
Reports\FALabel
FALabelSample.pfd
FA Memo Report
Reports\FAMemo
FAMemo.pfd
GL Memo Report
Reports\GLMemo
GLMemo.pfd
GST Memo Report
Reports\GSTMemo
GSTMemo.pfd
IC Basic Stocktake
Reports\ICStocktake
ICBasicStocktake.pfd
IC Bin Batch Labels
Reports\ICLabel
ICBinLabelSample.pfd
IC Bin Label
Reports\ICLabel
ICBinLabelSample.pfd
IC Count
Reports\ICCount
ICCount.pfd
IC Manufacture Sheet
Reports\ICManufacture
ICManufacture.pfd
IC Memo Report
Reports\ICMemo
ICMemo/pfd
IC Product Batch Labels
Reports\ICLabel
ICLabelSample.pfd
IC Product Label
Reports\ICLabel
ICLabelSample.pfd
IC Product Sheet
Reports\ICProdSheet
ICProductSheet.pfd
IC Stocktake Sheet
Reports\ICStocktake
ICStocktake.pfd
IC Transfer
Reports\ICTransfer
ICTransfer.pfd
IC Transfer Dispatch Labels
Reports\ICLabel
ICLabelSample.pfd
IC Transfer Receipt Labels
Reports\ICLabel
ICLabelSample.pfd
IN Invoice
Reports\INInvoice
INInvoice.pfd
INInvoice.html
IN Invoice Label
Reports\INLabel
INLabelSample.pfd
IN Invoice Product Labels
Reports\ICLabel
ICLabelSample.pfd
IN Memo Report
Reports\INMemo
INMemo.pfd
IN Packing Slip
Reports\INInvoice
INInvoice.pfd
INInvoice.html
IN Quote
Reports\INInvoice
INInvoice.pfd
INInvoice.html
JC Job Batch Labels
Reports\JCLabel
JCLabelSample.pfd
JC Job Label
Reports\JCLabel
JCbelSample.pfd
JC Job Sheet
Reports\JCJobSheet
JCJobSheet.pfd
JCJobSheet.html
JC Memo Report
Reports\JCMemo
JCMemo.pfd
JC Quotation
Reports\JCJobSheet
JCQuote.pfd
JCQuote.html
OE Confirmation
Reports\OEPackingSlip
OEConfirmation.pfd
OEConfirmation.html
OE Memo Report
Reports\OEMemo
OEMemo.pfd
OE Order Label
Reports\OELabel
OELabelSample.pfd
OE Order Product Labels
Reports\ICLabel
ICLabelSample.pfd
OE Packing Slip
Reports\OEPackingSlip
OEPackingSlip.pfd
OEPackingSlip.html
PB Definition
Imports\PBImports
(none)
PO Memo Report
Reports\POMemo
POMemo.pfd
PO Order Label
Reports\POLabel
POLabelSample.pfd
PO Order Product Labels
Reports\ICLabel
ICLabelSample.pfd
PO Purchase Order
Reports\POOrder
POOrder.pfd
POOrder.html
PO Quotation Request
Reports\POOrder
POOrder.pfd
POOrder.html
Grid Toolbar
Expand Toolbar
(Alt+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Enter Edit mode.
Print Report
(Ctrl+P)
Print the report or save it as a PDF file.
Customise
(Alt+F5)
Opens
Customise Fields
, you can customise the fields visible in the grid.
Refresh
(F5)
Reloads changes other Users may have made.
Edit Document
(F12)
Open a selected document in the relevant designer.
Edit PDF Document
(Shift+F12)
Open a selected pdf document in the relevant designer.
Edit Email Template
(Alt+T)
Opens the selected email template in the
HTML Email Editor
.

---

## EDI Price Book Import

Source: https://accredo.co.nz/webhelp/PBImporting.htm

EDI Price Book Import
Navigator > Tasks > Price Book Import
This option is used to import data from suppliers price book files into the Accredo product masterfile.
Note: A maximum of 255 characters per field applies in a PB Import file. Values longer than that will be truncated. For longer values use DI Importing where this constraint does not apply.
Price Book Definition
The file that defines how the Price Book file is imported. It defines the layout, file name and
MaxBasic
code to manipulate the raw data from the file being imported.
Click
Open In Designer
to open the selected file in the
Price Book Designer
.
Price Book File
The file (from the supplier) that contains the raw data to be imported. A default value for this file name can be specified in the definition.
Excel Worksheet
If the import file is an Excel Workbook, you can specify a Sheet Name or Sheet Number.
If not specified, the Worksheet specified from the EDI Import definition file will be accessed, if this is not found, the first Worksheet will appear.
The next three fields determine the action to take for new/existing products.
Add New Stock Items
Selected
, to add new product records that are found in the import file but which do not currently exist in Accredo.
Clear
, only update the information for existing records.
Update Existing Stock Items
Selected
, updates details for existing product records.
Clear,
only add new products.
Creditor
The default Creditor code to be used for new Product records. The price book file usually does not contain the Creditor code, so this is a quick way of ensuring all new records added have the same Creditor code. A better way to ensure that the correct Creditor code is used is to set the required Creditor code in the price book definition - in that way it does not need to be entered every time you import a suppliers price book file and you can also have it update the Creditor code on existing records.
Set Creditor as Default
Selected
, the Creditor selected above will be set as the default creditor for Products imported.
New Product
Non-Diminishing
Selected
, new products will be non-diminishing. Specify the default value in
IC Settings - General tab
.
Currency
The currency of the selected Creditor, or base currency.
Price Book Date
The date prices relate to. Used to select an exchange rate from the Exchange Rates table for foreign creditors.
Exchange Rate
Specify an exchange rate if required.

---

## Form Designer Memory Table Designer

Source: https://accredo.co.nz/webhelp/FDMemoryTableDesigner.htm

Form Designer Memory Table Designer
Navigator > Setup > Form Designer > Layout tab >
Memory Table Component
>
Double-click
- OR -
Navigator > Setup > Form Designer > Layout tab >
Memory Table Component
>
Right-click
> Table Editor
Set the fields and keys to create a memory table.
No.
The ID number of the field and the field's order on the table.
Name
The name of the field on the table. May be entered with spaces, these will be stripped for the field name and retained for the default display label.
Display Label
Text that will appear in the Header for the Grid. An override for the label to be displayed for the field, leave blank to use the field name as entered.
Type
The type of data stored in the field affects the disk storage each field occupies. See
Table Field Types
for field types available.
Domain
Select a pre-defined size and type from existing data. If a Domain is selected, the Type, Size and Upper fields use the existing data (read-only). The field and the data have the usual Accredo rules, for example, GL Account codes must be formatted ####.###.
See
Domain Documentation
for a list of available domains.
Currency Code Field
Shows the currency code field to be used, if available.
Use the
FX Amount
Domain to set a currency code for an amount. Make sure there is another field in the table with the Domain
CO Currency Code
, and use that field.
Size
You can set the maximum number of characters allowed in String and Variant Type fields. The maximum field size is based on the number of characters. 1 character = 1 byte.
Width
You can set the amount of characters to be displayed for the field.
Req
Selected
, a field value is required before
Save.
Clear
, a record can be saved if the field is empty.
LPad
For string fields, pads strings with space characters to the maximum size specified by adding spaces to the left of the string.
Uppr
Selected
, entered text will be upper case. This is often used for codes.
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
(Ctrl+Up) (Ctrl+Down)
Select an item and move it higher or lower on the list.
Delete
(F3)
Delete the selected item.
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
Table Schema
(Alt+T)
Load a custom table or an Accredo table schema.
Import
(Alt+I)
Load a Memory Table Builder definition
pfm
file created in
Memory Table Builder
.
Export
(Alt+E)
Save the Memory Table as a Memory Table Builder definition
pfm
file.
Upgrade Table
(
Alt+U
)
Converts all non Unicode domains to the equivalent Unicode domain if one exits, e.g. Name -> Name U, Address Line 1 -> Address Line 1 U.
Save
(F9)
Save the table.
Cancel
(Esc)
Close the form without saving any changes.
In This Section
Form Designer Memory Table Designer - Keys tab
Table Field Types

---

## Form Designer Memory Table Designer - Keys tab

Source: https://accredo.co.nz/webhelp/FDMemoryTableDesigner_Keys.htm

Form Designer Memory Table Designer - Keys tab
Navigator > Setup > Form Designer > Layout tab >
Memory Table Component
>
Double-click
> Keys tab- OR -
Navigator > Setup > Form Designer > Layout tab >
Memory Table Component
>
Right-click
> Table Editor > Keys tab
You can define the index keys for the memory table. An index key is a data structure that improves the speed of operations. Index keys can be created using one or more fields of a table, providing the basis for both rapid look-ups and efficient access to records.
See also
Form Designer Memory Table Designer
.
Note: Custom keys added to Accredo tables cannot be
Unique
(see below) as this could violate Accredo data rules.
Fields
No.
The ID number of the index.
Name
The name of the index on the table.
Unique
Selected,
the index must be unique.
Note: Custom keys added to tables cannot be set to
Unique
as this could violate Accredo data rules.
Parts
Select the fields that are to be indexed by this key.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new field at the selected line.
Move
(Shift+Up) (Shift+Down)
Select a field and reorder the list.
Delete
(F3)
Delete the selected field.

---

## Keyboard Shortcuts - Navigation

Source: https://accredo.co.nz/webhelp/KeyboardShortcuts_Navigation.htm

Keyboard Shortcuts - Navigation
Forms and Grids
Tab
Enter
Moves to the next control.
Note: In a Narrative Editor, such as a Memo body or Description tab (as in
FA Asset - Description tab
or
JC Job - Description tab
),
Tab
or
Enter
will add a Tab or Enter character. Use
Ctrl+Tab
to move to the next control.
Down
Moves to next line of a grid.
Shift+Tab
Shift+Enter
Moves to previous control (except grids).
Up
Moves to previous line of a grid.
Home
Move to the start of the control.
End
Move to the end of the control.
Ctrl+Left
Ctrl+Left & Ctrl+Right move to Next/Previous
in
Users, Groups and Roles - Preferences tab
determines behavior.
Move to the next control left (form), or the next field left (grid), or move one word to the left.
Ctrl+Right
Move to the next control right (form), or next field right (grid), or move one word to the right.
Ctrl+Home
Moves to the first editable control (form) or to the first line (grid).
Ctrl+End
Moves to the last editable control (form) or to the last line (grid).
Ctrl+Enter
Moves to the first editable field of the next line on grids.
Esc
If data was edited, reverts to the state when the control (form) or field (grid) was entered. If data in the control or field was not edited, closes the window.
Page Down
Moves down in a grid by one window.
Page Up
Moves up in a grid by one window.
Between Tabs with a Form
Ctrl+Page Down
Page Down
If not used by a control on a grid or memo, moves to next tab.
Ctrl+Page Up
Page Up
If not used by a control on a grid or memo, moves to previous tab.
Between Windows
Ctrl+F6
Moves to next window in Windows menu sequence.
Shift+Ctrl+F6
Moves to previous window in Windows menu sequence.
Ctrl+Tab
Moves to next window in Tab Window sequence.
Shift+Ctrl+Tab
Moves to previous window in Tab Window sequence.
System Menu
Alt+Space
Display the system menu for the Main Window.
Alt+-
Display the system menu for the MDI window or Tab.
Alt+W
From the system menu, toggle between
Move to New Window
, and
Move to Main Window
.
Move to New Window makes the form a floating window.
Move to Main Window makes the form a normal MDI child window.
See Also
Accredo Keyboard Shortcuts

---

## Licensee Details & Accredo Security Code

Source: https://accredo.co.nz/webhelp/Security.htm

Licensee Details & Accredo Security Code
Accredo > File > Licensee details
Licensee Details will open automatically when Accredo is started until Accredo has been secured. The Accredo Security Code must be entered before you can perform End Of Period processing, and a watermark will appear on reports until it is entered.
To obtain an Accredo Security Code, complete the Licensee Details.
Click
Edit
(F11)
and complete the fields on the
Address
,
Details
and
QSP (Accredo Qualified Support Person)
tabs.
Click
Save
(F9)
, then
Print
(Ctrl+P)
the Accredo Security Application, sign it and send to
Accredo Business Software Ltd
.
Once saved QSP Contact information can be accessed under Accredo > Help > Contact QSP Company Name.
Use the Accredo Security Code to Secure Accredo
Accredo will send you a security code. On receiving the Accredo security code:
Go to Accredo > File > Licensee Details
Click
Secure
(Alt+S)
and enter the Accredo Security Code. When the "System secured" message appears, Accredo is secure. The name in the Licensee Name field must match the name on the Accredo Security Application containing the Accredo Security Code. If the name is changed after printing the Accredo Security Application, advise Accredo Business Software Ltd.
Changing Licensee name
Changing Licensee name after the system is secured will make the system unsecured. Submit a new Accredo Security Application with documentation for the reason for the name change, and Accredo will issue a new security code.
Changing Install Key
If you are issued a new installation key from Accredo, click
Install
(
Alt+I
) and enter the new key. This can be used to add or remove modules or users.
Check Accredo for Licence changes
Provided there is internet access Accredo checks daily for changes to your licence e.g. adding or removing modules or users, for subscription licence expiry date, and for build status.
The license and build checks go to:
ops.accredo.co.nz
, ensure this address is white-listed in your firewall.
Click
Check Accredo
(
Alt+A
) to manually initiate a licence check.
System tab
Displays details for the system:
Serial No.
Expiry date for systems with subscription modules or users.
Maximum concurrent users.
Modules installed and whether the modules is a subscription module.
Perpetual / Subscription Licence tabs
The Accredo Software Licence(s) which apply to the system are displayed, when viewing the Licence tabs select
Print
to print the Licence.
Privacy tab
The Accredo Privacy Policy is displayed, when viewing the Privacy tab select
Print
to print the Privacy Policy.
See Also
File Menu

---

## Link a Server to Accredo ODBC Driver

Source: https://accredo.co.nz/webhelp/LinkServerToAccredoODBCDriver.htm

Link a Server to Accredo ODBC Driver
To create a linked server to Accredo ODBC Driver, use Microsoft SQL Server Management Studio.
Go to Server Objects > Linked Servers > Right Click > New Linked Server...
Enter the following:
Linked Server
The name you will refer to in queries, for example, ACCREDO
Server type
Other data source
Provider
Microsoft OLE DB Provider for ODBC Drivers
Product Name
Anything
Datasource
Name of a datasource set up using the ODBC Administrator
Provider String
Blank
Location
Blank
Catalog
Blank
Example usage:
Select * From [ACCREDO].[Accredo]..[ARCUST]
- OR -
Select * From ACCREDO.Accredo..ARCUST
See Also
Setup AccredoDB OLEDB/ODBC driver

---

## Merge Codes

Source: https://accredo.co.nz/webhelp/MergeCodes.htm

Merge Codes
Navigator > Setup > Company > Utilities > Merge Codes
You can merge two masterfile records into one. See the different code types below to see how data is merged. We recommend checking this before merging, to make sure no required data is lost in the merge.
The masterfile record with the
To Code
will be retained in the masterfile data. The
From Code
record will be deleted. Any affected
word lookups
will be rebuilt.
When you Merge codes:
each change is recorded in the
Alias and Merge Log
.
each change is appended to an Alias.csv file in the data directory.
the
Merge
event and
Backup Confirmation
are recorded in the
File Recovery
log.
if the merged records are
Change Tracked
the
Merge
is recorded as a Delete of the From Code and an Update of the To Code.
for change tracking of other tables containing the merged code the
Merge
is recorded as an Update.
Tracking and logging is useful when you are integrating a third party application that will need to consider merged records.
Note that some Code types cannot merge, such as Fixed Asset codes and Depreciation transactions.
Code Type
Data Effect
All Masterfiles
Links and Memos are merged from the
From Code
to the
To Code.
Documents are merged from the
From Code
to the
To Code.
Transactions are merged from the
From Code
to the
To Code.
Balances are summed between the
From Code
and the
To Code.
Budgets are summed between the
From Code
and the
To Code.
Active
From Codes
cannot be merged to an inactive
To Code.
Records with different Currency Codes cannot merge.
The
0000 Unspecified Code
cannot be used as a
From Code
, as this code must exist.
AR Customer
AP Creditor
The records being merged must have the same
Tax Regime.
Customer or Creditor Type
must allow the merge. Normal, One-Time and Cash Type customers cannot merge to a Prospect Type. Cash Type customers cannot merge to Normal or One-Time Type.
Contacts are copied from the
From Code
to the
To Code.
Delivery Addresses on the
From Code
with a Code that does not exist on the
To Code
will be copied across. Delivery Address codes on the
From Code
that exist on the
To Code
will be deleted.
Banking details on the
From Code
will be deleted.
IC Product
Suppliers are merged from the
From Code
to the
To Code
if there is no conflict.
Bar codes are merged from the
From Code
to the
To Code.
UOM Codes are merged from the
From Code
to the
To Code
if there is no conflict.
Bin Code, Minimum and Maximum quantities are merged from the
From Code
to the
To Code
if they are not already entered on the
To Code.
Information tab details for the
From Code
will be deleted.
Image path for the
From Code
will be deleted.
Components for the
From Code
will be deleted.
Pending transactions are merged from the
From Code
to the
To Code.
Activity tab figures are summed between the
From Code
and the
To Code.
Prices for the
From Code
will be merged to the
To Code
if there is no conflict.
Diminishing
to
Non-diminishing
IC Product Code
(or vice versa) cannot merge.
Product Tracking
for the products must match for merge to proceed.
Tax records for the
To Code
are retained. If the
From Code
has tax records for regimes not in the
To Code
, these will be merged.
IC Location
Cannot merge IC Location Codes until all stock transfers have been processed.
Cannot merge IC Location Codes when the
From Code
location has unposted Stocktakes.
Cannot merge IC Location Codes when the
From Code
location and
To Code
Location do not have matching Bin Tracked settings.
(Accredo Saturn Only)
CB Bank Account
CB Bank Codes with a
From code
with no closed statements can merge.
Details tab data from the
From Code
are deleted.
Statements from the
From Code
are merged to the
To Code.
Rules are merged from the
From Code
to the
To Code.
Automatic Payments are merged from the
From Code
to the
To Code.
Banking Summaries are merged from the
From Code
to the
To Code.
GL Account
GL Account Codes of the same Account Type can merge.
You will be required to run a GL File Recovery after merging GL Account Codes.
Account and Reporting tab details for the
From Code
will be deleted.
GL Budget Codes
You will be required to run a GL File Recovery after merging GL Budget Codes.
JC Job
JC Job Codes of the same Job Type, Job Status and Job Currency Code can merge.
The Description tab and Information tab details for the
From Code
will be deleted.
Address details for the
From Code
are deleted.
Estimate lines from the
From Code
are deleted.
Pending transactions are merged from the
From Code
to the
To Code.
CO Media Codes
CO Media Codes
Cash
,
Cheque
and
Other
cannot be used as a From Code as these must exist.
CO User Codes
Cannot merge the current logged-in user.
Details from the User, Permissions. Roles Settings, Preference, Email and Image tabs for the
From Code
will be deleted.
CO Branch and Department Codes
You will be required to run a GL File Recovery after merging Branch or Department Codes.
(Accredo Saturn Only)
Category Codes
All references to the
From Code
will be changed to the
To Code.
Analysis Codes
The
0000 Unspecified Code
cannot be used as a
From Code
, as this code must exist.
Tax records for the
To Code
are retained. If the
From Code
has tax records for regimes not in the
To Code
, these will be merged.
Warning: You will be prompted to back up your data before running this utility, as this utility restructures Accredo data files. If you experience power or other failure during posting, restore the backup and perform the Merge again.  Do not run a file recovery before performing the steps above as file recovery will delete records relating to missing codes.
A log is appended to the
Error Log
. Each merge is appended to an
Alias.csv
file in the data directory as a change log. Use this when integrating with a third party application to identify the merged records. Validate the GL after merge on GL Account codes to identify any issues in the Chart Of Accounts.
Select Code
Select the type of code to be aliased. To include inactive records click
Show Inactive Records
(Ctrl+I)
. To open a list of Merge Codes, click
Open
(Shift+F12)
.
From Code
Select an existing code from the list of codes. To include inactive records click
Show Inactive Records
(Ctrl+I)
. To open a list of Merge Codes, click
Open
(Shift+F12)
.
To Code
Select an existing code, that the
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
Import a list of codes to be merged. This can save time from entering codes individually. The import file must be a text file with one line per code change. The fields on the line can be separated by commas (CSV format) or Tab characters (Tab delimited).
Field
Format
Size
From code
Alpha
Depends on code selected
To code
Alpha
Depends on code selected
Additional fields will be ignored by the import. Only lines in which the From code and To code differ, and a match for the From code is found are imported. When you import if there are errors you are prompted with the Merge Importing report selections, this report shows the error messages for lines which are not imported. If there are errors an exceptions file containing the rejected records is created with file name extension
.EXC.
Click
Post
(
Alt+T
) to merge the imported selections.
Buttons
Print
(Ctrl+P)
Print the Summary of Merge Codes report. See
Report Selections Form
.
Post
(Alt+T)
Post the changes.
See Also
Utilities

---

## Number Formats

Source: https://accredo.co.nz/webhelp/MBNumberFormats.htm

Number Formats
You can format numbers by specifying a
Domain
or a
Format String
. Colour can be included in the format string, see
Color Property
.
See Also
MaxBasic Formatting

---

## password

Source: https://accredo.co.nz/webhelp/90.htm#o5578

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

## Preferences - Colour tab

Source: https://accredo.co.nz/webhelp/Preferences_Colour.htm

Preferences - Colour tab
Accredo > View > Preferences > Colour tab
Status Hint
Status hints appear lower left of the active window. To change the colour, click the Colour, select a colour, then click
OK.
To restore the default, click
Use default status hint colour
.
The Windows
Default Beep
sound is used for Status Hints. Click to toggle the button to
muted.
Error Hint
Error hints appear on the active field. To change the colour, click the Colour, select a colour, then click
OK.
To restore the default, click
Use default error hint colour
.
The Windows
Exclamation
sound is used for Error Hints. Click to toggle the button to
muted.
The selected
Error Hint
Colour is also used for the background of error rows in results grids.
Read Only
Identifies read-only fields that cannot be edited. To change the colour, click the Colour, select a colour, then click
OK.
To restore the default, click
Use default read-only colour
.
Grid Line
Identifies the active line in a grid. To change the colour, click the Colour, select a colour, then click
OK.
To restore the default, click
Use default grid line colour
.
Grid Line Read Only
Identifies the active line in a read-only grid. To change the colour, click the Colour, select a colour, then click
OK.
To restore the default, click
Use default grid line colour
.
Grid Total Row
Identifies the total row in a totalled grid. To change the colour, click the Colour, select a colour, then click
OK.
To restore the default, click
Use default grid line colour
.
Credit
Select the colour to show credits and credit warnings.
Graphs Field 1
Graphs Field 2
Graph colours for Graph tabs on master file maintenance. To change the colour, click the
Graphs Field 1 or 2
colour, select a colour, then click
OK
.
Report Row Shade
Select a percent to shade alternate report rows, from
0
-
100
%, with
0
being no shading (light) and
100
being full shading (dark). Default is
20
.
Grid Row Shade
Select a percent to shade alternate grid rows and lookup rows, from
0
-
100
%, with
0
being no shading (light) and
100
being full shading (dark). Default is
20
.
Grid RO Row Shade
Select a percent to shade alternate Read Only grid rows, from
0
-
100
%, with
0
being no shading (light) and
100
being full shading (dark). Default is
10
.
See Also
Preferences - General tab

---

## Preferences - Display tab

Source: https://accredo.co.nz/webhelp/Preferences_Display.htm

Preferences - Display tab
Accredo > View > Preferences > Display tab
Maximised Style
Tabs,
(default) when maximised windows show as tabs in the main window. Switch between windows by clicking the tab or use
Ctrl+Tab
to cycle through open tabs. Windows are closed from the tab by clicking the close button or middle-clicking anywhere in the tab.
Use the
Window View and
Tabbed View buttons on the
Global Toolbar
to switch between tabbed and window view. You can also double-click in tab title to switch to window view or maximise a window to switch to tab view.
Classic
, when maximised windows are maximised within the main window and title bars are merged.
Navigator
Determines the default position for the Navigator when the company is opened. The Navigator can be dragged between normal, docked or floating.
Normal Window,
opens in the main window. If the Navigator is obscured, press
Ctrl+F6
to scroll through open windows or click
Navigator
(
Alt+F10)
or go to Accredo > View > Navigator.
Docked Left
, the Navigator is docked to the left of the screen. To dock the Navigator, drag it as far to the left as possible, a red line will appear. To undock the Navigator, drag it away from the screen edge. To minimise or maximise the docked Navigator, click
Navigator
(
Alt+F10)
or go to Accredo > View > Navigator.
Docked Right
, the Navigator is docked to the right of the screen. To dock the Navigator, drag it as far to the right as possible, a red line will appear. To undock the Navigator, drag it away from the screen edge. To minimise or maximise the docked Navigator, click
Navigator
(
Alt+F10)
or go to Accredo > View > Navigator.
Floating Window
,
floats on desktop. If obscured, click
Navigator
(
Alt+F10)
or go to Accredo > View > Navigator.
Toolbar
Selected,
show the
Accredo toolbar
. You can add shortcuts to the toolbar using the
Shortcut List
.
Clear,
hide the toolbar.
Status bar
Selected,
show the the lower
status bar
.
Clear,
hide the status bar.
Report
Normal Window
,
(default) opens in main window, if obscured, press
Ctrl+F6.
Floating Window
,
allows you to drag reports printed to screen across to another monitor.
Calculator
Floating Window
,
floats on desktop, if obscured, click
Show Calculator
(
Alt+F12)
, or Accredo > View > Calculator.
Floating Window Always On Top,
floats outside main window, always on top.
Normal Window,
(default) opens in the main window. If the Calculator is obscured, press
Ctrl+F6
to scroll through open windows, click
Show Calculator
(
Alt+F12)
, or Accredo > View > Calculator.
An extended edit Calculator is available.
Calendar
Floating Window
,
floats on desktop, if obscured, click
Show Calendar
(
Alt+F11)
, or Accredo > View > Calendar.
Floating Window Always On Top,
floats outside main window, always on top.
Normal Window,
opens in the main window. If the Calendar is obscured, press
Ctrl+F6
to scroll through open windows, click
Show Calendar
(
Alt+F11)
, or Accredo > View > Calendar.
Script Editor
This setting applies to the
Script Editor
,
Report List
and
Snippet Manager
.
Normal window,
(default) opens in main window, if obscured, press
Ctrl+F6.
Floating window
,
floats on desktop.
Reminder List
Normal Window
,
opens in main window, if obscured, press
Ctrl+F6.
Floating Window
,
(default). Opens a separate window which may be dragged.
Memos (Alarms & Reminders)
Normal Window
,
opens in main window, if obscured, press
Ctrl+F6.
Floating Window
,
(default). Opens a separate window which may be dragged.
Email Editor
Normal Window
,
opens in main window, if obscured, press
Ctrl+F6.
Floating Window
,
(default). Opens a separate window which may be dragged.
Editor Font
Choose from available Fixed Width fonts for memos and Max Basic editors.
Use Accredo Scaling
Selected
, Accredo handles scaling based on Display settings for your Primary monitor and Application size (below) can be set. Recommended when all monitors are using similar values for Windows scaling.
Clear
, Windows scaling and Display settings for each monitor apply.
Application size
Set the size of the application. Defaults to
100%
, but can be increased. Scaling is applied on top of any Windows scaling. Changes will be made when the application is restarted.
Note: Only available if
Use Accredo Scaling
(above) is Selected.
Drop Down Rows
The number of rows to be displayed in a drop-down. Defaults to
16
.
See Also
Preferences - General tab

---

## Preferences - General tab

Source: https://accredo.co.nz/webhelp/Preferences_General.htm

Preferences - General tab
Accredo > View > Preferences > General tab
Set preferences for Accredo workstations, see also
Users, Groups and Roles
.
Active Phone
Integrate information in Accredo with incoming and outgoing calls using
TAPI
.
Phone buttons on Phone Number fields are enabled if an active phone is selected and TAPI is initialized and we can connect to the TAPI driver, or if the
Allow Make Call without TAPI
System Preference
is selected.
Add Links Folder to Send To List
Selected,
add Accredo Links as a
Send To
option on the right-click menu.
Clear,
remove Accredo Links from the right-click menu.
Drop down key-press delay
The time delay between typing in a Lookup field, and the Lookup finding the nearest match. Increasing the delay can reduce network traffic. Defaults to
333 ms
.
Drop down on Double click for Lookups
Selected
, (default) double-clicking in a lookup will drop down the list.
Clear
, double-clicking in a lookup will select all in the lookup control, but will not drop down the list.
Use Online Web Help
Selected
, Help will be opened online in the default browser.
Clear
, Help will be opened in the windows help file.
In This Section
Preferences - Display tab
Preferences - Colour tab
Preferences - Trouble-shooting tab
Preferences - System tab
See Also
View Menu

---

## Preferences - System tab

Source: https://accredo.co.nz/webhelp/Preferences_System.htm

Preferences - System tab
Accredo > View > Preferences > System tab
If
Use Single Sign On
is selected in
System Settings
this tab does not appear and
Preferences
are set per
System User
.
Preferences are saved in the system registry.
Allow Make Call without TAPI
Activates call buttons on Accredo forms associated with a Make Call script event when TAPI is not present.
Allow only single Accredo application
Selected
, you will be unable to open Accredo more than once on a workstation or Remote Desktop Services session.
Prompt on application exit
Selected
, shows a message on close. This can be useful if you use maximised child windows.
Prompt on close company
Selected
, shows a message on Company close, to avoid accidental closing
.
Single click for Calendar dates
Selected
, a single click will select a date from the calendar.
Single click for Report fields
Selected
, a single click will select drill down from
Report Preview
.
Snippet Key
The key used to insert MaxBasic Code Snippets in the Code Editor. The default is
#
.
Show line numbers in editors
Line numbers will appear in editors such as the Script Editor.
Grid Highlight Credits
When
Selected
, show credit transactions and documents in the
Credit
colour below, in
IN Invoice List
,
AR Customers
and
AP Creditors
.
Graphs
Select the defaults for graph display. Default, only
Display Graph Legend
is selected.
Expand Toolbar
(
Ctrl+F9
), Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Show / Hide 3D Effect
, shows graphs in 3D or 2D.
Show / Hide Graph Key
, shows or hides the graph key on graphs.
Show / Hide Graph Legend
, shows or hides the graph legend on graphs.
Show / Hide Average Value,
shows or hides average values on graphs.
Designer Component Selection
Controls component selection in
Report Designer
and
Form Designer
.
Use Shift+Drag for Select by Region & Ctrl+Click for Multi Select for Components in Designers. (Default.)
Use Ctrl+Drag for Select by Region & Shift+Click for Multi Select for Components in Designers. (Default in prior Accredo versions.)
Minimum Hint Time
The minimum number of seconds that
Status hints
and
Error hints
remain on screen. Click a hint to dismiss it immediately.

---

## Preferences - Trouble-shooting tab

Source: https://accredo.co.nz/webhelp/Preferences_TroubleShooting.htm

Preferences - Trouble-shooting tab
Accredo > View > Preferences > Trouble-shooting tab
Do not change these options unless advised to by Accredo Support.
Use Windows to draw transparent glyphs
(Default). If purple or green shadows appear behind toolbar button glyphs, video drivers may conflict with the Windows version. Accredo support may advise to
clear
the checkbox.
Show stack traces in diagnostics
If there are system errors in MaxBasic scripts Accredo Support may advise this option.
Enhanced bitmap printing
Can be used to solve printer driver errors when printing bitmaps over 64Kb, or printing colour bitmaps to black and white (may print partial or corrupt images).
Standard
(Default) Assumes the printer driver will send bitmaps to the printer in the correct format, and feed large or coloured bitmaps in small chunks. Do not change unless advised.
Auto DDB
Automatic Device Dependent Bitmaps. Useful if the printer driver cannot convert bitmaps to the correct format, will report correctly on capabilities. If a bitmap will not send in the correct format, will allow Windows to convert it.
Force DDB
Force Device Dependent Bitmaps. If the printer driver can not send bitmaps to the printer in the correct format, does not report on capabilities. Forces Windows to convert bitmaps to the correct format.
Debug
Same as Auto DDB, but shows an error message.
Off
Sends bitmaps to the printer via the printer driver.
Zero printer device mode paper width & length
If the printer driver reports paper size
0
Accredo support may advise selecting this option.
Printer diagnostics level
Printer diagnostics level option, write printer messages to the
Error log
-
0
being none,
1
, significant messages,
2
, all messages.
TAPI diagnostics level
Level options,
0
being none,
1
, significant messages,
2
, all messages. All TAPI events trigger the
OnPhoneCall
event to detect the type of TAPI event.
Mail diagnostics level
Logging for Http and SMTP emails.
Level options,
0
being none,
1
, error messages,
2
, all messages - includes success messages confirming Accredo has sent the email. Logging is in the
Error Log
.
Use separate thread for SMTP
(Default). If problems occur with SMTP using SSL authorisation Accredo support may advise to
clear
the checkbox.
Capture Mailer stack traces
Selected
, if stack trace errors occur, they will be captured in the diag.log file.
User handles warning
If non-zero, triggers a Warning when the handle limit is reached. Warning resets when the current handles drop below the limit. Use to troubleshoot handle exhaustion issues.
GDI handles warning
If non-zero, triggers a Warning when the handle limit is reached. Warning resets when the current handles drop below the limit. Use to troubleshoot handle exhaustion issues.
Kernel handles warning
If non-zero, triggers a Warning when the handle limit is reached. Warning resets when the current handles drop below the limit. Use to troubleshoot handle exhaustion issues.
Use Adobe PDF reader embedded
Selected
, (Default)
View Saved Report
and
ViewPDF
functions open Adobe PDF reader embedded.
Unselected
, open PDFs externally from View Saved Reports or ViewPDF function when Adobe PDF reader is used. Unselect if you experience issues with Adobe PDF reader running embedded.
Unique public variable names
Selected
, (Recommended) Public variables with the same name as a MaxBasic function are disallowed.
Force Advanced graphics mode
Selected
, Force Advanced Metafile if required for trouble-shooting screen preview issues.

---

## Price Book Designer

Source: https://accredo.co.nz/webhelp/PriceBookDesigner.htm

Price Book Designer
Navigator > Setup > Data Interchange > Price Book Designer
Price Book Designer imports product and price information files. Create a definition file, then import using Navigator > Tasks >
Price Book Import
.
Definitions support file formats including CSV, fixed width ASCII and dBase files. When creating a definition or importing a file, preview the data in the file to create the correct definition. This is useful before importing to validate file format and data. Import definitions can contain
MaxBasic
code to manipulate data in the import file for:
Calculating Selling Prices from Cost Prices (or vice versa).
Applying exchange rates to prices in the file.
Filtering unwanted records.
Supplying constant values.
Note: A maximum of 255 characters per field applies in a PB Import file. Values longer than that will be truncated. For longer values use DI Importing where this constraint does not apply.
In This Section
Price Book Designer - Definition tab
Price Book Designer - Before Import tab
Price Book Designer - For Each Record tab
Price Book Designer - Comment tab
PB Import Preview

---

## Price Book Designer - Before Import tab

Source: https://accredo.co.nz/webhelp/PBBeforeImport.htm

Price Book Designer - Before Import tab
Navigator > Setup > Data Interchange > Price Book Designer > Before Import tab
Use MaxBasic code to manipulate import data. Set values to be used in the remainder of the import.
Code Editor
Objects:
ApplyMarkup
Global variable for Pricebook designer. Per record (i.e ForEach), this will be reset to
false
.
Markup will be applied per record when a price change is detected if either
Automatically Apply Markup
is set, or ApplyMarkup is set to
true
in
For Each Record
.
Import
Global variable for Pricebook designer. Per record (i.e ForEach), this will be reset to
true
.
May be set to
false
in
For Each Record
to skip import for the record.
Company
Contains details of the Company name and address.
Product
Fields from the Product record.
System
Fields from the System record.
SystemUser
Fields from the System User record.
User
Fields from the User record.
Note: See
Import Functions
for functions specific to the Import Designer.
See also
Price Book Designer - Definition tab
.
See Also
Price Book Designer

---

## Price Book Designer - Comment tab

Source: https://accredo.co.nz/webhelp/PBDefinition_Comment.htm

Price Book Designer - Comment tab
Navigator > Setup > Price Book Import Definition > Comment tab
You can use this tab to add comments regarding the import routine.
See also
Price Book Designer - Definition tab
.
See Also
Price Book Designer

---

## Price Book Designer - Definition tab

Source: https://accredo.co.nz/webhelp/PBDefinition.htm

Price Book Designer - Definition tab
Navigator > Setup > Data Interchange > Price Book Designer > Definition tab
Preview the import definition from Navigator > Tasks >
Price Book Import
Input Format
Select the import file type.
CSV/Tab Delimited CRLF Terminated
Comma separated value file or Tab delimited file, with lines terminated by Carriage Return Line Feed (CRLF) characters.
Fields are optionally enclosed in quotation marks (" "), and are separated by commas or the Tab CHR(9) character. Record terminators do not consider quotes.
CSV/Tab Delimited LF Terminated
Comma separated value file or Tab delimited file, with lines terminated by a Line Feed (LF) character.
Fields are optionally enclosed in quotation marks (" "), and are separated by commas or the Tab CHR(9) character. Record terminators do not consider quotes.
CSV/Tab Delimited Any Terminator
Comma separated value file or Tab delimited file, with lines terminated by either Line Feed (LF), Carriage Return (CR) or Carriage Return Line Feed (CRLF) characters.
Fields are optionally enclosed in quotation marks (" "), and are separated by commas or the Tab CHR(9) character. Record terminators do not consider quotes.
ASCII Fixed Widths
Fixed width ASCII file. Fields are located at fixed positions across each line of the import file.
DBF
dBase file format.
Excel Worksheet
The Excel Worksheet selection becomes available, and defaults to the first worksheet. Select the sheet from your workbook.
Default Input File
File name for the import definition. On
Price Book Import
the file name is supplied.
If this is an XLS or XLSX file, the
Input Format
must be
Excel Worksheet
.
Load Structure
For structured file formats (.DBF), loads the file structure in the grid.
Excel Worksheet
For Excel Worksheets, specifies the Worksheet.
Grid Fields
Name
Optional name for the field in the import file. Provided the name is a valid
MaxBasic variable
name it can be referenced in MaxBasic code, and is the field title in
PB Import Preview
.
Offset
Determine the position of the field in the import file. For CSV and DBF files it is the field number in the file,
1
as the first field. For ASCII files it is the starting character position, starting from
1.
To import data not represented in the import file (for example, default field values) specify an offset
0
and supply the data from MaxBasic code (if offset
0
the field is not located in the import file).
Width
For ASCII format, the field width in characters.
Destination
The field in the Accredo Product file the data will be imported into. Can be left blank as not all fields in the import file need to be imported.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new field at the selected line.
Move
(Shift+Up) (Shift+Down)
Select a field and reorder the list.
Delete
(F3)
Delete the selected field.
Buttons
View Data...
(Alt+D)
Opens
PB Import Preview
with data in the import file. Use this to ensure you have specified the data fields correctly.
Check Code
(Alt+C)
Check that the code entered on the Code tab compiles correctly without the need to run a price book import.
Load...
(Alt+L)
Load previously saved definitions for use in the
EDI Price Book Import
.
Save...
(Ctrl+S)
Save the definition for use in the
EDI Price Book Import
.

---

## Price Book Designer - For Each Record tab

Source: https://accredo.co.nz/webhelp/PBForEachRecord.htm

Price Book Designer - For Each Record tab
Navigator > Setup > Data Interchange > Price Book Designer > For Each Record tab
Set MaxBasic code to execute after each data record is loaded from the import file but before it is applied to Accredo.
This is used for selection purposes if a record is to be imported, and for adjusting the data before import (for example, to apply an exchange rate to calculate actual prices).
To set SupplierStandardCostDate for records where nothing has changed but you want the date updated for example:
Define StdCostDate mapping to SupplierStandardCostDate on the Definition tab and add the following code to For Each Record.
StdCostDate = PriceBookDate
See
Code Editor
for options available.
See
Before Import
for Objects and Global Variables available.
See also
Price Book Designer - Definition tab
.

---

## Report Preferences

Source: https://accredo.co.nz/webhelp/ReportPreferences.htm

Report Preferences
Navigator > Setup > Company > Reporting > Report Preferences
Set default preferences for producing reports.
Default File Format
Select from:
Adobe PDF
- view using
View Saved Report
from the Reports tab or Adobe Reader. When generating PDF files, if fonts are not found, Helvetica will be used. We recommend using standard system fonts in PDF documents.
CSV File
- fields on a line are separated by commas.
Tab Delimited File
- similar to CSV file except the fields are separated by the tab character.
Quoted CSV File
- CSV File with string fields enclosed by double quotation marks (" ").
Excel XLS File
- Microsoft Excel file.
Excel File Format
Determine the file format to use when Excel format reports are run to file.
Excel 97-2003 (.xls)
Excel (.xlsx)
PDF Image Max Dpi
Set the default maximum Dpi (Dots per inch) for images in report pdf files. Defaults to
300 dpi
. Picture boxes in report pfd files will recalculate the dpi for images to match this setting.
Double Spacing
Selected,
by default, reports will be formatted with double spacing.
Shade Alternate Rows
Selected,
by default, alternate rows on reports will be shaded, based on the
Report Row Shade
set in
Preferences - Display tab
.
Suppress Grand Totals
Selected,
by default, no grand totals for the top level of grouping are printed.
Enable Clickable Fields
Fields in reports layouts printed to screen can respond to click to open source record.
Selected,
(default) preference will be selected by default in new reports layouts.
Clear,
preference will be clear by default in new reports layouts.
Include Created Modified in Footer
Created and Modified information is tracked for report layouts.
Selected,
(default) shows the User code and date the layout was created, and last modified in Customise Layout.
Auto Open File
Set default when Report
Destination
is
Disk File.
Selected
, the file will automatically open with the system default viewer after it is created.
Include Date on File Names
Selected,
report files attached to email or printed to disk file have the date that the file was generated encoded into the file name in the format yyyymmdd.
Clear,
no date is encoded in the file name.
New Excel Workbook
Selected,
when running reports to Excel, by default, a new workbook will be created.
Embed Fonts in PDF reports
Selected,
(required, cannot be cleared) fonts which allow embedding are embedded in pdf files so that pdf's will be viewed as generated regardless of the viewing device.
Note: All TrueType and OpenType fonts have “embedding permissions” encoded within them, these are typically set by the font’s supplier, and are defined as part of the OpenType font file specification, if the font is set to No embedding—The font supplier does not allow embedding. These fonts are quite rare. We do not recommend using fonts that do not allow embedding.
Column Headers
Selected
, when the report
Destination
is
Disk File
and
Format
is a delimited file, column headers are included in the output file by default.
Append to File
Selected
, when the report
Destination
is
Disk File
and
Format
is
Adobe PDF
or
Excel XLSX File
, if the File is an existing file, the report will be appended to the end of the file.
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
Reporting Fonts
Select the font for each section. Click the relevant font button to open Windows fonts.
Align Title  AlignSelections
Select the alignment for the Report Title and Selections.
Restore Default Fonts
Restore font settings to their defaults.
Page Layout
Automatic
-
print in portrait orientation if the report will fit, otherwise print in landscape. If a report doesn't fit landscape, fonts will be scaled down.
Portrait or Landscape
-
print in the selected orientation. If a report is too wide to fit based on selected fonts and orientation, fonts will be scaled down.
Report Margins
Unless margins are set, reports will print close to the edge of the paper. This can make them hard to file in a ring binder. If data near the margins is missing, the wrong printer driver may be installed. You can temporarily increase the margins to fix this.
Buttons
Edit
(F11)
Enter edit mode.
Save
(F9)
Save changes. Defaults will be applied when new non-customisable report layouts are added.
Cancel
(Esc)
Discard changes and close the form.

---

## Script to Default Graph Fields

Source: https://accredo.co.nz/webhelp/ScriptToDefaultGraphFields.htm

Script to Default Graph Fields
This example shows you how to setup a script to default the Field Selections of a graph.
For this example we will set the default fields for the IC Product graph tab. A similar script could be set up for any graph tab.
Open the Script Editor from Accredo > Script > Script Editor.
Enter the following code. This will set the first graph field to
SalesQuantity
and the second graph field to
SalesQuantityLastYear
. You can change these to the fields you wish to default to.
Dim frmICProd1 as Object
frmICProd1 = GetTriggerObject
if IsNull(frmICProd1) then frmICProd1 = GetActiveObject
if IsNull(frmICProd1) or frmICProd1.ClassName <> "ICProductForm" then Error "Wrong form class for script"
frmICProd1.GraphField = "SalesQuantity"
frmICProd1.GraphField2 = "SalesQuantityLastYear"
frmICProd1.ActivePage = 0
frmICProd1.ActiveProperty = ""
Save the script as
ICProduct_SetGraphFields_OnOpen.pfs
.
Set the script to run when the IC Product form is opened. Go to Accredo > Script > Script Events. Click
Edit
(
F11
).
Set the following:
Module:
IC
Class:
ICProductForm
Type:
OnOpen
Script Name:
ICProduct_SetGraphFields_OnOpen.pfs
Click
Save
(
F9
).
Now when you open the IC Product form, the graph tab will show the fields you have set.

---

## Status Bar

Source: https://accredo.co.nz/webhelp/StatusBar.htm

Status Bar
The Status bar is displayed at the lower right of the Accredo Window, below the Period Bar.
Provided there is internet access Accredo checks daily for new builds and subscription licence changes and displays a status icon.
The license and build checks go to: ops.accredo.co.nz, ensure this address is white-listed in your firewall.
To manually trigger a Build Status check select Help > About.
To manually trigger a licence check select File > Licensee Details and click the
Check Accredo
button.
Build Status
(left of the Build)
Up-to-date.
Update available (date).
Error (error message). e.g. Failed to connect. For Build Status check.
Build
Shows the build number of your version of Accredo.
Subscription Status
(right of the Build)
For Subscriptions: Current (expiry date)
For Perpetual: Current.
Expiring (date).
Subscription Expired (date)
Error (error message). e.g. Failed to connect. For Subscription Status check.
Date
The
System Date
can be edited. To change the System Date, click in the field or go to Accredo > View > System Date.
Period
The
System Period
can be edited. The System Date must always be within the date range for the System Period. To change the period, click in the field or go to Accredo > View > System Date.
User
The User logged on to this session of Accredo. When logged into a company, to change the User, click in the field or go to Accredo > View >
Company Login
. When not logged into a company, click in the field to open
System Login
.
Data
The data file path for the open Company. Click this field or go to Accredo > View >
Logged-in Users
to show a list of all Users logged on to Accredo.
Appears if the Company is locked, see
File menu
.
See Also
Accredo Main Window

---

## SYS Users - Permissions tab

Source: https://accredo.co.nz/webhelp/SystemUsers_Permissions.htm

SYS Users - Permissions tab
Accredo > File > System > Users > Permissions tab
Set permissions for the System User or Group.
To set folder and option permissions, click a folder, click an option, select a permission, see
System User Permissions
. A permission can influence others. To set permissions for a group of functions, select the folder containing the group (for example, select the Accredo folder to set permissions for all functions), then select a Permission level from the toolbar. You can also right-click an option to set the Permissions.
The folders show the icon for the highest level of permission within the folder. You can fully expand and collapse the permission folders.
You can select a Group for a User. When a Group is selected, the User assumes the permissions of the Group. The Permissions will be displayed as read-only, and the User's permissions cannot be individually edited. To edit permissions for the Group, select the Group, then enter edit mode. To edit Permissions for an individual User, ensure the User is not part of a Group.
See
System User Permissions
to list all available permissions. See also
SYS Users - User tab
.
Toolbar
Expand Toolbar
(
Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
All None
(Alt+N)
Set permission for the selected folder to
None
, so no access is available.
All Read
(Alt+R)
Set permission for the selected folder to
Read
, so the folder is available for reading.
All Write
(Alt+W)
Set permission for the selected folder to
Write
, to allow editing.
All Control
(Alt+C)
Set permission for the selected folder to
Control
, to allow editing, inserting and deleting.
Expand Folder
(Shift+Num*)
Expand all folders to show all options available under the selected folder.
Collapse Folder
(Shift+Num/)
Collapse the folder to show only the selected folder, without showing options available under.
In This Section
System User Permissions
See Also
SYS Users - User tab

---

## SYS Users - Preferences tab

Source: https://accredo.co.nz/webhelp/SystemUsers_Preferences.htm

SYS Users - Preferences tab
Accredo > File > System > Users > Preferences tab
Set preferences for the System User.
User Preference Location
Select the location to save the preferences:
System -
(default) preferences are saved to the system.
Registry -
preferences are saved in the system registry.
Allow Make Call without TAPI
Activates call buttons on Accredo forms associated with a Make Call script event when TAPI is not present.
Allow only single Accredo application
Selected
, you will be unable to open Accredo more than once on a workstation or Remote Desktop Services session.
Prompt on application exit
Selected
, shows a message on close. This can be useful if you use maximised child windows.
Prompt on close company
Selected
, shows a message on Company close, to avoid accidental closing
.
Single click for Calendar dates
Selected
, a single click will select a date from the calendar.
Single click for Report fields
Selected
, a single click will select drill down from
Report Preview
.
Snippet Key
The key used to insert MaxBasic Code Snippets in the Code Editor. The default is
#
.
Show line numbers in editors
Line numbers will appear in editors such as the Script Editor.
Grid Highlight Credits
When
Selected
, show credit transactions and documents in the
Credit
colour below, in
IN Invoice List
,
AR Customers
and
AP Creditors
.
Graphs
Select the defaults for graph display. Default, only
Display Graph Legend
is selected.
Expand Toolbar
(
Ctrl+F9
), Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Show / Hide 3D Effect
, shows graphs in 3D or 2D.
Show / Hide Graph Key
, shows or hides the graph key on graphs.
Show / Hide Graph Legend
, shows or hides the graph legend on graphs.
Show / Hide Average Value,
shows or hides average values on graphs.
Designer Component Selection
Controls component selection in
Report Designer
and
Form Designer
.
Use Shift+Drag for Select by Region & Ctrl+Click for Multi Select for Components in Designers. (Default.)
Use Ctrl+Drag for Select by Region & Shift+Click for Multi Select for Components in Designers. (Default in prior Accredo versions.)
Minimum Hint Time
The minimum number of seconds that
Status hints
and
Error hints
remain on screen. Click a hint to dismiss it immediately.
Note: This tab is not available for Groups, as Groups do not have Preferences.
See Also
SYS Users - User tab

---

## System Login

Source: https://accredo.co.nz/webhelp/SystemUserLogin.htm

System Login
Accredo > File > System Login - OR -
Click the
User
field of the status bar in the lower right of the main Accredo window when not logged into a company - OR -
Opens on startup if System Login is required. When you select System Login, the current System User will be logged out. If you are logged into
Web Services
, you will be logged out of Web Services when the system user is logged out.
System Users are set up in Accredo > File > System > Users.
User Code
Password
Enter the User Code or Email Address and Password.
Show Password
Hide Password
Toggle Password visibility to check your input.
Change Password
(Alt+C)
To change a Password, enter the existing password in the
Old Password
field (if one exists), enter the new password in the
New Password
and
Confirm Password
fields. This is available dependent on
Permissions
.
If the System User is synced to any Company Users, the password will also be changed for the Company Users.
This is not available when logged into a Company.
If One-time password (OTP) is enabled in
System Settings - Passwords
and OTP is required for the User:
They will be prompted to enrol for OTP if their OTP Status is
Pending
.
They may be prompted for the OTP depending on the
Date of Last OTP Entry
and the required one-time password frequency setting in
System Settings - Passwords
.
See Also
File Menu

---

## System Settings - Passwords tab

Source: https://accredo.co.nz/webhelp/SystemSettings_Passwords.htm

System Settings - Passwords tab
Accredo > File > System > Settings > Passwords tab
Select System settings controlling Single Sign On, and if Use Single Sign On is selected password settings for System Users.
Single Sign On
Use Single Sign On
Selected
, a Single Sign On (SSO) can be used for multiple applications. You can set up users at a system level, then have them manually or automatically log through to Companies. System users can be linked to a Windows login to be automatically logged into the system. See
SYS Users
.
You can only log in as a System User when this is
Selected
.
Unselected
, when you turn off SSO, you will be prompted to delete all system user information. If you select this, all system users will be deleted.
See
Single Sign On
for more details on setting up SSO.
Note: Only the ACCREDO master User can select or unselect this option.
When SSO is not selected, if the ACCREDO user password is not the default password then the password is required when selecting
Use Single Sign On
(this will only be the case if SSO has been enabled/disabled previously).
If Single Sign On is selected the following settings apply:
Minimum Password Length
Set the minimum password length for all Users. If this is not set to
0
, all Users must have a Password. If you increase the minimum password length, all users with a shorter password and with permission to change their password will be forced to change their password on login. Users with shorter passwords without permission to change passwords will need their password changed for them.
For
Allow Windows Login
, the minimum password length must be greater than zero.
Password Complexity
Require lower case
Selected
, at least one lower case character is required in passwords.
Require upper case
Selected
, at least one upper case character is required in passwords.
Require digit
Selected
, at least one digit is required in passwords.
Require punctuation
Selected
, at least one special character is required in passwords.
Multi-factor Authentication
One-time password enabled
Selected
, users can be enrolled for, and Win and Web logins may require a One-time password (OTP).
Require one-time password for Win logins
Selected
, Win logins will require OTP unless the user is exempted in
System User - Users tab
.
Note:
Web Client
OTP requirements are set per Client.
Prompt for one-time password entry every ... days
For Win logins. The number of days between OTP prompts.
0
means OTP is required for every login.
Expire Passwords every ... days
The number of days between password expiries.
0
means passwords will never expire.
Disallow password reuse within ... months
Track and prevent password reuse for a number of months.
0
means no restriction on reuse.
Exempt ACCREDO from expiry
Selected
, the ACCREDO master user is exempted from password expiry, e.g. where the ACCREDO user is used in scheduled tasks.
Allow Windows Login
Selected
, users can login using their Windows login. To select this, you must have a
Minimum Password Length
greater than zero.
Set up Windows User Names in the
SYS Users
form.
Prompt for Password every ... days
Enabled if
Allow Windows Login
is selected.
Windows users will be prompted for their password at an interval of the days entered. Defaults to
30
.
0
means never prompt for Accredo password, i.e. Windows password is all that is required.
Audit Successful Logins and Logouts
Selected
, successful login and logout will be logged in the
System Audit Log
.
Clear
, only failed login attempts are logged.

---

## System User Permission Strings

Source: https://accredo.co.nz/webhelp/SysUserPermissionsStrings.htm

User Permission Strings
SY - System
SY\Perm\Audit Log
SY\Perm\Backup And Restore\Company
SY\Perm\Backup And Restore\System
SY\Perm\Company Maintenance
SY\Perm\Customisations
SY\Perm\Force User Exit
SY\Perm\Licensee Details
SY\Perm\Lock Company
SY\Perm\Reports
SY\Perm\Scripts
SY\Perm\Scripts\Encrypted
SY\Perm\Settings
SY\Perm\Token Maintenance
SY\Perm\Users
SY\Perm\Users\Password
SY\Perm\Users\Permissions
SY\Perm\Users\Synchronisation
SY\Perm\Web Service\Log File Viewer
SY\Perm\Web Service\Monitor
SY\Perm\Web Service\Monitor Settings
SY\Perm\Web Service\Settings
SY\Perm\Web Service\Tokens
SY\Perm\Web Service\Web Client Provisioning
SY\Perm\Web Service\Web Clients

---

## System User Permissions

Source: https://accredo.co.nz/webhelp/SysUserPermissions.htm

User Permissions
SY - System
Audit Log
Backup And Restore
Company
System
Company Maintenance
Customisations
Force User Exit
Licensee Details
Lock Company
Reports
Scripts
Access
Encrypted
Settings
Token Maintenance
Users
Access
Password
Permissions
Synchronisation
Web Service
Log File Viewer
Monitor
Access
Monitor Settings
Settings
Tokens
Web Client Provisioning
Web Clients

---

## Table Designer

Source: https://accredo.co.nz/webhelp/CustomTableDesigner.htm

Table Designer
Navigator > Setup > Table Designer > Table Designer > Fields tab
You will be prompted to take a backup of your data before running the Table Designer. We recommend taking a backup before modifying any tables.
Use
MaxBasic
,
Data Interchange
and
Form Designer
to add and maintain Custom tables (.adb files), and index keys (.anx files). Files are
registered
and saved in the Company data folder. Data can be entered directly in Custom Tables from
Table Editor
. A Maintenance grid can be added to the Navigator using a
Script Shortcut
.
Note: We recommend custom table names contain only alphanumeric characters and underscores. If a custom table name has any of the following characters or contains spaces that table will not be included in the metadata for the Web Service -''#@$^!%&(),;.[]{}`~+=
For Custom Tables to work correctly in the Web Service there must be a single field that uniquely defines each row. That field should be indexed, and the index key should only include that field and be flagged Unique and Primary.
Use custom fields and index keys to extend Accredo tables (.pdb files) and indexes (.pnx files).
Custom fields added to an Accredo table will appear on a Custom tab, and can be customised into grids and report layouts. See also
Extend Accredo Tables
.
Warning: Adding and removing custom tables can affect other Accredo tables. Please consider the impact when using Table Designer, and use with caution. If you are unsure, contact Accredo Support.
Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Edit
(F11)
Edit the Table.
New Table
(
F4
)
Create a new table.
Upgrade...
(Alt+U)
Active if the table is saved and is not an XML file. Prompts you to select an XML template. The table will be restructured to match the XML schema in the file.
See also
Upgrade Tables Using Templates
.
Note: Any fields that are not included the XML schema file, and have not been renamed to match new Custom fields added in the schema will be dropped, and data in these fields will be lost. This also applies to custom indexes, as only indexes in the XML schema will be retained. A warning will be shown if data will be lost from the source table.
Document
(Alt+D)
Active if the table is saved, shows the object documentation.
Print Fields
(Ctrl+P)
Print the fields shown in the grid.
Fields Tab
No.
The ID number of the field, and the field's position on the table.
Name
The name of the field in the table. May be entered with spaces, these will be stripped for the field name and retained for the default display label.
Type
The type of data stored in the field affects the disk storage each field occupies. See
Table Field Types
for field types available.
Domain
Select from
An existing
Domain
for pre-defined field size and type, when the field is an existing field type.
Custom
Domain to define the field size for
String
fields, when the field does not meet an existing field type.
Custom
U Domain to define the field size for
UString
fields, when the field does not meet an existing field type.
A new Domain when the field is a new
Lookup
or
ID
(autoinc) field.
If an existing Domain (excluding
Custom and Custom U
) is selected, the Type, Size and Upper fields use the existing data (read-only). The field and the data have the usual Accredo rules. For example, GL Account codes must be formatted ####.###. The following Domain types are dependent on Company settings,
Amount
Discount
Rounding
Quantity
If the
Custom
Domain is selected, the Size and Upper fields can be specified.
To add a new Domain for a new
Lookup
field, a unique domain name called Z_{tablename} is required. The unique domain name will not be in the drop down list, so must be keyed in, domain names are limited to a maximum of 40 characters. When the table is saved, the table must be saved as {tablename.adb}. The
Lookup
field must be
Selected
when a new Domain is entered.
A Domain is required when a field in a custom table will be used as a
Lookup
field in other tables. A Domain is required for all fields with type
String
.
FX Code Field
FX Domain fields require an associated
CO Currency Code
Domain field in the table.
Add one or more fields with domain
CO Currency Code
before adding FX Fields. The
CO Currency Code
fields will populate the
FX Code Field
.
Select an
FX Code Field
from the list of
CO Currency Code
fields.
Size
You can set the maximum number of characters allowed in String and Variant Type fields. The maximum field size is based on the number of characters, 1 character = 1 byte.
Lookup
Selected
, creates a lookup domain for the field that can be added to another table. Lookup fields must have a Custom Domain name, in the form Z_{name} and must be type String.
Clear
, (default).
Description
Selected
, the field becomes the description for the lookup domain. Tables with Lookup fields must have a Lookup Description selected. Only one Lookup Description can be selected per table.
Clear
, (default).
Heat
Heat is used to indicate how frequently a field is updated. Fields with a heat level of 1 are the "coldest" i.e. never change, with heat progressing upward with frequency of change  to a maximum of 9 for the hottest field, the RecordRevision, which ticks up for every modification. Fields within a record are sorted in their heat order and only the portion of the record at the minimum heat field being changed and above is written. This allows Accredo to minimise write sizes. For example, a Created Date or ID field would have heat number
1
, as it is written only once when a record is created.
Heat is only editable for custom domain fields and fields in custom tables. Defaults to
2
.
Required
Selected
, a field value is required before saving.
Clear
, a record can be saved if the field is empty.
Left Pad
String fields are right padded to the maximum length to allow for left padding. Pads strings with space characters to the maximum size specified by adding spaces to the left of the string.
Upper
Selected
, entered text will be upper case (usually for codes).
Encrypt
Selected
, entered text will be encrypted. This can be used for bank account numbers.
Custom Field
Selected
, indicates the field is a custom field.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Zoom
(Ctrl+F12)
Open Table Designer Field in Form view to add, delete, edit and scroll. Move off the field to save changes, they will appear on
CLOSE.
Insert
(F4)
Insert a new field at the selected line.
Note: Table field and key schemas have a limit of size 65535. If a table schema exceeds this it cannot be saved. Tables exceeding this limit are not ideally designed, and should be redesigned.
Move
(Shift+Up) (Shift+Down)
Select a field and reorder the list.
Delete
(F3)
Delete the selected field.
Add Tracking Fields
Inserts tracking fields:
Created User Code
, The user who created the record.
Created Time Stamp
, The date time the record was created.
Modified User Code
, The user who last modified the record.
Modified Time Stamp
, The date time the record was last modified.
Calculated
Created Date, Created Time, Modified Date and Modified Time
fields are automatically created for the table from the Time Stamps.
Timestamps are stored in
UTC
and returned/displayed in Local Time.
The Created and Modified fields are automatically populated when a record is inserted in the table.
The Modified fields can be updated by calling the
StampModified
method when a record is edited. When changes are made to fields in a grid, the Modified fields are updated.
Change
Tracking Fields
Replaces
Created Date
,
Created Time
fields with
Created Time Stamp
, and
Modified Date
,
Modified Time
fields with
Modified Time Stamp
. Data is automatically mapped to the new fields on save. Calculated
Created Date, Created Time, Modified Date and Modified Time
fields are automatically created for the table for backward compatibility.
Add Record Revision
Inserts the
Record Revision
field, showing the integer number of times the record has been revised.
Buttons
Load...
(Alt+L)
Loads an existing Custom
adb
or Accredo
pdb
table, or a table schema
xml
or
Memory Table definition
pfm
, to use or edit.
Note: You can only load tables from the current Company data directory. Tables from other companies may have different data structures to your company, so loading tables from them could cause problems.
Save...
(Ctrl+S)
Saves the table, you can add data via DI, load to select or edit. You can only save tables to the current Company data directory. Other companies may have different data structures to your company, so saving tables between companies could cause problems.
If the table is locked by another user, you will be prompted to save the changes to an XML file, which can be applied to the table when it is not locked.
Cancel
(
Esc
)
Cancel all changes.
In This Section
TD Table Designer - Keys tab
Table Field Types
Table Editor
Table Register
Table Designer - Reports
Rebuild Custom Data Dictionary
Extend Accredo Tables

---

## Table Designer - Reports

Source: https://accredo.co.nz/webhelp/TableDesigner_Reports.htm

Table Designer - Reports
Navigator > Reports > Table Designer
In This Section
TD Reports - Add Layout

---

## Table Designer Tutorials

Source: https://accredo.co.nz/webhelp/TableDesignerTutorials.htm

Table Designer Tutorials
In This Section
TD Tutorial: Add a Category to Customers Table
TD Tutorial: Create a Yes / No table available to other tables

---

## TD Table Designer - Keys tab

Source: https://accredo.co.nz/webhelp/CustomTableDesigner_KeysTab.htm

TD Table Designer - Keys tab
Navigator > Setup > Table Designer > Table Designer > Keys tab
You can define the index keys for a custom table. An index key is a data structure that improves the speed of operations. Index keys can be created using one or more fields of a table, providing the basis for both rapid look-ups and efficient access to records.
To show an Inactive Button on
Lookup
fields for the table, ensure the Table has the following two Indices:
Name
Active
Master
, having as the first field a boolean named Inactive, and the second field the lookup field. For example,
ActiveProduct
for ICPROD.
Name
Master
, having as the first field the lookup field. For example,
Product
for ICPROD.
See also
Table Designer
.
Note: Custom keys added to Accredo tables cannot be set as
Unique
(see below) as this could violate Accredo data rules.
Fields
No.
The ID number of the index.
Name
The name of the index on the table.
Unique
Selected,
the index will be unique.
Clear,
non-unique index.
Note: Custom keys added to tables cannot be set to
Unique
as this could violate Accredo data rules.
Primary
Selected,
primary index for the table. May not be selected for indexes added to Accredo tables.
Clear,
non-primary index.
Parts
Select the fields that are to be indexed by this key.
ExNull
Selected
, exclude null value fields from the index.
Clear
, null value fields will be included in the index.
Descending
Selected
, index in descending order.
Clear
, index in ascending order.
Case Ins
Selected
, the index is case insensitive.
Clear
, the index is case sensitive.
Encrypt
Selected
, the key will be encrypted.
Cluster
Selected
, indicates the key used for
Optimise Tables
.
Custom Key
Selected
, indicates the key is a custom key.
Grid Toolbar
Expand Toolbar
(Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
Insert
(F4)
Insert a new field at the selected line.
Note: Table field and key schemas have a limit of size 65535. If a table schema exceeds this it cannot be saved. Tables exceeding this limit are not ideally designed, and should be redesigned.
Move
(Shift+Up) (Shift+Down)
Select a field and reorder the list.
Delete
(F3)
Delete the selected field.
See Also
Table Designer

---

## User Login

Source: https://accredo.co.nz/webhelp/UserLogin.htm

User Login
Accredo > View >
Company Login - OR -
Click the
User
field of the status bar in the lower right of the main Accredo window - OR -
Opens on startup if User Login is required. If the User only has access to one Company, or has a
default Company
, they will be automatically logged into that Company.
The status bar shows the logged in User code.
Users are set up in Navigator > Setup > Company > Users >
Users, Groups and Roles
.
User Code
Password
Enter the User code and Password.
Force login
(Alt+F)
Force the next User to enter a valid User code and Password.
Show Password
Hide Password
Toggle Password visibility to check your input.
Change User Password
(Alt+C)
To change a Password, enter the existing password in the
Old Password
field (if one exists), enter the new password in the
New Password
and
Confirm Password
fields. This is available dependent on
Permissions
, and if System User and Company User match, the
Company Setting
for
Allow System Password Sync.
Note: Accredo forms are configured based on the User Permissions of the User who opens the forms. If the User logged is changed while forms are open, the permissions on the open forms will not change. If you are switching from a user with higher permissions to a user with lower permissions, we recommend closing forms before changing users.
See Also
View Menu

---

## User Permission Strings

Source: https://accredo.co.nz/webhelp/UserPermissionsStrings.htm

User Permission Strings
CO - Company
CO\Perm\Bank Account Change
CO\Perm\Banking Media
CO\Perm\Batch Email
CO\Perm\Branches
CO\Perm\Contact Categories
CO\Perm\Contacts
CO\Perm\Customisations\Grids
CO\Perm\Customisations\Toolbars
CO\Perm\Decimals
CO\Perm\Delivery Addresses
CO\Perm\Departments
CO\Perm\Designers
CO\Perm\Details
CO\Perm\Discounts
CO\Perm\Display
CO\Perm\Document Defaults
CO\Perm\File Exports
CO\Perm\File Upload Extensions
CO\Perm\Force User Exit
CO\Perm\Global Narratives
CO\Perm\Link Categories
CO\Perm\Links
CO\Perm\Mail Settings
CO\Perm\Memo Categories
CO\Perm\Memos
CO\Perm\Periods
CO\Perm\Price Lists
CO\Perm\Report Preferences
CO\Perm\Reports
CO\Perm\Reports Destinations
CO\Perm\Reports\Layout Management
CO\Perm\Reports\Layouts
CO\Perm\Reports\Queries
CO\Perm\Reports\View Saved Report
CO\Perm\Scripts
CO\Perm\Scripts\Encrypted
CO\Perm\Scripts\Events
CO\Perm\Scripts\List Views
CO\Perm\Scripts\Report Lists
CO\Perm\Scripts\Set Stamp User
CO\Perm\Scripts\Shortcuts
CO\Perm\Settings
CO\Perm\Tasks\Aliasing
CO\Perm\Tasks\Change Memo User
CO\Perm\Tasks\Merging
CO\Perm\Tasks\Optimise
CO\Perm\Tasks\Prune
CO\Perm\Tasks\Recovery
CO\Perm\User Access Times
CO\Perm\Users
CO\Perm\Users\Password
CO\Perm\Users\Permissions
CO\Perm\Users\Preferences
CO\Perm\Users\Settings
CO\Perm\Zoom
AR - Accounts Receivable
AR\Perm\Batch Email
AR\Perm\Categories
AR\Perm\Customer Groups
AR\Perm\Customers
AR\Perm\Customers\Balances
AR\Perm\Customers\Bank Account
AR\Perm\Customers\Banking
AR\Perm\Customers\Budgets
AR\Perm\Customers\Cash Customers
AR\Perm\Customers\Contacts
AR\Perm\Customers\Credit Limits
AR\Perm\Customers\Delivery Addresses
AR\Perm\Customers\Discounts
AR\Perm\Customers\Payment Terms
AR\Perm\Customers\Price Lists
AR\Perm\Customers\Prospect Customers
AR\Perm\Customers\Sales
AR\Perm\Customers\Stop Credit
AR\Perm\Designers
AR\Perm\Labels
AR\Perm\Links
AR\Perm\Memos
AR\Perm\Recovery
AR\Perm\Reports
AR\Perm\Reports\Layouts
AR\Perm\Reports\Queries
AR\Perm\Sales Areas
AR\Perm\Sales Areas\Balances
AR\Perm\Sales Areas\Budgets
AR\Perm\Sales Groups
AR\Perm\Sales Groups\Balances
AR\Perm\Sales Groups\Budgets
AR\Perm\Sales Persons
AR\Perm\Sales Persons\Balances
AR\Perm\Sales Persons\Budgets
AR\Perm\Settings
AR\Perm\Tasks\Allocations
AR\Perm\Tasks\End Of Periods
AR\Perm\Tasks\Generate Overdue Interest
AR\Perm\Tasks\Statements
AR\Perm\Tasks\Transfer To GL
AR\Perm\Transactions
AR\Perm\Transactions\Credits
AR\Perm\Transactions\Discount
AR\Perm\Transactions\GL Account
AR\Perm\Transactions\Invoices
AR\Perm\Transactions\Journals
AR\Perm\Transactions\Terms
IC - Inventory Control
IC\Perm\Batches\Adjustments
IC\Perm\Batches\Adjustments\Post
IC\Perm\Batches\Manufactures
IC\Perm\Batches\Manufactures\Post
IC\Perm\Batches\Receipts
IC\Perm\Batches\Receipts\Post
IC\Perm\Bins
IC\Perm\Categories
IC\Perm\Components
IC\Perm\Designers
IC\Perm\Expired Stock
IC\Perm\Labels
IC\Perm\Links
IC\Perm\Locations
IC\Perm\Memos
IC\Perm\Posted Documents
IC\Perm\Products
IC\Perm\Products\Activity
IC\Perm\Products\Budgets
IC\Perm\Products\Commissions
IC\Perm\Products\Cost Prices
IC\Perm\Products\Discounts
IC\Perm\Products\Quantities
IC\Perm\Products\Sell Prices
IC\Perm\Products\Supplier Cost Prices
IC\Perm\Products\Tracking
IC\Perm\Products\UOM
IC\Perm\Recovery
IC\Perm\Reports
IC\Perm\Reports\Layouts
IC\Perm\Reports\Queries
IC\Perm\Settings
IC\Perm\Stock Groups
IC\Perm\Store Persons
IC\Perm\Tasks\Aliasing and Merging Nos
IC\Perm\Tasks\Bin Counts
IC\Perm\Tasks\Bin Movements
IC\Perm\Tasks\End Of Periods
IC\Perm\Tasks\Printing
IC\Perm\Tasks\Repricing
IC\Perm\Tasks\Stocktakes
IC\Perm\Tasks\Stocktakes\Counts
IC\Perm\Tasks\Transfer To GL
IC\Perm\Transactions
IC\Perm\Transactions\Adjustments
IC\Perm\Transactions\GL Account
IC\Perm\Transactions\Manufactures
IC\Perm\Transfers
IC\Perm\Units Of Measure
IC\Perm\Units Of Measure Groups
IN - Invoicing System
IN\Perm\Categories
IN\Perm\Credits
IN\Perm\Designers
IN\Perm\Invoices
IN\Perm\Invoices\Cash Sales
IN\Perm\Invoices\Commissions
IN\Perm\Invoices\Cost Prices
IN\Perm\Invoices\Discounts
IN\Perm\Invoices\GL Account
IN\Perm\Invoices\Packing Slips
IN\Perm\Invoices\Payment Terms
IN\Perm\Invoices\Price Lists
IN\Perm\Invoices\Reprice
IN\Perm\Invoices\Sales Person
IN\Perm\Invoices\Sell Prices
IN\Perm\Invoices\Stop Credit
IN\Perm\Labels
IN\Perm\Links
IN\Perm\Memos
IN\Perm\Posted Documents
IN\Perm\Quotes
IN\Perm\Quotes\Invoices from Quotes
IN\Perm\Quotes\Orders from Quotes
IN\Perm\Recovery
IN\Perm\Reports
IN\Perm\Reports\Layouts
IN\Perm\Reports\Queries
IN\Perm\Settings
IN\Perm\Shippers
IN\Perm\Standing Invoices
IN\Perm\Tasks\Posting
IN\Perm\Tasks\Printing
IN\Perm\Tasks\Repricing
IN\Perm\Tasks\Revalue
OE - Order Entry
OE\Perm\Designers
OE\Perm\Invoices\Discounts
OE\Perm\Invoices\Quantities
OE\Perm\Invoices\Sell Prices
OE\Perm\Labels
OE\Perm\Links
OE\Perm\Memos
OE\Perm\Orders
OE\Perm\Orders\Commissions
OE\Perm\Orders\Cost Prices
OE\Perm\Orders\Discounts
OE\Perm\Orders\Generate
OE\Perm\Orders\GL Account
OE\Perm\Orders\Mark Processed
OE\Perm\Orders\Price Lists
OE\Perm\Orders\Reprice
OE\Perm\Orders\Sales Person
OE\Perm\Orders\Sell Prices
OE\Perm\Orders\Stop Credit
OE\Perm\Posted Documents
OE\Perm\Recovery
OE\Perm\Reports
OE\Perm\Reports\Layouts
OE\Perm\Reports\Queries
OE\Perm\Settings
OE\Perm\Standing Orders
OE\Perm\Tasks\Fullfillment
OE\Perm\Tasks\Generation
OE\Perm\Tasks\Printing
OE\Perm\Tasks\Repricing
OE\Perm\Tasks\Revalue
SP - Special Pricing
SP\Perm\Designers
SP\Perm\Price List Designer
SP\Perm\Recovery
SP\Perm\Reports
SP\Perm\Reports\Layouts
SP\Perm\Reports\Queries
SP\Perm\Rules
SP\Perm\Rules\Bypass Margin
SP\Perm\Settings
SP\Perm\What
SP\Perm\Where
SP\Perm\Who
SA - Sales Analysis
SA\Perm\Designer
SA\Perm\Reports
AP - Accounts Payable
AP\Perm\Batch Email
AP\Perm\Categories
AP\Perm\Cost Codes
AP\Perm\Creditor Groups
AP\Perm\Creditors
AP\Perm\Creditors\Balances
AP\Perm\Creditors\Bank Account
AP\Perm\Creditors\Budgets
AP\Perm\Creditors\Contacts
AP\Perm\Creditors\Prospect Creditors
AP\Perm\Designers
AP\Perm\Expenses
AP\Perm\Expenses\Balances
AP\Perm\Expenses\Budgets
AP\Perm\Labels
AP\Perm\Links
AP\Perm\Memos
AP\Perm\Posted Documents
AP\Perm\Recovery
AP\Perm\Reports
AP\Perm\Reports\Layouts
AP\Perm\Reports\Queries
AP\Perm\Settings
AP\Perm\Shipments
AP\Perm\Shipments\Cost Prices
AP\Perm\Shipments\GL Account
AP\Perm\Shipments\Invoice Only
AP\Perm\Shipments\Post Invoices
AP\Perm\Shipments\Post Receipts
AP\Perm\Shipments\Quantities
AP\Perm\Shipments\Receipt Only
AP\Perm\Shipments\Revalue
AP\Perm\Shipments\Vendor Code
AP\Perm\Tasks\Allocations
AP\Perm\Tasks\Approvals
AP\Perm\Tasks\Cheques
AP\Perm\Tasks\Electronic
AP\Perm\Tasks\End Of Periods
AP\Perm\Tasks\Generate
AP\Perm\Tasks\Printing
AP\Perm\Tasks\Remittances
AP\Perm\Tasks\Repricing
AP\Perm\Tasks\Transfer To GL
AP\Perm\Transactions
AP\Perm\Transactions\GL Account
AP\Perm\Transactions\Journals
AP\Perm\Transactions\Payments
PO - Purchase Orders
PO\Perm\Authorisations
PO\Perm\Categories
PO\Perm\Designers
PO\Perm\Labels
PO\Perm\Links
PO\Perm\Memos
PO\Perm\Orders
PO\Perm\Orders\Cost Prices
PO\Perm\Orders\GL Account
PO\Perm\Orders\Mark Processed
PO\Perm\Orders\Vendor Code
PO\Perm\Posted Documents
PO\Perm\Quotes
PO\Perm\Recovery
PO\Perm\Reports
PO\Perm\Reports\Layouts
PO\Perm\Reports\Queries
PO\Perm\Settings
PO\Perm\StandingOrders
PO\Perm\Tasks\Printing
PO\Perm\Tasks\Repricing
PO\Perm\Tasks\Revalue
PP - Purchase Pricing
PP\Perm\Designers
PP\Perm\Price List Designer
PP\Perm\Recovery
PP\Perm\Reports
PP\Perm\Reports\Layouts
PP\Perm\Reports\Queries
PP\Perm\Rules
PP\Perm\Settings
PP\Perm\What
PP\Perm\Where
PP\Perm\Who
PA - Purchase Analysis
PA\Perm\Designer
PA\Perm\Reports
CB - Cash Book
CB\Perm\Analysis Groups
CB\Perm\Analysis Groups\Balances
CB\Perm\Analysis Groups\Budgets
CB\Perm\Autopayments
CB\Perm\Bank Accounts
CB\Perm\Bank Accounts\Balances
CB\Perm\Categories
CB\Perm\Designers
CB\Perm\Links
CB\Perm\Memos
CB\Perm\Recovery
CB\Perm\Reports
CB\Perm\Reports\Layouts
CB\Perm\Reports\Queries
CB\Perm\Settings
CB\Perm\Tasks\Banking Summary
CB\Perm\Tasks\Banking\Allow Cross Period Banking
CB\Perm\Tasks\Banking\Bank Account
CB\Perm\Tasks\Banking\Banking Items
CB\Perm\Tasks\Banking\Charges
CB\Perm\Tasks\Banking\Electronic
CB\Perm\Tasks\End Of Periods
CB\Perm\Tasks\Reconciliations
CB\Perm\Tasks\Rules
CB\Perm\Tasks\Transfer To GL
CB\Perm\Transactions
CB\Perm\Transactions\Autopayments
CB\Perm\Transactions\GL Account
FA - Fixed Assets
FA\Perm\Asset Groups
FA\Perm\Assets
FA\Perm\Assets\Balances
FA\Perm\Books
FA\Perm\Categories
FA\Perm\Depreciation Defaults
FA\Perm\Designers
FA\Perm\Labels
FA\Perm\Links
FA\Perm\Locations
FA\Perm\Memos
FA\Perm\Recovery
FA\Perm\Reports
FA\Perm\Reports\Layouts
FA\Perm\Reports\Queries
FA\Perm\Settings
FA\Perm\Tasks\Change Depreciation
FA\Perm\Tasks\End Of Periods
FA\Perm\Tasks\Generate Depreciation
FA\Perm\Tasks\Transfer To GL
FA\Perm\Transactions
FA\Perm\Transactions\Additions
FA\Perm\Transactions\Adjustments
FA\Perm\Transactions\Disposals
FA\Perm\Transactions\Manual Depreciation
FA\Perm\Transactions\Revaluations
JC - Job Costing
JC\Perm\Batches
JC\Perm\Batches\Posting
JC\Perm\Budgets
JC\Perm\Categories
JC\Perm\Components
JC\Perm\Cost Centres
JC\Perm\Designers
JC\Perm\Estimates
JC\Perm\Job Groups
JC\Perm\Job Persons
JC\Perm\Jobs
JC\Perm\Jobs\Complete Job
JC\Perm\Jobs\Cost Prices
JC\Perm\Jobs\Discounts
JC\Perm\Jobs\Re-open Job
JC\Perm\Jobs\Sell Prices
JC\Perm\Jobs\Stop Credit
JC\Perm\Labels
JC\Perm\Links
JC\Perm\Memos
JC\Perm\Recovery
JC\Perm\Reports
JC\Perm\Reports\Layouts
JC\Perm\Reports\Queries
JC\Perm\Settings
JC\Perm\Tasks\End Of Periods
JC\Perm\Tasks\Invoicing
JC\Perm\Tasks\Printing
JC\Perm\Tasks\Repricing
JC\Perm\Tasks\Transfer To GL
JC\Perm\Transactions
JC\Perm\Transactions\GL Account
GL - General Ledger
GL\Perm\Accounts
GL\Perm\Budgets
GL\Perm\Categories
GL\Perm\Chart of Accounts
GL\Perm\Designers
GL\Perm\Links
GL\Perm\Memos
GL\Perm\Recovery
GL\Perm\Reports
GL\Perm\Reports\Layouts
GL\Perm\Reports\Queries
GL\Perm\Restricted Access
GL\Perm\Settings
GL\Perm\Tasks\End Of Periods
GL\Perm\Tasks\Reconciliations
GL\Perm\Tasks\Transfer from Sub Ledgers
GL\Perm\Transactions
GL\Perm\Transactions\Exporting
GL\Perm\Transactions\Importing
GL\Perm\Transactions\Posting
GL\Perm\Transactions\Subsidiary Importing
GL\Perm\Transactions\Unposting
JA - Job Analysis
JA\Perm\Designer
JA\Perm\Reports
RW - Report Designer
RW\Perm\Custom Reports
RW\Perm\Designers
EDI - Data Interchange
EDI\Perm\Database Access
EDI\Perm\Exports
EDI\Perm\Imports
EDI\Perm\Objects
EDI\Perm\Price Book Imports
EDI\Perm\SQL Query Builder
TD - Table Designer
TD\Perm\Recovery
TD\Perm\Reports
TD\Perm\Reports\Layouts
TD\Perm\Reports\Queries
TD\Perm\Tab Customisation
TD\Perm\Table Designer
TD\Perm\Table Editor
FD - Form Designer
FD\Perm\Form Designer
GST - Goods and Services Tax
GST\Perm\Designers
GST\Perm\Links
GST\Perm\Memos
GST\Perm\Recovery
GST\Perm\Reports
GST\Perm\Reports\Layouts
GST\Perm\Reports\Queries
GST\Perm\Return Forms
GST\Perm\Settings
GST\Perm\Tasks\Transfer To GL
GST\Perm\Transactions
FX - Foreign Exchange
FX\Perm\Currencies
FX\Perm\Rate Limits
FX\Perm\Rate Types
FX\Perm\Rates
FX\Perm\Reports
FX\Perm\Reports\Layouts
FX\Perm\Settings

---

## User Permissions

Source: https://accredo.co.nz/webhelp/UserPermissions.htm

User Permissions
CO - Company
Bank Account Change
Banking Media
Batch Email
Branches
Contact Categories
Contacts
Customisations
Grids
Toolbars
Decimals
Delivery Addresses
Departments
Designers
Details
Discounts
Display
Document Defaults
File Exports
File Upload Extensions
Force User Exit
Global Narratives
Link Categories
Links
Mail Settings
Memo Categories
Memos
Periods
Price Lists
Report Preferences
Reports
Access
Reports Destinations
Layout Management
Layouts
Queries
View Saved Report
Scripts
Access
Encrypted
Events
List Views
Report Lists
Set Stamp User
Shortcuts
Settings
Tasks
Aliasing
Change Memo User
Merging
Optimise
Prune
Recovery
User Access Times
Users
Access
Password
Permissions
Preferences
Settings
Zoom
AR - Accounts Receivable
Batch Email
Categories
Customer Groups
Customers
Access
Balances
Bank Account
Banking
Budgets
Cash Customers
Contacts
Credit Limits
Delivery Addresses
Discounts
Payment Terms
Price Lists
Prospect Customers
Sales
Stop Credit
Designers
Labels
Links
Memos
Recovery
Reports
Access
Layouts
Queries
Sales Areas
Access
Balances
Budgets
Sales Groups
Access
Balances
Budgets
Sales Persons
Access
Balances
Budgets
Settings
Tasks
Allocations
End Of Periods
Generate Overdue Interest
Statements
Transfer To GL
Transactions
Access
Credits
Discount
GL Account
Invoices
Journals
Terms
IC - Inventory Control
Batches
Adjustments
Access
Post
Manufactures
Access
Post
Receipts
Access
Post
Bins
Categories
Components
Designers
Expired Stock
Labels
Links
Locations
Memos
Posted Documents
Products
Access
Activity
Budgets
Commissions
Cost Prices
Discounts
Quantities
Sell Prices
Supplier Cost Prices
Tracking
UOM
Recovery
Reports
Access
Layouts
Queries
Settings
Stock Groups
Store Persons
Tasks
Aliasing and Merging Nos
Bin Counts
Bin Movements
End Of Periods
Printing
Repricing
Stocktakes
Access
Counts
Transfer To GL
Transactions
Access
Adjustments
GL Account
Manufactures
Transfers
Units Of Measure
Access
Units Of Measure Groups
IN - Invoicing System
Categories
Credits
Designers
Invoices
Access
Cash Sales
Commissions
Cost Prices
Discounts
GL Account
Packing Slips
Payment Terms
Price Lists
Reprice
Sales Person
Sell Prices
Stop Credit
Labels
Links
Memos
Posted Documents
Quotes
Access
Invoices from Quotes
Orders from Quotes
Recovery
Reports
Access
Layouts
Queries
Settings
Shippers
Standing Invoices
Tasks
Posting
Printing
Repricing
Revalue
OE - Order Entry
Designers
Invoices
Discounts
Quantities
Sell Prices
Labels
Links
Memos
Orders
Access
Commissions
Cost Prices
Discounts
Generate
GL Account
Mark Processed
Price Lists
Reprice
Sales Person
Sell Prices
Stop Credit
Posted Documents
Recovery
Reports
Access
Layouts
Queries
Settings
Standing Orders
Tasks
Fullfillment
Generation
Printing
Repricing
Revalue
SP - Special Pricing
Designers
Price List Designer
Recovery
Reports
Access
Layouts
Queries
Rules
Access
Bypass Margin
Settings
What
Where
Who
SA - Sales Analysis
Designer
Reports
AP - Accounts Payable
Batch Email
Categories
Cost Codes
Creditor Groups
Creditors
Access
Balances
Bank Account
Budgets
Contacts
Prospect Creditors
Designers
Expenses
Access
Balances
Budgets
Labels
Links
Memos
Posted Documents
Recovery
Reports
Access
Layouts
Queries
Settings
Shipments
Access
Cost Prices
GL Account
Invoice Only
Post Invoices
Post Receipts
Quantities
Receipt Only
Revalue
Vendor Code
Tasks
Allocations
Approvals
Cheques
Electronic
End Of Periods
Generate
Printing
Remittances
Repricing
Transfer To GL
Transactions
Access
GL Account
Journals
Payments
PO - Purchase Orders
Authorisations
Categories
Designers
Labels
Links
Memos
Orders
Access
Cost Prices
GL Account
Mark Processed
Vendor Code
Posted Documents
Quotes
Recovery
Reports
Access
Layouts
Queries
Settings
StandingOrders
Tasks
Printing
Repricing
Revalue
PP - Purchase Pricing
Designers
Price List Designer
Recovery
Reports
Access
Layouts
Queries
Rules
Settings
What
Where
Who
PA - Purchase Analysis
Designer
Reports
CB - Cash Book
Analysis Groups
Access
Balances
Budgets
Autopayments
Bank Accounts
Access
Balances
Categories
Designers
Links
Memos
Recovery
Reports
Access
Layouts
Queries
Settings
Tasks
Banking
Banking Summary
Allow Cross Period Banking
Bank Account
Banking Items
Charges
Electronic
End Of Periods
Reconciliations
Rules
Transfer To GL
Transactions
Access
Autopayments
GL Account
FA - Fixed Assets
Asset Groups
Assets
Access
Balances
Books
Categories
Depreciation Defaults
Designers
Labels
Links
Locations
Memos
Recovery
Reports
Access
Layouts
Queries
Settings
Tasks
Change Depreciation
End Of Periods
Generate Depreciation
Transfer To GL
Transactions
Access
Additions
Adjustments
Disposals
Manual Depreciation
Revaluations
JC - Job Costing
Batches
Access
Posting
Budgets
Categories
Components
Cost Centres
Designers
Estimates
Job Groups
Job Persons
Jobs
Access
Complete Job
Cost Prices
Discounts
Re-open Job
Sell Prices
Stop Credit
Labels
Links
Memos
Recovery
Reports
Access
Layouts
Queries
Settings
Tasks
End Of Periods
Invoicing
Printing
Repricing
Transfer To GL
Transactions
Access
GL Account
GL - General Ledger
Accounts
Budgets
Categories
Chart of Accounts
Designers
Links
Memos
Recovery
Reports
Access
Layouts
Queries
Restricted Access
Settings
Tasks
End Of Periods
Reconciliations
Transfer from Sub Ledgers
Transactions
Access
Exporting
Importing
Posting
Subsidiary Importing
Unposting
JA - Job Analysis
Designer
Reports
RW - Report Designer
Custom Reports
Designers
EDI - Data Interchange
Database Access
Exports
Imports
Objects
Price Book Imports
SQL Query Builder
TD - Table Designer
Recovery
Reports
Access
Layouts
Queries
Tab Customisation
Table Designer
Table Editor
FD - Form Designer
Form Designer
GST - Goods and Services Tax
Designers
Links
Memos
Recovery
Reports
Access
Layouts
Queries
Return Forms
Settings
Tasks
Transfer To GL
Transactions
FX - Foreign Exchange
Currencies
Rate Limits
Rate Types
Rates
Reports
Access
Layouts
Settings

---

## Users, Groups and Roles - Permissions tab

Source: https://accredo.co.nz/webhelp/COUsers_Permissions.htm

Users, Groups and Roles - Permissions tab
Navigator > Setup > Company > Users > Users, Groups and Roles > Permissions tab
Set permissions for the User or Group. Permissions default to none for new users and groups. The ACCREDO master user has control permissions for everything and these cannot be changed.
To set folder and option permissions, click a folder, click an option, select a permission, see
User Permissions
. A permission can influence others. To set permissions for a group of functions, select the folder containing the group (for example, select the Accredo folder to set permissions for all functions), then select a Permission level from the toolbar. You can also right-click an option to set the Permissions.
The folders show the icon for the highest level of permission within the folder. You can fully expand and collapse the permission folders.
The Level indicates the users current permission level for the Permission, the Description indicates which the Permission controls access to. Some permissions are interdependent. See Report
Customise Layouts
for an example of how different permission options affect one another.
You can select a Group for a User. When a Group is selected, the User assumes the permissions of the Group. The Permissions will be displayed as read-only, and the User's permissions cannot be individually edited. To edit permissions for the Group, select the Group, then enter edit mode. To edit Permissions for an individual User, ensure the User is not part of a Group.
See
User Permissions
to list all available permissions. See also
Users, Groups and Roles - User tab
.
Toolbar
Expand Toolbar
(
Ctrl+F9)
Expand the toolbar to give access to all toolbar options. Press
Esc
to close the expanded toolbar.
All None
(Alt+N)
Set permission for the selected folder to
None
, so no access is available.
All Read
(Alt+R)
Set permission for the selected folder to
Read
, so the folder is available for reading.
All Write
(Alt+W)
Set permission for the selected folder to
Write
, to allow editing.
All Control
(Alt+C)
Set permission for the selected folder to
Control
, to allow editing, inserting and deleting.
Expand Folder
(Shift+Num*)
Expand all folders to show all options available under the selected folder.
Collapse Folder
(Shift+Num/)
Collapse the folder to show only the selected folder, without showing options available under.
NOTE: Roles do not have permissions. Fields on this tab are unavailable when a Role is selected.
In This Section
User Permissions
See Also
Users, Groups and Roles - User tab

---

## Users, Groups and Roles - Preferences tab

Source: https://accredo.co.nz/webhelp/COUsers_Preferences.htm

Users, Groups and Roles - Preferences tab
Navigator > Setup > Company > Users > Users, Groups and Roles > Preferences tab
See also
Users, Groups and Roles - User tab
.
Set Preferences for a User.
Use machine date on startup
Selected,
System Date is the computer date on Company open. System Period is the period that contains that date (if found).
Clear,
System Date and System Period retain their most recent values.
Update date at midnight
Selected,
If System Date is the computer date and the user is logged in over midnight, the System Date and Period will roll forward.
Clear,
System Date and System Period do not roll forward until company is closed and reopened.
Prompt for date on startup
Selected,
on Company open, a message requests System Date and System Period.
Clear,
Company will open with the most recent date and period, or the computer date and matching period if
Use machine date on startup
(above) is
Selected.
Show created & modified status bar on records
Selected
, shows the User code and Date and Time stamp the record was created, or last modified.
Show period status bar
Selected,
the Current Period is shown beside each Module code.
Show detailed hint on lookup controls
Selected,
hovering over a lookup code, a hint appears with details of the code per the fields selected in the lookup.
Clear,
the hint is inactivated.
Show extra buttons on lookup controls
Selected,
all buttons on
Lookups
are available.
Clear,
filter, memo, open and show inactive buttons are not shown, keyboard shortcuts will operate.
Always show buttons when editing
Selected,
buttons (for example, the calculator, or lookup) become available for read-only controls.
Hide usages by default
Selected,
Show/Hide Usages
for Manual Kitsets in
IN Enter Invoices
and
OE Enter Sales Order
lines will be set to Hide by default.
Clear
,
Show/Hide Usages
for Manual Kitsets in IN Enter Invoices and OE Order Entry will be set to Show by default.
Prompt for Delete Line On by default
Selected
,
Prompt for Delete Line
buttons will be set to On by default. The "Delete record?" confirmation message will appear when lines are deleted.
Unselected
,
Prompt for Delete Line
buttons will be set to Off by default.
Show Memo Previews
Selected,
show the the preview pane on Memo windows.
Clear,
hide the preview pane on Memo windows.
Enable Delete on document and batch forms
Selected
, (default) when the user has delete permission, the
Delete
button on form toolbars is enabled.
Clear
, the
Delete
button on form toolbars is not enabled. This can be used when users are confusing the Delete Document and Delete Line buttons.
Hide completed OE lines by default
Selected,
hide status Processed and Cancelled lines for Unprocessed and Open Orders in
OE Sales Orders
.
Clear
, show all lines for Unprocessed and Open Orders in
OE Sales Orders
.
and
Hides or shows completed lines on the order.
Hide completed PO lines by default
Selected,
hide status Processed and Cancelled lines for Unprocessed and Open Orders in
PO Purchase Orders
.
Clear
, show status Processed lines for Unprocessed and Open Orders in
PO Purchase Orders
.
and
Hides or shows completed lines on the order.
Ctrl+Left & Ctrl+Right move to Next/Previous
Word,
the
Ctrl+Left
and
Ctrl+Right
keys operate as word left and right within an edit control.
Column,
the
Ctrl+Left
and
Ctrl+Right
keys move to the next column in multi column forms.
Field,
the
Ctrl+Left
and
Ctrl+Right
move to the next control (same as
Tab
/
Shift+Tab
).
See
Accredo Keyboard Shortcuts
.
Reminder Interval
How long prior to events to be reminded.
Dismiss Reminder
Preferred action when dismissing reminders.
Inactivate
, default, Reminder is set to Inactive.
To Memo
, Reminder is converted to a Memo and left as Active.
Contact Lookup ordering
Determine the order for looking up Contacts.
Memo Tab Ordering
Sort Order to display memos. Select from:
Descending Date
Ascending Date
UOM Enquiry Default
Sets the UOM Code in
IC Product - Quantity tab
,
IC Product - Locations tab
(Saturn only) ,
IC Product Quantities
and
IC Product Tracking Quantities
forms to the specified UOM Code for the selected Product.
If UOM is Active select from Base UOM (default), Sale UOM, Purchase UOM or Manufacture UOM.
Note: This tab is not available for Groups or Roles, as Groups and Roles do not have Preferences.

---

## Using Events to set Batch Selection Defaults

Source: https://accredo.co.nz/webhelp/UsingEventsToSetBatchSelectionDefaults.htm

Using Events to set Batch Selection Defaults
Navigator > Setup > Company > Scripts > Script Events
You can set defaults for batch selection forms using an OnOpen script event.
This is useful for batch email forms, where you may want to set default values on the forms.
For example, you can set email defaults on the IN Email Invoices form. The following sample code could be used in an INEmailInvoiceReport.OnOpen event to set field defaults:
Dim EmailInvoiceForm as Object
EmailInvoiceForm = GetTriggerObject
EmailInvoiceForm.CustomerFrom = "ASHENG"
EmailInvoiceForm.CustomerTo = "ASHENG"
EmailInvoiceForm.CC = "CC Test"
EmailInvoiceForm.BCC = "BCC Test"
EmailInvoiceForm.ReplyTo = "Reply To Test"
EmailInvoiceForm.From = "From Test"
EmailInvoiceForm.EmailSubject = "Subject Test"
EmailInvoiceForm.EmailFileName = "Email File Name Test"
This allows you to set defaults for fields including the Customer selection, CC, BCC, ReplyTo, From address, Subject and Attachment.
Note that if you are using an email template, values set in the OnOpen script will override the template values.

---

## Workstation Settings and Preferences

Source: https://accredo.co.nz/webhelp/WorkstationSettingsAndPreferences.htm

Workstation Settings and Preferences
Accredo recommend the following settings and preferences for Accredo workstations.
Display Settings
We recommend a screen / desktop area resolution of 1280 x 1024 pixels or higher. Accredo supports High DPI (Dots Per Inch) scaling, from 100% to 200%.
Date / Time Settings
Accredo uses the Short Date style specified in Windows Regional Options. We recommend using dd-mmm-yyyy format. Other applications may require dd-mm-yyyy format. We do not recommend using formats where the month precedes the day (for example, mm-dd-yyyy) or two-digit year formats (for example, dd-mm-yy).
Ensure the date and time settings on each workstation are correct, and check they match the date and time settings on the Server.
Power and Sleep Settings
If your computer is configured to sleep after a period of idle time, ensure that you are not leaving Accredo running across this. When Windows puts a computer to sleep, open network connections are dropped because it is not responding to the server. This is a Windows setting and is not something Accredo has control over. If your machine wakes from sleep, Accredo wakes up and can't survive since all its network connections have gone.
Certain Windows power settings can cause your network adapter to go to sleep which can result in network errors. Ensure that the settings for Link State Power Management is set to 'Off'. You can find this in the Advanced settings for your Windows power plan. Go to Windows Control Panel > Power Options > Change Plan Settings > Change advanced power settings > PCI Express.
Drive Mapping
Drive Letters mapped via Group Policy should be configured to Update rather than Replace. Replacing can cause the mapped drive to disconnect, and reconnecting can trigger
Error Code 59 or 87 issues
.
Preferences
Accredo > View > Preferences
Use the Preferences in Accredo to modify options per workstation. Preferences are stored in the System by default, but can be stored in the workstation registry. The default location is set in File > System > Settings.
Preferences per user can be set in Setup > Company > Users > Users, Groups and Roles > Preferences tab.
See Also
Install Accredo Client

---

