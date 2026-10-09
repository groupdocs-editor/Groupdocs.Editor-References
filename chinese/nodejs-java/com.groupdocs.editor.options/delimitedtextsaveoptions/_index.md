---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "包含用于生成和保存基于文本的电子表格文档（CSV、基于制表符等）且使用分隔符的选项"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

包含用于生成和保存基于文本的电子表格文档的选项
（CSV、基于制表符等），使用分隔符（delimiter）


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | 此无参构造函数创建一个 DelimitedTextSaveOptions 的新实例，默认分隔符为分号 (;)（随后可以通过以下方式修改 |
Separator
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) 属性）
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | 创建一个带有必需 |
分隔符（delimiter）
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | 允许为基于文本的 |
电子表格文档
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | 允许为基于文本的 |
电子表格文档
|
|  | [getEncoding()](#getEncoding--) | 允许为基于文本的 Spreadsheet 文档设置编码。 |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 允许为基于文本的 Spreadsheet 文档设置编码。 |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | 指示是否应修剪前导空行和空列，类似 |
MS Excel 的做法
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | 指示是否应修剪前导空行和空列，类似 |
MS Excel 的做法
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | 指示是否应为空行输出分隔符。 |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | 指示是否应为空行输出分隔符。 |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


此无参构造函数创建一个 DelimitedTextSaveOptions 的新实例，默认分隔符为分号 (;)（随后可以通过以下方式修改
Separator
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) 属性）


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


创建一个带有必需
分隔符（delimiter）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 分隔符 | java.lang.String | 基于文本的 Spreadsheet 文档的字符串分隔符（delimiter） |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


允许为基于文本的
电子表格文档


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


允许为基于文本的
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


指示是否应修剪前导空行和空列，类似
MS Excel 的做法


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


指示是否应修剪前导空行和空列，类似
MS Excel 的做法


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

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
| 值 | 布尔 |  |

