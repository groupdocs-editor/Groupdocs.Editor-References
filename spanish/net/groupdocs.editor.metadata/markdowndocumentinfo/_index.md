---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa los metadatos de un documento Markdown"
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
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Devuelve un formato de este documento Markdown — siempre es [`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Debido a que los documentos Markdown no pueden ser cifrados con contraseña, esta propiedad siempre devuelve ``false`` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Devuelve el número de páginas. Los documentos Markdown normalmente no tienen páginas fijas y, por lo tanto, recuento de páginas, por lo que este número se calcula a partir del tamaño de página estándar establecido en A4 en orientación vertical. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Devuelve el tamaño en bytes de este documento Markdown |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Determina si esta instancia es igual a la otra instancia especificada de [`MarkdownDocumentInfo`](../markdowndocumentinfo). |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
