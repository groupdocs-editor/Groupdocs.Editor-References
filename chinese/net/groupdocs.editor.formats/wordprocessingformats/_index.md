---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for .NET API 参考"
description: "封装所有 WordProcessing 格式。包括以下文件类型"
type: docs
weight: 150
url: /zh/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

封装所有文字处理格式。包括以下文件类型：

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

了解更多关于 Word Processing 格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing)。

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 获取文档格式的文件扩展名。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 获取文档格式所属的格式族。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 获取格式族的唯一标识符。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 获取文档格式的 MIME 类型。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 获取格式族的名称。 |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | 获取所有 [`WordProcessingFormats`](../wordprocessingformats) 的可枚举集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | 检索具有指定文件扩展名的指定类型 [`WordProcessingFormats`](../wordprocessingformats) 实例。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 确定此实例是否等于指定的 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 确定此实例是否等于指定的 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 实例。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 确定此实例是否等于指定的 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 实例。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 返回当前对象的哈希码。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 返回表示当前对象的字符串。 |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | 将表示文件扩展名的字符串转换为 [`WordProcessingFormats`](../wordprocessingformats) 对象。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 二进制文件格式 (DOC) 表示由 Microsoft Word 或其他文字处理软件生成的二进制文件格式文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/doc)。 |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML 启用宏文档 (DOCM) 文件是由 Microsoft Word 2007 及以上版本生成且能够运行宏的文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/docm)。 |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML 无宏文档 (DOCX) 是一种广为人知的 Microsoft Word 文档格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/docx)。 |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 模板 (DOT) 是由 Microsoft Word 创建的模板文件，具有预设格式设置，用于生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/dot)。 |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML 启用宏模板 (DOTM) 表示由 Microsoft Word 2007 及以上版本创建的模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/dotm)。 |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML 无宏模板 (DOTX) 是由 Microsoft Word 创建的模板文件，具有预设格式设置，用于生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/dotx)。 |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML 存储为平面 XML 文件，而非 ZIP 包。 |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format 文本文件 (ODT) 是基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/odt)。 |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format 文本文件模板 (OTT) 代表符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/ott)。 |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) 表示一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/rtf)。 |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML 格式 — WordProcessingML 或 WordML (.XML)。 |

### 另请参见

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
