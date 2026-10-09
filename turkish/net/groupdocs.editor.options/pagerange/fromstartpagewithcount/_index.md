---
title: "FromStartPageWithCount"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen sayfa numarasından başlayan ve belirtilen sayıda sayfa içeren ya da sonuna kadar sınırsız sayfa sayısına sahip bir sayfa aralığı oluşturur."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

Belirtilen sayfa numarasından başlayan ve belirtilen sayıda sayfa içeren veya sınırsız sayfa sayısına (sona kadar) sahip bir sayfa aralığı oluşturur

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| startPageNumber | UInt16 | Sayfa aralığının başladığı sayfa numarası, dahil. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalıdır. |
| pageCount | UInt16 | Sayfa sayısı, sıfırdan büyük olmalıdır. Sıfır ise - bu, belgenin sonuna kadar tüm sayfalar anlamına gelir. |

### Dönüş Değeri

Yeni PageRange örneği

### Ayrıca Bakınız

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
