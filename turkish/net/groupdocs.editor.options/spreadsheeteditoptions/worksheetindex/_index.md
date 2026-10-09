---
title: "WorksheetIndex"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "HTML'ye dönüştürülmesi gereken giriş Spreadsheet belgesinin çalışma sayfası sekmesinin 0 tabanlı indeksini belirtmeye izin verir; açıklamalara bakınız."
type: docs
weight: 50
url: /tr/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

Giriş Spreadsheet belgesinin HTML'ye dönüştürülmesi gereken çalışma sayfasının (sekme) 0 tabanlı indeksini belirtmeye izin verir (notlara bakınız).

```csharp
public int WorksheetIndex { get; set; }
```

### Açıklamalar

Çoğu Spreadsheet belgesi sekme kavramını destekler, yani çoklu sekmeli olabilir. Öte yandan HTML formatı böyle bir yapıyı desteklemez. Bu nedenle GroupDocs.Editor, giriş belgesinin yalnızca tek bir belirli sekmesini HTML'ye dönüştürebilir ve bu seçenek onu belirtmenizi sağlar. Sekme indeksi 0 tabanlıdır, negatif değerler yasaktır. Belirtilen indeks tüm sekme sayısını aşarsa bir istisna fırlatılır. Giriş Spreadsheet belgesi yalnızca bir sekme içeriyorsa bu seçenek yok sayılır. Varsayılan değer 0 (ilk sekme).

### Ayrıca Bakınız

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
