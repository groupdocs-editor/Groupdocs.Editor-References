---
title: "WorksheetIndex"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать 0‑базовый индекс вкладки листа входного документа Spreadsheet, который должен быть преобразован в HTML (см. примечания)."
type: docs
weight: 50
url: /ru/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

Позволяет указать индекс листа (вкладки) входного документа Spreadsheet, начинающийся с 0, который должен быть преобразован в HTML (см. примечания).

```csharp
public int WorksheetIndex { get; set; }
```

### Замечания

Большинство документов Spreadsheet поддерживают концепцию вкладок, т.е. могут быть многовкладочными. С другой стороны, формат HTML не поддерживает такую структуру. Поэтому GroupDocs.Editor может преобразовать в HTML только одну конкретную вкладку входного документа, и эта опция позволяет её указать. Индекс вкладки начинается с 0, отрицательные значения запрещены. Если указанный индекс превышает количество всех вкладок, будет выброшено исключение. Если входной документ Spreadsheet содержит только одну вкладку, эта опция будет игнорироваться. Значение по умолчанию — 0 (первая вкладка).

### См. также

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
