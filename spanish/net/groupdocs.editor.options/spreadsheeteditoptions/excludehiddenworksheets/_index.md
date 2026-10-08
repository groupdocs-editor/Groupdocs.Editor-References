---
title: "ExcludeHiddenWorksheets"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite excluir hojas de cálculo ocultas en el documento Spreadsheet de entrada para que sean totalmente ignoradas. Por defecto es false; las hojas ocultas están disponibles y se procesan como normales."
type: docs
weight: 20
url: /es/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Permite excluir hojas de cálculo ocultas en el documento de Hoja de cálculo de entrada, de modo que se ignoren por completo. Por defecto es falso: las hojas ocultas están disponibles y se procesan como normales.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Observaciones

Varios formatos binarios de Spreadsheet (como XLSX) admiten el concepto de hojas de cálculo ocultas (pestañas). Un documento de dicho formato, si tiene más de una hoja, puede contener hojas ocultas adicionales. Por defecto, esas hojas ocultas están disponibles para el procesamiento, pero con esta opción se pueden ignorar, como si esas hojas ocultas no existieran. Cuando esta opción está habilitada, no se puede seleccionar una hoja oculta con la propiedad '[`WorksheetIndex`](../worksheetindex)'.

### Ver también

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
