---
title: "PngImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Base64 kodlu dize olarak temsil edilen içerikten ve belirtilen adla yeni PngImage örneği oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/pngimage/
---
## PngImage(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir PngImage örneği oluşturur

```csharp
public PngImage(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | PNG görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. PNG içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## PngImage(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir PngImage örneği oluşturur

```csharp
public PngImage(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | PNG görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
