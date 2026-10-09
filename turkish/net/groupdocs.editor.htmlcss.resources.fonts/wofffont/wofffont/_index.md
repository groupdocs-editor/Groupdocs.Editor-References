---
title: "WoffFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni WoffFont sınıfı oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/wofffont/
---
## WoffFont(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir WoffFont sınıfı oluşturur

```csharp
public WoffFont(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | WOFF yazı tipinin adı. Boş, null veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. Eğer WOFF içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## WoffFont(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir WoffFont sınıfı oluşturur

```csharp
public WoffFont(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | WOFF yazı tipinin adı. Boş, null veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Boş olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek iptal edilirse, bu akış da iptal edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
