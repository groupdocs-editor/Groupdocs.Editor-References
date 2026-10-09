---
title: "GeneratePreview"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Seçilen sayfanın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür"
type: docs
weight: 60
url: /tr/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

Seçilen sayfanın bir SVG görüntüsü şeklinde önizlemesini oluşturur ve döndürür

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| pageIndex | Int32 | İstenen sayfanın 0 tabanlı indeksi. 0'dan küçük olamaz, bu WordProcessing belgesindeki sayfa sayısını aşamaz. |

### Dönüş Değeri

SVG görüntüsü, null olmayan [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) sınıfının bir örneği olarak.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Belirtilen *pageIndex* 0'dan küçük veya bu WordProcessing belgesindeki sayfa sayısından büyüktür. |

### Ayrıca Bakınız

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
