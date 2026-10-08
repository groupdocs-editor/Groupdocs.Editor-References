---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para editar documentos de todos los formatos compatibles con WordProcessing y Wordscompliant, como DOCX, RTF, ODT, etc."
type: docs
weight: 1200
url: /es/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Permite especificar opciones personalizadas para editar documentos de todos los formatos compatibles de procesamiento de texto (compatibles con Words) como DOC(X), RTF, ODT, etc.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Crea y devuelve una nueva instancia de la clase WordProcessingEditOptions, donde todas las opciones se establecen a sus valores predeterminados. |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Crea y devuelve una nueva instancia de la clase WordProcessingEditOptions con paginación especificada y el resto de opciones predeterminadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Especifica si la información de idioma se exporta al marcado HTML en forma de atributos HTML 'lang'. Esta opción puede ser útil para la conversión de ida y vuelta de documentos multilingües. Por defecto está desactivada (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitada (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Obtiene o establece un valor que indica si solo se extraen los recursos de fuentes que se utilizan en el contenido textual del documento. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Responsable de extraer los recursos de fuentes que se utilizan en el documento WordProcessing de entrada. Por defecto no extrae ninguna fuente (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Permite especificar un nombre de clase, que se colocará en los atributos 'class' de cada elemento HTML que represente algún campo en el documento WordProcessing de entrada. Por defecto es NULL; los atributos 'class' no se aplican. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | Controla dónde almacenar los datos de estilo y formato del documento WordProcessing de entrada: en una hoja de estilo externa (`false`) o como estilos en línea en el marcado HTML (`true`). Por defecto se usan estilos externos (`false`). |

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
