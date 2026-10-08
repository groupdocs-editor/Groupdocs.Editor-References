---
title: "MergeEmptyAdjacentCells"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Когда включено, пустые соседние горизонтальные ячейки из входного документа Spreadsheet будут представлены в редактируемом HTML‑документе как объединённые в одну ячейку с соответствующим атрибутом colspan. По умолчанию отключено false."
type: docs
weight: 40
url: /ru/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

Если включено, пустые смежные горизонтальные ячейки из исходного документа таблицы будут представлены в редактируемом HTML‑документе как объединённые в одну ячейку с соответствующим атрибутом `colspan`. По умолчанию отключено (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### Замечания

По умолчанию GroupDocs.Editor преобразует таблицу из входного документа Spreadsheet в выходной HTML‑документ, сохраняю каждую ячейку. Однако документы Spreadsheet могут быть разреженными — они могут содержать огромное количество «пустых областей», где многие ячейки пусты. Эта опция, когда включена, объединяет такие пустые ячейки в одну с атрибутом `colspan` в элементе `TD`, что может значительно уменьшить размер полученной HTML‑разметки.

### См. также

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
