---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Yazı tipi gömme seçenekleri, hangi yazı tipi kaynaklarının çıktı WordProcessing veya PDF belgesine gömülmesi gerektiğini kontrol eder"
type: docs
weight: 880
url: /tr/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Yazı tipi gömme seçenekleri, hangi yazı tipi kaynaklarının çıktı WordProcessing veya PDF belgesine gömülmesi gerektiğini kontrol eder

```csharp
public enum FontEmbeddingOptions
```

### Değerler

| Name | Değer | Açıklama |
| --- | --- | --- |
| NotEmbed | `0` | EditableDocument'ten ya da sistemden hiçbir yazı tipi kaynağı gömülmez. Varsayılan değer. |
| EmbedAll | `1` | Giriş EditableDocument'ten belge içeriğini analiz eder, kullanılan tüm yazı tiplerini bulur ve bunları çıktı WordProcessing ya da PDF belgesine gömer. İlk olarak GroupDocs.Editor, EditableDocument içindeki yazı tipi kaynaklarından yazı tiplerini alır. Eğer yetersiz ya da eksikse, GroupDocs.Editor işletim sisteminden (OS) yazı tiplerini alır. |
| EmbedWithoutSystem | `2` | EmbedAll ile aynı, ancak işletim sistemi tarafından sistem yazı tipleri olarak kabul edilen yazı tiplerini hariç tutar. |

### Açıklamalar

Yazı tipi gömme seçenekleri belge kaydedilirken (araç EditableDocument'ten çıktı WordProcessing ya da PDF formatına) uygulanır, bu enum WordProcessingSaveOptions ve PdfSaveOptions içinde bir özellik olarak bulunur ve oradan kullanılmalıdır.

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
