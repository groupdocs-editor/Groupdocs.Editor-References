---
title: "TtfFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen adla ve base64 kodlu dize olarak temsil edilen içerikten yeni bir TtfFont sınıfı oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/ttffont/
---
## TtfFont(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil edilen ve belirtilen adla yeni bir TtfFont sınıfı oluşturur

```csharp
public TtfFont(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | TTF yazı tipinin adı. Boş, null veya yalnızca boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. Boş, null veya yalnızca boşluk olamaz. TTF içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtfFont(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil edilen ve belirtilen adla yeni bir TtfFont sınıfı oluşturur

```csharp
public TtfFont(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | TTF yazı tipinin adı. Boş, null veya yalnızca boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Belirtilen ikili içerik geçerli bir TTF yazı tipi olarak doğru şekilde yorumlanamadığında fırlatılır |

### Ayrıca Bakınız

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
