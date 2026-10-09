---
title: "LocaleBi"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "WordProcessing belgesi için RTL (sağdan sola) metinlerde uygulanacak yerel dil ayarını geçersiz kılmaya izin verir. Belirtilmediğinde, varsayılan değer MS Word veya diğer programlar, kendi ayarları veya diğer faktörlere göre belgenin RTL yerel ayarını algılar veya seçer."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

WordProcessing belgesinin RTL (sağdan sola) metinleri için yerel ayarını (dil) geçersiz kılmanıza olanak tanır; bu ayar oluşturma sırasında uygulanır. Belirtilmezse (varsayılan değer), MS Word (veya başka bir program) belge RTL yerel ayarını kendi ayarları veya diğer faktörlere göre algılar (veya seçer).

```csharp
public CultureInfo LocaleBi { get; set; }
```

### Açıklamalar

Bu seçenek, belirtilen yereli belgedeki tüm RTL metne zorla uygular. Belge farklı dillerde yazılmış farklı metin bölümleri içeriyorsa kullanmayın.

### Ayrıca Bakınız

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
