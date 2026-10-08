---
title: "TtcFont"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar en ny TtcFont-klass från innehåll representerat som en base64-kodad sträng och med angivet namn"
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

Skapar en ny TtcFont-klass från innehåll, representerat som base64‑kodad sträng, och med angivet namn

```csharp
public TtcFont(string name, string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på TTC‑fonten. Får inte vara null, tom eller bestå av enbart blanksteg. |
| contentInBase64 | String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bestå av enbart blanksteg. Om det inte är TTC‑innehåll kommer ett undantag att kastas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Någon av inmatningssträngarna är `null`, tom eller endast blanksteg |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | Innehåll i *contentInBase64*-argumentet kan inte identifieras som en giltig TTC‑font |

### Se även

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

Skapar en ny TtcFont-klass från innehåll, representerat som byte‑ström, och med angivet namn

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | String | Namn på TTC‑fonten. Får inte vara null, tom eller bestå av enbart blanksteg. |
| binaryContent | Stream | Innehåll som byte‑ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även denna ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | *name*-argumentet är `null`, tom eller endast blanksteg |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Kastas när angivet binärt innehåll inte kan tolkas korrekt som en giltig TTF‑font |

### Se även

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
