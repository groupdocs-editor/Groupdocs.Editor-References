---
title: "Woff2Font"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny Woff2Font-klass från innehåll som representeras som en base64-kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

Skapar en ny Woff2Font‑klass från innehåll som representeras som en base64‑kodad sträng och med angivet namn

```csharp
public Woff2Font(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på WOFF2-typsnittet. Får inte vara null, tomt eller bestå av bara mellanslag. |
| contentInBase64 | String | Innehåll som base64-kodad sträng. Får inte vara null, tomt eller bestå av bara mellanslag. Om det inte är ett WOFF2-innehåll kommer ett undantag att kastas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

Skapar en ny Woff2Font‑klass från innehåll som representeras som en byte‑ström och med angivet namn

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på WOFF2-typsnittet. Får inte vara null, tomt eller bestå av bara mellanslag. |
| binaryContent | Stream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om detta objekt kommer att avyttras, kommer även denna ström att avyttras. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
