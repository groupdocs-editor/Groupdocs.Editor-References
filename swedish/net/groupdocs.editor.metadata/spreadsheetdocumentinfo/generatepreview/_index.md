---
title: "GeneratePreview"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Genererar och returnerar en förhandsgranskning av det valda arbetsbladet i form av en SVG‑bild"
type: docs
weight: 60
url: /sv/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

Genererar och returnerar en förhandsgranskning av det valda arbetsbladet i form av en SVG‑bild

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| worksheetIndex | Int32 | 0‑baserat index för det önskade kalkylbladet. Kan inte vara mindre än 0 och får inte överstiga antalet kalkylblad i detta kalkylblad. |

### Returvärde

SVG‑bild som den icke‑nulla instansen av klassen [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Angivet *worksheetIndex* är mindre än 0 eller större än antalet kalkylblad i detta kalkylblad |

### Se även

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
