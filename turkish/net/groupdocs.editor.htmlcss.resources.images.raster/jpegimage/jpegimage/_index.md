---
title: "JpegImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Base64 kodlu dize olarak temsil edilen içerikten ve belirtilen adla yeni bir JpegImage örneği oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.images.raster/jpegimage/jpegimage/
---
## JpegImage(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir JpegImage örneği oluşturur

```csharp
public JpegImage(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | JPEG görüntüsünün adı. null, boş veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. null, boş veya sadece boşluk olamaz. JPEG içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [JpegImage](../../jpegimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## JpegImage(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir JpegImage örneği oluşturur

```csharp
public JpegImage(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | JPEG görüntüsünün adı. null, boş veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [JpegImage](../../jpegimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
