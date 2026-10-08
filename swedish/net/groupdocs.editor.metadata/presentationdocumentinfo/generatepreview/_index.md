---
title: "GeneratePreview"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Genererar och returnerar en förhandsgranskning av den valda bilden i form av en SVG‑bild"
type: docs
weight: 50
url: /sv/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Genererar och returnerar en förhandsgranskning av den valda bilden i form av en SVG‑bild

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| slideIndex | Int32 | 0‑baserat index för den önskade bilden. Kan inte vara mindre än 0 och får inte överstiga antalet bilder i denna presentation. |

### Returvärde

SVG‑bild som den icke‑nulla instansen av klassen [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Angivet *slideIndex* är mindre än 0 eller större än antalet bilder i denna presentation |

### Se även

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
