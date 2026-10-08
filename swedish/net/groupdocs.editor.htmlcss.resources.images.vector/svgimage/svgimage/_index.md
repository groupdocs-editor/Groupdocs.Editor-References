---
title: "SvgImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny SvgImage-instans från innehåll representerat som en vanlig sträng och med angivet namn."
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Skapar en ny SvgImage-instans från innehåll, representerat som vanlig sträng, och med angivet namn

```csharp
public SvgImage(string name, string content)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på SVG-bilden. Får inte vara null, tom eller bestå av bara mellanslag. |
| innehåll | String | Innehåll som en vanlig sträng, som innehåller ett giltigt XML-kompatibelt innehåll för en SVG-bild. Får inte vara null, tom eller bestå av bara mellanslag. Om det inte är SVG-innehåll kommer ett undantag att kastas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Vissa parametrar är ogiltiga. |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content*-argumentet innehåller ogiltigt SVG-innehåll |

### Se även

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Skapar en ny SvgImage-instans från innehåll, representerat som byte‑ström, och med angivet namn

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på SVG-bilden. Får inte vara null, tom eller bestå av bara mellanslag. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
