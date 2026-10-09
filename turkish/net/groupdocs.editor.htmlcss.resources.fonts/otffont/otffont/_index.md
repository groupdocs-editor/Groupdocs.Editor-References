---
title: "OtfFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni OtfFont sınıfı oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir OtfFont sınıfı oluşturur

```csharp
public OtfFont(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | OTF yazı tipinin adı. Boş, null veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. Eğer OTF içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir OtfFont sınıfı oluşturur

```csharp
public OtfFont(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | OTF yazı tipinin adı. Boş, null veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
