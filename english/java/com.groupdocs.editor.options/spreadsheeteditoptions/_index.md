---
title: SpreadsheetEditOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Allows to specify custom options for editing documents of all supportable
 Spreadsheet Excel-compatible formats
type: docs
weight: 34
url: /java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents of all supportable Spreadsheet (Excel-compatible) formats
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheetIndex()](#getWorksheetIndex--) | Allows to specify the 0-based index of the worksheet (tab) of the input Spreadsheet document, which should be converted to the HTML (see remarks). |
| [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Allows to specify the 0-based index of the worksheet (tab) of the input Spreadsheet document, which should be converted to the HTML (see remarks). |
| [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Allows to exclude hidden worksheets in the input Spreadsheet document, so they will be totally ignored. |
| [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Allows to exclude hidden worksheets in the input Spreadsheet document, so they will be totally ignored. |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Allows to specify the 0-based index of the worksheet (tab) of the input Spreadsheet document, which should be converted to the HTML (see remarks).

--------------------

Most of Spreadsheet documents support a concept of tabs, i.e. they can be multi-tabbed. On the other hand, HTML format doesn't support such structure. Because of this GroupDocs.Editor can convert to the HTML only one specific tab of the input document, and this option allows to specify it. Tab index is 0-based, negative values are prohibited. If specified index exceeds the number of all tabs, the exception will be thrown. If input Spreadsheet document contains only one tab, this option will be ignored. Default value is 0 (first tab).

**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Allows to specify the 0-based index of the worksheet (tab) of the input Spreadsheet document, which should be converted to the HTML (see remarks).

--------------------

Most of Spreadsheet documents support a concept of tabs, i.e. they can be multi-tabbed. On the other hand, HTML format doesn't support such structure. Because of this GroupDocs.Editor can convert to the HTML only one specific tab of the input document, and this option allows to specify it. Tab index is 0-based, negative values are prohibited. If specified index exceeds the number of all tabs, the exception will be thrown. If input Spreadsheet document contains only one tab, this option will be ignored. Default value is 0 (first tab).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Allows to exclude hidden worksheets in the input Spreadsheet document, so they will be totally ignored. Default is false - hidden worksheets are available and processed as normal.

--------------------

Several binary Spreadsheet formats (like XLSX) support hidden worksheets (tabs) concept. Document of such format, if it has more then one worksheet, may contain additional hidden worksheets. By default such hidden worksheets are available for processing, but with this option it is able to ignore them, like these hidden worksheets are absent and don't exist. When this option is enabled, you cannot select hidden worksheet with the '\`\`\` WorksheetIndex \`\`\`([\#getWorksheetIndex](../../null/\#getWorksheetIndex)/[\#setWorksheetIndex(int)](../../null/\#setWorksheetIndex-int-))' property.

**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Allows to exclude hidden worksheets in the input Spreadsheet document, so they will be totally ignored. Default is false - hidden worksheets are available and processed as normal.

--------------------

Several binary Spreadsheet formats (like XLSX) support hidden worksheets (tabs) concept. Document of such format, if it has more then one worksheet, may contain additional hidden worksheets. By default such hidden worksheets are available for processing, but with this option it is able to ignore them, like these hidden worksheets are absent and don't exist. When this option is enabled, you cannot select hidden worksheet with the '\`\`\` WorksheetIndex \`\`\`([\#getWorksheetIndex](../../null/\#getWorksheetIndex)/[\#setWorksheetIndex(int)](../../null/\#setWorksheetIndex-int-))' property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

