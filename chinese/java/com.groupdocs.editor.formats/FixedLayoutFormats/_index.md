---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for Java API 参考"
description: "封装所有固定布局（亦称 fixed-page）格式，包括 PDF 和 XPS，但不包括光栅图像。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

封装所有固定布局（亦称 "fixed-page"）格式，包括 PDF 和 XPS（不包括光栅图像）

<br />

*** ** * ** ***

各种文档查看或发布应用程序允许用户打开（Adobe Acrobat、XPS Viewer），有时还能编辑（Adobe InDesign）特定格式的文档。这些应用程序通常会生成所谓的 \\u201cfixed-page\\u201d 格式文档。此类文档格式精确描述了文档\u2019s 内容在每页上的放置位置。在内部，PDF 或 XPS 格式包含每页的描述以及绘图指令，指定页面上内容的布局。这类似于图像格式，描述内容以光栅或矢量形式显示的位置。

<br />


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Pdf](#Pdf) | 便携式文档格式（PDF）是一种由 Adobe 在 1990 年代创建的文档。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 对象。 |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


便携式文档格式（PDF）是一种由 Adobe 在 1990 年代创建的文档。此文件格式的目的是引入一种标准，用于以独立于应用软件、硬件以及操作系统的格式表示文档和其他参考材料。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


获取所有 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 的可枚举集合。
值：一个包含所有 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 实例的 IEnumerable{FixedLayoutFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点之后的部分。 |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

