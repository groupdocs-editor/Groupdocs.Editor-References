---
title: "WorksheetIndex"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar el índice basado en 0 de la pestaña de hoja de cálculo del documento Spreadsheet de entrada que debe convertirse a HTML; ver observaciones."
type: docs
weight: 50
url: /es/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

Permite especificar el índice basado en cero de la hoja de cálculo (pestaña) del documento Spreadsheet de entrada, que debe convertirse a HTML (ver observaciones).

```csharp
public int WorksheetIndex { get; set; }
```

### Observaciones

La mayoría de los documentos Spreadsheet admiten el concepto de pestañas, es decir, pueden ser multi-pestaña. Por otro lado, el formato HTML no soporta esa estructura. Debido a esto, GroupDocs.Editor solo puede convertir a HTML una pestaña específica del documento de entrada, y esta opción permite especificarla. El índice de pestaña es basado en 0, los valores negativos están prohibidos. Si el índice especificado supera el número total de pestañas, se lanzará una excepción. Si el documento Spreadsheet de entrada contiene solo una pestaña, esta opción se ignorará. El valor predeterminado es 0 (primera pestaña).

### Ver también

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
