---
title: "PresentationFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm Sunum formatlarını kapsar. Aşağıdaki formatları içerir"
type: docs
weight: 120
url: /tr/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Tüm Sunum formatlarını kapsar. Aşağıdaki formatları içerir:

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

Sunum formatları hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Tüm [`PresentationFormats`](../presentationformats) öğelerinin bir enumerable koleksiyonunu alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Belirtilen dosya uzantısına sahip, belirtilen tipteki [`PresentationFormats`](../presentationformats) örneğini alır. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Bir dosya uzantısını temsil eden dizeyi bir [`PresentationFormats`](../presentationformats) nesnesine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Sunumu (ODP). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Sunum şablonu (OTP). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Sunum Şablonu (POT). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 Slayt Gösterisi (PPS). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Sunum (PPT). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 Sunumu (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Makro Etkin Belge (PPTM). Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/presentation/pptm) tıklayın. |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML Makro İçermeyen Belge (PPTX). Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/presentation/pptx) tıklayın. |

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
