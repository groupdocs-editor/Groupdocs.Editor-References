---
title: "WmfImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny WmfImage‑instans från innehåll representerat som en base64‑kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Skapar en ny WmfImage-instans från innehåll, representerat som base64‑kodad sträng, och med angivet namn

```csharp
public WmfImage(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på WMF‑bilden. Får inte vara null, tom eller bara blanksteg. |
| contentInBase64 | String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bara blanksteg. Om det inte är WMF‑innehåll kastas ett undantag. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Skapar en ny WmfImage-instans från innehåll, representerat som byte‑ström, och med angivet namn

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på WMF‑bilden. Får inte vara null, tom eller bara blanksteg. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
