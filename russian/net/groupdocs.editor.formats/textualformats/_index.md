---
title: "TextualFormats"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует все текстовые форматы, основанные на тексте, включая разметку XML, HTML и другие. Включает следующие форматы Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /ru/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Инкапсулирует все текстовые (text-based) форматы, включая разметку (XML, HTML) и другие. Включает следующие форматы: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Получает перечисляемую коллекцию всех [`TextualFormats`](../textualformats). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Получает экземпляр указанного типа [`TextualFormats`](../textualformats), имеющий указанное расширение файла. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Определяет, равен ли данный экземпляр указанному экземпляру [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Преобразует строку, представляющую расширение файла, в объект [`TextualFormats`](../textualformats). |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help — это проприетарный бинарный формат онлайн‑справки Microsoft, состоящий из набора HTML‑страниц, индекса и других средств навигации. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Документ HyperText Markup Language (HTML) — это расширение для веб‑страниц, созданных для отображения в браузерах. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) — открытый стандартный формат файла для обмена данными, использующий человекочитаемый текст для хранения и передачи данных. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown — это облегчённый язык разметки для создания форматированного текста с помощью обычного текстового редактора. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME‑инкапсуляция агрегированных HTML‑документов — это формат архива веб‑страниц, используемый для объединения в одном компьютерном файле HTML‑кода и сопутствующих ресурсов. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Текстовый документ (TXT) представляет собой документ, содержащий обычный текст в виде строк. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Документ eXtensible Markup Language (XML), похожий на HTML, но отличающийся использованием тегов для определения объектов. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/web/xml). |

### См. также

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
