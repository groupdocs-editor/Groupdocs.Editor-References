---
title: "EotFont"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny EotFont‑klass från innehåll representerat som en base64‑kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Skapar en ny EotFont-klass från innehåll, representerat som en base64-kodad sträng, och med angivet namn

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| eotName | String | Namn på EOT‑fonten. Får inte vara null, tom eller bestå av enbart blanksteg. |
| eotContentInBase64 | String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller bara whitespace. Om det inte är ett EOT-innehåll kastas ett undantag. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Skapar en ny EotFont-klass från innehåll, representerat som en byte-ström, och med angivet namn

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| eotName | String | Namn på EOT‑fonten. Får inte vara null, tom eller bestå av enbart blanksteg. |
| eotBinaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
