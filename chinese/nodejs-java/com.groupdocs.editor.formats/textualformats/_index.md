---
title: "TextualFormats"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装所有基于文本的格式，包括标记 XML、HTML 等。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

封装所有文本（基于文本）格式，包括标记语言（XML、HTML）等。
包括以下格式：
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Html](#Html) | 超文本标记语言文档（HTML）是用于在浏览器中显示的网页的扩展名。 |
|
|  | [Xml](#Xml) | 可扩展标记语言文档（XML）类似于 HTML，但在使用标签定义对象方面不同。 |
|
|  | [Txt](#Txt) | 纯文本文档（TXT）表示一种包含以行形式呈现的纯文本的文档。 |
|
|  | [Md](#Md) | Markdown 是一种轻量级标记语言，用于使用纯文本编辑器创建格式化文本。 |
|
|  | [Json](#Json) | JSON（JavaScript 对象表示法）是一种开放标准文件格式，用于共享数据，使用人类可读的文本来存储和传输数据。 |
|
|  | [Mhtml](#Mhtml) | MIME 聚合 HTML 文档的封装是一种网页存档格式，用于在单个计算机文件中合并 HTML 代码及其伴随资源。 |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help 是微软专有的在线帮助二进制格式，由一组 HTML 页面、索引和其他导航工具组成。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 对象。 |
|
### Html {#Html}
```
public static final TextualFormats Html
```


超文本标记语言文档（HTML）是用于在浏览器中显示的网页的扩展名。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


可扩展标记语言文档（XML）类似于 HTML，但在使用标签定义对象方面不同。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


纯文本文档（TXT）表示一种包含以行形式呈现的纯文本的文档。
了解有关此文件格式的更多信息
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown 是一种轻量级标记语言，用于使用纯文本编辑器创建格式化文本。
了解有关此文件格式的更多信息
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON（JavaScript 对象表示法）是一种开放标准文件格式，用于共享数据，使用人类可读的文本来存储和传输数据。
了解有关此文件格式的更多信息
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME 聚合 HTML 文档的封装是一种网页存档格式，用于在单个计算机文件中合并 HTML 代码及其伴随资源。
了解有关此文件格式的更多信息
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help 是微软专有的在线帮助二进制格式，由一组 HTML 页面、索引和其他导航工具组成。
了解有关此文件格式的更多信息
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


获取所有 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 的可枚举集合。
值：一个包含所有 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 实例的 IEnumerable{TextualFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点后的部分。 |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

