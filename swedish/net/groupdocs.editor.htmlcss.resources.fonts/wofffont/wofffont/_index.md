---
title: "WoffFont"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny WoffFont-klass från innehåll som representeras som en base64encoded sträng och med angivet namn."
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/wofffont/
---
## WoffFont(string, string) {#constructor_1}

Skapar en ny WoffFont-klass från innehåll, representerat som base64-kodad sträng, och med angivet namn

```csharp
public WoffFont(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på WOFF-typsnittet. Får inte vara null, tom eller bara whitespace. |
| contentInBase64 | String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller bara whitespace. Om det inte är ett WOFF-innehåll kastas ett undantag. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## WoffFont(string, Stream) {#constructor}

Skapar en ny WoffFont-klass från innehåll, representerat som byte-ström, och med angivet namn

```csharp
public WoffFont(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på WOFF-typsnittet. Får inte vara null, tom eller bara whitespace. |
| binaryContent | Stream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om detta objekt kommer att avyttras, kommer även denna ström att avyttras. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
