---
title: "SvgImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Yeni bir SvgImage örneğini, normal bir dize olarak temsil edilen içerikten ve belirtilen adla oluşturur"
type: docs
weight: 10
url: /tr/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

İçeriği normal bir dize olarak temsil eden ve belirtilen adla yeni bir SvgImage örneği oluşturur

```csharp
public SvgImage(string name, string content)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | SVG görüntüsünün adı. Boş, null veya yalnız boşluk olamaz. |
| içerik | String | SVG görüntüsünün geçerli XML uyumlu içeriğini içeren normal bir dize olarak içerik. Boş, null veya yalnız boşluk olamaz. SVG içeriği değilse, bir istisna fırlatılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Bazı parametreler geçersiz |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* argümanı geçersiz SVG içeriği içeriyor |

### Ayrıca Bakınız

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir SvgImage örneği oluşturur

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| ad | String | SVG görüntüsünün adı. Boş, null veya yalnız boşluk olamaz. |
| binaryContent | Stream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek imha edilirse, bu akış da imha edilecektir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ayrıca Bakınız

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
