---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar metadata för ett textdokument som XML HTML eller vanlig text TXT"
type: docs
weight: 780
url: /sv/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Representerar metadata för ett textdokument som XML, HTML eller vanlig text (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Returnerar den upptäckta sannolika kodningen av textdokumentet |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Returnerar ett format för detta textdokument. Kan vara inte 100 % korrekt i vissa fall. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Returnerar alltid ``false``, eftersom textdokument inte kan krypteras |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Returnerar alltid 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Returnerar storlek i byte (inte antalet tecken) för detta textdokument |

### Se även

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
