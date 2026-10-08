---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de texto plano TXT"
type: docs
weight: 1170
url: /es/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos de texto plano (TXT)

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | Especifica si se deben agregar marcas bidireccionales antes de cada ejecución BiDi al exportar en formato de texto plano. El valor predeterminado es 'false' — no agregar marcas BiDi. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | Codificación de caracteres del documento de texto, que se aplicará al guardarlo |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | Especifica si el programa debe intentar preservar el diseño de las tablas al guardar en formato de texto plano. El valor predeterminado es false. |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
