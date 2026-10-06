---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许为生成和保存 XPS XML 纸张规范文档指定自定义选项"
type: docs
weight: 54
url: /zh/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

允许为生成和保存 XPS（XML 纸张规范）文档指定自定义选项。

<br />

*** ** * ** ***

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。它被开发为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | 负责将字体资源嵌入生成的 XPS 文档中，这些字体在原始文档中使用。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。 |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


负责将字体资源嵌入生成的 XPS 文档中，这些字体在原始文档中使用。
默认情况下不嵌入任何字体（NotEmbed）。


**Returns:**
字节
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。
将此选项设为 true 可以在生成大型文档时显著降低内存消耗，但会以保存时间变慢为代价。
默认值为 false（为获得更好的性能，内存优化已被禁用）。


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在从 HTML 生成文档的过程中启用内存优化机制，这会以降低性能为代价来减少内存使用。
将此选项设为 true 可以在生成大型文档时显著降低内存消耗，但会以保存时间变慢为代价。
默认值为 false（为获得更好的性能，内存优化已被禁用）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

