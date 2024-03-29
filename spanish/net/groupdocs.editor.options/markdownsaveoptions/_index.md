---
title: MarkdownSaveOptions
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Permite especificar opciones personalizadas para generar y guardar documentos Markdown
type: docs
weight: 990
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
| [MarkdownSaveOptions](markdownsaveoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Especifica si las imágenes se guardan en formato Base64 en el archivo de salida. El valor predeterminado es`FALSO` . |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Especifica la carpeta física donde se guardan las imágenes al exportar un documento a el formato Markdown. El valor predeterminado es nulo. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Habilita los mecanismos de optimización de la memoria durante la generación de documentos desde HTML, lo que degrada el rendimiento como costo de la disminución del uso de la memoria. Estableciendo esta opción en`verdadero`puede reducir significativamente el consumo de memoria mientras genera documentos grandes a costa de un ahorro de tiempo más lento. El valor predeterminado es`FALSO` (la optimización de la memoria está deshabilitada en aras de un mejor rendimiento). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Permitir especifica cómo alinear el contenido de las tablas al exportar al formato Markdown. El valor predeterminado esAuto . |

### Observaciones

El usuario debe aplicar la clase MarkdownSaveOptions cuando hay una instancia de la clase EditableDocument, que contiene un contenido de documento editado, y es necesario guardar este contenido en el nuevo documento de formato Markdown.

### Ver también

* interface [ISaveOptions](../isaveoptions)
* espacio de nombres [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
