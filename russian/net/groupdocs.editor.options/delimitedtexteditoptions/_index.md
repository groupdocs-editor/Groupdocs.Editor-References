---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Параметры загрузки текстовых документов Spreadsheet, таких как CSV, табличных и т.п., использующих разделитель"
type: docs
weight: 810
url: /ru/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Параметры загрузки текстовых документов таблиц (CSV, табличных и т.д.), использующих разделитель (разделитель)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Создаёт экземпляр класса параметров для разделённого текста с обязательным разделителем (делимитером) |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Получает или задает значение, указывающее, преобразуется ли строка в текстовом документе в данные даты. По умолчанию `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Получает или задает значение, указывающее, преобразуется ли строка в текстовом документе в числовые данные. По умолчанию `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Включает механизмы оптимизации памяти при обработке входного документа, что может ухудшить производительность в некоторых особых случаях, но, с другой стороны, уменьшить использование памяти. Полезно при обработке огромных документов и возникновении OutOfMemoryException. По умолчанию `false` (оптимизация памяти отключена ради лучшей производительности). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Позволяет указать строковый разделитель (делимитер) для текстовых документов Spreadsheet |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Определяет, следует ли рассматривать последовательные разделители как один. По умолчанию `false`. |

### Замечания

https://en.wikipedia.org/wiki/Delimiter-separated_values

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
