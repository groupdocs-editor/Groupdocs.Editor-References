---
title: "EBookFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm eKitap formatlarını kapsar. Aşağıdaki dosya türlerini içerir Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /tr/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

Tüm eKitap formatlarını kapsar. Aşağıdaki dosya türlerini içerir: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | Tüm [`EBookFormats`](../ebookformats) koleksiyonunu enumerable olarak alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Belirtilen dosya uzantısına sahip belirtilen türdeki [`EBookFormats`](../ebookformats) örneğini alır. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | Bir dosya uzantısını temsil eden dizeyi bir [`EBookFormats`](../ebookformats) nesnesine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, Kindle Format 8 (KF8) olarak da bilinir, Amazon Kindle cihazları için geliştirilen AZW e-kitap dijital dosya formatının değiştirilmiş sürümüdür. Bu format, eski AZW dosyalarına bir iyileştirmedir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Electronic Publication (IDPF ePub) formatı, yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI, MobiPocket Reader için geliştirilen formata verilen isimdir. Ayrıca PRC, AZW olarak da adlandırılır. Şu anda Amazon tarafından biraz farklı bir DRM şemasıyla kullanılmakta ve AZW olarak adlandırılmaktadır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/ebook/mobi/). |

### Açıklamalar

Mobi formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/ebook/mobi/), AZW3 formatı hakkında [burada](https://docs.fileformat.com/ebook/azw3/), ve ePub formatı hakkında [burada](https://docs.fileformat.com/ebook/epub/).

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
