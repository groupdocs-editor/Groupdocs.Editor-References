---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "包含用于生成和保存基于文本的 Spreadsheet 文档（CSV、Tab-based 等）并使用分隔符的选项"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

包含用于生成和保存基于文本的 Spreadsheet 文档的选项
(CSV、Tab-based 等)，使用分隔符（delimiter）


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | 此无参数构造函数创建一个 DelimitedTextSaveOptions 的新实例，默认分隔符为分号 (;)（可以随后通过 |
分隔符
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) 属性)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | 创建带有必需的分隔文本选项类的实例 |
分隔符（delimiter）
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | 允许为基于文本的指定字符串分隔符（delimiter） |
电子表格文档
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | 允许为基于文本的指定字符串分隔符（delimiter） |
电子表格文档
|
|  | [getEncoding()](#getEncoding--) | 允许为基于文本的 Spreadsheet 文档设置编码。 |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 允许为基于文本的 Spreadsheet 文档设置编码。 |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | 指示是否应修剪前导的空行和空列，如 |
MS Excel 所做的
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | 指示是否应修剪前导的空行和空列，如 |
MS Excel 所做的
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | 指示是否应为空行输出分隔符。 |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | 指示是否应为空行输出分隔符。 |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


此无参数构造函数创建一个 DelimitedTextSaveOptions 的新实例，默认分隔符为分号 (;)（可以随后通过
分隔符
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) 属性)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


创建带有必需的分隔文本选项类的实例
分隔符（delimiter）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 分隔符 | java.lang.String | String 分隔符（delimiter），用于基于文本的 Spreadsheet 文档 |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


允许为基于文本的指定字符串分隔符（delimiter）
电子表格文档


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


允许为基于文本的指定字符串分隔符（delimiter）
电子表格文档


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


允许为基于文本的 Spreadsheet 文档设置编码。通过
默认（如果未指定）为 UTF8。


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


允许为基于文本的 Spreadsheet 文档设置编码。通过
默认（如果未指定）为 UTF8。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


指示是否应修剪前导的空行和空列，如
MS Excel 所做的


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


指示是否应修剪前导的空行和空列，如
MS Excel 所做的


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


指示是否应为空行输出分隔符。默认
值为 false，这意味着空行的内容将为空。


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


指示是否应为空行输出分隔符。默认
值为 false，这意味着空行的内容将为空。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

