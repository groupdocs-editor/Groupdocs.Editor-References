---
title: "IconImage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny IconImage-instans från innehåll representerat som en base64-kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/iconimage/
---
## IconImage(string, string) {#constructor_1}

Skapar en ny IconImage-instans från innehåll, representerat som en base64-kodad sträng, och med angivet namn

```csharp
public IconImage(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på ICON-bilden. Får inte vara null, tom eller bestå av bara blanksteg. |
| contentInBase64 | String | Innehåll som en base64-kodad sträng. Får inte vara null, tom eller bestå av bara blanksteg. Om det inte är ICON-innehåll kommer ett undantag att kastas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## IconImage(string, Stream) {#constructor}

Skapar en ny IconImage-instans från innehåll, representerat som en byte-ström, och med angivet namn

```csharp
public IconImage(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på ICON-bilden. Får inte vara null, tom eller bestå av bara blanksteg. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
