---
title: "TextEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать пользовательские параметры загрузки простых текстовых TXT‑документов."
type: docs
weight: 1150
url: /ru/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

Позволяет задавать пользовательские параметры для загрузки простых текстовых (TXT) документов

```csharp
public class TextEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextEditOptions](texteditoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | Позволяет задать направление потока текста во входном простом текстовом документе. По умолчанию — слева направо. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По умолчанию отключено (false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | Кодировка символов текстового документа, которая будет применена при его открытии. |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | Получает или задает предпочтительный вариант обработки начальных пробелов. По умолчанию преобразует начальные пробелы в левый отступ. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | Позволяет указать, как распознавать элементы нумерованного списка при импорте документа из простого текстового формата. Значение по умолчанию — true. |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | Получает или задает предпочтительный вариант обработки конечных пробелов. По умолчанию усекает все конечные пробелы. |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
