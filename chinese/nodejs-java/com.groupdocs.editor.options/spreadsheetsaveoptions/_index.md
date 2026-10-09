---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为生成和保存 Spreadsheet Excel兼容文档指定自定义选项"
type: docs
weight: 37
url: /zh/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

允许为生成和保存 Spreadsheet 指定自定义选项
（Excel兼容）文档

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | 此无参数构造函数创建一个 SpreadsheetSaveOptions 的新实例，使用 XLSX 输出格式（随后可通过 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) 属性)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | 使用指定的必需项创建一个 SpreadsheetSaveOptions 的新实例 |
Spreadsheet 输出格式，而所有其他参数保持默认
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改、获取或删除密码，密码将 |
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改、获取或删除密码，密码将 |
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | 允许将已编辑的工作表插入到现有电子表格的副本中 |
而不是创建新的单工作表电子表格（默认
行为）。
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | 允许将已编辑的工作表插入到现有电子表格的副本中 |
而不是创建新的单工作表电子表格（默认
行为）。
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | 布尔标志，指定已编辑的工作表是否应替换 |
原始电子表格中指定位置的现有工作表，位置由
该

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性，或者它应插入到现有工作表与
前一个工作表之间，而不替换其内容。
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | 布尔标志，指定已编辑的工作表是否应替换 |
原始电子表格中指定位置的现有工作表，位置由
该

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性，或者它应插入到现有工作表与
前一个工作表之间，而不替换其内容。
|
|  | [getOutputFormat()](#getOutputFormat--) | 允许指定一种 Spreadsheet 格式，该格式将用于保存 |
文档
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | 允许指定一种 Spreadsheet 格式，该格式将用于保存 |
文档
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | 允许为输出的 Spreadsheet 启用工作表保护 |
文档。
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | 允许为输出的 Spreadsheet 启用工作表保护 |
文档。
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | 允许指定一个包含基于 1 的工作表编号的数组，以在保存电子表格时删除这些工作表，前提是编辑后的工作表被插入到已有的电子表格中。 |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | 允许指定一个包含基于 1 的工作表编号的数组，以在保存电子表格时删除这些工作表，前提是编辑后的工作表被插入到已有的电子表格中。 |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


此无参数构造函数创建一个 SpreadsheetSaveOptions 的新实例，使用 XLSX 输出格式（随后可通过
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) 属性)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


使用指定的必需项创建一个 SpreadsheetSaveOptions 的新实例
Spreadsheet 输出格式，而所有其他参数保持默认


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | 必须的输出格式，电子表格文档应以此格式保存 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改、获取或删除密码，密码将
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。指定 NULL 或空字符串以移除
（清除）密码。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改、获取或删除密码，密码将
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。指定 NULL 或空字符串以移除
（清除）密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


允许将已编辑的工作表插入到现有电子表格的副本中
而不是创建新的单工作表电子表格（默认
行为)。WorksheetNumber 是工作表的基于 1 的编号，位于
电子表格中，由 Editor 类加载。如果它为 0（默认值），则
将创建一个仅包含单个编辑工作表的新电子表格。如果它是
大于或小于零，并且存在已在
Editor 类中的有效电子表格，编辑工作表由输入的
EditableDocument 实例表示的编辑工作表将被插入此电子表格。


*** ** * ** ***

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
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


允许将已编辑的工作表插入到现有电子表格的副本中
而不是创建新的单工作表电子表格（默认
行为)。WorksheetNumber 是工作表的基于 1 的编号，位于
电子表格中，由 Editor 类加载。如果它为 0（默认值），则
将创建一个仅包含单个编辑工作表的新电子表格。如果它是
大于或小于零，并且存在已在
Editor 类中的有效电子表格，编辑工作表由输入的
EditableDocument 实例表示的编辑工作表将被插入此电子表格。


*** ** * ** ***

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
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


布尔标志，指定已编辑的工作表是否应替换
原始电子表格中指定位置的现有工作表，位置由
该

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性，或者它应插入到现有工作表与
之前的工作表，而不替换其内容。默认值为 false \\u2014
现有工作表将被替换。如果属性的值
为

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性设置为 '0' 时，此属性将被忽略。


*** ** * ** ***

默认情况下工作表会被替换。这意味着如果给定的电子表格有 5 个工作表，并且 WorksheetNumber（#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int)）=4，则第 4 个工作表将被新的编辑工作表替换，而电子表格中工作表的总数（5）保持不变。然而，如果此属性的值设置为 *true*，新的编辑工作表将被插入为第 4 个工作表，所有后续工作表将向后移动：\"old\" 第 4 个工作表变为第 5 个，第 5 个变为第 6 个，电子表格中工作表的总数将增加一个，变为 6。

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


布尔标志，指定已编辑的工作表是否应替换
原始电子表格中指定位置的现有工作表，位置由
该

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性，或者它应插入到现有工作表与
之前的工作表，而不替换其内容。默认值为 false \\u2014
现有工作表将被替换。如果属性的值
为

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性设置为 '0' 时，此属性将被忽略。


*** ** * ** ***

默认情况下工作表会被替换。这意味着如果给定的电子表格有 5 个工作表，并且 WorksheetNumber（#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int)）=4，则第 4 个工作表将被新的编辑工作表替换，而电子表格中工作表的总数（5）保持不变。然而，如果此属性的值设置为 *true*，新的编辑工作表将被插入为第 4 个工作表，所有后续工作表将向后移动：\"old\" 第 4 个工作表变为第 5 个，第 5 个变为第 6 个，电子表格中工作表的总数将增加一个，变为 6。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


允许指定一种 Spreadsheet 格式，该格式将用于保存
文档


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


允许指定一种 Spreadsheet 格式，该格式将用于保存
文档


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


允许为输出的 Spreadsheet 启用工作表保护
文档。默认值为 NULL——未应用保护。并非所有格式
支持工作表保护。


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


允许为输出的 Spreadsheet 启用工作表保护
文档。默认值为 NULL——未应用保护。并非所有格式
支持工作表保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


允许指定一个包含基于 1 的工作表编号的数组，以在保存电子表格时删除这些工作表，前提是编辑后的工作表被插入到已有的电子表格中。当编辑工作表不是另存为新的单工作表电子表格（默认行为），而是使用 #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int) 保存到已有电子表格时，也可以通过在此数组中指定编号来删除该电子表格中的特定工作表。默认情况下此数组为  null  \\u2014 不会删除任何工作表。然而，当此数组为非 null 且非空，并且至少包含一个有效的工作表编号时，在生成包含编辑工作表内容的输出电子表格文档后，指定编号的工作表将在写入输出流或文件之前被删除。此数组中的工作表编号为基于 1 的，而非 0 基。无效的编号（小于 1 或大于工作表总数）将被忽略。


**Returns:**
int[] - 要删除的基于 1 的工作表编号数组，若无需删除则为  null 。

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


允许指定一个包含基于 1 的工作表编号的数组，以在保存电子表格时删除这些工作表，前提是编辑后的工作表被插入到已有的电子表格中。此数组中的工作表编号为基于 1 的。无效的编号将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 要删除的基于 1 的工作表编号数组（可以为  null  或为空）。 |
|

