---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar metadata för ett ordbehandlingsdokument"
type: docs
weight: 790
url: /sv/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
## WordProcessingDocumentInfo structure

Representerar metadata för ett ordbehandlingsdokument

```csharp
public struct WordProcessingDocumentInfo : IDocumentInfo, IEquatable<WordProcessingDocumentInfo>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/format) { get; } | Returnerar ett format för detta WordProcessing-dokument |
| [IsEncrypted](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/isencrypted) { get; } | Bestämmer om detta specifika WordProcessing-dokument är krypterat och kräver lösenord för öppning |
| [PageCount](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/pagecount) { get; } | Returnerar antal sidor |
| [Size](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/size) { get; } | Returnerar storlek i byte för detta WordProcessing-dokument |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/equals#equals)(WordProcessingDocumentInfo) | Bestämmer om detta objekt är lika med den andra angivna WordProcessingDocumentInfo-instansen |
| [GeneratePreview](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview)(int) | Genererar och returnerar en förhandsgranskning av den valda sidan i form av en SVG-bild |

### Se även

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
