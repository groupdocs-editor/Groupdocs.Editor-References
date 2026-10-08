---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует все форматы WordProcessing. Включает следующие типы файлов"
type: docs
weight: 150
url: /ru/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Инкапсулирует все форматы обработки текста. Включает следующие типы файлов:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Подробнее о форматах обработки текста читайте [здесь](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Получает перечисляемую коллекцию всех [`WordProcessingFormats`](../wordprocessingformats). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Получает экземпляр указанного типа [`WordProcessingFormats`](../wordprocessingformats), имеющего заданное расширение файла. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Определяет, равен ли данный экземпляр указанному экземпляру [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Преобразует строку, представляющую расширение файла, в объект [`WordProcessingFormats`](../wordprocessingformats). |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Бинарный файловый формат MS Word 97-2007 (DOC) представляет документы, созданные Microsoft Word или другими программами обработки текста, в бинарном формате. Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Файлы Office Open XML WordProcessingML Macro-Enabled Document (DOCM) — это документы, созданные Microsoft Word 2007 или более поздних версий, с возможностью выполнения макросов. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) — широко известный формат документов Microsoft Word. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Шаблоны MS Word 97‑2007 (DOT) — это файлы шаблонов, созданные Microsoft Word и содержащие предварительно отформатированные настройки для создания дальнейших файлов DOC или DOCX. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) представляет собой файлы шаблонов, созданные в Microsoft Word 2007 или более поздних версиях. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) — это файлы шаблонов, созданные Microsoft Word и содержащие предварительно отформатированные настройки для создания последующих файлов DOCX. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML хранится в виде плоского XML‑файла вместо ZIP‑пакета. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Файлы Open Document Format Text Document (ODT) — это тип документов, создаваемых с помощью приложений для обработки текста, основанных на формате OpenDocument Text File. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) представляет собой шаблоны документов, генерируемые приложениями в соответствии со стандартом OpenDocument от OASIS. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) представляет метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML или WordML (.XML). |

### См. также

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
