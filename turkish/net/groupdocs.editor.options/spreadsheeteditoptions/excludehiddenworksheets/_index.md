---
title: "ExcludeHiddenWorksheets"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Giriş Spreadsheet belgesindeki gizli çalışma sayfalarını dışarıda bırakmaya izin verir, böylece tamamen yok sayılırlar. Varsayılan değer false; gizli çalışma sayfaları mevcut olup normal işlenir."
type: docs
weight: 20
url: /tr/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Girdi Elektronik Tablo belgesindeki gizli çalışma sayfalarını dışlamaya izin verir, böylece tamamen göz ardı edilirler. Varsayılan olarak yanlıştır - gizli çalışma sayfaları mevcuttur ve normal şekilde işlenir.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Açıklamalar

XLSX gibi bazı ikili Spreadsheet formatları gizli çalışma sayfaları (sekme) kavramını destekler. Bu formatta bir belge birden fazla çalışma sayfasına sahipse, ek gizli çalışma sayfaları içerebilir. Varsayılan olarak bu gizli çalışma sayfaları işleme açıktır, ancak bu seçenekle onları yok sayabilirsiniz; yani bu gizli çalışma sayfaları mevcut değildir ve varmış gibi davranılmaz. Bu seçenek etkinleştirildiğinde, '[`WorksheetIndex`](../worksheetindex)' özelliği ile gizli çalışma sayfası seçemezsiniz.

### Ayrıca Bakınız

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
