---
title: "PageRange"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Açık veya kapalı sınırları olabilen bir sayfa aralığını kapsar. Varsayılan olarak tamamen açıktır ve mevcut tüm sayfaları içerir. Sayfa numaralandırması 0'dan değil 1'den başlar."
type: docs
weight: 1030
url: /tr/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

Açık veya kapalı sınırları olabilen bir sayfa aralığını kapsar. Varsayılan olarak tamamen açıktır - mevcut tüm sayfaları içerir. Sayfa numaralandırması 0'dan değil, 1'den başlar.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | Aralık içindeki sayfa sayısı. 0 ise, sayfa aralığı belgenin sonuna kadar, kaç sayfa olursa olsun yayılır. |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | Bu sayfa aralığının devam ettiği ve yalnızca bu sayfada sona erdiği dışlayıcı son sayfa numarası. 0 ise, sayfa aralığı belgenin sonuna kadar yayılır. |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | Bu örneğin varsayılan "tamamen açık" bir sayfa aralığını temsil edip etmediğini gösterir; yani belgenin tüm sayfalarını temsil eder (true) veya temsil etmez (false). |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | Bu sayfa aralığının başladığı kapsayıcı başlangıç sayfa numarası. 1 ise, sayfa aralığı belgenin ilk sayfasından başlar. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | İlk sayfadan başlayan ve belirtilen sayıda sayfa içeren bir sayfa aralığı oluşturur |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | Belirtilen sayfa numarasından başlayan ve belgenin sonuna kadar devam eden bir sayfa aralığı oluşturur |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | Belirtilen sayfa numarasından (dahil) başlayan ve belirtilen sayfa numarasına (hariç) kadar devam eden bir sayfa aralığı oluşturur |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | Belirtilen sayfa numarasından başlayan ve belirtilen sayıda sayfa içeren veya sınırsız sayfa sayısına (sona kadar) sahip bir sayfa aralığı oluşturur |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | Bu PageRange örneğinin belirtilenle eşit olup olmadığını algılar |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | Bir belgenin mevcut tüm sayfalarını temsil eder. Varsayılan değer. |

### Açıklamalar

Belirli bir belgeye bağlı olmayan ve herhangi bir belge için sayfa aralığını temsil edebilen, sayfa aralığını kapsayan değiştirilemez bir yapı.

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
