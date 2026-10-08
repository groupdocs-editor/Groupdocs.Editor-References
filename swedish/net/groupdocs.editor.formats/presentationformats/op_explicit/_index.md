---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Konverterar en sträng som representerar en filändelse till ett PresentationFormatsgroupdocs.editor.formats/presentationformats-objekt."
type: docs
weight: 150
url: /sv/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

Konverterar en sträng som representerar en filändelse till ett [`PresentationFormats`](../../presentationformats)-objekt.

```csharp
public static explicit operator PresentationFormats(string extension)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| filändelse | String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |

### Returvärde

Ett [`PresentationFormats`](../../presentationformats)-objekt som motsvarar den angivna filändelsen.

### Undantag

| undantag | villkor |
| --- | --- |
| [PresentationFormats](../../presentationformats) | Kastas när den angivna filändelsen är null. |

### Se även

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
