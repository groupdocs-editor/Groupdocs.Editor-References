---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Fontextraktionsalternativ styr vilka teckensnitt som ska extraheras och varifrån"
type: docs
weight: 890
url: /sv/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

Fontextraktionsalternativ styr vilka teckensnitt som ska extraheras och varifrån

```csharp
public enum FontExtractionOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NotExtract | `0` | Extraherar inte någon teckensnittresurs varken från dokumentet eller från systemet. Standardvärde. |
| ExtractAllEmbedded | `1` | Extraherar alla teckensnittresurser som är inbäddade i det inmatade Word-dokumentet, oavsett vad de är: anpassade eller system. |
| ExtractEmbeddedWithoutSystem | `2` | Extraherar endast de inbäddade teckensnittresurserna som är anpassade (inte system). |
| ExtractAll | `3` | Försöker extrahera alla teckensnitt som används i det inmatade WordProcessing-dokumentet, inklusive systemteckensnitt. |

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
