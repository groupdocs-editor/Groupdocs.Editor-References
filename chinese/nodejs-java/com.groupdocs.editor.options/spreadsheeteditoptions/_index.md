---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为所有支持的电子表格（Excel 兼容）格式的文档编辑指定自定义选项"
type: docs
weight: 35
url: /zh/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

允许为所有支持的文档指定自定义编辑选项
电子表格（Excel 兼容）格式

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 允许指定输入工作表（标签页）的 0 基索引 |
应转换为 HTML 的电子表格文档（参见
备注）。
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 允许指定输入工作表（标签页）的 0 基索引 |
应转换为 HTML 的电子表格文档（参见
备注）。
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | 允许排除输入电子表格文档中的隐藏工作表，因此 |
它们将被完全忽略。
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | 允许排除输入电子表格文档中的隐藏工作表，因此 |
它们将被完全忽略。
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | 启用后，来自输入电子表格文档的相邻空白水平单元格将 |
在可编辑的 HTML 文档中表示为合并为具有相应
colspan 属性的单元格。
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | 启用后，生成的 HTML 文档中的 HTML 表格包含一个底部空白隐藏行，具有 |
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


允许指定输入工作表（标签页）的 0 基索引
应转换为 HTML 的电子表格文档（参见
备注）。


*** ** * ** ***

大多数电子表格文档支持标签概念，即它们可以是多标签的。另一方面，HTML 格式不支持此结构。因此，GroupDocs.Editor 在转换为 HTML 时只能转换输入文档的一个特定标签，此选项允许指定该标签。标签索引从 0 开始，负值不允许。如果指定的索引超过所有标签的数量，将抛出异常。如果输入电子表格文档只有一个标签，则此选项将被忽略。默认值为 0（第一个标签）。

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


允许指定输入工作表（标签页）的 0 基索引
应转换为 HTML 的电子表格文档（参见
备注）。


*** ** * ** ***

大多数电子表格文档支持标签概念，即它们可以是多标签的。另一方面，HTML 格式不支持此结构。因此，GroupDocs.Editor 在转换为 HTML 时只能转换输入文档的一个特定标签，此选项允许指定该标签。标签索引从 0 开始，负值不允许。如果指定的索引超过所有标签的数量，将抛出异常。如果输入电子表格文档只有一个标签，则此选项将被忽略。默认值为 0（第一个标签）。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


允许排除输入电子表格文档中的隐藏工作表，因此
它们将被完全忽略。默认值为 false - 隐藏工作表是
可用的，并按常规处理。


*** ** * ** ***

几种二进制电子表格格式（如 XLSX）支持隐藏工作表（标签）概念。此类格式的文档如果包含多个工作表，可能包含额外的隐藏工作表。默认情况下，这些隐藏工作表可用于处理，但使用此选项可以忽略它们，就好像这些隐藏工作表不存在。当启用此选项时，您无法使用 ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' 属性选择隐藏工作表。

<br />



**Returns:**
布尔
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


允许排除输入电子表格文档中的隐藏工作表，因此
它们将被完全忽略。默认值为 false - 隐藏工作表是
可用的，并按常规处理。


*** ** * ** ***

几种二进制电子表格格式（如 XLSX）支持隐藏工作表（标签）概念。此类格式的文档如果包含多个工作表，可能包含额外的隐藏工作表。默认情况下，这些隐藏工作表可用于处理，但使用此选项可以忽略它们，就好像这些隐藏工作表不存在。当启用此选项时，您无法使用 ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' 属性选择隐藏工作表。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


启用后，来自输入电子表格文档的相邻空白水平单元格将
在可编辑的 HTML 文档中表示为合并为具有相应
colspan 属性。默认情况下为禁用（false）。


默认情况下，GroupDocs.Editor 将输入电子表格文档中的表格转换为输出的
HTML 文档，保留每个单元格。然而，电子表格文档可能是稀疏的——它们
可能包含大量的“空白区域”，其中许多单元格为空。此选项在
启用时，会将这些空单元格合并为 TD 元素中具有 colspan 属性的一个单元格，
从而显著减少生成的 HTML 标记的大小。


**Returns:**
布尔
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


启用后，生成的 HTML 文档中的 HTML 表格包含一个底部空白隐藏行，具有
零高度和空单元格，仅指定宽度。此包含空单元格的行包含
每列的精确宽度值，并改进从 HTML 到电子表格的反向转换。通过
默认情况下为启用（true）。


**Returns:**
布尔
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

