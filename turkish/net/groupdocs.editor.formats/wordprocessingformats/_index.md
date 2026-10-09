---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm WordProcessing biçimlerini kapsar. Aşağıdaki dosya türlerini içerir"
type: docs
weight: 150
url: /tr/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Tüm Kelime İşleme formatlarını kapsar. Aşağıdaki dosya türlerini içerir:

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

Word Processing biçimleri hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing) bakın.

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Tüm [`WordProcessingFormats`](../wordprocessingformats) öğelerinin yinelenebilir bir koleksiyonunu alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Belirtilen dosya uzantısına sahip belirtilen türdeki [`WordProcessingFormats`](../wordprocessingformats) örneğini alır. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Dosya uzantısını temsil eden bir dizeyi bir [`WordProcessingFormats`](../wordprocessingformats) nesnesine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 İkili Dosya Biçimi (DOC), Microsoft Word veya diğer kelime işlemci programları tarafından ikili formatta oluşturulan belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/word-processing/doc) bakın. |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM) dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümler tarafından oluşturulan belgelerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX), Microsoft Word belgeleri için yaygın bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Şablonu (DOT), daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM), Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan şablon dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX), daha sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML, ZIP paketi yerine düz bir XML dosyasında depolanır. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format Text Document (ODT) dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgelerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML veya WordML (.XML). |

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
