---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos Markdown"
type: docs
weight: 1000
url: /es/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos Markdown

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Especifica si las imágenes se guardan en formato Base64 en el archivo de salida. El valor predeterminado es `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Especifica la carpeta física donde se guardan las imágenes al exportar un documento al formato Markdown. El valor predeterminado es null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Habilita los mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. Configurar esta opción en `true` puede disminuir significativamente el consumo de memoria al generar documentos grandes, a costa de un tiempo de guardado más lento. El valor predeterminado es `false` (la optimización de memoria está deshabilitada para lograr un mejor rendimiento). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Permite especificar cómo alinear el contenido en tablas al exportar al formato Markdown. El valor predeterminado es Auto. |

### Observaciones

La clase MarkdownSaveOptions debe ser aplicada por el usuario cuando exista una instancia de la clase EditableDocument, que contiene el contenido de un documento editado, y sea necesario guardar este contenido en un nuevo documento con formato Markdown.

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
