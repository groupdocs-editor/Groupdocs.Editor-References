---
title: WordProcessingSaveOptions
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Permite especificar opciones personalizadas para generar y guardar documentos compatibles con WordProcessing después de editarlos
type: docs
weight: 1010
url: /es/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos compatibles con WordProcessing después de editarlos

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions)(WordProcessingFormats) | Crea una nueva instancia de WordProcessingSaveOptions con el formato de salida de WordProcessing obligatorio especificado, mientras que todos los demás parámetros son predeterminados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Permite habilitar o deshabilitar la paginación que se utilizará para guardar el documento de WordProcessing. Si el documento original se abrió y editó en modo paginación, esta opción también debe estar habilitada. Por defecto está deshabilitado. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Responsable de incrustar recursos de fuente en el documento de procesamiento de textos de salida. Por defecto no incrusta ninguna fuente (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Permite anular la configuración regional predeterminada (idioma) para el documento de WordProcessing, que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) la configuración regional del documento según a su propia configuración o a otros factores. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Permite establecer la anulación de la configuración regional (idioma) del documento de procesamiento de texto para el texto RTL (de derecha a izquierda), que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá) el documento RTL locale según su propia configuración u otros factores. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Permite anular la configuración regional (idioma) del documento de WordProcessing para el texto de Asia oriental, que se aplicará durante su creación. Cuando no se especifica (valor predeterminado), MS Word (u otro programa) detectará (o elegirá ) el documento East-Asian locale según su propia configuración u otros factores. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Habilita los mecanismos de optimización de la memoria durante la generación de documentos desde HTML, lo que degrada el rendimiento como costo de la disminución del uso de la memoria. Establecer esta opción en verdadero puede reducir significativamente el consumo de memoria mientras se generan documentos grandes a costa de un ahorro de tiempo más lento. El valor predeterminado es falso (la optimización de la memoria está deshabilitada en aras de un mejor rendimiento). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Permite especificar un formato de procesamiento de texto, que se utilizará para guardar el documento |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Permite especificar, modificar, obtener o eliminar una contraseña, que se utilizará para codificar el documento de WordProcessing generado. Especifique NULL o una cadena vacía para eliminar (limpiar) la contraseña. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Permite controlar y aplicar las opciones de protección de documentos para el documento de WordProcessing de cualquier formato que soporte la protección de documentos. Por defecto es NULL - no se utilizará la protección de documentos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Crea y devuelve una copia completa de esta instancia de WordProcessingSaveOptions class |

### Observaciones

WordProcessingSaveOptions se aplica en situaciones en las que hay una instancia de la clase EditableDocument, que contiene un contenido de documento editado, y se requiere guardar este contenido en el nuevo documento de formato WordProcessing.

### Ver también

* interface [ISaveOptions](../isaveoptions)
* espacio de nombres [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
