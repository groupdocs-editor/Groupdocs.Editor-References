---
title: "GeneratePreview"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Genererar och returnerar en förhandsgranskning av den valda sidan i form av en SVG-bild"
type: docs
weight: 60
url: /sv/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

Genererar och returnerar en förhandsgranskning av den valda sidan i form av en SVG-bild

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| pageIndex | Int32 | 0-baserat index för den önskade sidan. Kan inte vara mindre än 0, kan inte överstiga antalet sidor i detta WordProcessing-dokument. |

### Returvärde

SVG‑bild som den icke‑nulla instansen av klassen [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Angivet *pageIndex* är mindre än 0 eller större än antalet sidor i detta WordProcessing-dokument |

### Se även

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
