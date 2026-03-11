# SQL Reference

> SQL functions, operators, syntax, and query reference

**Sections:** 125

---

## Quick Reference

- [Abs - SQL Function](#abs---sql-function)
- [AddGST - SQL Function](#addgst---sql-function)
- [AddMonths - SQL Function](#addmonths---sql-function)
- [AddPeriod - SQL Function](#addperiod---sql-function)
- [AmountDecimals - SQL Function](#amountdecimals---sql-function)
- [ApplicationSettingBoolean - SQL Function](#applicationsettingboolean---sql-function)
- [ApplicationSettingDate - SQL Function](#applicationsettingdate---sql-function)
- [ApplicationSettingNumber - SQL Function](#applicationsettingnumber---sql-function)
- [ApplicationSettingString - SQL Function](#applicationsettingstring---sql-function)
- [AppName - SQL Function](#appname---sql-function)
- [AppVersion - SQL Function](#appversion---sql-function)
- [Asc - SQL Function](#asc---sql-function)
- [AVG - SQL Function](#avg---sql-function)
- [Case - SQL Function](#case---sql-function)
- [Case When - SQL Function](#case-when---sql-function)
- [CAST - SQL Function](#cast---sql-function)
- [Chr - SQL Function](#chr---sql-function)
- [Coalesce - SQL Function](#coalesce---sql-function)
- [ComputerName - SQL Function](#computername---sql-function)
- [ConvertBaseToFX - SQL Function](#convertbasetofx---sql-function)
- [ConvertFXToBase - SQL Function](#convertfxtobase---sql-function)
- [CostPriceDecimals - SQL Function](#costpricedecimals---sql-function)
- [COUNT - SQL Function](#count---sql-function)
- [CountryCode - SQL Function](#countrycode---sql-function)
- [Current_date - SQL Function](#currentdate---sql-function)
- [Current_time - SQL Function](#currenttime---sql-function)
- [CurrentPeriod - SQL Function](#currentperiod---sql-function)
- [DateValue - SQL Function](#datevalue---sql-function)
- [DateWithinPeriod - SQL Function](#datewithinperiod---sql-function)
- [Day - SQL Function](#day---sql-function)
- [DayOfWeek - SQL Function](#dayofweek---sql-function)
- [DefaultGSTCode - SQL Function](#defaultgstcode---sql-function)
- [Extract - SQL Function](#extract---sql-function)
- [FirstAvailablePeriod - SQL Function](#firstavailableperiod---sql-function)
- [FirstInYear - SQL Function](#firstinyear---sql-function)
- [FirstPeriod - SQL Function](#firstperiod---sql-function)
- [FirstUserPeriod - SQL Function](#firstuserperiod---sql-function)
- [Fix - SQL Function](#fix---sql-function)
- [Floor - SQL Function](#floor---sql-function)
- [FormatNumber - SQL Function](#formatnumber---sql-function)
- [GetBaseCurrency - SQL Function](#getbasecurrency---sql-function)
- [GetExchangeRate - SQL Function](#getexchangerate---sql-function)
- [GSTBasis - SQL Function](#gstbasis---sql-function)
- [GSTRate - SQL Function](#gstrate---sql-function)
- [GSTRegistered - SQL Function](#gstregistered---sql-function)
- [Instr - SQL Function](#instr---sql-function)
- [InstrRev - SQL Function](#instrrev---sql-function)
- [LastAvailablePeriod - SQL Function](#lastavailableperiod---sql-function)
- [LastInYear - SQL Function](#lastinyear---sql-function)
- [LastPeriod - SQL Function](#lastperiod---sql-function)
- [LastUserPeriod - SQL Function](#lastuserperiod---sql-function)
- [Left - SQL Function](#left---sql-function)
- [Length - SQL Function](#length---sql-function)
- [LoginUserName - SQL Function](#loginusername---sql-function)
- [Lower - SQL Function](#lower---sql-function)
- [LPad - SQL Function](#lpad---sql-function)
- [MakePeriodID - SQL Function](#makeperiodid---sql-function)
- [Margin - SQL Function](#margin---sql-function)
- [Markup - SQL Function](#markup---sql-function)
- [MAX - SQL Function](#max---sql-function)
- [MaxDate - SQL Function](#maxdate---sql-function)
- [MaxNumber - SQL Function](#maxnumber---sql-function)
- [Mid - SQL Function](#mid---sql-function)
- [MIN - SQL Function](#min---sql-function)
- [MinDate - SQL Function](#mindate---sql-function)
- [MinNumber - SQL Function](#minnumber---sql-function)
- [ModuleAvailable - SQL Function](#moduleavailable---sql-function)
- [Month - SQL Function](#month---sql-function)
- [NullIf - SQL Function](#nullif---sql-function)
- [Occurs - SQL Function](#occurs---sql-function)
- [PadAcctNo - SQL Function](#padacctno---sql-function)
- [Percent - SQL Function](#percent---sql-function)
- [PeriodEndDate - SQL Function](#periodenddate---sql-function)
- [PeriodForDate - SQL Function](#periodfordate---sql-function)
- [PeriodName - SQL Function](#periodname---sql-function)
- [PeriodPeriodNo - SQL Function](#periodperiodno---sql-function)
- [PeriodStartDate - SQL Function](#periodstartdate---sql-function)
- [PeriodYearNo - SQL Function](#periodyearno---sql-function)
- [Position - SQL Function](#position---sql-function)
- [PriceDecimals - SQL Function](#pricedecimals---sql-function)
- [Proper - SQL Function](#proper---sql-function)
- [QuantityDecimals - SQL Function](#quantitydecimals---sql-function)
- [Ratio - SQL Function](#ratio---sql-function)
- [Replace - SQL Function](#replace---sql-function)
- [Right - SQL Function](#right---sql-function)
- [Rnd - SQL Function](#rnd---sql-function)
- [Round - SQL Function](#round---sql-function)
- [RoundDown - SQL Function](#rounddown---sql-function)
- [RoundUp - SQL Function](#roundup---sql-function)
- [RPad - SQL Function](#rpad---sql-function)
- [SellPriceDecimals - SQL Function](#sellpricedecimals---sql-function)
- [SerialNo - SQL Function](#serialno---sql-function)
- [Sgn - SQL Function](#sgn---sql-function)
- [SQL Arithmetic Operators](#sql-arithmetic-operators)
- [SQL BETWEEN Extended Comparison Operator](#sql-between-extended-comparison-operator)
- [SQL Case Functions](#sql-case-functions)
- [SQL Comparison Operators](#sql-comparison-operators)
- [SQL GROUP BY Clause](#sql-group-by-clause)
- [SQL HAVING Clause](#sql-having-clause)
- [SQL IN Extended Comparison Operator](#sql-in-extended-comparison-operator)
- [SQL JOIN Clauses](#sql-join-clauses)
- [SQL LIKE Extended Comparison Operator](#sql-like-extended-comparison-operator)
- [SQL Logical Operators](#sql-logical-operators)
- [SQL ORDER BY Clause](#sql-order-by-clause)
- [SQL Overview](#sql-overview)
- [SQL SELECT Clause](#sql-select-clause)
- [SQL SELECT Clause Indexing](#sql-select-clause-indexing)
- [SQL SELECTIVITY Clause](#sql-selectivity-clause)
- [SQL String Operators](#sql-string-operators)
- [SQL WHERE Clause](#sql-where-clause)
- [StringToNumber - SQL Function](#stringtonumber---sql-function)
- [Substring - SQL Function](#substring---sql-function)
- [SubtractGST - SQL Function](#subtractgst---sql-function)
- [SUM - SQL Function](#sum---sql-function)
- [System_user - SQL Function](#systemuser---sql-function)
- [SystemDate - SQL Function](#systemdate---sql-function)
- [SystemPeriod - SQL Function](#systemperiod---sql-function)
- [TimeValue - SQL Function](#timevalue---sql-function)
- [Trim - SQL Function](#trim---sql-function)
- [Upper - SQL Function](#upper---sql-function)
- [UserPermission - SQL Function](#userpermission---sql-function)
- [WeekNo - SQL Function](#weekno---sql-function)
- [WordAmount - SQL Function](#wordamount---sql-function)
- [Year - SQL Function](#year---sql-function)
- [YearName - SQL Function](#yearname---sql-function)

---

## Abs - SQL Function

Source: https://accredo.co.nz/webhelp/AbsSQLFunction.htm

Abs - SQL Function
Abs(Number: Number): Number
Returns the absolute numeric value of a number.
Abs function syntax has these named arguments:
Parameter
Description
Number
Required. The number to be evaluated.
See Also
SQL Number Functions

---

## AddGST - SQL Function

Source: https://accredo.co.nz/webhelp/AddGSTSQLFunction.htm

AddGST - SQL Function
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
SQL GST Functions

---

## AddMonths - SQL Function

Source: https://accredo.co.nz/webhelp/AddMonthsSQLFunction.htm

AddMonths  - SQL Function
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
SQL Date Functions

---

## AddPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/AddPeriodSQLFunction.htm

AddPeriod - SQL Function
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
Note: To pass boolean parameters to the function use:
cast(1 as boolean) for
True.
cast(0 as boolean) for
False
.
See also the MaxBasic
AddPeriod
function, and the Web Services
AddPeriod
function.
See Also
SQL Period Functions

---

## AmountDecimals - SQL Function

Source: https://accredo.co.nz/webhelp/AmountDecimalsSQLFunction.htm

AmountDecimals - SQL Function
AmountDecimals: Number
Returns the number of decimal places used to display all financial values and totals in base currency.
See Also
SQL Number Functions

---

## ApplicationSettingBoolean - SQL Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingBooleanSQLFunction.htm

ApplicationSettingBoolean - SQL Function
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
SQL Application Functions

---

## ApplicationSettingDate - SQL Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingDateSQLFunction.htm

ApplicationSettingDate - SQL Function
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
SQL Application Functions

---

## ApplicationSettingNumber - SQL Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingNumberSQLFunction.htm

ApplicationSettingNumber - SQL Function
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
SQL Application Functions

---

## ApplicationSettingString - SQL Function

Source: https://accredo.co.nz/webhelp/ApplicationSettingStringSQLFunction.htm

ApplicationSettingString - SQL Function
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
SQL Application Functions

---

## AppName - SQL Function

Source: https://accredo.co.nz/webhelp/AppNameSQLFunction.htm

AppName - SQL Function
AppName: String
App Name function returns the string
Mercury
or
Saturn
depending on the application the script is executed from for both Accredo Mercury and Accredo Saturn scripts.
See also the MaxBasic
AppName
function and the Web Services
AppName
function.
See Also
SQL Application Functions

---

## AppVersion - SQL Function

Source: https://accredo.co.nz/webhelp/AppVersionSQLFunction.htm

AppVersion - SQL Function
AppVersion[(Parameter: Boolean)]: String
App Version function returns the application version number. This can be used to test that a script is being used on a suitable version. Takes one optional boolean parameter. If
True
, it returns the extended version information string including .exe date, time and build flags.
AppVersion function syntax has these named arguments:
Parameter
Description
Parameter
Optional. If set to
True
, AppVersion returns extended version information. Defaults to
False
.
See Also
SQL Application Functions

---

## Asc - SQL Function

Source: https://accredo.co.nz/webhelp/AscSQLFunction.htm

Asc - SQL Function
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
SQL String Functions

---

## AVG - SQL Function

Source: https://accredo.co.nz/webhelp/AVGFunction.htm

AVG - SQL Function
AVG {Expression}
AVG
returns the average of values in a specified field or expression.
Use
AVG
to calculate the average value for a numeric field. As an aggregate function,
AVG
performs its calculation aggregating values in the same field across all rows in a dataset. The dataset can be the entire table, a filtered dataset, or a logical group produced by a
GROUP BY
clause. Field values of zero are included in the averaging, so values of 1, 2, 3, 0, 0, 0 result in an average of 1. NULL field values are not counted in the calculation.
AVG function syntax has these named arguments:
Parameter
Description
Expression
Required. The field reference or expression to calculate the average of.
For example, to calculate the average gross amount for all Invoices:
SELECT AVG(GrossAmount) FROM INHEAD
When used with a
GROUP BY
clause,
AVG
calculates one value for each group. This value is the aggregation of the specified field for all rows in each group. The following example aggregates the average value for the GrossAmount field in the INHEAD table, producing a subtotal for each Customer in the ARCUST table:
SELECT C.CustomerCode , AVG(H.GrossAmount) as Average, MAX(H.GrossAmount) as Biggest, MIN(H.GrossAmount) as Smallest
FROM ARCUST C, INHEAD H
WHERE C.CustomerCode = H.CustomerCode
GROUP BY C.CustomerCode
ORDER BY C.CustomerCode
See Also
SQL Aggregate Functions

---

## Case - SQL Function

Source: https://accredo.co.nz/webhelp/CaseFunction.htm

Case - SQL Function
Case {Expression} When {ComparisonExpression} Then {ReturnExpression} Else {ElseExpression} End
Case
expressions let you use
If...Then...Else
logic in SQL Statements.
The database searches for the first instance of {Expression} that is equal to {ComparisonExpression}, and returns the {ReturnExpression}. If no instances of {Expression} matching {ComparisonExpression} are found, the {ElseExpression} is returned.
Case
function syntax has these named arguments:
Parameter
Description
Expression
Required. The expression to be searched.
ComparisonExpression
Required. Expression to be searched for in Expression.
ReturnExpression
Required. The expression to be returned if ComparisonExpression is found in Expression.
ElseExpression
Required. Required. The expression to be returned if ComparisonExpression is not found in Expression.
For example:
SELECT  CustomerCode,
Case Category1
When 'GOLD' Then 'High'
When 'SILVER' Then 'Medium'
Else 'Low'
End
FROM    ARCUST
See Also
SQL Case Functions

---

## Case When - SQL Function

Source: https://accredo.co.nz/webhelp/CaseWhenFunction.htm

Case When - SQL Function
Case When {Condition} Then {ReturnExpression} Else {ElseExpression} End
Case When
expressions let you use
If...Then...Else
logic in SQL Statements.
The database searches for an occurrence of {Condition} that is
True
, and returns the {ReturnExpression}. If no {Condition} is
True
, the {ElseExpression} is returned.
Case When
function syntax has these named arguments:
Parameter
Description
Condition
Required. The condition to be evaluated.
ReturnExpression
Required. The expression to be returned if Condition is
True
.
ElseExpression
Required. The expression to be returned if Condition is not
True
.
For example:
SELECT  CustomerCode,
Case When CreditLimit > 5000
Then 'High'
Else 'Low'
End
FROM    ARCUST
See Also
SQL Case Functions

---

## CAST - SQL Function

Source: https://accredo.co.nz/webhelp/CASTFunction.htm

CAST - SQL Function
The
CAST
function converts a specified value to the specified data type. This function is particularly useful when you need to explicitly define data types in your queries.
Usage
The
CAST
function can be utilized in:
The fields list of a
SELECT
statement.
The predicate of a
WHERE
clause.
Syntax
CAST({Field: Variant AS DataType: String})
Parameters
Parameter
Description
Field
(
Required)
The field or value to be converted.
DataType
(Required)
The target data type to which the field should be converted.
Supported Data Types
AMOUNT
BOOLEAN
BYTE
CHAR(X)
: A character string of length X.
CHARACTER(X)
: Synonym for CHAR(X).
DATE
DATETIME
DECIMAL
DISCOUNT
FLOAT
INT
INTEGER
LARGEINT
MONEY
NCHAR(X)
: A Unicode character string of length X.
NUMERIC
SMALLINT
TIME
TIMESTAMP
VARCHAR(X)
: A variable-length character string of length X.
WORD
Note: Replace X with the desired length for character-based data types. The maximum length for X is 8192 characters.
Examples:
Example 1: Casting to a DATE
SELECT CAST(DocumentDate as DATE)
FROM INHEAD
This example converts the DocumentDate field to the DATE data type.
Example 2: Casting to a Variable-length String
SELECT CAST(INHEAD.DocumentID as VARCHAR(20))
FROM INHEAD
This example converts the DocumentID field to a variable-length string of up to 20 characters.
Example 3: Casting to a Unicode-Supported String
SELECT CAST('' as NCHAR(200)) AS EmptyUnicodeString
FROM INHEAD
This example creates an empty Unicode supported string with a length of 200 characters.
Additional Notes
Use CAST to ensure compatibility and correctness in data type transformations.
When casting to character types, be mindful of the specified length (X) to avoid truncation or errors.
Use NCHAR for wide character strings that require Unicode support.
By leveraging the CAST function effectively, you can manage and manipulate data types in SQL queries with precision.
See Also
SQL Cast Function

---

## Chr - SQL Function

Source: https://accredo.co.nz/webhelp/ChrSQLFunction.htm

Chr - SQL Function
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
SQL String Functions

---

## Coalesce - SQL Function

Source: https://accredo.co.nz/webhelp/CoalesceFunction.htm

Coalesce - SQL Function
Coalesce(Expr1: Variant[, Expr2: Variant[, ... ExprN: Variant]]): Variant
Coalesce
Returns the first non-NULL value from a list of expressions. If all values in the list are NULL, returns NULL.
All expressions must have the same data type. You can use the
CAST
function to ensure all expressions have the same data type.
Coalesce
function syntax has these named arguments:
Parameter
Description
Expr1
Required. The first expression to be evaluated as non-NULL.
Expr2...ExprN
Optional. A list of expressions to be evaluated as non-NULL.
In the following example, if the BankReference field contains a NULL value, then the field value returned will be the BankParticulars field. If the BankParticulars field also contains a NULL, then the literal string 'No Bank' will be returned:
SELECT CustomerCode,
Coalesce(BankReference,BankParticulars,'No Bank') AS Bank
FROM ARCUST
See Also
SQL Case Functions

---

## ComputerName - SQL Function

Source: https://accredo.co.nz/webhelp/ComputerNameSQLFunction.htm

ComputerName - SQL Function
ComputerName: String
Computer Name function returns the name of the running computer as configured in Windows.
See Also
SQL Environment Functions

---

## ConvertBaseToFX - SQL Function

Source: https://accredo.co.nz/webhelp/ConvertBaseToFXSQLFunction.htm

ConvertBaseToFX - SQL Function
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
SQL Foreign Exchange Functions

---

## ConvertFXToBase - SQL Function

Source: https://accredo.co.nz/webhelp/ConvertFXToBaseSQLFunction.htm

ConvertFXToBase - SQL Function
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
SQL Foreign Exchange Functions

---

## CostPriceDecimals - SQL Function

Source: https://accredo.co.nz/webhelp/CostPriceDecimalsSQLFunction.htm

CostPriceDecimals - SQL Function
CostPriceDecimals:[(CurrencyCode: String)]: Number
Returns number of decimal places used to display cost prices. If CurrencyCode is empty, the decimal places for base currency is returned.
CostPriceDecimals function syntax has these named arguments:
Parameter
Description
CurrencyCode
Optional. The Currency Code to return the cost price decimals for.
See also the MaxBasic
CostPriceDecimals
function.
See Also
SQL Number Functions

---

## COUNT - SQL Function

Source: https://accredo.co.nz/webhelp/COUNTFunction.htm

COUNT - SQL Function
COUNT {Expression}
The
COUNT
function returns the number of rows that satisfy a query’s search condition.
Count function syntax has these named arguments:
Parameter
Description
Expression
Required. The field reference or expression to count, or
*
to count all records.
For example:
SELECT COUNT(*) FROM INHEAD WHERE (INHEAD.GrossAmount > 10000)
See Also
SQL Aggregate Functions

---

## CountryCode - SQL Function

Source: https://accredo.co.nz/webhelp/CountryCodeSQLFunction.htm

CountryCode - SQL Function
CountryCode: String
CountryCode
returns the system country code.
See Also
SQL Environment Functions

---

## Current_date - SQL Function

Source: https://accredo.co.nz/webhelp/Current_dateFunction.htm

Current_date - SQL Function
Current_date: Date
Current_date
returns the current machine date.
See Also
SQL Date Functions

---

## Current_time - SQL Function

Source: https://accredo.co.nz/webhelp/Current_timeFunction.htm

Current_time - SQL Function
Current_time: Time
Current_time returns the current machine time.
See Also
SQL Date Functions

---

## CurrentPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/CurrentPeriodSQLFunction.htm

CurrentPeriod - SQL Function
CurrentPeriod(Module: String): Number
Returns the Current Period for Module Code specified in Module,
CurrentPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to return the current period for.
See also the MaxBasic
CurrentPeriod
function and the Web Services
CurrentPeriod
function.
See Also
SQL Period Functions

---

## DateValue - SQL Function

Source: https://accredo.co.nz/webhelp/DateValueSQLFunction.htm

DateValue - SQL Function
DateValue(DateParameter: String/Date/Time/DateTime [,String: String]): Date
DateValue returns a date value for DateParameter, optionally using the String parameter to specify the format of DateParameter (either Day Month Year or Month Day Year). If String is omitted, assumes the format of DateParameter matches the default date / time format.
DateValue function syntax has these named arguments:
Parameter
Description
DateParameter
Required. Parameter to be formatted as a date. This can be a String, Date, Time or DateTime value, including ISO 8601 Date Time strings.
String
Optional. Date format for the DateParameter. If not entered, uses the default date / time format. Select from:
Day Month Year
Month Day Year
See Also
SQL Date Functions

---

## DateWithinPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/DateWithinPeriodSQLFunction.htm

DateWithinPeriod - SQL Function
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
SQL Period Functions

---

## Day - SQL Function

Source: https://accredo.co.nz/webhelp/DaySQLFunction.htm

Day  - SQL Function
Day(Date: Date): Number
Day returns the day value for the Date. If Date is null then null is returned.
Day function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the day value for.
See Also
SQL Date Functions

---

## DayOfWeek - SQL Function

Source: https://accredo.co.nz/webhelp/DayOfWeekSQLFunction.htm

DayOfWeek - SQL Function
DayOfWeek(Date: Date): Number
DayOfWeek returns day of week for a Date, as a number from 1 to 7 numbering from Sunday as 1.
DayOfWeek function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the day of week value for.
See Also
SQL Date Functions

---

## DefaultGSTCode - SQL Function

Source: https://accredo.co.nz/webhelp/DefaultGSTCodeSQLFunction.htm

DefaultGSTCode - SQL Function
DefaultGSTCode: String
Default GST Code Function returns the Default GST Code.
See Also
SQL GST Functions

---

## Extract - SQL Function

Source: https://accredo.co.nz/webhelp/ExtractFunction.htm

Extract - SQL Function
Extract(DateTime: String From Expr1: String): String
Extract
returns the value of a specified DateTime field from Expr1. This can be useful for manipulating date and time fields in large tables.
Extract
function syntax has these named arguments:
Parameter
Description
DateTime
Required. The date or time field to be returned. Select from:
Year
Month
Day
Hour
Minute
Second
Expr1
Required. The date, time or timestamp field.
For example:
Select Extract(Year from DateOfLastSale) From ARCUST
See Also
SQL Date Functions

---

## FirstAvailablePeriod - SQL Function

Source: https://accredo.co.nz/webhelp/FirstAvailablePeriodSQLFunction.htm

FirstAvailablePeriod - SQL Function
FirstAvailablePeriod(Module: String): Number
Returns the first available period for the Module Code specified in Module (not limited by User).
FirstAvailablePeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the first available period for.
See Also
SQL Period Functions

---

## FirstInYear - SQL Function

Source: https://accredo.co.nz/webhelp/FirstInYearSQLFunction.htm

FirstInYear - SQL Function
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
SQL Period Functions

---

## FirstPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/FirstPeriodSQLFunction.htm

FirstPeriod - SQL Function
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
Note: To pass boolean parameters to the function use:
cast(1 as boolean) for
True.
cast(0 as boolean) for
False
.
See Also
SQL Period Functions

---

## FirstUserPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/FirstUserPeriodSQLFunction.htm

FirstUserPeriod - SQL Function
FirstUserPeriod(Module: String[, User: String]): Number
Returns the first period which the User may post transactions into for the specified module. If the User parameter is not specified, the User is the logged in User.
FirstUserPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the first user period for.
User
Optional. User to find the first period for. Defaults to the User currently logged in.
See also the MaxBasic
FirstUserPeriod
function and the Web Services
FirstUserPeriod
function.
See Also
SQL Period Functions

---

## Fix - SQL Function

Source: https://accredo.co.nz/webhelp/FixSQLFunction.htm

Fix - SQL Function
Fix(Number: Number): Number
Returns the Integer portion of Number, rounded toward zero. Negative numbers round up.
Fix function syntax has these named arguments:
Parameter
Description
Number
Required. The number to be evaluated.
See Also
SQL Number Functions

---

## Floor - SQL Function

Source: https://accredo.co.nz/webhelp/FloorSQLFunction.htm

Floor - SQL Function
Floor(Number: Number): Number
Returns the Integer portion of Number, rounded away from zero.
Floor function syntax has these named arguments:
Parameter
Description
Number
Required. The number to be evaluated.
See Also
SQL Number Functions

---

## FormatNumber - SQL Function

Source: https://accredo.co.nz/webhelp/FormatNumberSQLFunction.htm

FormatNumber - SQL Function
FormatNumber(Number: Number[, String: String]): String
Formats Number as a string. If Number is
Null
, returns
Null
, or returns number formatted in accordance with String. If String is omitted, the default Windows number format will be used. String can either be a domain name or a valid formatting string. See
Formatting
for acceptable values of String.
FormatNumber function syntax has these named arguments:
Parameter
Description
Number
Required. Number to be formatted.
String
Optional. Formatting string for the number. See
Formatting
for acceptable values of String.
See Also
SQL Number Functions

---

## GetBaseCurrency - SQL Function

Source: https://accredo.co.nz/webhelp/GetBaseCurrencySQLFunction.htm

GetBaseCurrency - SQL Function
GetBaseCurrency: String
Return the currency code for the base currency.
See Also
SQL Foreign Exchange Functions

---

## GetExchangeRate - SQL Function

Source: https://accredo.co.nz/webhelp/GetExchangeRateSQLFunction.htm

GetExchangeRate - SQL Function
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
See also the MaxBasic
GetExchangeRate
function and the Web Services
GetExchangeRate
function.
See Also
SQL Foreign Exchange Functions

---

## GSTBasis - SQL Function

Source: https://accredo.co.nz/webhelp/GSTBasisSQLFunction.htm

GSTBasis - SQL Function
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
SQL GST Functions

---

## GSTRate - SQL Function

Source: https://accredo.co.nz/webhelp/GSTRateSQLFunction.htm

GSTRate - SQL Function
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
See also the MaxBasic
GSTRate
function and the Web Services
GSTRate
function.
See Also
SQL GST Functions

---

## GSTRegistered - SQL Function

Source: https://accredo.co.nz/webhelp/GSTRegisteredSQLFunction.htm

GSTRegistered - SQL Function
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
SQL GST Functions

---

## Instr - SQL Function

Source: https://accredo.co.nz/webhelp/InstrSQLFunction.htm

Instr - SQL Function
Instr(String1: String, String2: String): Number
String position from start. Returns the position of the start of the first instance of String2 contained within String1. If String2 is not found in String1 or String1 is zero length, 0 is returned. If either argument is null, null is returned.
InstrRev function syntax has these named arguments:
Parameter
Description
String 1
Required. String to be searched for String 2.
String 2
Required. String to search for in String 1.
For example:
Instr("moonbeam", "beam")
Returns:
5
See Also
SQL String Functions

---

## InstrRev - SQL Function

Source: https://accredo.co.nz/webhelp/InstrRevSQLFunction.htm

InstrRev - SQL Function
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
SQL String Functions

---

## LastAvailablePeriod - SQL Function

Source: https://accredo.co.nz/webhelp/LastAvailablePeriodSQLFunction.htm

LastAvailablePeriod - SQL Function
LastAvailablePeriod(Module: String): Number
Returns the last available period for the Module Code specified in Module (not limited by User).
LastAvailablePeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the last available period for.
See Also
SQL Period Functions

---

## LastInYear - SQL Function

Source: https://accredo.co.nz/webhelp/LastInYearSQLFunction.htm

LastInYear  - SQL Function
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
Note: To pass boolean parameters to the function use:
cast(1 as boolean) for
True.
cast(0 as boolean) for
False
.
See Also
SQL Period Functions

---

## LastPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/LastPeriodSQLFunction.htm

LastPeriod - SQL Function
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
Note: To pass boolean parameters to the function use:
cast(1 as boolean) for
True.
cast(0 as boolean) for
False
.
See Also
SQL Period Functions

---

## LastUserPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/LastUserPeriodSQLFunction.htm

LastUserPeriod - SQL Function
LastUserPeriod(Module: String [,User: String]): Number
Returns the last period which the User may post transactions into for the specified module. If the User parameter is not specified, the User is the logged in User.
LastUserPeriod function syntax has these named arguments:
Parameter
Description
Module
Required. Module to find the last user period for.
User
Optional. User to find the last period for. Defaults to the User currently logged in.
See also the MaxBasic
LastUserPeriod
function and the Web Services
LastUserPeriod
function.
See Also
SQL Period Functions

---

## Left - SQL Function

Source: https://accredo.co.nz/webhelp/LeftSQLFunction.htm

Left - SQL Function
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
SQL String Functions

---

## Length - SQL Function

Source: https://accredo.co.nz/webhelp/LengthSQLFunction.htm

Length - SQL Function
Length(String: String): Number
String length. Returns a number containing the length of String.
Length function syntax has these named arguments:
Parameter
Description
String
Required. Field reference or string to return the length of.
See Also
SQL String Functions

---

## LoginUserName - SQL Function

Source: https://accredo.co.nz/webhelp/LoginUserNameSQLFunction.htm

LoginUserName - SQL Function
LoginUserName: String
Login User Name function returns the logged in User Name.
See Also
SQL User Functions

---

## Lower - SQL Function

Source: https://accredo.co.nz/webhelp/LowerSQLFunction.htm

Lower - SQL Function
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
SQL String Functions

---

## LPad - SQL Function

Source: https://accredo.co.nz/webhelp/LPadSQLFunction.htm

LPad - SQL Function
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
SQL String Functions

---

## MakePeriodID - SQL Function

Source: https://accredo.co.nz/webhelp/MakePeriodIDSQLFunction.htm

MakePeriodID - SQL Function
MakePeriodID(Year: Number, Period: Number): Number
Create a period ID from the given Year and Period numbers. Returns zero if YearNo or PeriodNo are outside valid range.
MakePeriodID function syntax has these named arguments:
Parameter
Description
YearNo
Required. YearNo to use to create the Period ID. Valid range integers 1-99.
Period
Required. PeriodNo to use to create the Period ID. Valid range integers 1-99.
For example:
MakePeriodID(2,1)
Returns: 201.
See Also
SQL Period Functions

---

## Margin - SQL Function

Source: https://accredo.co.nz/webhelp/MarginSQLFunction.htm

Margin - SQL Function
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
SQL Number Functions

---

## Markup - SQL Function

Source: https://accredo.co.nz/webhelp/MarkupSQLFunction.htm

Markup - SQL Function
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
SQL Number Functions

---

## MAX - SQL Function

Source: https://accredo.co.nz/webhelp/SQLMAXFunction.htm

MAX - SQL Function
MAX {Expression}
The
MAX
function returns the largest value in the specified field.
Use
MAX
to calculate the largest value for a numeric, date, time, or timestamp field. As an aggregate function,
MAX
performs its calculation aggregating values in the same field across all rows in a dataset. The dataset can be the entire table, a filtered dataset, or a logical group produced by a
GROUP BY
clause. Field values of zero are included in the aggregation. NULL field values are not counted in the calculation. If the number of qualifying rows is zero,
MAX
returns a NULL value.
MAX
function syntax has these named arguments:
Parameter
Description
Expression
Required. The field reference or expression to return the maximum of.
For example:
SELECT MAX(GrossAmount) FROM INHEAD
When used with a
GROUP BY
clause,
MAX
returns one calculation value for each group. This value is the aggregation of the specified field for all rows in each group. The following example aggregates the largest value for the GrossAmount field in the INHEAD table, producing a subtotal for each Customer in the ARCUST table:
SELECT C.CustomerCode , AVG(H.GrossAmount) as Average, MAX(H.GrossAmount) as Biggest, MIN(H.GrossAmount) as Smallest
FROM ARCUST C, INHEAD H
WHERE C.CustomerCode = H.CustomerCode
GROUP BY C.CustomerCode
ORDER BY C.CustomerCode
See Also
SQL Aggregate Functions

---

## MaxDate - SQL Function

Source: https://accredo.co.nz/webhelp/MaxDateSQLFunction.htm

MaxDate - SQL Function
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
SQL Date Functions

---

## MaxNumber - SQL Function

Source: https://accredo.co.nz/webhelp/MaxNumberSQLFunction.htm

MaxNumber - SQL Function
MaxNumber(Num1: Number, Num2: Number[, Num3: Number[,...NumN: Number]]): Number
Returns the maximum number from a list of parameters.
MaxNumber function syntax has these named arguments:
Parameter
Description
Num1
Required. The first number to be compared.
Num2
Required. The second number to be compared.
Num3...NumN
Optional. Additional numbers to be compared.
See Also
SQL Number Functions

---

## Mid - SQL Function

Source: https://accredo.co.nz/webhelp/MidSQLFunction.htm

Mid - SQL Function
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
SQL String Functions

---

## MIN - SQL Function

Source: https://accredo.co.nz/webhelp/SQLMINFunction.htm

MIN - SQL Function
MIN {Expression}
The
MIN
function returns the smallest value in the specified field.
Use
MIN
to calculate the smallest value for a numeric, date, time, or timestamp field. As an aggregate function,
MIN
performs its calculation aggregating values in the same field across all rows in a dataset. The dataset can be the entire table, a filtered dataset, or a logical group produced by a
GROUP BY
clause. Field values of zero are included in the aggregation. NULL field values are not counted in the calculation. If the number of qualifying rows is zero,
MIN
returns a NULL value.
MIN
function syntax has these named arguments:
Parameter
Description
Expression
Required. The field reference or expression to return the minimum of.
For example:
SELECT MIN(GrossAmount) FROM INHEAD
When used with a
GROUP BY
clause,
MIN
returns one calculation value for each group. This value is the aggregation of the specified field for all rows in each group. The following example aggregates the smallest value for the GrossAmount field in the INHEAD table, producing a subtotal for each Customer in the ARCUST table:
SELECT C.CustomerCode , AVG(H.GrossAmount) as Average, MAX(H.GrossAmount) as Biggest, MIN(H.GrossAmount) as Smallest
FROM ARCUST C, INHEAD H
WHERE C.CustomerCode = H.CustomerCode
GROUP BY C.CustomerCode
ORDER BY C.CustomerCode
See Also
SQL Aggregate Functions

---

## MinDate - SQL Function

Source: https://accredo.co.nz/webhelp/MinDateSQLFunction.htm

MinDate - SQL Function
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
SQL Date Functions

---

## MinNumber - SQL Function

Source: https://accredo.co.nz/webhelp/MinNumberSQLFunction.htm

MinNumber - SQL Function
MinNumber(Num1: Number, Num2: Number[, Num3: Number[,...NumN: Number]]): Number
Returns the minimum number from a list of parameters.
MinNumber function syntax has these named arguments:
Parameter
Description
Num1
Required. The first number to be compared.
Num2
Required. The second number to be compared.
Num3...NumN
Optional. Additional numbers to be compared.
See Also
SQL Number Functions

---

## ModuleAvailable - SQL Function

Source: https://accredo.co.nz/webhelp/ModuleAvailableSQLFunction.htm

ModuleAvailable - SQL Function
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
SQL Environment Functions

---

## Month - SQL Function

Source: https://accredo.co.nz/webhelp/MonthSQLFunction.htm

Month - SQL Function
Month(Date: Date): Number
Month returns the month value for the Date. If Date is Null then Null is returned.
Month function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the Month value for.
See Also
SQL Date Functions

---

## NullIf - SQL Function

Source: https://accredo.co.nz/webhelp/NullIfFunction.htm

NullIf - SQL Function
NULLIF(Expr1: Variant, Expr2: Variant:): Variant
NullIf
is a conditional function. If Expr1 is equal to Expr2, NULL is returned, else Expr1 is returned.
NullIf
function syntax has these named arguments:
Parameter
Description
Expr 1
Required. Expression to be compared to Expr2.
Expr 2
Required. Expression to be compared to Expr1.
The following example returns the ExchangeRate for Invoices, if the ExchangeRate is not equal to
1
:
SELECT DocumentID, NullIf(ExchangeRate, 1) FROM INHEAD
See Also
SQL Case Functions

---

## Occurs - SQL Function

Source: https://accredo.co.nz/webhelp/OccursSQLFunction.htm

Occurs - SQL Function
Occurs(String1: String In String2: String): Number
Returns the number of occurrences of String1 in String 2. If there are no occurrences, 0 will be returned.
Occurs can only be used with string or memo fields or constants.
Occurs function syntax has these named arguments:
Parameter
Description
String1
Required. String to search String2 for.
String2
Required. The field reference or string to be searched for occurrences of String1.
For example:
SELECT * FROM Country WHERE OCCURS('NEW' IN Name) > 0
See Also
SQL String Functions

---

## PadAcctNo - SQL Function

Source: https://accredo.co.nz/webhelp/PadAcctNoSQLFunction.htm

PadAcctNo - SQL Function
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
SQL String Functions

---

## Percent - SQL Function

Source: https://accredo.co.nz/webhelp/PercentSQLFunction.htm

Percent - SQL Function
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
SQL Number Functions

---

## PeriodEndDate - SQL Function

Source: https://accredo.co.nz/webhelp/PeriodEndDateSQLFunction.htm

PeriodEndDate - SQL Function
PeriodEndDate(PeriodID: Number): Date
Returns the end date for period with ID PeriodID
.
PeriodEndDate function syntax has these named arguments:
Parameter
Description
Period ID
Required. The Period ID to return the end date for.
See Also
SQL Period Functions

---

## PeriodForDate - SQL Function

Source: https://accredo.co.nz/webhelp/PeriodForDateSQLFunction.htm

PeriodForDate - SQL Function
PeriodForDate(Date: Date): Number
Returns the Period ID of the period containing Date. If no period contains Date then 0 is returned.
PeriodForDate function syntax has these named arguments:
Parameter
Description
Date
Required. The Date to find the Period ID for.
See also the MaxBasic
PeriodForDate
function and the Web Services
PeriodForDate
function.
See Also
SQL Period Functions

---

## PeriodName - SQL Function

Source: https://accredo.co.nz/webhelp/PeriodNameSQLFunction.htm

PeriodName - SQL Function
PeriodName(PeriodID: Number): String
Returns name for the for the period with ID PeriodID.
PeriodName function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the name for.
See Also
SQL Period Functions

---

## PeriodPeriodNo - SQL Function

Source: https://accredo.co.nz/webhelp/PeriodPeriodNoSQLFunction.htm

PeriodPeriodNo - SQL Function
PeriodPeriodNo(PeriodID: Number): Number
Returns the Period Number of the Period with ID PeriodID.
PeriodPeriodNo function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to find the Period number for.
See Also
SQL Period Functions

---

## PeriodStartDate - SQL Function

Source: https://accredo.co.nz/webhelp/PeriodStartDateSQLFunction.htm

PeriodStartDate - SQL Function
PeriodStartDate(PeriodID: Number): Date
Returns the start date for period with ID PeriodID
.
PeriodStartDate function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the start date for.
See Also
SQL Period Functions

---

## PeriodYearNo - SQL Function

Source: https://accredo.co.nz/webhelp/PeriodYearNoSQLFunction.htm

PeriodYearNo - SQL Function
PeriodYearNo(PeriodID: Number): Number
Returns the year number of the Period with ID PeriodID.
PeriodYearNo function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the year number for.
See Also
SQL Period Functions

---

## Position - SQL Function

Source: https://accredo.co.nz/webhelp/PositionSQLFunction.htm

Position - SQL Function
Position(String1: String In String2: String): Number
Returns the position of the start of the first instance of String2 contained within String1. If String2 is not found in String1 or String1 is zero length, 0 is returned. If either argument is null, null is returned.
Position function syntax has these named arguments:
Parameter
Description
String 1
Required. String to be searched for String 2.
String 2
Required. Field reference or String to search for in String 1.
For example:
SELECT * FROM Country WHERE POSITION('NEW' IN Name) > 0
See Also
SQL String Functions

---

## PriceDecimals - SQL Function

Source: https://accredo.co.nz/webhelp/PriceDecimalsSQLFunction.htm

PriceDecimals - SQL Function
PriceDecimals: Number
Returns the maximum of
CostPriceDecimals
and
SellPriceDecimals
for the base currency.
See Also
SQL Number Functions

---

## Proper - SQL Function

Source: https://accredo.co.nz/webhelp/ProperSQLFunction.htm

Proper - SQL Function
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
SQL String Functions

---

## QuantityDecimals - SQL Function

Source: https://accredo.co.nz/webhelp/QuantityDecimalsSQLFunction.htm

QuantityDecimals - SQL Function
QuantityDecimals: Number
Returns number of decimals places used to display all item quantities.
See Also
SQL Number Functions

---

## Ratio - SQL Function

Source: https://accredo.co.nz/webhelp/RatioSQLFunction.htm

Ratio - SQL Function
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
SQL Number Functions

---

## Replace - SQL Function

Source: https://accredo.co.nz/webhelp/ReplaceSQLFunction.htm

Replace - SQL Function
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
SQL String Functions

---

## Right - SQL Function

Source: https://accredo.co.nz/webhelp/RightSQLFunction.htm

Right - SQL Function
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
SQL String Functions

---

## Rnd - SQL Function

Source: https://accredo.co.nz/webhelp/RndSQLFunction.htm

Rnd - SQL Function
Rnd: Number
Returns a random number between 0 and 1.
See Also
SQL Number Functions

---

## Round - SQL Function

Source: https://accredo.co.nz/webhelp/RoundSQLFunction.htm

Round - SQL Function
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
SQL Number Functions

---

## RoundDown - SQL Function

Source: https://accredo.co.nz/webhelp/RoundDownSQLFunction.htm

RoundDown - SQL Function
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
SQL Number Functions

---

## RoundUp - SQL Function

Source: https://accredo.co.nz/webhelp/RoundUpSQLFunction.htm

RoundUp - SQL Function
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
SQL Number Functions

---

## RPad - SQL Function

Source: https://accredo.co.nz/webhelp/RPadSQLFunction.htm

RPad - SQL Function
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
SQL String Functions

---

## SellPriceDecimals - SQL Function

Source: https://accredo.co.nz/webhelp/SellPriceDecimalsSQLFunction.htm

SellPriceDecimals - SQL Function
SellPriceDecimals:[(CurrencyCode: String)]: Number
Returns number of decimal places used to display sell prices. If CurrencyCode is empty, the decimal places for base currency is returned.
SellPriceDecimals function syntax has these named arguments:
Parameter
Description
CurrencyCode
Optional. The Currency Code to return the sell price decimals for.
See also the MaxBasic
SellPriceDecimals
function.
See Also
SQL Number Functions

---

## SerialNo - SQL Function

Source: https://accredo.co.nz/webhelp/SerialNoSQLFunction.htm

SerialNo - SQL Function
SerialNo: String
Serial No function returns the application serial number.
See Also
SQL Application Functions

---

## Sgn - SQL Function

Source: https://accredo.co.nz/webhelp/SgnSQLFunction.htm

Sgn - SQL Function
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
SQL Number Functions

---

## SQL Arithmetic Operators

Source: https://accredo.co.nz/webhelp/SQLArithmeticOperators.htm

SQL Arithmetic Operators
Use arithmetic operators to perform arithmetic calculations on data in
SELECT
queries. The following outlines the arithmetic operators supported by the SQL engine.
Operator
Description
+
Addition
-
Subtraction
*
Multiplication
/
Division
Calculations can be performed wherever non-aggregated data values are allowed, such as in a
SELECT
or
WHERE
clause. In following example, a field value is multiplied by a numeric literal:
SELECT (GrossAmount * 0.0825) AS Tax FROM INHEAD
Arithmetic calculations are performed in the normal order of precedence: multiplication, division, addition, and then subtraction. To cause a calculation to be performed out of the normal order of precedence, use parentheses around the operation to be performed first. Here the addition is performed before the multiplication:
SELECT (UOMSellingPrice * (UOMQuantitySupplied + 1)) As Result FROM INLINE
Arithmetic operators operate only on numeric and date/time values. The following example shows how you would add 30 days to a date to get an Invoice due date for an Invoice in a SELECT SQL statement:
SELECT DocumentDate, (DocumentDate + 30) AS DueDate, GrossAmount FROM INHEAD WHERE DocumentDate BETWEEN '2014-1-01' AND '2015-01-31'
See Also
SQL Operators

---

## SQL BETWEEN Extended Comparison Operator

Source: https://accredo.co.nz/webhelp/SQLBETWEENExtendedComparisonOperator.htm

SQL BETWEEN Extended Comparison Operator
Determines if a value falls inside a range. The syntax is as follows:
Value1 [NOT] BETWEEN Value2 AND Value3
Use the
BETWEEN
extended comparison operator to compare a value to a value range. If the value is greater than or equal to the low end of the range and less than or equal to the high end of the range,
BETWEEN
returns a TRUE value. If the value is less than the low end value or greater than the high end value,
BETWEEN
returns a FALSE value. For example, the expression below returns a FALSE value because 10 is not between 1 and 5:
10 BETWEEN 1 AND 5
Use
NOT
to return the converse of a
BETWEEN
comparison. For example, the expression below returns a TRUE value:
10 NOT BETWEEN 1 AND 5
BETWEEN
can be used with all non-BLOB data types, but all values compared must be of the same or a compatible data type. The left-side and right-side values used in a
BETWEEN
comparison can be fields, literals, or calculated values. The following example returns all of the orders that where the DocumentDate field is between January 1 2014 and January 1 2015:
SELECT DocumentDate FROM INHEAD WHERE (DocumentDate BETWEEN '2014-01-01' and '2015-01-01')
BETWEEN
is useful when filtering to retrieve rows with contiguous values within the specified range. For filtering to retrieve rows with non-contiguous values, use the
IN
extended comparison operator.
See Also
SQL Extended Comparison Operators

---

## SQL Case Functions

Source: https://accredo.co.nz/webhelp/SQLCaseFunctions.htm

SQL Case Functions
Function
Description
Case
Returns an expression based on a comparison.
Case When
Returns an expression based on a condition being met.
Coalesce
Returns the first non-NULL value from a list of expressions.
NullIf
If values are equal then returns Null.
In This Section
Case - SQL Function
Case When - SQL Function
Coalesce - SQL Function
NullIf - SQL Function

---

## SQL Comparison Operators

Source: https://accredo.co.nz/webhelp/SQLComparisonOperators.htm

SQL Comparison Operators
Use comparison operators to perform comparisons on data in
SELECT
queries. The following outlines the comparison operators supported by the SQL engine.
Operator
Description
<
Less than
>
Greater than
=
Equal to
<>
Not equal to
>=
Greater than or equal to
<=
Less than or equal to
Use comparison operators to compare two like values. Values compared can be field values, literals, or calculations. The result of the comparison is a boolean value that is used in contexts such as
WHERE
clauses to determine on a line-by-line basis if a line meets the filtering criteria. The following example uses the >= comparison operator to show only the Invoices where the GrossAmount field is greater than or equal to
10000
:
SELECT * FROM INHEAD WHERE GrossAmount >= 10000
Comparisons must be between two values of the same or a compatible data type. The result of a comparison operation can be modified by a logical operator, such as
NOT
. The following example uses the >= comparison operator and the logical
NOT
operator to show only Invoices where the GrossAmount field is not greater than or equal to
10000
:
SELECT * FROM INHEAD WHERE NOT (GrossAmount >= 10000)
NULL
values can only be compared for equality or non-equality and any other comparison will evaluate to a Boolean False value.
Comparison operators can only be used in a
WHERE
or
HAVING
clause, or in the
ON
clause of a join. They cannot be used in the
SELECT
clause.  The only exception to this would be within the first argument to the
IF()
function, that allows comparison expressions for performing
IF...ELSE
boolean logic.
See Also
SQL Operators

---

## SQL GROUP BY Clause

Source: https://accredo.co.nz/webhelp/SQLGROUPBYClause.htm

SQL GROUP BY Clause
The
GROUP BY
clause combines rows that have field values in common into single rows for the
SELECT
statement. The syntax is as follows:
GROUP BY field_reference [, field reference...]
You can use a
GROUP BY
clause to cause an aggregation process to be repeated once for each group of similar rows. Similarity between rows is determined by the distinct values (or combination of values) in the fields specified in the
GROUP BY
. For instance, a query with a
SUM
function produces a result set with a single line with the total of all the values for the field used in the
SUM
function. But when a
GROUP BY
clause is added, the
SUM
function performs its summing action once for each group of rows. In statements that support a
GROUP BY
clause, the use of a
GROUP BY
clause is optional. A
GROUP BY
clause becomes necessary when both aggregated and non-aggregated fields are included in the same
SELECT
statement.
In the statement below, the
SUM
function produces one subtotal of the GrossAmount field for each distinct value in the CustomerCode field, that is, one subtotal for each Customer:
SELECT CustomerCode, SUM(GrossAmount) FROM INHEAD GROUP BY CustomerCode
The value for the
GROUP BY
clause is a comma-separated list of fields. Each field in this list must meet the following criteria:
Be in one of the tables specified in the
FROM
clause of the query.
Also be in the
SELECT
clause of the query.
Cannot have an aggregate function applied to it (in the
SELECT
clause).
When a
GROUP BY
clause is used, all table fields in the
SELECT
and
ORDER BY
clauses of the query must meet at least one of the following criteria, or it cannot be included in the
SELECT
or
ORDER BY
clause:
Be in the
GROUP BY
clause of the query.
Be the subject of an aggregate function.
Literal values in the SELECT clause are not subject to the preceding criteria and are not required to be in the GROUP BY clause in addition to the SELECT clause.
The distinctness of rows is based on the fields in the field list specified. All rows with the same values in these fields are combined into a single line (or logical group). Fields that are the subject of an aggregate function have their values across all rows in the group combined. All fields not the subject of an aggregate function retain their value and serve to distinctly identify the group. For example, in the
SELECT
statement below, the values in the GrossAmount field are aggregated (totalled) into groups based on distinct values in the CustomerCode field. This produces total gross amount for each Customer:
SELECT C.CustomerCode, SUM(H.GrossAmount)
FROM ARCUST C, INHEAD H
WHERE C.CustomerCode = H.CustomerCode
GROUP BY C.CustomerCode
ORDER BY C.CustomerCode
A field can be referenced in a
GROUP BY
clause by a field correlation name, instead of actual field names. The statement below forms groups using the first field, CustomerCode, represented by the field correlation name CC:
SELECT C.CustomerCode CC, SUM(H.GrossAmount) AS TotalGross
FROM ARCUST C, INHEAD H
WHERE C.CustomerCode = H.CustomerCode
GROUP BY CC
ORDER BY 1
See Also
SQL Clauses

---

## SQL HAVING Clause

Source: https://accredo.co.nz/webhelp/SQLHAVINGClause.htm

SQL HAVING Clause
The
HAVING
clause specifies filtering conditions for a
SELECT
statement. The syntax is as follows:
HAVING predicates
Use a
HAVING
clause to limit the rows retrieved by a
SELECT
statement to a subset of rows where aggregated field values meet the specified criteria. A
HAVING
clause can only be used in a
SELECT
statement when:
The statement also has a
GROUP BY
clause.
One or more fields are the subjects of aggregate functions.
The value for a
HAVING
clause is one or more logical expressions or predicates that evaluate to true or false for each aggregate line retrieved from the table. Only those rows where the predicates evaluate to true are retrieved by a
SELECT
statement. For example, the
SELECT
statement below retrieves all rows where the total Gross Amount for a Customer exceeds $100,000:
SELECT CustomerCode, SUM(GrossAmount) as TotalGross
FROM INHEAD
GROUP BY CustomerCode
HAVING Sum(GrossAmount) > 100000
ORDER BY CustomerCode
Multiple predicates must be separated by one of the logical operators
OR
or
AND
. Each predicate can be negated with the
NOT
operator. Parentheses can be used to isolate logical comparisons and groups of comparisons to produce different line evaluation criteria.
A
SELECT
statement can include both a
WHERE
clause and a
HAVING
clause. The
WHERE
clause filters the data to be aggregated, using fields not the subject of aggregate functions. The
HAVING
clause then further filters the data after the aggregation, using fields that are the subject of aggregate functions. The
SELECT
query below performs the same operation as that above, but data limited to those rows where the Price Code field is
NZTRADE
:
SELECT CustomerCode, SUM(GrossAmount) as TotalGross
FROM INHEAD
WHERE PriceCode = 'NZTRADE'
GROUP BY CustomerCode
HAVING Sum(GrossAmount) > 100000
ORDER BY CustomerCode
A
HAVING
clause filters data after the aggregation of a
GROUP BY
clause. For filtering based on line values prior to aggregation, use a
WHERE
clause.

---

## SQL IN Extended Comparison Operator

Source: https://accredo.co.nz/webhelp/SQLINExtendedComparisonOperator.htm

SQL IN Extended Comparison Operator
The IN extended comparison operator indicates if a value exists in a set of values. The syntax is:
value [NOT] IN (value_set)
Use the
IN
extended comparison operator to filter a table based on the existence of a field value in a specified set of comparison values. The set of comparison values can be a comma-separated list of field names, literals, or calculated values. The following example returns all Customers where the Country field is either 'NZ' or 'AU':
SELECT A.CustomerCode, A.CountryCode FROM ARCUST A WHERE (A.CountryCode IN ('NZ', 'AU'))
The value to compare with the values set can be any or a combination of: a field value, a literal value, or a calculated value.
Use
NOT
to return the converse of an IN comparison.
IN
can be used with all non-BLOB data types, but all values compared must be of the same or a compatible data type.
IN is useful when filtering to retrieve rows with non-contiguous values. For filtering to retrieve rows with contiguous values that fall within a specified range, use the
BETWEEN
extended comparison operator.
See Also
SQL Extended Comparison Operators

---

## SQL JOIN Clauses

Source: https://accredo.co.nz/webhelp/SQLJOINClauses.htm

SQL JOIN Clauses
There are three types of
JOIN
clauses that can be used in the
FROM
clause to perform relational joins between source tables. The implicit join condition is always Cartesian for source tables without an explicit JOIN clause. The following table outlines the three types of
JOIN
clauses that can be used in the
FROM
clause. See below for more detailed information about each type of join.
Type
Description
Cartesian
Joins two tables, matching each line of one table with each line from the other.
INNER
Joins two tables, filtering out non-matching rows.
OUTER
Joins two tables, retaining non-matching rows.
Cartesian Join
A Cartesian join connects two tables in a non-relational manner. The syntax is as follows:
FROM table_reference, table_reference [,table_reference...]
Use a Cartesian join to connect the field of two tables into one result set, but without correlation between the rows from the tables. Cartesian joins match each line of the source table with each line of the joining table. No field comparisons are used, just simple association. If the source table has 10 rows and the joining table has 10, the result set will contain 100 rows as each line from the source table is joined with each line from the joined table.
INNER JOIN Clause
An
INNER JOIN
connects two tables based on field values common between the two, excluding non-matches. The syntax is as follows:
FROM table_reference [INNER] JOIN table_reference ON predicate [[INNER] JOIN table_reference ON predicate...]
Use an
INNER JOIN
to connect two tables, a source and joining table, that have values from one or more fields in common. One or more fields from each are compared in the
ON
clause for equal values. For rows in the source table that have a match in the joining table, the data for the source table rows and matching joining table rows are included in the result set. Rows in the source table without matches in the joining table are excluded from the joined result set. In the following example the AR Customer ARCUST and IN Invoice Header INHEAD tables are joined based on values in the CustomerCode field:
SELECT * FROM ARCUST INNER JOIN INHEAD ON ARCUST.CustomerCode = INHEAD.CustomerCode
More than one table can be joined with an
INNER JOIN
. The
INNER JOIN
operator and corresponding
ON
clause can be repeated for each set of two tables joined. One fields comparison predicate in an ON clause is required for each field compared to join each two tables. The following example joins the ARCUST table to INHEAD, and then INHEAD to INLINE (IN Invoice Lines). In this case, the joining table INHEAD acts as a source table for the joining table Items. Note that the statement appears without the optional
INNER
keyword.
SELECT * FROM ARCUST JOIN INHEAD ON (ARCUST.CustomerCode = INHEAD.CustomerCode) JOIN INLINE ON (INHEAD.DocumentID = INLINE.DocumentID)
Tables can also be joined using a concatenation of multiple field values to produce a single value for the join comparison predicate. In the following example the Category1 and Category2 fields in INHEAD are concatenated and compared with the single Comment field in ARCUST:
SELECT * FROM ARCUST INNER JOIN INHEAD ON (ARCUST.Comment = INHEAD.CATEGORY1 || INHEAD.CATEGORY2)
OUTER JOIN Clause
The
OUTER JOIN
clause connects two tables based on field values common between the two, including non- matches. The syntax is as follows:
FROM table_reference LEFT | RIGHT | FULL [OUTER] JOIN table_reference ON predicate [LEFT | RIGHT [OUTER] JOIN table_reference ON predicate...]
Use an
OUTER JOIN
to connect two tables, a source and joining table, that have one or more fields in common. One or more fields from each are compared in the
ON
clause for equal values. The primary difference between inner and outer joins is that in
OUTER
joins rows from the source table that do not have a match in the joining table are not excluded from the result set. Fields from the joining table for rows in the source table without matches have NULL values.
In the following example the ARCUST and INHEAD tables are joined based on values in the CustomerCode field. For rows from ARCUST that do not have a matching value between ARCUST.CustomerCode and INHEAD.CustomerCode, the fields from INHEAD contain NULL values:
SELECT * FROM ARCUST LEFT OUTER JOIN INHEAD ON (ARCUST.CustomerCode = INHEAD.CustomerCode)
The
LEFT
modifier causes all rows from the table on the left of the
OUTER JOIN
operator to be included in the result set, with or without matches in the table to the right. If there is no matching line from the table on the right, its fields contain NULL values. The
RIGHT
modifier causes all rows from the table on the right of the
OUTER JOIN
operator to be included in the result set, with or without matches. If there is no matching line from the table on the left, its fields contain NULL values. The
FULL
modifier returns non-matching rows from both left and right, that is, a combination of both
LEFT
and
RIGHT
.
More than one table can be joined with an
OUTER JOIN
. The
OUTER JOIN
operator and corresponding
ON
clause can be repeated for each set of two tables joined. One field comparison predicate in an
ON
clause is required for each field compared to join each two tables. The following example joins the ARCUST table to the INHEAD table, and then INHEAD to INLINE. In this case, the joining table INHEAD acts as a source table for the joining table Items:
SELECT * FROM ARCUST LEFT OUTER JOIN INHEAD ON (ARCUST.CustomerCode = INHEAD.CustomerCode) LEFT OUTER JOIN INLINE ON (INHEAD.DocumentID = INLINE.DocumentID)
Tables can also be joined using expressions to produce a single value for the join comparison predicate. In the following example the Category1 and Category2 fields in INHEAD are separately compared with two values produced by the SUBSTRING function using the single Comment field in ARCUST:
SELECT * FROM ARCUST RIGHT OUTER JOIN INHEAD ON (SUBSTRING(ARCUST.Comment FROM 1 FOR 2) = INHEAD.CATEGORY1 AND SUBSTRING(ARCUST.COMMENT FROM 3 FOR 1) = INHEAD.CATEGORY2)

---

## SQL LIKE Extended Comparison Operator

Source: https://accredo.co.nz/webhelp/SQLLIKEExtendedComparisonOperator.htm

SQL LIKE Extended Comparison Operator
The
LIKE
extended comparison operator indicates the similarity of one value as compared to another. The syntax is:
Value [NOT] LIKE [Substitution_char] Comparison_value [Substitution_char]
Use the
LIKE
extended comparison operator to filter a table based on the similarity of a field value to a comparison value. Use of substitution characters allows the comparison to be based on the whole field value or just a portion. The following example returns all Customers where the CustomerName field is equal to
Asheng Engineering Ltd
:
SELECT * FROM ARCUST WHERE CustomerName LIKE 'Asheng Engineering Ltd'
The wildcard substitution character
%
can be used in the comparison to represent an unknown number of characters.
LIKE
returns a TRUE when the portion of the field value matches that portion of the comparison value not corresponding to the position of the wildcard character. The wildcard character can appear at the beginning, middle, or end of the comparison value (or multiple combinations of these positions). The following example retrieves rows where the field value begins with 'A' and is followed by any number of any characters:
SELECT * FROM ARCUST WHERE (CustomerName LIKE 'A%')
The wildcard substitution character
_
(underscore) can be used to represent one unknown character. This can be used to return fields with an exact length. The following example retrieves rows where the field value begins with 'A' and is followed by three characters, represented by three underscore characters:
SELECT * FROM ARCUST WHERE (CustomerName LIKE 'A___')
Use
NOT
to return the converse of a
LIKE
comparison.
LIKE
can be used only with string or compatible data types such as memo fields. The comparison performed by the
LIKE
extended comparison operator is case-sensitive.
See Also
SQL Extended Comparison Operators

---

## SQL Logical Operators

Source: https://accredo.co.nz/webhelp/SQLLogicalOperators.htm

SQL Logical Operators
Use logical operators to perform Boolean logic between different predicates (conditions) in an SQL
WHERE
clause. The following outlines the logical operators supported by the SQL engine.
Operator
Description
OR
Boolean OR operation
AND
Boolean AND operation
NOT
Boolean NOT operation
This allows the source table to be filtered based on multiple conditions. Logical operators compare the boolean result of two predicate comparisons, each producing a boolean result. If OR is used, either of the two predicate comparisons can result on a TRUE value for the whole expression to evaluate to TRUE. If
AND
is used, both predicate comparisons must evaluate to TRUE for the whole expression to be TRUE; if either is FALSE, the whole is FALSE. In the following example, if only one of the two predicate comparisons is TRUE, the line will be included in the query result set:
SELECT * FROM INHEAD WHERE ((DocumentDate > '2015-01-01') OR (PrintStatus = 'Unprinted'))
Logical operator comparisons are performed in the order of precedence: OR and then AND. To perform a comparison out of the normal order of precedence, use parentheses around the comparison to be performed first. The
SELECT
statement below retrieves all rows where the CountryCode field is
NZ
and the PriceCode is
NZWSALE
. It also returns those rows where the CountryCode field is
AU
, regardless of the value in the PriceCode field:
SELECT * FROM ARCUST WHERE ((CountryCode = 'NZ') AND (PriceCode = 'NZTRADE')) OR (CountryCode = 'AU')
Use the
NOT
operator to negate the boolean result of a comparison. In the following example, only those rows where the Paid field contains a FALSE value are retrieved:
SELECT * FROM INHEAD WHERE NOT (PrintStatus = 'Unprinted')
See Also
SQL Operators

---

## SQL ORDER BY Clause

Source: https://accredo.co.nz/webhelp/SQLORDERBYClause.htm

SQL ORDER BY Clause
The
ORDER BY
clause sorts the rows retrieved by a
SELECT
statement. The syntax is as follows:
ORDER BY field_reference [ASC|DESC] [, field_reference... [ASC|DESC]] [NOCASE]
Use an
ORDER BY
clause to sort the rows retrieved by a
SELECT
statement based on the values from one or more fields. In
SELECT
statements, use of the clause is optional.
The value for the
ORDER BY
clause is a comma-separated list of field names. The fields in this list must also be in the
SELECT
clause of the query statement. Fields in the
ORDER BY
list can be from one or multiple tables. If the fields used for an
ORDER BY
clause come from multiple tables, the tables must all be those that are part of a join, as they cannot be a table included in the statement only through a
SELECT
subquery.
A field can be specified in an
ORDER BY
clause using a number representing the relative position of the field in the
SELECT
of the statement. Field correlation names can also be used in an
ORDER BY
clause fields list. Calculations can be used directly in an
ORDER BY
clause.
Use
ASC
to force the sort to be in ascending order (smallest to largest), or
DESC
for a descending sort order (largest to smallest). When not specified,
ASC
is the implied default.
Use
NOCASE
to force the sort to be case-insensitive. This is also useful for allowing a live result set when an index is available that matches the
ORDER BY
clause but is marked as case-insensitive. When not specified, case-sensitive is the implied default.
The statement below sorts the result set ascending by the year extracted from the DocumentDate field, then descending by the SalesPersonCode field, and then ascending by the CustomerCode field:
SELECT EXTRACT(YEAR FROM DocumentDate) AS YY, SalesPersonCode, CustomerCode
FROM INHEAD
ORDER BY YY DESC, SalesPersonCode ASC, 3

---

## SQL Overview

Source: https://accredo.co.nz/webhelp/SQL_Overview.htm

SQL Overview
Select information from anywhere in Accredo using SQL Queries.
SQL Queries underlie the Masterfile and Document lists, many of the build in report layouts, and the Analysis Report designers.
Accredo
Custom Reports
are based on a pre-defined SQL Query.
The
SQL Query Builder
can be used to create and execute Queries.
Queries may be executed in MaxBasic using the
ExecuteSQL
function.
Note: Permission for executing SQL queries is set per module under Reports > Queries. SQL queries also respect user field level permissions, e.g. for access to IC cost prices, AR Customer account balances. Note that this does not apply to OLEDB/ODBC.
In This Section
SQL Clauses
SQL Functions
SQL Operators
SQL Reserved Words

---

## SQL SELECT Clause

Source: https://accredo.co.nz/webhelp/SQLSelectClause.htm

SQL SELECT Clause
The
SELECT
clause is used to retrieve data from tables. You can use the
SELECT
clause to retrieve,
a single line, or part of a line, from a table, referred to as a singleton select
multiple rows, or parts of rows, from a table
related rows, or parts of rows, from a join of two or more tables
The syntax is as follows:
SELECT [FIRST number_of_rows] [DISTINCT | ALL] * | field | parameter [AS correlation_name | correlation_name], [field | parameter ...]
FROM table_reference [AS correlation_name | correlation_name]
[[[[INNER | [LEFT | RIGHT | FULL] OUTER JOIN] table_reference [AS correlation_name | correlation_name] ON join_condition]
[WHERE predicates]
[GROUP BY group_list]
[HAVING predicates]
[ORDER BY order_list]
[UNION [ALL] [SELECT...]]
The
SELECT
clause defines the list of items returned by the
SELECT
statement. The
SELECT
clause uses a comma-separated list composed of table fields, literal values, and field or literal values modified by functions. You cannot use parameters in this list of items. Use an asterisk to retrieve values from all fields. Fields in the field list for the
SELECT
clause can come from more than one table, but can only come from those tables listed in the
FROM
clause.
The
FROM
clause identifies the table from which data is retrieved.
The following example retrieves data for two fields in all rows of a table:
SELECT CustomerCode, CustomerName from ARCUST
You can use the
AS
keyword to specify a field correlation name, or alternately you can simply just specify the field correlation name after the selected field. The following example uses both methods to give each selected field a more descriptive name in the query result set:
SELECT ARCUST.CustomerCode AS "Customer Code",
ARCUST.CustomerName AS "Customer Name",
INHEAD.DocumentNo AS "Invoice Number",
SUM(INLINE.QuantitySupplied) "Total Qty"
FROM ARCUST LEFT OUTER JOIN INHEAD ON ARCUST.CUSTOMERCODE = INHEAD.CUSTOMERCODE
LEFT OUTER JOIN INLINE ON INHEAD.DOCUMENTID = INLINE.DOCUMENTID
WHERE ARCUST.CustomerName like '%Furn%'
GROUP BY ARCUST.CustomerCode, ARCUST.CustomerName, INHEAD.DocumentNo
ORDER BY ARCUST.CustomerCode
Use
DISTINCT
to limit the retrieved data to only distinct rows. The distinctness of rows is based on the combination of all of the fields in the SELECT clause fields list.
Sub query for select fields
Sub-queries are often referred to as sub-selects, as they allow a
SELECT
statement to be executed arbitrarily within the body of another SQL statement. A sub-query is executed by enclosing it in a set of parentheses.
Select
FieldA,
FieldB,
FieldC,
(Select ......From .... Where ...),
From
TableA
For example:
Select ARCUST.CustomerCode,
(Select Sum(TransactionAmount) from ARTRAN Where ARTRAN.CustomerCode = ARCUST.CustomerCode)
From ARCUST
Note: You can manipulate SQL Query performance using indices. See
SQL Select Clause Indexing
.
In This Section
SQL SELECT Clause Indexing

---

## SQL SELECT Clause Indexing

Source: https://accredo.co.nz/webhelp/SQLSelectClauseIndexing.htm

SQL SELECT Clause Indexing
You can manipulate the performance of SQL
SELECT
statements by controlling which table indices are used or excluded.
Exclude Indexes in Select Queries
You can select to exclude particular indexes or all indexes from a table in a
SELECT
statement, using a query hint. This can be useful when an index slows down query performance.
The syntax is as follows:
SELECT [//&HINT EXCLUDEINDEX tablename.indexname, tablename.*] *
FROM ....
For example:
SELECT //&HINT EXCLUDEINDEX INHEAD.Document
INLINE.*
FROM INHEAD LEFT OUTER JOIN INLINE ON INHEAD.DocumentID = INLINE.DocumentId
The above example will stop the document index on INHEAD from being used, and will stop all indexes on INLINE from being used.
Force Indexes in Select Queries
You can select to use a specific index from a table in a
SELECT
statement, using a query hint. This can be useful for controlling query performance.
The syntax is as follows:
SELECT [//&HINT FORCEINDEX tablename1.indexname1, tablename2.indexname2] *
FROM ....
If multiple indexes are referenced for a table, only the last one will be used.
For example:
SELECT //&HINT FORCEINDEX INHEAD.Document
INLINE.Document
FROM INHEAD LEFT OUTER JOIN INLINE ON INHEAD.DocumentID = INLINE.DocumentId
The above example will stop the document index on INHEAD from being used, and will stop all indexes on INLINE from being used.
See Also
SQL SELECT Clause

---

## SQL SELECTIVITY Clause

Source: https://accredo.co.nz/webhelp/SQLSELECTIVITYClause.htm

SQL SELECTIVITY Clause
If a query runs slower than expected, it is possible that the actual selectivity for one or more of the expressions in the query differs from the default selectivity that the Accredo SQL Engine uses. The selectivity of an expression is the proportion of rows that is expected to be returned out of all possible rows.
For example, take the following query:
SELECT * FROM ARTRAN
WHERE CustomerCode = 'ASHENG'
If table ARTRAN has 600 rows, this is it’s cardinality, meaning the number of different elements.
If there are 60 rows with CustomerCode = 'ASHENG', the actual selectivity of CustomerCode = 'ASHENG' is 60/600 = 0.1
This actual selectivity is very close to the defaults used by the Accredo SQL engine (see below) but in some cases due to differing data distribution the actual selectivity may be very different which may cause the SQL engine to execute the query in a way that is not optimum.
For example:
SELECT * FROM ICWORD
WHERE Word = 'bedroom'
If ICWORD has 140 rows and there is 1 row (card) with word = 'bedroom'.
Accredo’s estimate will be a selectivity of 0.1 which would give a cardinality of 14 which we know is incorrect. To force a selectivity, a selectivity clause is added:
SELECT * FROM ICWORD
WHERE Word = 'bedroom' SELECTIVITY 0.01
A selectivity clause can only be added to any single expression, it cannot be added to compound expressions. The following is not valid:
SELECT * FROM ICWORD
WHERE (Word = 'bedroom' or Word = 'pine') SELECTIVITY 0.01
That the above examples were single table selects; selectivity defaults and overrides will have the most effect when joins are involved. For example:
SELECT * FROM ICWORD
INNER JOIN ICPROD
ON  ICPROD.ProductCode = ICWORD.ProductCode
WHERE ICWORD.Word LIKE '%bed%' SELECTIVITY 0.001
Accredo Default Selectivities
Accredo uses the following Selectivities by default, if a Selectivity is not specified:
table.field = value
= 1 / CARD(table) if there is a unique index on Table
= 0.10 otherwise
table1.field1 = table2.field2
= 1 / CARD(table2) if there is a unique index on field2 and the join is Table1 JOIN Table2
= ( CARD(table2) / CARD(table1) ) / CARD(table2) if there is a non-unique index on field2 and the join is Table1 JOIN Table2
= 1 / CARD(table1) if there is a unique index on field1 and the join is Table2 JOIN Table1
= ( CARD(table1) / CARD(table2) ) / CARD(table1) if there is a non-unique index on field1and the join is Table2 JOIN Table1
= 0.1 otherwise
field >, <, >=, <= value
= 0.333
field BETWEEN value1 AND value2
= 0.25
field IN (list of values)
= Min(0.5, InValueCount*0.1)
field <> field or value
= 0.9
NOT (expression)
= 1 – Selectivity of expression
field IS NULL
= 0.1
expr1 AND expr2
= Selectivity of expr1 * Selectivity of exp2
expr1 OR expr2
= Selectivity of expr1 + Selectivity of expr2 - (Selectivity of expr1 * Selectivity of expr2)
field LIKE expression
= Selectivity of equals if expression is a constant, that is, field LIKE ‘product’
= Selectivity of BETWEEN if expression starts with a constant, that is, field LIKE ‘prod%’
= 0.5 otherwise
See Also
SQL Clauses

---

## SQL String Operators

Source: https://accredo.co.nz/webhelp/SQLStringOperators.htm

SQL String Operators
Use string operators to perform string concatenation on character data in
SELECT
queries. The following outlines the string operator supported by the SQL engine.
Operator
Description
||
Concatenation
String operations can be performed wherever non-aggregated data values are allowed, such as in a
SELECT
or
WHERE
clause. In following example, a field value concatenated with a second field value to provide a new calculated field in the query result set:
SELECT (LastName || ', ' || FirstName) As FullName from APCONTCT
String operators operate only on string values or memo fields.
Note: Concatenating with a null string will return null. To treat null strings as empty coalesce with an empty string.
e.g.
Select CustomerCode
,Cast(Coalesce(Address1, '') || ' ' || Coalesce(Address2, '') || ' ' || Coalesce(Address3, '') || ' ' || Coalesce(Address4, '') as VarChar(120)) as Address
From ARCUST
Where CustomerCode = 'ASHENG'
See Also
SQL Operators

---

## SQL WHERE Clause

Source: https://accredo.co.nz/webhelp/SQLWHEREClause.htm

SQL WHERE Clause
The
WHERE
clause specifies filtering conditions for the
SELECT
statement. The syntax is as follows:
WHERE predicates
Use a
WHERE
clause to limit the effect of a
SELECT
statement to a subset of rows in the table. The value for a
WHERE
clause is one or more logical expressions, or predicates, that evaluate to true or false for each line in the table. Only those rows where the predicates evaluate to TRUE are retrieved by the
SELECT
statement. For example, the
SELECT
statement below retrieves all rows where the CountryCode field contains a value of
NZ
:
SELECT CustomerCode, CountryCode FROM ARCUST WHERE CountryCode = 'NZ'
A field used in the
WHERE
clause of a statement is not required to also appear in the
SELECT
clause of that statement. In the preceding statement, the CountryCode field could be used in the
WHERE
clause even if it was not also in the
SELECT
clause.
You can use multiple predicates, separated by one of the logical operators
OR
or
AND
. Each predicate can be negated with the
NOT
operator. Parentheses can be used to isolate logical comparisons and groups of comparisons to produce different line evaluation criteria. For example, the
SELECT
statement below retrieves all rows where the CountryCode field contains a value of
NZ
and those with a value of
AU
:
SELECT CustomerCode, CountryCode FROM ARCUST WHERE (CountryCode = 'NZ') OR (CountryCode = 'AU')
The
SELECT
statement below retrieves all rows from ICPROD (IC Product) where the Style (Category1) field is
RUSTIC
or
SHAKER
, but only if the Range (Category2) field is
BED
.
SELECT ProductCode, Category1, Category2 FROM ICPROD WHERE ((Category1 = 'RUSTIC') OR (Category1 = 'SHAKER')) AND (Category2 = 'BED')
Parentheses affect the order or precedence of the logical operators. Without parentheses the above statement would return different results. The following statement retrieves rows where the Style is RUSTIC, regardless of the value of the Range field. It also retrieves rows where the Style is SHAKER but only when the range is BED.
SELECT ProductCode, Category1, Category2 FROM ICPROD WHERE Category1 = 'RUSTIC' OR Category1 = 'SHAKER' AND Category2 = 'BED'
Field correlation names cannot be used in filter comparisons in the
WHERE
clause. Use the field name.
A
WHERE
clause filters data prior to the aggregation of a
GROUP BY
clause. For filtering based on aggregated values, use a
HAVING
clause
.
Fields devoid of data contain NULL values. To filter using such field values, use the
IS NULL
predicate.
You can search for reserved characters using the
ESCAPE
keyword with
LIKE
. For example, to search for a customer with a
%
character in the customer code:
SELECT ARCUST.CustomerCode, ARCUST.CustomerName FROM ARCUST WHERE ARCUST.CustomerCode LIKE '%!%%' ESCAPE '!'
This will return all customers with a
%
in the customer code.
See Also
SQL Clauses

---

## StringToNumber - SQL Function

Source: https://accredo.co.nz/webhelp/StringToNumberSQLFunction.htm

StringToNumber - SQL Function
StringToNumber(String: String): Number
Returns a number representing the value of String. If String is empty, a value of 0 is returned.
StringToNumber function syntax has these named arguments:
Parameter
Description
String
Required. String expression to be evaluated.
See Also
SQL Number Functions

---

## Substring - SQL Function

Source: https://accredo.co.nz/webhelp/SubstringSQLFunction.htm

Substring - SQL Function
Substring(String: String From StartPosition: Number [For Length: Number]DH494)
Returns a substring of String, starting from StartPosition, with Length number of characters. If For Length is omitted, the substring goes from the StartPosition to the end of the String.
When applied to retrieved data of a SELECT statement, the effect is transient and does not affect stored data. When applied to the update atoms of an UPDATE statement, the effect is persistent and permanently converts the stored values.
Substring function syntax has these named arguments:
Parameter
Description
String
Required. String to extract the substring from.
StartPosition
Required. The character to start the substring from.
Length
Optional. The number of characters for extract.
For example:
Select Substring(CustomerName From 1 to 3)
From ARCUST
See Also
SQL String Functions

---

## SubtractGST - SQL Function

Source: https://accredo.co.nz/webhelp/SubtractGSTSQLFunction.htm

SubtractGST - SQL Function
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
SQL GST Functions

---

## SUM - SQL Function

Source: https://accredo.co.nz/webhelp/SQLSUMFunction.htm

SUM - SQL Function
SUM {Expression}
The
SUM
function calculates the sum of values for a field.
Use
SUM
to sum all the values in the specified field. As an aggregate function, SUM performs its calculation aggregating values in the same field across all rows in a dataset. The dataset can be the entire table, a filtered dataset, or a logical group produced by a GROUP BY clause. Field values of zero are included in the aggregation. NULL field values are not counted in the calculation. If the number of qualifying rows is zero,
SUM
returns a NULL value.
SUM
function syntax has these named arguments:
Parameter
Description
Expression
Required. The field reference or expression to calculate the sum total.
For example:
SELECT SUM(GrossAmount) from INHEAD
When used with a
GROUP BY
clause,
SUM
returns one calculation value for each group. This value is the aggregation of the specified field for all rows in each group. The following example aggregates the total value for the GrossAmount field in the INHEAD table, producing a subtotal for each Customer in the ARCUST table:
SELECT C.CustomerCode , SUM(H.GrossAmount) as Total
FROM ARCUST C, INHEAD H
WHERE C.CustomerCode = H.CustomerCode
GROUP BY C.CustomerCode
ORDER BY C.CustomerCode
See Also
SQL Aggregate Functions

---

## System_user - SQL Function

Source: https://accredo.co.nz/webhelp/System_userSQLFunction.htm

System_user - SQL Function
System_user: String
System_User
returns the Windows user name.
See Also
SQL Environment Functions

---

## SystemDate - SQL Function

Source: https://accredo.co.nz/webhelp/SystemDateSQLFunction.htm

SystemDate - SQL Function
SystemDate: Date
System date returns the current System Date, see
System Date & System Period
.
See also the MaxBasic
SystemDate
function and the Web Services
SystemDate
function.
See Also
SQL Date Functions

---

## SystemPeriod - SQL Function

Source: https://accredo.co.nz/webhelp/SystemPeriodSQLFunction.htm

SystemPeriod - SQL Function
SystemPeriod: Number
Returns the current System Period ID, see
System Date & System Period
.
See also the MaxBasic
SystemPeriod
function and the Web Services
SystemPeriod
function.
See Also
SQL Period Functions

---

## TimeValue - SQL Function

Source: https://accredo.co.nz/webhelp/TimeValueSQLFunction.htm

TimeValue - SQL Function
TimeValue(TimeParameter: String/Date/Time/DateTime): Time
TimeValue returns a time value for TimeParameter
.
The format matches the default date / time format.
TimeValue function syntax has these named arguments:
Parameter
Description
TimeParameter
Required. Parameter to be formatted as a time.This can be a String, Date, Time or DateTime parameter.
See Also
SQL Date Functions

---

## Trim - SQL Function

Source: https://accredo.co.nz/webhelp/TrimSQLFunction.htm

Trim - SQL Function
TRIM ([LEADING|TRAILING|BOTH] FROM String: String): String
Trim
returns String with either leading, trailing or both spaces removed, as specified.
TRIM
can only be used with string or memo fields or constants.
Trim
function syntax has these named arguments:
Parameter
Description
Position
Required. Select from:
Leading
- delete all spaces at the left end of the string.
Trailing
- delete all spaces at the right end of the string.
Both
- delete all spaces at both ends of the string.
String
Required. String to be trimmed.
The following are examples of using the
TRIM
function:
TRIM(LEADING FROM ' ABC ') -
will return
'ABC '
TRIM(TRAILING FROM ' ABC ')
- will return
' ABC'
TRIM(BOTH FROM ' ABC ')
- will return
'ABC'
See Also
SQL String Functions

---

## Upper - SQL Function

Source: https://accredo.co.nz/webhelp/UpperSQLFunction.htm

Upper - SQL Function
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
SQL String Functions

---

## UserPermission - SQL Function

Source: https://accredo.co.nz/webhelp/UserPermissionSQLFunction.htm

UserPermission - SQL Function
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
See Also
SQL User Functions

---

## WeekNo - SQL Function

Source: https://accredo.co.nz/webhelp/WeekNoSQLFunction.htm

WeekNo - SQL Function
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
SQL Date Functions

---

## WordAmount - SQL Function

Source: https://accredo.co.nz/webhelp/WordAmountSQLFunction.htm

WordAmount - SQL Function
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
SQL String Functions

---

## Year - SQL Function

Source: https://accredo.co.nz/webhelp/YearSQLFunction.htm

Year - SQL Function
Year(Date: Date): Number
Year returns the year value for the Date. If Date is Null then Null is returned.
Year function syntax has these named arguments:
Parameter
Description
Date
Required. Date to return the Year value for.
See Also
SQL Date Functions

---

## YearName - SQL Function

Source: https://accredo.co.nz/webhelp/YearNameSQLFunction.htm

YearName - SQL Function
YearName(PeriodID: Number): String
Returns the year name for the year which includes PeriodID.
YearName function syntax has these named arguments:
Parameter
Description
Period ID
Required. Period ID to return the year name for.
See Also
SQL Period Functions

---

