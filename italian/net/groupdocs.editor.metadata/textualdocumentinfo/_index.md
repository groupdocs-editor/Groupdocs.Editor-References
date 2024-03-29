---
title: TextualDocumentInfo
second_title: GroupDocs.Editor per Riferimento API .NET
description: Rappresenta i metadati di un documento testuale come XML HTML o testo normale TXT
type: docs
weight: 780
url: /it/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Rappresenta i metadati di un documento testuale come XML, HTML o testo normale (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Restituisce presumibile codifica rilevata del documento di testo |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Restituisce un formato di questo documento testuale. Potrebbe non essere corretto al 100% in alcuni casi. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Restituisce sempre ``falso` `, poiché i documenti testuali non possono essere crittografati |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Restituisce sempre 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Restituisce la dimensione in byte (non il numero di caratteri) di questo documento testuale |

### Guarda anche

* interface [IDocumentInfo](../idocumentinfo)
* spazio dei nomi [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
