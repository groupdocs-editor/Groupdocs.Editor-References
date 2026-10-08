---
title: "FormatFamilies"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет различные семейства форматов, доступные в системе."
type: docs
weight: 110
url: /ru/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

Представляет различные семейства форматов, доступные в системе.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | Представляет семейство форматов eBook. Узнайте больше о формате Mobi [здесь](https://docs.fileformat.com/ebook/mobi/), о формате AZW3 [здесь](https://docs.fileformat.com/ebook/azw3/), и о формате ePub [здесь](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | Представляет семейство форматов Email. Узнайте больше о формате электронной почты [здесь](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Представляет семейство форматов Fixed Layout. Различные приложения для просмотра или публикации документов позволяют пользователям открывать (Adobe Acrobat, XPS Viewer), а иногда и редактировать (Adobe InDesign) документы определённых форматов. Эти приложения обычно создают так называемые «fixed-page» документы. Такой формат документа точно описывает, где размещается содержимое документа на каждой странице. Внутри форматы PDF или XPS содержат описание каждой страницы, а также инструкции по рисованию, определяющие расположение содержимого на странице. Это аналогично форматам изображений, описывающим, где отображается содержимое в растровой или векторной форме. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Представляет семейство форматов Presentation. Узнайте больше о форматах презентаций [здесь](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Представляет семейство форматов Spreadsheet. Все бинарные, XML и текстовые форматы таблиц (за исключением всех текстовых форматов с разделителями, таких как CSV, TSV, форматы с разделителем‑точка с запятой и т.д.), в которых можно сохранять рабочую книгу. |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Представляет семейство текстовых форматов. Инкапсулирует все текстовые (основанные на тексте) форматы, включая разметку (XML, HTML) и другие. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Представляет семейство форматов обработки текста. Узнайте больше о форматах обработки текста [здесь](https://wiki.fileformat.com/word-processing). |

### См. также

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
