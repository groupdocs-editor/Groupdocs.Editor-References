---
title: "GeneratePreview"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Seçilen çalışma sayfasının bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür"
type: docs
weight: 60
url: /tr/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

Seçilen çalışma sayfasının bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| worksheetIndex | Int32 | İstenen çalışma sayfasının 0 tabanlı indeksi. 0'dan küçük olamaz, bu elektronik tabloda bulunan çalışma sayfası sayısını aşamaz. |

### Dönüş Değeri

SVG görüntüsü, null olmayan [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) sınıfının bir örneği olarak.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Belirtilen *worksheetIndex* 0'dan küçük veya bu elektronik tabloda bulunan çalışma sayfası sayısından büyüktür. |

### Ayrıca Bakınız

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
