---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos compatibles con WordProcessing después de haber sido editados"
type: docs
weight: 1240
url: /es/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos compatibles con procesamiento de texto después de haber sido editados

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Este constructor sin parámetros crea una nueva instancia de WordProcessingSaveOptions con formato de salida DOCX (puede modificarse luego mediante la propiedad [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Crea una nueva instancia de WordProcessingSaveOptions con el formato de salida WordProcessing obligatorio especificado, mientras que todos los demás parámetros son predeterminados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Permite habilitar o deshabilitar la paginación que se utilizará al guardar el documento WordProcessing. Si el documento original se abrió y editó en modo de paginación, esta opción también debe estar habilitada. Por defecto está deshabilitada. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Responsable de incrustar recursos de fuentes en el documento WordProcessing de salida. Por defecto no incrusta ninguna fuente (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Permite establecer anular la configuración regional predeterminada (idioma) para el documento WordProcessing, que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) la configuración regional del documento según sus propias configuraciones u otros factores. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Permite establecer anular la configuración regional (idioma) para el texto RTL (de derecha a izquierda), que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) la configuración regional RTL del documento según sus propias configuraciones u otros factores. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Permite anular la configuración regional (idioma) para el documento WordProcessing para el texto de Asia Oriental, que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) la configuración regional de Asia Oriental del documento según sus propias configuraciones u otros factores. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. Configurar esta opción como true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento. El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Permite especificar un formato WordProcessing, que se utilizará para guardar el documento |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Permite especificar, modificar, obtener o eliminar una contraseña, que se utilizará para codificar el documento WordProcessing generado. Especifique NULL o una cadena vacía para eliminar (limpiar) la contraseña. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Permite controlar y aplicar las opciones de protección del documento para el documento WordProcessing de cualquier formato, que soporte protección de documentos. Por defecto es NULL - no se utilizará la protección del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Crea y devuelve una copia completa de esta instancia de la clase WordProcessingSaveOptions |

### Observaciones

WordProcessingSaveOptions se aplica en situaciones en las que existe una instancia de la clase EditableDocument, que contiene el contenido de un documento editado, y se requiere guardar este contenido en un nuevo documento con formato WordProcessing.

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
