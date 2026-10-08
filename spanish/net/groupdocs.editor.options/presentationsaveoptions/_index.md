---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de presentación compatibles con PowerPoint."
type: docs
weight: 1100
url: /es/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos de Presentación (compatibles con PowerPoint)

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Este constructor sin parámetros crea una nueva instancia de PresentationSaveOptions con formato de salida PPTX (puede modificarse luego a través de la propiedad [`OutputFormat`](./outputformat)). |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | Crea una nueva instancia de PresentationSaveOptions con el formato de salida de presentación obligatorio especificado, mientras que todos los demás parámetros son predeterminados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Bandera booleana que especifica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por la propiedad [`SlideNumber`](./slidenumber), o si debe insertarse entre la diapositiva existente y la anterior, sin reemplazar su contenido. Por defecto es `false` — la diapositiva existente será reemplazada. Esta propiedad se ignora si el valor de la propiedad [`SlideNumber`](./slidenumber) se establece en '0'. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Permite especificar un formato de presentación que se utilizará para guardar el documento. |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Permite especificar, modificar y obtener la contraseña que se utilizará para codificar el documento de presentación resultante. Por defecto es NULL - no se establecerá contraseña. Establezca NULL o una cadena vacía para eliminar la contraseña, si se había establecido previamente. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Permite insertar la diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado). El número de diapositiva es un número basado en 1 de una diapositiva en la presentación, cargada en la clase Editor. Si es 0 (valor predeterminado), la nueva presentación se creará con una sola diapositiva editada. Si es mayor o menor que cero, y existe una presentación válida cargada en la clase Editor, la diapositiva editada, almacenada dentro de la instancia de EditableDocument de entrada, se insertará en esa presentación. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | Permite especificar una matriz con números de diapositivas basados en 1 que deben eliminarse de la presentación durante su guardado, en caso de que la diapositiva editada se inserte en una presentación existente. |

### Observaciones

Una instancia de esta clase debe pasarse al método  para guardar la presentación editada en el documento final de algún formato específico de presentación. Todos los demás parámetros son opcionales y pueden omitirse; por defecto, el formato de la presentación guardada es PPTX, pero puede cambiarse mediante el constructor o una propiedad.

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
