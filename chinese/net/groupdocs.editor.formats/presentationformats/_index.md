---
title: "PresentationFormats"
second_title: "GroupDocs.Editor for .NET API 参考"
description: "封装所有演示文稿格式。包括以下格式"
type: docs
weight: 120
url: /zh/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

封装所有演示文稿格式。包括以下格式：

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

了解更多关于演示文稿格式的信息，请点击[此处](https://wiki.fileformat.com/presentation)。

```csharp
public class PresentationFormats : DocumentFormatBase
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 获取文档格式的文件扩展名。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 获取文档格式所属的格式族。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 获取格式族的唯一标识符。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 获取文档格式的 MIME 类型。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 获取格式族的名称。 |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | 获取所有[`PresentationFormats`](../presentationformats)的可枚举集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | 检索具有指定文件扩展名的指定类型[`PresentationFormats`](../presentationformats)实例。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 确定此实例是否等于指定的 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 确定此实例是否等于指定的 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 实例。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 确定此实例是否等于指定的 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 实例。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 返回当前对象的哈希码。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 返回表示当前对象的字符串。 |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | 将表示文件扩展名的字符串转换为[`PresentationFormats`](../presentationformats)对象。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument 演示文稿（ODP）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/odp)。 |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument 演示文稿模板（OTP）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/otp)。 |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 演示文稿模板（POT）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/pot)。 |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML 启用宏的模板（POTM）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/potm)。 |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML 无宏模板（POTX）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/potx)。 |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 幻灯片放映（PPS）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/pps)。 |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML 启用宏的幻灯片放映（PPSM）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/ppsm)。 |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML 无宏幻灯片放映（PPSX）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/ppsx)。 |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 演示文稿（PPT）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/ppt)。 |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 演示文稿（PPT）。 |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML 启用宏的文档（PPTM）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/pptm)。 |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML 无宏文档（PPTX）。了解此文件格式的更多信息，请点击[此处](https://wiki.fileformat.com/presentation/pptx)。 |

### 另请参见

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
