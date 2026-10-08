---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos PDF (Portable Document Format)."
type: docs
weight: 1070
url: /es/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos PDF (Formato de Documento Portátil)

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | Especifica el nivel de cumplimiento de los estándares PDF para los documentos de salida. Por defecto es PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | Responsable de incrustar los recursos de fuentes, que se usan en el documento original, en el documento PDF resultante. Por defecto no incrusta ninguna fuente (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. Configurar esta opción como true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento. El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | Contraseña que se aplicará al documento PDF generado como contraseña de usuario, requerida para abrirlo. Si es NULL o está vacía, no se aplicará ninguna contraseña al documento. De lo contrario, el documento se cifrará con RC4 (longitud de clave de 128 bits). Por defecto es NULL — no se aplica contraseña. |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
