---
title: "ExcludeHiddenWorksheets"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет исключать скрытые листы в входном документе Spreadsheet, чтобы они полностью игнорировались. По умолчанию false — скрытые листы доступны и обрабатываются как обычные."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

Позволяет исключать скрытые листы в исходном документе таблицы, чтобы они полностью игнорировались. По умолчанию false — скрытые листы доступны и обрабатываются как обычные.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### Замечания

Некоторые двоичные форматы Spreadsheet (например, XLSX) поддерживают концепцию скрытых листов (вкладок). Документ такого формата, если в нём более одного листа, может содержать дополнительные скрытые листы. По умолчанию такие скрытые листы доступны для обработки, но с этой опцией их можно игнорировать, как будто этих скрытых листов нет. Когда эта опция включена, нельзя выбрать скрытый лист с помощью свойства '[`WorksheetIndex`](../worksheetindex)'.

### См. также

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
