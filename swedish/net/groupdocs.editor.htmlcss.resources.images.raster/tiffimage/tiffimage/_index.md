---
title: "TiffImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny TiffImage‑instans från innehåll som representeras som en base64‑kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/tiffimage/
---
## TiffImage(string, string) {#constructor_1}

Skapar en ny TiffImage-instans från innehåll, representerat som base64‑kodad sträng, och med angivet namn

```csharp
public TiffImage(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på TIFF-bilden. Får inte vara null, tom eller bestå av bara blanksteg. |
| contentInBase64 | String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bestå av bara blanksteg. Om det inte är TIFF‑innehåll kastas ett undantag. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [TiffImage](../../tiffimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## TiffImage(string, Stream) {#constructor}

Skapar en ny GifImage-instans från innehåll, representerat som byte‑ström, och med angivet namn

```csharp
public TiffImage(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på GIF-bilden. Får inte vara null, tom eller bestå av bara blanksteg. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [TiffImage](../../tiffimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
