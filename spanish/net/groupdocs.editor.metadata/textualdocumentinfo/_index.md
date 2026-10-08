---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa los metadatos de un documento textual como XML HTML o texto plano TXT"
type: docs
weight: 780
url: /es/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Representa los metadatos de un documento textual como XML, HTML o texto plano (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Devuelve la codificación detectada presumiblemente del documento de texto |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Devuelve un formato de este documento textual. Puede que no sea 100 % correcto en algunos casos. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Siempre devuelve ``false``, ya que los documentos textuales no pueden ser cifrados |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Siempre devuelve 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Devuelve el tamaño en bytes (no el número de caracteres) de este documento textual |

### Ver también

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
