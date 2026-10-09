---
title: "EmfImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Base64 kodlu dize olarak temsil edilen içerikten ve belirtilen adla yeni bir EmfImage örneği oluşturur."
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/emfimage/
---
## EmfImage(string, string) {#constructor_1}

Belirtilen adla ve base64 kodlu dize olarak temsil edilen içerikten yeni bir EmfImage örneği oluşturur

```csharp
public EmfImage(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | EMF görüntüsünün adı. null, boş veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. null, boş veya sadece boşluk olamaz. EMF içeriği değilse, bir istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## EmfImage(string, Stream) {#constructor}

Belirtilen adla ve bayt akışı olarak temsil edilen içerikten yeni bir EmfImage örneği oluşturur

```csharp
public EmfImage(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | EMF görüntüsünün adı. null, boş veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
