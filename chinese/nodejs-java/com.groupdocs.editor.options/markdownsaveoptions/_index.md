---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许指定用于生成和保存 Markdown 文档的自定义选项。"
type: docs
weight: 24
url: /zh/nodejs-java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

允许指定用于生成和保存 Markdown 文档的自定义选项。

<br />

*** ** * ** ***

当存在 EditableDocument 类的实例且其中包含已编辑的文档内容时，用户必须使用 MarkdownSaveOptions 类，并且需要将此内容保存为 Markdown 格式的新文档。

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。 |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow 指定在导出为 Markdown 格式时，如何对齐表格中的内容。 |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow 指定在导出为 Markdown 格式时，如何对齐表格中的内容。 |
|
|  | [getImagesFolder()](#getImagesFolder--) | 指定在导出文档时保存图像的物理文件夹 |
Markdown 格式。
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | 指定在导出文档时保存图像的物理文件夹 |
Markdown 格式。
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | 指定是否将图像以 Base64 格式保存到输出文件中。 |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | 指定是否将图像以 Base64 格式保存到输出文件中。 |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。
将此选项设置为
true
可以显著降低生成大型文档时的内存消耗，但会以保存时间变慢为代价。
默认是
false
（为获得更好的性能，已禁用内存优化）。


**Returns:**
布尔
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


在从 HTML 生成文档期间启用内存优化机制，以降低内存使用为代价会降低性能。
将此选项设置为
true
可以显著降低生成大型文档时的内存消耗，但会以保存时间变慢为代价。
默认是
false
（为获得更好的性能，已禁用内存优化）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow 指定在导出为 Markdown 格式时，如何对齐表格中的内容。
默认值是 [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto)。
值：表格内容对齐方式


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow 指定在导出为 Markdown 格式时，如何对齐表格中的内容。
默认值是 [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto)。
值：表格内容对齐方式


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


指定在导出文档时保存图像的物理文件夹
Markdown 格式。默认值为 null。

<br />

*** ** * ** ***

如果用户未指定 ImagesFolder（#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)）和 ExportImagesAsBase64（#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)），则 GroupDocs.Editor 将自行尝试确定 ImagesFolder（#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)），并在成功时应用它。

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


指定在导出文档时保存图像的物理文件夹
Markdown 格式。默认值为 null。

<br />

*** ** * ** ***

如果用户未指定 ImagesFolder（#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)）和 ExportImagesAsBase64（#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)），则 GroupDocs.Editor 将自行尝试确定 ImagesFolder（#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)），并在成功时应用它。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


指定是否将图像以 Base64 格式保存到输出文件中。默认是
false
.

<br />

*** ** * ** ***

当此属性设置为 true 时，图像数据将直接导出到图像元素 ![](../) 中，不会创建单独的文件。若此属性设置为 true，则其优先级高于 MarkdownSaveOptions.ImagesFolder（#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)）属性。

<br />



**Returns:**
布尔
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


指定是否将图像以 Base64 格式保存到输出文件中。默认是
false
.

<br />

*** ** * ** ***

当此属性设置为 true 时，图像数据将直接导出到图像元素 ![](../) 中，不会创建单独的文件。若此属性设置为 true，则其优先级高于 MarkdownSaveOptions.ImagesFolder（#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)）属性。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

