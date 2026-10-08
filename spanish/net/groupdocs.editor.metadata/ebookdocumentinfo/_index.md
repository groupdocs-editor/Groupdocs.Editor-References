---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa los metadatos de un documento eBook"
type: docs
weight: 710
url: /es/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Representa los metadatos de un documento e-Book

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Devuelve el formato de este e-Book |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Debido a que los documentos e-Book no pueden encriptarse con contraseña, esta propiedad siempre devuelve 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Devuelve el número de páginas en caso de MOBI o AZW3 o el número de capítulos en caso de ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Devuelve el tamaño en bytes de este documento eBook. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Determina si esta instancia es igual a la otra instancia especificada de EbookDocumentInfo. |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
