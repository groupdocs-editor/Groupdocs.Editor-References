---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar la encapsulación MIME MHTML de documentos HTML agregados"
type: docs
weight: 1020
url: /es/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

Permite especificar opciones personalizadas para generar y guardar los documentos MHTML (encapsulación MIME de documentos HTML agregados)

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | Especifica si se deben usar URLs CID (Content-ID) para referenciar recursos (imágenes, fuentes, CSS) incluidos en documentos MHTML. El valor predeterminado es `false`. |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | Especifica si se deben exportar las propiedades de documento integradas y personalizadas a MHTML. El valor predeterminado es `false`. |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | Especifica si la información de idioma se exporta a MHTML. El valor predeterminado es `false`. |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
