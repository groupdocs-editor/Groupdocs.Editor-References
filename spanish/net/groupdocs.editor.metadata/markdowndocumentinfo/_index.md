---
title: MarkdownDocumentInfo
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa los metadatos de un documento Markdown
type: docs
weight: 750
url: /es/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Representa los metadatos de un documento Markdown

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Devuelve un formato de este documento Markdown — siempre es[`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Debido a que los documentos de Markdown no se pueden cifrar con contraseña, esta propiedad siempre devuelve ``FALSO` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Devuelve el número de páginas. Los documentos Markdown normalmente no tienen páginas fijas y, por lo tanto, el recuento de páginas, por lo que este número se calcula a partir del tamaño de página estándar establecido en A4 en orientación vertical. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Devuelve el tamaño en bytes de este documento Markdown |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Determina si esta instancia es igual a la otra especificada[`MarkdownDocumentInfo`](../markdowndocumentinfo) instancia. |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* espacio de nombres [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
