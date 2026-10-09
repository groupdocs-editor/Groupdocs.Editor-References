---
title: "GifImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Base64 kodlu dize olarak temsil edilen içerikten ve belirtilen adla yeni GifImage örneği oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.images.raster/gifimage/gifimage/
---
## GifImage(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir GifImage örneği oluşturur

```csharp
public GifImage(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | GIF görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. GIF içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## GifImage(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir GifImage örneği oluşturur

```csharp
public GifImage(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | GIF görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
