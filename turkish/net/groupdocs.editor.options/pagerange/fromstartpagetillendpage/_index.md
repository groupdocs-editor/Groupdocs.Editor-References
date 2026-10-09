---
title: "FromStartPageTillEndPage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen sayfa numarasından dahil olarak başlayıp, belirtilen sayfa numarasına dışarıdan dahil olmadan devam eden bir sayfa aralığı oluşturur."
type: docs
weight: 40
url: /tr/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Belirtilen sayfa numarasından (dahil) başlayan ve belirtilen sayfa numarasına (hariç) kadar devam eden bir sayfa aralığı oluşturur

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| startPageNumber | UInt16 | Sayfa aralığının başladığı sayfa numarası, dahil. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalıdır. |
| endPageNumber | UInt16 | Sayfa aralığının devam ettiği sayfa numarası, dışarıdan dahil olmadan. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalı ve ayrıca *startPageNumber*'dan da büyük olmalıdır. |

### Ayrıca Bakınız

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
