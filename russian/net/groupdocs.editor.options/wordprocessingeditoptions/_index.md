---
title: WordProcessingEditOptions
second_title: Справочник по API GroupDocs.Editor для .NET
description: Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов WordProcessing Wordsсовместимых таких как DOCX RTF ODT и т. д.
type: docs
weight: 970
url: /ru/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов WordProcessing (Words-совместимых), таких как DOC(X), RTF, ODT и т. д.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Создает и возвращает новый экземпляр класса WordProcessingEditOptions, в котором для всех параметров установлены значения по умолчанию |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Создает и возвращает новый экземпляр класса WordProcessingEditOptions с указанным разбиением на страницы и всеми остальными параметрами по умолчанию |

## Характеристики

| Имя | Описание |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Указывает, экспортируется ли языковая информация в HTML-разметку в форме HTML-атрибутов 'lang'. Этот параметр может быть полезен для двустороннего преобразования многоязычных документов. По умолчанию он отключен (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Позволяет включать или отключать нумерацию страниц в результирующем HTML-документе. По умолчанию отключено (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Получает или задает значение, указывающее, следует ли извлекать только те ресурсы шрифта, которые используются в текстовом содержимом документа. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Отвечает за извлечение ресурсов шрифта, которые используются во входном документе WordProcessing. По умолчанию не извлекает шрифты (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Позволяет указать имя класса, которое будет помещено в атрибуты class в каждом элементе HTML, представляющем некоторое поле во входном документе WordProcessing. По умолчанию NULL - атрибуты класса не применяются. |

### Смотрите также

* interface [IEditOptions](../ieditoptions)
* пространство имен [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->