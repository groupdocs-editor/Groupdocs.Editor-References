---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Konverterar en sträng som representerar en filändelse till ett EmailFormatsgroupdocs.editor.formats/emailformats‑objekt."
type: docs
weight: 150
url: /sv/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

Konverterar en sträng som representerar en filändelse till ett [`EmailFormats`](../../emailformats)-objekt.

```csharp
public static explicit operator EmailFormats(string extension)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| filändelse | String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |

### Returvärde

Ett [`EmailFormats`](../../emailformats)-objekt som motsvarar den angivna filändelsen.

### Undantag

| undantag | villkor |
| --- | --- |
| [EmailFormats](../../emailformats) | Kastas när den angivna filändelsen är null. |

### Se även

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
