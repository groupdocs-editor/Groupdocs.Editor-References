---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Содержит параметры, позволяющие настроить подсветку XML во время преобразования XMLtoHTML"
type: docs
weight: 1290
url: /ru/net/groupdocs.editor.options/xmlhighlightoptions/
---
## XmlHighlightOptions class

Содержит параметры, позволяющие настроить подсветку XML при конвертации XML в HTML

```csharp
public sealed class XmlHighlightOptions : IEditOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AttributeNamesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributenamesfontsettings) { get; } | Отвечает за отображение шрифта имён атрибутов |
| [AttributeValuesFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/attributevaluesfontsettings) { get; } | Отвечает за отображение шрифта значений атрибутов |
| [CDataFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/cdatafontsettings) { get; } | Отвечает за отображение шрифта секций CDATA (включая пару открывающего и закрывающего тегов) |
| [HtmlCommentsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/htmlcommentsfontsettings) { get; } | Отвечает за отображение шрифта комментариев HTML (включая пару открывающего и закрывающего тегов) |
| [InnerTextFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/innertextfontsettings) { get; } | Отвечает за отображение шрифта текста внутри тега |
| [IsDefault](../../groupdocs.editor.options/xmlhighlightoptions/isdefault) { get; } | Определяет, имеет ли объект параметров подсветки XML настройки шрифта по умолчанию |
| [XmlTagsFontSettings](../../groupdocs.editor.options/xmlhighlightoptions/xmltagsfontsettings) { get; } | Отвечает за отображение шрифта XML‑тегов (угловые скобки с именами тегов) |

## Методы

| Имя | Описание |
| --- | --- |
| [ResetToDefault](../../groupdocs.editor.options/xmlhighlightoptions/resettodefault)() | Сбрасывает текущие настройки шрифта к их значениям по умолчанию |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
