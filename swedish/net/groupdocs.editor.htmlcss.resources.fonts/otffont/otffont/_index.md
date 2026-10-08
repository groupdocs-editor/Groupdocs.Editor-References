---
title: "OtfFont"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny OtfFont-klass från innehåll som representeras som en base64encoded sträng och med angivet namn."
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

Skapar en ny OtfFont-klass från innehåll, representerat som base64-kodad sträng, och med angivet namn

```csharp
public OtfFont(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på OTF-typsnittet. Får inte vara null, tom eller bara whitespace. |
| contentInBase64 | String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller bara whitespace. Om det inte är ett OTF-innehåll kastas ett undantag. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

Skapar en ny OtfFont-klass från innehåll, representerat som byte-ström, och med angivet namn

```csharp
public OtfFont(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på OTF-typsnittet. Får inte vara null, tom eller bara whitespace. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
