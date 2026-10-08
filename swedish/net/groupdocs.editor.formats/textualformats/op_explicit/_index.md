---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Konverterar en sträng som representerar en filändelse till ett TextualFormatsgroupdocs.editor.formats/textualformats-objekt."
type: docs
weight: 100
url: /sv/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

Konverterar en sträng som representerar en filändelse till ett [`TextualFormats`](../../textualformats) objekt.

```csharp
public static explicit operator TextualFormats(string extension)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| filändelse | String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |

### Returvärde

Ett [`TextualFormats`](../../textualformats) objekt som motsvarar den angivna filändelsen.

### Undantag

| undantag | villkor |
| --- | --- |
| [TextualFormats](../../textualformats) | Kastas när den angivna filändelsen är null. |

### Se även

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
