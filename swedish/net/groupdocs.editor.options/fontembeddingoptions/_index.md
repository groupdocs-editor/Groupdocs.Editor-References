---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Teckensnittsinbäddningsalternativ styr vilka teckensnittresurser som ska bäddas in i det genererade WordProcessing- eller PDF-dokumentet"
type: docs
weight: 880
url: /sv/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Teckensnittsinbäddningsalternativ styr vilka teckensnittresurser som ska bäddas in i det genererade WordProcessing- eller PDF-dokumentet

```csharp
public enum FontEmbeddingOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NotEmbed | `0` | Bädda inte in någon teckensnittresurs, varken från EditableDocument eller från systemet. Standardvärde. |
| EmbedAll | `1` | Analysera dokumentinnehållet från den ingående EditableDocument, hitta alla använda teckensnitt och bädda in dem i utdata‑WordProcessing‑ eller PDF‑dokumentet. I första hand hämtar GroupDocs.Editor teckensnitt från teckensnittresurserna i EditableDocument. Om de är otillräckliga eller saknas, hämtar GroupDocs.Editor teckensnitt från OS. |
| EmbedWithoutSystem | `2` | Samma som EmbedAll, men exkludera de teckensnitt som OS behandlar som systemteckensnitt. |

### Anmärkningar

Alternativen för teckensnittsinfogning tillämpas under dokumentlagring (från mellansteg‑EditableDocument till utdata‑WordProcessing‑ eller PDF‑format), den här uppräkningen ingår som en egenskap i WordProcessingSaveOptions och PdfSaveOptions, varifrån den ska användas.

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
