---
title: "PageCount"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve el número de páginas en caso de MOBI o AZW3 o el número de capítulos en caso de ePub."
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

Los documentos e-Book normalmente no tienen páginas fijas y, por lo tanto, recuento de páginas. En el caso de ePub es posible calcular un número de capítulos. Sin embargo, los formatos MOBI y AZW3 tampoco tienen capítulos, por lo que este número se calcula a partir del tamaño de página estándar establecido en A4 en orientación vertical.

### Ver también

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
