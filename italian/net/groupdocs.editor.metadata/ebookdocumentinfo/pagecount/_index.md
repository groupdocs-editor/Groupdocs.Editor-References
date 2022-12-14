---
title: PageCount
second_title: GroupDocs.Editor per Riferimento API .NET
description: Restituisce il numero di pagine in caso di MOBI o AZW3 o il numero di capitoli in caso di ePub.
type: docs
weight: 30
url: /it/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Restituisce il numero di pagine in caso di MOBI o AZW3 o il numero di capitoli in caso di ePub.

```csharp
public int PageCount { get; }
```

### Osservazioni

I documenti e-book di solito non hanno pagine fisse e quindi il conteggio delle pagine. Nel caso di ePub è possibile calcolare un numero di capitoli. Tuttavia, anche i formati MOBI e AZW3 non hanno capitoli, quindi questo numero viene calcolato dal formato pagina standard impostato su A4 con orientamento verticale.

### Guarda anche

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* spazio dei nomi [GroupDocs.Editor.Metadata](../../ebookdocumentinfo)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
