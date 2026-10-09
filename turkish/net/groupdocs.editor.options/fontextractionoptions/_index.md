---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Yazı tipi çıkarma seçenekleri, hangi yazı tiplerinin çıkarılacağını ve nereden alınacağını kontrol eder"
type: docs
weight: 890
url: /tr/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

Yazı tipi çıkarma seçenekleri, hangi yazı tiplerinin çıkarılacağını ve nereden alınacağını kontrol eder

```csharp
public enum FontExtractionOptions
```

### Değerler

| Name | Değer | Açıklama |
| --- | --- | --- |
| NotExtract | `0` | Belge ya da sistemden hiçbir yazı tipi kaynağı çıkarmaz. Varsayılan değer. |
| ExtractAllEmbedded | `1` | Giriş Word belgesine gömülü olan tüm yazı tipi kaynaklarını, özelleştirilmiş ya da sistem olsun fark etmeksizin çıkarır. |
| ExtractEmbeddedWithoutSystem | `2` | Yalnızca özelleştirilmiş (sistem olmayan) gömülü yazı tipi kaynaklarını çıkarır. |
| ExtractAll | `3` | Giriş WordProcessing belgesinde kullanılan tüm yazı tiplerini, sistem yazı tipleri dahil, çıkarmaya çalışır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
