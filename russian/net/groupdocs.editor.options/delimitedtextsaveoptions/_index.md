---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Содержит параметры для создания и сохранения текстовых документов Spreadsheet, таких как CSV, Tab‑based и др., которые используют разделитель‑делимитер"
type: docs
weight: 820
url: /ru/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Содержит параметры для создания и сохранения текстовых документов таблиц (CSV, табличных и т.д.), использующих разделитель (разделитель)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | Этот конструктор без параметров создает новый экземпляр DelimitedTextSaveOptions с разделителем по умолчанию — точкой с запятой (;). (может быть изменён позже через свойство [`Separator`](./separator)) |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Создаёт экземпляр класса параметров для разделённого текста с обязательным разделителем (делимитером) |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Позволяет задать кодировку для текстового документа Spreadsheet. По умолчанию (и если не указано) — UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Указывает, следует ли выводить разделители для пустой строки. Значение по умолчанию — `false`, что означает, что содержимое пустой строки будет пустым. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Позволяет указать строковый разделитель (делимитер) для текстовых документов Spreadsheet |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Указывает, следует ли обрезать ведущие пустые строки и столбцы, как это делает MS Excel |

### Замечания

https://en.wikipedia.org/wiki/Delimiter-separated_values

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
