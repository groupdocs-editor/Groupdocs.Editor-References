---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para editar documentos de todos los formatos compatibles con Hoja de cálculo Excel admitidos"
type: docs
weight: 1110
url: /es/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

Permite especificar opciones personalizadas para editar documentos de todos los formatos de Hoja de cálculo (compatibles con Excel) soportados

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | Permite excluir hojas de cálculo ocultas en el documento de Hoja de cálculo de entrada, de modo que se ignoren por completo. Por defecto es falso: las hojas ocultas están disponibles y se procesan como normales. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | Cuando está habilitado, la tabla HTML en el documento HTML generado contiene una fila oculta inferior vacía con altura cero y celdas vacías, donde solo se especifica el ancho. Esta fila con celdas vacías contiene los valores exactos de ancho para cada columna y mejora la conversión inversa de HTML a Hoja de cálculo. Por defecto está habilitado (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | Cuando está habilitado, las celdas horizontales vacías adyacentes del documento de Hoja de cálculo de entrada se representarán en el documento HTML editable como fusionadas en una sola celda con el atributo `colspan` correspondiente. Por defecto está deshabilitado (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | Permite especificar el índice basado en cero de la hoja de cálculo (pestaña) del documento Spreadsheet de entrada, que debe convertirse a HTML (ver observaciones). |

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
