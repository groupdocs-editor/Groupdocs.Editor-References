---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "用于加载基于文本的电子表格文档（CSV、制表符分隔等）的选项，这些文档使用分隔符。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

用于加载基于文本的电子表格文档（CSV、制表符分隔等）的选项，
使用分隔符（delimiter）


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | 创建一个带有必需 |
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
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | 获取或设置一个值，指示基于文本的字符串是否 |
文档被转换为日期数据。
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | 获取或设置一个值，指示基于文本的字符串是否 |
文档被转换为日期数据。
|
|  | [getConvertNumericData()](#getConvertNumericData--) | 获取或设置一个值，指示基于文本的字符串是否 |
文档被转换为数值数据。
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | 获取或设置一个值，指示基于文本的字符串是否 |
文档被转换为数值数据。
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | 定义是否将连续的分隔符视为一个。 |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | 定义是否将连续的分隔符视为一个。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在输入文档处理期间启用内存优化机制， |
这可能在某些特殊情况下降低性能，但另一方面
可以减少内存使用。
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在输入文档处理期间启用内存优化机制， |
这可能在某些特殊情况下降低性能，但另一方面
可以减少内存使用。
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


创建一个带有必需
分隔符（delimiter）


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 分隔符 | java.lang.String | 必需的分隔符（delimiter），不能为 NULL 或为空 |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


允许为基于文本的
电子表格文档


**Returns:**
java.lang.String
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

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


获取或设置一个值，指示基于文本的字符串是否
文档被转换为日期数据。默认值为 false。


**Returns:**
布尔
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


获取或设置一个值，指示基于文本的字符串是否
文档被转换为日期数据。默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


获取或设置一个值，指示基于文本的字符串是否
文档被转换为数值数据。默认值为 false。


**Returns:**
布尔
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


获取或设置一个值，指示基于文本的字符串是否
文档被转换为数值数据。默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


定义是否将连续的分隔符视为一个。通过
默认值为 false。


**Returns:**
布尔
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


定义是否将连续的分隔符视为一个。通过
默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在输入文档处理期间启用内存优化机制，
这可能在某些特殊情况下降低性能，但另一方面
可以减少内存使用。当处理超大文档时非常有用，并且
遇到 OutOfMemoryException 时。默认值为 false（内存优化是
为获得更好性能而禁用）。


**Returns:**
布尔
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在输入文档处理期间启用内存优化机制，
这可能在某些特殊情况下降低性能，但另一方面
可以减少内存使用。当处理超大文档时非常有用，并且
遇到 OutOfMemoryException 时。默认值为 false（内存优化是
为获得更好性能而禁用）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

