---
title: "GeneratePreview"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Genera y devuelve una vista previa de la hoja de cálculo seleccionada en forma de imagen SVG"
type: docs
weight: 60
url: /es/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

Genera y devuelve una vista previa de la hoja de cálculo seleccionada en forma de imagen SVG

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| worksheetIndex | Int32 | Índice basado en cero de la hoja de cálculo deseada. No puede ser menor que 0, no puede exceder el número de hojas de cálculo en esta hoja de cálculo. |

### Valor devuelto

Imagen SVG como la instancia no nula de la clase [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El *worksheetIndex* especificado es menor que 0 o mayor que el número de hojas de cálculo en esta hoja de cálculo. |

### Ver también

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
