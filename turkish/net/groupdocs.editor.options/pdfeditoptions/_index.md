---
title: "PdfEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "PDF belgelerini düzenlemek için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 1050
url: /tr/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

PDF belgelerini düzenlemek için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Tüm seçeneklerin varsayılan değerlere ayarlandığı PdfEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Belirtilen sayfalama ile ve diğer tüm seçenekler varsayılan olarak ayarlanmış PdfEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür |

## Properties

| Name | Açıklama |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye (true) veya devre dışı bırakmaya (false) izin verir. Varsayılan olarak devre dışı (false) durumdadır. |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | İşlenecek sayfa aralığını ayarlamaya izin verir. Varsayılan olarak sabit düzen belgesinin tüm sayfaları işlenir. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Girdi sabit‑düzen belgesini sonuç HTML'ye dönüştürürken görüntülerin atlanıp atlanmayacağını gösteren bayrağı alır veya ayarlar. Varsayılan değer false - görüntüler korunur. |

### Ayrıca Bakınız

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
