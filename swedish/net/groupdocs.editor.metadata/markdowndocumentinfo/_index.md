---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar metadata för ett Markdown-dokument"
type: docs
weight: 750
url: /sv/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Representerar metadata för ett Markdown-dokument

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Returnerar formatet för detta Markdown‑dokument — är alltid [`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Eftersom Markdown‑dokument inte kan krypteras med lösenord, returnerar denna egenskap alltid ``false`` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Returnerar antal sidor. Markdown‑dokument har vanligtvis inga fasta sidor och därmed ingen sidräkning, så detta tal beräknas utifrån standard sidstorlek satt till A4 i stående orientering. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Returnerar storlek i byte för detta Markdown‑dokument |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Bestämmer om detta objekt är lika med det andra angivna [`MarkdownDocumentInfo`](../markdowndocumentinfo)-objektet. |

### Se även

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
