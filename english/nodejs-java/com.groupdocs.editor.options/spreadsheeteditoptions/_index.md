---
title: SpreadsheetEditOptions
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Allows to specify custom options for editing documents of all supportable Spreadsheet Excel-compatible formats
type: docs
weight: 35
url: /nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents of all supportable
Spreadsheet (Excel-compatible) formats

## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheetIndex()](#getWorksheetIndex--) | Allows to specify the 0-based index of the worksheet (tab) of the input
Spreadsheet document, which should be converted to the HTML (see
remarks).
 |
| [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Allows to specify the 0-based index of the worksheet (tab) of the input
Spreadsheet document, which should be converted to the HTML (see
remarks).
 |
| [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Allows to exclude hidden worksheets in the input Spreadsheet document, so
they will be totally ignored.
 |
| [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Allows to exclude hidden worksheets in the input Spreadsheet document, so
they will be totally ignored.
 |
| [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | When enabled, the empty adjacent horizontal cells from the input Spreadsheet document will be
represented in editable HTML document as merged into a single cell with corresponding
colspan attribute.
 |
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
| [getExportBogusRowData()](#getExportBogusRowData--) | When enabled, the HTML table in produced HTML document contains an empty bottom hidden row with
zero height and empty cells, where only width is specified.
 |
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Allows to specify the 0-based index of the worksheet (tab) of the input
Spreadsheet document, which should be converted to the HTML (see
remarks).


*** ** * ** ***

Most of Spreadsheet documents support a concept of tabs, i.e. they can be multi-tabbed. On the other hand, HTML format doesn't support such structure. Because of this GroupDocs.Editor can convert to the HTML only one specific tab of the input document, and this option allows to specify it. Tab index is 0-based, negative values are prohibited. If specified index exceeds the number of all tabs, the exception will be thrown. If input Spreadsheet document contains only one tab, this option will be ignored. Default value is 0 (first tab).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Allows to specify the 0-based index of the worksheet (tab) of the input
Spreadsheet document, which should be converted to the HTML (see
remarks).


*** ** * ** ***

Most of Spreadsheet documents support a concept of tabs, i.e. they can be multi-tabbed. On the other hand, HTML format doesn't support such structure. Because of this GroupDocs.Editor can convert to the HTML only one specific tab of the input document, and this option allows to specify it. Tab index is 0-based, negative values are prohibited. If specified index exceeds the number of all tabs, the exception will be thrown. If input Spreadsheet document contains only one tab, this option will be ignored. Default value is 0 (first tab).

<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Allows to exclude hidden worksheets in the input Spreadsheet document, so
they will be totally ignored. Default is false - hidden worksheets are
available and processed as normal.


*** ** * ** ***

Several binary Spreadsheet formats (like XLSX) support hidden worksheets (tabs) concept. Document of such format, if it has more then one worksheet, may contain additional hidden worksheets. By default such hidden worksheets are available for processing, but with this option it is able to ignore them, like these hidden worksheets are absent and don't exist. When this option is enabled, you cannot select hidden worksheet with the ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' property.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Allows to exclude hidden worksheets in the input Spreadsheet document, so
they will be totally ignored. Default is false - hidden worksheets are
available and processed as normal.


*** ** * ** ***

Several binary Spreadsheet formats (like XLSX) support hidden worksheets (tabs) concept. Document of such format, if it has more then one worksheet, may contain additional hidden worksheets. By default such hidden worksheets are available for processing, but with this option it is able to ignore them, like these hidden worksheets are absent and don't exist. When this option is enabled, you cannot select hidden worksheet with the ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' property.

<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


When enabled, the empty adjacent horizontal cells from the input Spreadsheet document will be
represented in editable HTML document as merged into a single cell with corresponding
colspan attribute. By default is disabled (false).


By default the GroupDocs.Editor converts a table from input Spreadsheet document to the output
HTML document by preserving each cell. However, the Spreadsheet documents may be sparse \\u2014 they
may contain huge amount of "empty areas", where a lot of cells are empty. This option, when
enabled, merges such empty cells into one with colspan attribute in the TD element,
and thus can significantly reduce the size of the produced HTML markup.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


When enabled, the HTML table in produced HTML document contains an empty bottom hidden row with
zero height and empty cells, where only width is specified. This row with empty cells contains
exact width values for each column and improves backward conversion from HTML to Spreadsheet. By
default is enabled (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

