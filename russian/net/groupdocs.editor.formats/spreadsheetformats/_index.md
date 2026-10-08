---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует все бинарные, XML и текстовые форматы таблиц, исключая все текстовые форматы с разделителями, такие как CSV, TSV, форматы с разделителем‑точка с запятой и т.д., в которых можно сохранять рабочую книгу. Включает следующие форматы Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Узнайте больше о форматах таблиц здесьhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /ru/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Инкапсулирует все бинарные, XML и текстовые форматы таблиц (исключая все текстовые форматы с разделителями, такие как CSV, TSV, форматы с разделителем‑точка с запятой и т.д.), в которых можно сохранять рабочую книгу. Включает следующие форматы: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Узнайте больше о форматах таблиц [здесь](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Получает перечисляемую коллекцию всех [`SpreadsheetFormats`](../spreadsheetformats). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Получает экземпляр указанного типа [`SpreadsheetFormats`](../spreadsheetformats), имеющего заданное расширение файла. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Определяет, равен ли данный экземпляр указанному экземпляру [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Преобразует строку, представляющую расширение файла, в объект [`SpreadsheetFormats`](../spreadsheetformats). |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Значения, разделённые запятыми (CSV). Подробнее о этом формате файла читайте [здесь](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Формат обмена данными (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Плоский OpenDocument Spreadsheet (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — формат XML Microsoft Office Excel 2002 и Excel 2003. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice или OpenOffice.org Calc XML Spreadsheet (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Значения, разделённые табуляцией (TSV). Подробнее о этом формате файла читайте [здесь](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Дополнение Excel (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Бинарный файловый формат Excel 97-2003 (XLS). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Бинарная рабочая книга Excel (XLSB). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Рабочая книга Office Open XML с поддержкой макросов (XLSM). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Рабочая книга Office Open XML без макросов (XLSX). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Шаблон Excel 97-2003 (XLT). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Шаблон Office Open XML с поддержкой макросов (XLTM). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Шаблон Office Open XML без макросов (XLTX). Подробнее о этом формате файла читайте [здесь](https://wiki.fileformat.com/spreadsheet/xltx). |

### См. также

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
