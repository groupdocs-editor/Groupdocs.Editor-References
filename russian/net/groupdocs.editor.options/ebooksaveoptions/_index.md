---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать пользовательские параметры для создания и сохранения документа во всех поддерживаемых форматах eBook: ePub, MOBI и AZW3."
type: docs
weight: 840
url: /ru/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документа во всех поддерживаемых форматах электронных книг: ePub, MOBI и AZW3.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | Этот конструктор без параметров создаёт новый экземпляр EbookSaveOptions с форматом вывода ePub (может быть изменён позже через свойство [`OutputFormat`](./outputformat)). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | Создает новый экземпляр [`EbookSaveOptions`](../ebooksaveoptions) с указанным обязательным форматом вывода e-Book, при этом все остальные параметры имеют значения по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | Указывает, следует ли экспортировать встроенные и пользовательские свойства документа в результирующий файл. Значение по умолчанию — `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | Указывает формат результирующего e-Book файла: IDPF ePub, MOBI или AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | Указывает максимальный уровень заголовков, при котором файл e-Book будет разбит. Значение по умолчанию — `2`. Установка значения `0` отключит разбивку, и всё содержимое e-Book будет включено в один пакет внутри результирующего файла. |

### Замечания

Поддерживаемые форматы e‑book:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Электронная публикация)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Формат Kindle 8t)

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
