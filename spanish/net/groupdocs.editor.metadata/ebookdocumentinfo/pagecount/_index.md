---
title: PageCount
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Devuelve el número de páginas en caso de MOBI o AZW3 o el número de capítulos en caso de ePub.
type: docs
weight: 30
url: /es/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Devuelve el número de páginas en caso de MOBI o AZW3 o el número de capítulos en caso de ePub.

```csharp
public int PageCount { get; }
```

### Observaciones

Los documentos de libros electrónicos generalmente no tienen páginas fijas y, por lo tanto, no cuentan con páginas. En el caso de ePub es posible calcular un número de capítulos. Sin embargo, los formatos MOBI y AZW3 tampoco tienen capítulos, por lo que este número se calcula a partir del tamaño de página estándar establecido en A4 en orientación vertical.

### Ver también

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* espacio de nombres [GroupDocs.Editor.Metadata](../../ebookdocumentinfo)
* asamblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->