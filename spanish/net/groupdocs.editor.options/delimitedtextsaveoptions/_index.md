---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Contiene opciones para generar y guardar documentos de hoja de cálculo basados en texto, CSV, basados en tabulaciones, etc., que utilizan un delimitador separador"
type: docs
weight: 820
url: /es/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Contiene opciones para generar y guardar documentos de hoja de cálculo basados en texto (CSV, basados en tabulaciones, etc.), que utilizan un separador (delimitador)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | Este constructor sin parámetros crea una nueva instancia de DelimitedTextSaveOptions con un separador predeterminado de punto y coma (;) (puede modificarse luego a través de la propiedad [`Separator`](./separator)) |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Crea una instancia de la clase de opciones para texto delimitado con un separador (delimitador) obligatorio |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Permite establecer una codificación para el documento de hoja de cálculo basado en texto. Por defecto (y si no se especifica) es UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Indica si los separadores deben generarse para una fila en blanco. El valor predeterminado es `false`, lo que significa que el contenido de la fila en blanco estará vacío. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Permite especificar un separador (delimitador) de cadena para documentos de hoja de cálculo basados en texto |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Indica si las filas y columnas en blanco iniciales deben recortarse como lo hace MS Excel |

### Observaciones

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
