---
title: WordProcessingFormats
second_title: GroupDocs.Editor for .NET API 参考
description: 封装所有文字处理格式包括以下文件类型 Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . 了解有关文字处理格式的更多信息这里https//wiki.fileformat.com/wordprocessing.
type: docs
weight: 170
url: /zh/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

封装所有文字处理格式。包括以下文件类型： [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . 了解有关文字处理格式的更多信息[这里](https://wiki.fileformat.com/word-processing).

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | 以小写形式返回此 WordProcessing 格式的扩展名（不带前导点字符） |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | 返回此格式的 MIME 代码 |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | 返回此字处理格式的正式全名 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | 返回实例[`WordProcessingFormats`](../wordprocessingformats)结构，关联到指定的文件扩展名，或者如果扩展名无法正确解析，则抛出异常 |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | 确定此实例是否等于其他指定的 IDocumentFormat 实例 |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | 确定这个实例是否等于另一个指定的对象，大概是装箱的 WordProcessingFormats |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | 确定此实例是否等于其他指定的 WordProcessingFormats 实例 |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | 返回一个哈希码，对于这个实例是不可变的 |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | 返回此特定格式的名称，与“名称”属性相同 |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | 检查两个给定的 WordProcessingFormats 实例是否相等 |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | 从指定的 WordProcessingFormats 实例的基础字段返回一个字节值 (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | 在不等式 上检查两个给定的 WordProcessingFormats 实例 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 二进制文件格式 (DOC) 表示由 Microsoft Word 或其他二进制文件格式的文字处理文档生成的文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML 启用宏的文档 (DOCM) 文件是 Microsoft Word 2007 或更高版本生成的文档，能够运行宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML 无宏文档 (DOCX) 是一种众所周知的 Microsoft Word 文档格式。从 2007 年随着 Microsoft Office 2007 的发布引入，这种新文档格式的结构从普通二进制更改为 XML 和二进制文件的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 模板是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOC 或 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML 启用宏的模板 (DOTM) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML 无宏模板 (DOTX) 是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML 存储在平面 XML 文件中，而不是 ZIP 包中 |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | 开放文档格式文本文档 (ODT) 文件是使用基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | 开放文档格式文本文档模板 (OTT) 表示由应用程序生成的符合 OASIS 的 OpenDocument 标准格式的模板文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | 富文本格式 (RTF) 表示一种对格式化文本和图形进行编码以在应用程序中使用的方法。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML 格式 — WordProcessingML 或 WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | 返回一个内部类，它为所有现有的文字处理格式提供了可枚举的可能性 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | 实现 IEnumerable 通用接口，为 WordProcessingFormats 类型启用“foreach”可能性 |

### 评论

MIME 代码是从给定的资源中获取的： https://fileext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### 也可以看看

* interface [IDocumentFormat](../idocumentformat)
* 命名空间 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
