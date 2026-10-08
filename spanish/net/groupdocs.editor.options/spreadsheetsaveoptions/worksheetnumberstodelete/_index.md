---
title: "WorksheetNumbersToDelete"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar una matriz con números de hoja de cálculo basados en 1 que deben eliminarse de la hoja de cálculo al guardarla en caso de que la hoja editada se inserte en una hoja de cálculo existente."
type: docs
weight: 60
url: /es/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

Permite especificar una matriz con números basados en 1 de las hojas de cálculo que deben eliminarse de la hoja de cálculo durante su guardado, en caso de que la hoja editada se inserte en una hoja de cálculo existente

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### Observaciones

Cuando la hoja de cálculo editada se guarda no como una nueva hoja de cálculo de una sola hoja (comportamiento predeterminado), sino que se guarda en una hoja de cálculo existente (usando la propiedad [`WorksheetNumber`](../worksheetnumber)), también es posible eliminar algunas hojas específicas de esa hoja de cálculo especificando sus números en esta matriz.

Por defecto esta matriz es `null` — no se eliminará ninguna hoja. Sin embargo, cuando esta matriz no es nula y no está vacía, y contiene al menos un número de hoja válido, después de generar el documento de hoja de cálculo de salida con el contenido de la hoja editada, las hojas con los números especificados se eliminarán de la hoja de cálculo justo antes de escribir su contenido en el flujo o archivo de salida.

Los números de hoja en esta matriz son basados en 1, no en 0; los números no válidos (menores que 1 o mayores que el número total de hojas) serán ignorados.

### Ver también

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
