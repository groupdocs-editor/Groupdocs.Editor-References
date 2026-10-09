---
title: "FormatFamilies"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Sistemde mevcut olan farklı format ailelerini temsil eder."
type: docs
weight: 110
url: /tr/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

Sistemde mevcut olan farklı format ailelerini temsil eder.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | eKitap format ailesini temsil eder. Mobi formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/ebook/mobi/), AZW3 formatı hakkında [burada](https://docs.fileformat.com/ebook/azw3/), ve ePub formatı hakkında [burada](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | E-posta format ailesini temsil eder. E-posta formatları hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Fixed Layout format ailesini temsil eder. Çeşitli belge görüntüleme veya yayınlama uygulamaları, kullanıcıların belirli formatlardaki belgeleri açmasına (Adobe Acrobat, XPS Viewer) ve bazen düzenlemesine (Adobe InDesign) izin verir. Bu uygulamalar genellikle sözde “fixed-page” format belgeleri üretir. Böyle bir belge formatı, belgenin içeriğinin her sayfada tam olarak nerede konumlandığını tanımlar. İçeride, PDF veya XPS formatı her sayfanın bir açıklamasını ve sayfadaki içeriğin düzenini belirten çizim talimatlarını içerir. Bu, içeriğin raster veya vektör biçiminde gösterildiğini tanımlayan görüntü formatlarına benzer. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Sunum format ailesini temsil eder. Sunum formatları hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Elektronik tablo format ailesini temsil eder. Çalışma kitabının kaydedilebileceği tüm ikili, XML ve metin tabanlı Elektronik tablo formatları (CSV, TSV, noktalı virgül gibi ayırıcılarla kullanılan tüm metin ayırıcı tabanlı formatlar hariç). |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Metinsel format ailesini temsil eder. İşaretleme dilleri (XML, HTML) ve diğerlerini içeren tüm metin tabanlı (text-based) formatları kapsar. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Kelime işlem format ailesini temsil eder. Kelime işlem formatları hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing). |

### Ayrıca Bakınız

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
