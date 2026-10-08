---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для сохранения экземпляра EditableDocument../groupdocs.editor/editabledocument в формате HTML."
type: docs
weight: 900
url: /ru/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

Позволяет задавать пользовательские параметры для сохранения экземпляра [`EditableDocument`](../../groupdocs.editor/editabledocument) в формате HTML.

```csharp
public sealed class HtmlSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | Определяет, какой разделитель будет использоваться вокруг значений атрибутов в HTML‑элементах: одинарная кавычка (значение по умолчанию) или двойная кавычка. |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | Определяет, где хранить CSS‑таблицы стилей: как внешние ресурсы (`false`) или внедрять их в разметку HTML, внутри элемента STYLE в секции HTML-&gt;HEAD (`true`). |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | Определяет, как будут отображаться имена HTML‑тегов в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная. |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов. Это свойство **must** не должно быть `null`, иначе GroupDocs.Editor выбросит исключение при сохранении [`EditableDocument`](../../groupdocs.editor/editabledocument) в формат HTML. |

### См. также

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
