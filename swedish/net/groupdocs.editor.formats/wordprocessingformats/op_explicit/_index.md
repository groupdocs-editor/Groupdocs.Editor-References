---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Konverterar en sträng som representerar en filändelse till ett WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats-objekt."
type: docs
weight: 140
url: /sv/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

Konverterar en sträng som representerar en filändelse till ett [`WordProcessingFormats`](../../wordprocessingformats) objekt.

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| filändelse | String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |

### Returvärde

Ett [`WordProcessingFormats`](../../wordprocessingformats) objekt som motsvarar den angivna filändelsen.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när den angivna filändelsen är null. |

### Se även

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
