---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указывать пользовательские параметры для редактирования документов XML (eXtensible Markup Language) и их преобразования в HTML"
type: docs
weight: 1270
url: /ru/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Позволяет задавать пользовательские параметры для редактирования XML (eXtensible Markup Language) документов и их преобразования в HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Позволяет указывать тип кавычек (одинарные или двойные) для значений атрибутов. По умолчанию двойные кавычки. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Кодировка символов текстового документа, которая будет применена при его открытии. По умолчанию null — будет использована внутренняя кодировка документа. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Позволяет включать или отключать механизм исправления повреждённой структуры XML. По умолчанию отключено (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | Позволяет настроить форматирование XML, которое будет применено к структуре XML при её представлении в HTML. По умолчанию используется форматирование, которое можно изменить. Не может быть null. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | Позволяет настроить подсветку XML, которая будет применена к структуре XML при её представлении в HTML. По умолчанию используется подсветка, которую можно изменить. Не может быть null. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Позволяет включить алгоритм распознавания адресов электронной почты в значениях атрибутов |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Позволяет включить алгоритм распознавания URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Позволяет включить усечение конечных пробелов во внутреннем тексте тега. По умолчанию отключено (false) — конечные пробелы будут сохранены. |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
