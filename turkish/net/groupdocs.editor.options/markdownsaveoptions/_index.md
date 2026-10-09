---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Markdown belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 1000
url: /tr/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Görüntülerin çıktı dosyasına Base64 formatında kaydedilip kaydedilmeyeceğini belirtir. Varsayılan `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Bir belgenin Markdown formatına dışa aktarılması sırasında görüntülerin kaydedileceği fiziksel klasörü belirtir. Varsayılan değer null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | HTML'den belge oluşturulurken bellek optimizasyon mekanizmalarını etkinleştirir; bu, bellek kullanımını azaltma karşılığında performansı düşürür. Bu seçeneği `true` olarak ayarlamak, büyük belgeler oluşturulurken bellek tüketimini önemli ölçüde azaltabilir, ancak kaydetme süresini yavaşlatır. Varsayılan `false` (daha iyi performans için bellek optimizasyonu devre dışıdır). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow, Markdown formatına dışa aktarılırken tablolar içindeki içeriğin nasıl hizalanacağını belirtir. Varsayılan değer Auto. |

### Açıklamalar

MarkdownSaveOptions sınıfı, düzenlenmiş belge içeriğini içeren bir EditableDocument sınıfı örneği mevcut olduğunda ve bu içeriğin yeni bir Markdown formatı belgeye kaydedilmesi gerektiğinde kullanıcı tarafından uygulanmalıdır.

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
