---
title: "WorksheetNumber"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite insertar la hoja de cálculo editada en una copia de una hoja de cálculo existente en lugar de crear una nueva hoja de cálculo de una sola hoja (comportamiento predeterminado). WorksheetNumber es un número basado en 1 de una hoja en la hoja de cálculo cargada en la clase Editor. Si es 0 (valor predeterminado), se creará la nueva hoja de cálculo con una sola hoja editada. Si es mayor o menor que cero y hay una hoja de cálculo válida cargada en la clase Editor, la hoja editada representada por la instancia EditableDocument de entrada se insertará en esa hoja de cálculo."
type: docs
weight: 50
url: /es/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber/
---
## SpreadsheetSaveOptions.WorksheetNumber property

Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente en lugar de crear una nueva hoja de cálculo de una sola hoja (comportamiento predeterminado). WorksheetNumber es un número basado en 1 que indica la hoja de cálculo en la hoja de cálculo cargada en la clase Editor. Si es 0 (valor predeterminado), la nueva hoja de cálculo se creará con una sola hoja editada. Si es mayor o menor que cero, y existe una hoja de cálculo válida cargada en la clase Editor, la hoja de cálculo editada, representada por la instancia de EditableDocument de entrada, se insertará en esta hoja de cálculo.

```csharp
public int WorksheetNumber { get; set; }
```

### Observaciones

Propiedad entera WorksheetNumber, si no está en su estado predeterminado (valor reservado '0'), representa un número de hoja, por lo que comienza en 1, no en cero, y su valor máximo es la cantidad de diapositivas existentes en una presentación. Sin embargo, si el valor especificado es mayor que la cantidad de diapositivas, GroupDocs.Editor lo ajustará para marcar la última hoja. También se permiten valores negativos y cuentan las hojas desde el final. Por ejemplo, "-1" indica la última hoja en una hoja de cálculo, "-2" — la penúltima, etc. Al igual que con los valores positivos, cuando el número de hoja negativo supera el recuento total de hojas en la hoja de cálculo dada, se ajustará a la primera hoja. La propiedad booleana [`InsertAsNewWorksheet`](../insertasnewworksheet) está estrechamente vinculada a esta.

### Ejemplos

El libro de cálculo dado tiene 5 hojas de trabajo: WorksheetNumber = 0; — ignore el libro de cálculo dado, cree un nuevo libro de cálculo y coloque la hoja de trabajo editada en él. WorksheetNumber = 1; — reemplace la primera hoja de trabajo con la editada WorksheetNumber = 2; — reemplace la segunda hoja de trabajo con la editada WorksheetNumber = 5; — reemplace la última (5ª) hoja de trabajo con la editada WorksheetNumber = 6; — reemplace la última (5ª) hoja de trabajo con la editada, porque 6 es mayor que 5 y por lo tanto se ajusta WorksheetNumber = -1; — reemplace la última (5ª) hoja de trabajo con la editada, porque "-1" significa "último existente" WorksheetNumber = -2; — reemplace la cuarta hoja de trabajo con la editada WorksheetNumber = -3; — reemplace la tercera hoja de trabajo con la editada WorksheetNumber = -4; — reemplace la segunda hoja de trabajo con la editada WorksheetNumber = -5; — reemplace la primera hoja de trabajo con la editada WorksheetNumber = -6; — reemplace la primera hoja de trabajo con la editada, porque "-6" es mayor que 5 y por lo tanto se ajusta

### Ver también

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
