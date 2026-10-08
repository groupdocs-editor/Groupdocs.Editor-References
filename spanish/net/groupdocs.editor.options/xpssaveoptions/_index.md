---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos XPS XML Paper Specifications"
type: docs
weight: 1300
url: /es/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos XPS (XML Paper Specifications)

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. Configurar esta opción como true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento. El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento). |

### Observaciones

Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications creados por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en la información de diseño, apariencia e impresión de un documento.

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
