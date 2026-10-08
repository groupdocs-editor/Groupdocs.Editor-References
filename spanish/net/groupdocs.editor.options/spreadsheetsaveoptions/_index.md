---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos Spreadsheet compatibles con Excel"
type: docs
weight: 1130
url: /es/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos de Hoja de cálculo (compatibles con Excel)

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Este constructor sin parámetros crea una nueva instancia de SpreadsheetSaveOptions con formato de salida XLSX (puede modificarse luego a través de la propiedad [`OutputFormat`](./outputformat)) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | Crea una nueva instancia de SpreadsheetSaveOptions con el formato de salida Spreadsheet obligatorio especificado, mientras que todos los demás parámetros son predeterminados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Bandera booleana que especifica si la hoja de cálculo editada debe reemplazar la hoja de cálculo existente en la hoja de cálculo original en la posición especificada por la propiedad [`WorksheetNumber`](./worksheetnumber), o si debe insertarse entre la hoja existente y la anterior, sin reemplazar su contenido. Por defecto es false — la hoja existente será reemplazada. Esta propiedad se ignora si el valor de la propiedad [`WorksheetNumber`](./worksheetnumber) se establece en '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Permite especificar un formato Spreadsheet que se utilizará para guardar el documento |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Permite especificar, modificar, obtener o eliminar una contraseña que se utilizará para codificar el documento Spreadsheet generado, si el formato de este documento admite protección con contraseña. Especifique NULL o una cadena vacía para eliminar (limpiar) la contraseña. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente en lugar de crear una nueva hoja de cálculo de una sola hoja (comportamiento predeterminado). WorksheetNumber es un número basado en 1 que indica la hoja de cálculo en la hoja de cálculo cargada en la clase Editor. Si es 0 (valor predeterminado), la nueva hoja de cálculo se creará con una sola hoja editada. Si es mayor o menor que cero, y existe una hoja de cálculo válida cargada en la clase Editor, la hoja de cálculo editada, representada por la instancia de EditableDocument de entrada, se insertará en esta hoja de cálculo. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | Permite especificar una matriz con números basados en 1 de las hojas de cálculo que deben eliminarse de la hoja de cálculo durante su guardado, en caso de que la hoja editada se inserte en una hoja de cálculo existente |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Permite habilitar la protección de hoja de cálculo para el documento Spreadsheet de salida. Por defecto es NULL — la protección no se aplica. No todos los formatos admiten protección de hoja de cálculo. |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
