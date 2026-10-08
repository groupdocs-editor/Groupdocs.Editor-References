---
title: "IDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Gemensamt gränssnitt för alla filmetadata‑omslag"
type: docs
weight: 740
url: /sv/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

Gemensamt gränssnitt för alla filmetadata‑omslag

```csharp
public interface IDocumentInfo
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | Den implementerande typen bör returnera ett dokumentformat som ett enda värde från en typ, som representerar en formatfamilj och ärver från IDocumentFormat‑gränssnittet |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | Anger om en specifik fil är krypterad och kräver lösenord för öppning. För dokumenttyper som inte kan krypteras (t.ex. alla textbaserade) bör alltid returnera 'false'. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | Den implementerande typen bör returnera antalet (sidor) eller andra liknande formatberoende enheter (flikar, bilder osv.). För de familjetyper som inte har något liknande (t.ex. rena textdokument eller XML) bör den returnera 1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | Dokumentstorlek i byte |

### Se även

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
