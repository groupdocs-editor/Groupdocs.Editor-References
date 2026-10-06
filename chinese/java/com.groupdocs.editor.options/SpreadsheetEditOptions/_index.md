---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许为所有支持的 Spreadsheet Excel 兼容格式的文档编辑指定自定义选项"
type: docs
weight: 35
url: /zh/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

允许为编辑所有可支持的文档指定自定义选项
Spreadsheet（Excel 兼容）格式

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 允许指定输入工作表（标签）的 0 基索引 |
应转换为 HTML 的 Spreadsheet 文档（参见
备注）。
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 允许指定输入工作表（标签）的 0 基索引 |
应转换为 HTML 的 Spreadsheet 文档（参见
备注）。
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | 允许排除输入 Spreadsheet 文档中的隐藏工作表，以便 |
它们将被完全忽略。
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | 允许排除输入 Spreadsheet 文档中的隐藏工作表，以便 |
它们将被完全忽略。
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | 启用后，来自输入 Spreadsheet 文档的相邻空水平单元格将被 |
在可编辑的 HTML 文档中表示为合并为一个单元格，并带有相应的
colspan 属性。
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | 启用后，生成的 HTML 文档中的 HTML 表格将包含一个底部空隐藏行，具有 |
零高度和空单元格，仅指定宽度。
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


允许指定输入工作表（标签）的 0 基索引
应转换为 HTML 的 Spreadsheet 文档（参见
备注）。


*** ** * ** ***

大多数 Spreadsheet 文档支持标签概念，即它们可以拥有多个标签。另一方面，HTML 格式不支持此类结构。因此，GroupDocs.Editor 在转换为 HTML 时只能转换输入文档的一个特定标签，此选项用于指定该标签。标签索引为 0 基，负值被禁止。如果指定的索引超出所有标签的数量，将抛出异常。如果输入 Spreadsheet 文档仅包含一个标签，则此选项将被忽略。默认值为 0（第一个标签）。

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


允许指定输入工作表（标签）的 0 基索引
应转换为 HTML 的 Spreadsheet 文档（参见
备注）。


*** ** * ** ***

大多数 Spreadsheet 文档支持标签概念，即它们可以拥有多个标签。另一方面，HTML 格式不支持此类结构。因此，GroupDocs.Editor 在转换为 HTML 时只能转换输入文档的一个特定标签，此选项用于指定该标签。标签索引为 0 基，负值被禁止。如果指定的索引超出所有标签的数量，将抛出异常。如果输入 Spreadsheet 文档仅包含一个标签，则此选项将被忽略。默认值为 0（第一个标签）。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


允许排除输入 Spreadsheet 文档中的隐藏工作表，以便
它们将被完全忽略。默认值为 false——隐藏工作表是
可用的并按常规处理。


*** ** * ** ***

一些二进制 Spreadsheet 格式（如 XLSX）支持隐藏工作表（标签）概念。此类格式的文档如果包含多个工作表，可能会包含额外的隐藏工作表。默认情况下，这些隐藏工作表是可供处理的，但使用此选项可以将其忽略，就好像这些隐藏工作表不存在一样。启用此选项后，无法使用 ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' 属性选择隐藏工作表。

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


允许排除输入 Spreadsheet 文档中的隐藏工作表，以便
它们将被完全忽略。默认值为 false——隐藏工作表是
可用的并按常规处理。


*** ** * ** ***

一些二进制 Spreadsheet 格式（如 XLSX）支持隐藏工作表（标签）概念。此类格式的文档如果包含多个工作表，可能会包含额外的隐藏工作表。默认情况下，这些隐藏工作表是可供处理的，但使用此选项可以将其忽略，就好像这些隐藏工作表不存在一样。启用此选项后，无法使用 ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' 属性选择隐藏工作表。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


启用后，来自输入 Spreadsheet 文档的相邻空水平单元格将被
在可编辑的 HTML 文档中表示为合并为一个单元格，并带有相应的
colspan 属性。默认情况下已禁用（false）。


默认情况下，GroupDocs.Editor 将输入 Spreadsheet 文档中的表格转换为输出的
HTML 文档，同时保留每个单元格。然而，Spreadsheet 文档可能是稀疏的 \u2014 它们
可能包含大量的"empty areas"，其中许多单元格为空。此选项在
启用时，会将这些空单元格合并为 TD 元素中带有 colspan 属性的一个单元格，
从而显著减少生成的 HTML 标记的大小。


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


启用后，生成的 HTML 文档中的 HTML 表格将包含一个底部空隐藏行，具有
零高度和空单元格，仅指定宽度。此包含空单元格的行包含
为每列提供精确的宽度值，并改进从 HTML 到电子表格的反向转换。通过
默认已启用（true）。


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

