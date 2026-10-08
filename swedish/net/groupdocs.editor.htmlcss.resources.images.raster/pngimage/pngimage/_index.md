---
title: "PngImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny PngImage-instans från innehåll representerat som en base64-kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/pngimage/
---
## PngImage(string, string) {#constructor_1}

Skapar en ny PngImage-instans från innehåll, representerat som base64‑kodad sträng, och med angivet namn

```csharp
public PngImage(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på PNG-bilden. Får inte vara null, tom eller bestå av endast blanksteg. |
| contentInBase64 | String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller bestå av endast blanksteg. Om det inte är PNG-innehåll kommer ett undantag att kastas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## PngImage(string, Stream) {#constructor}

Skapar en ny PngImage-instans från innehåll, representerat som byte‑ström, och med angivet namn

```csharp
public PngImage(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på PNG-bilden. Får inte vara null, tom eller bestå av endast blanksteg. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
