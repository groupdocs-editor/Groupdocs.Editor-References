---
title: "PageCount"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar antal sidor i fallet MOBI eller AZW3 eller antal kapitel i fallet ePub."
type: docs
weight: 30
url: /sv/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Returnerar antal sidor i fallet MOBI eller AZW3 eller antal kapitel i fallet ePub.

```csharp
public int PageCount { get; }
```

### Anmärkningar

e-Book-dokument har vanligtvis inga fasta sidor och därmed ingen sidräkning. För ePub är det möjligt att beräkna ett antal kapitel. Däremot har MOBI- och AZW3-formaten inga kapitel heller, så detta antal beräknas utifrån standard sidstorlek inställd på A4 i stående orientering.

### Se även

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
