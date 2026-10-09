---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "XPS XML Paper Specifications belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 1300
url: /tr/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

XPS (XML Paper Specifications) belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye olanak tanır

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | HTML'den belge oluşturma sırasında bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken bellek tüketimini önemli ölçüde azaltabilir, ancak kaydetme süresini yavaşlatır. Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır). |

### Açıklamalar

XPS dosyası, Microsoft tarafından oluşturulan XML Paper Specifications tabanlı sayfa düzeni dosyalarını temsil eder. EMF dosya formatının yerine geçecek şekilde geliştirilmiş olup PDF dosya formatına benzer, ancak bir belgenin düzen, görünüm ve baskı bilgileri için XML kullanır.

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
