---
title: SvgImage
second_title: GroupDocs.Editor för .NET API-referens
description: Skapar ny SvgImageinstans från innehåll representerad som en vanlig sträng och med specificerat namn
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Skapar ny SvgImage-instans från innehåll, representerad som en vanlig sträng och med specificerat namn

```csharp
public SvgImage(string name, string content)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | SVG-bildens namn. Kan inte vara null, tom eller blanksteg. |
| content | String | Innehåll som en vanlig sträng, som innehåller ett giltigt XML-kompatibelt innehåll i SVG-bilden. Kan inte vara null, tomt eller blanksteg. Om det inte är ett SVG-innehåll kommer undantag att kastas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Vissa parametrar är ogiltiga |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* argumentet innehåller ogiltigt SVG-innehåll |

### Se även

* class [SvgImage](../../svgimage)
* namnutrymme [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../svgimage)
* hopsättning [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Skapar ny SvgImage-instans från innehåll, representerad som byteström och med specificerat namn

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | SVG-bildens namn. Kan inte vara null, tom eller blanksteg. |
| binaryContent | Stream | Innehåll som byteström. Läsningen börjar från den ursprungliga positionen. Kan inte vara null. Bör vara läsbar och sökbar. Om den här instansen kommer att kasseras kommer även denna ström att kasseras. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [SvgImage](../../svgimage)
* namnutrymme [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../svgimage)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->