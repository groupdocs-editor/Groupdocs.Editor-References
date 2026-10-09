---
title: "ExtractOnlyUsedFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belgenin metin içeriğinde kullanılan yalnızca yazı tipi kaynaklarını çıkarıp çıkarmayacağını gösteren bir değeri alır veya ayarlar."
type: docs
weight: 40
url: /tr/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

Belgenin metin içeriğinde kullanılan yalnızca yazı tipi kaynaklarını çıkarıp çıkarmayacağını gösteren bir değeri alır veya ayarlar.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` eğer yalnızca belgede metin içeriğinde kullanılan yazı tipi kaynaklarını çıkarmak gerekiyorsa; aksi takdirde `false`. Varsayılan değer `false`.

### Açıklamalar

WordProcessing belgesinde kullanılan tüm yazı tipleri %100 doğrudan (bazı metne uygulanarak) kullanılmaz. Belge içinde bir yazı tipine referans verilmiş ve hatta gömülü olabilir, ancak hiçbir metin parçasına uygulanmamış bir durum olabilir. Örneğin, bir yazı tipi bir stile eklenmiş olabilir, ancak bu stil metnin hiçbir bölümüne uygulanmamış olabilir. Bu seçenek bu tür durumların nasıl işleneceğini kontrol eder.

### Ayrıca Bakınız

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
