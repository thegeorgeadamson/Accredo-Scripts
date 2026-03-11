# MaxBasic Functions A-Z Reference

> Complete alphabetical reference of all MaxBasic functions

**Sections:** 482

---

## Quick Reference

- [Abort - MaxBasic Function](#abort---maxbasic-function)
- [Abs - MaxBasic Function](#abs---maxbasic-function)
- [AddCompany - MaxBasic Function](#addcompany---maxbasic-function)
- [AddFileLink - MaxBasic Function](#addfilelink---maxbasic-function)
- [AddGST - MaxBasic Function](#addgst---maxbasic-function)
- [AddMonths - MaxBasic Function](#addmonths---maxbasic-function)
- [AddNewYear - MaxBasic Function](#addnewyear---maxbasic-function)
- [AddPeriod - MaxBasic Function](#addperiod---maxbasic-function)
- [AddressType - MaxBasic Function](#addresstype---maxbasic-function)
- [AddWebLink - MaxBasic Function](#addweblink---maxbasic-function)
- [AllowInteractive - MaxBasic Function](#allowinteractive---maxbasic-function)
- [AllowManualNumbering - MaxBasic Function](#allowmanualnumbering---maxbasic-function)
- [AmountDecimals - MaxBasic Function](#amountdecimals---maxbasic-function)
- [APAllocateTransactions - MaxBasic Function](#apallocatetransactions---maxbasic-function)
- [APEndOfPeriod - MaxBasic Function](#apendofperiod---maxbasic-function)
- [AppBits - MaxBasic Function](#appbits---maxbasic-function)
- [AppendPDFs - MaxBasic Function](#appendpdfs---maxbasic-function)
- [ApplicationLeft - MaxBasic Function](#applicationleft---maxbasic-function)
- [ApplicationMaximise - MaxBasic Function](#applicationmaximise---maxbasic-function)
- [ApplicationMinimise - MaxBasic Function](#applicationminimise---maxbasic-function)
- [ApplicationRefreshPrinters - MaxBasic Function](#applicationrefreshprinters---maxbasic-function)
- [ApplicationRestore - MaxBasic Function](#applicationrestore---maxbasic-function)
- [ApplicationSetting - MaxBasic Function](#applicationsetting---maxbasic-function)
- [ApplicationSettingBoolean - MaxBasic Function](#applicationsettingboolean---maxbasic-function)
- [ApplicationSettingDate - MaxBasic Function](#applicationsettingdate---maxbasic-function)
- [ApplicationSettingNumber - MaxBasic Function](#applicationsettingnumber---maxbasic-function)
- [ApplicationSettingString - MaxBasic Function](#applicationsettingstring---maxbasic-function)
- [ApplicationTop - MaxBasic Function](#applicationtop---maxbasic-function)
- [AppName - MaxBasic Function](#appname---maxbasic-function)
- [AppVersion - MaxBasic Function](#appversion---maxbasic-function)
- [ARAllocateTransactions - MaxBasic Function](#arallocatetransactions---maxbasic-function)
- [AREndOfPeriod - MaxBasic Function](#arendofperiod---maxbasic-function)
- [Asc - MaxBasic Function](#asc---maxbasic-function)
- [Base64DecodeBinary - MaxBasic Function](#base64decodebinary---maxbasic-function)
- [Base64DecodeString - MaxBasic Function](#base64decodestring---maxbasic-function)
- [Base64DecodeToFile - MaxBasic Function](#base64decodetofile---maxbasic-function)
- [Base64EncodeBinary - MaxBasic Function](#base64encodebinary---maxbasic-function)
- [Base64EncodeFile - MaxBasic Function](#base64encodefile---maxbasic-function)
- [Base64EncodeString - MaxBasic Function](#base64encodestring---maxbasic-function)
- [BeginTransaction - MaxBasic Function](#begintransaction---maxbasic-function)
- [BinName - MaxBasic Function](#binname---maxbasic-function)
- [BrowseDataset - MaxBasic Function](#browsedataset---maxbasic-function)
- [BudgetActivity - MaxBasic Function](#budgetactivity---maxbasic-function)
- [BudgetOpening - MaxBasic Function](#budgetopening---maxbasic-function)
- [BuildJSON - MaxBasic Function](#buildjson---maxbasic-function)
- [BuildJSONArray - MaxBasic Function](#buildjsonarray---maxbasic-function)
- [BusinessNo - MaxBasic Function](#businessno---maxbasic-function)
- [BusinessNoName - MaxBasic Function](#businessnoname---maxbasic-function)
- [CalcMarkup - MaxBasic Function](#calcmarkup---maxbasic-function)
- [CashInvoice - MaxBasic Function](#cashinvoice---maxbasic-function)
- [CBAutoPost - MaxBasic Function](#cbautopost---maxbasic-function)
- [CBEndOfPeriod - MaxBasic Function](#cbendofperiod---maxbasic-function)
- [ChargeName - MaxBasic Function](#chargename---maxbasic-function)
- [CheckPOPassword - MaxBasic Function](#checkpopassword---maxbasic-function)
- [CheckUserPassword - MaxBasic Function](#checkuserpassword---maxbasic-function)
- [ChequeNo - MaxBasic Function](#chequeno---maxbasic-function)
- [Chr - MaxBasic Function](#chr---maxbasic-function)
- [ClearLog - MaxBasic Function](#clearlog---maxbasic-function)
- [ClientName - MaxBasic Function](#clientname---maxbasic-function)
- [CloneQuery - MaxBasic Function](#clonequery---maxbasic-function)
- [ColorByName - MaxBasic Function](#colorbyname---maxbasic-function)
- [ColorRGB - MaxBasic Function](#colorrgb---maxbasic-function)
- [CommitTransaction - MaxBasic Function](#committransaction---maxbasic-function)
- [CompanyList - MaxBasic Function](#companylist---maxbasic-function)
- [ComparePropertyValues - MaxBasic Function](#comparepropertyvalues---maxbasic-function)
- [ComputerName - MaxBasic Function](#computername---maxbasic-function)
- [ConvertAscii - MaxBasic Function](#convertascii---maxbasic-function)
- [ConvertBaseToFX - MaxBasic Function](#convertbasetofx---maxbasic-function)
- [ConvertFXToBase - MaxBasic Function](#convertfxtobase---maxbasic-function)
- [CopyFieldsByName - MaxBasic Function](#copyfieldsbyname---maxbasic-function)
- [CopyFile - MaxBasic Function](#copyfile---maxbasic-function)
- [CopyFromClipboard - MaxBasic Function](#copyfromclipboard---maxbasic-function)
- [CopyInvoice - MaxBasic Function](#copyinvoice---maxbasic-function)
- [CopyNumber - MaxBasic Function](#copynumber---maxbasic-function)
- [CopyOrder - MaxBasic Function](#copyorder---maxbasic-function)
- [CopyToClipboard - MaxBasic Function](#copytoclipboard---maxbasic-function)
- [CostPriceDecimals - MaxBasic Function](#costpricedecimals---maxbasic-function)
- [CountryISOCode - MaxBasic Function](#countryisocode---maxbasic-function)
- [CountryName - MaxBasic Function](#countryname---maxbasic-function)
- [CreateCompany - MaxBasic Function](#createcompany---maxbasic-function)
- [CreateCustomForm - MaxBasic Function](#createcustomform---maxbasic-function)
- [CreateCustomTableEditor - MaxBasic Function](#createcustomtableeditor---maxbasic-function)
- [CreateCustomWindowForm - MaxBasic Function](#createcustomwindowform---maxbasic-function)
- [CreateJobAnalysisReport - MaxBasic Function](#createjobanalysisreport---maxbasic-function)
- [CreateLinkData - MaxBasic Function](#createlinkdata---maxbasic-function)
- [CreateLinkList - MaxBasic Function](#createlinklist---maxbasic-function)
- [CreateMemoData - MaxBasic Function](#creatememodata---maxbasic-function)
- [CreateMemoList - MaxBasic Function](#creatememolist---maxbasic-function)
- [CreateModuleMemoData - MaxBasic Function](#createmodulememodata---maxbasic-function)
- [CreateObject - MaxBasic Function](#createobject---maxbasic-function)
- [CreatePrintLog - MaxBasic Function](#createprintlog---maxbasic-function)
- [CreatePrintSingle - MaxBasic Function](#createprintsingle---maxbasic-function)
- [CreatePurchaseAnalysisReport - MaxBasic Function](#createpurchaseanalysisreport---maxbasic-function)
- [CreateReport - MaxBasic Function](#createreport---maxbasic-function)
- [CreateRuleList - MaxBasic Function](#createrulelist---maxbasic-function)
- [CreateSalesAnalysisReport - MaxBasic Function](#createsalesanalysisreport---maxbasic-function)
- [CreateSpecialPriceListReport - MaxBasic Function](#createspecialpricelistreport---maxbasic-function)
- [Creditor - MaxBasic Function](#creditor---maxbasic-function)
- [CrossTabCount - MaxBasic Function](#crosstabcount---maxbasic-function)
- [CurrencyOf - MaxBasic Function](#currencyof---maxbasic-function)
- [CurrentIteratorName - MaxBasic Function](#currentiteratorname---maxbasic-function)
- [CurrentPeriod - MaxBasic Function](#currentperiod---maxbasic-function)
- [Date - MaxBasic Function](#date---maxbasic-function)
- [DateAvailable - MaxBasic Function](#dateavailable---maxbasic-function)
- [DateValue - MaxBasic Function](#datevalue---maxbasic-function)
- [DateWithinPeriod - MaxBasic Function](#datewithinperiod---maxbasic-function)
- [Day - MaxBasic Function](#day---maxbasic-function)
- [DayOfWeek - MaxBasic Function](#dayofweek---maxbasic-function)
- [Debug - MaxBasic Function](#debug---maxbasic-function)
- [DefaultGSTCode - MaxBasic Function](#defaultgstcode---maxbasic-function)
- [DefaultReadOnlyColor - MaxBasic Function](#defaultreadonlycolor---maxbasic-function)
- [DeleteCompany - MaxBasic Function](#deletecompany---maxbasic-function)
- [DeleteFile - MaxBasic Function](#deletefile---maxbasic-function)
- [DequotedString- MaxBasic Function](#dequotedstring--maxbasic-function)
- [DesktopHeight - MaxBasic Function](#desktopheight---maxbasic-function)
- [DesktopWidth - MaxBasic Function](#desktopwidth---maxbasic-function)
- [DirectoryExists - MaxBasic Function](#directoryexists---maxbasic-function)
- [DisableUserAccessCheck - MaxBasic Function](#disableuseraccesscheck---maxbasic-function)
- [DocumentObject - MaxBasic Function](#documentobject---maxbasic-function)
- [DoEvents - MaxBasic Function](#doevents---maxbasic-function)
- [DropChars - MaxBasic Function](#dropchars---maxbasic-function)
- [Duplex - MaxBasic Function](#duplex---maxbasic-function)
- [EDIExport - MaxBasic Function](#ediexport---maxbasic-function)
- [EDIImport - MaxBasic Function](#ediimport---maxbasic-function)
- [EmailFilename - MaxBasic Function](#emailfilename---maxbasic-function)
- [EmailSubject - MaxBasic Function](#emailsubject---maxbasic-function)
- [EnableUserAccessCheck - MaxBasic Function](#enableuseraccesscheck---maxbasic-function)
- [EnsureRefreshToken - MaxBasic Function](#ensurerefreshtoken---maxbasic-function)
- [Eval - MaxBasic Function](#eval---maxbasic-function)
- [ExecuteSQL - MaxBasic Function](#executesql---maxbasic-function)
- [Exists - MaxBasic Function](#exists---maxbasic-function)
- [ExpandEnvironmentVariables - MaxBasic Function](#expandenvironmentvariables---maxbasic-function)
- [FAEndOfPeriod - MaxBasic Function](#faendofperiod---maxbasic-function)
- [FileExists - MaxBasic Function](#fileexists---maxbasic-function)
- [FindCode - MaxBasic Function](#findcode---maxbasic-function)
- [FirstAvailablePeriod - MaxBasic Function](#firstavailableperiod---maxbasic-function)
- [FirstInYear - MaxBasic Function](#firstinyear---maxbasic-function)
- [FirstPeriod - MaxBasic Function](#firstperiod---maxbasic-function)
- [FirstUserPeriod - MaxBasic Function](#firstuserperiod---maxbasic-function)
- [Fix - MaxBasic Function](#fix---maxbasic-function)
- [FormatBankAccountNo - MaxBasic Function](#formatbankaccountno---maxbasic-function)
- [FormatDateDifference - MaxBasic Function](#formatdatedifference---maxbasic-function)
- [FormatDateTime - MaxBasic Function](#formatdatetime---maxbasic-function)
- [FormatNumber - MaxBasic Function](#formatnumber---maxbasic-function)
- [FormatQuantity - MaxBasic Function](#formatquantity---maxbasic-function)
- [FormatTaxNo - MaxBasic Function](#formattaxno---maxbasic-function)
- [FormCapture - MaxBasic Function](#formcapture---maxbasic-function)
- [GenerateGUID - MaxBasic Function](#generateguid---maxbasic-function)
- [GenerateSchema - MaxBasic Function](#generateschema---maxbasic-function)
- [GetAccount - MaxBasic Function](#getaccount---maxbasic-function)
- [GetAccredoDefaultPrinter - MaxBasic Function](#getaccredodefaultprinter---maxbasic-function)
- [GetActiveEventName - MaxBasic Function](#getactiveeventname---maxbasic-function)
- [GetActiveFileName - MaxBasic Function](#getactivefilename---maxbasic-function)
- [GetActiveObject - MaxBasic Function](#getactiveobject---maxbasic-function)
- [GetBaseCurrency - MaxBasic Function](#getbasecurrency---maxbasic-function)
- [GetComponent - MaxBasic Function](#getcomponent---maxbasic-function)
- [GetConfigValue - MaxBasic Function](#getconfigvalue---maxbasic-function)
- [GetEnumText - MaxBasic Function](#getenumtext---maxbasic-function)
- [GetEnvironmentVariable - MaxBasic Function](#getenvironmentvariable---maxbasic-function)
- [GetExcelSheetNames - MaxBasic Function](#getexcelsheetnames---maxbasic-function)
- [GetExchangeRate - MaxBasic Function](#getexchangerate---maxbasic-function)
- [GetFieldNames - MaxBasic Function](#getfieldnames---maxbasic-function)
- [GetFieldValue - MaxBasic Function](#getfieldvalue---maxbasic-function)
- [GetGDIHandles - MaxBasic Function](#getgdihandles---maxbasic-function)
- [GetKernelHandles - MaxBasic Function](#getkernelhandles---maxbasic-function)
- [GetLicenseID - MaxBasic Function](#getlicenseid---maxbasic-function)
- [GetLicensesAvailable - MaxBasic Function](#getlicensesavailable---maxbasic-function)
- [GetLicensesCount - MaxBasic Function](#getlicensescount---maxbasic-function)
- [GetLog - MaxBasic Function](#getlog---maxbasic-function)
- [GetLoggedInUsers - MaxBasic Function](#getloggedinusers---maxbasic-function)
- [GetLowerRateLimit - MaxBasic Function](#getlowerratelimit---maxbasic-function)
- [GetNamedObject - MaxBasic Function](#getnamedobject---maxbasic-function)
- [GetPermUser - MaxBasic Function](#getpermuser---maxbasic-function)
- [GetPreference - MaxBasic Function](#getpreference---maxbasic-function)
- [GetPropertyValue - MaxBasic Function](#getpropertyvalue---maxbasic-function)
- [GetRef - MaxBasic Function](#getref---maxbasic-function)
- [GetScriptOutput - MaxBasic Function](#getscriptoutput---maxbasic-function)
- [GetSessionDesc - MaxBasic Function](#getsessiondesc---maxbasic-function)
- [GetStampUser - MaxBasic Function](#getstampuser---maxbasic-function)
- [GetTickCount - MaxBasic Function](#gettickcount---maxbasic-function)
- [GetTriggerMethod - MaxBasic Function](#gettriggermethod---maxbasic-function)
- [GetTriggerObject - MaxBasic Function](#gettriggerobject---maxbasic-function)
- [GetTypedObject - MaxBasic Function](#gettypedobject---maxbasic-function)
- [GetUpperRateLimit - MaxBasic Function](#getupperratelimit---maxbasic-function)
- [GetUserHandles - MaxBasic Function](#getuserhandles---maxbasic-function)
- [GetVarType - MaxBasic Function](#getvartype---maxbasic-function)
- [GLEndOfPeriod - MaxBasic Function](#glendofperiod---maxbasic-function)
- [GSTBasis - MaxBasic Function](#gstbasis---maxbasic-function)
- [GSTRate - MaxBasic Function](#gstrate---maxbasic-function)
- [GSTRegistered - MaxBasic Function](#gstregistered---maxbasic-function)
- [HasBudgetActivity - MaxBasic Function](#hasbudgetactivity---maxbasic-function)
- [HasBudgetOpening - MaxBasic Function](#hasbudgetopening---maxbasic-function)
- [HasPeriodActivity - MaxBasic Function](#hasperiodactivity---maxbasic-function)
- [HasPeriodBalance - MaxBasic Function](#hasperiodbalance---maxbasic-function)
- [HasPeriodBudget - MaxBasic Function](#hasperiodbudget---maxbasic-function)
- [HasPeriodOpening - MaxBasic Function](#hasperiodopening---maxbasic-function)
- [HasPeriodProjected - MaxBasic Function](#hasperiodprojected---maxbasic-function)
- [HasProjectedActivity - MaxBasic Function](#hasprojectedactivity---maxbasic-function)
- [HasProjectedOpening - MaxBasic Function](#hasprojectedopening---maxbasic-function)
- [HasYearBalance - MaxBasic Function](#hasyearbalance---maxbasic-function)
- [HasYearBudget - MaxBasic Function](#hasyearbudget---maxbasic-function)
- [HasYearProjected - MaxBasic Function](#hasyearprojected---maxbasic-function)
- [HMACSHA1String - MaxBasic Function](#hmacsha1string---maxbasic-function)
- [HTMLAvailable - MaxBasic Function](#htmlavailable---maxbasic-function)
- [HTMLEncode - MaxBasic Function](#htmlencode---maxbasic-function)
- [HTMLToText - MaxBasic Function](#htmltotext---maxbasic-function)
- [ICEndOfPeriod - MaxBasic Function](#icendofperiod---maxbasic-function)
- [IIf - MaxBasic Function](#iif---maxbasic-function)
- [ImportFile - MaxBasic Function](#importfile---maxbasic-function)
- [InputBinCode - MaxBasic Function](#inputbincode---maxbasic-function)
- [InputBoolean - MaxBasic Function](#inputboolean---maxbasic-function)
- [InputBox - MaxBasic Function](#inputbox---maxbasic-function)
- [InputCode - MaxBasic Function](#inputcode---maxbasic-function)
- [InputContact - MaxBasic Function](#inputcontact---maxbasic-function)
- [InputCountry - MaxBasic Function](#inputcountry---maxbasic-function)
- [InputCustomCode - MaxBasic Function](#inputcustomcode---maxbasic-function)
- [InputDate - MaxBasic Function](#inputdate---maxbasic-function)
- [InputDeliveryAddress - MaxBasic Function](#inputdeliveryaddress---maxbasic-function)
- [InputEnum - MaxBasic Function](#inputenum---maxbasic-function)
- [InputFileOpen - MaxBasic Function](#inputfileopen---maxbasic-function)
- [InputFileSave - MaxBasic Function](#inputfilesave---maxbasic-function)
- [InputFolder - MaxBasic Function](#inputfolder---maxbasic-function)
- [InputInteger - MaxBasic Function](#inputinteger---maxbasic-function)
- [InputList - MaxBasic Function](#inputlist---maxbasic-function)
- [InputMemo - MaxBasic Function](#inputmemo---maxbasic-function)
- [InputNumber - MaxBasic Function](#inputnumber---maxbasic-function)
- [InputPeriod - MaxBasic Function](#inputperiod---maxbasic-function)
- [InputPrinter - MaxBasic Function](#inputprinter---maxbasic-function)
- [InputQuery - MaxBasic Function](#inputquery---maxbasic-function)
- [InputTime - MaxBasic Function](#inputtime---maxbasic-function)
- [InStr - MaxBasic Function](#instr---maxbasic-function)
- [InstrRev - MaxBasic Function](#instrrev---maxbasic-function)
- [Int - MaxBasic Function](#int---maxbasic-function)
- [IsArray - MaxBasic Function](#isarray---maxbasic-function)
- [IsBatch - MaxBasic Function](#isbatch---maxbasic-function)
- [IsBoolean - MaxBasic Function](#isboolean---maxbasic-function)
- [IsCompanyLocked - MaxBasic Function](#iscompanylocked---maxbasic-function)
- [IsCurrency - MaxBasic Function](#iscurrency---maxbasic-function)
- [IsDate - MaxBasic Function](#isdate---maxbasic-function)
- [IsEmpty - MaxBasic Function](#isempty---maxbasic-function)
- [IsInteractive - MaxBasic Function](#isinteractive---maxbasic-function)
- [IsNull - MaxBasic Function](#isnull---maxbasic-function)
- [IsNumber - MaxBasic Function](#isnumber---maxbasic-function)
- [IsObject - MaxBasic Function](#isobject---maxbasic-function)
- [IsString - MaxBasic Function](#isstring---maxbasic-function)
- [IsWebService - MaxBasic Function](#iswebservice---maxbasic-function)
- [JCEndOfPeriod - MaxBasic Function](#jcendofperiod---maxbasic-function)
- [Join - MaxBasic Function](#join---maxbasic-function)
- [JoinTransaction - MaxBasic Function](#jointransaction---maxbasic-function)
- [JSONClone - MaxBasic Function](#jsonclone---maxbasic-function)
- [JSONCreateArray - MaxBasic Function](#jsoncreatearray---maxbasic-function)
- [JSONCreateObject - MaxBasic Function](#jsoncreateobject---maxbasic-function)
- [JSONDelete - MaxBasic Function](#jsondelete---maxbasic-function)
- [JSONGetKeys - MaxBasic function](#jsongetkeys---maxbasic-function)
- [JSONLength - MaxBasic Function](#jsonlength---maxbasic-function)
- [JSONPop - MaxBasic Function](#jsonpop---maxbasic-function)
- [JSONPush - MaxBasic Function](#jsonpush---maxbasic-function)
- [JSONSetPropertyValue - MaxBasic Function](#jsonsetpropertyvalue---maxbasic-function)
- [JSONShift - MaxBasic Function](#jsonshift---maxbasic-function)
- [JSONSplice - MaxBasic Function](#jsonsplice---maxbasic-function)
- [JSONStringify - MaxBasic Function](#jsonstringify---maxbasic-function)
- [JSONToString - MaxBasic Function](#jsontostring---maxbasic-function)
- [JSONUnshift - MaxBasic Function](#jsonunshift---maxbasic-function)
- [KeepChars - MaxBasic Function](#keepchars---maxbasic-function)
- [LabelCopies - MaxBasic Function](#labelcopies---maxbasic-function)
- [LastAvailablePeriod - MaxBasic Function](#lastavailableperiod---maxbasic-function)
- [LastInYear - MaxBasic Function](#lastinyear---maxbasic-function)
- [LastPage - MaxBasic Function](#lastpage---maxbasic-function)
- [LastPeriod - MaxBasic Function](#lastperiod---maxbasic-function)
- [LastTaxDate - MaxBasic Function](#lasttaxdate---maxbasic-function)
- [LastUserPeriod - MaxBasic Function](#lastuserperiod---maxbasic-function)
- [LBound - MaxBasic Function](#lbound---maxbasic-function)
- [Left - MaxBasic Function](#left---maxbasic-function)
- [Len - MaxBasic Function](#len---maxbasic-function)
- [LineNumber - MaxBasic Function](#linenumber---maxbasic-function)
- [LineType - MaxBasic Function](#linetype---maxbasic-function)
- [LinkAccountFiles - MaxBasic function](#linkaccountfiles---maxbasic-function)
- [LoadConfig - MaxBasic Function](#loadconfig---maxbasic-function)
- [LocalDateTimeToUTC - MaxBasic Function](#localdatetimetoutc---maxbasic-function)
- [LockCompany - MaxBasic Function](#lockcompany---maxbasic-function)
- [LoggedIn - MaxBasic Function](#loggedin---maxbasic-function)
- [Login - MaxBasic Function](#login---maxbasic-function)
- [LoginPrompt - MaxBasic Function](#loginprompt---maxbasic-function)
- [LoginUserCode - MaxBasic Function](#loginusercode---maxbasic-function)
- [Logout - MaxBasic Function](#logout---maxbasic-function)
- [Lower - MaxBasic Function](#lower---maxbasic-function)
- [LPad - MaxBasic Function](#lpad---maxbasic-function)
- [LTrim - MaxBasic Function](#ltrim---maxbasic-function)
- [MakeCurrency - MaxBasic Function](#makecurrency---maxbasic-function)
- [MakeDate - MaxBasic Function](#makedate---maxbasic-function)
- [MakePeriodID - MaxBasic Function](#makeperiodid---maxbasic-function)
- [MakePhoneCall - MaxBasic Function](#makephonecall---maxbasic-function)
- [MakeTime - MaxBasic Function](#maketime---maxbasic-function)
- [MakeValidCode - MaxBasic Function](#makevalidcode---maxbasic-function)
- [Margin - MaxBasic Function](#margin---maxbasic-function)
- [Markup - MaxBasic Function](#markup---maxbasic-function)
- [MatchRegEx - MaxBasic Function](#matchregex---maxbasic-function)
- [Max - MaxBasic Function](#max---maxbasic-function)
- [MaxDate - MaxBasic Function](#maxdate---maxbasic-function)
- [MemoAccountFiles - MaxBasic function](#memoaccountfiles---maxbasic-function)
- [MemoryTotalAllocated - MaxBasic Function](#memorytotalallocated---maxbasic-function)
- [MemoryTotalCommitted - MaxBasic Function](#memorytotalcommitted---maxbasic-function)
- [MemoryTotalFree - MaxBasic Function](#memorytotalfree---maxbasic-function)
- [MemoryTotalMemory - MaxBasic Function](#memorytotalmemory---maxbasic-function)
- [MergePDFs - MaxBasic Function](#mergepdfs---maxbasic-function)
- [Mid - MaxBasic Function](#mid---maxbasic-function)
- [Min - MaxBasic Function](#min---maxbasic-function)
- [MinDate - MaxBasic Function](#mindate---maxbasic-function)
- [ModuleAvailable - MaxBasic Function](#moduleavailable---maxbasic-function)
- [Month - MaxBasic Function](#month---maxbasic-function)
- [MsgBox - MaxBasic Function](#msgbox---maxbasic-function)
- [NavigateURL - MaxBasic Function](#navigateurl---maxbasic-function)
- [NextTaxDate - MaxBasic Function](#nexttaxdate---maxbasic-function)
- [OAuth2TokenFromAuthCode - MaxBasic Function](#oauth2tokenfromauthcode---maxbasic-function)
- [OAuth2TokenFromAuthCodeEx - MaxBasic Function](#oauth2tokenfromauthcodeex---maxbasic-function)
- [OAuth2TokenFromRefreshToken - MaxBasic Function](#oauth2tokenfromrefreshtoken---maxbasic-function)
- [OAuth2TokenFromResourceOwner - MaxBasic Function](#oauth2tokenfromresourceowner---maxbasic-function)
- [ObjectProperties - MaxBasic Function](#objectproperties---maxbasic-function)
- [OpenCustomTable - MaxBasic Function](#opencustomtable---maxbasic-function)
- [OpenForm - MaxBasic Function](#openform---maxbasic-function)
- [OpenPDF - MaxBasic Function](#openpdf---maxbasic-function)
- [OpenSysTable - MaxBasic Function](#opensystable---maxbasic-function)
- [OpenTable - MaxBasic Function](#opentable---maxbasic-function)
- [OpenWindowForm - MaxBasic Function](#openwindowform---maxbasic-function)
- [OptimiseCompany - MaxBasic Function](#optimisecompany---maxbasic-function)
- [PackingSlip - MaxBasic Function](#packingslip---maxbasic-function)
- [PadAcctNo - MaxBasic Function](#padacctno---maxbasic-function)
- [PageHeight - MaxBasic Function](#pageheight---maxbasic-function)
- [PageNumber - MaxBasic Function](#pagenumber---maxbasic-function)
- [PageOfNumber - MaxBasic Function](#pageofnumber---maxbasic-function)
- [PageRemaining - MaxBasic Function](#pageremaining---maxbasic-function)
- [PageWidth - MaxBasic Function](#pagewidth---maxbasic-function)
- [ParseJSON - MaxBasic Function](#parsejson---maxbasic-function)
- [ParseJSONFromFile - MaxBasic Function](#parsejsonfromfile---maxbasic-function)
- [PartNumber - MaxBasic Function](#partnumber---maxbasic-function)
- [Percent - MaxBasic Function](#percent---maxbasic-function)
- [PercentEncode - MaxBasic Function](#percentencode---maxbasic-function)
- [Period - MaxBasic Function](#period---maxbasic-function)
- [PeriodActivity - MaxBasic Function](#periodactivity---maxbasic-function)
- [PeriodAvailable - MaxBasic Function](#periodavailable---maxbasic-function)
- [PeriodBalance - MaxBasic Function](#periodbalance---maxbasic-function)
- [PeriodBudget - MaxBasic Function](#periodbudget---maxbasic-function)
- [PeriodDifference - MaxBasic Function](#perioddifference---maxbasic-function)
- [PeriodEndDate - MaxBasic Function](#periodenddate---maxbasic-function)
- [PeriodForDate - MaxBasic Function](#periodfordate---maxbasic-function)
- [PeriodName - MaxBasic Function](#periodname---maxbasic-function)
- [PeriodOpening - MaxBasic Function](#periodopening---maxbasic-function)
- [PeriodPeriodNo - MaxBasic Function](#periodperiodno---maxbasic-function)
- [PeriodProjected - MaxBasic Function](#periodprojected---maxbasic-function)
- [PeriodStartDate - MaxBasic Function](#periodstartdate---maxbasic-function)
- [PeriodYearNo - MaxBasic Function](#periodyearno---maxbasic-function)
- [PivotTable - MaxBasic Function](#pivottable---maxbasic-function)
- [PlayScript - MaxBasic Function](#playscript---maxbasic-function)
- [PriceDecimals - MaxBasic Function](#pricedecimals---maxbasic-function)
- [PrinterList - MaxBasic Function](#printerlist---maxbasic-function)
- [PrinterName - MaxBasic Function](#printername---maxbasic-function)
- [ProcessLineType - MaxBasic Function](#processlinetype---maxbasic-function)
- [ProcessSave - MaxBasic Function](#processsave---maxbasic-function)
- [ProjectedActivity - MaxBasic Function](#projectedactivity---maxbasic-function)
- [ProjectedOpening - MaxBasic Function](#projectedopening---maxbasic-function)
- [Proper - MaxBasic Function](#proper---maxbasic-function)
- [QuantityDecimals - MaxBasic Function](#quantitydecimals---maxbasic-function)
- [QuotedString - MaxBasic Function](#quotedstring---maxbasic-function)
- [Ratio - MaxBasic Function](#ratio---maxbasic-function)
- [RecoverCompany - MaxBasic Function](#recovercompany---maxbasic-function)
- [RenameFile - MaxBasic Function](#renamefile---maxbasic-function)
- [Replace - MaxBasic Function](#replace---maxbasic-function)
- [ReplaceEnvironmentVariables - MaxBasic Function](#replaceenvironmentvariables---maxbasic-function)
- [ReplaceQuery - MaxBasic Function](#replacequery---maxbasic-function)
- [ReplaceRegEx - MaxBasic Function](#replaceregex---maxbasic-function)
- [ReportDate - MaxBasic Function](#reportdate---maxbasic-function)
- [ReportDestination - MaxBasic Function](#reportdestination---maxbasic-function)
- [ReportFileName - MaxBasic Function](#reportfilename---maxbasic-function)
- [ReportPreview - MaxBasic Function](#reportpreview---maxbasic-function)
- [ReportTitle - MaxBasic Function](#reporttitle---maxbasic-function)
- [RestartIterators - MaxBasic Function](#restartiterators---maxbasic-function)
- [ReturnForDate - MaxBasic Function](#returnfordate---maxbasic-function)
- [RevalueAPForeignBalances - MaxBasic Function](#revalueapforeignbalances---maxbasic-function)
- [RevalueARForeignBalances - MaxBasic Function](#revaluearforeignbalances---maxbasic-function)
- [RevalueCBForeignBalances - MaxBasic Function](#revaluecbforeignbalances---maxbasic-function)
- [RevalueICStockOnHand - MaxBasic Function](#revalueicstockonhand---maxbasic-function)
- [RevalueICToGL - MaxBasic Function](#revalueictogl---maxbasic-function)
- [Right - MaxBasic Function](#right---maxbasic-function)
- [Rnd - MaxBasic Function](#rnd---maxbasic-function)
- [RollbackTransaction - MaxBasic Function](#rollbacktransaction---maxbasic-function)
- [Round - MaxBasic Function](#round---maxbasic-function)
- [RoundDown - MaxBasic Function](#rounddown---maxbasic-function)
- [RoundUp - MaxBasic Function](#roundup---maxbasic-function)
- [RPad - MaxBasic Function](#rpad---maxbasic-function)
- [RTrim - MaxBasic Function](#rtrim---maxbasic-function)
- [ScriptArgs - MaxBasic Function](#scriptargs---maxbasic-function)
- [SelectBin - MaxBasic Function](#selectbin---maxbasic-function)
- [SellPriceDecimals - MaxBasic Function](#sellpricedecimals---maxbasic-function)
- [SendKeys - MaxBasic Function](#sendkeys---maxbasic-function)
- [SerialNo - MaxBasic Function](#serialno---maxbasic-function)
- [SessionCode - MaxBasic Function](#sessioncode---maxbasic-function)
- [SetAccredoDefaultPrinter - MaxBasic Function](#setaccredodefaultprinter---maxbasic-function)
- [SetConfigValue - MaxBasic Function](#setconfigvalue---maxbasic-function)
- [SetDuplex - MaxBasic Function](#setduplex---maxbasic-function)
- [SetEnvironmentVariable - MaxBasic Function](#setenvironmentvariable---maxbasic-function)
- [SetExchangeRate - MaxBasic Function](#setexchangerate---maxbasic-function)
- [SetPermUser - MaxBasic Function](#setpermuser---maxbasic-function)
- [SetPreference - MaxBasic Function](#setpreference---maxbasic-function)
- [SetRateLimits - MaxBasic Function](#setratelimits---maxbasic-function)
- [SetScriptReportResult - MaxBasic Function](#setscriptreportresult---maxbasic-function)
- [SetSessionDesc - MaxBasic Function](#setsessiondesc---maxbasic-function)
- [SetStampUser - MaxBasic Function](#setstampuser---maxbasic-function)
- [SetSystemDate - MaxBasic Function](#setsystemdate---maxbasic-function)
- [SetSystemPeriod - MaxBasic Function](#setsystemperiod---maxbasic-function)
- [Sgn - MaxBasic Function](#sgn---maxbasic-function)
- [Shell - MaxBasic Function](#shell---maxbasic-function)
- [ShowAlarms - MaxBasic Function](#showalarms---maxbasic-function)
- [ShowSQLProgress - MaxBasic Function](#showsqlprogress---maxbasic-function)
- [Sleep - MaxBasic Function](#sleep---maxbasic-function)
- [Split - MaxBasic Function](#split---maxbasic-function)
- [StampHash - MaxBasic Function](#stamphash---maxbasic-function)
- [StatementDate - MaxBasic Function](#statementdate---maxbasic-function)
- [StatementPeriod - MaxBasic Function](#statementperiod---maxbasic-function)
- [Str - MaxBasic Function](#str---maxbasic-function)
- [SubtractGST - MaxBasic Function](#subtractgst---maxbasic-function)
- [Sum - MaxBasic Function](#sum---maxbasic-function)
- [SystemAnyPresent - MaxBasic Function](#systemanypresent---maxbasic-function)
- [SystemDate - MaxBasic Function](#systemdate---maxbasic-function)
- [SystemLogin - MaxBasic Function](#systemlogin---maxbasic-function)
- [SystemLoginUserCode - MaxBasic Function](#systemloginusercode---maxbasic-function)
- [SystemLogout - MaxBasic Function](#systemlogout---maxbasic-function)
- [SystemPeriod - MaxBasic Function](#systemperiod---maxbasic-function)
- [SystemSetting - MaxBasic Function](#systemsetting---maxbasic-function)
- [SystemUserPermission - MaxBasic Function](#systemuserpermission---maxbasic-function)
- [TaxName - MaxBasic Function](#taxname---maxbasic-function)
- [TaxNo - MaxBasic Function](#taxno---maxbasic-function)
- [TaxNoName - MaxBasic Function](#taxnoname---maxbasic-function)
- [TempFileName - MaxBasic Function](#tempfilename---maxbasic-function)
- [TerminalServer - MaxBasic Function](#terminalserver---maxbasic-function)
- [TermsDate - MaxBasic Function](#termsdate---maxbasic-function)
- [Time - MaxBasic Function](#time---maxbasic-function)
- [TimeValue - MaxBasic Function](#timevalue---maxbasic-function)
- [TimeZoneOffset - MaxBasic Function](#timezoneoffset---maxbasic-function)
- [TransferAPToGL - MaxBasic Function](#transferaptogl---maxbasic-function)
- [TransferARToGL - MaxBasic Function](#transferartogl---maxbasic-function)
- [TransferCBToGL - MaxBasic Function](#transfercbtogl---maxbasic-function)
- [TransferFAToGL - MaxBasic Function](#transferfatogl---maxbasic-function)
- [TransferGSTToGL - MaxBasic Function](#transfergsttogl---maxbasic-function)
- [TransferICToGL - MaxBasic Function](#transferictogl---maxbasic-function)
- [TransferJCToGL - MaxBasic Function](#transferjctogl---maxbasic-function)
- [TransformPhoneNo - MaxBasic Function](#transformphoneno---maxbasic-function)
- [Trim - MaxBasic Function](#trim---maxbasic-function)
- [TryInteractive - MaxBasic Function](#tryinteractive---maxbasic-function)
- [UBound - MaxBasic Function](#ubound---maxbasic-function)
- [UnlockCompany - MaxBasic Function](#unlockcompany---maxbasic-function)
- [UnpostedBatches - MaxBasic Function](#unpostedbatches---maxbasic-function)
- [UntransferredBatches - MaxBasic Function](#untransferredbatches---maxbasic-function)
- [UnZipFiles - MaxBasic Function](#unzipfiles---maxbasic-function)
- [UOMActive - MaxBasic Function](#uomactive---maxbasic-function)
- [UpgradeTable - MaxBasic Function](#upgradetable---maxbasic-function)
- [Upper - MaxBasic Function](#upper---maxbasic-function)
- [URLEncode - MaxBasic Function](#urlencode---maxbasic-function)
- [UserPermission - MaxBasic Function](#userpermission---maxbasic-function)
- [UserSetting - MaxBasic Function](#usersetting---maxbasic-function)
- [UseWindowsDefaultPrinter - MaxBasic Function](#usewindowsdefaultprinter---maxbasic-function)
- [UTCDateTimeToLocal - MaxBasic Function](#utcdatetimetolocal---maxbasic-function)
- [Val - MaxBasic Function](#val---maxbasic-function)
- [ValidateLedger - MaxBasic Function](#validateledger---maxbasic-function)
- [ValidBankAccountNo - MaxBasic Function](#validbankaccountno---maxbasic-function)
- [ValidCode - MaxBasic Function](#validcode---maxbasic-function)
- [ValidEmailAddress - MaxBasic Function](#validemailaddress---maxbasic-function)
- [ValidFileName - MaxBasic Function](#validfilename---maxbasic-function)
- [ValidTaxNo - MaxBasic Function](#validtaxno---maxbasic-function)
- [VariancePercent - MaxBasic Function](#variancepercent---maxbasic-function)
- [ViewPDF - MaxBasic Function](#viewpdf---maxbasic-function)
- [ViewWindowPDF - MaxBasic Function](#viewwindowpdf---maxbasic-function)
- [WaitCursor - MaxBasic Function](#waitcursor---maxbasic-function)
- [WeekNo - MaxBasic Function](#weekno---maxbasic-function)
- [WindowsUserName - MaxBasic Function](#windowsusername---maxbasic-function)
- [WordAmount - MaxBasic Function](#wordamount---maxbasic-function)
- [WordLookup - MaxBasic Function](#wordlookup---maxbasic-function)
- [Year - MaxBasic Function](#year---maxbasic-function)
- [YearBalance - MaxBasic Function](#yearbalance---maxbasic-function)
- [YearBudget - MaxBasic Function](#yearbudget---maxbasic-function)
- [YearName - MaxBasic Function](#yearname---maxbasic-function)
- [YearProjected - MaxBasic Function](#yearprojected---maxbasic-function)
- [ZipFiles - MaxBasic Function](#zipfiles---maxbasic-function)

---

## Abort - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AbortFunction.htm

Abort - MaxBasic Function
Abort[(Message: String, Silent: Boolean)]
Terminates executing code immediately, displaying an optional Message parameter in a dialog box. If no message is supplied the generic 'XXXX aborted' message will appear. Abort can optionally terminate silently (without a prompt) by passing the optional Silent parameter as True, default is False.
Abort function syntax has these named arguments:
Parameter
Description
Message
Optional. Message to be displayed.
Silent
Optional. When
True,
no message is displayed. Defaults to
False
.
See Also
Report Functions

---

## Abs - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AbsFunction.htm

Abs - MaxBasic Function
Abs(Number: Number): Number
Returns the absolute numeric value of a number.
Abs function syntax has these named arguments:
Parameter
Description
Number
Required. The number to be evaluated.
See Also
Number Functions

---

## AddCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddCompanyFunction.htm

AddCompany - MaxBasic Function
AddCompany(CompanyCode: String, CompanyName: String; DataPath: String): Boolean
Add entry to Company List, does not add data files.
Returns
True
if an existing company is successfully added, otherwise returns
False
.
AddCompany function syntax has these named arguments:
Parameter
Description
Company Code
Required. The Code for the company. Must be a valid unique code.
Company Name
Required. The name of the company.
Data Path
Required. The company data path.

---

## AddFileLink - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddFileLinkFunction.htm

AddFileLink - MaxBasic Function
AddFileLink(Account File: String, Account Code: String, File Path: String[, File Source: String, Reference: String, Comment: String, Category 1: String,Category 2: String]): Number
Adds a file link, returning LinkID.
AddFileLink function syntax has these named arguments:
Parameter
Description
Account File
Required. The file type to create the link for.
Account Code
Required. The value used to create the link. A unique code or ID.
File Path
Required. Must be a relative path rooted in the Links directory or use empty string or filename only to default from the Link Path for the Account File if specified in Setup > [Module] > Settings > Links tab.
File Source
Optional. File to copy and name as specified in the File path. If not specified file is assumed to exist in the file path and link will be created.
Reference
Optional. Reference for the added link.
Comment
Optional. Comment for the added link.
Category 1
Optional. Link Category 1 for the added link.
Category 2
Optional. Link Category 2 for the added link.
Example code:
const SourceFile = "c:\data\AccredoSaturn\TestHelpLinks.csv"
const FilePath = "\AR\ASHENG\MyLinkedFile.csv"
Dim LinkID as Number
LinkID = AddFileLink("ARCUST", "ASHENG", FilePath, SourceFile)
Msgbox("LinkID: " & LinkID)
or
AddFileLink("ARCUST", "BOWEN", "Renamed.txt", "c:\data\Saturn600\TestHelpLinks.csv")
will copy c:\data\saturn600\TestHelpLinks.csv to the links folder, and link path if one is specified for ARCUST in
AR Settings > Links
, and rename the file to "Renamed.txt" before adding it as a link against customer BOWEN.
See Also
Objects Functions

---

## AddGST - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddGSTFunction.htm

AddGST - MaxBasic Function
AddGST(Amount: Number[, Code: String, EffectiveDate: Date]): Number
Add GST to Amount. GST at the rate applicable to Code and EffectiveDate
is added to Amount. If Code is not entered, the rate for the default GST code is used. If EffectiveDate is not specified, the current
accounting System Date
date is used.
AddGST function syntax has these named arguments:
Parameter
Description
Amount
Required. The amount to add GST to.
Code
Optional. The GST Code to be used.
Effective Date
Optional. The effective date to apply GST at.
See Also
GST Functions

---

## AddMonths - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddMonthsFunction.htm

AddMonths - MaxBasic Function
AddMonths(Date: Date, Months: Number[, ForceDay as Number]): Date
AddMonths adds the number of Months specified to Date. If ForceDay is not specified the result will be the date in the new month closest to the original day specified. If ForceDay is specified the results will be a date in the new month closest to ForceDay.
AddMonths function syntax has these named arguments:
Parameter
Description
Date
Required. Date to add the months to.
Months
Required. Number of months to add to the Date.
Force Day
Optional. Select the day value for the return date. If not entered, the result will be a date in the new month closest to the day specified in Date.
See Also
Date Functions

---

## AddNewYear - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddNewYearFunction.htm

AddNewYear - MaxBasic Function
AddNewYear([YearName: String [,PeriodStyle: String [, PlusAdjustment: Boolean [, InitialStatus: String [, StartDate: Date [, EndDate: Date , [NumPeriods: Number]]]]]]])
Add a new year of periods.
AddNewYear function syntax has these named arguments:
Parameter
Description
YearName
Optional. Name for the added year. Defaults to "Year ending MMM YYYY".
PeriodStyle
Optional. Period style for the added year. Defaults to the Period Style in Company Settings.
PeriodStyle parameter can be one of the following:
"1"
12 Month
"2"
4/4/5 Week
"3"
4/5/4 Week
"4"
5/4/4 Week
"5"
52 Week
"6"
13 Period
"7"
Custom
"8"
Single Period
"9"
2 Period
"A"
6 Period
PlusAdjustment
Optional. Defaults to the Period Style in Company Settings.
InitialStatus
Optional.
"O"
Open (default)
"C"
Closed
StartDate
Optional. Will only be used by the function if it is a new company i.e no existing periods.
EndDate
Optional. Will only be used if PeriodStyle is Custom.
NumPeriods
Optional. Will only be used if PeriodStyle is Custom.
Usage:
AddNewYear("YearEnding Custom", "1", True, "O")
or
AddNewYear

---

## AddPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddPeriodFunction.htm

AddPeriod - MaxBasic Function
AddPeriod(PeriodID: Number, Offset: Number, [Financial: Boolean]): Number
Adds Offset to PeriodID. Offset can be either positive or negative.
The optional boolean parameter Financial is
True
by default, and restricts periods considered to Financial Periods only (excludes Adjustment periods). If specified as
False
then all periods including Adjustment periods are considered.
AddPeriod function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to be added to.
Offset
Required. Offset to be added to Period ID.
Financial
Optional. If
True
, only financial periods are considered. If
False,
all periods including adjustment periods are considered.
See also the SQL
AddPeriod
function, and the Web Services
AddPeriod
function.
See Also
Period Functions

---

## AddressType - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddressTypeFunction.htm

AddressType - MaxBasic Function
AddressType: String
Returns the AddressType selected in the report selections, or if none is available, returns an empty string.
See Also
Report Functions

---

## AddWebLink - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AddWebLinkFunction.htm

AddWebLink - MaxBasic Function
AddWebLink(Account File: String, Account Code: String, URL: String[, Reference: String, Comment: String, Category 1: String,Category 2: String]): Number
Adds a weblink, returning LinkID.
AddWebLink function syntax has these named arguments:
Parameter
Description
Account File
Required. The file type to create the link for.
Account Code
Required. The value used to create the link. A unique code or ID.
URL
Required. URL to link.
Reference
Optional. Reference for the added link.
Comment
Optional. Comment for the added link.
Category 1
Optional. Link Category 1 for the added link.
Category 2
Optional. Link Category 2 for the added link.
Example code:
const Url = "www.accredo.co.nz"
Dim LinkID as Number
LinkID = AddWebLink("ARCUST", "ASHENG", Url)
Msgbox("LinkID: " & LinkID)
See Also
Objects Functions

---

## AllowInteractive - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AllowInteractiveFunction.htm

AllowInteractive - MaxBasic Function
AllowInteractive(Allow: Boolean): Boolean
Allow Interactive function attempts to set IsInteractive to
True
or
False
as provided in the Allow Boolean. If successful, returns the previous value of IsInteractive, otherwise invokes an error.
See
Company IsInteractive Setting
.

---

## AllowManualNumbering - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AllowManualNumberingFunction.htm

AllowManualNumbering - MaxBasic Function
AllowManualNumbering(Boolean: Boolean)
Controls manual numbering of Invoices.
AllowManualNumbering function syntax has these named arguments:
Parameter
Description
Boolean
Required. When
True
, Invoices can be manually numbered. When
False
, Invoices are automatically numbered.
See Also
Import Functions

---

## AmountDecimals - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AmountDecimalsFunction.htm

AmountDecimals - MaxBasic Function
AmountDecimals: Number
Returns the number of decimal places used to display all financial values and totals in base currency.
See Also
Number Functions

---

## APAllocateTransactions - MaxBasic Function

Source: https://accredo.co.nz/webhelp/APAllocateTransactionsFunction.htm

APAllocateTransactions - MaxBasic Function
APAllocateTransactions(CreditTransactionID: Number, DebitTransactionID: Number, AllocationAmount: Number[, AllocationDate: Date[, DiscountAmount]): Number
Attempts to allocate a pair of transactions and returns the resulting AllocationID. Usual validation occurs and function errors if allocation was not successful.
APAllocateTransactions function syntax has these named arguments:
Parameter
Description
CreditTransactionID
Required. APTransactionID with Unallocated Credit Amount.
DebitTransactionID
Required. APTransactionID with Unallocated Debit Amount.
AllocationAmount
Required. Amount to be allocated.
AllocationDate
Optional. Date for allocation. If  not specified the date of the later transaction is used.
DiscountAmount
Optional. Discount amount to be allocated.
APAllocateTransactions function returns:
Return Type
Description
Number
APAllocationID if successful.
See Also
Accounting Functions

---

## APEndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/APEndOfPeriodFunction.htm

APEndOfPeriod - MaxBasic Function
APEndOfPeriod: Boolean
Performs an End Of Period on AP
APEndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## AppBits - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AppBitsFunction.htm

AppBits - MaxBasic Function
Appbits: Number
App Bits function returns
32
if a 32-bit version of Accredo is running, or
64
if a 64-bit version of Accredo is running.
See Also
Application Functions

---

## AppendPDFs - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AppendPDFsFunction.htm

AppendPDFs - MaxBasic Function
AppendPDFs(File1: String, File2: String[, File3: String, ...]): String - OR -
AppendPDFs(FileStringList: StringList): String
AppendPDFs function appends Accredo generated PDF files to the first file listed, in the order they are listed, and saves the file with the name of File1. Subsequent appended files are not deleted. If no directory is supplied, the system path will be used as the directory.
Returns the name of the consolidated file.
AppendPDFs function syntax has these named arguments:
Parameter
Description
File1
Required. The name of the file that will be appended to.
File2
Required. The name of the first file to be appended.
File3 to File n
Optional. The names of additional files to be appended.
- OR -
Parameter
Description
File String List
Required. A
Stringlist Object
containing the names of the files to be appended.
See Also
Script Functions

---

## ApplicationLeft - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationLeftFunction.htm

ApplicationLeft - MaxBasic Function
ApplicationLeft: Number
ApplicationLeft function returns the left coordinate of the Accredo Main Window.
See Also
Application Functions

---

## ApplicationMaximise - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationMaximiseFunction.htm

ApplicationMaximise - MaxBasic Function
ApplicationMaximise: Boolean
Maximises the application and returns
True
if the application is successfully maximised.
See Also
Application Functions

---

## ApplicationMinimise - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationMinimiseFunction.htm

ApplicationMinimise - MaxBasic Function
ApplicationMinimise: Boolean
Minimises the application and returns
True
if the application is successfully minimised.
See Also
Application Functions

---

## ApplicationRefreshPrinters - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationRefreshPrintersFunction.htm

ApplicationRefreshPrinters - MaxBasic Function
ApplicationRefreshPrinters: Boolean
Sets a flag to refresh the printer list the next time it is used, returns
True
if successful.
See Also
Application Functions

---

## ApplicationRestore - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationRestoreFunction.htm

ApplicationRestore - MaxBasic Function
ApplicationRestore: Boolean
Restores the application to its original state and returns
True
if the application is successfully stored.
See Also
Application Functions

---

## ApplicationSetting - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingFunction.htm

ApplicationSetting - MaxBasic Function
ApplicationSetting(SettingName: String): Variant
Application Settings function reads and returns an
application setting
value as a variant. Use to select an application setting such as "IC\ValuationBasis" in a script.
ApplicationSetting function syntax has these named arguments:
Parameter
Description
Setting Name
Required. Name of the
Application Setting
.
In This Section
Application Settings Documentation
See Also
Application Functions

---

## ApplicationSettingBoolean - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingBooleanFunction.htm

ApplicationSettingBoolean - MaxBasic Function
ApplicationSettingBoolean(SettingName: String): Boolean
Application Setting Boolean function reads and returns a boolean
application setting
value as a boolean.
ApplicationSettingBoolean function syntax has these named arguments:
Parameter
Description
Setting Name
Required. Name of the boolean
Application Setting
.
See Also
Application Functions

---

## ApplicationSettingDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingDateFunction.htm

ApplicationSettingDate - MaxBasic Function
ApplicationSettingDate(SettingName: String): Date
Application Setting Date function reads and returns a date
application setting
value as a date.
ApplicationSettingDate function syntax has these named arguments:
Parameter
Description
Setting Name
Required. Name of the date
Application Setting
.
See Also
Application Functions

---

## ApplicationSettingNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingNumberFunction.htm

ApplicationSettingNumber - MaxBasic Function
ApplicationSettingNumber(SettingName: String): Number
Application Setting Number function reads and returns a numeric
application setting
value as a number.
ApplicationSettingNumber function syntax has these named arguments:
Parameter
Description
Setting Name
Required. Name of the numeric
Application Setting
.
See Also
Application Functions

---

## ApplicationSettingString - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingStringFunction.htm

ApplicationSettingString - MaxBasic Function
ApplicationSettingString(SettingName: String): String
Application Setting String function reads and returns a string
application setting
value as a string.
ApplicationSettingString function syntax has these named arguments:
Parameter
Description
Setting Name
Required. Name of the string
Application Setting
.
See Also
Application Functions

---

## ApplicationTop - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ApplicationTopFunction.htm

ApplicationTop - MaxBasic Function
ApplicationTop: Number
ApplicationTop function returns the top coordinate of the Accredo Main Window.
See Also
Application Functions

---

## AppName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AppNameFunction.htm

AppName - MaxBasic Function
AppName: String
App Name function returns the string
Mercury
or
Saturn
depending on the application the script is executed from for both Accredo Mercury and Accredo Saturn scripts.
See also the SQL
AppName
function and the Web Services
AppName
function.
See Also
Application Functions

---

## AppVersion - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AppVersionFunction.htm

AppVersion - MaxBasic Function
AppVersion[(ExtendedInfo: Boolean)]: String
App Version function returns the application version number. This can be used to test that a script is being used on a suitable version. Takes one optional boolean parameter. If
True
, it returns the extended version information string including .exe date, time and build flags.
AppVersion function syntax has these named arguments:
Parameter
Description
ExtendedInfo
Optional. If set to
True
, AppVersion returns extended version information. Defaults to
False
.
See Also
Application Functions

---

## ARAllocateTransactions - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ARAllocateTransactionsFunction.htm

ARAllocateTransactions - MaxBasic Function
ARAllocateTransactions(CreditTransactionID: Number, DebitTransactionID: Number, AllocationAmount: Number[, AllocationDate: Date[, DiscountAmount]): Number
Attempts to allocate a pair of transactions and returns the resulting AllocationID. Usual validation occurs and function errors if allocation was not successful.
ARAllocateTransactions function syntax has these named arguments:
Parameter
Description
CreditTransactionID
Required. ARTransactionID with Unallocated Credit Amount.
DebitTransactionID
Required. ARTransactionID with Unallocated Debit Amount.
AllocationAmount
Required. Amount to be allocated.
AllocationDate
Optional. Date for allocation. If  not specified the date of the later transaction is used.
DiscountAmount
Optional. Discount amount to be allocated.
ARAllocateTransactions function returns:
Return Type
Description
Number
ARAllocationID if successful.
See Also
Accounting Functions

---

## AREndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AREndOfPeriodFunction.htm

AREndOfPeriod - MaxBasic Function
AREndOfPeriod: Boolean
Performs an End Of Period on AR.
AREndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## Asc - MaxBasic Function

Source: https://accredo.co.nz/webhelp/AscFunction.htm

Asc - MaxBasic Function
Asc(String: String): Number
Returns a number representing the ASCII character code of the first character in string. If string is empty, a run-time error occurs.
See also the
ASCII Code table
.
Asc function syntax has these named arguments:
Parameter
Description
String
Required. String to return the ASCII code for the first character for.
For example:
Asc("abc")
Returns:
97
See Also
String Functions

---

## Base64DecodeBinary - MaxBasic Function

Source: https://accredo.co.nz/webhelp/Base64DecodeBinaryFunction.htm

Base64DecodeBinary - MaxBasic Function
Base64DecodeBinary(Base64EncodedString: String): String
Returns decoded binary string of a Base64 encoded string.
Base64DecodeString function has these named arguments:
Parameter
Description
EncodedText
Required. A Base64 encoded string, to be decoded.
Sample code:
Dim Source as String
Source = "0101010001101000011001010010000001110001011101010110100101100011011010110010000001100010011100100110111101110111011011100010000001100110011011110111100000100000011010100111010101101101011100000111001100100000011011110111011001100101011100100010000000110001001100110010000001101100011000010111101001111001001000000110010001101111011001110111001100101110"
Print "Binary Source:"
Print Source
Print ""
Dim Encoded as String
Print "Base64Encoded:"
Encoded = Base64EncodeBinary(Source)
Print Encoded
Print ""
Dim Decoded as String
Decoded = Base64DecodeBinary(Encoded)
Print "Base64Decoded:"
Print Decoded
Print ""
Dim PayLoad as String
Payload = Base64DecodeString(Encoded)
Print "Payload:"
Print Payload
Print ""
See Also
String Functions

---

## Base64DecodeString - MaxBasic Function

Source: https://accredo.co.nz/webhelp/Base64DecodeStringFunction.htm

Base64DecodeString - MaxBasic Function
Base64DecodeString(EncodedText: String): String
Given a Base64 encoded string EncodedText, returns its decoded version as a string.
Base64DecodeString function has these named arguments:
Parameter
Description
EncodedText
Required. A Base64 encoded string, to be decoded.
Sample code:
S = "Hello World"
Encoded = Base64EncodeString(S)
Decoded = Base64DecodeString(Encoded)
Print "Encoded:" & Encoded
Print "Decoded:" & Decoded
Returns:
Encoded:SGVsbG8gV29ybGQ=
Decoded:Hello World
See Also
String Functions

---

## Base64DecodeToFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/Base64DecodeToFileFunction.htm

Base64DecodeToFile - MaxBasic Function
Base64DecodeToFile(EncodedText: String, Filename:String): File
Decodes a given base 64 string to a binary file.
Base64DecodeToFile function has these named arguments:
Parameter
Description
EncodedText
Required. A Base64 encoded string, to be decoded.
Filename
Required. The output filename.
Sample code:
const InputFile = "c:\data\WordOutput.pdf"
const OutputFile = "c:\data\Output.pdf"
Dim Encoded as String
Encoded = Base64EncodeFile(InputFile)
Base64DecodeToFile(Encoded, OutputFile)
See Also
String Functions

---

## Base64EncodeBinary - MaxBasic Function

Source: https://accredo.co.nz/webhelp/Base64EncodeBinaryFunction.htm

Base64EncodeBinary - MaxBasic Function
Base64EncodeBinary(BinaryString: String): String
Returns Base64 encoded string version of a binary string.
Base64EncodeBinary function has these named arguments:
Parameter
Description
Binary String
Required. Text string to be encoded.
Sample code:
Dim Source as String
Source = "0101010001101000011001010010000001110001011101010110100101100011011010110010000001100010011100100110111101110111011011100010000001100110011011110111100000100000011010100111010101101101011100000111001100100000011011110111011001100101011100100010000000110001001100110010000001101100011000010111101001111001001000000110010001101111011001110111001100101110"
Print "Binary Source:"
Print Source
Print ""
Dim Encoded as String
Print "Base64Encoded:"
Encoded = Base64EncodeBinary(Source)
Print Encoded
Print ""
Dim Decoded as String
Decoded = Base64DecodeBinary(Encoded)
Print "Base64Decoded:"
Print Decoded
Print ""
Dim PayLoad as String
Payload = Base64DecodeString(Encoded)
Print "Payload:"
Print Payload
Print ""
See Also
String Functions

---

## Base64EncodeFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/Base64EncodeFileFunction.htm

Base64EncodeFile - MaxBasic Function
Base64EncodeFile(InputFileName: String): EncodedString
Returns Base64 encoded version of a file.
Base64EncodeFile function has these named arguments:
Parameter
Description
InputFileName
Required. File to be encoded.
Sample code:
const InputFile = "c:\data\WordOutput.pdf"
const OutputFile = "c:\data\Output.pdf"
Dim Encoded as String
Encoded = Base64EncodeFile(InputFile)
Base64DecodeToFile(Encoded, OutputFile)
See Also
String Functions

---

## Base64EncodeString - MaxBasic Function

Source: https://accredo.co.nz/webhelp/Base64EncodeStringFunction.htm

Base64EncodeString - MaxBasic Function
Base64EncodeString(Text: String): String
Returns Base64 encoded string version of the given Text.
Base64EncodeString function has these named arguments:
Parameter
Description
Text
Required. Text string to be encoded.
Sample code:
S = "Hello World"
Encoded = Base64EncodeString(S)
Decoded = Base64DecodeString(Encoded)
Print "Encoded:" & Encoded
Print "Decoded:" & Decoded
Returns:
Encoded:SGVsbG8gV29ybGQ=
Decoded:Hello World
See Also
String Functions

---

## BeginTransaction - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BeginTransactionFunction.htm

BeginTransaction - MaxBasic Function
BeginTransaction
Controls batch processing if a record fails inside a batch. The entire batch can be rolled back using
RollbackTransaction
.
CommitTransaction
saves the batch.
When a rollbacks is triggered by unhandled MaxBasic code, a Warning exception is logged in the system
Error Log
. Note that internal Accredo events can be rolled back, but external events such as printing and emailing cannot be rolled back.
For example:
BeginTransaction
Try
'Create and save transactions
CommitTransaction
Catch e
RollBackTransaction
End Try
See Also
Script Functions

---

## BinName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BinNameFunction.htm

BinName - MaxBasic Function
BinName: String
Returns the Bin Name if the report destination is "Printer", or returns an empty string otherwise.
See Also
Report Functions

---

## BrowseDataset - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BrowseDatasetFunction.htm

BrowseDataset - MaxBasic Function
BrowseDataset(ObjectName: String[, Title: String])
Opens the dataset ObjectName in the Dataset Browser, a modal dialog box, for browsing. You can print a report from the Dataset Browser.
If a Title is specified, it will be displayed in the Dataset Browser. The Line and Character position that BrowseDataset is called from in the code is displayed in the Dataset Browser footer.
BrowseDataset function syntax has these named arguments:
Parameter
Description
Object Name
Required. Object name of the dataset to browse.
Title
Options. Title to be displayed in the Dataset Browser.
For example:
Customer = ExecuteSQL("Select * from ARCust")
BrowseDataset(Customer, "AR Customers")
See Also
Script Functions

---

## BudgetActivity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BudgetActivityFunction.htm

BudgetActivity - MaxBasic Function
BudgetActivity([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String, Level: Number, ExcludeNull: Boolean])
Budget activity between the range of periods specified. Optionally can be passed additional parameters to calculate summed period activity over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
If any of the Branch, Department, Segment1, Segment2, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
Note:
Branch
and
Department
are only available in Accredo Saturn.
BudgetActivity function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## BudgetOpening - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BudgetOpeningFunction.htm

BudgetOpening - MaxBasic Function
BudgetOpening([BudgetCode: String,] PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Budget opening balance for period specified. Optionally can be passed additional parameters to calculate summed period opening balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the Branch, Department, Segment1, Segment2, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
BudgetOpening function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use.  If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## BuildJSON - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BuildJSONFunction.htm

BuildJSON - MaxBasic Function
BuildJSON(AccredoObject: Object [, IncludeProperties: String, ExcludeProperties: String]): Object
Returns a JSON object based on the AccredoObject, including properties in the IncludeProperties semi-colon separated string, and excluding properties in the ExcludeProperties semi-colon separated string.
BuildJSON function has these named arguments:
Parameter
Description
Accredo Object
Required. An Accredo Object to use as the base of the JSON object.
Include Properties
Optional. A semi-colon delimited string containing properties to be included.
Exclude Properties
Optional. A semi-colon delimited string containing properties to be excluded.
The following sample code creates a JSON Object based on the IN Invoice data, containing the Customer Code, Document No, Document ID, excluding the Charge and Banking sub-objects.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
See Also
Web Functions

---

## BuildJSONArray - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BuildJSONArrayFunction.htm

BuildJSONArray - MaxBasic Function
BuildJSONArray(MemoryTableObject: Object [, IncludeProperties: String, ExcludeProperties: String]): Object
Returns a JSON object based on the MemoryTableObject, including properties in the IncludeProperties semi-colon separated string, and excluding properties in the ExcludeProperties semi-colon separated string.
BuildJSONArray function has these named arguments:
Parameter
Description
Memory Table Object
Required. An Accredo Memory Table Object to use as the base of the JSON object.
Include Properties
Optional. A semi-colon delimited string containing properties to be included.
Exclude Properties
Optional. A semi-colon delimited string containing properties to be excluded.
The following sample code creates a JSON Object from a Memory Table.
Sample code:
Dim Table as Object
Table = ExecuteSQL("Select CustomerCode, CustomerName From ARCUST")
JSONArray = BuildJSONArray(Table)
Print JSONStringify(JSONArray)
See Also
Web Functions

---

## BusinessNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BusinessNoFunction.htm

BusinessNo - MaxBasic Function
BusinessNo[(TaxRegime: String)]: String
Business No function returns the Business No for a given Tax Regime. If no Tax Regime is given, the Business No for the Base Tax Regime is returned.
BusinessNo function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the Business No for. If not supplied, the Base Tax Regime is used.

---

## BusinessNoName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/BusinessNoNameFunction.htm

BusinessNoName - MaxBasic Function
BusinessNoName[(TaxRegime: String)]: String
Business No Name function returns the Business No Name for a given Tax Regime. If no Tax Regime is given, the Business No Name for the Base Tax Regime is returned.
BusinessNoName function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the Business No Name for. If not supplied, the Base Tax Regime is used.

---

## CalcMarkup - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CalcMarkupFunction.htm

CalcMarkup - MaxBasic Function
CalcMarkup(Number1: Number, Number2: Number): Number
Calculates markup percentage from Number1 to Number2.
CalcMarkup function syntax has these named arguments:
Parameter
Description
Number 1
Required. Number to calculate the markup percentage from.
Number 2
Required. Number to calculate the markup percentage to.
See Also
Number Functions

---

## CashInvoice - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CashInvoiceFunction.htm

CashInvoice - MaxBasic Function
CashInvoice: Boolean
Returns
True
if the currently printing Invoice document is processing as a Cash Sale Invoice, returns
False
otherwise.
Available in IN Invoice Document design script editors.
See Also
Report Functions

---

## CBAutoPost - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CBAutoPostFunction.htm

CBAutoPost - MaxBasic Function
CBAutoPost
Posts due automatic payments to the CB.
See Also
Accounting Functions

---

## CBEndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CBEndOfPeriodFunction.htm

CBEndOfPeriod - MaxBasic Function
CBEndOfPeriod :Boolean
Performs an End Of Period on CB.
CBEndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## ChargeName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ChargeNameFunction.htm

ChargeName - MaxBasic Function
ChargeName(ChargeCode: Character): String
Returns the Charge Name for the ChargeCode (1, 2, 3 or 4).
Available in OE Packing Slip and IN Invoice Document design script editors.
ChargeName function syntax has these named arguments:
Parameter
Description
Charge Code
Required. Charge Code to return the Charge Name for.
See Also
Report Functions

---

## CheckPOPassword - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CheckPOPasswordFunction.htm

CheckPOPassword - MaxBasic Function
CheckPOPassword(UserName: String, Password: String): Boolean
Checks the UserName can be found as a PO Author Code, and checks the Password matches the code. Returns
True
if User Name and Password match, otherwise returns
False
.
CheckPOPassword function syntax has these named arguments:
Parameter
Description
User Name
Required. User name to check.
Password
Required. Password to check.
See Also
User Functions

---

## CheckUserPassword - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CheckUserPasswordFunction.htm

CheckUserPassword - MaxBasic Function
CheckUserPassword(UserName: String, Password: String): Boolean
Checks the UserName can be found as a User Code, and checks the Password matches the code. Returns
True
if User Name and Password match, otherwise returns
False
.
CheckUserPassword function syntax has these named arguments:
Parameter
Description
User Name
Required. User name to check.
Password
Required. Password to check.
See Also
User Functions

---

## ChequeNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ChequeNoFunction.htm

ChequeNo - MaxBasic Function
ChequeNo: Variant
Cheque No function returns the cheque number assigned to the current AP cheque or remittance advice.
Available in AP Cheque/Remittance Document design script editor.
See Also
Environment Functions

---

## Chr - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ChrFunction.htm

Chr - MaxBasic Function
Chr(Number: Number): String
Returns a one character string containing the character whose character code is Number. Number must be in the range 0-255, or a run-time error will occur.
See also the
ASCII Code table
.
Chr function syntax has these named arguments:
Parameter
Description
Number
Required. The ASCII character code to return the character for.
For example:
Chr(97)
Returns:
a
See Also
String Functions

---

## ClearLog - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ClearLogFunction.htm

ClearLog - MaxBasic Function
ClearLog
Clears the current output log.
See Also
Import Functions

---

## ClientName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ClientNameFunction.htm

ClientName - MaxBasic Function
ClientName: String
Client Name function returns the WTSClientName if running in a Remote Desktop Session, or MachineName otherwise.
See Also
Environment Functions

---

## CloneQuery - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CloneQueryFunction.htm

CloneQuery - MaxBasic Function
CloneQuery: Variant
Returns a Read Only clone of the report query results that can be used for anything required without effecting the state of the reporting engine.
Available in Custom Report design script editors, not available in the BeforeReport code since query executes after the BeforeReport code.
For example:
Dim MyQuery as Object
MyQuery = CloneQuery
MyQuery.AddIndex("Transaction","TransactionID")
MyQuery.IndexName = "Transaction"
See Also
Report Functions

---

## ColorByName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ColorByNameFunction.htm

ColorByName - MaxBasic Function
ColorByName(ColorName: String)
Creates a
color
by its name.
ColorByName function syntax has these named arguments:
Parameter
Description
Color Name
Required. Name of the color to create.
See Also
Script Functions

---

## ColorRGB - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ColorRGBFunction.htm

ColorRGB - MaxBasic Function
ColorRGB(RedValue: Number, GreenValue: Number, BlueValue: Number)
Creates a
color
by its Red, Green and Blue values (0-255).
ColorRGB function syntax has these named arguments:
Parameter
Description
Red Value
Required. Red value.
Green Value
Required. Green value.
Blue Value
Required. Blue value.
See Also
Script Functions

---

## CommitTransaction - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CommitTransactionFunction.htm

CommitTransaction - MaxBasic Function
CommitTransaction
Commits a database transaction.
See also
BeginTransaction
and
RollbackTransaction
.
See Also
Script Functions

---

## CompanyList - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CompanyListFunction.htm

CompanyList - MaxBasic Function
CompanyList: Object
Returns an object that lists company names.
CompanyList object has the following methods:
Method
Description
CompanyBackupPath(Index: Number): String
Returns the company backup path.
CompanyCode(Index: Number): String
Returns the company code.
CompanyComLimit([Index: Number]): Number
Returns the company maximum COM users.
CompanyID([Index: Number]): Number
Returns the Company ID.
CompanyMaxPayees([Index: Number]): Number
Returns the company maximum Payroll payees.
CompanyName(Index: Number): String
Returns the company name.
CompanyPath(Index: Number): String
Returns the location of company files.
CompanyType(Index: Number): String
Returns the company type, either
Live
,
Test
or
Demo.
CompanyTypeDesc(Index: Number): String
Returns the company type description.
CompanyUserLimit([Index: Number]): Number
Returns the company maximum users.
CompanyWebLimit([Index: Number]): Number
Returns the company maximum web users.
For example:
Dim Companies as Object
Companies = CompanyList
documentObject(Companies)
For x = 0 to (Companies.Count - 1)
Print Companies.Item(x) & " " & Companies.CompanyID(x) & " " & Companies.CompanyCode(x)  & " " & Companies.CompanyName(x) _
& " " & Companies.CompanyType(x) & " " & Companies.CompanyTypeDesc(x) & " " & Companies.CompanyPath(x) _
& " " & Companies.CompanyBackupPath(x)  & " " & Companies.CompanyComLimit(x) & " " & Companies.CompanyUserLimit(x) _
& " " & Companies.CompanyWebLimit(x) & " " & Companies.CompanyMaxPayees(x)
Next x
See Also
Company Functions

---

## ComparePropertyValues - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ComparePropertyValuesFunction.htm

ComparePropertyValues - MaxBasic Function
ComparePropertyValues(DataObject1: Object, DataObject2: Object): Object
Compares two Data Objects with comparable properties, and returns a string list of the Property Names where the objects have differing values. The string list returned is sorted alphabetically.
ComparePropertyValues function syntax has these named arguments:
Parameter
Description
Data Object 1
Required. The first data object to be compared.
Data Object 2
Required. The data object to compare to Data Object 1. Must be the same class as Data Object 1.
For example:
Dim CompareVals as Object
CompareVals = ComparePropertyValues(datINInvoice1, datINInvoice2)
Print "Properties that are different"
For I = 0 to CompareVals.Count - 1
Print CompareVals[I]
Next I
See Also
Script Functions

---

## ComputerName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ComputerNameFunction.htm

ComputerName - MaxBasic Function
ComputerName: String
Computer Name function returns the name of the running computer as configured in Windows.
See Also
Environment Functions

---

## ConvertAscii - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ConvertAsciiFunction.htm

ConvertAscii - MaxBasic Function
ConvertAscii(UnicodeString: String [, CodePage: Number]) as String
Returns converted ASCII string version of the given Unicode string.
ConvertAscii function has these named arguments:
Parameter
Description
UnicodeString
Required. Unicode string to be converted.
CodePage
Optional. Default is 1252 (Ansi).
Sample code:
Dim unicode as String
Unicode = "Some unicode characters âÄªÄÌ - end of string"
Print "Unicode: " & Unicode
Print "Ascii: " & ConvertAscii(Unicode)

---

## ConvertBaseToFX - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ConvertBaseToFXFunction.htm

ConvertBaseToFX - MaxBasic Function
ConvertBaseToFX(BaseAmount: Number, ExchangeRate: Number, CurrencyCode: String): Number
Passed a Base Amount an Exchange Rate and a Currency Code, returns an FX Amount. Exchange Rate must be non zero.
ConvertBaseToFX function syntax has these named arguments:
Parameter
Description
Base Amount
Required. Base amount to be converted.
Exchange Rate
Required. Exchange rate used to convert the Base amount.
Currency Code
Required. Currency code to return the converted amount in.
See Also
Foreign Exchange Functions

---

## ConvertFXToBase - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ConvertFXToBaseFunction.htm

ConvertFXToBase - MaxBasic Function
ConvertFXToBase(FXAmount: Number, ExchangeRate: Number): Number
Passed an FX Amount and an Exchange Rate, returns a Base Amount. Exchange Rate must be non zero.
ConvertFXToBase function syntax has these named arguments:
Parameter
Description
FX Amount
Required. FX amount to be converted.
Exchange Rate
Required. Exchange rate used to convert the Base amount.
See Also
Foreign Exchange Functions

---

## CopyFieldsByName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyFieldsByNameFunction.htm

CopyFieldsByName - MaxBasic Function
CopyFieldsByName(SourceTable: Object, DestinationTable: Object)
Copies table fields from SourceTable to DestinationTable, matched by field name. The type and size of fields in the SourceTable and DestinationTable must be the same.
CopyFieldsByName function syntax has these named arguments:
Parameter
Description
Source Table
Required. The table to copy table fields from.
Destination Table
Required. The table to copy table fields to.
See Also
Script Functions

---

## CopyFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyFileFunction.htm

CopyFile - MaxBasic Function
CopyFile(SourceFileName: String, DestinationFileName: String[, Overwrite: Boolean]): Boolean
Copy File function copy the file specified in Source File Name to the file specified in Destination File Name, optionally over writing if destination file already exists.
CopyFile function syntax has these named arguments:
Parameter
Description
Source File Name
Required. The name of the file to be copied from.
Destination File Name
Required. The name of the file to be copied to.
Overwrite
Optional. Overwrite Destination file if it already exists. Default False if not specified.
See Also
Environment Functions

---

## CopyFromClipboard - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyFromClipboardFunction.htm

CopyFromClipboard - MaxBasic Function
CopyFromClipboard: String
Copy From Clipboard function copies the contents of the Windows Clipboard as a string. If the Windows Clipboard contents cannot be converted to text, an empty string is returned.
See Also
Environment Functions

---

## CopyInvoice - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyInvoiceFunction.htm

CopyInvoice - MaxBasic Function
CopyInvoice: Boolean
Returns
True
if the Print as Copy selection box has been checked for the currently printing Invoice, returns
False
otherwise.
Available in IN Invoice Document design script editors.
See Also
Report Functions

---

## CopyNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyNumberFunction.htm

CopyNumber - MaxBasic Function
CopyNumber: Number
Returns the current label copy number.
Available in [Module] Label Designer.
See Also
Report Functions

---

## CopyOrder - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyOrderFunction.htm

CopyOrder - MaxBasic Function
CopyOrder: Boolean
Returns
True
if the Print as Copy selection box has been checked for the currently printing Purchase Order, returns
False
otherwise.
Available in PO Purchase Order Document design script editors.
See Also
Report Functions

---

## CopyToClipboard - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CopyToClipboardFunction.htm

CopyToClipboard - MaxBasic Function
CopyToClipboard(Variable: String / Number / Date / Boolean)
Copy To Clipboard function copies the passed Variable value to the Windows Clipboard.
CopyToClipboard function syntax has these named arguments:
Parameter
Description
Variable
Required. Can be a String, Number, Date or Boolean. The value of the Variable will be passed to the Windows Clipboard.
See Also
Environment Functions

---

## CostPriceDecimals - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CostPriceDecimalsFunction.htm

CostPriceDecimals - MaxBasic Function
CostPriceDecimals[(CurrencyCode: String)]: Number
Returns number of decimal places used to display cost prices. If CurrencyCode is empty, the decimal places for base currency is returned.
CostPriceDecimals function syntax has these named arguments:
Parameter
Description
CurrencyCode
Optional. The Currency Code to return the cost price decimals for.
See also the SQL
CostPriceDecimals
function.
See Also
Number Functions

---

## CountryISOCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CountryISOCodeFunction.htm

CountryISOCode - MaxBasic Function
CountryISOCode(CountryName: String): String
Country ISO Code function returns the ISO 2 character country code when passed a country name.
CountryISOCode function syntax has these named arguments:
Parameter
Description
Country Name
Required. The Country Name to return the Country Code for.
See Also
Script Functions

---

## CountryName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CountryNameFunction.htm

CountryName - MaxBasic Function
CountryName(CountryCode: String): String
Country Name function returns the country name when passed an ISO 2 character country code.
CountryName function syntax has these named arguments:
Parameter
Description
Country Code
Required. The Country Code to return the Country Name for.
See Also
Script Functions

---

## CreateCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateCompanyFunction.htm

CreateCompany - MaxBasic Function
CreateCompany(CompanyCode: String, CompanyName: String; DataPath: String, [ModuleList: String, [Country: String, [Currency: String, [TaxRegime: String]]]]): Boolean
Create new company database and add to the Company List.
Returns
True
if a company is successfully created, otherwise returns
False
.
CreateCompany function syntax has these named arguments:
Parameter
Description
Company Code
Required. The Code for the company. Must be a valid unique code.
Company Name
Required. The name of the company.
Data Path
Required. The company data path. This can optionally begin with
.\
Module List
Optional. The list of modules codes to create for the company, separated by commas, such as
"AP,AR,IC,IN,IS,PO,OE"
. If not specified or an empty string is passed then all installed modules are created.
Country
Optional. The country ISO Code. Defaults to the Windows Regional Setting if not entered.
Currency
Optional. The currency ISO code. If entered, must match the Country, otherwise defaults from the Country.
Tax Regime
Optional. The tax regime code. If entered, must match the Country, otherwise defaults from the Country.

---

## CreateCustomForm - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateCustomFormFunction.htm

CreateCustomForm - MaxBasic Function
CreateCustomForm(FormName: String): Object
Creates a User defined instance of the form FormName as an MDI child window.
CreateCustomForm function syntax has these named arguments:
Parameter
Description
FormName
Required. Name of custom form to create.
For example:
Form = CreateCustomForm("TestForm.pfd")
To open the custom form in Form Designer, place the cursor in the FormName, and click
Ctrl+Enter
, or right click to open the
Context Menu
, then select
Open Source
.
This function accepts an infinite number of arguments after the required parameter.
For example:
CreateCustomForm("TestForm.pfd", "Parameter1", 0, Date)
Inside
TestForm
.pfd
the arguments are accessed using the
ScriptArgs
function.
See Also
Objects Functions

---

## CreateCustomTableEditor - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateCustomTableEditorFunction.htm

CreateCustomTableEditor - MaxBasic Function
CreateCustomTableEditor(TableName: String, Title: String): Object
Creates an edit form for a user defined table.
CreateCustomTableEditor function syntax has these named arguments:
Parameter
Description
Table Name
Required. The table to create the edit form for.
Title
Optional. The title of the Custom Table Editor form created.
See Also
Objects Functions

---

## CreateCustomWindowForm - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateCustomWindowFormFunction.htm

CreateCustomWindowForm - MaxBasic Function
CreateCustomWindowForm(FormName: String): Object
Creates a User defined instance of the form FormName as a floating window form. For example:
CreateCustomWindowForm function syntax has these named arguments:
Parameter
Description
FormName
Required. Name of custom form to create.
Form = CreateCustomWindowForm("TestForm.pfd")
To open the custom form in Form Designer, place the cursor in the FormName, and click
Ctrl+Enter
, or right click to open the
Context Menu
, then select
Open Source
.
This function accepts an infinite number of arguments after the required parameter.
For example:
CreateCustomWindowForm("TestForm.pfd", "Parameter1", 0, Date)
Inside
TestForm
.pfd
the arguments are accessed using the
ScriptArgs
function.
See Also
Objects Functions

---

## CreateJobAnalysisReport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateJobAnalysisReportFunction.htm

CreateJobAnalysisReport - MaxBasic Function
CreateJobAnalysisReport(ReportDefinitionFilePath: String): Object
Creates a Job Analysis report from the specified JA Analysis report definition file.
CreateJobAnalysisReport function syntax has these named arguments:
Parameter
Description
Report Definition File Path
Required. The JA Analysis report definition file to create the job analysis report from.
See Also
Objects Functions

---

## CreateLinkData - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateLinkDataFunction.htm

CreateLinkData - MaxBasic Function
CreateLinkData(Account File: String, Account Code: String): Object
Creates a link list data object for the given Account File using the given Account Code.
CreateLinkData function syntax has these named arguments:
Parameter
Description
Account File
Required. The file type to create the link list from.
Account Code
Required. The value used to create the link list. A unique code or ID.
For example:
LinkData = CreateLinkData("APCRED", "AA")
Documentobject(LinkData)
Note: Form and Data objects have AccountFile and AccountCode properties which can be passed to the function.
See Also
Objects Functions

---

## CreateLinkList - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateLinkListFunction.htm

CreateLinkList - MaxBasic Function
CreateLinkList(Account File: String, Account Code: String): Object
Creates a link list form for the given  Account File using the given Account Code.
CreateLinkList function syntax has these named arguments:
Parameter
Description
Account File
Required. The file type to create the link list from.
Account Code
Required. The value used to create the link list. A unique code or ID.
For example:
CreateLinkList("APCRED", "AA")
Note: Form and Data objects have AccountFile and AccountCode properties which can be passed to the function.
See Also
Objects Functions

---

## CreateMemoData - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateMemoDataFunction.htm

CreateMemoData - MaxBasic Function
CreateMemoData(Account File: String, Account Code: String): Object
Creates a memo data object for the specified Account File and Account Code. The Memo data object has a sub-object of Memo. The Open and Insert methods of this sub-object will return the corresponding data object for the given Account File and Account Code.
CreateMemoData function syntax has these named arguments:
Parameter
Description
Account File
Required. The file type to create the memo data object for.
Account Code
Required. The value to create the memo data object for. A unique code or ID.
For example:
Dim data as Object
data = CreateMemoData("ARCUST","ASHENG")
Dim memoObj as Object
memoObj = data.memo
Dim newMemo as Object
newMemo = memoObj.Insert("M")
newMemo.Memo.Text = "It always seems impossible until its done"
newMemo.Save
The code above will create a Memo for the AR Customer "ASHENG".
Note: Form and Data objects have AccountFile and AccountCode properties which can be passed to the function. AccountFile GLOBAL and AccountCode GLOBAL will create Global Memo data.
See Also
Objects Functions

---

## CreateMemoList - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateMemoListFunction.htm

CreateMemoList - MaxBasic Function
CreateMemoList[(Account File: String, Account Code: String)]: Object
Creates a memo list from for the specified Account File and AccountCode. If no parameters are passed a Global memo list form will be created.
Available for Script Editor and
Import Designer
.
CreateMemoList function syntax has these named arguments:
Parameter
Description
Account File
Optional. The file type to create the memo list from.
Account Code
Optional. The record name to create the memo list from. A unique code or ID.
Note: Form and Data objects have AccountFile and AccountCode properties which can be passed to the function.
See Also
Objects Functions

---

## CreateModuleMemoData - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateModuleMemoDataFunction.htm

CreateModuleMemoData - MaxBasic Function
CreateModuleMemoData(ModuleCode: String): Object
Creates a Module Memo Data object, that can be used to Insert or Edit a memo within a Module.
CreateModuleMemoData function syntax has this named argument:
Parameter
Description
Module Code
Required. The Module Code to create the memo data object for.
The following example shows how to use the function to add a memo to an AR Customer:
Dim datMemo as Object
datMemo = CreateModuleMemoData("AR")
datMemo.Append
datMemo.AccountFile = "ARCUST"
datMemo.AccountCode = "ZMER0002"
datMemo.Subject = "Testing"
datMemo.Save
See Also
Objects Functions

---

## CreateObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateObjectFunction_1.htm

CreateObject - MaxBasic Function
CreateObject(ObjectType: String[, Interactive: Boolean]): Object
Create an automation object of the ObjectType specified. The type is a standard Windows OLE object name, for example, Excel.Application.
Available in Script functions, Report Designer and
Import Designer
.
Press
F1
with the cursor in the ObjectType to see the Automated Documentation for the object.
CreateObject function syntax has these named arguments:
Parameter
Description
ObjectType
Required. Type of object to create.
Interactive
Optional, default
true
. If
false
no dialog will be displayed.
Applies to Automated Report Objects and Batch Printing/Processing Form Objects only. For all other objects the parameter is ignored.
Note: Objects created using CreateObject will be opened in the Accredo window. To open a floating window, use the
OpenWindowForm
or
CreateCustomWindowForm
functions.
Properties of objects created can differ, based on circumstances under which objects are created. See also
MaxBasic Object Properties
.
See Also
Report Functions

---

## CreatePrintLog - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreatePrintLogFunction.htm

CreatePrintLog - MaxBasic Function
CreatePrintLog(Account File: String, Account Code: String [, Document Code: String]): Object
Creates a
print log
for the specified Account File and AccountCode. The records shown may optionally be limited by DocumentCode if more than one document type may be logged for the AccountFile.
Available for Script Editor.
CreatePrintLog function syntax has these named arguments:
Parameter
Description
Account File
Required. The file type to create the print log for.
Account Code
Required. The record name to create the memo list from. A unique code or ID.
Document Code
Optional. Limit logging displayed by document code.
Note: Form and Data objects have AccountFile and AccountCode properties which can be passed to the function.

---

## CreatePrintSingle - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreatePrintSingleFunction.htm

CreatePrintSingle - MaxBasic Function
CreatePrintSingle(DocumentFile: String, DocumentID: Number): Object
Returns the print form object for the Document. Opens as an MDI child form.
CreatePrintSingle function syntax has these named arguments:
Parameter
Description
Document File
Restricted to OEHEAD, INHEAD, POHEAD and APSHIP.
Document ID
Required. ID of the document to print.
See Also
Objects Functions

---

## CreatePurchaseAnalysisReport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreatePurchaseAnalysisReportFunction.htm

CreatePurchaseAnalysisReport - MaxBasic Function
CreatePurchaseAnalysisReport(ReportDefinition: String, FilePath: String): Object
Creates a Purchase Analysis report from the specified ReportDefinition in the FilePath file.
CreatePurchaseAnalysisReport function syntax has these named arguments:
Parameter
Description
Report Definition
Required. The report definition for the Purchase Analysis Report.
File Path
Required. The file path for the Purchase Analysis Report.
See Also
Objects Functions

---

## CreateReport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateReportFunction.htm

CreateReport - MaxBasic Function
CreateReport(ObjectName: Variant, Title: String[, SelectionText: String]): Object
Create a report from the specified data Object, with the specified report Title. Optional SelectionText string appears at the top of the report.
CreateReport function syntax has these named arguments:
Parameter
Description
Object Name
Required. The data object used to create the report.
Title
Required. The report title.
Selection Text
Optional. Text to appear at the top of the report.
See Also
Objects Functions

---

## CreateRuleList - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateRuleListFunction.htm

CreateRuleList - MaxBasic Function
CreateRuleList(FileName: String): Object
Create a list of rules for a Special Pricing Rule designed in
SP Rule List Designer
, saved as FileName.
CreateRuleList function syntax has these named arguments:
Parameter
Description
File Name
Required. The file name of the Special Pricing Rule file.
See Also
Objects Functions

---

## CreateSalesAnalysisReport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateSalesAnalysisReportFunction.htm

CreateSalesAnalysisReport - MaxBasic Function
CreateSalesAnalysisReport(ReportDefinitionFile: String): Object
Create a Sales Analysis report from the specified SA Analysis report definition file.
CreateSalesAnalysisReport function syntax has these named arguments:
Parameter
Description
Report Definition File
Required. The SA Analysis report definition file.
See Also
Objects Functions

---

## CreateSpecialPriceListReport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreateSpecialPriceListReportFunction.htm

CreateSpecialPriceListReport - MaxBasic Function
CreateSpecialPriceListReport(ReportDefinitionFile: String): Object
Create a Special Price List report from the specified SP Price List report definition file.
CreateSpecialPriceListReport function syntax has these named arguments:
Parameter
Description
Report Definition File
Required. The SP Price List report definition file.

---

## Creditor - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CreditorFunction.htm

Creditor - MaxBasic Function
Creditor: String
Returns the Accounts Payable Creditor. If AP is not available, an empty string is returned.
This function is available for
Price Book Designer
only.
See Also
Import Functions

---

## CrossTabCount - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CrossTabCountFunction.htm

CrossTabCount - MaxBasic Function
CrossTabCount: Number
Return number of columns resulting for cross tabbed fields.
Available in Analysis Reports only.
See Also
Report Functions

---

## CurrencyOf - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CurrencyOfFunction.htm

CurrencyOf - MaxBasic Function
CurrencyOf(CurrencyValue: Number): String
Passed a currency value, returns the currency code.
CurrencyOf function syntax has these named arguments:
Parameter
Description
Currency Value
Required. The currency value to return the code for.
See Also
Foreign Exchange Functions

---

## CurrentIteratorName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CurrentIteratorNameFunction.htm

CurrentIteratorName - MaxBasic Function
CurrentIteratorName: String
Returns
the currently executing iterator name in a document design or GL financial report, in custom reports will always return "Query".

---

## CurrentPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/CurrentPeriodFunction.htm

CurrentPeriod - MaxBasic Function
CurrentPeriod(Module: String): Number
Returns the Current Period for Module Code specified in Module,
CurrentPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to return the current period for.
See also the SQL
CurrentPeriod
function and the Web Services
CurrentPeriod
function.
See Also
Period Functions

---

## Date - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DateFunction.htm

Date - MaxBasic Function
Date: Date
Returns the current machine date.
See Also
Date Functions

---

## DateAvailable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DateAvailableFunction.htm

DateAvailable - MaxBasic Function
DateAvailable(Date: Date,Module: String[,User: String]): Boolean
Returns true if Period containing Date is available for posting to for the Module, optionally limited by user code.
DateAvailable function syntax has these named arguments:
Parameter
Description
Date
Required. Date to check.
Module
Required. Module to check.
User
Optional. User to constrain check.
See Also
Date Functions

---

## DateValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DateValueFunction.htm

DateValue - MaxBasic Function
DateValue(DateParameter: String/Date/Time/DateTime[, FormatString: String]): Date
DateValue returns a date value for DateParameter, optionally using the FormatString parameter to specify the format of DateParameter (either Day Month Year or Month Day Year). If FormatString is omitted, assumes the format of DateParameter matches the default date / time format.
DateValue function syntax has these named arguments:
Parameter
Description
DateParameter
Required. Parameter to be formatted as a date. This can be a String, Date, Time or DateTime value, including ISO 8601 Date Time strings.
FormatString
Optional. Date format for the DateParameter. If not entered, uses the default date / time format. Select from:
Day Month Year
Month Day Year
See Also
Date Functions

---

## DateWithinPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DateWithinPeriodFunction.htm

DateWithinPeriod - MaxBasic Function
DateWithinPeriod(PeriodID: Number, Date: Date): Boolean
Returns
True
if the Date is within the valid date range for the period specified by PeriodID, or returns
False
.
DateWithinPeriod function syntax has these named arguments:
Parameter
Description
PeriodID
Required. The Period ID to evaluate for the date.
Date
Required. The date to be looked up in the Period ID.
See Also
Period Functions

---

## Day - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DayFunction.htm

Day - MaxBasic Function
Day(Date: Date): Number
Day returns the day value for the Date. If Date is null then null is returned.
Day function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the day value for.
See Also
Date Functions

---

## DayOfWeek - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DayOfWeekFunction.htm

DayOfWeek - MaxBasic Function
DayOfWeek(Date: Date): Number
DayOfWeek returns day of week for a Date, as a number from 1 to 7 numbering from Sunday as 1.
DayOfWeek function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the day of week value for.
See Also
Date Functions

---

## Debug - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DebugFunction.htm

Debug - MaxBasic Function
Debug
Stops script execution and displays a list of the variables in scope and their values, in the modal dialog
MaxBasic Variable Browser.
Similar to the
MaxBasic Debugger Variables tab
.
In This Section
MaxBasic Variable Browser

---

## DefaultGSTCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DefaultGSTcodeFunction.htm

DefaultGSTCode - MaxBasic Function
DefaultGSTCode[(TaxRegime: String)]: String
Default GST Code Function returns the Default GST Code for a given tax regime.
If no Tax Regime is given, the Default GST Code for the Base Tax Regime is returned.
DefaultGSTCode function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the Default GST Code for. If not supplied, the Base Tax Regime is used.
See Also
GST Functions

---

## DefaultReadOnlyColor - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DefaultReadOnlyColorFunction.htm

DefaultReadOnlyColor - MaxBasic Function
DefaultReadOnlyColor: Number
Returns the Read Only Colour as set in View > Preferences >
Colour
.
Function available in FD Forms.
See Also
Script Functions

---

## DeleteCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DeleteCompanyFunction.htm

DeleteCompany - MaxBasic Function
DeleteCompany(CompanyCode: String): Boolean
Delete entry from Company List, does not delete data files.
Returns
True
if a company is successfully deleted, otherwise returns
False
.
DeleteCompany function syntax has these named arguments:
Parameter
Description
Company Code
Required. The Code for the company. Must be a valid company code.

---

## DeleteFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DeleteFileFunction.htm

DeleteFile - MaxBasic Function
DeleteFile(FileName: String): Boolean
Delete File function delete the file specified in File Name. Returns Boolean indicating success of operation.
DeleteFile function syntax has these named arguments:
Parameter
Description
File Name
Required. The name of the file to be deleted.
See Also
Environment Functions

---

## DequotedString- MaxBasic Function

Source: https://accredo.co.nz/webhelp/DequotedStringFunction.htm

DequotedString- MaxBasic Function
DequotedString(QuotedText: String[,Character:String]): String
Returns dequoted string version of the given QuotedText.
DequotedString function has these named arguments:
Parameter
Description
QuotedText
Required. Text string to be dequoted.
Character
Quoting character, default value "
Sample code:
S = "8" & """" & " pipe"
Quoted = QuotedString(S)
Dequoted = DequotedString(Quoted)
Print "S: " & S
Print "Quoted: " & Quoted
Print "Dequoted: " & Dequoted
Returns:
S: 8" pipe
Quoted: "8"" pipe"
Dequoted: 8" pipe
Sample code using character:
S = "8" & "'" & " pipe"
Quoted = QuotedString(S,"'")
Dequoted = DequotedString(Quoted,"'")
Print "S: " & S
Print "Quoted: " & Quoted
Print "Dequoted: " & Dequoted
Returns:
S: 8' pipe
Quoted: '8'' pipe'
Dequoted: 8' pipe
See Also
String Functions

---

## DesktopHeight - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DesktopHeightFunction.htm

DesktopHeight - MaxBasic Function
DesktopHeight: Number
Desktop Height function returns the height of the Windows desktop in pixels.
See Also
Environment Functions

---

## DesktopWidth - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DesktopWidthFunction.htm

DesktopWidth - MaxBasic Function
DesktopWidth: Number
Desktop Width function returns the width of the Windows desktop in pixels.
See Also
Environment Functions

---

## DirectoryExists - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DirectoryExistsFunction.htm

DirectoryExists - MaxBasic Function
DirectoryExists(DirectoryName: String): Boolean
DirectoryExists function syntax has these named arguments:
Parameter
Description
Directory Name
Required. The name of the directory to check.
See Also
Environment Functions

---

## DisableUserAccessCheck - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DisableUserAccessCheckFunction.htm

DisableUserAccessCheck - MaxBasic Function
DisableUserAccessCheck: Boolean
If User has control permission for
User Access Times
this inactivates the User Access Check for the current session.
See Also
Environment Functions

---

## DocumentObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DocumentObjectFunction.htm

DocumentObject - MaxBasic Function
DocumentObject(Object: Variant)
Creates documentation for the specified Object.
Useful for developing scripts when getting objects back from functions, for example, OpenTable, where the properties are dynamic depending on the object.
Within the Script Editor, you can also place the cursor within an object name and press F1 to show the object documentation.
DocumentObject function syntax has these named arguments:
Parameter
Description
Object
Required. The object to be documented.
See Also
Objects Functions

---

## DoEvents - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DoEventsFunction.htm

DoEvents - MaxBasic Function
DoEvents[(AllowInput:Boolean)]
Available in FD Forms only. Process all messages currently in the message queue.
DoEvents function syntax has these named arguments:
Parameter
Description
AllowInput
Optional, default False.
Controls how Application.ProcessMessages is called by the DoEvents function. If True, any Windows messages caused by Input (e.g click to focus) will also get processed.
See Also
Script Functions

---

## DropChars - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DropCharsFunction.htm

DropChars - MaxBasic Function
DropChars(String1: String, String2: String): String
Removes all occurrences of each character in String2 from String 1.
DropChars function syntax has these named arguments:
Parameter
Description
String1
Required. The String to be edited.
String2
Required. The string containing the characters to be removed from String1.
Sample code:
Print DropChars("abcedfghijklmnopqrstuvwxyz","face")
Returns:
bdghijklmnopqrstuvwxyz
See Also
String Functions

---

## Duplex - MaxBasic Function

Source: https://accredo.co.nz/webhelp/DuplexFunction.htm

Duplex - MaxBasic Function
Duplex: String
Returns the printer duplex mode. Modes available are:
"One side" - prints on one side of paper.
"Long edge" - prints on both sides of paper, flips on long edge.
"Short edge" - prints on both sides of paper, flips on short edge.
See Also
Report Functions

---

## EDIExport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EDIExportFunction.htm

EDIExport - MaxBasic Function
EDIExport(Definition: String, File: String[, Append: Boolean]): Variant - OR -
EDIExport(Format: Number, Definition: String, File: String, [Append: Boolean [, SheetName: String]]): Variant
Runs an EDI export using a DI definition file
Definition
and an export file name
File
. If the optional Append parameter is
True
, the export will append to File, or it will overwrite. Returns
True
on successful export,
False
if export fails, Error if definition is not found.
EDIExport function syntax has these named arguments:
Parameter
Description
Format
Optional. If used Valid formats are
0
for Text export, or
1
for Excel export. If parameter is omitted Text export is implied.
Definition
Required. The name of the DI definition file.
File
Required. The file to export to.
Append
Optional. When
True,
will append the exported data to the File. When
False
, will overwrite the File.
SheetName
Optional. The name of the Excel Worksheet to export to.
Note: Do not use apostrophes (') in worksheet names, as this can cause problems.
To open the file in a new Script Editor window, place the cursor in the File Name and click
Ctrl+Enter
, or right click to open the
Context Menu
, then select
Open Source
.
This function accepts an infinite number of arguments after the required parameters, these may be accessed using the
ScriptArgs
function in the Definition script.
See Also
Import/Export Functions

---

## EDIImport - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EDIImportFunction.htm

EDIImport - MaxBasic Function
EDIImport(Definition: String, File: String[, Clear: Boolean, Backup: Boolean, Worksheet: Variant]): Variant
Imports an EDI file called
File
, using an EDI Definition file called
Definition
.
If the optional
Clear
parameter is
True
, the import will clear the successfully imported records from the File. If the second optional parameter
Backup
is also
True
, a backup of the import file will be made.
The backup copy has the original import file name with the extension ".BAK". Previous backups of the import files will be renamed to increment the backup number ".BAK" to ".BK1", ".BK1" to ".BK2", and so on through to ".BK8" to ".BK9"; the oldest backup previously ".BK9" will drop off.
If the import file is an Excel Workbook, you can specify a Sheet Name or Sheet Number. If not specified, the Worksheet specified from the EDI Import definition file will be used.
This function returns
True
when the
Definition
and
File
files are found, and creates an error if either of these files are not found. This does not reflect whether the file was imported successfully, as a file can be imported with some records importing successfully and others unsuccessfully. To set the return value of the EDIImport function, set the ImportFile.Result property in the EDI Import Definition using MaxBasic code. The ImportFile.Result property defaults to
True
. For example:
ImportFile.Result = False
. See also
Import Invoices Example
.
The
ScriptArgs
function can be used with this function.
EDIImport function syntax has these named arguments:
Parameter
Description
Definition
Required. The name of the DI definition file.
File
Required. The import file name.
Clear
Optional. When
True,
will clear successfully imported records from the File.
Backup
Optional. When
True,
will create a backup copy of the File.
Worksheet
Optional. When File is an Excel Workbook, the Sheet Name or Sheet Number for import can be specified.
Note: Do not use apostrophes (') in worksheet names, as this can cause problems.
To open the file in a new Script Editor window, place the cursor in the File Name and click
Ctrl+Enter
, or right click to open the
Context Menu
, then select
Open Source
.
This function accepts an infinite number of arguments after the required parameters, these may be accessed using the
ScriptArgs
function in the Import Definition.
See Also
Import/Export Functions

---

## EmailFilename - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EmailFilenameFunction.htm

EmailFilename - MaxBasic Function
EmailFilename : String
Returns the Email Filename normally used. Available in Email Designers.
Email Designers
Email Filename
AR Receipt,         AR Statement
Document Type & " " & Date & " " & CustomerCode & ".pdf"
AP Remittance
DocumentClass & " " & DocumentNo & " " & CustomerCode & ".pdf"
IN Invoice,          OE Packing Slip,   AP Shipment,      PO Purchase Order, JC Job Sheet/Quote
DocumentClass & " " & DocumentNo & ".pdf"
For example, for invoices the email filename will return:
DocumentClass & " " & DocumentNo & ".pdf"
For example:
Invoice 100435.pdf
See Also
Report Functions

---

## EmailSubject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EmailSubjectFunction.htm

EmailSubject - MaxBasic Function
EmailSubject: String
Returns the Email Subject normally used. Available in Email Designers.
Email Designers
Email Subject
AR Statement,    AR Receipt,         AP Remittance,    JC Job Sheet/Quote
Document Type & " from " & CompanyName & " for " & CustomerName
IN Invoice,          OE Packing Slip,   AP Shipment,      PO Purchase Order
DocumentClass & " " & DocumentNo & " from " & CompanyName & " for " & CustomerName
For example, for invoices the email subject will return:
DocumentClass & " " & DocumentNo & " from " & CompanyName & " for " & CustomerName
For example:
Invoice 100435 from ABC Holdings Limited for Asheng Engineering Ltd
See Also
Report Functions

---

## EnableUserAccessCheck - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EnableUserAccessCheckFunction.htm

EnableUserAccessCheck - MaxBasic Function
EnableUserAccessCheck: Boolean
Activates the User Access Check for the current session if it was inactivated.
See Also
Environment Functions

---

## EnsureRefreshToken - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EnsureRefreshTokenFunction.htm

EnsureRefreshToken - MaxBasic Function
EnsureRefreshToken(Provider: string, User: string [,  ExpiryWithinDays: Number]) :Boolean
EnsureRefreshToken function returns True if RefreshToken will not expire within the number of days given, False otherwise.
If a refresh token will expire within ExpiryWithinDays days, then an authentication prompt will be presented to the user to complete login. The function will only return once this information has been entered.
In all cases, we will assume RefreshTokens expire within 90 days of being first issued (which is currently the case for MS JWT tokens).
EnsureRefreshToken function syntax has these named arguments:
Parameter
Description
Provider
Required. The Token provider.
Values are
"O" - Office 365
"P" - MS Graph
User
Required. The User Code to Ensure Refresh Token for.
Expiry Within Days
Optional. Number of days to check the refresh token will not expire for.
If ExpirywithinDays is not specified, then the logic for expiry will change to "expired if more than 67.5 days (75% of 90) have passed since first issued.
Sample usage:
msgbox(EnsureRefreshToken("P", "DEMO", 3))

---

## Eval - MaxBasic Function

Source: https://accredo.co.nz/webhelp/EvalFunction.htm

Eval - MaxBasic Function
Eval(ExpressionString: String)
Evaluates ExpressionString as a MaxBasic expression.
Eval function syntax has these named arguments:
Parameter
Description
ExpressionString
Required. The MaxBasic expression to be evaluated.
See Also
Script Functions

---

## ExecuteSQL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ExecuteSQLFunction.htm

ExecuteSQL - MaxBasic Function
ExecuteSQL(Query: String[, Param1: Variant, ..., MemoryTable: Object])
Execute SQL function executes the SQL Query with the parameters specified in Param1, and so on. Returns a memory table containing results of query.
The query string can be a
.pfq
file name. If the parameter is a pfq file name, you can use the right-click context menu or press Open Source (
Ctrl+Enter)
on the file name to open the file in the
SQL Query Builder
.
ExecuteSQL function syntax has these named arguments:
Parameter
Description
Query
Required. The SQL Query code to be executed. This can be a
.pfq
file name (SQL Query file).
Param1...
Optional. Any parameters required by the SQL Query.
MemoryTable
Optional. If a Memory Table object is passed in, it will be emptied and the results of the query will be copied to the MemoryTable.
See Also
Script Functions

---

## Exists - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ExistsFunction.htm

Exists - MaxBasic Function
Exists(
Codetype
: String, Indexname: String, Value1: Variant[, Value2: Variant, ...]): Boolean
Returns
True
if values (Value1 to ValueN) exist in the table specified by the string Codetype, otherwise returns
False
.
Exists function syntax has these named arguments:
Parameter
Description
Code Type
Required. String expression must be a valid MaxBasic Input
Code
, representing an Accredo code table.
Index Name
Required. Must be a valid index name for the table, or an empty string (which selects the default index).
Value1
Required. Value to search for in the Code table.
Value2 - Value 2
Optional. Additional values to search for in the Code table.
See Also
Boolean Functions

---

## ExpandEnvironmentVariables - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ExpandEnvironmentVariablesFunction.htm

ExpandEnvironmentVariables - MaxBasic Function
ExpandEnvironmentVariables(SourceString: String): String
Returns a string with Environment Variables registered in
Company Settings
expanded.
ExpandEnvironmentVariables function syntax has these named arguments:
Parameter
Description
SourceString
Required. The string containing environment variables to be expanded.
Sample code:
Print ExpandEnvironmentVariables("%OneDrive%")

---

## FAEndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FAEndOfPeriodFunction.htm

FAEndOfPeriod - MaxBasic Function
FAEndOfPeriod
Performs an End Of Period on FA.
FAEndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## FileExists - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FileExistsFunction.htm

FileExists - MaxBasic Function
FileExists(FileName: String): Boolean
FileExists function syntax has these named arguments:
Parameter
Description
File Name
Required. The name of the file to check.
See Also
Environment Functions

---

## FindCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FindCodeFunction.htm

FindCode - MaxBasic Function
FindCode(CodeType: String, Code: String): String
Returns the nearest match to a supplied value. Returns
Null
if there are no records in the file.
FindCode function syntax has these named arguments:
Parameter
Description
Code Type
Required. String expression used to select the type of code to be entered.
Code
Required. String expression specifying nearest code match.
See Also
Input Functions

---

## FirstAvailablePeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FirstAvailablePeriodFunction.htm

FirstAvailablePeriod - MaxBasic Function
FirstAvailablePeriod(Module: String): Number
Returns the first available period for the Module Code specified in Module (not limited by User).
FirstAvailablePeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the first available period for.
See Also
Period Functions

---

## FirstInYear - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FirstInYearFunction.htm

FirstInYear - MaxBasic Function
FirstInYear(PeriodID: Number[, Financial: Boolean]: Number
Returns the first period in the year that contains PeriodID. If the optional boolean parameter Financial is
True
then only financial periods are considered (adjustment periods are ignored).
It is also possible to call this function passing a year number in place of PeriodID
.
FirstInYear function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to be used to find the first in the year. Can also be passed a Year number.
Financial
Optional. If
True
, only financial periods are considered. If
False
, all periods are considered.
See Also
Period Functions

---

## FirstPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FirstPeriodFunction.htm

FirstPeriod - MaxBasic Function
FirstPeriod[(Financial: Boolean)]: Number
Returns the first period in the Company. If the optional boolean parameter Financial is
True
then only financial periods are considered (adjustment periods are ignored).
FirstPeriod function syntax has these named arguments:
Parameter
Description
Financial
Optional. If
True
, only financial periods are considered. If
False
, all periods are considered.
See Also
Period Functions

---

## FirstUserPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FirstUserPeriodFunction.htm

FirstUserPeriod - MaxBasic Function
FirstUserPeriod(Module: String[, User: String]): Number
Returns the first period which the User may post transactions into for the specified module. If the User parameter is not specified, the User is the logged in User.
FirstUserPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the first user period for.
User
Optional. User to find the first period for. Defaults to the User currently logged in.
See also the SQL
FirstUserPeriod
function and the Web Services
FirstUserPeriod
function.
See Also
Period Functions

---

## Fix - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FixFunction.htm

Fix - MaxBasic Function
Fix(Number: Number): Number
Returns the Integer portion of Number, rounded toward zero. Negative numbers round up.
Fix function syntax has these named arguments:
Parameter
Description
Number
Required. The number to be evaluated.
See Also
Number Functions

---

## FormatBankAccountNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormatBankAccountNoFunction.htm

FormatBankAccountNo - MaxBasic Function
FormatBankAccountNo(BankAcct: String, Pattern: String[, CountryCode: String]): String
Returns a formatted bank account number given a valid BankAcct string and valid Pattern string.
Currently only NZ bank accounts are supported.
FormatBankAccountNo function syntax has these named arguments:
Parameter
Description
BankAcct
Required. The bank account to be formatted.
If separators are included (dot, dash, or space) the number is broken into parts on the separators, if there are no separators for NZ accounts the parts break into 2, 4, 8, 2 or 3 character blocks per the original databank spec.
Pattern
Required. number of digits and desired separator for the formatted account number. Valid characters dot, dash, space and digits (1-9). Validity of the pattern is checked. e.g. "2-4-7-2".
CountryCode
Optional, defaults to Company Country Code if not specified. The country for the Bank Account. Currently only NZ supported other Country Codes will error.
For example:
FormatBankAccountNo("0109020006838900","2-4-7-2","NZ")
Returns: "01-0902-0068389-00"
FormatBankAccountNo("01 0902 0068389 001","2-4-7-2","NZ")
Returns: "01-0902-0068389-01"
See Also
String Functions

---

## FormatDateDifference - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormatDateDifferenceFunction.htm

FormatDateDifference - MaxBasic Function
FormatDateDifference(Time2: Time - Time1: Time): String or
FormatDateDifference(Date2: Date - Date1: Date): String
Converts a date / time difference into a number of hours, minutes, seconds and milliseconds string formatted value.
FormatDateDifference function syntax has these named arguments:
Parameter
Description
Time2 / Date2
Required. Time or Date to be subtracted from.
Time1 / Date1
Required. Time or Date to subtract from Time2 / Date2.
See Also
Date Functions

---

## FormatDateTime - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormatDateTimeFunction.htm

FormatDateTime - MaxBasic Function
FormatDateTime(Date: Date[, FormatString: String]): String
Date/time formatted as a string. If Date is
Null,
returns
Null
, otherwise returns Date formatted in accordance with String. If FormatString is omitted, the default windows date / time format will be used. See Max Basic
Date and Time Formats
for acceptable values of String.
FormatDateTime function syntax has these named arguments:
Parameter
Description
Date
Required. Date to be converted.
FormatString
Optional. Format for the conversion. If not entered, uses the default date / time format.
If "iso8601" is provided as the format string then the result will be an iso8601 formatted UTC date/time value.
If "iso8601tz" is provided as the format string then the result will be an iso8601 formatted UTC date/time value with local timezone offset.
Sample code:
Dim aDateTime as Date
aDateTime = Date + Time ' now
' format from DateTime variable
Dim isoDate as String, isoDateTz as String
isoDate = FormatDateTime(aDateTime, "iso8601")
isoDateTz = FormatDateTime(aDateTime, "iso8601tz")
Print "iso8601 DateTime:" & isoDate
Print "iso8601Tz DateTime:" & isoDateTz
' Convert to DateTime from string
Dim aTimeOnly as Date, aDateOnly as Date
aDateOnly = DateValue(isoDateTz)
aTimeOnly = TimeValue(isoDateTz)
Print "Parsed Date: " & aDateOnly
Print "Parsed Time: " & aTimeOnly
See Also
Date Functions

---

## FormatNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormatNumberFunction.htm

FormatNumber - MaxBasic Function
FormatNumber(Number: Number[, FormatString: String, RemoveCurrency: Boolean]): String
Formats Number as a string. If Number is
Null
, returns
Null
, or returns number formatted in accordance with FormatString. If FormatString is omitted, the default Windows number format will be used. FormatString can either be a domain name or a valid formatting string. See
Formatting
for acceptable values of FormatString. The RemoveCurrency boolean parameter is optional.
True
causes all currency related formatting for Number to be stripped, but retains the decimals formatting.
False
leaves the currency formatting for Number, and is the default if not specified.
FormatNumber function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be formatted.
FormatString
Optional.
Format string
for the number.
RemoveCurrency
Optional. If
True
, removes currency formatting. Defaults to
False
.
See Also
Number Functions

---

## FormatQuantity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormatQuantityFunction.htm

FormatQuantity - MaxBasic Function
FormatQuantity(Quantity: Number[, UOMCode: String, BlankZero: Boolean]): Number
Formats Number to Quantity Decimals. Number is the Quantity, String is an optional UOM Code, Boolean determines whether blank values are displayed as zero, and defaults to True. If String is empty or not a valid UOM Code, formats to the
Quantities
Decimals set in
Decimals
, otherwise formats to the Decimals for the UOM Code in String.
FormatQuantity function syntax has these named arguments:
Parameter
Description
Quantity
Required. Number to be formatted.
UOMCode
Optional. UOM Code to format the decimals to.
BlankZero
Optional. If
True
, returns blank results as
0
. Defaults to
True
.
See Also
Number Functions

---

## FormatTaxNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormatTaxNoFunction.htm

FormatTaxNo - MaxBasic Function
FormatTaxNo(TaxNo: String, Pattern: String[, CountryCode: String]): String
Returns a formatted Tax Number given a valid tax number and valid Pattern string.
Currently only NZ IRD numbers are supported.
FormatTaxNo function syntax has these named arguments:
Parameter
Description
TaxNo
Required. The tax number to be validated.
Pattern
Required. number of digits and desired separator for the formatted account number. Valid characters dot, dash, space and digits (1-9). Validity of the pattern is checked. e.g. "3-3-3".
CountryCode
Optional, defaults to Company Country Code if not specified. The country for the Tax Number. Currently only NZ supported other Country Codes will error.
For example:
FormatTaxNo("56 748 393","3-3-3" "NZ")
Returns: "056-748-393"
See Also
String Functions

---

## FormCapture - MaxBasic Function

Source: https://accredo.co.nz/webhelp/FormCaptureFunction.htm

FormCapture - MaxBasic Function
FormCapture[(FileName: String)] : Object
Form Capture function captures the Active Form saving the capture to the filename if specified. Returns an object with Print, Save and Email scripted procedures available.
FormCapture function syntax has these named arguments:
Parameter
Description
FileName
Optional. The File name to save the capture to. If file already exists, then it will be overwritten.
For example:
Dim Form1 as Object
Form1 = CreateObject("Accredo.APCreditorForm")
Dim Form2 as Object
Form2 = FormCapture
Form2.Print
Form2.Email
Form2.Save
or
Dim strCaptureFile as String
strCaptureFile = "c:\data\screenshot.bmp"
Dim imgCapture as Object
imgCapture = FormCapture(strCaptureFile)
imgCapture.Close
See Also
Script Functions

---

## GenerateGUID - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GenerateGUIDFunction.htm

GenerateGUID - MaxBasic Function
GenerateGUID: String
Generates and returns a Globally Unique Identifier (GUID) string.
Sample code:
Print GenerateGUID
Returns a unique GUID string.
See Also
String Functions

---

## GenerateSchema - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GenerateSchemaFunction.htm

GenerateSchema - MaxBasic Function
GenerateSchema(TableName: String, Path\SchemaFile.XML: String): Boolean
Generate Schema function uses the schema from the table specified in
TableName
, to generate an XML schema file, with the file name and location specified in
Path\SchemaFile.XML
. The schema file can later be used by the
UpgradeTable
function to upgrade a table using scripting.
Returns
False
if the schema is not created, or
True
if it is created.
GenerateSchema function syntax has these named arguments:
Parameter
Description
TableName
Required. Name of the table whose schema will be used to generate the file.
Path\SchemaFile.XML
Required. The location path and file name of the generated schema XML file.
See Also
Tables Functions

---

## GetAccount - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetAccountFunction.htm

GetAccount - MaxBasic Function
GetAccount(AccountCode: String): Object
Returns the GL Account object for a given account code regardless of account type.
GetAccount function syntax has these named arguments:
Parameter
Description
Account Code
Required. The Account Code to get the GL Account for.
See Also
General Ledger Functions

---

## GetAccredoDefaultPrinter - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetAccredoDefaultPrinterFunction.htm

GetAccredoDefaultPrinter - MaxBasic Function
GetAccredoDefaultPrinter: String
Returns the name of the Accredo default printer.
See Also
Environment Functions

---

## GetActiveEventName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetActiveEventNameFunction.htm

GetActiveEventName - MaxBasic Function
GetActiveEventName: String
Returns the name of the event that triggered the executing script.
See Also
Script Functions

---

## GetActiveFileName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetActiveFileNameFunction.htm

GetActiveFileName - MaxBasic Function
GetActiveFileName: String
Returns the path and name of the executing file, for example, Report, Script, EDI Import.
See Also
Script Functions

---

## GetActiveObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetActiveObjectFunction.htm

GetActiveObject - MaxBasic Function
GetActiveObject(IncludeCustomForms: Boolean): Object
Returns the object that is the currently active form in the application. This ignores the Navigator. If IncludeCustomForms is set to False, also ignores Script Editor forms to make testing easier. Also available from
Import Designer
.
GetActiveObject function syntax has these named arguments:
Parameter
Description
Include Custom Forms
Optional. When
True
, returns the active object. When
False
, returns the active object, ignoring Custom Forms. Defaults to
False
.
See Also
Objects Functions

---

## GetBaseCurrency - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetBaseCurrencyFunction.htm

GetBaseCurrency - MaxBasic Function
GetBaseCurrency: String
Return the currency code for the base currency.
See Also
Foreign Exchange Functions

---

## GetComponent - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetComponentFunction.htm

GetComponent - MaxBasic Function
GetComponent(ComponentName: String): Object
Returns the component named ComponentName.
Available in Report Designers.
GetComponent function syntax has these named arguments:
Parameter
Description
ComponentName
Required. The name of the report component.
See Also
Report Functions

---

## GetConfigValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetConfigValueFunction.htm

GetConfigValue - MaxBasic Function
GetConfigValue(VariableName: String)
GetConfigValue function gets the variable for VariableName
from the file specified in
LoadConfig
or variable created using
SetConfig
and returns the value. Must be used in conjunction with
LoadConfig
or
SetConfig
.
GetConfigValue function syntax has these named arguments:
Parameter
Description
VariableName
Required. Variable name for Config value loaded into memory.
See Also
Environment Functions

---

## GetEnumText - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetEnumTextFunction.htm

GetEnumText - MaxBasic Function
GetEnumText(EnumName: String, EnumValue: Variant): String
Get Enum Text function returns the Enum text given an Enum value and the domain.
GetENumText function syntax has these named arguments:
Parameter
Description
Enum Name
Required. The name of the Enum domain.
Enum Value
Required. The Enum value.
For example:
Print GetEnumText("MemoType","A")
will print "Alarm"
See Also
Environment Functions

---

## GetEnvironmentVariable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetEnvironmentVariableFunction.htm

GetEnvironmentVariable - MaxBasic Function
GetEnvironmentVariable(EnvironmentVariable: String): String
Get Environment Variable function returns the value of an environment variable. Returns
Null
if
Null
passed or the specified variable does not exist, or returns the environment string as requested.
GetEnvironmentVariable function syntax has these named arguments:
Parameter
Description
Environment Variable
Required. The environment variable to be evaluated.
See Also
Environment Functions

---

## GetExcelSheetNames - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetExcelSheetNamesFunction.htm

GetExcelSheetNames - MaxBasic Function
GetExcelSheetNames(ExcelFileName: String): Object
Returns a string list of sheet names for the given Excel file.
GetExcelSheetNames function syntax has these named arguments:
Parameter
Description
ExcelFileName
Required. The name of the Excel file to extract SheetNames from.
See Also
Script Functions

---

## GetExchangeRate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetExchangeRateFunction.htm

GetExchangeRate - MaxBasic Function
GetExchangeRate(CurrencyCode: String, RateType: String, Date: Date): Number
Passed a CurrencyCode, Rate Type and Date, returns the Exchange Rate. Returns zero if no rate found.
GetExchangeRate function syntax has these named arguments:
Parameter
Description
Currency Code
Required. The currency code to get the rate for.
Rate Type
Required. The type of exchange rate.
Date
Required. The effective date for the exchange rate.
See also the SQL
GetExchangeRate
function and the Web Services
GetExchangeRate
function.
See Also
Foreign Exchange Functions

---

## GetFieldNames - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetFieldNamesFunction.htm

GetFieldNames - MaxBasic Function
GetFieldNames(FileName: String[, CustomFields: Boolean]): StringList
Get Field Names function returns a
StringList Object
containing field names for the table FileName, sorted alphabetically.
GetFieldNames function syntax has these named arguments:
Parameter
Description
FileName
Required. The Accredo table or Custom table name.
CustomFields
Optional. If True, only Custom field names are returned. If False all field names are returned. Defaults to False.
Note: The type for a Field Name can be obtained using the
PropertyType
method on the Table object.
See Also
Tables Functions

---

## GetFieldValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetFieldValueFunction.htm

GetFieldValue - MaxBasic Function
GetFieldValue(String: Variant)
GetFieldValue function returns the current value for an Import field given the field name. Only available in DI Import LineType.
GetFieldValue function syntax has these named arguments:
Parameter
Description
String
Required. Variable name as shown in the Field Names for the Line Type.
See Also
Import Functions

---

## GetGDIHandles - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetGDIHandlesFunction.htm

GetGDIHandles - MaxBasic Function
GetGDIHandles: Number
GetGDIHandles returns the GDI handles used by this process.
See Also
Application Functions

---

## GetKernelHandles - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetKernelHandlesFunction.htm

GetKernelHandles - MaxBasic Function
GetKernelHandles: Number
GetKernelHandles returns the Kernel handles used by this process.
See Also
Application Functions

---

## GetLicenseID - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetLicenseIDFunction.htm

GetLicenseID - MaxBasic Function
GetLicenseID: String
Get License ID function returns the session license allocated, or returns
None
if no session license is allocated.
See Also
Environment Functions

---

## GetLicensesAvailable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetLicensesAvailableFunction.htm

GetLicensesAvailable - MaxBasic Function
GetLicensesAvailable(LicenseGroup: String): Number
Get Licenses Available function returns the number of licenses available for the LicenseGroup. LicenseGroup is optional and defaults to "WIN". Other available values for LicenseGroup are "COM" or "CMD".
GetLicensesAvailable function syntax has these named arguments:
Parameter
Description
License Group
Optional. The LicenseGroup to return the count of licenses for. If no value is entered, defaults to "WIN". Other available values for LicenseGroup are "COM" or "CMD".
See Also
Environment Functions

---

## GetLicensesCount - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetLicensesCountFunction.htm

GetLicensesCount - MaxBasic Function
GetLicensesCount: Number
Get Licenses Count function returns the number of user licenses.
See Also
Environment Functions

---

## GetLog - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetLogFunction.htm

GetLog - MaxBasic Function
GetLog: String
Returns current output log string.
See Also
Import Functions

---

## GetLoggedInUsers - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetLoggedInUsersFunction.htm

GetLoggedInUsers - MaxBasic Function
GetLoggedInUsers([All Companies: Boolean]): Object
Returns a memory table object that lists currently logged in users.
Parameter
Description
All Companies
Optional. When
True
, returns logged in users for all companies. When
False
, returns logged in users for the current company. Defaults to
False
.
For example:
Dim x as Object
x = GetLoggedInUsers(True)

---

## GetLowerRateLimit - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetLowerRateLimitFunction.htm

GetLowerRateLimit - MaxBasic Function
GetLowerRateLimit (CurrencyCode: String): Number
Passed a CurrencyCode. Returns Minimum Rate for currency from
FX Exchange Rate Limits
.
GetLowerRateLimit function syntax has these named arguments:
Parameter
Description
Currency Code
Required. The currency code to get the rate limit for.
See also the Web Services GetLowerRateLimit function.
See Also
Foreign Exchange Functions

---

## GetNamedObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetNamedObjectFunction.htm

GetNamedObject - MaxBasic Function
GetNamedObject(Name: String): Object
Attempts to locate an object with the name Name. Names are given to objects by assigning to their Name property. This can be used to relocate a form created by a previous script. Also available from
Import Designer
.
GetNamedObject function syntax has these named arguments:
Parameter
Description
Name
Required. The name of the object to be located.
See Also
Objects Functions

---

## GetPermUser - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetPermUserFunction.htm

GetPermUser - MaxBasic Function
GetPermUser: String
Returns the UserCode for the current Permission User.
Note: This will always be the same as the User.LoginUserCode except in an
encrypted script
where
SetPermUser
has be used to elevate the Permission User.

---

## GetPreference - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetPreferenceFunction.htm

GetPreference - MaxBasic Function
GetPreference(PreferenceName: String): Number
Get Preference function returns the value of a Workstation Preference.
See
Application Preference Strings
for a list of all available preferences. See also
SetPreference
function.
Examples are:
General > Mail Integration
PreferenceName: Generic\MAPIStyle
0 = Autodetect (default)
1 = Outlook
2 = Simple MAPI
3 = Full MAPI
Trouble-shooting > TAPI diagnostics level
PreferenceName: Generic\TAPIDiagLevel
0 = None
1 = significant messages
2 = all messages
Trouble-shooting > Printer diagnostics level
PreferenceName: Generic\PrinterDiagLevel
0 = None
1 = significant messages
2 = all messages
GetPreference function syntax has these named arguments:
Parameter
Description
Preference Name
Required. The workstation preference to be evaluated. Some valid values are "Generic\MAPIStyle", "Generic\TAPIDiagLevel" or "Generic\PrinterDiagLevel".
In This Section
Application Preference Strings
See Also
Application Functions

---

## GetPropertyValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetPropertyValueFunction.htm

GetPropertyValue - MaxBasic Function
GetPropertyValue(Object: Object, Property: String): Object
Returns the Value of a Property of an Object.
GetPropertyValue function syntax has these named arguments:
Parameter
Description
Object
Required. The object containing the property.
Property
Required. The name of the Property to return the value of.
See also the Scripted Form
GetPropertyValue
Object Method, the Memory Table Builder
GetPropertyValue
method and the Memory Table
GetPropertyValue
method.
See Also
Script Functions

---

## GetRef - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetRefFunction.htm

GetRef - MaxBasic Function
GetRef(SubName: String): Object
Returns reference to Sub statement named SubName.
This is similar to
AddressOf
.
GetRef function syntax has these named arguments:
Parameter
Description
SubName
Required. The name of the Sub statement.
See Also
Script Functions

---

## GetScriptOutput - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetScriptOutputFunction.htm

GetScriptOutput - MaxBasic Function
GetScriptOutput :StringList
The GetScriptOutput function retrieves the content of the Print stream and returns it as a StringList object. This allows you to access and manipulate the output of Print commands within your script.
Example Usage:
' Example script demonstrating GetScriptOutput
Print "1"
Print 2
Print "Three"
Dim OutputLog as Object
OutputLog = GetScriptOutput
' Print the content of the Print stream
Print OutputLog.Text
Expected Output:
1
2
Three
Notes:
The GetScriptOutput function is useful for capturing Print output during script execution for logging or debugging purposes.
The returned
StringList
object provides methods for further manipulation of the captured content, such as iterating through lines or searching for specific text.

---

## GetSessionDesc - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetSessionDescFunction.htm

GetSessionDesc - MaxBasic Function
GetSessionDesc: String
Returns description for the current session.
The session description can also be viewed by customising Description into
Logged-In Users
.
See Also
User Functions

---

## GetStampUser - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetStampUserFunction.htm

GetStampUser - MaxBasic Function
GetStampUser: String
Returns record stamp user name.
See Also
User Functions

---

## GetTickCount - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetTickCountFunction.htm

GetTickCount - MaxBasic Function
GetTickCount: Number
Get Tick Count function returns the system tick count (in milliseconds).
See Also
Environment Functions

---

## GetTriggerMethod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetTriggerMethodFunction.htm

GetTriggerMethod - MaxBasic Function
GetTriggerMethod: String
For use with script events, this returns the name of the method that triggered the event to allow differentiation where the same event may be triggered via different methods.
Currently returned TriggerMethods are OrderFromQuote, OrderFromInvoice and QuoteFromOrder for the AfterInsert event on the OESalesOrderEntryForm and InvoiceFromQuote and OrderFromQuote for the BeforeAccept event on the INInvoiceEntryForm.
See Also
Objects Functions

---

## GetTriggerObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetTriggerObjectFunction.htm

GetTriggerObject - MaxBasic Function
GetTriggerObject: Object
For script events this returns the object that triggered the event.
For script or custom form shortcuts on Form toolbars returns the form object which the shortcut was triggered on.
Because of timing this may not be the current GetActiveObject object.
See Also
Objects Functions

---

## GetTypedObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetTypedObjectFunction.htm

GetTypedObject - MaxBasic Function
GetTypedObject(ClassNames: List): Object
Returns the first found object matching the ClassNames list of objects, or returns Null if not found.
GetTypedObject function syntax has these named arguments:
Parameter
Description
Class Names
Required. A list of class names to return, in double quotes "", separated by semi-colons ';'. For example,
"INInvoiceEntryForm;OESalesOrderForm"
.
See Also
Objects Functions

---

## GetUpperRateLimit - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetUpperRateLimitFunction.htm

GetUpperRateLimit - MaxBasic Function
GetUpperRateLimit (CurrencyCode: String): Number
Passed a CurrencyCode. Returns Maximum Rate for currency from
FX Exchange Rate Limits
.
GetUpperRateLimit function syntax has these named arguments:
Parameter
Description
Currency Code
Required. The currency code to get the rate limit for.
See also the Web Services GetUpperRateLimit function.
See Also
Foreign Exchange Functions

---

## GetUserHandles - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetUserHandlesFunction.htm

GetUserHandles - MaxBasic Function
GetUserHandles: Number
GetUserHandles returns the User handles used by this process.
See Also
Application Functions

---

## GetVarType - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GetVarTypeFunction.htm

GetVarType - MaxBasic Function
GetVarType(VariableName: Variable): String
For a given VariableName, returns the variable type as a string.
GetVarType function syntax has these named arguments:
Parameter
Description
VariableName
Required. The name of the variable to return the type of.
See Also
Script Functions

---

## GLEndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GLEndOfPeriodFunction.htm

GLEndOfPeriod - MaxBasic Function
GLEndOfPeriod
Performs an End Of Period on GL.
GLEndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## GSTBasis - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GSTBasisFunction.htm

GSTBasis - MaxBasic Function
GSTBasis[(TaxRegime: String)]: String
GST Basis Function returns the GST basis for a given tax regime. Returns
I
for Invoice,
P
for payments or
N
for not registered. If no Tax Regime is given, the GST Basis for the Base Tax Regime is returned.
GSTBasis function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the GST Basis for. If not supplied, the Base Tax Regime is used.
See Also
GST Functions

---

## GSTRate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GSTRateFunction.htm

GSTRate - MaxBasic Function
GSTRate[(Code: String, Date: Date)]: Number
GST rate for Code. If Code is empty, the rate for the default GST code is returned. If Date is not specified then the current
Accounting System Date
date is used.
GSTRate function syntax has these named arguments:
Parameter
Description
Code
Optional. The GST Code to return the rate for.
Date
Optional. The effective date to return the rate for.
See also the SQL
GSTRate
function and the Web Services
GSTRate
function.
See Also
GST Functions

---

## GSTRegistered - MaxBasic Function

Source: https://accredo.co.nz/webhelp/GSTRegisteredFunction.htm

GSTRegistered - MaxBasic Function
GSTRegistered[(TaxRegime: String)]: Boolean
GST Registered function returns
True
if GST Settings GST Basis is Invoice / Accruals (Non-Cash) or Payments / Cash, or
False
, for a given Tax Regime. If no Tax Regime is given, the Base Tax Regime is used.
Available in Report and Document design script editors.
GSTRegistered  function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the GST Registered for. If not supplied, the Base Tax Regime is used.
See Also
GST Functions

---

## HasBudgetActivity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasBudgetActivityFunction.htm

HasBudgetActivity - MaxBasic Function
HasBudgetActivity([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Budget activity between the range of periods specified,
False
otherwise.
Optionally can be passed additional parameters to calculate summed period activity over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasBudgetActivity function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasBudgetOpening - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasBudgetOpeningFunction.htm

HasBudgetOpening - MaxBasic Function
HasBudgetOpening([BudgetCode: String,] PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Period Opening,
False
otherwise.
Calculates Period opening balance for period specified. Optionally can be passed additional parameters to calculate summed period opening balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasBudgetOpening function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
ID Period
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasPeriodActivity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasPeriodActivityFunction.htm

HasPeriodActivity - MaxBasic Function
HasPeriodActivity(StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Period activity between the range of periods specified,
False
otherwise.
Optionally can be passed additional parameters to calculate summed period activity over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasPeriodActivity function syntax has these named arguments:
Parameter
Description
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasPeriodBalance - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasPeriodBalanceFunction.htm

HasPeriodBalance - MaxBasic Function
HasPeriodBalance(StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Period Balance,
False
otherwise.
Optionally can be passed additional parameters to calculate summed period balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
If a range of periods is specified, for example, to obtain a quarterly balance, calculates balance as OpeningBalance for start period plus sum of Activity from start period to end period.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasPeriodBalance function syntax has these named arguments:
Parameter
Description
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasPeriodBudget - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasPeriodBudgetFunction.htm

HasPeriodBudget - MaxBasic Function
HasPeriodBudget([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Period Budget,
False
otherwise.
Calculates sum of period budgets over range of periods specified. If a budget code is not passed then default budget is used. Optionally can be passed additional parameters to calculate summed period budgets over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasPeriodBudget function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasPeriodOpening - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasPeriodOpeningFunction.htm

HasPeriodOpening - MaxBasic Function
HasPeriodOpening(PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Period Opening,
False
otherwise.
Calculates Period opening balance for period specified. Optionally can be passed additional parameters to calculate summed period opening balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasPeriodOpening function syntax has these named arguments:
Parameter
Description
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasPeriodProjected - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasPeriodProjectedFunction.htm

HasPeriodProjected - MaxBasic Function
HasPeriodProjected([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Period Projected,
False
otherwise.
Calculates Period projected balance from actual figures up to report Period and budgeted figures for future periods relative to report period over the specified period range. If a budget code is not passed then the default budget is used. Optionally can be passed additional parameters to calculate projected summed period over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasPeriodProjected function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasProjectedActivity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasProjectedActivityFunction.htm

HasProjectedActivity - MaxBasic Function
HasProjectedActivity([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Projected Activity,
False
otherwise.
Calculates projected activity between the range of periods specified. Optionally can be passed additional parameters to calculate summed period activity over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasProjectedActivity function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasProjectedOpening - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasProjectedOpeningFunction.htm

HasProjectedOpening - MaxBasic Function
HasProjectedOpening([BudgetCode: String,] PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Projected Opening balances,
False
otherwise.
Calculates projected opening balance for period specified. Optionally can be passed additional parameters to calculate summed period opening balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasProjectedOpening function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasYearBalance - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasYearBalanceFunction.htm

HasYearBalance - MaxBasic Function
HasYearBalance(PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Year Balance,
False
otherwise.
Calculates Year to date balance as at period specified. Optionally can be passed additional parameters to calculate summed year to date balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasYearBalance function syntax has these named arguments:
Parameter
Description
Period ID
Required. The starting Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasYearBudget - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasYearBudgetFunction.htm

HasYearBudget - MaxBasic Function
HasYearBudget([BudgetCode: String,] PeriodID: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Year Budget,
False
otherwise.
Calculates Year to date budget as at period specified. If a budget code is not passed then the default budget is used. Optionally can be passed additional parameters to calculate summed year to date budget over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasYearBudget function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HasYearProjected - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HasYearProjectedFunction.htm

HasYearProjected - MaxBasic Function
HasYearProjected([BudgetCode: String,] PeriodID: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean]): Boolean
Returns
True
if accounts have non zero Year Projected,
False
otherwise.
Calculates Year projected balance for actual figures as at the period specified and budgeted figures to the end of the year. If a budget code is not passed then the default budget is used. Optionally can be passed additional parameters to calculate projected summed year over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
HasYearProjected function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## HMACSHA1String - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HMACSHA1StringFunction.htm

HMACSHA1String - MaxBasic Function
HMACSHA1String(SignatureBase: String, Key: String): String
Calculates the Hash-based Message Authentication Code using the SHA1 hash function. Returns the Base64Encoded string value of the calculated hash.
HMACSHA1String function has these named arguments:
Parameter
Description
Signature Base
Required. Signature base for the calculation.
Key
Required. Key to use for the calculation.
Sample code:
sig = "PDvpzHwTEKh4f8eQNNQsoMV1RiApOk9SPpiC-OCw7-im52Z9bL2OPwFBQ2KhD8pGD1AVRSkcATKZ9zfeZrulQw"
key = "accredotest"
HashCode = HMACSHA1String(sig, key)
print HashCode
Returns:
t8i70RcLWIf64q91E/v0jsXGWiM=
See Also
Web Functions

---

## HTMLAvailable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HTMLAvailableFunction.htm

HTMLAvailable - MaxBasic Function
HTMLAvailable: Boolean
HTML Available function returns
True
if the User Setting for Mail Format is HTML, and either the work station preference for Mail Integration is not Simple MAPI or Use SMTP Mailing is selected. Otherwise returns
False
.
See Also
Environment Functions

---

## HTMLEncode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HTMLEncodeFunction.htm

HTMLEncode - MaxBasic Function
HTMLEncode(HTMLText: String): String
Given a string containing HTML text, returns a string containing escaped characters for non-valid HTML elements.
HTMLEncode function has these named arguments:
Parameter
Description
HTMLText
Required. The string of HTML Text to encode.
Sample code:
Text = "This is a <Test String>"
HTMLEncoded = HTMLEncode(Text)
Print HTMLEncoded
Returns:
This is a &lt;Test String&gt;
See Also
Web Functions

---

## HTMLToText - MaxBasic Function

Source: https://accredo.co.nz/webhelp/HTMLToTextFunction.htm

HTMLToText - MaxBasic Function
HTMLToText(HTML: String): String
Given an encoded HTML, returns a string containing the textual representation of the rendered HTML.
HTMLToText function has these named arguments:
Parameter
Description
HTML
Required. The string of HTML to render as text.
Sample code:
html = "<p>There is a <u><b>growing</b></u> realisation&ndash; that</p>"
HTMLText = HTMLToText(HTML)
Print HTMLText
Returns: There is a growing realisation– that
See Also
Web Functions

---

## ICEndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ICEndOfPeriodFunction.htm

ICEndOfPeriod - MaxBasic Function
ICEndOfPeriod
Performs an End Of Period on IC.
ICEndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## IIf - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IIfFunction.htm

IIf - MaxBasic Function
IIf(Expr1: Variant, Expr2: Variant, Expr3: Variant): Boolean
Conditional function. All three expression parameters are evaluated. If Expr1 is
True
, Expr2 is returned else Expr3 is returned.
IIf function syntax has these named arguments:
Parameter
Description
Expr 1
Required. String expression to be evaluated as True or False.
Expr 2
Required. Expression to be returned if Expr1 is True.
Expr 3
Required. Expression to be returned if Expr1 is False.
See Also
Boolean Functions

---

## ImportFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ImportFileFunction.htm

ImportFile - MaxBasic Function
ImportFile: String
Returns the import file object.
See Also
Import Functions

---

## InputBinCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputBinCodeFunction.htm

InputBinCode - MaxBasic Function
Accredo Saturn only, use InputCode.
InputBinCode(Location: String, Prompt: String[, Title: String, DefaultValue: String, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean]): StringAccredo Saturn only, use InputCode in Accredo Mercury.
Displays a prompt in a dialog box, User can enter or select a valid Bin Code, and returns the Bin Code.
Note, if User clicks
OK
or presses
Enter
InputBinCode function returns the Bin Code. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputBinCode function syntax has these named arguments:
Parameter
Description
Location
Required. The Location to show Bin Codes for.
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default Value
Optional. The default Bin Code to display. If you omit Default Value, the control will display empty.
Filter
Optional. String containing a filter value to apply to Bins available.
Filter Button Visible
Optional, defaults to
False
. Determines whether to display the Filter button.
Allow Inactive
Optional, defaults to
False
. Determines if Inactive Bins are available.
See also Scripted Form InputBinCode method.

---

## InputBoolean - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputBooleanFunction.htm

InputBoolean - MaxBasic Function
InputBoolean(Prompt: String[, Title: String, Default: Boolean]): Boolean
Displays a dialog box, the User must select or clear a checkbox, or click a button; returns a boolean (yes/no) value depending on the checkbox state.
Notes: If User clicks
OK
or presses
Enter
, the InputBoolean function returns
true
or
false
depending on the checkbox state. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputBoolean function syntax has these named arguments:
Parameter
Description
Prompt
Required. A string expression that will display as a message in the dialog box.
Title
Optional. A string expression that will display in the title bar of the dialog box. If you omit a title, the application name will appear in the title bar.
Default
Optional. If you omit a value, the default is
false.
See also Scripted Form
InputBoolean
method and Input Grid
InputBoolean
method.
See Also
Input Functions

---

## InputBox - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputBoxFunction.htm

InputBox - MaxBasic Function
InputBox(Prompt: String[, Title: String, Default: String, PasswordChar: Char]): String
Displays a prompt in a dialog box, User must input text or click a button, returns a string containing the contents of the text box.
Notes: If User clicks
OK
or presses
Enter
, InputBox function returns what is in the text box (empty string "" if no value entered). If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputBox function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. String expression displayed in the text box as the default response if no other input is provided. If you omit default, the text box is displayed empty.
PasswordChar
Optional. Character displayed in the text box to mask user input.
See also Scripted Form
InputBox
method and Input Grid
InputBox
method.
See Also
Input Functions

---

## InputCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputCodeFunction.htm

InputCode - MaxBasic Function
InputCode(CodeType: String, Prompt: String[, Title: String, Default: String, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean, AllowEmpty: Boolean, UseExactMatch: Boolean]): String
Displays a prompt in a dialog box, User must input or select a correct Code or click a button, returns a string containing the contents of the Code box.
If the Code Type is a Category Code, and Prompt is an empty string (that is ""), the Prompt will be set to the Category Alias for the Category Code. To specify the Category Alias and some additional text use the
ApplicationSetting
function to retrieve the Category alias, for example:
InputCode("ICCAT1", ApplicationSetting("IC\Cat1Alias") & " - From")
If the User clicks
OK
or presses
Enter,
InputCode function returns what is in the look-up control (empty string "" if no value entered). If the User clicks
Cancel
or presses
Esc
, this function returns
Null
.
See
MaxBasic Input Code Types
for available codes.
InputCode function syntax has these named arguments:
Parameter
Description
Code Type
Required. String expression used to select the type of code to be entered.
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Code displayed in the look-up control as the default response if no other input is provided. If you omit default, the look-up control is displayed empty.
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
See also Scripted Form
InputCode
method and Input Grid
InputCode
method.
In This Section
MaxBasic Input Code Types
See Also
Input Functions

---

## InputContact - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputContactFunction.htm

InputContact - MaxBasic Function
InputContact(CodeType: String, CodeValue: String, Prompt: String[, Title: String, DefaultValue: Number, Filter: String, FilterButtonVisible: Boolean, AllowInactive: Boolean]): String
Displays a prompt in a dialog box, User can enter or select a valid Contact Code, and returns the Contact Code.
Note, if User clicks
OK
or presses
Enter
InputContact function returns the Contact Code. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputContact function syntax has these named arguments:
Parameter
Description
Code Type
Required. Can be "ARCONTCT" for AR Contacts or "APCONTCT" for AP Contacts.
Code Value
Required. Can be blank for all contacts, or set to a Customer or Creditor code to limit to contacts for a particular Customer or Creditor, based on the Code Type.
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default Value
Optional. Number with the default Contact ID. If you omit Default Value, the control will display empty.
Filter
Optional. String containing a filter value to apply to contacts available.
Filter Button Visible
Optional, defaults to
False
. Determines whether to display the Filter button.
Allow Inactive
Optional, defaults to
False
. Determines if Inactive Contacts are available.
See also Scripted Form
InputContact
method.

---

## InputCountry - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputCountryFunction.htm

InputCountry - MaxBasic Function
InputCountry(Prompt: String[, Title: String, Default: String, AllowEmpty: Boolean]): String
Displays a prompt in a dialog box, User must input a valid country or click a button, and returns a country code.
Note, if User clicks
OK
or presses
Enter
InputCountry function returns the country code. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputCountry function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. String expression with the default Country name or code. If you omit default, the control will display empty.
Allow Empty
Optional, defaults to
False
. Determines if the Lookup can be cleared after a value has been selected.
See also Scripted Form
InputCountry
method.
See Also
Input Functions

---

## InputCustomCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputCustomCodeFunction.htm

InputCustomCode - MaxBasic Function
InputCustomCode(CustomTable: String, Prompt: String[, Title: String, Default: String, Filter: String, FilterButtonVisible: Boolean, AllowEmpty: Boolean, UseExactMatch: Boolean]): String
Displays a prompt in a dialog box, User must input or select a correct code or click a button, returns a string containing the contents of the code box.
Notes: If User clicks
OK
or presses
Enter
, InputCustomCode function returns what is in the look-up control (empty string "" if no value entered). If User clicks
Cancel
or presses
Esc
, function returns
Null
. The Code field is identified by being the single field in the first primary or unique index on the table, or the first field if that fails.
InputCustomCode function syntax has these named arguments:
Parameter
Description
Custom Table
Required. Custom table name or memory table object used to select the custom code to be entered.
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Code displayed in the look-up control as the default response if no other input is provided. If you omit default, the look-up control is displayed empty.
Filter
Optional. Filter expression for limiting available master file codes.
Filter Button Visible
Optional, defaults to
True
. Determines if the filter button is available on the control.
Allow Empty
Optional, defaults to
False.
Determines if the Lookup can be cleared after a value has been selected.
Use Exact Match
Optional, defaults to
True
. Determines if the Lookup can accept and return values not in the code list.
Note: You can load and save customisations to the drop-down list by right-clicking in the list and selecting
Customise
.
See also Scripted Form
InputCustomCode
method and Input Grid
InputCustomCode
method.
See Also
Input Functions

---

## InputDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputDateFunction.htm

InputDate - MaxBasic Function
InputDate(Prompt: String[, Title: String, Default: Date]): Date
Displays a prompt in a dialog box, User must input a valid date or click a button, and returns a date containing the contents of the date box.
Notes: If User clicks
OK
or presses
Enter
InputDate function returns what is in the date control (current machine date if no value entered). If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputDate function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Date expression displayed in the date control as the default response if no other input is provided. If you omit default, the date control is displayed empty.
See also Scripted Form
InputDate
method and Input Grid
InputDate
method.
See Also
Input Functions

---

## InputDeliveryAddress - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputDeliveryAddressFunction.htm

InputDeliveryAddress - MaxBasic Function
InputDeliveryAddress(CustomerCode: String, Prompt: String[, Title: String, DefaultDeliveryCode: String, Filter: String, FilterButtonVisible: Boolean]): String
Displays a prompt in a dialog box, User can enter or select a valid Delivery Address for a Customer, and returns the Delivery Code.
Note, if User clicks
OK
or presses
Enter
InputDeliveryAddress function returns the Delivery Code. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputDeliveryAddress function syntax has these named arguments:
Parameter
Description
Customer Code
Required. The Customer Code to select the address for.
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default Delivery Code
Optional. String expression with the default Delivery Code. If you omit Default Delivery Code, the control will display empty.
Filter
Optional. String containing a filter value to apply to delivery addresses available.
Filter Button Visible
Optional, defaults to
False
. Determines whether to display the Filter button.
See also Scripted Form
InputDeliveryAddress
method.
See Also
Input Functions

---

## InputEnum - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputEnumFunction.htm

InputEnum - MaxBasic Function
InputEnum(Domain: String, Prompt: String[, Title: String, Default: String, AllowEmpty: Boolean]): String
Displays a prompt in a dialog box, User must choose a valid enum (Enumerated Type) from a Domain, returns the selected enum.
Note, if User clicks
OK
or presses
Enter
InputEnum function returns the enum value. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputEnum function syntax has these named arguments:
Parameter
Description
Domain
Required. A valid
Domain Definition
.
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Enum value displayed in the control as the default response if no other input is provided. If you omit default, the control will display empty.
Allow Empty
Optional, defaults to
True.
Determines if the Lookup can be cleared after a value has been selected.
See also Scripted Form
InputEnum
method.
See Also
Input Functions

---

## InputFileOpen - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputFileOpenFunction.htm

InputFileOpen - MaxBasic Function
InputFileOpen(Prompt: String[, Title: String, InitialDirectory: String, Filter: String]): String
Displays a prompt in a dialog box, User must input or select a valid file name, and returns the file name as a string.
InputFileOpen function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Initial Directory
Optional. The initial directory the file will load from, for example, "C:\".
Filter
Optional. The list of file filters, separated by pipes, for example, "Text Files(*.txt)|*.txt".
See also Scripted Form
InputFileOpen
method.
See Also
Input Functions

---

## InputFileSave - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputFileSaveFunction.htm

InputFileSave - MaxBasic Function
InputFileSave(Prompt: String[, Title: String, InitialDirectory: String, Filter: String, DefaultExtension: String]): String
Displays a prompt in a dialog box, User must input or select a valid file name, and returns the file name as a string.
InputFileSave function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Initial Directory
Optional. The initial directory the Windows file select dialog will open in, for example, "C:\Data".
Filter
Optional. The list of file filters for the Save as Type selection, separated by pipes, for example, "Text Files(*.txt)|*.txt|All Files|*.*".
Note that the first extension in the list is applied as the default extension if one is not specified.
Default Extension
Optional. If specified, then this extension gets added to the end of the file name which is returned if an extension is not specified.
See also Scripted Form
InputFileSave
method.
For example:
Dim x as string
x = inputfilesave("Save File","Select file","C:\Data","Excel Files|*.xlsx;*.xls;*.xlsm|All Files|*.*", ".xlsx")
print x
See Also
Input Functions

---

## InputFolder - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputFolderFunction.htm

InputFolder - MaxBasic Function
InputFolder(Prompt: String[, Title: String, InitialDirectory: String]): String
Displays a prompt in a dialog box, User must input or select a valid folder name, and returns the folder name as a string.
InputFolder function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Initial Directory
Optional. The initial directory the folder will load from, for example, "C:\".
See also Scripted Form
InputFolder
method.
See Also
Input Functions

---

## InputInteger - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputIntegerFunction.htm

InputInteger - MaxBasic Function
InputInteger(Prompt: String[, Title: String, Default: String]): Number
Displays a prompt in a dialog box, User must input a valid integer or click a button, returns an integer value from the integer spin edit control.
Notes: If User clicks
OK
or presses
Enter
, InputInteger function returns what is in the integer control. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
The InputInteger function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Integer value displayed in the integer spin edit control as the default response if no other input is provided. If you omit default, the value is
zero
.
See also Scripted Form
InputInteger
method and Input Grid
InputInteger
method.
See Also
Input Functions

---

## InputList - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputListFunction.htm

InputList - MaxBasic Function
InputList(Prompt: String, [Title: String, DefaultItem: String AllowEmpty: Boolean, UseExactMatch: Boolean, Item1, ... ]): String
Prompts the User to select one item from a list of items from a combo box. Returns the item selected or Null if none selected.
The InputList function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box. The maximum length of prompt is approximately 40 characters, depending on the width of the characters used.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default Item
Optional, the item to default the input list to. Will be displayed selected in the Input List.
Allow Empty
Optional, defaults to
true
. The combo box can be emptied after a value has been selected.
Use Exact Match
Optional, defaults to
true.
The combo box can accept and return values that are not in the list.
Item1 to Item n
The list values for the combo box.
See also Scripted Form
InputList
method and Input Grid
InputList
method.
See Also
Input Functions

---

## InputMemo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputMemoFunction.htm

InputMemo - MaxBasic Function
InputMemo(Prompt: String[, Title: String, Default: String, Maxlength: Number]): String
Displays a message, User can input a block of text, returns text entered.
Notes: If User clicks
OK
or presses
Enter
, InputMemo function returns what is in the memo control. If User clicks
Cancel
or presses
Esc,
function returns
Null
.
InputMemo function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message.
Title
Optional. String expression displayed in the title bar. If you omit title, the application name is placed in the title bar.
Default
Optional. String expression displayed in the memo control as the default response if no other input is provided. If you omit default, the value is "".
Max Length
Optional. Set the maximum number of characters that can be entered in the memo.
See also Scripted Form
InputMemo
method.
See Also
Input Functions

---

## InputNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputNumberFunction.htm

InputNumber - MaxBasic Function
InputNumber(Prompt: String[, Title: String, Default: String,Domain: String, CurrencyCode: String]): Number
Displays a message, User must input a valid number or click a button, returns a number from the number control.
Notes: If User clicks
OK
or presses
Enter
, InputNumber function returns what is in the number control. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputNumber function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message.
Title
Optional. String expression displayed in the title bar. If you omit title, the application name is placed in the title bar.
Default
Optional. Number value displayed in the number control as the default response if no other input is provided. If you omit default, the value is
zero
.
Domain
Optional, Domain to be applied to the number. Valid domains are listed in
Domains
.
Currency Code
Optional. String expression representing the Currency Code for the number.
Domain
must be set to either
Amount
,
Price
,
Cost Price
or
Sell Price
.
Warning: If you select a Domain with no decimal places, the decimal place will be ignored by the system. For example, if a User enters 4.55 in a field with no decimal places, the system will return 455.
See also Scripted Form
InputNumber
method and Input Grid
InputNumber
method.
See Also
Input Functions

---

## InputPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputPeriodFunction.htm

InputPeriod - MaxBasic Function
InputPeriod(Prompt: String[, Title: String, Default: String, PeriodFrom: Number, PeriodTo: Number, Financial: Boolean]): Number
Displays a message, User must select a financial period or click a button, returns a number containing the PeriodID for the selected period.
InputPeriod function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as a message.
Title
Optional. String expression displayed in the title bar. If you omit title, the application name is placed in the title bar.
Default
Optional period ID. Period displayed in the look-up control as the default response if no other input is provided. If you omit default, the look-up control is displayed empty.
Period From
Optional period ID to restrict available periods. First period available in the look-up control.
PeriodTo
Optional period ID to restrict available periods. Last period available in the look-up control.
Financial
Optional, defaults to True. Determines if only Financial periods are included. If True, restricts periods to Financial periods only. If False, includes Financial and Adjustment periods.
See also Scripted Form
InputPeriod
method and Input Grid
InputPeriod
method.
See Also
Input Functions

---

## InputPrinter - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputPrinterFunction.htm

InputPrinter - MaxBasic Function
InputPrinter(Prompt: String[, Title: String, Default: String, AllowEmpty: Boolean]): String
Displays a message, User must select a printer from the list or click a button, returns a string containing the printer name for the selected printer.
InputPrinter function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Printer name displayed in the look-up control as the default response if no other input is provided. If you omit default, the default printer for Accredo is displayed.
Allow Empty
Optional, defaults to
False
. Determines if the Lookup can be cleared after a value has been selected.
See also Scripted Form
InputPrinter
method.
See Also
Input Functions

---

## InputQuery - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputQueryFunction.htm

InputQuery - MaxBasic Function
InputQuery(Prompt: String[, Title: String, Default: Boolean, Label1: String, Label2: String, Glyph: Boolean]): Boolean
Displays a prompt in a query box, User must click a button, returns a boolean value -
True
if left button pressed,
False
if right button pressed.
Notes: If the User presses
Enter
, InputQuery function returns the selected button. If User presses
Esc
, function returns
False
.
InputQuery function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Sets focus to the specified button. If you omit default, the default is
True
.
Label1
Optional. String expression displayed in the left button. If you omit label1, the default is '
Yes
'.
Label2
Optional. String expression displayed in the right button. If you omit label2, the default is '
No
'.
Glyph
Optional. Allows suppression of glyphs on buttons. Pass
True
to suppress glyph, the default is
False
.
See Also
Input Functions

---

## InputTime - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InputTimeFunction.htm

InputTime - MaxBasic Function
InputTime(Prompt: String[, Title: String, Default: Time]): String
Displays a prompt in a dialog box, User must input a valid time or select a time from the dropdown, and returns a time.
Note, if User clicks
OK
or presses
Enter
InputTime function returns what is in the time control. If User clicks
Cancel
or presses
Esc
, function returns
Null
.
InputDate function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title, the application name is placed in the title bar.
Default
Optional. Time expression displayed in the time control as the default response if no other input is provided. If you omit default, the time control is displayed empty.
See also Scripted Form
InputTime
method.
See Also
Input Functions

---

## InStr - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InStrFunction.htm

InStr - MaxBasic Function
InStr(String1: String, String2: String): Number
String position. Returns the position of the start of the first instance of String2 contained within String1. If String2 is not found in String1 or String1 is zero length, 0 is returned. If either argument is null, null is returned.
Instr function syntax has these named arguments:
Parameter
Description
String 1
Required. String to be searched for String 2.
String 2
Required. String to search for in String 1.
Sample code:
Print Instr("caterpillar", "pill")
Returns:
6
See Also
String Functions

---

## InstrRev - MaxBasic Function

Source: https://accredo.co.nz/webhelp/InstrRevFunction.htm

InstrRev - MaxBasic Function
InstrRev(String1: String, String2: String): Number
String position from end. Returns the position of the start of the last instance of String2 contained within String1. If String2 is not found in String1 or String1 is zero length, 0 is returned. If either argument is null, null is returned.
InstrRev function syntax has these named arguments:
Parameter
Description
String 1
Required. String to be searched for String 2.
String 2
Required. String to search for in String 1.
For example:
InstrRev("moonbeam", "beam")
Returns:
5
See Also
String Functions

---

## Int - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IntFunction.htm

Int - MaxBasic Function
Int(Number: Number): Integer
Returns the integer portion of Number. Negative numbers round down (away from 0).
Int function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be evaluated.
See Also
Number Functions

---

## IsArray - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsArrayFunction.htm

IsArray - MaxBasic Function
IsArray(Expression: Variant): Boolean
Returns
True
if the Expression is of type array, or is a JSON array, otherwise returns
False
.
This can be used with the
ParseJSON
function.
IsArray function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated.
See Also
Boolean Functions

---

## IsBatch - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsBatchFunction.htm

IsBatch - MaxBasic Function
IsBatch: Boolean
Returns True if the current email is a batch email, returns False otherwise.
Available in Email Designers.
See Also
Report Functions

---

## IsBoolean - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsBooleanFunction.htm

IsBoolean - MaxBasic Function
IsBoolean(Expression: Variant): Boolean
Returns
True
if the Expression is of type Boolean, otherwise returns
False
.
IsBoolean function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated.
See Also
Boolean Functions

---

## IsCompanyLocked - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IcCompanyLockedFunction.htm

IsCompanyLocked - MaxBasic Function
IsCompanyLocked : Boolean
Returns
True
if company is locked,
False
otherwise.

---

## IsCurrency - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsCurrencyFunction.htm

IsCurrency - MaxBasic Function
IsCurrency(Number: Number): Boolean
Returns true for currency values.
IsCurrency function syntax has these named arguments:
Parameter
Description
Number
Required. The number to validate as a currency value.
See Also
Foreign Exchange Functions

---

## IsDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsDateFunction.htm

IsDate - MaxBasic Function
IsDate(Expression: Variant): Boolean
Returns
True
if the Expression is of type Date, otherwise returns
False
.
IsDate function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated.
See Also
Boolean Functions

---

## IsEmpty - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsEmptyFunction.htm

IsEmpty - MaxBasic Function
IsEmpty(Expression: Variant): Boolean
Returns
True
if the Expression is an empty variable. This returns
True
if the variable has not been initialised or has been set to Empty, otherwise returns
False
.
IsEmpty function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated as Empty.
See Also
Boolean Functions

---

## IsInteractive - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsInteractiveFunction.htm

IsInteractive - MaxBasic Function
IsInteractive: Boolean
Is Interactive function returns
True
if the company is in Interactive mode, otherwise returns
False
.
See
Company IsInteractive Setting
.

---

## IsNull - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsNullFunction.htm

IsNull - MaxBasic Function
IsNull(Expression: Variant): Boolean
Returns
True
if the Expression has a Null value (contains no valid data), otherwise returns
False
.
IsNull function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated as Null.
See Also
Boolean Functions

---

## IsNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsNumberFunction.htm

IsNumber - MaxBasic Function
IsNumber(Expression: Variant): Boolean
Returns
True
if the Expression is of type Number, otherwise returns
False
.
IsNumber function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated.
See Also
Boolean Functions

---

## IsObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsObjectFunction.htm

IsObject - MaxBasic Function
IsObject(Identifier: Variant): Boolean
Returns
True
if the Identifier represents an object variable, otherwise returns
False
.
IsObject function syntax has these named arguments:
Parameter
Description
Identifier
Required. Identifier to be evaluated as an object variable.
See Also
Boolean Functions

---

## IsString - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsStringFunction.htm

IsString - MaxBasic Function
IsString(Expression: Variant): Boolean
Returns
True
if the Expression is of type String, otherwise returns
False
.
IsString function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be evaluated.
See Also
Boolean Functions

---

## IsWebService - MaxBasic Function

Source: https://accredo.co.nz/webhelp/IsWebServiceFunction.htm

IsWebService - MaxBasic Function
IsWebService: Boolean
IsWebService function returns
True
if the company is in WebService mode, otherwise returns
False
.

---

## JCEndOfPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JCEndOfPeriodFunction.htm

JCEndOfPeriod - MaxBasic Function
JCEndOfPeriod
Performs an End Of Period on JC.
JCEndOfPeriod function returns:
Return Type
Description
Boolean
True if successful.
See Also
Accounting Functions

---

## Join - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JoinFunction.htm

Join - MaxBasic Function
Join(StringList: Object, Delimiter: String): String
Given a
StringList object
and a Delimiter, returns a delimited string.
Join function syntax has these named arguments:
Parameter
Description
StringList
Required. A list of strings to be delimited.
Delimiter
Required. String to be used as the delimiter.
Sample code:
Dim SL as Object
SL = CreateObject("Accredo.StringList")
s = "1,2,3,4"
SL.CommaText = s
t = Join(SL, "|")
Print t
Returns:
1|2|3|4
See Also
String Functions

---

## JoinTransaction - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JoinTransactionFunction.htm

JoinTransaction - MaxBasic Function
JoinTransaction(MemTable: MemoryTable)
Allows temporary negative record numbers generated from AutoInc fields (such as Surrogate IDs) inside a database transaction to be updated in memory tables when the transaction is committed.
JoinTransaction function syntax has these named arguments:
Parameter
Description
MemTable
Required. The Memory table to update.
See Also
Script Functions

---

## JSONClone - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONCloneFunction.htm

JSONClone - MaxBasic Function
JSONClone(JSONObject: Object): Object
Takes a JSON Object and returns a new JSON Object cloned from the original object.
JSONClone function has these named arguments:
Parameter
Description
JSON Object
Required. A JSON Object to clone.
The following sample code creates a JSON Object called JSON1 based on IN Invoice Data, the clones the object as JSON2.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON1 as Object
JSON1 = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim JSON2 as Object
JSON2 = Clone(JSON1)
See Also
Web Functions

---

## JSONCreateArray - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONCreateArrayFunction.htm

JSONCreateArray - MaxBasic Function
JSONCreateArray([RootObject: Object, ElementName: String]): Object
Creates a JSON Array rooted to the RootObject, with elements named in the Element Name string.
JSONCreateArray function has these named arguments:
Parameter
Description
Root Object
Optional. The object to root the JSON Array to.
Element Name
Required if Root Object specified. A semi-colon delimited string containing the elements to be included.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON Array containing the Customer Code and Document No.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim obj as Object
obj = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
See Also
Web Functions

---

## JSONCreateObject - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONCreateObjectFunction.htm

JSONCreateObject - MaxBasic Function
JSONCreateObject[(RootObject: Object, ElementName: String)]: Object
Creates a JSON Object. If no parameters are passed, creates am empty JSON object. If parameters are passed, creates a nested JSON Object with the elements in the Element Name string.
JSONCreateObject function has these named arguments:
Parameter
Description
Root Object
Optional. The object to create a nested JSON Object from. Required if Element Name is passed in.
Element Name
Optional. A semi-colon delimited string containing the elements to be included. Required if the Root Object is passed in.
The following sample code creates and empty JSON object:
Dim obj1 as Object
obj1 = JSONCreateObject
The following sample code creates a JSON object based on IN Invoice Data, then creates a nested JSON Object called obj2 containing the Customer Code and Document No.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim obj2 as Object
obj2 = JSONCreateObject(JSON, "CustomerCode;DocumentNo")
See Also
Web Functions

---

## JSONDelete - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONDeleteFunction.htm

JSONDelete - MaxBasic Function
JSONDelete(JSONObject: Object, ElementName: String)
Takes a JSON Object and deletes the element named in ElementName.
JSONDelete function has these named arguments:
Parameter
Description
JSON Object
Required. The JSON Object to modify.
Element Name
Required. The name of the element to delete from the JSON Object.
The following sample code creates a JSON object based on IN Invoice Data, then deletes the Document No element.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
JSONDelete(JSON, "DocumentNo")
See Also
Web Functions

---

## JSONGetKeys - MaxBasic function

Source: https://accredo.co.nz/webhelp/JSONGetKeysFunction.htm

JSONGetKeys - MaxBasic function
JSONGetKeys(JSONObject: Object): Stringlist
Takes a JSON Object and returns a StringList containing the top level key name of the object.
JSONGetKeys function has these named arguments:
Parameter
Description
JSON Object
Required. A JSON Object to return keys for.
Sample code:
const Filename = "C:\data\Invoices.json"
If not FileExists(Filename) Then Error("File " & FileName & " not found")
Dim Invoices as Object
Invoices = ParseJSONFromFile(FileName)
Dim History as Object
History = Invoices.InvoiceHistory
Dim Keys as Object
Keys = JSONGetKeys(History)
Print "Total number of Keys: " & Keys.Count
Print "Keys:"
for each key in Keys
Print key
next

---

## JSONLength - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONLengthFunction.htm

JSONLength - MaxBasic Function
JSONLength(JSONArray: Object): Number
Returns the length of a JSON Array.
JSONLength function has these named arguments:
Parameter
Description
JSON Array
Required. The JSON Array to return the length of.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON array, then returns the length of the JSON array.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim Json Array as Object
JsonArray = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
Dim ArrayLength as Number
ArrayLength = JSONLength(JsonArray)
See Also
Web Functions

---

## JSONPop - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONPopFunction.htm

JSONPop - MaxBasic Function
JSONPop(JSONArray: Object): Object
Takes a JSON Array and removes and returns the last element of the array.
JSONPop function has these named arguments:
Parameter
Description
JSON Array
Required. A JSON Object to remove and return the last element of.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON Array. It adds two elements to the JSON Array, then uses the JSONPop function to remove the last Element and return it as JSON2. It then prints the JSON2 object, and the JSONArray.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim JsonArray as Object
JsonArray = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
JSONPush(JsonArray,"ASHENG;1")
JSONPush(JsonArray"BROWN;2")
Dim JSON2 as Object
JSON2 = JSONPop(JsonArray)
Print JSONStringify(JSON2)
Print JSONStringify(JsonArray)
See Also
Web Functions

---

## JSONPush - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONPushFunction.htm

JSONPush - MaxBasic Function
JSONPush(JSONArray: Object, Value: Variant): Number
Adds the Value to a JSON Array and returns the new length of the JSON array.
JSONPush function has these named arguments:
Parameter
Description
JSON Array
Required. A JSON Array to add the Value to.
Value
Required. The Value to be added to the JSON Array.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON Array. It uses the JSONPush function to add two elements to the JSON Array, then prints the JSONArray.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim JsonArray as Object
JsonArray = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
JSONPush(JsonArray,"ASHENG;1")
JSONPush(JsonArray"BROWN;2")
Print JSONStringify(JsonArray)
See Also
Web Functions

---

## JSONSetPropertyValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONSetPropertyValueFunction.htm

JSONSetPropertyValue - MaxBasic Function
JSONSetPropertyValue(JSONObject: Object, PropertyName: String, Value: Variant)
Takes a JSON Object and dynamically sets a JSON property value.
JSONSetPropertyValue function has these named arguments:
Parameter
Description
JSON Object
Required. A JSON Object to set a property for.
Property Name
Required. The property name.
Value
The value for the property. Must be a valid JSON type.
Example use:
objJSON = ParseJSON("{}")
objJSON.CustomerName = "Test Name"
objJSON["Description"] = "This is a description added by array notation"
JSONSetPropertyValue(objJSON,"Description2", "This is a description added by function")
BrowseDataSet(objJSON)
Print objJSON["CustomerName"]
Print objJSON["Description"]
Print objJSON["Description2"]

---

## JSONShift - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONShiftFunction.htm

JSONShift - MaxBasic Function
JSONShift(JSONArray: Object): Object
Takes a JSON Array and removes and returns the first element of the array.
JSONShift function has these named arguments:
Parameter
Description
JSON Array
Required. The JSON Array to remove and return the first element of.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON Array. It adds two elements to the JSON Array, then uses the JSONShift function to remove the first Element and return it as JSON2. It then prints the JSON2 object, and the JSONArray.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim JsonArray as Object
JsonArray = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
JSONPush(JsonArray,"ASHENG;1")
JSONPush(JsonArray"BROWN;2")
Dim JSON2 as Object
JSON2 = JSONShift(JSONArray)
Print JSONStringify(JSON2)
Print JSONStringify(JsonArray)
See Also
Web Functions

---

## JSONSplice - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONSpliceFunction.htm

JSONSplice - MaxBasic Function
JSONSplice(JSONArray: Object, Start: Number[, DeleteCount: Number, AddItem1: Variant, AddItem2: Variant, ..., AddItemN: Variant]): Object
Takes a JSON Array and adds or removes existing elements. Returns a JSON Array containing the deleted items.
The Start number is the Index at which to start changing the JSON Array. If the Start is negative, the position will begin from the end of the JSON Array.
The DeleteCount number specifies the number if items to be deleted. If the DeleteCount is not included, or is larger than the Array Length minus the Start, then all elements from the start to the end of the array will be deleted. If the DeleteCount is zero or is negative, no elements will be deleted.
If any number of AddItem parameters are included, the AddItem items will be added to the JSON Array.
JSONSplice function has these named arguments:
Parameter
Description
JSON Array
Required. A JSON Array to be modified.
Start
Required. The Index position in the JSON Array to start modifications.
DeleteCount
Optional. The number of items to be deleted from the JSON Array. If the DeleteCount is not included, or is larger than the Array Length minus the Start, then all elements from the start to the end of the array will be deleted. If the DeleteCount is zero or is negative, no elements will be deleted.
AddItem1, AddItem2,  ... AddItemN
Optional. Items included as parameters after the DeleteCount parameter will be added to the JSON Array.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON Array. It adds three elements to the JSON Array, then uses the JSONSplice function to remove the second Element and return it as JSON2, and add two more elements. It then prints the JSON2 object, and the JSONArray.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim JsonArray as Object
JsonArray = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
JSONPush(JsonArray,"ASHENG;1")
JSONPush(JsonArray"BROWN;2")
JSONPush(JsonArray"CHESTER;3")
Dim JSON2 as Object
JSON2 = JSONSplice(JsonArray, 1, 1, "DUGG:4", "FINE:5")
Print JSONStringify(JSON2)
Print JSONStringify(JsonArray)
Sample code:
JSONSplice(JSON1, 2, 1, "NewItem")
This will replace the Item at Position 2 of the JSON Array with "NewItem".
See Also
Web Functions

---

## JSONStringify - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONStringifyFunction.htm

JSONStringify - MaxBasic Function
JSONStringify(JSONObject: Object): String
Takes a JSON Object and returns the object represented as a formatted JSON string.
JSONStringify function has these named arguments:
Parameter
Description
JSON Object
Required. A JSON Object to represent as a formatted string.
The following sample code creates a JSON object based on IN Invoice Data, then uses the JSONStringify to print the formatted JSON object.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Print JSONStringify(JSON)
See Also
Web Functions

---

## JSONToString - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONToStringFunction.htm

JSONToString - MaxBasic Function
JSONToString(JSONObject: Object): String
Takes a JSON Object and returns the object represented as a raw JSON string.
JSONToString function has these named arguments:
Parameter
Description
JSON Object
Required. A JSON Object to represent as a raw string.
The following sample code creates a JSON object based on IN Invoice Data, then uses the JSONToString to print the raw JSON object.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Print JSONToString(JSON)
See Also
Web Functions

---

## JSONUnshift - MaxBasic Function

Source: https://accredo.co.nz/webhelp/JSONUnshiftFunction.htm

JSONUnshift - MaxBasic Function
JSONUnShift(JSONArray: Object, Value: Variant): Number
Takes a JSON Array and adds the Value item to the beginning of the Array, then returns the Array Length.
JSONUnShift function has these named arguments:
Parameter
Description
JSON Array
Required. The JSON Array to add to.
Value
Required. The Value to be added to the start of the JSON Array.
The following sample code creates a JSON object based on IN Invoice Data, then creates a JSON Array. It adds two elements to the JSON Array, then uses the JSONUnShift function to add a new element to the beginning of the array, then prints the ArrayLength returned.
Sample code:
Dim datINInvoice as Object
datINInvoice = CreateObject("Accredo.INInvoiceData")
Dim JSON as Object
JSON = BuildJSON(datINInvoice, "CustomerCode;DocumentNo;DocumentID;Line", "Charge;Banking")
Dim JsonArray as Object
JsonArray = JSONCreateArray(JSON, "CustomerCode;DocumentNo")
JSONPush(JsonArray,"ASHENG;1")
JSONPush(JsonArray"BROWN;2")
Dim ArrayLength as Number
ArrayLength = JSONUnShift(JsonArray, "Chester:3")
Print ArrayLength
See Also
Web Functions

---

## KeepChars - MaxBasic Function

Source: https://accredo.co.nz/webhelp/KeepCharsFunction.htm

KeepChars - MaxBasic Function
KeepChars(String1: String, String2: String): String
Removes all occurrences of any character not contained in String2 from String 1.
KeepChars function syntax has these named arguments:
Parameter
Description
String1
Required. The String to be edited.
String2
Required. The string containing the characters to be kept in String1.
Sample code:
Print KeepChars("abcedfghijklmnopqrstuvwxyz","face")
Returns:
acef
See Also
String Functions

---

## LabelCopies - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LabelCopiesFunction.htm

LabelCopies - MaxBasic Function
LabelCopies: Number
Returns total number of labels being printed for the currently printing label.
Available in Label Designer script editors.
See Also
Report Functions

---

## LastAvailablePeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LastAvailablePeriodFunction.htm

LastAvailablePeriod - MaxBasic Function
LastAvailablePeriod(Module: String): Number
Returns the last available period for the Module Code specified in Module (not limited by User).
LastAvailablePeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the last available period for.
See Also
Period Functions

---

## LastInYear - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LastInYearFunction.htm

LastInYear - MaxBasic Function
LastInYear(PeriodID: Number[, Financial: Boolean]): Number
Returns the last period in the year that contains PeriodID. If the optional boolean parameter Financial is True then only financial periods are considered (adjustment periods are ignored).
It is also possible to call this function passing a year number in place of PeriodID
.
LastInYear function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to be used to find the last in the year. Can also be passed a Year number.
Financial
Optional. If
True
, only financial periods are considered. If
False
, all periods are considered.
See Also
Period Functions

---

## LastPage - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LastPageFunction.htm

LastPage - MaxBasic Function
LastPage: Boolean
Returns
True
if the current page is the final page of the report and the function is in a Summary, PageFooter or Overmark band, that is, one that can determine that all detail bands have been printed, or
False
.
See Also
Report Functions

---

## LastPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LastPeriodFunction.htm

LastPeriod - MaxBasic Function
LastPeriod[(Financial: Boolean)]: Number
Returns the last period in the Company. If the optional boolean parameter Financial is True then only financial periods are considered (adjustment periods are ignored).
LastPeriod function syntax has these named arguments:
Parameter
Description
Financial
Optional. If
True
, only financial periods are considered. If
False
, all periods are considered.
See Also
Period Functions

---

## LastTaxDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LastTaxDateFunction.htm

LastTaxDate - MaxBasic Function
LastTaxDate[(TaxRegime: String)]: Date
Last Tax Date function returns the last tax date for a given Tax Regime. If no Tax Regime is given, the last tax date for the Base Tax Regime is returned.
LastTaxDate function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the last tax date for. If not supplied, the Base Tax Regime is used.
See Also
GST Functions

---

## LastUserPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LastUserPeriodFunction.htm

LastUserPeriod - MaxBasic Function
LastUserPeriod(Module: String [,User: String]): Number
Returns the last period which the User may post transactions into for the specified module. If the User parameter is not specified, the User is the logged in User.
LastUserPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the last user period for.
User
Optional. User to find the last period for. Defaults to the User currently logged in.
See also the SQL
LastUserPeriod
function and the Web Services
LastUserPeriod
function.
See Also
Period Functions

---

## LBound - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LBoundFunction.htm

LBound - MaxBasic Function
LBound (Arrayname: String): Number
Returns a number containing the smallest available subscript for the dimension of an array or JSON array.
The LBound function is used with the
UBound
function to determine the size of an array. Use the UBound function to find the upper limit of an array dimension.
LBound function syntax has these named arguments:
Parameter
Description
Array Name
Required. Name of the array variable; follows standard variable naming conventions.
See Also
Array Functions

---

## Left - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LeftFunction.htm

Left - MaxBasic Function
Left(String: String, Length: Number): String
Left string. Returns the leftmost Length characters of String. If String contains less than Length characters, the entire string is returned.
Left function syntax has these named arguments:
Parameter
Description
String
Required. String to return the leftmost characters for.
Length
Required. The length of the string to be returned. If the String is shorter than Length, the entire string is returned.
For example:
Left("gladiator", 4)
Returns:
glad
See Also
String Functions

---

## Len - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LenFunction.htm

Len - MaxBasic Function
Len(String: String): Number
String length. Returns a number containing the length of String.
Len function syntax has these named arguments:
Parameter
Description
String
Required. String to return the length of.
Sample code:
Print Len("Antidisestablishmentarianism")
Returns:
28
See Also
String Functions

---

## LineNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LineNumberFunction.htm

LineNumber - MaxBasic Function
LineNumber: Number
Returns the line number in the executing script, useful for inserting debugging messages in a script.
See Also
Script Functions

---

## LineType - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LineTypeFunction.htm

LineType - MaxBasic Function
LineType([Offset: Number]): Variant
Returns the value of the offset field in the current line of the import file.
LineType function syntax has these named arguments:
Parameter
Description
Offset
Optional.  Offset is 1 based i.e 1 means the first field and is the default it not specified. Passing in a value greater than available fields will return empty string.
See Also
Import Functions

---

## LinkAccountFiles - MaxBasic function

Source: https://accredo.co.nz/webhelp/LinkAccountFilesFunction.htm

LinkAccountFiles - MaxBasic function
LinkAccountFiles : Object
LinkAccountFiles function returns a
StringList Object
containing a string list of the tables that support links.
Sample code:
Dim List as Object
List = LinkAccountFiles
For I = 0 to List.Count - 1
Print List[I]
Next I
Print ""
Print "Total: " & List.Count

---

## LoadConfig - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LoadConfigFunction.htm

LoadConfig - MaxBasic Function
LoadConfig(FileName: String)
Load Config function loads the file specified, so
GetConfigValue
can read the variables inside. Must be used in conjunction with
GetConfigValue
.
LoadConfig function syntax has these named arguments:
Parameter
Description
File Name
Required. The file to be loaded.
See Also
Environment Functions

---

## LocalDateTimeToUTC - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LocalDateTimeToUTCFunction.htm

LocalDateTimeToUTC - MaxBasic Function
LocalDateTimeToUTC(LocalTime: DateTime): DateTime
Converts a local timezone datetime to UTC (Coordinated Universal Time).
LocalDateTimeToUTC function syntax has these named arguments:
Parameter
Description
LocalTime
Required. The datetime value to convert to UTC.
Sample code:
Print FormatDateTime(LocalDateTimeToUTC(#1/1/2025 2.26 pm#))

---

## LockCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LockCompanyFunction.htm

LockCompany - MaxBasic Function
LockCompany([Reason: String])
Initiates a
Forced User Exit
then Locks the open Company for single user access if executed by a User with the
Force User Exit
permission. Can also be triggered by selecting
Lock Company
from the File Menu .
LockCompany function syntax has these named arguments:
Parameter
Description
Reason
Optional. The reason the company is being locked.
See Also
Company Functions

---

## LoggedIn - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LoggedInFunction.htm

LoggedIn - MaxBasic Function
LoggedIn: Boolean
Returns
True
if there is a User currently logged into a Company, otherwise returns
False
.
See Also
User Functions

---

## Login - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LoginFunction.htm

Login - MaxBasic Function
Login(CompanyCode: String, UserName: String, Password: String[, ForceConversion: Boolean]): Boolean or
Login(CompanyName: String, UserName: String, Password: String[, ForceConversion: Boolean]): Boolean
Logs in to a specified Company using the User Name and Password provided. Usually used in
Command Line scripts
or for login via
COM
. Returns
True
if the login was successful, or
False
if the login was unsuccessful.
You can optionally force a data conversion by setting
Force Conversion
to
True
.
This defaults to
False
and is only applicable to Command Line scripting. If this is set to
True
, and data conversion from an earlier version is required, data conversion will proceed automatically prior to login.
Login function syntax has these named arguments:
Parameter
Description
Company Code / Company Name
Required. The company to log in to.
User Name
Required. The User to log into the company.
Password
Required. The password for the User account.
Force Conversion
Optional. If
True
, automatically performs data conversion. Defaults to
False
.
See Also
User Functions

---

## LoginPrompt - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LoginPromptFunction.htm

LoginPrompt - MaxBasic Function
LoginPrompt(ForceLogin: Boolean): Boolean
Displays a login prompt. ForceBoolean is optional, and default to the company
Force Login Default
setting. When ForceBoolean is true and there is a logged in user, the logged in user is forced to login again. Returns
True
if the login was successful, or
False
if the login was cancelled.
LoginPrompt function syntax has these named arguments:
Parameter
Description
Force Login
Optional. Defaults to the company Force Login Default setting. When True, the logged in user is forced to login again.
See Also
User Functions

---

## LoginUserCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LoginUserCodeFunction.htm

LoginUserCode - MaxBasic Function
LoginUserCode: String
Login User Code function returns the logged in User code.
See Also
User Functions

---

## Logout - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LogoutFunction.htm

Logout - MaxBasic Function
Logout
Logs out a Company. Do not run from a script editor while logged in.
See Also
User Functions

---

## Lower - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LowerFunction.htm

Lower - MaxBasic Function
Lower(String: String): String
Returns String in lower case.
Lower function syntax has these named arguments:
Parameter
Description
String
Required. String to return in lower case.
For example:
Lower("DO NOT SHOUT")
Returns:
do not shout
See Also
String Functions

---

## LPad - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LPadFunction.htm

LPad - MaxBasic Function
LPad(String1: String, Number: Number[, String2: String]): String
Left pad string. Returns a string with exactly Number of characters. If String2 is specified, the pad character is the first character of String2, otherwise the pad character is a space. The result is String1 padded on the left with the pad character to produce a string of exactly Number characters. If the length of String1 is greater than number, then the rightmost Number characters of String1 are returned.
LPad function syntax has these named arguments:
Parameter
Description
String1
Required. String to be padded with additional characters.
Number
Required. The length of the string to be returned.
String2
Optional. If supplied, the first character of String2 will be used to pad String1.
For example:
LPad("12345", 8, "abc")
Returns:
aaa12345
See Also
String Functions

---

## LTrim - MaxBasic Function

Source: https://accredo.co.nz/webhelp/LTrimFunction.htm

LTrim - MaxBasic Function
LTrim(String: String): String
Left trim String. Returns String with leading spaces removed.
LTrim function syntax has these named arguments:
Parameter
Description
String
Required. String to be trimmed on the left.
Sample code:
Print LTrim("   banana")
Returns:
banana
See Also
String Functions

---

## MakeCurrency - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MakeCurrencyFunction.htm

MakeCurrency - MaxBasic Function
MakeCurrency(Amount: Number,CurrencyCode: String): Number
Passed an Amount and a currency code, returns a currency value.
MakeCurrency function syntax has these named arguments:
Parameter
Description
Amount
Required. The amount to make into a currency value.
Currency Code
Required. The currency code to convert to.
See Also
Foreign Exchange Functions

---

## MakeDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MakeDateFunction.htm

MakeDate - MaxBasic Function
MakeDate(Year: Number, Month: Number, Day: Number): Date
Returns a valid date with the Year, Month and Day provided.
MakeDate function syntax has these named arguments:
Parameter
Description
Year
Required. The year of the date. Must be between 1000 and 9999.
Month
Required. The month of the date. If this is negative, a wrap around will result.
Day
Required. The day of the date. Must be a positive integer, if a day greater than number of days in the month is passed the nearest day is returned.
Sample code:
lDate = MakeDate(2019, 2, 15)
Print "Date = " & FormatDateTime(lDate, "dd/mm/yyyy")
See Also
Date Functions

---

## MakePeriodID - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MakePeriodIDFunction.htm

MakePeriodID - MaxBasic Function
MakePeriodID(YearNo: Number, PeriodNo: Number): Number
Create a period ID from the given Year and Period numbers. Returns zero if YearNo or PeriodNo are outside valid range.
MakePeriodID function syntax has these named arguments:
Parameter
Description
YearNo
Required. YearNo to use to create the Period ID. Valid range integers 1-99.
PeriodNo
Required. PeriodNo to use to create the Period ID. Valid range integers 1-99.
For example:
MakePeriodID(2,1)
Returns: 201.
See Also
Period Functions

---

## MakePhoneCall - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MakePhoneCallFunction.htm

MakePhoneCall - MaxBasic Function
MakePhoneCall(PhoneNumber: String)
Make Phone Call function initiates a phone call using
ActivePhone
for
TAPI
.
MakePhoneCall function syntax has these named arguments:
Parameter
Description
Phone Number
Required. The phone number to be used.
See Also
Script Functions

---

## MakeTime - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MakeTimeFunction.htm

MakeTime - MaxBasic Function
MakeTime(Hour: Number, Minutes: Number[, Seconds: Number[, Milliseconds: Number]]): Date
Returns a valid time with the Hour and Minutes provided, optionally with Seconds and Milliseconds.
MakeTime function syntax has these named arguments:
Parameter
Description
Hour
Required. The hour of the time.
Minutes
Required. The minutes of the time.
Seconds
Optional. The seconds of the time.
Milliseconds
Optional. The milliseconds of the time.
Sample code:
lTime = MakeTime(12,5,2)
Print "Time = " & FormatDateTime(lTime, "hh:mm:ss")
See Also
Date Functions

---

## MakeValidCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MakeValidCodeFunction.htm

MakeValidCode - MaxBasic Function
MakeValidCode(aCode: String[, ExcludeChars: String]): String
Returns a valid code, by stripping non-printing characters from a code. Characters stripped are any less than Ascii(32) or greater than Ascii(126), wildcards (such as *, ?, %, _), and csv punctuation (such as " ,). If the ExcludeChars is included, wildcard and csv punctuation in ExcludeChars will not be stripped. Non-printing characters and leading spaces are always stripped.
MakeValidCode function syntax has these named arguments:
Parameter
Description
aCode
Required. The code to be converted.
ExcludeChars
Optional. Any wildcard or csv characters to be excluded from the conversion.
See Also
String Functions

---

## Margin - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MarginFunction.htm

Margin - MaxBasic Function
Margin(A: Number, B: Number): Number
Calculates margin from parameters as follows,
Margin(A, B) = ((B - A) / B )*100.
Divide by zero returns zero.
If A and B are of opposite signs returns zero.
Margin function syntax has these named arguments:
Parameter
Description
A
Required. Number to determine the margin from.
B
Required. Number to determine the margin to.
See Also
Number Functions

---

## Markup - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MarkupFunction.htm

Markup - MaxBasic Function
Markup(A: Number, B: Number): Number
Marks up a price by a percentage as follows,
Markup(A,B) = A * (1 + B / 100).
Markup function syntax has these named arguments:
Parameter
Description
A
Required. Number to be marked up by Percentage B.
B
Required. Percentage to mark up Number A by.
See Also
Number Functions

---

## MatchRegEx - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MatchRegExFunction.htm

MatchRegEx - MaxBasic Function
MatchRegEx(InputString: String, RegularExpression: String): Boolean
Returns a Boolean indicating whether regular expression matches string.
MatchRegEx function syntax has these named arguments:
Parameter
Description
InputString
Required. The String to be matched.
RegularExpression
Required. The string containing the regular expression.
Sample code:
Dim Matched as Boolean
Matched = MatchRegEx("Hello World", "^[A-Za-z ]+$")
Msgbox(Matched)
Note: For details of the Regular Expression syntax see
Regular expressions (RegEx)
See Also
String Functions

---

## Max - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MaxFunction.htm

Max - MaxBasic Function
Max(Number1: Number, Number2: Number[, Number3: Number, ...]): Number
Returns the maximum from the numbers supplied.
Max function syntax has these named arguments:
Parameter
Description
Number 1
Required. First number to be evaluated.
Number 2
Required. Second number to be evaluated.
Number 3 ....
Optional. Additional numbers to be evaluated.
See Also
Number Functions

---

## MaxDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MaxDateFunction.htm

MaxDate - MaxBasic Function
MaxDate(Date1: Date, Date2: Date[, Date3: Date, ...]): Date
Returns the maximum from the dates supplied.
MaxDate function syntax has these named arguments:
Parameter
Description
Date 1
Required. First date to be evaluated.
Date 2
Required. Second date to be evaluated.
Date 3 ....
Optional. Additional dates to be evaluated.
See Also
Date Functions

---

## MemoAccountFiles - MaxBasic function

Source: https://accredo.co.nz/webhelp/MemoAccountFilesFunction.htm

MemoAccountFiles - MaxBasic function
MemoAccountFiles : Object
MemoAccountFiles function returns a
StringList Object
containing a string list of the tables that support memos.
Sample code:
Dim List as Object
List = MemoAccountFiles
For I = 0 to List.Count - 1
Print List[I]
Next I
Print ""
Print "Total: " & List.Count

---

## MemoryTotalAllocated - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MemoryTotalAllocatedFunction.htm

MemoryTotalAllocated - MaxBasic Function
MemoryTotalAllocated: String
Memory Total Allocated function returns the total allocated memory.
This is made available for debugging purposes for checking internal application memory use values, returns the value shown for Program Memory - Total allocated under File >
Diagnostics
> Memory.
See Also
Environment Functions

---

## MemoryTotalCommitted - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MemoryTotalCommittedFunction.htm

MemoryTotalCommitted - MaxBasic Function
MemoryTotalCommitted: String
Memory Total Committed function returns the total OS committed memory.
This is made available for debugging purposes for checking internal application memory use values, returns the value shown for OS Memory - Total committed under File >
Diagnostics
> Memory.
See Also
Environment Functions

---

## MemoryTotalFree - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MemoryTotalFreeFunction.htm

MemoryTotalFree - MaxBasic Function
MemoryTotalFree: String
Memory Total Free function returns the total free memory.
This is made available for debugging purposes for checking internal application memory use values, returns the value shown for Program Memory - Total free under File >
Diagnostics
> Memory.
See Also
Environment Functions

---

## MemoryTotalMemory - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MemoryTotalMemoryFunction.htm

MemoryTotalMemory - MaxBasic Function
MemoryTotalMemory: String
Memory Total Memory function returns the total program memory.
This is made available for debugging purposes for checking internal application memory use values, returns the value shown for Program Memory - Total memory under File >
Diagnostics
> Memory.
See Also
Environment Functions

---

## MergePDFs - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MergePDFsFunction.htm

MergePDFs - MaxBasic Function
MergePDFs(File1: String, File2: String[, File3: String, ...]): String - OR -
MergePDFs(FileStringList: StringList): String
Merge PDFs function merges Accredo generated PDF files in the order they are listed, and saves the merged file with the name of File1. Subsequent merged files are deleted. If no directory is supplied, the system path will be used as the directory.
Returns the name of the consolidated file.
MergePDFs function syntax has these named arguments:
Parameter
Description
File1, File2
Required. The names of the first two files to be merged.
File3 to File n
Optional. The names of additional files to be merged.
- OR -
Parameter
Description
File String List
Required. A
StringList Object
containing the names of the files to be merged.
See Also
Script Functions

---

## Mid - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MidFunction.htm

Mid - MaxBasic Function
Mid(String: String, Start: Number[, Length: Number]): String
Returns a sub-string of String, starting at character number Start, that is Number characters long.
If Length is specified and there are more than Length characters in the string starting at start then Length characters are returned, or all characters from start to the end of the string are returned.
Mid function syntax has these named arguments:
Parameter
Description
String
Required. String to return the mid characters for.
Start
Required. The first character to return string characters.
Length
Optional. The length of the string to be returned.
For example:
Mid("credit", 2, 3)
Returns:
red
See Also
String Functions

---

## Min - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MinFunction.htm

Min - MaxBasic Function
Min(Number1: Number, Number2: Number[, Number3: Number, ...]): Number
Returns the minimum from the numbers supplied.
Min function syntax has these named arguments:
Parameter
Description
Number 1
Required. First number to be evaluated.
Number 2
Required. Second number to be evaluated.
Number 3 ....
Optional. Additional numbers to be evaluated.
See Also
Number Functions

---

## MinDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MinDateFunction.htm

MinDate - MaxBasic Function
MinDate(Date1: Date, Date2: Date[, Date3: Date, ...]): Date
Returns the minimum from the dates supplied.
MinDate function syntax has these named arguments:
Parameter
Description
Date 1
Required. First date to be evaluated.
Date 2
Required. Second date to be evaluated.
Date 3 ....
Optional. Additional dates to be evaluated.
See Also
Date Functions

---

## ModuleAvailable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ModuleAvailableFunction.htm

ModuleAvailable - MaxBasic Function
ModuleAvailable(ModuleCode: String): Boolean
Module Available function returns
True
if the module specified by ModuleCode is installed in the Company, or returns
False
.
ModuleAvailable function syntax has these named arguments:
Parameter
Description
Module Code
Required. The module code to be evaluated.
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
See also the Web Services
ModuleAvailable
function.
See Also
Environment Functions

---

## Month - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MonthFunction.htm

Month - MaxBasic Function
Month(Date: Date): Number
Month returns the month value for the Date. If Date is Null then Null is returned.
Month function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the Month value for.
See Also
Date Functions

---

## MsgBox - MaxBasic Function

Source: https://accredo.co.nz/webhelp/MsgBoxFunction.htm

MsgBox - MaxBasic Function
MsgBox(Prompt: String[, Title: String])
Displays a message in a dialog box, User must click
OK
or press
Enter.
MsgBox function syntax has these named arguments:
Parameter
Description
Prompt
Required. String expression displayed as the message in the dialog box.
Title
Optional. String expression displayed in the title bar of the dialog box. If you omit title,"Information" is displayed in the title bar.
Usage:
MsgBox("This is the message body", "Title")
See Also
Input Functions

---

## NavigateURL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/NavigateURLFunction.htm

NavigateURL - MaxBasic Function
NavigateURL(URL: String[, CloseFormURL: String])
Function will show a Modal WebBrowser window (embedded webview) inside Accredo, and navigate to a given page. This function can optionally detect a redirect URL and close the form if required.
URLEncode function syntax has these named arguments:
Parameter
Description
URL
Required. URL to navigate to.
CloseFormURL.
Optional. If redirected to this URL close the form.
See Also
Web Functions

---

## NextTaxDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/NextTaxDateFunction.htm

NextTaxDate - MaxBasic Function
NextTaxDate[(TaxRegime: String)]: Date
Next Tax Date function returns the next tax date for a given Tax Regime. If no Tax Regime is given, the next tax date for the Base Tax Regime is returned.
NextTaxDate function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the next tax date for. If not supplied, the Base Tax Regime is used.
See Also
GST Functions

---

## OAuth2TokenFromAuthCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OAuth2TokenFromAuthCodeFunction.htm

OAuth2TokenFromAuthCode - MaxBasic Function
OAuth2TokenFromAuthCode(Client_ID: String, ClientSecret: String, Scope: String, TokenEndPoint: String, AuthEndPoint: String, UsePKCE: Boolean[, QueryString: String]): Object
OAuth2TokenFromAuthCode function returns a JSON OAuth2 token based on parameters passed. If an error occurs, the login form will close and the Response Code, Error and any additional Error Text will be returned as a JSON object.
OAuth2TokenFromAuthCode function accepts an optional QueryString parameter. This can be used to pass additional parameters. When using this function with the IRD, pass the query parameter "
logout=true
" to ensure the token expires immediately after the session. Multiple parameters can be included in this string by appending with the string "
&
".
OAuth2TokenFromAuthCode function syntax has these named arguments:
Parameter
Description
Client_ID
Required. The OAuth2 client identifier.
Client Secret
Required. The client secret string.
Scope
Required. The scope of the authorisation.
Token End Point
Required. Web address of the token end point.
Auth End Point
Required. Web address of the authorisation end point.
Use PKCE
Required. When True, the Proof Key for Code Exchange (PKCE) will be used.
Query String
Optional. Send additional query parameters.
Redirect URI
Optional. The redirect URI (if specified) must use protocol http, and host can only be "localhost", or "127.0.01". A port can also be specified, and if specified, must be available, otherwise a randomised port will be used.
Note: This function makes use of an Windows component that wraps Internet Explorer. As such, you may need to modify your Internet Explorer security options depending on the website you are connecting to.
See Also
Web Functions

---

## OAuth2TokenFromAuthCodeEx - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OAuth2TokenFromAuthCodeExFunction.htm

OAuth2TokenFromAuthCodeEx - MaxBasic Function
OAuth2TokenFromAuthCodeEx(Options: StringList): Object
OAuth2TokenFromAuthCodeEx function returns a JSON OAuth2 token based on String List Key/Value pairs passed. If an error occurs, the login form will close and the Response Code, Error and any additional Error Text will be returned as a JSON object.
OAuth2TokenFromAuthCodeEx function syntax has these named arguments:
Parameter
Description
Options
Required. A Stringlist object containing at a minimum all mandatory parameters as name value pairs.
ClientID
ClientSecret
Scope
TokenEndpoint
AuthEndpoint
UsePKCE
ExtraQueryParams (optional)
RedirectUrl (optional)
Accepts "Y", "Yes", "T", "True", or "1" for the boolean UsePKCE param.
See
OAuth2TokenFromAuthCode
for additional information.
Note: This function makes use of an Windows component that wraps Internet Explorer. As such, you may need to modify your Internet Explorer security options depending on the website you are connecting to.

---

## OAuth2TokenFromRefreshToken - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OAuth2TokenFromRefreshTokenFunction.htm

OAuth2TokenFromRefreshToken - MaxBasic Function
OAuth2TokenFromRefreshToken(Client_ID: String, ClientSecret: String, Scope: String, TokenEndPoint: String, RefreshToken: String): Object
OAuth2TokenFromRefreshToken function returns a JSON OAuth2 token based on parameters passed.
OAuth2TokenFromRefreshToken function syntax has these named arguments:
Parameter
Description
Client_ID
Required. The OAuth2 client identifier.
Client Secret
Required. The client secret string.
Scope
Required. The scope of the authorisation.
Token End Point
Required. Web address of the token end point.
Refresh Token
Required. Web address of the authorisation end point.
See Also
Web Functions

---

## OAuth2TokenFromResourceOwner - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OAuth2TokenFromResourceOwnerFunction.htm

OAuth2TokenFromResourceOwner - MaxBasic Function
OAuth2TokenFromResourceOwner(Client_ID: String, ClientSecret: String, Scope: String, TokenEndPoint: String, UserName: String, Password: String): Object
OAuth2TokenFromResourceOwner function returns a JSON OAuth2 token based on parameters passed.
OAuth2TokenFromResourceOwner function syntax has these named arguments:
Parameter
Description
Client_ID
Required. The OAuth2 client identifier.
Client Secret
Required. The client secret string.
Scope
Required. The scope of the authorisation.
Token End Point
Required. Web address of the token end point.
User Name
Required. User Name of the resource owner.
Password
Required. Password for the resource owner.
See Also
Web Functions

---

## ObjectProperties - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ObjectPropertiesFunction.htm

ObjectProperties - MaxBasic Function
ObjectProperties(ObjectName: String[, Expand: Boolean]): Object
Returns a
StringList Object
containing a string list of the top-level properties of the object
ObjectName
. If the Expand boolean is set to
True
, all child properties are also included. Expand defaults to
False
.
ObjectProperties function syntax has these named arguments:
Parameter
Description
Object Name
Required. The name of the Object to return properties for.
Expand
Optional. When set to
True
, the list will include all expanded child properties. Defaults to
False
.
For example:
Dim datARCust as Object
datARCust = CreateObject("Accredo.ARCustomerData")
Dim Props as Object
Props = ObjectProperties(datARCust, True)
Props.Sort
For I = 0 to Props.Count - 1
Print Props[I]
Next I
will print an expanded list of all properties of the ARCUST object.
See Also
Script Functions

---

## OpenCustomTable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OpenCustomTableFunction.htm

OpenCustomTable - MaxBasic Function
OpenCustomTable(FileName: String[, Read-only: Boolean])
Open Custom Table function opens a custom Accredo table. FileName must be a table name for a table added using the
Table Designer
module. This function provides access to custom tables.
Only available when Table Designer and DI are installed.
Press
F1
with the cursor in the FileName to see the Automated Documentation for the file.
OpenCustomTable function syntax has these named arguments:
Parameter
Description
File Name
Required. The custom table name.
Read Only
Optional. Determines if the table is opened as Read Only. Defaults to False if the User has Write permission (or higher) for Custom Tables, otherwise True.
See Also
Tables Functions

---

## OpenForm - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OpenFormFunction.htm

OpenForm - MaxBasic Function
OpenForm(AccountFile: String[, AccountCode: String, Line/SubType: Number or String]): Object
Opens the form associated with the Account File, loads the record for the AccountCode if specified, and positions on the line if specified. Opens as an MDI child form. Requires a minimum of Read permission for the form.
OpenForm function syntax has these named arguments:
Parameter
Description
Account File
Required. The account file with the associated form to be opened.
Account Code
Optional. The Account Code to load records from into the form.
Line / SubType
Optional. The line position within the form or sub type for the form.
Account File
Account Code
Line
Subtype
Form Opened
APANL
AP Expense Code
APExpenseCodeForm
APCAT1
AP Category 1 Code
APCategories1GridForm
APCAT2
AP Category 2 Code
APCategories2GridForm
APCONTCT
Contact ID
APContactEditForm
APCOST
AP Cost Code
APCostCodeForm
APCRED
AP Creditor Code
APCreditorForm
APGROUP
AP Creditor Group Code
APCreditorGroupForm
APMEMO
Memo ID
APMemoEditForm
APSHCAT1
AP Shipment Category 1 Code
APSHCategories1GridForm
APSHCAT2
AP Shipment Category 2 Code
APSHCategories2GridForm
APSHIP
Document ID
Line ID
APShipmentEntryForm
APTRAN
Transaction ID
APTransactionForm
ARANL
AR Sales Group Code
ARSalesGroupForm
ARAREA
AR Sales Area Code
ARSalesAreaForm
ARCAT1
AR Category 1 Code
ARCategories1GridForm
ARCAT2
AR Category 2 Code
ARCategories2GridForm
ARCONTCT
Contact ID (Number)
ARContactEditForm
ARCUST
AR Customer Code
ARCustomerForm
ARGROUP
AR Customer Group Code
ARCustomerGroupForm
ARMEMO
Memo ID
ARMemoEditForm
ARPERS
AR Sales Person Code
ARSalesPersonForm
ARTRAN
Transaction ID (Number)
ARTransactionForm
CBANL
CB Analysis Code
CBAnalysisCodeForm
CBAUTO
CB Automatic Payment Code
CBAutomaticPaymentForm
CBBANK
CB Bank Account Code
CBBankAccountForm
CBCAT1
CB Category 1 Code
CBCategories1GridForm
CBCAT2
CB Category 2 Code
CBCategories2GridForm
CBMEMO
Memo ID
CBMemoEditForm
CBSTMT
Statement ID
CBStatementEditForm
CBSUM
Summary ID
CBBankingSummaryForm
CBTRAN
Transaction ID (Number)
CBEnterTransactionForm
COADDR
CO Delivery Code
CODeliveryAddressForm
COBRANCH
CO Branch Code
COBranchForm
CODEPT
CO Department Code
CODepartmentForm
COFXCURR
CO Currency Code
FXCurrenciesForm
COLKCAT1
CO Link Category 1 Code
COLinkCategories1GridForm
COLKCAT2
CO Link Category 2 Code
COLinkCategories2GridForm
COMEDIA
CO Media Code
COBankingMediaForm
COMEMO
Memo ID
COMemoEditForm
COMOCAT1
CO Memo Category 1 Code
COMoCategories1GridForm
COMOCAT2
CO Memo Category 2 Code
COMoCategories2GridForm
FAASSET
FA Asset Code
FAAssetForm
FABOOK
FA Book Code
FABookForm
FACAT1
FA Category 1 Code
FACategories1GridForm
FACAT2
FA Category 2 Code
FACategories2GridForm
FAGROUP
FA Asset Group Code
FAGroupForm
FAMEMO
Memo ID
FAMemoEditForm
FATRAN
Transaction ID
FATransactionForm
GLACCT
GL Account Code
GLAccountForm
GLBUDGET
GL Budget Code
GLBudgetCodeForm
GLCAT1
GL Category 1 Code
GLCategories1GridForm
GLCAT2
GL Category 2 Code
GLCategories2GridForm
GLHEAD
Batch ID
Line No or Transaction ID
GLBatchEditForm
GLMEMO
Memo ID
GLMemoEditForm
GSTTRAN
Transaction ID
GSTEnterTransactionForm
ICCAT1
IC Category 1 Code
ICCategories1GridForm
ICCAT2
IC Category 2 Code
ICCategories2GridForm
ICCNTHD
IC Stocktake Count ID
Line ID
ICCountEditForm
ICGROUP
IC Stock Group Code
ICStockGroupForm
ICLOCN
IC Location Code
ICLocationForm
ICMEMO
Memo ID
ICMemoEditForm
ICPART
IC Part ID
ICComponentForm
ICPARTHD
IC Product Code
ICComponentForm
ICPROD
IC Product Code
ICProductForm
ICQTY
IC Quantity ID
ICProductForm > Location tab (Saturn only)
ICSTKHD
IC Stocktake Number
ICStocktakeEditForm
ICTFER
Document ID
Line ID
ICStockTransferForm
ICTRAN
Transaction ID
ICEnterTransactionForm
ICUOM
IC UOM ID
ICProductForm > UOM tab
INCAT1
IN Category 1 Code
INCategories1GridForm
INCAT2
IN Category 2 Code
INCategories2GridForm
INHEAD
Document ID
Line ID
INInvoiceEntryForm
INMEMO
Memo ID
INMemoEditForm
INSHIP
IN Shipper Code
INShipperForm
JCCAT1
JC Category 1 Code
JCCategories1GridForm
JCCAT2
JC Category 2 Code
JCCategories2GridForm
JCCOMP
JC Component Code
JCComponentGridForm
JCCOST
JC Cost Centre Code
JCCostCentreGridForm
JCGROUP
JC Job Group Code
JCJobGroupForm
JCHEAD
Batch ID
Line ID
or Transaction ID
"B" (Batch),
"T" (Timesheet),
"D" (Disbursement)
JCBatchTransactionEntryForm or
JCTimesheetTransactionEntryForm
JCDisbursementForm
Dependant on Batch Class if Batch ID is passed as AccountCode, or Subtype specified where AccountCode is empty or zero.
JCJOB
JC Job Code
JCJobForm
JCMEMO
Memo ID
JCMemoEditForm
JCTRAN
Transaction ID
JCEnterTransactionsForm
OEHEAD
Document ID
Line ID
OESalesOrderEntryForm
OEMEMO
Memo ID
OEMemoEditForm
POAUTHOR
PO Author Code
POAuthorMatrixForm
POCAT1
PO Category 1 Code
POCategories1GridForm
POCAT2
PO Category 2 Code
POCategories2GridForm
POHEAD
Document ID
Line ID
POPurchaseOrderEntryForm
POMEMO
Memo ID
POMemoEditForm
SPRULE
Rule ID
SPRuleEditForm
SPBREAK
Break ID
SPRuleEditForm
See Also
Objects Functions

---

## OpenPDF - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OpenPDFFunction.htm

OpenPDF - MaxBasic Function
OpenPDF(FileName: String)
OpenPDF function opens the file specified in File Name by asking Windows to display the PDF using thedefault application associated with the PDF file extension.
OpenPDF function syntax has these named arguments:
Parameter
Description
File Name
Required. The name of the file to be opened.
See Also
Environment Functions

---

## OpenSysTable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OpenSysTableFunction.htm

OpenSysTable - MaxBasic Function
OpenSysTable(TableName: String)
Open Sys Table function opens a
read-only
view of a standard Accredo system table. The File Name must be an Accredo system table name, see
Automated Table Objects
. This function provides low level DI access to standard tables (DI installed).
Press
F1
with the cursor in the FileName to see the Automated Documentation for the file.
OpenSysTable function syntax has these named arguments:
Parameter
Description
Table Name
Required. The Accredo system table name.
See Also
Tables Functions

---

## OpenTable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OpenTableFunction.htm

OpenTable - MaxBasic Function
OpenTable(FileName: String)
Open Table function opens a
read-only
view of a standard Accredo table. The File Name must be an Accredo table name, see
Automated Table Objects
. This function provides low level DI access to standard tables (DI installed).
Press
F1
with the cursor in the FileName to see the Automated Documentation for the file.
OpenTable function syntax has these named arguments:
Parameter
Description
File Name
Required. The Accredo table name.
See Also
Tables Functions

---

## OpenWindowForm - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OpenWindowFormFunction.htm

OpenWindowForm - MaxBasic Function
OpenWindowForm(AccountFile: String[, AccountCode: String, Line/SubType: Number or String]): Object
Opens the form associated with the Account File, loads the record for the AccountCode if specified, and positions on the line if specified. Opens as a floating Window form. Requires a minimum of Read permission for the form.
OpenWindowForm function syntax has these named arguments:
Parameter
Description
Account File
Required. The account file with the associated form to be opened.
Account Code
Optional. The Account Code to load records from into the form.
Line / SubType
Optional. The line position within the form or sub type for the form.
Account File
Account Code
Line
Subtype
Form Opened
APANL
AP Expense Code
APExpenseCodeForm
APCAT1
AP Category 1 Code
APCategories1GridForm
APCAT2
AP Category 2 Code
APCategories2GridForm
APCONTCT
Contact ID
APContactEditForm
APCOST
AP Cost Code
APCostCodeForm
APCRED
AP Creditor Code
APCreditorForm
APGROUP
AP Creditor Group Code
APCreditorGroupForm
APMEMO
Memo ID
APMemoEditForm
APSHCAT1
AP Shipment Category 1 Code
APSHCategories1GridForm
APSHCAT2
AP Shipment Category 2 Code
APSHCategories2GridForm
APSHIP
Document ID
Line ID
APShipmentEntryForm
APTRAN
Transaction ID
APTransactionForm
ARANL
AR Sales Group Code
ARSalesGroupForm
ARAREA
AR Sales Area Code
ARSalesAreaForm
ARCAT1
AR Category 1 Code
ARCategories1GridForm
ARCAT2
AR Category 2 Code
ARCategories2GridForm
ARCONTCT
Contact ID (Number)
ARContactEditForm
ARCUST
AR Customer Code
ARCustomerForm
ARGROUP
AR Customer Group Code
ARCustomerGroupForm
ARMEMO
Memo ID
ARMemoEditForm
ARPERS
AR Sales Person Code
ARSalesPersonForm
ARTRAN
Transaction ID (Number)
ARTransactionForm
CBANL
CB Analysis Code
CBAnalysisCodeForm
CBAUTO
CB Automatic Payment Code
CBAutomaticPaymentForm
CBBANK
CB Bank Account Code
CBBankAccountForm
CBCAT1
CB Category 1 Code
CBCategories1GridForm
CBCAT2
CB Category 2 Code
CBCategories2GridForm
CBMEMO
Memo ID
CBMemoEditForm
CBSTMT
Statement ID
CBStatementEditForm
CBSUM
Summary ID
CBBankingSummaryForm
CBTRAN
Transaction ID (Number)
CBEnterTransactionForm
COADDR
CO Delivery Code
CODeliveryAddressForm
COBRANCH
CO Branch Code
COBranchForm
CODEPT
CO Department Code
CODepartmentForm
COFXCURR
CO Currency Code
FXCurrenciesForm
COLKCAT1
CO Link Category 1 Code
COLinkCategories1GridForm
COLKCAT2
CO Link Category 2 Code
COLinkCategories2GridForm
COMEDIA
CO Media Code
COBankingMediaForm
COMEMO
Memo ID
COMemoEditForm
COMOCAT1
CO Memo Category 1 Code
COMoCategories1GridForm
COMOCAT2
CO Memo Category 2 Code
COMoCategories2GridForm
FAASSET
FA Asset Code
FAAssetForm
FABOOK
FA Book Code
FABookForm
FACAT1
FA Category 1 Code
FACategories1GridForm
FACAT2
FA Category 2 Code
FACategories2GridForm
FAGROUP
FA Asset Group Code
FAGroupForm
FAMEMO
Memo ID
FAMemoEditForm
FATRAN
Transaction ID
FATransactionForm
GLACCT
GL Account Code
GLAccountForm
GLBUDGET
GL Budget Code
GLBudgetCodeForm
GLCAT1
GL Category 1 Code
GLCategories1GridForm
GLCAT2
GL Category 2 Code
GLCategories2GridForm
GLHEAD
Batch ID
Line ID
or Transaction ID
GLBatchEditForm
GLMEMO
Memo ID
GLMemoEditForm
GSTTRAN
Transaction ID
GSTEnterTransactionForm
ICCAT1
IC Category 1 Code
ICCategories1GridForm
ICCAT2
IC Category 2 Code
ICCategories2GridForm
ICCNTHD
IC Stocktake Count Code
ICCountEditForm
ICGROUP
IC Stock Group Code
ICStockGroupForm
ICLOCN
IC Location Code
ICLocationForm
ICMEMO
Memo ID
ICMemoEditForm
ICPROD
IC Product Code
ICProductForm
ICSTKHD
IC Stocktake Number
ICStocktakeEditForm
ICTFER
Document ID
Line ID
ICStockTransferForm
ICTRAN
Transaction ID
ICEnterTransactionForm
INCAT1
IN Category 1 Code
INCategories1GridForm
INCAT2
IN Category 2 Code
INCategories2GridForm
INHEAD
Document ID
Line ID
INInvoiceEntryForm
INMEMO
Memo ID
INMemoEditForm
INSHIP
IN Shipper Code
INShipperForm
JCCAT1
JC Category 1 Code
JCCategories1GridForm
JCCAT2
JC Category 2 Code
JCCategories2GridForm
JCCOMP
JC Component Code
JCComponentGridForm
JCCOST
JC Cost Centre Code
JCCostCentreGridForm
JCGROUP
JC Job Group Code
JCJobGroupForm
JCHEAD
Batch ID
Line ID
or Transaction ID
"B" (Batch),
"T" (Timesheet),
"D" (Disbursement)
JCBatchTransactionEntryForm or
JCTimesheetTransactionEntryForm
JCDisbursementForm
Dependant on Batch Class if Batch ID is passed as AccountCode, or Subtype specified where AccountCode is empty or zero.
JCJOB
JC Job Code
JCJobForm
JCMEMO
Memo ID
JCMemoEditForm
JCTRAN
Transaction ID
JCEnterTransactionsForm
OEHEAD
Document ID
Line ID
OESalesOrderEntryForm
OEMEMO
Memo ID
OEMemoEditForm
POAUTHOR
PO Author Code
POAuthorMatrixForm
POCAT1
PO Category 1 Code
POCategories1GridForm
POCAT2
PO Category 2 Code
POCategories2GridForm
POHEAD
Document ID
Line ID
POPurchaseOrderEntryForm
POMEMO
Memo ID
POMemoEditForm
SPRULE
Rule ID
SPRuleEditForm
See Also
Objects Functions

---

## OptimiseCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/OptimiseCompanyFunction.htm

OptimiseCompany - MaxBasic Function
OptimiseCompany[(Module: String, AllFiles:Boolean)]: Number
Optimise Company function performs optimisation on the company. If Module is specified, the module is optimised, otherwise all modules are optimised. If All Files is True, all files will be optimised, otherwise only recommended files are optimised. Returns a number showing the combined number of Errors and Warnings returned. If any errors occur, they are displayed in the Print stream, and sent to the Log.
OptimiseCompany function syntax has these named arguments:
Parameter
Description
Module
Optional. The name of the module to be optimised. If Module is not passed, all modules are optimised.
All Files
Optional. When set to
True
, all files are optimised. When set to
False
, only recommended files are optimised. Defaults to
False
.
See Also
Company Functions

---

## PackingSlip - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PackingSlipFunction.htm

PackingSlip - MaxBasic Function
PackingSlip: Boolean
Returns
True
if the currently printing Invoice document is being printed as a Packing Slip, otherwise returns
False
.
Available in IN Invoice Document design script editors.
See Also
Report Functions

---

## PadAcctNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PadAcctNoFunction.htm

PadAcctNo - MaxBasic Function
PadAcctNo(BankAcct: String, Pattern: String[, PadCharacter: String]): String
Creates a bank account number based on the BankAcct string and Pattern string. If PadCharacter is not specified, the character used to pad defaults to 0.
PadAcctNo function syntax has these named arguments:
Parameter
Description
BankAcct
Required. The bank account to be padded.
Pattern
Required. The format of the bank account number. The bank account format is separated by the . character, such as "2.4.8.2".
PadCharacter
Options. The character to pad the bank account string with. If not entered, defaults to zero. Some banks require a space character.
For example:
PadAcctNo("123-123-55555-22","4.4.8.2")
Returns:
012301230005555522
See Also
String Functions

---

## PageHeight - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PageHeightFunction.htm

PageHeight - MaxBasic Function
PageHeight: Number
Returns the physical page height. This is useful for positioning/sizing components relative to the end of the page.
See Also
Report Functions

---

## PageNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PageNumberFunction.htm

PageNumber - MaxBasic Function
PageNumber: Number
Returns the currently printing page number.
See Also
Report Functions

---

## PageOfNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PageOfNumberFunction.htm

PageOfNumber - MaxBasic Function
PageOfNumber: String
Returns "Page X of Y" where X is current page and Y is total pages for the document or report.
See Also
Report Functions

---

## PageRemaining - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PageRemainingFunction.htm

PageRemaining - MaxBasic Function
PageRemaining: Number
Returns the physical page space remaining to print on. This is useful for determining whether or not to start a new page for a GroupHeader band.
See Also
Report Functions

---

## PageWidth - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PageWidthFunction.htm

PageWidth - MaxBasic Function
PageWidth: Number
Returns the physical page width. This is useful for positioning/sizing components relative to the right hand edge of the page.
See Also
Report Functions

---

## ParseJSON - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ParseJSONFunction.htm

ParseJSON - MaxBasic Function
ParseJSON(aJSONString: String): JSONObject
Parse JSON function returns the top level JSON object representing the aJSONString string. Each JSON element will become a property against this object, which can be accessed using dot "." notation or array notation. For example:
Print json.MyProperty
or
Print json["MyProperty"]
As JSON is case sensitive and MaxBasic is not case sensitive, the second example above can be used when case sensitivity is required.
The ParseJSON function can be used with the
IsArray
,
LBound
and
UBound
functions.
ParseJSON function syntax has these named arguments:
Parameter
Description
a JSON String
Required. The string to be parsed into a JSON object.
See Also
Web Functions

---

## ParseJSONFromFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ParseJSONFromFileFunction.htm

ParseJSONFromFile - MaxBasic Function
ParseJSONFromFile(aJSONFile: String): JSONObject
ParseJSONFromFile function returns the top level JSON object representing the aJSONFile file. Each JSON element will become a property against this object, which can be accessed using dot "." notation or array notation. For example:
Print json.MyProperty
or
Print json["MyProperty"]
As JSON is case sensitive and MaxBasic is not case sensitive, the second example above can be used when case sensitivity is required.
ParseJSONFromFile function syntax has these named arguments:
Parameter
Description
a JSON File
Required. The file name of the file to be parsed into a JSON object.
See Also
Web Functions

---

## PartNumber - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PartNumberFunction.htm

PartNumber - MaxBasic Function
PartNumber: Number
Returns the Part Number for multi-part forms.
See Also
Report Functions

---

## Percent - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PercentFunction.htm

Percent - MaxBasic Function
Percent(A: Number, B: Number): Number
Calculates percentage from parameters as follows:
Percent(A,B) = (A/B)*100
Divide by zero returns zero.
Percent function syntax has these named arguments:
Parameter
Description
A
Required. Amount to be calculated as a percentage of Total B.
B
Required. Total amount to calculate Amount A as a percentage of.
See Also
Number Functions

---

## PercentEncode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PercentEncodeFunction.htm

PercentEncode - MaxBasic Function
PercentEncode(Value: String): String
Returns a string with percent encoded reserved characters. This can be used when passing parameters to endpoints with escape characters.
PercentEncode function syntax has these named arguments:
Parameter
Description
String
Required. String to return with percent encoded reserved characters.
Sample code:
s = "search?q=big little"
t = PercentEncode(s)
msgbox(t)
Returns: search%3Fq%3Dbig+little
See Also
Web Functions

---

## Period - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodFunction.htm

Period - MaxBasic Function
Period: Number
For reports and document that have an As At Period selection, returns the Period ID for the selected period.
See Also
Report Functions

---

## PeriodActivity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodActivityFunction.htm

PeriodActivity - MaxBasic Function
PeriodActivity(StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Period activity between the range of periods specified. Optionally can be passed additional parameters to calculate summed period activity over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
PeriodActivity function syntax has these named arguments:
Parameter
Description
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## PeriodAvailable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodAvailableFunction.htm

PeriodAvailable - MaxBasic Function
PeriodAvailable(PeriodID: Number,Module: String[,User: String]): Boolean
Returns true if Period available for posting to for the Module, optionally limited by user code.
PeriodAvailable function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to check.
Module
Required. Module check.
User
Optional. User to constrain check.
See Also
Period Functions

---

## PeriodBalance - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodBalanceFunction.htm

PeriodBalance - MaxBasic Function
PeriodBalance(StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Period balance as at period specified. Optionally can be passed additional parameters to calculate summed period balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
If a range of periods is specified, for example, to obtain a quarterly balance, returns balance as OpeningBalance for start period plus sum of Activity from start period to end period.
PeriodBalance function syntax has these named arguments:
Parameter
Description
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## PeriodBudget - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodBudgetFunction.htm

PeriodBudget - MaxBasic Function
PeriodBudget([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Sum of period budgets over range of periods specified. If a budget code is not passed then default budget is used. Optionally can be passed additional parameters to calculate summed period budgets over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
PeriodBudget function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## PeriodDifference - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodDifferenceFunction.htm

PeriodDifference - MaxBasic Function
PeriodDifference(PeriodFrom: Number, PeriodTo: Number[, IncludeAdjustment: Boolean]): Number
Returns the number of periods between PeriodFrom and PeriodTo. If IncludeAdjustment is True, Adjustment Periods are also calculated.
PeriodDifference function syntax has these named arguments:
Parameter
Description
PeriodFrom
Required. The Period ID to calculate from.
PeriodTo
Required. The Period ID to calculate to.
IncludeAdjustment
Optional. When set to True, Adjustment Periods are included in the calculation. When set to False, Adjustment Periods are ignored.
See Also
Period Functions

---

## PeriodEndDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodEndDateFunction.htm

PeriodEndDate - MaxBasic Function
PeriodEndDate(PeriodID: Number): Date
Returns the end date for period with ID PeriodID
.
PeriodEndDate function syntax has these named arguments:
Parameter
Description
Period ID
Required. The Period ID to return the end date for.
See Also
Period Functions

---

## PeriodForDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodForDateFunction.htm

PeriodForDate - MaxBasic Function
PeriodForDate(Date: Date): Number
Returns the Period ID of the period containing Date. If no period contains Date then 0 is returned.
PeriodForDate function syntax has these named arguments:
Parameter
Description
Date
Required. The Date to find the Period ID for.
See also the SQL
PeriodForDate
function and the Web Services
PeriodForDate
function.
See Also
Period Functions

---

## PeriodName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodNameFunction.htm

PeriodName - MaxBasic Function
PeriodName(PeriodID: Number): String
Returns name for the for the period with ID PeriodID.
PeriodName function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the name for.
See Also
Period Functions

---

## PeriodOpening - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodOpeningFunction.htm

PeriodOpening - MaxBasic Function
PeriodOpening(PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Period opening balance for period specified. Optionally can be passed additional parameters to calculate summed period opening balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
PeriodOpening function syntax has these named arguments:
Parameter
Description
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## PeriodPeriodNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodPeriodNoFunction.htm

PeriodPeriodNo - MaxBasic Function
PeriodPeriodNo(PeriodID: Number): Number
Returns the Period Number of the Period with ID PeriodID.
PeriodPeriodNo function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to find the Period number for.
See Also
Period Functions

---

## PeriodProjected - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodProjectedFunction.htm

PeriodProjected - MaxBasic Function
PeriodProjected([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Period projected balance from actual figures up to report Period and budgeted figures for future periods relative to report period over the specified period range. If a budget code is not passed then the default budget is used. Optionally can be passed additional parameters to calculate projected summed period over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
PeriodProjected function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## PeriodStartDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodStartDateFunction.htm

PeriodStartDate - MaxBasic Function
PeriodStartDate(PeriodID: Number): Date
Returns the start date for period with ID PeriodID
.
PeriodStartDate function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the start date for.
See Also
Period Functions

---

## PeriodYearNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PeriodYearNoFunction.htm

PeriodYearNo - MaxBasic Function
PeriodYearNo(PeriodID: Number): Number
Returns the year number of the Period with ID PeriodID.
PeriodYearNo function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the year number for.
See Also
Period Functions

---

## PivotTable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PivotTableFunction_1.htm

PivotTable - MaxBasic Function
PivotTable(MemoryTable: Object, NonPivotFields: String, PivotFields: String, PivotValueFields: String, [RowTotals: Boolean]): Variant
Returns a pivoted memory table.
The NonPivotFields and PivotValuesFields are semi-colon separated list of field names from the MemoryTable. The PivotValue fields must be specified as a list of FunctionName(FieldName) pairs. Supported functions for now are Sum and Count. RowTotals boolean is optional with default
False
.
For example:
Dim tblSrc as Object
tblSrc = executesql("SELECT ICTran.PeriodID " & _
" , ICTran.TransactionDate " & _
" , ICTran.ProductCode " & _
" , ICProd.Description " & _
" , ICTran.DepartmentCode " & _
" ,CostValueExclusive as Cost " & _
" ,SalesValueExclusive as Sales " & _
" FROM ICTran INNER JOIN ICProd ON " & _
" ICProd.ProductCode = ICTran.ProductCode " & _
" WHERE ICTran.TransactionType IN ('I','C','U') " & _
" AND ICTran.ProductCode IN ('T10MMRD', 'DESIGN')")
tblResult = PivotTable(tblSrc, "ProductCode;Description", _
"DepartmentCode", "sum(Cost);sum(sales)",true)
CreateReport(tblResult,"Example Pivot Table")
See also the tutorials:
MB Tutorial: IC Product Quantities by Location Pivot Table
MB Tutorial: IC Products and Prices Pivot Table
PivotTable function syntax has these named arguments:
Parameter
Description
Memory Table
Required. The memory table to be used to pivot data from.
Non Pivot Fields
Required. A semi-colon separated list of fields from the Memory Table, not to be pivoted.
Pivot Field
Required. The field from the Memory Table to be pivoted.
Pivot Value Fields
Required. A list of Function Name (Field Name) pairs. Supported functions are Sum and Count.
Row Totals
Optional. When
True
, the pivot table returned contains row totals. Defaults to
False
.
After you have created a pivot table, you can use the
DocumentObject
function to see the attributes of the pivot table.
See Also
Script Functions

---

## PlayScript - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PlayScriptFunction.htm

PlayScript - MaxBasic Function
PlayScript(FileName: String): Boolean
Plays the script specified in FileName. The script is searched for in the Company script directory if a full path is not specified in the FileName. Returns
True
on successful Play Script,
False
if Play Script fails, Error if script file is not found.
The
ScriptArgs
function can be used with this function.
PlayScript function syntax has these named arguments:
Parameter
Description
File Name\
Required. The file name containing the script to play.
This function accepts an infinite number of arguments after the required parameters, for example:
PlayScript("Script1.pfs", "Parameter1", 0, Date)
Inside
script1.pfs
these are accessed via the
ScriptArgs
function.
To open the file in a new Script Editor window, place the cursor in the File Name and click
Ctrl+Enter
, or right click to open the
Context Menu
, then select
Open Source
.
See also the Web Services
PlayScript
function.
See Also
Script Functions

---

## PriceDecimals - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PriceDecimalsFunction.htm

PriceDecimals - MaxBasic Function
PriceDecimals: Number
Returns the maximum of
CostPriceDecimals
and
SellPriceDecimals
for the base currency.
See Also
Number Functions

---

## PrinterList - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PrinterListFunction.htm

PrinterList - MaxBasic Function
PrinterList: Object
Returns a list of available printers.
For example:
Dim printers as object
printers = PrinterList
for i = 0 to printers.count -1
if i = printers.currentprinter then
print "* " & printers[i]
else
print " " & printers[i]
end if
next
print "count: " & printers.count
See Also
Environment Functions

---

## PrinterName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/PrinterNameFunction.htm

PrinterName - MaxBasic Function
PrinterName: String
Returns the Printer Name if the report destination is "Printer", returns an empty string otherwise.
See Also
Report Functions

---

## ProcessLineType - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ProcessLineTypeFunction.htm

ProcessLineType - MaxBasic Function
ProcessLineType(Number: Number)
Executes the Line Type import code, specified by the Number. For example, ProcessLineType(1) will execute the code defined in Line Type 1, ProcessLineType(2) will execute the code defined in Line Type 2, and so on.
ProcessLineType function syntax has these named arguments:
Parameter
Description
Number
Required. The number of the Line Type to be processed.
See Also
Import Functions

---

## ProcessSave - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ProcessSaveFunction.htm

ProcessSave - MaxBasic Function
ProcessSave
Executes the Save Import code.
See Also
Import Functions

---

## ProjectedActivity - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ProjectedActivityFunction.htm

ProjectedActivity - MaxBasic Function
ProjectedActivity([BudgetCode: String,] StartPeriod: Number[, EndPeriod: Number] [, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Projected activity between the range of periods specified. Optionally can be passed additional parameters to calculate summed period activity over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
ProjectedActivity function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Start Period
Required. The starting period number.
End Period
Optional. If End Period is not included, the Start Period is used as a single period.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## ProjectedOpening - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ProjectedOpeningFunction.htm

ProjectedOpening - MaxBasic Function
ProjectedOpening([BudgetCode: String,] PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Projected opening balance for period specified. Optionally can be passed additional parameters to calculate summed period opening balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
ProjectedOpening function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## Proper - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ProperFunction.htm

Proper - MaxBasic Function
Proper(String: String): String
Returns String in proper case, that is, capitalises the first letter in a text string and other letters in text that follow a character other than a letter. Converts all other letters to lower case letters.
Proper function syntax has these named arguments:
Parameter
Description
String
Required. String to return in proper case.
For example:
Proper("emily jones")
Returns:
Emily Jones
See Also
String Functions

---

## QuantityDecimals - MaxBasic Function

Source: https://accredo.co.nz/webhelp/QuantityDecimalsFunction.htm

QuantityDecimals - MaxBasic Function
QuantityDecimals: Number
Returns number of decimals places used to display all item quantities.
See Also
Number Functions

---

## QuotedString - MaxBasic Function

Source: https://accredo.co.nz/webhelp/QuotedStringFunction.htm

QuotedString - MaxBasic Function
QuotedString(Expression: Variant[,Character:String]): String
Returns quoted string version of the given Expression.
QuotedString function has these named arguments:
Parameter
Description
Expression
Required. Expression to be converted to a quoted string.
Character
Quoting character, default value "
Note: For EDI Export only if Output is to Excel Worksheet QuotedString is automatically suppressed since it is not required.
Sample code:
S = "8" & """" & " pipe"
Quoted = QuotedString(S)
Dequoted = DequotedString(Quoted)
Print "S: " & S
Print "Quoted: " & Quoted
Print "Dequoted: " & Dequoted
Returns:
S: 8" pipe
Quoted: "8"" pipe"
Dequoted: 8" pipe
Sample code using character:
S = "8" & "'" & " pipe"
Quoted = QuotedString(S,"'")
Dequoted = DequotedString(Quoted,"'")
Print "S: " & S
Print "Quoted: " & Quoted
Print "Dequoted: " & Dequoted
Returns:
S: 8' pipe
Quoted: '8'' pipe'
Dequoted: 8' pipe
See Also
String Functions

---

## Ratio - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RatioFunction.htm

Ratio - MaxBasic Function
Ratio(A: Number, B: Number): Number
Calculates the ratio of two numbers as follows,
Ratio(A,B) = A/B.
Divide by zero returns zero.
Ratio function syntax has these named arguments:
Parameter
Description
A
Required. Amount to be calculated as a ratio of Total B.
B
Required. Total amount to calculate Amount A as a ratio of.
See Also
Number Functions

---

## RecoverCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RecoverCompanyFunction.htm

RecoverCompany - MaxBasic Function
RecoverCompany([Module: String])
Recover Company function performs a file recovery on the company. If Module is specified, the module is recovered, otherwise all modules are recovered. A Recovery Report is displayed in the Print stream, and is sent to the Recovery Log.
RecoverCompany function syntax has these named arguments:
Parameter
Description
Module
Optional. The name of the module to be recovered. If Module is not passed, all modules are recovered.
See Also
Company Functions

---

## RenameFile - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RenameFileFunction.htm

RenameFile - MaxBasic Function
RenameFile(SourceFileName: String, DestinationFileName: String[, Overwrite: Boolean]): Boolean
Rename File function rename the file specified in Source File Name to the file specified in Destination File Name, optionally over writing if destination file already exists.
RenameFile function syntax has these named arguments:
Parameter
Description
Source File Name
Required. The name of the file to be renamed.
Destination File Name
Required. The name of the file to be renamed to.
Overwrite
Optional. Overwrite Destination file if it already exists. Default False if not specified.
See Also
Environment Functions

---

## Replace - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReplaceFunction.htm

Replace - MaxBasic Function
Replace(String1: String, String2: String, String3: String): String
Replaces a specified substring with another substring.
All occurrences of String2 in String1 are replaced with String3. String comparison is performed based on the current
Option Compare
setting.
Replace function syntax has these named arguments:
Parameter
Description
String1
Required. String to be searched for String2.
String2
Required. String to be searched for in String1.
String3
Required. String to replace String2 in String1.
For example:
Replace("she comes and she goes", "she", "he")
Returns:
he comes and he goes
See Also
String Functions

---

## ReplaceEnvironmentVariables - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReplaceEnvironmentVariablesFunction.htm

ReplaceEnvironmentVariables - MaxBasic Function
ReplaceEnvironmentVariables(SourceString: String): String
Returns a string with Environment Variables registered in
Company Settings
replaced in the string.
ReplaceEnvironmentVariables syntax has these named arguments:
Parameter
Description
SourceString
Required. The string containing environment variables to be replaced.
Sample code:
Print ReplaceEnvironmentVariables ("c:\Users\UserName\OneDrive - ABC Holdings Limited")
Return %onedrive%

---

## ReplaceQuery - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReplaceQueryFunction.htm

ReplaceQuery - MaxBasic Function
ReplaceQuery(Query: Object)
Replaces the SQL Query.
Used within the AfterQuery code.
The schema of the query being replaced must match the schema of the new MemoryTable.
ReplaceQuery function syntax has these named arguments:
Parameter
Description
Query
Required. The Query to replace the existing SQL Query with.
For example:
Dim MyQuery as Object
MyQuery = CloneQuery
MyQuery.AddIndex("Transaction","TransactionID")
MyQuery.IndexName = "Transaction"
...
...
ReplaceQuery(MyQuery)
See Also
Report Functions

---

## ReplaceRegEx - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReplaceRegExFunction.htm

ReplaceRegEx - MaxBasic Function
ReplaceRegEx(SourceString: String, RegularExpression: String, ReplacementString: String): String
Returns a replaced string based on regular expression.
ReplaceRegEx function syntax has these named arguments:
Parameter
Description
SourceString
Required. The String to be modified.
RegularExpression
Required. The string containing the regular expression.
ReplacementString
The string to replace each match for the RegularExpression.
Sample code:
Dim Transformed as String
' transforms comma separated <link>,<link> into comma separated <a href="link">link</a>
const sourceText = "<http://www.google.com>, <http://www.facebook.com>"
const regex = "<((http://|ftp://|mailto:)[^>]+)>"
const replaceWith = "<a href=""$1"">$1</a>"
Transformed = ReplaceRegEx(sourceText, regex, replaceWith)
Msgbox(Transformed)
Note: For details of the Regular Expression syntax see
Regular expressions (RegEx)
See Also
String Functions

---

## ReportDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReportDateFunction.htm

ReportDate - MaxBasic Function
ReportDate: Date
Some reports allow setting of a ReportDate. This function will return that date, if set, or null. See also
Date
function.
See Also
Report Functions

---

## ReportDestination - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReportDestinationFunction.htm

ReportDestination - MaxBasic Function
ReportDestination: String
Returns the selected destination for the report or document. Available destinations are the same text strings as are in the list of available destinations in the Report selection dialog boxes.
Note: If the report
Destination
selected is
Disk File
or
Mail Message
and the
Format
is
Excel XLSX Format
, the string returned will be
Excel Worksheet
.
See Also
Report Functions

---

## ReportFileName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReportFileNameFunction.htm

ReportFileName - MaxBasic Function
ReportFileName: String
Returns the file name of the report.
See Also
Report Functions

---

## ReportPreview - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReportPreviewFunction.htm

ReportPreview - MaxBasic Function
ReportPreview: Boolean
Returns True if the report has been generated as a Preview.
Available in Document Designers.
See Also
Report Functions

---

## ReportTitle - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReportTitleFunction.htm

ReportTitle - MaxBasic Function
ReportTitle: String
Returns the ReportTitle of the report.
See Also
Report Functions

---

## RestartIterators - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RestartIteratorsFunction.htm

RestartIterators - MaxBasic Function
RestartIterators
Restarts report from first iterator.
Available in GL Report Designer only.
See Also
Report Functions

---

## ReturnForDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ReturnForDateFunction.htm

ReturnForDate - MaxBasic Function
ReturnForDate(Date: Date[, TaxRegime: String]): Number
Return For Date function returns the Return ID of the tax return that the Date is contained in date for a given Tax Regime. If no Tax Regime is given, the Base Tax Regime is used.
ReturnForDate function syntax has these named arguments:
Parameter
Description
Date
Required. The date to find the Return ID for, within a tax regime.
Tax Regime
Optional. The Tax Regime to return the next tax date for. If not supplied, the Base Tax Regime is used.
See Also
GST Functions

---

## RevalueAPForeignBalances - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RevalueAPForeignBalancesFunction.htm

RevalueAPForeignBalances - MaxBasic Function
RevalueAPForeignBalances[(Valuation Date: Date)]
Revalue AP Foreign Balances as at Valuation date. Valuation date must be within current AP period. Exchange rates are drawn from the Rates table.
RevalueAPForeignBalances function syntax has these named arguments:
Parameter
Description
Valuation Date
Optional. Date to revalue balances at. Defaults to current AP Period End Date.
See Also
Accounting Functions

---

## RevalueARForeignBalances - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RevalueARForeignBalancesFunction.htm

RevalueARForeignBalances - MaxBasic Function
RevalueARForeignBalances[(Valuation Date: Date)]
Revalue AR Foreign Balances as at Valuation date. Valuation date must be within current AR period. Exchange rates are drawn from the Rates table.
RevalueARForeignBalances function syntax has these named arguments:
Parameter
Description
Valuation Date
Optional. Date to revalue balances at. Defaults to current AR Period End Date.
See Also
Accounting Functions

---

## RevalueCBForeignBalances - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RevalueCBForeignBalancesFunction.htm

RevalueCBForeignBalances - MaxBasic Function
RevalueCBForeignBalances[(Valuation Date: Date)]
Revalue CB Foreign Balances as at Valuation date. Valuation date must be within current CB period. Exchange rates are drawn from the Rates table.
RevalueCBForeignBalances function syntax has these named arguments:
Parameter
Description
Valuation Date
Optional. Date to revalue balances at. Defaults to current CB Period End Date.
See Also
Accounting Functions

---

## RevalueICStockOnHand - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RevalueICStockOnHandFunction.htm

RevalueICStockOnHand - MaxBasic Function
RevalueICStockOnHand[(Valuation Date: Date)]
Revalue IC Stock on Hand as at Valuation date. Valuation date must be within current IC period.
RevalueICStockOnHand function syntax has these named arguments:
Parameter
Description
Valuation Date
Optional. Date to revalue stock at. Defaults to current IC Period End Date.
See Also
Accounting Functions

---

## RevalueICToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RevalueICToGLFunction.htm

RevalueICToGL - MaxBasic Function
RevalueICToGL
Performs a revaluation of IC to the GL in the current IC period.
See Also
Accounting Functions

---

## Right - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RightFunction.htm

Right - MaxBasic Function
Right(String: String, Length: Number): String
Right string. Returns the rightmost Length characters of String. If String contains less than Length characters, the entire string is returned.
Right function syntax has these named arguments:
Parameter
Description
String
Required. String to return the rightmost characters for.
Length
Required. The length of the string to be returned. If the String is shorter than Length, the entire string is returned.
For example:
Right("courage", 4)
Returns:
rage
See Also
String Functions

---

## Rnd - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RndFunction.htm

Rnd - MaxBasic Function
Rnd: Number
Returns a random number between 0 and 1.
See Also
Number Functions

---

## RollbackTransaction - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RollbackTransactionFunction.htm

RollbackTransaction - MaxBasic Function
RollbackTransaction
Rollback a database transaction.
When a rollback is triggered by unhandled MaxBasic code, a Warning exception is logged in the system
Error Log
. Note that internal Accredo events can be rolled back, but external events such as printing and emailing cannot be rolled back.
See also
BeginTransaction
and
CommitTransaction
.
See Also
Script Functions

---

## Round - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RoundFunction.htm

Round - MaxBasic Function
Round(Number: Number[, Decimals: Number]): Number
Round Number to the number of decimal places specified in Decimals, range for Decimals is maximum 9, minimum -6.
If decimals is omitted, 0 is assumed and Round rounds to an integer. Rounding to nearest 10, 100, 1000 and so on may be achieved with negative decimals.
Round function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be rounded.
Decimals
Optional. Number of decimal places to round Number to.
See Also
Number Functions

---

## RoundDown - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RoundDownFunction.htm

RoundDown - MaxBasic Function
RoundDown(Number: Number[, Decimals: Number]): Number
Rounds Number downwards (that is, towards zero) to the number of decimal places specified in Decimals, range for Decimals is maximum 9, minimum -6.
If decimals is omitted, 0 is assumed and RoundDown rounds to an integer. Rounding down to 10, 100, 1000 and so on may be achieved with negative decimals.
RoundDown function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be rounded down.
Decimals
Optional. Number of decimal places to round Number down to.
See Also
Number Functions

---

## RoundUp - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RoundUpFunction.htm

RoundUp - MaxBasic Function
RoundUp(Number: Number[, Decimals: Number]): Number
Rounds Number upwards (that is, away from zero) to the number of decimal places specified in Decimals, range for Decimals
is maximum 9, minimum -6.
If decimals is omitted, 0 is assumed and RoundUp rounds to an integer. Rounding up to 10, 100, 1000 and so on may be achieved with negative decimals.
RoundUp function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be rounded up.
Decimals
Optional. Number of decimal places to round Number up to.
See Also
Number Functions

---

## RPad - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RPadFunction.htm

RPad - MaxBasic Function
RPad(String1: String, Number: Number[, String2: String]): String
Right pad string. Returns a string with exactly Number of characters. If String2 is specified, the pad character is the first character of String2, otherwise the pad character is a space. The result is String1 padded on the right with the pad character to produce a string of exactly Number characters. If the length of String1 is greater than number, then the leftmost Number characters of String1 are returned.
RPad function syntax has these named arguments:
Parameter
Description
String1
Required. String to be padded with additional characters.
Number
Required. The length of the string to be returned.
String2
Optional. If supplied, the first character of String2 will be used to pad String1.
For example:
Print RPad("12345", 8, "abc")
Returns:
12345aaa
See Also
String Functions

---

## RTrim - MaxBasic Function

Source: https://accredo.co.nz/webhelp/RTrimFunction.htm

RTrim - MaxBasic Function
RTrim(String: String): String
Right trim String. Returns String with trailing spaces removed.
RTrim function syntax has these named arguments:
Parameter
Description
String
Required. String to be trimmed on the right.
Sample code:
Print RTrim("orange   ")
Returns:
orange
See Also
String Functions

---

## ScriptArgs - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ScriptArgsFunction.htm

ScriptArgs - MaxBasic Function
ScriptArgs
ScriptArgs is a global Maxbasic function which returns a collection of Variants corresponding to the arguments passed. In Maxbasic, ScriptArgs can be accessed directly as an Array (0 based), for example:
Print ScriptArgs[0]
ScriptArgs[0] will always contain the file name of the context, for example, if used inside a script, then ScriptArgs[0] will be the name of the script.
ScriptArgs.Count returns the number of parameters passed. ScriptArgs can be passed through the following functions:
PlayScript
CreateCustomForm
CreateCustomWindowForm
EDIExport
EDIImport
'.
Run
' method of all designer based reports.
'
.SetScriptArgs
' method of all designer based reports.
Note: SetScriptArgs method passes the args to the Run method appended after any which are set directly on Run.
The above functions accept an infinite number of arguments after the required parameters, for example:
PlayScript("Script1.pfs", "Parameter1", 0, Date)
Inside
script1.pfs
the three ScriptArgs are accessed as follows:
Dim varString as String
varString = ""
Dim varNumber as Number
varNumber = 0
Dim varDate as Date
varDate = ##
If ScriptArgs.Count > 1 Then
varString = ScriptArgs[1]
varNumber = ScriptArgs[2]
varDate = ScriptArgs[3]
End If
Note: You should consider checking for the presence of SciptArgs before assigning them to variables, this is important as without this check scripts or reports relying on ScriptArgs will fail to run independently of the script that calls them.
See Also
Script Functions

---

## SelectBin - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SelectBinFunction.htm

SelectBin - MaxBasic Function
SelectBin(BinName: String)
Select the printer bin (tray) for a print Job. BinName is a text string exactly as the bin name appears in the printer properties.
Note, this will only function correctly before printing has begun on a page, such as in the BeforeReport code, or in the PageFooter of the previously page.
Note: SelectBin applied in BeforeReport code re-executes the BeforeReport code.
For example:
If PartNumber = 2 then SelectBin("Tray 2")
SelectBin function syntax has these named arguments:
Parameter
Description
Bin Name
Required. Name of the printer bin (tray) to select.
See Also
Report Functions

---

## SellPriceDecimals - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SellPriceDecimalsFunction.htm

SellPriceDecimals - MaxBasic Function
SellPriceDecimals:[(CurrencyCode: String)]: Number
Returns number of decimal places used to display sell prices. If CurrencyCode is empty, the decimal places for base currency is returned.
SellPriceDecimals function syntax has these named arguments:
Parameter
Description
CurrencyCode
Optional. The Currency Code to return the sell price decimals for.
See also the SQL
SellPriceDecimals
function.
See Also
Number Functions

---

## SendKeys - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SendKeysFunction.htm

SendKeys - MaxBasic Function
SendKeys(Keys: String[, Delay: Number)
Send Keys function sends the keystrokes for the Keys string to the active window. If a Delay number is entered, has a delay of Delay milliseconds between keys.
SendKeys function syntax has these named arguments:
Parameter
Description
Keys
Required. The string of keystrokes to be sent to the active window.
Most ASCII characters can be represented by the character itself. E.g. the key sequence FRED can be represented by "FRED".
Some special keys, such as the control keys, function keys etc are encoded in a string enclosed by {braces}.
See the table below.
Delay
Optional. If entered, there will be a delay of Delay milliseconds between keys.
Key/Character
SendKey
Description
~
{~}
Send a tilde (~)
!
{!}
Send an exclamation point (!)
^
{^}
Send a caret (^)
+
{+}
Send a plus sign (+)
Backspace
{BACKSPACE} or {BKSP} or {BS}
Send a Backspace keystroke
Break
{BREAK}
Send a Break keystroke
Caps Lock
{CAPSLOCK}
Press the Caps Lock Key (toggle on or off)
Clear
{CLEAR}
Clear the field
Delete
{DELETE} or {DEL}
Send a Delete keystroke
Insert
{INSERT} or {INS}
Send an Insert keystroke
Cursor control arrows
{LEFT} / {RIGHT} / {UP} / {DOWN}
Send a Left/Right/Up/Down Arrow
End
{END}
Send an End keystroke
Enter
{ENTER} or ~
Send an Enter keystroke
Escape
{ESCAPE}
Send an Esc keystroke
F1 through F12
{F1} through {F12}
Send a Function keystroke
Home
{HOME}
Send a Home keystroke
Numlock
{NUMLOCK}
Send a Num Lock keystroke
Page Down
Page Up
{PGDN}
{PGUP}
Send a Page Down or Page Up keystroke
Print Screen
{PRTSC}
Send a Print Screen keystroke
Scroll lock
{SCROLLLOCK}
Press the Scroll lock Key (toggle on or off)
TAB
{TAB}
Send a TAB keystroke
To specify keys combined with any combination of SHIFT, CTRL, and ALT keys, precede the key code with one or more of the following:
For SHIFT prefix with +
For CTRL  prefix with ^
For ALT   prefix with %
Example with modifier keys:
const Ctrl = "^"
const Alt = "%"
const Shift = "+"
SendKeys(Ctrl & Alt & Shift & "A")
SendKeys(Ctrl & "A"). ' select all text in the script editor
SendKeys(Ctrl & Shift & "I")  ' indent all text in the script editor
See Also
Script Functions

---

## SerialNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SerialNoFunction.htm

SerialNo - MaxBasic Function
SerialNo: String
Serial No function returns the application serial number.
See Also
Application Functions

---

## SessionCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SessionCodeFunction.htm

SessionCode - MaxBasic Function
SessionCode: String
Session Code returns the session type for the current user.
See Also
Environment Functions

---

## SetAccredoDefaultPrinter - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetAccredoDefaultPrinterFunction.htm

SetAccredoDefaultPrinter - MaxBasic Function
SetAccredoDefaultPrinter(PrinterName: String)
Sets the Accredo Default Printer to PrinterName. If the PrinterName is invalid, an exception message is displayed.
SetAccredoDefaultPrinter function syntax has these named arguments:
Parameter
Description
Printer Name
Required. The Printer Name to set as the Accredo Default Printer.
See Also
Environment Functions

---

## SetConfigValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetConfigValueFunction.htm

SetConfigValue - MaxBasic Function
SetConfigValue(Name: String, Value: String)
SetConfigValue function creates a variable / value pair for the session which can be read using
GetConfigValue.
SetConfigValue function syntax has these named arguments:
Parameter
Description
Name
Required. A valid variable name.
Value
Required. The associated value.

---

## SetDuplex - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetDuplexFunction.htm

SetDuplex - MaxBasic Function
SetDuplex(DuplexMode: String)
Set the printer duplex mode. Options for DuplexMode are:
SetDuplex("One side")
- Prints on one side of paper.
SetDuplex("Long edge")
- Prints on both sides of paper, flips on the long edge.
SetDuplex("Short edge")
- Prints on both sides of paper, flips on the short edge.
Note, this will only function correctly before printing has begun on a page, such as in the BeforeReport code, or in the PageFooter of the previously page.
Note: SetDuplex applied in BeforeReport code re-executes the BeforeReport code.
SetDuplex function syntax has these named arguments:
Parameter
Description
Duplex Mode
Required. The printer duplex mode to use. Valid values are:
"One Side"
"Long Edge"
"Short Edge"
See Also
Report Functions

---

## SetEnvironmentVariable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetEnvironmentVariableFunction.htm

SetEnvironmentVariable - MaxBasic Function
SetEnvironmentVariable(EnvironmentVariable: String, Value: String): Boolean
SetEnvironmentVariable function sets the value of an Environment Variable which may be retrieved using
GetEnvironmentVariable
.
Environment variables persist within a session and across company logins. Returns the value of an environment variable.
Returns
True
if successful.
SetEnvironmentVariable function syntax has these named arguments:
Parameter
Description
Environment Variable
Required. The environment variable to be set. Must meet the rules for valid Environment Variable names.
Value
Required. The value to assign.

---

## SetExchangeRate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetExchangeRateFunction.htm

SetExchangeRate - MaxBasic Function
SetExchangeRate(CurrencyCode: String, RateType: String, Date: Date, NewRate: Number[, ExpiryDate: Date])
Passed a CurrencyCode, Rate Type, Date and Exchange Rate sets and Exchange Rate in the Rate Table.
GetExchangeRate function syntax has these named arguments:
Parameter
Description
Currency Code
Required. The currency code to set the rate for.
Rate Type
Required. The type of exchange rate.
Date
Required. The effective date for the exchange rate.
New Rate
Required. The exchange rate to set, must be between the Exchange Rare Limits for the currency.
Expiry Date
Optional. The expiry date for the rate if any.
See also the the Web Services SetExchangeRate function.
See Also
Foreign Exchange Functions

---

## SetPermUser - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetPermUserFunction.htm

SetPermUser - MaxBasic Function
SetPermUser(NewUserCode: String, Password:String) : OldUserCode
Sets the User Code for permissions within the executing
encrypted script
, for example where elevated permissions are wanted for event scripts. Returns the old Permission User Code.
If the NewUserCode is invalid, an exception message is displayed. The Permission User Code is reset on script completion to the logged in user.
SetPermUser function can only be called in an encrypted script (.pfz extension).
Saving (and encrypting) and Loading (and decrypting) encrypted scripts in the script editor requires Write permission for Company > Scripts > Encrypted, in addition other scripting permissions.
Executing encrypted scripts requires at least Read permission for Company > Scripts > Encrypted, in addition other scripting permissions.
SetPermUser function syntax has these named arguments:
Parameter
Description
New User Code
Required. The User Code to set as the Permission User.
Returns the previous Permission User.
Password
Required. The password for the Permission User.
Example use:
OldPermUser = SetPermUser("ACCREDO", "ACCREDO")
try
msgbox("OldPermUser:" & OldPermUser & ", CurrentPermUser:" & GetPermUser)
Dim datARCust as Object
datARCust = CreateObject("Accredo.ARCustomerData")
Print datARCust.Balance1
finally
SetPermUser(OldPermUser, "")
end try

---

## SetPreference - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetPreferenceFunction.htm

SetPreference - MaxBasic Function
SetPreference(PreferenceName: String, Value: Number): Number
Set Preference function sets a Workstation Preference to the value entered. Returns the previous value of the workstation preference.
See
Application Preference Strings
for a list of all available preferences. See also
GetPreference
function.
Examples are:
General > Mail Integration
PreferenceName: Generic\MAPIStyle
0 = Autodetect (default)
1 = Outlook
2 = Simple MAPI
3 = Full MAPI
Advanced > TAPI diagnostics level
PreferenceName: Generic\TAPIDiagLevel
0 = None
1 = significant messages
2 = all messages
Advanced > Printer diagnostics level
PreferenceName: Generic\PrinterDiagLevel
0 = None
1 = significant messages
2 = all messages
SetPreference function syntax has these named arguments:
Parameter
Description
Preference Name
Required. The workstation preference to be set. Some valid values are "Generic\MAPIStyle", "Generic\TAPIDiagLevel" or "Generic\PrinterDiagLevel".
Value
Required. Value to set the workstation preference to.
In This Section
Application Preference Strings
See Also
Application Functions

---

## SetRateLimits - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetRateLimitsFunction.htm

SetRateLimits - MaxBasic Function
SetRateLimits (CurrencyCode: String, LowerLimit: Number, UpperLimit: Number)
Passed a CurrencyCode, LowerLimit and UpperLimit. Sets Minimum and Maximum Rate for currency in
FX Exchange Rate Limits
.
SetRateLimits function syntax has these named arguments:
Parameter
Description
Currency Code
Required. The currency code to set the rate limit for.
Lower Limt
Required. The Minimum rate to be set.
Upper Limit
Required. The Maximum rate to set.
See also the Web Services SetRateLimits function.
See Also
Foreign Exchange Functions

---

## SetScriptReportResult - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetScriptReportResultFunction.htm

SetScriptReportResult - MaxBasic Function
SetScriptReportResult(Success: Boolean, Filename: String, ResultFileOrError: String)
Set Script Report Result function notifies an Accredo App that a report has run.
For successful reports, Success is set to True, the report Filename is sent, and the name of the pdf file to create is sent as ResultFileOrError. The result file pdf file is shown on the app.
For unsuccessful reports, Success is set to False, the report filename is sent, and the error message to display is sent as ResultFileOrError. The error message is displayed on the app.
See the
App Sample Report Script
for an example of this function.
SetScriptReportResult function syntax has these named arguments:
Parameter
Description
Success
Required. True if the report ran successfully, or False if not.
Filename
Required. The filename of the report that was run.
ResultFileOrError
Required. If the report ran successfully, the pdf file name of the report result. If the report did not run successfully, the error message to display.
For example:
SetScriptReportResult(True, "c:\MyReport.pdf", "ARAgedTrialBalance.pdf")
displays the report as ARAgedTrialBalance.pdf on the app.
SetScriptReportResult(False, "c:\MyReport.pdf", "Report did not run")
displays the error message on the app.
See Also
Script Functions

---

## SetSessionDesc - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetSessionDescFunction.htm

SetSessionDesc - MaxBasic Function
SetSessionDesc(Description: String)
Sets the description for the current session to
Description
.
This is useful for naming COM sessions where more than one COM session is active. The session description can be viewed by customising Description into
Logged-In Users
.
See Also
User Functions

---

## SetStampUser - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetStampUserFunction.htm

SetStampUser - MaxBasic Function
SetStampUser(NewUserCode: String)
Sets the User Code for creation and modification stamps. If the NewUserCode is invalid, an exception message is displayed. The StampUserCode is reset on login to become the logged in user.
Only the Users with the Company > Scripts > SetStampUser permission can call this function.
SetStampUser function syntax has these named arguments:
Parameter
Description
New User Code
Required. The User Code to set as the Stamp User.
Returns the previous Stamp User.
See Also
User Functions

---

## SetSystemDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetSystemDateFunction.htm

SetSystemDate - MaxBasic Function
SetSystemDate(Date: Date)
Sets the System Date to the Date specified.
SetSystemDate function syntax has these named arguments:
Parameter
Description
Date
Required. Date to set the system date to.
See Also
Date Functions

---

## SetSystemPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SetSystemPeriodFunction.htm

SetSystemPeriod - MaxBasic Function
SetSystemPeriod(PeriodID: Number)
Sets the System Period ID to PeriodID.
SetSystemPeriod function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to set the system period to.
See Also
Period Functions

---

## Sgn - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SgnFunction.htm

Sgn - MaxBasic Function
Sgn(Number: Number): Number
Sign of number.
If number is:
Sgn returns
Greater than zero
+1
Equal to zero
0
Less than zero
-1
Sgn function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be evaluated.
See Also
Number Functions

---

## Shell - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ShellFunction.htm

Shell - MaxBasic Function
Shell(Command: String[, ShowWindow: Number, Wait: Boolean, Timeout: Number]): Variant
Shell function executes the external program Command. ShowWindow is an optional number parameter controlling display of the external program.
Returns -1 if the timeout is exceeded, 0 if the process cannot be launched, or ProcessID if the command completed successfully.
Shell function syntax has these named arguments:
Parameter
Description
Command
Required. The external program to be executed.
Show Window
Optional. Valid values are as follows,
Hide = 0
ShowNormal = 1
ShowMinimized = 2
ShowMaximized = 3
ShowNoActivate = 4
Show = 5
Minimize = 6
ShowMinNoActive = 7
ShowNA = 8
Restore = 9
ShowDefault = 10
Wait
Optional. When True, the Shell function will wait for completion of the program. Defaults to False.
Timeout
Optional. The number of milliseconds to wait for completion if Wait is true. If this is omitted, an infinite time is assumed.
See Also
Environment Functions

---

## ShowAlarms - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ShowAlarmsFunction.htm

ShowAlarms - MaxBasic Function
ShowAlarms(Boolean: Boolean[, ShowModal: Boolean]): Boolean
Controls the display of modal alarms while a script is running, takes a Boolean parameter that sets the new state of modal alarm handling, and returns the old state. If ShowAlarms is not specified alarms are not displayed. To show alarms in a normal window rather than modally, set ShowModal to False.
ShowAlarms function syntax has these named arguments:
Parameter
Description
Boolean
Required. When
True
, shows modal alarms while script is running. When
False
, specified alarms are not displayed.
ShowModal
Optional. When
True
alarms are shown modally. When
False
, alarms are shown in a normal, not modal window. Defaults to
True
.
See Also
Script Functions

---

## ShowSQLProgress - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ShowSQLProgressFunction.htm

ShowSQLProgress - MaxBasic Function
ShowSQLProgress(Boolean: Boolean)
Show SQL Progress function controls display of the progress bar in SQL Queries. Returns the previous state so you can save and restore the state if wanted. Defaults to True. Once set, the state remains for the session unless it is reset.
ShowSQLProgress function syntax has these named arguments:
Parameter
Description
Boolean
Required. Sets the state of the cursor bar in SQL queries.
For example:
ShowSQLProgress(False)
Customers = ExecuteSQL("Select * from ARCust")
BrowseDataset(Customers)
ShowSQLProgress(True)
See Also
Environment Functions

---

## Sleep - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SleepFunction.htm

Sleep - MaxBasic Function
Sleep(Milliseconds: Number)
Pause execution for specified number of Milliseconds.
Sleep function syntax has these named arguments:
Parameter
Description
Milliseconds
Required. Number of milliseconds to pause the execution for.
See Also
Date Functions

---

## Split - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SplitFunction.htm

Split - MaxBasic Function
Split(Text: String, Delimiter: String): StringList
Splits a text string into a list of strings, separated by a delimiter. Given a Text string and Delimiter string, returns a
StringList Object
of tokenised strings.
Split function syntax has these named arguments:
Parameter
Description
Text
Required. String to be split.
Delimiter
Required. The character at which to split Text.
Sample code:
strText = "I2 B1 B3 C5 F1 C8"
Dim AccredoTokens as Object
AccredoTokens = Split(strText, " ")
Print "Source:" & strText
If AccredoTokens.Count > 0 Then
For x = 0 to AccredoTokens.Count - 1
Print AccredoTokens[x]
Next x
Else
Print "Not split"
End If
Returns:
Source:I2 B1 B3 C5 F1 C8
I2
B1
B3
C5
F1
C8
See Also
String Functions

---

## StampHash - MaxBasic Function

Source: https://accredo.co.nz/webhelp/StampHashFunction.htm

StampHash - MaxBasic Function
StampHash(HashTotal: String)
Available in the CB Electronic Banking Designer only.
Updates the CBSUM HashTotal field with the hash total.
StampHash function syntax has these named arguments:
Parameter
Description
HashTotal
The hash total to be updated in the HashTotal field.
Note: If a bank account number contains alphanumeric characters, the built in hash total calculation will for the line will be zero (0). For alphanumeric bank account numbers, calculate the Hash Total in MaxBasic, then use the StampHash function to set the CBSUM Hash Total.
See Also
Script Functions

---

## StatementDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/StatementDateFunction.htm

StatementDate - MaxBasic Function
StatementDate: Date
Some reports have a StatementDate. This function will return that date, if set, or null. See also
Date
function.
See Also
Report Functions

---

## StatementPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/StatementPeriodFunction.htm

StatementPeriod - MaxBasic Function
StatementPeriod: Number
Some reports allow setting of a Statement Period. This function will return that period, if set, or null.
See Also
Report Functions

---

## Str - MaxBasic Function

Source: https://accredo.co.nz/webhelp/StrFunction.htm

Str - MaxBasic Function
Str(Expression: Variant): String
Converts Expression into a string. This converts the expression into its string representation. This is not often required as the & operator converts expressions to strings before concatenation.
Str function syntax has these named arguments:
Parameter
Description
Expression
Required. Expression to be converted to a string.
Sample code:
Print Str(555)
Returns:
"555"
See Also
String Functions

---

## SubtractGST - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SubtractGSTFunction.htm

SubtractGST - MaxBasic Function
SubtractGST(Amount: Number[, Code: String, EffectiveDate: Date])
Subtract GST from Amount. GST at the rate applicable to Code and EffectiveDate
is subtracted from Amount. If Code is not entered, the rate for the default GST code is used. If EffectiveDate is not specified, the current
accounting System Date
date is used.
SubtractGST function syntax has these named arguments:
Parameter
Description
Amount
Required. The amount to subtract GST from.
Code
Optional. The GST Code to be used.
Effective Date
Optional. The effective date to apply GST at.
See Also
GST Functions

---

## Sum - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SumFunction.htm

Sum - MaxBasic Function
Sum(Parameter1: Number, Parameter2: Number[, Parameter3: Number, ...])
Return total values for field parameters.
Available in Analysis Reports only.
Sum function syntax has these named arguments:
Parameter
Description
Parameter 1
Required. First parameter to be added to the total.
Parameter 2
Required. Second parameter to be added to the total.
Parameter 3 ...
Optional. Additional parameters to be added to the total.
See Also
Report Functions

---

## SystemAnyPresent - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemAnyPresentFunction.htm

SystemAnyPresent - MaxBasic Function
SystemAnyPresent(Module Codes: String): Boolean
SystemAnyPresent function checks if any of a list of modules are present at the System level. Returns
True
if any module in the list is present,
False
otherwise.
SystemAnyPresent function syntax has these named arguments:
Parameter
Description
Module Codes
Required. A semicolon separated list of module codes.

---

## SystemDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemDateFunction.htm

SystemDate - MaxBasic Function
SystemDate: Date
System date returns the current System Date, see
System Date & System Period
.
See also the SQL
SystemDate
function and the Web Services
SystemDate
function.
See Also
Date Functions

---

## SystemLogin - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemLoginFunction.htm

SystemLogin - MaxBasic Function
SystemLogin(UserCode: String, Password: String): Boolean
System Login function logs user with UserCode and Password supplied into the system. Returns
True
if successful,
False
otherwise. Only available when
Use Single Sign On
is turned on.
SystemLogin function syntax has these named arguments:
Parameter
Description
User code
Required. The User Code to log in.
A unique System User email address may be supplied as an alternative to UserCode.
Password
Required. The password for the user.

---

## SystemLoginUserCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemLoginUserCodeFunction.htm

SystemLoginUserCode - MaxBasic Function
SystemLoginUserCode: String
System Login User Code function returns the user code of the logged in system user.

---

## SystemLogout - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemLogoutFunction.htm

SystemLogout - MaxBasic Function
SystemLogout: Boolean
System Logout function logs the current user out of the system. Returns
True
if successful,
False
otherwise. Only available when
Use Single Sign On
is turned on.

---

## SystemPeriod - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemPeriodFunction.htm

SystemPeriod - MaxBasic Function
SystemPeriod: Number
Returns the current System Period ID, see
System Date & System Period
.
See also the SQL
SystemPeriod
function and the Web Services
SystemPeriod
function.
See Also
Period Functions

---

## SystemSetting - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemSettingFunction.htm

SystemSetting - MaxBasic Function
SystemSetting(SettingName: String): Variant
System Settings function reads and returns a
system setting
value as a variant.
SystemSetting function syntax has these named arguments:
Parameter
Description
Setting Name
Required. Name of the
System Setting
.
In This Section
System Settings Documentation
See Also
System Functions

---

## SystemUserPermission - MaxBasic Function

Source: https://accredo.co.nz/webhelp/SystemUserPermission.htm

SystemUserPermission - MaxBasic Function
SystemUserPermission(PermissionString: String): Number
System User Permission function returns the permission level for the logged in System User for the specified
permission string
as follows:
None = 0
Allow = 1
Read = 1
Write = 2
Control = 3
SystemUserPermission
function syntax has these named arguments:
Parameter
Description
Permission String
Required. The system permission string to get user access for.
In This Section
System User Permission Strings
See Also
System Functions

---

## TaxName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TaxNameFunction.htm

TaxName - MaxBasic Function
TaxName[(TaxRegime: String)]: String
Tax Name function returns the Tax Name for a given Tax Regime. If no Tax Regime is given, the Tax Name for the Base Tax Regime is returned.
TaxName function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the Tax Name for. If not supplied, the Base Tax Regime is used.

---

## TaxNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TaxNoFunction.htm

TaxNo - MaxBasic Function
TaxNo[(TaxRegime: String)]: String
Tax No function returns the Tax Number for a given Tax Regime. If no Tax Regime is given, the Tax Number for the Base Tax Regime is returned.
TaxNo function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the Tax Number for. If not supplied, the Base Tax Regime is used.

---

## TaxNoName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TaxNoNameFunction.htm

TaxNoName - MaxBasic Function
TaxNoName[(TaxRegime: String)]: String
Tax No Name function returns the Tax Number Name for a given Tax Regime. If no Tax Regime is given, the Tax Number Name for the Base Tax Regime is returned.
TaxNo function syntax has these named arguments:
Parameter
Description
Tax Regime
Optional. The Tax Regime to return the Tax Number Name for. If not supplied, the Base Tax Regime is used.

---

## TempFileName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TempFileNameFunction.htm

TempFileName - MaxBasic Function
TempFileName[(Extension: String)]: String
Temp File Name function returns the name of a new temporary file with the extension specified. If no extension is provided the default TMP extension is used. The temporary file is created in the standard windows temporary file directory. The temporary file should be deleted.
TempFileName function syntax has these named arguments:
Parameter
Description
Extension
Optional. The three character temporary file extension for the temporary file. Defaults to TMP.
See Also
Environment Functions

---

## TerminalServer - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TerminalServerFunction.htm

TerminalServer - MaxBasic Function
TerminalServer: Boolean
Terminal Server function returns
True
if the client is running in a Remote Desktop Host session, otherwise returns
False
.
See Also
Environment Functions

---

## TermsDate - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TermsDateFunction.htm

TermsDate - MaxBasic Function
TermsDate(Date: Date, Unit: String, Count: Number [DayOfMonth: Number]): Date
Returns a Date having added the count of units (Periods, Months, Weeks, Days) optionally forcing the DayOfMonth for Months.
TermsDate function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return Terms Date for.
Unit
Required. Values: P (Period), M (Months), W (Weeks), D (Days)
Count
Required. Count of Units to add.
DayOfMonth
Optional. For Months unit force the dat of month.

---

## Time - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TimeFunction.htm

Time - MaxBasic Function
Time: Time
Returns the current machine time.
See Also
Date Functions

---

## TimeValue - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TimeValueFunction.htm

TimeValue - MaxBasic Function
TimeValue(TimeParameter: String/Date/Time/DateTime): Time
TimeValue returns a time value for TimeParameter
.
The format matches the default date / time format.
TimeValue function syntax has these named arguments:
Parameter
Description
TimeParameter
Required. Parameter to be formatted as a time. This can be a String, Date, Time or DateTime parameter, including ISO 8601 Date Time strings.
See Also
Date Functions

---

## TimeZoneOffset - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TimeZoneOffsetFunction.htm

TimeZoneOffset - MaxBasic Function
TimeZoneOffset: integer
TimeZoneOffset returns the current local timezone offset from UTC in minutes.

---

## TransferAPToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferAPToGLFunction.htm

TransferAPToGL - MaxBasic Function
TransferAPToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from AP up to the specified period.
TransferAPToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransferARToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferARToGLFunction.htm

TransferARToGL - MaxBasic Function
TransferARToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from AR up to the specified period.
TransferARToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransferCBToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferCBToGLFunction.htm

TransferCBToGL - MaxBasic Function
TransferCBToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from CB up to the specified period.
TransferCBToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransferFAToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferFAToGLFunction.htm

TransferFAToGL - MaxBasic Function
TransferFAToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from FA up to the specified period.
TransferFAToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransferGSTToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferGSTToGLFunction.htm

TransferGSTToGL - MaxBasic Function
TransferGSTToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from GST up to the specified period.
TransferGSTToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransferICToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferICToGLFunction.htm

TransferICToGL - MaxBasic Function
TransferICToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from IC up to the specified period.
TransferICToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransferJCToGL - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransferJCToGLFunction.htm

TransferJCToGL - MaxBasic Function
TransferJCToGL([Period: Number])
Generate Transaction Batch(es) for the GL of data from JC up to the specified period.
TransferJCToGL function syntax has these named arguments:
Parameter
Description
Period
Optional. Period to generate batches up to. Defaults to the last transfer period.
See Also
Accounting Functions

---

## TransformPhoneNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TransformPhoneNoFunction.htm

TransformPhoneNo - MaxBasic Function
TransformPhoneNo(PhoneNumber: String): String
Transform Phone No function returns a string transformed to a Phone number using transformations.
TransformPhoneNo function syntax has these named arguments:
Parameter
Description
Phone Number
Required. The phone number as a string to be transformed.
See Also
String Functions

---

## Trim - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TrimFunction.htm

Trim - MaxBasic Function
Trim(String: String): String
Returns String with leading and trailing spaces removed.
Trim function syntax has these named arguments:
Parameter
Description
String
Required. String to be trimmed on the left and right.
Sample code:
Print Trim("   persimmon   ")
Returns:
"persimmon"
For use in SQL, see also
SQL TRIM Function
.
See Also
String Functions

---

## TryInteractive - MaxBasic Function

Source: https://accredo.co.nz/webhelp/TryInteractiveFunction.htm

TryInteractive - MaxBasic Function
TryInteractive: Boolean
Try Interactive function attempts to switch the IsInteractive setting to
True
. Returns
True
if successful, otherwise returns
False
.
See
Company IsInteractive Setting
.

---

## UBound - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UBoundFunction.htm

UBound - MaxBasic Function
UBound (Arrayname: String): Number
Returns a number containing the largest available subscript for the dimension of an array or JSON array.
The UBound function is used with the
LBound
function to determine the size of an array. Use the LBound function to find the lower limit of an array dimension.
UBound function syntax has these named arguments:
Parameter
Description
Array Name
Required. Name of the array variable; follows standard variable naming conventions.
See Also
Array Functions

---

## UnlockCompany - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UnlockCompanyFunction.htm

UnlockCompany - MaxBasic Function
UnlockCompany
Unlocks a previously locked company if executed by the Master User.
See Also
Company Functions

---

## UnpostedBatches - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UnpostedBatchesFunction.htm

UnpostedBatches - MaxBasic Function
UnpostedBatches: Boolean
Returns
True
if there are unposted batches for the reporting period,
False
otherwise.
See Also
General Ledger Functions

---

## UntransferredBatches - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UntransferredBatchesFunction.htm

UntransferredBatches - MaxBasic Function
UntransferredBatches: Boolean
Returns
True
if there are untransferred batches for the reporting period,
False
otherwise.
See Also
General Ledger Functions

---

## UnZipFiles - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UnZipFilesFunction.htm

UnZipFiles - MaxBasic Function
UnZipFiles(FileName: String, FolderName: String)
Extract contents from a zip file to a given folder. If the folder does not exist, it will be created,
UnZipFiles function syntax has these named arguments:
Parameter
Description
File Name
Required. The zip or 7z file name. If file extension is 7z then 7 zip is used for extraction.
Folder Name
Required. The folder to extract files into.
For example:
Unzipfiles("c:\test.zip", "c:\Exports")
extracts the contents of c:\Test.zip into c:\Exports.
See Also
Script Functions

---

## UOMActive - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UOMActiveFunction.htm

UOMActive - MaxBasic Function
UOMActive: Boolean
UOMActive function returns
True
if UOM Status is Active, otherwise returns
False
.

---

## UpgradeTable - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UpgradeTableFunction.htm

UpgradeTable - MaxBasic Function
UpgradeTable(TableFileName: String, TemplateFileName: String[, UpdateFields: Boolean, ReplaceSchema: Boolean]): Boolean
Uses an XML Schema file
TemplateFileName
to upgrade or create a table. If
TableFileName
is not found, a new .ADB table file will be created. If
TableFileName
is found, the table will be upgraded.
The
TableFileName
file is saved in the data directory.
TemplateFileName
must be a fully specified path. Template files can be generated using the
GenerateSchema
function.
The function returns
True
if the upgrade was successful, or
False
if it was unsuccessful.
Default without optional parameters specified (or both false) is non-destructive upgrade, i.e. from the template schema, add a new table or add fields to an existing table or add indexes to an existing table or make existing string fields bigger.
Note:
UpgradeTable function syntax has these named arguments:
Parameter
Description
Table File Name
Required. The file name of the table in the data directory to be created or upgraded.
Template File Name
Required. The template used to upgrade the table.
Update Fields
Optional, default false. If true then field types and sizes will change to match the template schema - this could lose or corrupt data.
Replace Schema
Optional, default false. If true then make the old table match the template schema and do the best effort with copying data.
For existing tables, any fields that are not included in the XML schema file and have not been renamed to match new Custom fields added in the schema will be dropped and data in these fields will be lost. This also applies to custom indexes, as only indexes in the XML schema will be retained.
For example, to add a Category 3 field to Customers, create a ARCAT3.ADB table, and
extend
the ARCUST.pdb table to add the new Category 3 field.
UpgradeTable("ARCAT3.ADB", "c:\ARCategory3.xml")
UpgradeTable("ARCUST.PDB", "c:\ARCustExtensions.xml")
See Also
Tables Functions

---

## Upper - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UpperFunction.htm

Upper - MaxBasic Function
Upper(String: String): String
Returns String in upper case.
Upper function syntax has these named arguments:
Parameter
Description
String
Required. String to return in upper case.
For example:
Upper("shout")
Returns:
SHOUT
See Also
String Functions

---

## URLEncode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/URLEncodeFunction.htm

URLEncode - MaxBasic Function
URLEncode(URLText: String[, URLProtocol: String]): String
Given a string containing a URL, returns URL with percent encoded reserved characters.
Protocol can optionally be passed as a second parameter, default if not included in URL and not passed explicitly is "HTTP".
URLEncode function syntax has these named arguments:
Parameter
Description
URLText
Required. String to encode with percent encoded reserved characters.
URLProtocol.
Optional. The protocol to use, defaults to "HTTP".
Sample code:
MyUrl = "www.example.com/index.html?param=1 &anotherParam=2"
MyURL = URLEncode(MyURL)
print MyURL
Returns:
http://www.example.com/index.html?param=1%20&anotherParam=2
See Also
Web Functions

---

## UserPermission - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UserPermissionFunction.htm

UserPermission - MaxBasic Function
UserPermission(PermissionString: String): Number
User Permission function returns the users permission level for the specified
permission string
as follows:
None = 0
Allow = 1
Read = 1
Write = 2
Control = 3
UserPermission
function syntax has these named arguments:
Parameter
Description
Permission String
Required. The permission string to get user access for.
In This Section
User Permission Strings
See Also
User Functions

---

## UserSetting - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UserSettingFunction.htm

UserSetting - MaxBasic Function
UserSetting(UserSettingName: String[, UserCode: String]): Variant
User Setting function returns the users setting for the specified
user setting string
, for the current user or specified user. If UserCode is not specified, the setting is returned for the current user.
UserSetting function syntax has these named arguments:
Parameter
Description
User Setting Name
Required. The user setting string to get user setting for.
User Code
Optional. The user code to return the setting for. If no user code is specified, the setting for the current user is returned.
In This Section
User Setting Strings

---

## UseWindowsDefaultPrinter - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UseWindowsDefaultPrinterFunction.htm

UseWindowsDefaultPrinter - MaxBasic Function
UseWindowsDefaultPrinter
Sets the Accredo Default Printer to the Windows Default Printer.
See Also
Environment Functions

---

## UTCDateTimeToLocal - MaxBasic Function

Source: https://accredo.co.nz/webhelp/UTCDateTimeToLocalFunction.htm

UTCDateTimeToLocal - MaxBasic Function
UTCDateTimeToLocal(UTCTime: DateTime): DateTime
Converts a UTC (Coordinated Universal Time) datetime to local timezone datetime.
UTCDateTimeToLocal function syntax has these named arguments:
Parameter
Description
UTCTime
Required. The datetime value to convert to local timezone.
Sample code:
Print FormatDateTime(UTCDateTimeToLocal(#1/1/2025 2.26 pm#))

---

## Val - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValFunction.htm

Val - MaxBasic Function
Val(String: String): Number
Returns a number representing the value of String. If String is empty, a value of 0 is returned.
Val function syntax has these named arguments:
Parameter
Description
String
Required. String expression to be evaluated.
See Also
Number Functions

---

## ValidateLedger - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValidateLedgerFunction.htm

ValidateLedger - MaxBasic Function
ValidateLedger: Boolean
ValidateLedger function
validates
the General Ledger. Returns
True
if valid, otherwise returns
False
.
See Also
Accounting Functions

---

## ValidBankAccountNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValidBankAccountNoFunction.htm

ValidBankAccountNo - MaxBasic Function
ValidBankAccountNo(BankAcct: String[, CountryCode: String]): Boolean
Returns a boolean indicating if the bank account number is valid for the country.
Currently only NZ bank account number can be validated.
ValidBankAccountNo function syntax has these named arguments:
Parameter
Description
BankAcct
Required. The bank account to be validated.
Validation expects either a number zero padded to 2.4.8.2 or 2.4.8.3 digits or with separators between segments.
CountryCode
Optional, defaults to Company Country Code if not specified. The country for the Bank Account. Currently only NZ supported other Country Codes will error.
For example:
ValidBankAccountNo("0109020006838900","NZ")
ValidBankAccountNo("01090200068389000","NZ")
ValidBankAccountNo("01-0902-0068389-00","NZ")
ValidBankAccountNo("01 0902 00068389 000","NZ")
ValidBankAccountNo("01.0902.0068389.00","NZ")
All Return: True
ValidBankAccountNo("010902006838900","NZ")
Returns: False
because Account No is not padded to 8 characters.
See Also
String Functions

---

## ValidCode - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValidCodeFunction.htm

ValidCode - MaxBasic Function
ValidCode(aCode: String[, ExcludeChars: String]): Boolean
Returns
True
for a valid Code with no non-printing characters. Characters must not be less than Ascii(32) or greater than Ascii(126), and must not contain spaces, wildcards (such as *, ?, %, _), or csv punctuation (such as " ,). If the ExcludeChars is included, wildcard and csv punctuation in ExcludeChars will not be considered. Non-printing characters and leading spaces are always considered invalid. Returns
False
for an invalid code.
ValidCode function syntax has these named arguments:
Parameter
Description
aCode
Required. The code to be validated.
ExcludeChars
Optional. Any wildcard or csv characters to be excluded from the validation.
See Also
String Functions

---

## ValidEmailAddress - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValidEmailAddressFunction.htm

ValidEmailAddress - MaxBasic Function
ValidEmailAddress(EmailAddress: String): Boolean
Returns
True
for a valid email address or
False
for an invalid email address.
ValidEmailAddress function syntax has these named arguments:
Parameter
Description
Email Address
Required. The email address to be validated.
See Also
String Functions

---

## ValidFileName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValidFileNameFunction.htm

ValidFileName - MaxBasic Function
ValidFileName(FileName: String): String
Strips out invalid characters to return a valid file name.
ValidFileName function syntax has these named arguments:
Parameter
Description
File Name
Required. The file name to be evaluated.
Note that the words
CON
,
PRN
,
AUX
,
CLOCK$
and
NUL
are reserved words and cannot be used as file names. These will result in an empty string.
See Also
String Functions

---

## ValidTaxNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ValidTaxNoFunction.htm

ValidTaxNo - MaxBasic Function
ValidTaxNo(TaxNo: String[, CountryCode: String]): Boolean
Returns a boolean indicating if the tax number is valid for the country.
Currently only NZ IRD numbers can be validated.
ValidTaxNo function syntax has these named arguments:
Parameter
Description
TaxNo
Required. The tax number to be validated.
CountryCode
Optional, defaults to Company Country Code if not specified. The country for the Tax Number. Currently only NZ supported other Country Codes will error.
For example:
ValidTaxNo("56-748-393", "NZ")
Returns: True
See Also
String Functions

---

## VariancePercent - MaxBasic Function

Source: https://accredo.co.nz/webhelp/VariancePercentFunction.htm

VariancePercent - MaxBasic Function
VariancePercent(Actual: Number, Budget: Number): Number
Calculates the variance percent of two numbers as follows,
VariancePercent(Actual, Budget) = (Budget - Actual)/Budget * 100, with variance sign matching.
VariancePercent function syntax has these named arguments:
Parameter
Description
Actual
Required. Actual amount to be calculated as a variance percent of the Budget.
Budget
Required. Budget Amount to calculate Actual as a variance percent of.
See Also
Number Functions

---

## ViewPDF - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ViewPDFFunction.htm

ViewPDF - MaxBasic Function
ViewPDF(FileName: String): Object
ViewPDF function opens the file specified in File Name in a Saved Report form and returns the form Object
ViewPDF function syntax has these named arguments:
Parameter
Description
File Name
Required. The name of the file to be viewed.
Note: ViewPDF uses the View Saved Report Viewer form for the PDF. This form uses the Adobe Reader COM object and requires Adobe Reader.
See Also
Environment Functions

---

## ViewWindowPDF - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ViewWindowPDFFunction.htm

ViewWindowPDF - MaxBasic Function
ViewWindowPDF(FileName: String): Object
ViewWindowPDF function opens the file specified in File Name in a floating Saved Report Window and returns the form Object.
ViewWindowsPDF function syntax has these named arguments:
Parameter
Description
File Name
Required. The name of the file to be viewed.
Note: ViewWindowPDF uses the View Saved Report Viewer form for the PDF. This form uses the Adobe Reader COM object and requires Adobe Reader.
See Also
Environment Functions

---

## WaitCursor - MaxBasic Function

Source: https://accredo.co.nz/webhelp/WaitCursorFunction.htm

WaitCursor - MaxBasic Function
WaitCursor(Boolean: Boolean)
Wait Cursor function sets the application cursor to an hour glass to provide UI feedback during a script.
WaitCursor function syntax has these named arguments:
Parameter
Description
Boolean
Required. If
True
, sets the application cursor to an hour glass. If
False
, sets application cursor to its default.
For example:
WaitCursor(True)
Try
Dim Delay as Number
Delay = 0
Do
Delay = Delay + 1
Loop Until Delay > 100000
Finally
WaitCursor(False)
End Try
See Also
Environment Functions

---

## WeekNo - MaxBasic Function

Source: https://accredo.co.nz/webhelp/WeekNoFunction.htm

WeekNo - MaxBasic Function
WeekNo(Date: Date, StartDate: Date): Number
WeekNo returns the week of the year the Date occurs in. 1st of January is considered to be Week 1.
WeekNo function syntax has these named arguments:
Parameter
Description
Date
Required. Date value to have the corresponding week of the year returned.
StartDate
Optional. If included, the WeekNo will be calculated starting from the StartDate. If not included, defaults to 1/1.
See Also
Date Functions

---

## WindowsUserName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/WindowsUserNameFunction.htm

WindowsUserName - MaxBasic Function
WindowsUserName: String
Windows User Name function returns the name of the current User as determined by Windows.
See Also
User Functions

---

## WordAmount - MaxBasic Function

Source: https://accredo.co.nz/webhelp/WordAmountFunction.htm

WordAmount - MaxBasic Function
WordAmount(Amount: Number): String
Returns a string containing Amount in words.
WordAmount function syntax has these named arguments:
Parameter
Description
Amount
Required. The number to be converted to a string.
Sample code:
WordAmount(927)
Returns:
NINE HUNDRED AND TWENTY SEVEN DOLLARS ONLY
See Also
String Functions

---

## WordLookup - MaxBasic Function

Source: https://accredo.co.nz/webhelp/WordLookupFunction.htm

WordLookup - MaxBasic Function
WordLookup(Masterfile: String, LookupWords: String, AnyWords: Boolean, PartialWords: Boolean[, Inactive: Boolean]): MemoryTable
Looks up the words in Lookup Words, in the Masterfile, and returns a Memory Table containing matching results. Lookup Words is a space delimited string containing the words to be looked up.
When Any Words is
True
, the results will be an "OR" search, and will contain records with at least one of the Lookup Words. When Any Words is
False
, the results will be an "AND" search, and will contain records with all the words specified in Lookup Words.
For example, if you have indexed the Name and Address fields for AR Customers or AP Creditors, and you enter 'Jones' and 'Auckland':
True
, returns 'Jones Furniture Ltd, Christchurch', 'Jones Furniture Ltd, Auckland' and 'Smith's Furniture, Auckland'.
False
, returns only 'Jones Furniture Ltd, Auckland'.
When Partial Words is
True,
the results will include all words starting with the Lookup Words. When Partial Words is
False
, the results will contain only exact word matches in Lookup Words.
For example, if Lookup Words contains the word 'and':
True
, Accredo will return 'Anderson and Co.' and 'J. Andrews Ltd', but not 'Peter Sands Ltd' or 'Harland Homes'.
False
, Accredo will return only 'and'.
The optional parameter Inactive determines whether to search inactive records.
WordLookup function syntax has these named arguments:
Parameter
Description
Masterfile
Required. The name of the masterfile to search.
Lookup Words
Required. A list of space delimited words to be looked up.
Any Words
Required. When
True
, looks for any words in the Lookup Words. When
False
, looks for all words in the Lookup Words.
Partial Words
Required. When
True
, looks for all words starting with the Lookup Words. When
False
, looks for exact word matches in Lookup Words.
Inactive
Optional. When
True
, searches inactive records. Defaults to
False
.
See Also
Script Functions

---

## Year - MaxBasic Function

Source: https://accredo.co.nz/webhelp/YearFunction.htm

Year - MaxBasic Function
Year(Date: Date): Number
Year returns the year value for the Date. If Date is Null then Null is returned.
Year function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the Year value for.
See Also
Date Functions

---

## YearBalance - MaxBasic Function

Source: https://accredo.co.nz/webhelp/YearBalanceFunction.htm

YearBalance - MaxBasic Function
YearBalance(PeriodId: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Year to date balance as at period specified. Optionally can be passed additional parameters to calculate summed year to date balance over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
YearBalance function syntax has these named arguments:
Parameter
Description
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## YearBudget - MaxBasic Function

Source: https://accredo.co.nz/webhelp/YearBudgetFunction.htm

YearBudget - MaxBasic Function
YearBudget([BudgetCode: String,] PeriodID: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Year to date budget as at period specified. If a budget code is not passed then the default budget is used. Optionally can be passed additional parameters to calculate summed year to date budget over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
YearBudget function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## YearName - MaxBasic Function

Source: https://accredo.co.nz/webhelp/YearNameFunction.htm

YearName - MaxBasic Function
YearName(PeriodID: Number): String
Returns the year name for the year which includes PeriodID.
YearName function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the year name for.
See Also
Period Functions

---

## YearProjected - MaxBasic Function

Source: https://accredo.co.nz/webhelp/YearProjectedFunction.htm

YearProjected - MaxBasic Function
YearProjected([BudgetCode: String,] PeriodID: Number[, BranchRange: String, DepartmentRange: String, Segment1Range: String, Segment2Range: String, Selection: String, ConsolidateBy: String] [, Level: Number, ExcludeNull: Boolean])
Year projected balance for actual figures as at the period specified and budgeted figures to the end of the year. If a budget code is not passed then the default budget is used. Optionally can be passed additional parameters to calculate projected summed year over a range of accounts. If additional parameters are not supplied, they will default from the iterator for the band.
Note:
Branch
and
Department
are only available in Accredo Saturn.
Note: If any of the BranchRange, DepartmentRange, Segment1Range, Segment2Range, Selection and ConsolidateBy parameters are passed in, all these parameters must be passed in.
YearProjected function syntax has these named arguments:
Parameter
Description
Budget Code
Optional. Budget code to use. If not specified, defaults to the
Default Budget Code
set in
GL Settings
.
Period ID
Required. The Period ID to use.
Branch Range
Optional. Range of branches to be included. If this is entered, the Department Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Department Range
Optional. Range of departments to be included. If this is entered, the Branch Range, Segment 1 Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 1 Range
Optional. Range of Segment 1 values to be included. If this is entered, the Branch Range, Department Range and Segment 2 Range must be entered. If this is not entered, defaults from the Iterator.
Segment 2 Range
Optional. Range of Segment 2 values to be included. If this is entered, the Branch Range, Department Range and Segment 1 Range must be entered. If this is not entered, defaults from the Iterator.
Selection
Optional. Selection to be included.
Consolidate By
Optional. String to consolidate by.
Level
Optional. The level to total to.
Exclude Null
Optional. When True, nulls will be excluded.
See Also
General Ledger Functions

---

## ZipFiles - MaxBasic Function

Source: https://accredo.co.nz/webhelp/ZipFilesFunction.htm

ZipFiles - MaxBasic Function
ZipFiles(FileName: String, FileList: String[, BasePath: String])
Creates or adds to the file specified in Filename, from a comma separated list of files specified in FileList.
Note: folders can be included as long as a filemask is also included, for example, "
c:\Exports\*.csv
". See the example below.
An optional Base Path for the files to zip can be specified. If this is included then all files in the file list must be in relative paths. Base path is inferred if only one file or filemask is passed in the file list.
ZipFiles function syntax has these named arguments:
Parameter
Description
File Name
Required. The zip or 7z file name to be created or added to.
If extension 7z is used file will be a 7 zip archive.
File List
Required. The files to be added to the zip or 7z file.
Base Path
Optional. The base path for the files in the list.
For example:
Zipfiles("c:\test.zip", "c:\File1.csv,c:\Exports*.csv")
will create test.zip file, and add all csv file from c:\Exports and also c:\file1.csv.
Zipfiles("c:\test.7z", "*.csv,*.txt","c:\Exports\")
will create test.7z file, and add all csv and txt files from c:\Exports.
See Also
Script Functions

---

