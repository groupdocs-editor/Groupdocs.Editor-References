---
title: "InsertAsNewWorksheet"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Bandera booleana que especifica si la hoja de trabajo editada debe reemplazar la hoja de trabajo existente en el libro de cálculo original en la posición especificada por la propiedad WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber o si debe insertarse entre la hoja de trabajo existente y la anterior sin reemplazar su contenido. Por defecto es false, la hoja de trabajo existente será reemplazada. Esta propiedad se ignora si el valor de la propiedad WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber se establece en 0."
type: docs
weight: 20
url: /es/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Bandera booleana que especifica si la hoja de trabajo editada debe reemplazar la hoja de trabajo existente en el libro de cálculo original en la posición especificada por la propiedad [`WorksheetNumber`](../worksheetnumber), o si debe insertarse entre la hoja de trabajo existente y la anterior, sin reemplazar su contenido. Por defecto es false — la hoja de trabajo existente será reemplazada. Esta propiedad se ignora si el valor de la propiedad [`WorksheetNumber`](../worksheetnumber) se establece en '0'.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### Observaciones

Por defecto la hoja de trabajo es reemplazada. Esto significa que si el libro de cálculo dado tiene 5 hojas de trabajo, y [`WorksheetNumber`](../worksheetnumber)=4, entonces la cuarta hoja de trabajo será reemplazada por la nueva hoja de trabajo editada, mientras que la cantidad total de hojas de trabajo en el libro de cálculo (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en true, la nueva hoja de trabajo editada se insertará como cuarta hoja de trabajo, y todas las hojas de trabajo subsecuentes se desplazarán al final: la hoja de trabajo "old" cuarta se convierte en quinta, y la quinta se convierte en sexta, y la cantidad total de hojas de trabajo en el libro de cálculo se incrementará en uno y será igual a 6.

### Ver también

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
