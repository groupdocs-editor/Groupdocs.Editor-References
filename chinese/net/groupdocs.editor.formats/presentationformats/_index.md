---
title: PresentationFormats
second_title: GroupDocs.Editor for .NET API 参考
description: 封装所有 Presentation 格式包括以下格式 Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. 了解有关演示文稿格式的更多信息这里https//wiki.fileformat.com/presentation.
type: docs
weight: 110
url: /zh/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

封装所有 Presentation 格式。包括以下格式： [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). 了解有关演示文稿格式的更多信息[这里](https://wiki.fileformat.com/presentation).

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | 以小写形式返回此演示文稿格式的扩展名（不带前导点字符） |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | 返回此格式的 MIME 代码 |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | 返回此演示文稿格式的正式全名 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | 返回实例[`PresentationFormats`](../presentationformats)结构，与指定的文件扩展名相关联，或者如果无法正确解析扩展名则抛出异常 |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | 判断这个实例是否等于另一个指定的IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | 确定此实例是否等于其他指定对象，大概是装箱的 PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | 判断这个实例是否等于其他指定的 PresentationFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | 返回一个哈希码，对于这个实例是不可变的 |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | 在 equality 上检查两个给定的 PresentationFormats 实例 |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | 在 inequality 上检查两个给定的 PresentationFormats 实例 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP) 文件表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/odp) |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument 演示模板 (OTP) 文件表示应用程序以 OASIS OpenDocument 标准格式创建的演示模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/otp) |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 演示模板 (POT) 文件表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pot) |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML 启用宏的模板 (POTM) 是支持宏的文件。 POTM 文件是使用 PowerPoint 2007 或更高版本创建的，包含可用于创建更多演示文稿文件的默认设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potm) |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML 无宏模板 (POTX) 文件表示使用 Microsoft PowerPoint 2007 及更高版本创建的 Microsoft PowerPoint 模板演示文稿。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potx) |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 幻灯片 (PPS) 文件是使用 Microsoft PowerPoint 创建的，用于幻灯片放映。 Microsoft PowerPoint 97-2003 支持 PPS 文件读取和创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pps) |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) 文件是使用 Microsoft PowerPoint 2007 或更高版本创建的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML 无宏幻灯片 (PPSX) 文件是使用 Microsoft PowerPoint 2007 及更高版本创建的，用于幻灯片放映目的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint 演示文稿 (.ppt) 代表 PowerPoint 文件，该文件由一组幻灯片组成，用于显示为 SlideShow。它指定 Microsoft PowerPoint 97-2003 使用的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 演示文稿 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | 使用 Microsoft PowerPoint 2007 或更高版本创建的 Microsoft Office Open XML PresentationML 启用宏的文档 (PPTM) 文件。它们类似于 PPTX 文件，不同之处在于横向不能执行宏，但它们可以包含宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML 演示文稿 (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。与以前版本的二进制演示文稿文件格式 PPT 不同，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptx) |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | 返回一个内部类，它为所有现有的 Presentation formats 提供可枚举的可能性 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | 实现 IEnumerable 通用接口，为 PresentationFormats type 启用“foreach”可能性 |

### 也可以看看

* interface [IDocumentFormat](../idocumentformat)
* 命名空间 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
