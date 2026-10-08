---
title: "MergeEmptyAdjacentCells"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Cuando está habilitada, las celdas horizontales vacías adyacentes del documento Spreadsheet de entrada se representarán en el documento HTML editable como fusionadas en una única celda con el atributo colspan correspondiente. Por defecto está deshabilitada false."
type: docs
weight: 40
url: /es/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

Cuando está habilitado, las celdas horizontales vacías adyacentes del documento de Hoja de cálculo de entrada se representarán en el documento HTML editable como fusionadas en una sola celda con el atributo `colspan` correspondiente. Por defecto está deshabilitado (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### Observaciones

Por defecto, GroupDocs.Editor convierte una tabla del documento Spreadsheet de entrada al documento HTML de salida preservando cada celda. Sin embargo, los documentos Spreadsheet pueden ser escasos — pueden contener una gran cantidad de \"áreas vacías\", donde muchas celdas están vacías. Esta opción, cuando está habilitada, fusiona esas celdas vacías en una sola con el atributo `colspan` en el elemento `TD`, y así puede reducir significativamente el tamaño del marcado HTML generado.

### Ver también

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
