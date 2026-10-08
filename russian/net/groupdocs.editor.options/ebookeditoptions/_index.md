---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать и настраивать пользовательские параметры для редактирования электронных книг во всех поддерживаемых форматах ePub, MOBI и AZW3."
type: docs
weight: 830
url: /ru/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

Позволяет задавать и настраивать пользовательские параметры для редактирования электронных книг во всех поддерживаемых форматах: ePub, MOBI и AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | Инициализирует новый экземпляр класса [`EbookEditOptions`](../ebookeditoptions), в котором все параметры установлены в значения по умолчанию. |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | Инициализирует новый экземпляр класса [`EbookEditOptions`](../ebookeditoptions) с указанным режимом пагинации. |

## Свойства

| Имя | Описание |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | Указывает, экспортируется ли информация о языке в разметку HTML в виде атрибутов 'lang'. Этот параметр может быть полезен для обратного преобразования многоязычных документов. По умолчанию отключён (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | Позволяет включать или отключать пагинацию в результирующем HTML‑документе. По умолчанию отключена (`false`). |

### Замечания

Поддерживаемые форматы e‑book:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Электронная публикация)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Формат Kindle 8t)

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
