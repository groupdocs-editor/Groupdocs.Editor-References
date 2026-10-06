---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许指定用于生成和保存符合 Excel 标准的 Spreadsheet 文档的自定义选项"
type: docs
weight: 37
url: /zh/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

允许指定用于生成和保存 Spreadsheet 的自定义选项
(符合 Excel 标准) 文档

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | 此无参构造函数创建一个使用 XLSX 输出格式的 SpreadsheetSaveOptions 新实例（随后可通过 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) 属性)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | 创建一个具有指定必需的 SpreadsheetSaveOptions 新实例 |
Spreadsheet 输出格式，而所有其他参数保持默认
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改、获取或移除密码，该密码将 |
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改、获取或移除密码，该密码将 |
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
属性，或者应插入到现有工作表与
前一个工作表之间，而不替换其内容。
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | 布尔标志，指定已编辑的工作表是否应替换 |
原始电子表格中指定位置的现有工作表，位置由
该

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性，或者应插入到现有工作表与
前一个工作表之间，而不替换其内容。
|
|  | [getOutputFormat()](#getOutputFormat--) | 允许指定用于保存的 Spreadsheet 格式， |
文档
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | 允许指定用于保存的 Spreadsheet 格式， |
文档
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | 允许为输出的 Spreadsheet 启用工作表保护 |
文档。
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | 允许为输出的 Spreadsheet 启用工作表保护 |
文档。
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | 允许指定一个包含以 1 为基数的工作表编号数组，这些工作表将在保存期间从电子表格中删除，以防已编辑的工作表被插入到现有电子表格中。 |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | 允许指定一个包含以 1 为基数的工作表编号数组，这些工作表将在保存期间从电子表格中删除，以防已编辑的工作表被插入到现有电子表格中。 |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


此无参构造函数创建一个使用 XLSX 输出格式的 SpreadsheetSaveOptions 新实例（随后可通过
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) 属性)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


创建一个具有指定必需的 SpreadsheetSaveOptions 新实例
Spreadsheet 输出格式，而所有其他参数保持默认


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | 必需的输出格式，Spreadsheet 文档应保存的方式 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改、获取或移除密码，该密码将
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。指定 NULL 或空字符串以移除
(清理) 密码。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改、获取或移除密码，该密码将
用于对生成的 Spreadsheet 文档进行编码，如果该文档格式
支持密码保护。指定 NULL 或空字符串以移除
(清理) 密码。


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
行为)。WorksheetNumber 是工作表的 1 基编号，位于
spreadsheet，加载于 Editor 类中。如果它为 0（默认值），则
将创建一个包含单个已编辑工作表的新 spreadsheet。如果它是
大于或小于零，并且存在有效的 spreadsheet，已加载于
Editor 类中，已编辑的工作表，由输入的
EditableDocument 实例，将插入此 spreadsheet。


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
行为)。WorksheetNumber 是工作表的 1 基编号，位于
spreadsheet，加载于 Editor 类中。如果它为 0（默认值），则
将创建一个包含单个已编辑工作表的新 spreadsheet。如果它是
大于或小于零，并且存在有效的 spreadsheet，已加载于
Editor 类中，已编辑的工作表，由输入的
EditableDocument 实例，将插入此 spreadsheet。


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
属性，或者应插入到现有工作表与
之前的那个，而不替换其内容。默认值为 false \\u2014
现有工作表将被替换。如果值
为

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性设置为 '0'。


*** ** * ** ***

默认情况下工作表会被替换。这意味着如果给定的 spreadsheet 有 5 个工作表，并且 WorksheetNumber（#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int)）=4，则第 4 个工作表将被新的已编辑工作表替换，而 spreadsheet 中工作表的总数（5）保持不变。然而，如果此属性的值设置为 *true*，新的已编辑工作表将被插入为第 4 个工作表，所有后续工作表将向后移动：\"old\" 第 4 个工作表变为第 5 个，第 5 个变为第 6 个，且 spreadsheet 中工作表的总数将增加到 6。

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
属性，或者应插入到现有工作表与
之前的那个，而不替换其内容。默认值为 false \\u2014
现有工作表将被替换。如果值
为

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
属性设置为 '0'。


*** ** * ** ***

默认情况下工作表会被替换。这意味着如果给定的 spreadsheet 有 5 个工作表，并且 WorksheetNumber（#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int)）=4，则第 4 个工作表将被新的已编辑工作表替换，而 spreadsheet 中工作表的总数（5）保持不变。然而，如果此属性的值设置为 *true*，新的已编辑工作表将被插入为第 4 个工作表，所有后续工作表将向后移动：\"old\" 第 4 个工作表变为第 5 个，第 5 个变为第 6 个，且 spreadsheet 中工作表的总数将增加到 6。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


允许指定用于保存的 Spreadsheet 格式，
文档


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


允许指定用于保存的 Spreadsheet 格式，
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
文档。默认值为 NULL - 不应用保护。并非所有格式
支持工作表保护。


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


允许为输出的 Spreadsheet 启用工作表保护
文档。默认值为 NULL - 不应用保护。并非所有格式
支持工作表保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


允许指定一个数组，包含在保存期间应从 spreadsheet 中删除的工作表的基于 1 的编号，前提是已编辑的工作表被插入到已有的 spreadsheet 中。当已编辑工作表不是作为新的单工作表 spreadsheet 保存（默认行为），而是保存到已有的 spreadsheet 中（使用 #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)）时，也可以通过在此数组中指定编号来删除该 spreadsheet 中的特定工作表。默认情况下此数组为  null  \\u2014 不会删除任何工作表。然而，当此数组为非 null 且非空，并且至少包含一个有效的工作表编号时，在生成包含已编辑工作表内容的输出 spreadsheet 文档后，指定编号的工作表将在写入输出流或文件之前从 spreadsheet 中删除。此数组中的工作表编号为基于 1 的，而非 0 基。无效的编号（小于 1 或大于工作表总数）将被忽略。


**Returns:**
int[] - 要删除的基于 1 的工作表编号数组，若不删除任何内容则为  null 。

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


允许指定一个数组，包含在保存期间应从 spreadsheet 中删除的工作表的基于 1 的编号，前提是已编辑的工作表被插入到已有的 spreadsheet 中。此数组中的工作表编号为基于 1 的。无效的编号将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 要删除的基于 1 的工作表编号数组（可为  null  或空）。 |
|

