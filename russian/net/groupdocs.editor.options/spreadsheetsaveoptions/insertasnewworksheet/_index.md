---
title: "InsertAsNewWorksheet"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Булевый флаг, указывающий, следует ли заменять существующий лист отредактированным листом в оригинальной таблице на позиции, указанной свойством WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber, или его следует вставить между существующим листом и предыдущим без замены их содержимого. По умолчанию значение false — существующий лист будет заменён. Это свойство игнорируется, если значение свойства WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber установлено в 0."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Булевый флаг, указывающий, следует ли заменять существующий лист отредактированным листом в оригинальной таблице на позиции, указанной свойством [`WorksheetNumber`](../worksheetnumber), или его следует вставить между существующим листом и предыдущим без замены их содержимого. По умолчанию значение false — существующий лист будет заменён. Это свойство игнорируется, если значение свойства [`WorksheetNumber`](../worksheetnumber) установлено в '0'.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### Замечания

По умолчанию лист заменяется. Это означает, что если в заданной таблице 5 листов и [`WorksheetNumber`](../worksheetnumber)=4, то 4‑й лист будет заменён новым отредактированным листом, при этом общее количество листов в таблице (5) останется без изменений. Однако если значение этого свойства установлено в true, новый отредактированный лист будет вставлен как 4‑й лист, а все последующие листы будут сдвинуты вниз: "old" 4‑й лист становится 5‑м, а 5‑й становится 6‑м, и общее количество листов в таблице увеличится на один и станет равным 6.

### См. также

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
