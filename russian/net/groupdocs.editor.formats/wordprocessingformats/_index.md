---
title: WordProcessingFormats
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инкапсулирует все форматы WordProcessing. Включает следующие типы файлов Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Подробнее о форматах обработки текстовздесьhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /ru/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Инкапсулирует все форматы WordProcessing. Включает следующие типы файлов: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Подробнее о форматах обработки текстов[здесь](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Возвращает расширение (без ведущей точки) этого формата WordProcessing в нижнем регистре |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Возвращает код MIME для этого формата |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Возвращает формальное полное имя этого формата WordProcessing |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Возвращает экземпляр[`WordProcessingFormats`](../wordprocessingformats) структура, связанная с указанным расширением имени файла, или выдает исключение, если расширение не может быть правильно проанализировано |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Определяет, равен ли этот экземпляр другому указанному IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Определяет, равен ли этот экземпляр другому указанному объекту, предположительно упакованному WordProcessingFormats |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Определяет, равен ли этот экземпляр другому указанному экземпляру WordProcessingFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Возвращает хеш-код, неизменяемый для данного экземпляра |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Возвращает имя этого конкретного формата, аналогично свойству «Имя» |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Проверяет два заданных экземпляра WordProcessingFormats на равенство |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Возвращает значение байта из базового поля указанного WordProcessingFormats instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Проверяет два заданных экземпляра WordProcessingFormats на неравенство |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Формат двоичных файлов MS Word 97-2007 (DOC) представляет собой документы, сгенерированные Microsoft Word или другими текстовыми редакторами, в двоичном формате. Узнайте больше об этом формате файлов.[здесь](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Файлы Office Open XML WordProcessingML Macro-Enabled Document (DOCM) представляют собой документы Microsoft Word 2007 или более поздней версии с возможностью запуска макросов. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) — широко известный формат документов Microsoft Word. Представленный в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого двоичного файла на комбинацию XML и двоичных файлов. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Шаблон MS Word 97-2007 — это файлы шаблонов, созданные Microsoft Word для предварительно отформатированных настроек для создания дополнительных файлов DOC или DOCX. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Шаблон Office Open XML WordprocessingML с поддержкой макросов (DOTM) представляет собой файл шаблона, созданный с помощью Microsoft Word 2007 или более поздней версии. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) — это файлы шаблонов, созданные Microsoft Word с предварительно отформатированными настройками для создания дополнительных файлов DOCX. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML хранится в простом файле XML вместо ZIP-пакета |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Файлы текстового документа в формате Open Document (ODT) — это тип документов, созданных с помощью приложений для обработки текстов, основанных на формате текстового файла OpenDocument. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Шаблоны текстовых документов в формате Open Document (OTT) представляют собой шаблоны документов, созданные приложениями в соответствии со стандартным форматом OASIS OpenDocument. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) представляет собой метод кодирования форматированного текста и графики для использования в приложениях. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Формат Microsoft Office Word 2003 XML — WordProcessingML или WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Возвращает внутренний класс, который предоставляет перечисляемые возможности для всех существующих форматов WordProcessing |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Реализует универсальный интерфейс IEnumerable, который включает возможность foreach для WordProcessingFormats type |

### Примечания

Коды MIME взяты из указанных ресурсов: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Смотрите также

* interface [IDocumentFormat](../idocumentformat)
* пространство имен [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
