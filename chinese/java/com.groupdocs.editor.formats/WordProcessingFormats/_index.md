---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for Java API 参考"
description: "封装所有文字处理格式。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

封装所有 WordProcessing 格式。包括以下文件类型：
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
了解更多关于 Word Processing 格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing)。

MIME 代码来自以下资源：
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 二进制文件格式 (DOC) 表示由 Microsoft Word 或其他文字处理程序生成的二进制文件格式文档。 |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML 无宏文档 (DOCX) 是一种广为人知的 Microsoft Word 文档格式。 |
|
|  | [Dot](#Dot) | MS Word 97-2007 模板 (DOT) 是由 Microsoft Word 创建的模板文件，具有预设格式，用于生成后续的 DOC 或 DOCX 文件。 |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML 含宏文档 (DOCM) 文件是由 Microsoft Word 2007 及更高版本生成的、能够运行宏的文档。 |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML 无宏模板 (DOTX) 是由 Microsoft Word 创建的模板文件，具有预设格式，用于生成后续的 DOCX 文件。 |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML 含宏模板 (DOTM) 代表由 Microsoft Word 2007 及更高版本创建的模板文件。 |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML 存储在平面 XML 文件中，而不是 ZIP 包。 |
|
|  | [Rtf](#Rtf) | 富文本格式 (RTF) 代表一种用于在应用程序中编码格式化文本和图形的方法。 |
|
|  | [Odt](#Odt) | Open Document Format 文本文档 (ODT) 文件是一种基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档。 |
|
|  | [Ott](#Ott) | Open Document Format 文本文档模板 (OTT) 代表符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。 |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML 格式 — WordProcessingML 或 WordML (.XML)。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 对象。 |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 二进制文件格式 (DOC) 表示由 Microsoft Word 或其他文字处理程序生成的二进制文件格式文档。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML 无宏文档 (DOCX) 是一种广为人知的 Microsoft Word 文档格式。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 模板 (DOT) 是由 Microsoft Word 创建的模板文件，具有预设格式，用于生成后续的 DOC 或 DOCX 文件。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML 含宏文档 (DOCM) 文件是由 Microsoft Word 2007 及更高版本生成的、能够运行宏的文档。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML 无宏模板 (DOTX) 是由 Microsoft Word 创建的模板文件，具有预设格式，用于生成后续的 DOCX 文件。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML 含宏模板 (DOTM) 代表由 Microsoft Word 2007 及更高版本创建的模板文件。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML 存储在平面 XML 文件中，而不是 ZIP 包。


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


富文本格式 (RTF) 代表一种用于在应用程序中编码格式化文本和图形的方法。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format 文本文档 (ODT) 文件是一种基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format 文本文档模板 (OTT) 代表符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。
了解更多关于此文件格式的信息
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML 格式 — WordProcessingML 或 WordML (.XML)。

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


获取所有 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 的可枚举集合。
值：一个包含所有 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 实例的 IEnumerable{WordProcessingFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点之后的部分。 |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

