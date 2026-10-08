---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для редактирования документов всех поддерживаемых форматов WordProcessing, совместимых с Words, таких как DOCX, RTF, ODT и т.д."
type: docs
weight: 1200
url: /ru/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Позволяет задавать пользовательские параметры для редактирования документов всех поддерживаемых форматов обработки текста (совместимых с Words), таких как DOC(X), RTF, ODT и т.д.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Создаёт и возвращает новый экземпляр класса WordProcessingEditOptions, где все параметры установлены в значения по умолчанию. |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Создаёт и возвращает новый экземпляр класса WordProcessingEditOptions с указанной пагинацией и всеми другими параметрами, установленными по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Указывает, экспортируется ли информация о языке в разметку HTML в виде атрибутов 'lang'. Эта опция может быть полезна для двустороннего преобразования многоязычных документов. По умолчанию она отключена (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По умолчанию отключено (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Получает или задаёт значение, указывающее, извлекать ли только ресурсы шрифтов, используемые в текстовом содержимом документа. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Отвечает за извлечение ресурсов шрифтов, используемых во входном документе WordProcessing. По умолчанию не извлекает никакие шрифты (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Позволяет указать имя класса, которое будет помещено в атрибуты 'class' каждого HTML‑элемента, представляющего какое‑то поле во входном документе WordProcessing. По умолчанию равно NULL — атрибуты 'class' не применяются. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | Определяет, где хранить данные стилей и форматирования входного документа WordProcessing: во внешней таблице стилей (`false`) или как встроенные стили в разметке HTML (`true`). По умолчанию используются внешние стили (`false`). |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
