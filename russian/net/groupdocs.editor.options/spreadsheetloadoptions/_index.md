---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Содержит параметры для загрузки бинарных документов Spreadsheet Cells, совместимых с Excel, таких как XLSX, ODS и т.д., в класс Editor"
type: docs
weight: 1120
url: /ru/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Содержит параметры для загрузки бинарных документов таблиц (Cells, совместимых с Excel), таких как XLS(X), ODS и т.д., в класс Editor

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Конструктор без параметров по умолчанию — все параметры имеют значения по умолчанию |

## Свойства

| Имя | Описание |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Включает механизмы оптимизации памяти во время обработки входного документа, что может ухудшить производительность в некоторых особых случаях, но, с другой стороны, уменьшить использование памяти. Полезно при обработке огромных документов и возникновении OutOfMemoryException. По умолчанию - false (оптимизация памяти отключена ради лучшей производительности). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Позволяет указать, изменить и получить пароль, который будет использоваться для открытия документа Spreadsheet, если он зашифрован. Установите NULL или пустую строку, чтобы не использовать пароль (значение по умолчанию). |

### См. также

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
