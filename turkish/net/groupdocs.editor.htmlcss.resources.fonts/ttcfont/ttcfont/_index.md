---
title: "TtcFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Base64 kodlu dize olarak temsil edilen içerikten ve belirtilen adla yeni bir TtcFont sınıfı oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir TtcFont sınıfı oluşturur

```csharp
public TtcFont(string name, string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | TTC yazı tipinin adı. null, boş veya sadece boşluk olamaz. |
| contentInBase64 | String | İçerik base64 kodlu dize olarak. null, boş veya sadece boşluk olamaz. TTC içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Giriş dizelerinden herhangi biri `null`, boş veya yalnızca boşluk ise |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *contentInBase64* argümanındaki içerik geçerli bir TTC yazı tipi olarak tanınamıyor |

### Ayrıca Bakınız

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir TtcFont sınıfı oluşturur

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | TTC yazı tipinin adı. null, boş veya sadece boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *name* argümanı `null`, boş veya yalnızca boşluk |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Belirtilen ikili içerik geçerli bir TTF yazı tipi olarak doğru şekilde yorumlanamadığında fırlatılır |

### Ayrıca Bakınız

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
