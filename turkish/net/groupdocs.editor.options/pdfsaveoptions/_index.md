---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "PDF Taşınabilir Belge Formatı belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir."
type: docs
weight: 1070
url: /tr/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

PDF (Portable Document Format) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | Çıktı belgeleri için PDF standart uyumluluk seviyesini belirtir. Varsayılan değer PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | Orijinal belgede kullanılan yazı tipi kaynaklarını sonuç PDF belgesine gömmekten sorumludur. Varsayılan olarak hiçbir yazı tipi gömülmez (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | HTML'den belge oluşturma sırasında bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken bellek tüketimini önemli ölçüde azaltabilir, ancak kaydetme süresini yavaşlatır. Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | Oluşturulan PDF belgesine kullanıcı şifresi olarak uygulanacak şifre, açmak için gereklidir. NULL veya boş ise belgeye şifre uygulanmaz. Aksi takdirde belge RC4 (128 bit anahtar uzunluğu) ile şifrelenir. Varsayılan olarak NULL — şifre uygulanmaz. |

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
