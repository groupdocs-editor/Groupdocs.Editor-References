---
title: PresentationFormats
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Tüm Sunum biçimlerini kapsüller. Şu biçimleri içerir Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Sunum biçimleri hakkında daha fazla bilgi edininburadahttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /tr/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Tüm Sunum biçimlerini kapsüller. Şu biçimleri içerir: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Sunum biçimleri hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Bu Sunum biçiminin bir uzantısını (baştaki nokta karakteri olmadan) küçük harfle döndürür |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Bu biçim için bir MIME kodu döndürür |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Bu Sunum formatının resmi bir tam adını döndürür |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | örneğini döndürür[`PresentationFormats`](../presentationformats)yapı, belirtilen dosya adı uzantısıyla ilişkilendirilir veya uzantı düzgün bir şekilde ayrıştırılamazsa bir istisna atar |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Bu örneğin belirtilen diğer IDocumentFormat örneğine eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Bu örneğin, muhtemelen kutulu PresentationFormats olan belirtilen diğer nesneye eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Bu örneğin, belirtilen diğer PresentationFormats örneğine eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Bu örnek için sabit olan bir karma kodu döndürür |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Verilen iki PresentationFormats örneğini eşitlik üzerinde kontrol eder |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | eşitsizlik üzerinde verilen iki PresentationFormats örneğini kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP) dosyası, OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosyası formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP) dosyası, uygulamalar tarafından OASIS OpenDocument standart formatında oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Sunu Şablonu (POT) dosyası, PowerPoint 97-2003 sürümleri tarafından oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM), Makroları destekleyen dosyalardır. POTM dosyaları, PowerPoint 2007 veya üzeri sürümlerle oluşturulur ve daha fazla sunum dosyası oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Açık XML SunumuML Makro İçermeyen Şablon (POTX) dosyası, Microsoft PowerPoint 2007 ve sonraki sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 Slayt Gösterisi (PPS) dosyaları, Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosyası okuma ve oluşturma, Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Açık XML PresentationML Makro Etkin Slayt Gösterisi (PPSM) dosyaları, Microsoft PowerPoint 2007 veya üstü ile oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Makro İçermeyen Slayt Gösterisi (PPSX) dosyası, Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üzeri kullanılarak oluşturulmuştur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint Sunumu (.ppt), SlideShow olarak görüntülemek için bir slayt koleksiyonundan oluşan PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 Sunumu (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan Microsoft Office Açık XML PresentationML Makro Etkin Belge (PPTM) dosyaları. PPTX dosyalarına benzerler, tek fark, lateral dosyaların makro içerebilmelerine rağmen makroları çalıştıramamasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Açık XML Sunumu (.pptx), popüler Microsoft PowerPoint uygulamasıyla oluşturulmuş bir sunum dosyasıdır. İkili olan sunum dosyası biçimi PPT'nin önceki sürümünün aksine, PPTX biçimi Microsoft PowerPoint açık XML sunum dosyası biçimini temel alır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Mevcut tüm Sunum formatları üzerinde sayısız olasılık sağlayan dahili bir sınıf döndürür |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | PresentationFormats type için 'foreach' olasılığını etkinleştiren IEnumerable genel arabirimini uygular |

### Ayrıca bakınız

* interface [IDocumentFormat](../idocumentformat)
* ad alanı [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
