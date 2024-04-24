---
title: SpreadsheetSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving Spreadsheet Excel-compliant documents
type: docs
weight: 35
url: /java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving Spreadsheet (Excel-compliant) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | This parameterless constructor creates a new instance of SpreadsheetSaveOptions with XLSX output format (can be modified then through  OutputFormat (\#getOutputFormat.getOutputFormat/\#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) property) |
| [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Creates a new instance of SpreadsheetSaveOptions with specified mandatory Spreadsheet output format, while all other parameters are default |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated Spreadsheet document, if tis document format supports password protection. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated Spreadsheet document, if tis document format supports password protection. |
| [getWorksheetNumber()](#getWorksheetNumber--) | Allows to insert edited worksheet into copy of existing spreadsheet instead of creating a new single-worksheet spreadsheet (default behavior). |
| [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Allows to insert edited worksheet into copy of existing spreadsheet instead of creating a new single-worksheet spreadsheet (default behavior). |
| [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Boolean flag, which specifies whether edited worksheet should replace the existing worksheet in original spreadsheet on the position, specified by the  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int)) property, or it should be injected between existing worksheet and previous one, without replacing its content. |
| [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Boolean flag, which specifies whether edited worksheet should replace the existing worksheet in original spreadsheet on the position, specified by the  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int)) property, or it should be injected between existing worksheet and previous one, without replacing its content. |
| [getOutputFormat()](#getOutputFormat--) | Allows to specify a Spreadsheet format, which will be used for saving the document |
| [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Allows to specify a Spreadsheet format, which will be used for saving the document |
| [getWorksheetProtection()](#getWorksheetProtection--) | Allows to enable a worksheet protection for the output Spreadsheet document. |
| [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Allows to enable a worksheet protection for the output Spreadsheet document. |
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


This parameterless constructor creates a new instance of SpreadsheetSaveOptions with XLSX output format (can be modified then through  OutputFormat (\#getOutputFormat.getOutputFormat/\#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) property)

### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Creates a new instance of SpreadsheetSaveOptions with specified mandatory Spreadsheet output format, while all other parameters are default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Mandatory output format, in which the Spreadsheet document should be saved |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated Spreadsheet document, if tis document format supports password protection. Specify NULL or empty string for removing (cleaning) the password.

**Returns:**
java.lang.String - 
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated Spreadsheet document, if tis document format supports password protection. Specify NULL or empty string for removing (cleaning) the password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Allows to insert edited worksheet into copy of existing spreadsheet instead of creating a new single-worksheet spreadsheet (default behavior). WorksheetNumber is a 1-based number of a worksheet in the spreadsheet, loaded in the Editor class. If it is 0 (default value), the new spreadsheet will be created with single edited worksheet. If it is greater or lesser then zero, and there is valid spreadsheet, loaded in the Editor class, the edited worksheet, that is represented by input EditableDocument instance, will be inserted into this spreadsheet.

--------------------

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
> ```

--------------------

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (\#getInsertAsNewWorksheet.getInsertAsNewWorksheet/\#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

**Returns:**
int - 
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Allows to insert edited worksheet into copy of existing spreadsheet instead of creating a new single-worksheet spreadsheet (default behavior). WorksheetNumber is a 1-based number of a worksheet in the spreadsheet, loaded in the Editor class. If it is 0 (default value), the new spreadsheet will be created with single edited worksheet. If it is greater or lesser then zero, and there is valid spreadsheet, loaded in the Editor class, the edited worksheet, that is represented by input EditableDocument instance, will be inserted into this spreadsheet.

--------------------

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
> ```

--------------------

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (\#getInsertAsNewWorksheet.getInsertAsNewWorksheet/\#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Boolean flag, which specifies whether edited worksheet should replace the existing worksheet in original spreadsheet on the position, specified by the  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int)) property, or it should be injected between existing worksheet and previous one, without replacing its content. By default is false \\u2014 existing worksheet will be replaced. This property is ignored, if value of  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int)) property is set to '0'.

--------------------

By default worksheet is replaced. This means that if given spreadsheet has 5 worksheets, and  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int))=4, then 4th worksheet will be replaced with the new edited worksheet, while the total amount of worksheets in spreadsheet (5) will remain untouched. However, if value of this property is set to  *true* , the new edited worksheet will be injected as 4th worksheet, and all subsequent worksheets will be shifted to the end: "old" 4th worksheet becomes 5th, and 5th becomes 6th, and the total amount of worksheets in spreadsheet will be incremented by one and equal to 6.

**Returns:**
boolean - 
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Boolean flag, which specifies whether edited worksheet should replace the existing worksheet in original spreadsheet on the position, specified by the  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int)) property, or it should be injected between existing worksheet and previous one, without replacing its content. By default is false \\u2014 existing worksheet will be replaced. This property is ignored, if value of  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int)) property is set to '0'.

--------------------

By default worksheet is replaced. This means that if given spreadsheet has 5 worksheets, and  WorksheetNumber (\#getWorksheetNumber.getWorksheetNumber/\#setWorksheetNumber(int).setWorksheetNumber(int))=4, then 4th worksheet will be replaced with the new edited worksheet, while the total amount of worksheets in spreadsheet (5) will remain untouched. However, if value of this property is set to  *true* , the new edited worksheet will be injected as 4th worksheet, and all subsequent worksheets will be shifted to the end: "old" 4th worksheet becomes 5th, and 5th becomes 6th, and the total amount of worksheets in spreadsheet will be incremented by one and equal to 6.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Allows to specify a Spreadsheet format, which will be used for saving the document

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Allows to specify a Spreadsheet format, which will be used for saving the document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Allows to enable a worksheet protection for the output Spreadsheet document. By default is NULL - protection is not applied. Not all formats support a worksheet protection.

**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Allows to enable a worksheet protection for the output Spreadsheet document. By default is NULL - protection is not applied. Not all formats support a worksheet protection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

