---
title: "Locale"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "WordProcessing belgesi için oluşturulurken uygulanacak varsayılan yerel dil ayarını geçersiz kılmaya izin verir. Belirtilmediğinde, varsayılan değer MS Word veya diğer programlar, kendi ayarları veya diğer faktörlere göre belgenin yerel ayarını algılar veya seçer."
type: docs
weight: 40
url: /tr/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

WordProcessing belgesi oluşturulurken uygulanacak varsayılan yerel ayarı (dili) geçersiz kılmanıza olanak tanır. Belirtilmezse (varsayılan değer), MS Word (veya başka bir program) belge yerel ayarını kendi ayarları veya diğer faktörlere göre algılar (veya seçer).

```csharp
public CultureInfo Locale { get; set; }
```

### Açıklamalar

Bu seçenek, belirtilen yereli belgedeki tüm metne zorla uygular. Belge farklı dillerde yazılmış farklı metin bölümleri içeriyorsa kullanmayın.

### Ayrıca Bakınız

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
