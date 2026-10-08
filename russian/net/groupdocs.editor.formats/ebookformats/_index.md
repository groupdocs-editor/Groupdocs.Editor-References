---
title: "EBookFormats"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует все форматы электронных книг. Включает следующие типы файлов Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /ru/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

Инкапсулирует все форматы электронных книг. Включает следующие типы файлов: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | Получает перечисляемую коллекцию всех [`EBookFormats`](../ebookformats). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Возвращает экземпляр указанного типа [`EBookFormats`](../ebookformats), имеющего заданное расширение файла. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Определяет, равен ли данный экземпляр указанному экземпляру [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | Преобразует строку, представляющую расширение файла, в объект [`EBookFormats`](../ebookformats). |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, также известный как Kindle Format 8 (KF8), является модифицированной версией цифрового формата электронных книг AZW, разработанной для устройств Amazon Kindle. Этот формат улучшает старые файлы AZW. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Формат Electronic Publication (IDPF ePub) — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и потребителей. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI — это название формата, разработанного для MobiPocket Reader. Также называется PRC, AZW. В настоящее время Amazon использует его с немного иной схемой DRM и называет AZW. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/ebook/mobi/). |

### Замечания

Узнайте больше о формате Mobi [здесь](https://docs.fileformat.com/ebook/mobi/), о формате AZW3 [здесь](https://docs.fileformat.com/ebook/azw3/), и о формате ePub [здесь](https://docs.fileformat.com/ebook/epub/).

### См. также

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
