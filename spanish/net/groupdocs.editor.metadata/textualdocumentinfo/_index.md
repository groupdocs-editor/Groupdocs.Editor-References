---
title: TextualDocumentInfo
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa los metadatos de un documento de texto como XML HTML o texto sin formato TXT
type: docs
weight: 630
url: /es/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Representa los metadatos de un documento de texto como XML, HTML o texto sin formato (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Devuelve la presunta codificación detectada del documento de texto |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Devuelve un formato de este documento de texto. Puede que no sea 100% correcto en algunos casos. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Siempre devuelve 'falso', ya que los documentos de texto no se pueden cifrar. |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Siempre devuelve 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Devuelve el tamaño en bytes (no el número de caracteres) de este documento textual |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* espacio de nombres [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->