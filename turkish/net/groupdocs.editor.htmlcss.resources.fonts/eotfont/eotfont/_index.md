---
title: "EotFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen adla ve base64 kodlu dize olarak temsil edilen içerikten yeni bir EotFont sınıfı oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

İçeriği base64 kodlu dize olarak temsil edilen ve belirtilen adla yeni bir EotFont sınıfı oluşturur

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| eotName | String | EOT yazı tipinin adı. Boş, null veya yalnızca boşluk olamaz. |
| eotContentInBase64 | String | İçerik base64 kodlu dize olarak. Boş, null veya yalnızca boşluk olamaz. EOT içeriği değilse, istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil edilen ve belirtilen adla yeni bir EotFont sınıfı oluşturur

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| eotName | String | EOT yazı tipinin adı. Boş, null veya yalnızca boşluk olamaz. |
| eotBinaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
