---
title: WordProcessingFormats
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Tüm Kelime İşleme biçimlerini kapsüller. Aşağıdaki dosya türlerini içerir Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Kelime İşleme biçimleri hakkında daha fazla bilgi edininburadahttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /tr/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Tüm Kelime İşleme biçimlerini kapsüller. Aşağıdaki dosya türlerini içerir: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Kelime İşleme biçimleri hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Bu WordProcessing biçiminin bir uzantısını (baştaki nokta karakteri olmadan) küçük harfle döndürür |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Bu biçim için bir MIME kodu döndürür |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Bu Kelime İşleme biçiminin resmi bir tam adını döndürür |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | örneğini döndürür[`WordProcessingFormats`](../wordprocessingformats)yapı, belirtilen dosya adı uzantısıyla ilişkilendirilir veya uzantı düzgün bir şekilde ayrıştırılamazsa bir istisna atar |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Bu örneğin belirtilen diğer IDocumentFormat örneğine eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Bu örneğin, muhtemelen kutulu WordProcessingFormats olan belirtilen diğer nesneye eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Bu örneğin, belirtilen diğer WordProcessingFormats örneğine eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Bu örnek için sabit olan bir karma kodu döndürür |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | 'Ad' özelliğiyle aynı olan bu belirli biçimin adını döndürür |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Eşitlik üzerinde verilen iki WordProcessingFormats örneğini kontrol eder |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Belirtilen WordProcessingFormats örneğinin temel alınan alanından bir bayt değeri döndürür (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | eşitsizlik üzerinde verilen iki WordProcessingFormats örneğini kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 İkili Dosya Biçimi (DOC), Microsoft Word tarafından oluşturulan belgeleri veya ikili dosya biçimindeki diğer kelime işlem belgelerini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM) dosyaları, Microsoft Word 2007 veya daha yüksek sürümde oluşturulmuş ve makro çalıştırabilen belgelerdir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Açık XML WordProcessingML Makro İçermeyen Belge (DOCX), Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007'den Microsoft Office 2007'nin piyasaya sürülmesiyle kullanıma sunulan bu yeni Belge biçiminin yapısı, düz ikiliden XML ve ikili dosyaların birleşimine değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Şablonu, daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Açık XML WordprocessingML Makro Etkin Şablon (DOTM), Microsoft Word 2007 veya üstü ile oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Açık XML WordprocessingML Makro İçermeyen Şablon (DOTX), daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | ZIP paketi yerine düz bir XML dosyasında saklanan Office Açık XML WordprocessingML |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Açık Belge Biçimi Metin Belgesi (ODT) dosyaları, OpenDocument Metin Dosyası biçimini temel alan kelime işlemci uygulamalarıyla oluşturulan belge türleridir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Açık Belge Formatı Metin Belgesi Şablonu (OTT), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Zengin Metin Biçimi (RTF), uygulamalarda kullanılmak üzere biçimlendirilmiş metin ve grafikleri kodlama yöntemini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Biçimi — WordProcessingML veya WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Mevcut tüm WordProcessing formatları üzerinde sayısız olasılık sağlayan dahili bir sınıf döndürür |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | WordProcessingFormats type için 'foreach' olasılığını etkinleştiren IEnumerable genel arabirimini uygular |

### Notlar

MIME kodları şu kaynaklardan alınır: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Ayrıca bakınız

* interface [IDocumentFormat](../idocumentformat)
* ad alanı [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
