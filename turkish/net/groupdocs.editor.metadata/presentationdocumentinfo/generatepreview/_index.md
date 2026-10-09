---
title: "GeneratePreview"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Seçilen slaytın önizlemesini SVG görüntüsü biçiminde oluşturur ve döndürür"
type: docs
weight: 50
url: /tr/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Seçilen slaytın önizlemesini SVG görüntüsü biçiminde oluşturur ve döndürür

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| slideIndex | Int32 | İstenen slaytın 0 tabanlı indeksi. 0'dan küçük olamaz, bu sunumdaki slayt sayısını aşamaz. |

### Dönüş Değeri

SVG görüntüsü, null olmayan [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) sınıfının bir örneği olarak.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | Belirtilen *slideIndex* 0'dan küçük veya bu sunumdaki slayt sayısından büyüktür. |

### Ayrıca Bakınız

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
