---
title: FixedLayoutFormats
second_title: .NET API Başvurusu için GroupDocs.Editor
description: PDF ve XPS buna raster görüntüler dahil değildir dahil olmak üzere tüm sabit düzen sabit sayfa olarak da bilinir biçimlerini kapsüller
type: docs
weight: 80
url: /tr/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

PDF ve XPS (buna raster görüntüler dahil değildir) dahil olmak üzere tüm sabit düzen ("sabit sayfa" olarak da bilinir) biçimlerini kapsüller

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Bu sabit düzen biçiminin bir uzantısını (baştaki nokta karakteri olmadan) küçük harfle döndürür |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Bu biçim için bir MIME kodu döndürür |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Bu sabit düzen formatının resmi bir tam adını döndürür |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | örneğini döndürür[`FixedLayoutFormats`](../fixedlayoutformats) yapı, belirtilen dosya adı uzantısıyla ilişkilendirilir veya uzantı düzgün bir şekilde ayrıştırılamazsa bir istisna atar |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Bu örneğin, belirtilen diğer FixedLayoutFormats örneğine eşit olup olmadığını belirler |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Bu örneğin belirtilen diğer IDocumentFormat örneğine eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Bu örneğin, muhtemelen kutulu FixedLayoutFormats olan belirtilen diğer nesneye eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Bu örnek için sabit olan bir karma kodu döndürür |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | 'Ad' özelliğiyle aynı olan bu belirli biçimin adını döndürür |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | eşitlik üzerinde verilen iki FixedLayoutFormats örneğini kontrol eder |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Belirtilen FixedLayoutFormats örneğinin temel alınan alanından bir bayt değeri döndürür (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | eşitsizlik üzerinde verilen iki FixedLayoutFormats örneğini kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Taşınabilir Belge Biçimi (PDF), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. Bu dosya formatının amacı, uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir formatta belgelerin ve diğer referans materyallerinin temsili için bir standart getirmekti. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | XPS dosyası, Microsoft tarafından oluşturulan XML Kağıt Spesifikasyonlarına dayalı sayfa düzeni dosyalarını temsil eder. EMF dosya biçiminin yerine geliştirilmiştir ve PDF dosya biçimine benzer, ancak düzen, görünüm ve bir belgenin yazdırma bilgilerinde XML kullanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Varolan tüm sabit mizanpaj biçimleri üzerinde sayısız olasılık sağlayan dahili bir sınıf döndürür |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | FixedLayoutFormats type için 'foreach' olasılığını etkinleştiren IEnumerable genel arabirimini uygular |

### Notlar

Çeşitli belge görüntüleme veya yayınlama uygulamaları, kullanıcıların belirli biçimlerdeki belgeleri açmasına (Adobe Acrobat, XPS Viewer) ve bazen düzenlemesine (Adobe InDesign) olanak tanır. Bu uygulamalar tipik olarak "sabit sayfa" olarak adlandırılan formatta belgeler üretir. Böyle bir belge formatı, bir belgenin içeriğinin her sayfada nereye yerleştirildiğini tam olarak tanımlar. Dahili olarak, PDF veya XPS formatı, sayfadaki içeriğin düzenini belirleyen çizim talimatlarının yanı sıra her sayfanın bir açıklamasını içerir. Bu, içeriğin raster veya vektör biçiminde nerede gösterildiğini açıklayan görüntü biçimlerine benzer.

### Ayrıca bakınız

* interface [IDocumentFormat](../idocumentformat)
* ad alanı [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
