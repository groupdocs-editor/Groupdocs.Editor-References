---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "包含用于加载二进制 Spreadsheet Cells（Excel 兼容）文档的选项，例如 XLSX、ODS 等。"
type: docs
weight: 36
url: /zh/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

包含用于加载二进制 Spreadsheet（Cells，Excel 兼容）的选项
将 XLS(X)、ODS 等文档加载到 Editor 类中

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | 默认无参数构造函数——所有参数都有默认值 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改并获取将用于 |
打开 Spreadsheet 文档时，如果它已编码。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改并获取将用于 |
打开 Spreadsheet 文档时，如果它已编码。
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在输入文档处理期间启用内存优化机制， |
这可能在某些特殊情况下降低性能，但另一方面
可以减少内存使用。
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在输入文档处理期间启用内存优化机制， |
这可能在某些特殊情况下降低性能，但另一方面
可以减少内存使用。
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


默认无参数构造函数——所有参数都有默认值


### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改并获取将用于
打开 Spreadsheet 文档时，如果它已编码。设置为 NULL 或空
字符串，以便不使用密码（默认值）。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改并获取将用于
打开 Spreadsheet 文档时，如果它已编码。设置为 NULL 或空
字符串，以便不使用密码（默认值）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在输入文档处理期间启用内存优化机制，
这可能在某些特殊情况下降低性能，但另一方面
手动降低内存使用。 在处理大型文档时很有用，并且
面对 OutOfMemoryException。 默认值为 false（内存优化是
为了更好的性能而禁用)。


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在输入文档处理期间启用内存优化机制，
这可能在某些特殊情况下降低性能，但另一方面
手动降低内存使用。 在处理大型文档时很有用，并且
面对 OutOfMemoryException。 默认值为 false（内存优化是
为了更好的性能而禁用)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

