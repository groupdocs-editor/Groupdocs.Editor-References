---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для редактирования документов всех поддерживаемых форматов таблиц, совместимых с Excel."
type: docs
weight: 1110
url: /ru/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

Позволяет задавать пользовательские параметры для редактирования документов всех поддерживаемых форматов таблиц (совместимых с Excel)

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | Позволяет исключать скрытые листы в исходном документе таблицы, чтобы они полностью игнорировались. По умолчанию false — скрытые листы доступны и обрабатываются как обычные. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | Если включено, HTML‑таблица в создаваемом HTML‑документе содержит пустую скрытую нижнюю строку нулевой высоты с пустыми ячейками, где указана только ширина. Эта строка с пустыми ячейками содержит точные значения ширины для каждого столбца и улучшает обратное преобразование из HTML в таблицу. По умолчанию включено (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | Если включено, пустые смежные горизонтальные ячейки из исходного документа таблицы будут представлены в редактируемом HTML‑документе как объединённые в одну ячейку с соответствующим атрибутом `colspan`. По умолчанию отключено (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | Позволяет указать индекс листа (вкладки) входного документа Spreadsheet, начинающийся с 0, который должен быть преобразован в HTML (см. примечания). |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
