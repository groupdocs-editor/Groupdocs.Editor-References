---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa los metadatos de un documento de correo electrónico de cualquier formato de correo compatible"
type: docs
weight: 720
url: /es/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Representa los metadatos de un documento de correo electrónico de cualquier formato de correo compatible

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Devuelve el formato de este documento de correo electrónico |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | Debido a que los documentos de correo electrónico no pueden encriptarse con contraseña, esta propiedad siempre devuelve 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Siempre devuelve 1, porque los documentos de correo electrónico no tienen vista paginada |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Devuelve el tamaño en bytes de este documento de correo electrónico |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Determina si esta instancia es igual a la otra instancia especificada de EmailDocumentInfo |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
