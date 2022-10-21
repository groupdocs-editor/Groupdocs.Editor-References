---
title: SpreadsheetFormats
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инкапсулирует все двоичные XML и текстовые форматы электронных таблиц за исключением всех текстовых форматов на основе разделителей с разделителями такими как CSV TSV разделенных точкой с запятой и т. д. в которых можно сохранить книгу. Включает следующие форматы Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Подробнее о форматах электронных таблицздесьhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /ru/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Инкапсулирует все двоичные, XML и текстовые форматы электронных таблиц (за исключением всех текстовых форматов на основе разделителей с разделителями, такими как CSV, TSV, разделенных точкой с запятой и т. д.), в которых можно сохранить книгу. Включает следующие форматы: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Подробнее о форматах электронных таблиц[здесь](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Возвращает расширение (без начального символа точки) этого формата электронной таблицы в нижнем регистре |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Возвращает код MIME для этого формата |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Возвращает формальное полное имя этого формата электронной таблицы |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Возвращает экземпляр[`SpreadsheetFormats`](../spreadsheetformats)структура, связанная с указанным расширением имени файла, или выдает исключение, если расширение не может быть правильно проанализировано |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Определяет, равен ли этот экземпляр другому указанному IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Определяет, равен ли этот экземпляр другому указанному объекту, который предположительно имеет коробочную форму SpreadsheetFormats |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Определяет, равен ли этот экземпляр другому указанному SpreadsheetFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Возвращает хеш-код, неизменяемый для данного экземпляра |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Проверяет два заданных экземпляра SpreadsheetFormats на равенство |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Проверяет два заданных экземпляра SpreadsheetFormats на неравенство |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Документы со значениями, разделенными запятыми (CSV), представляют собой обычный текст, который содержит записи данных со значениями, разделенными запятыми. Каждая строка в файле CSV — это новая запись из набора записей, содержащихся в файле. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Формат обмена данными (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — хранится как один несжатый XML-документ |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | Электронная таблица OpenDocument (ODS) означает формат документа электронной таблицы OpenDocument, который может редактировать пользователь. Данные хранятся в файле ODF в виде строк и столбцов. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 и Excel 2003 XML Format |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | Электронная таблица StarOffice или OpenOffice.org Calc XML (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Формат файла значений, разделенных табуляцией (TSV), представляет данные, разделенные табуляцией, в текстовом формате. Формат файла, аналогичный CSV, используется для организации данных в структурированном виде для импорта и экспорта между различными приложениями. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Надстройка Excel (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Формат двоичных файлов Excel 97-2003 (XLS) представляет собой файлы, которые могут быть созданы Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Двоичная рабочая книга Excel (XLSB) определяет формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое рабочей книги Excel. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Рабочая книга Office Open XML с поддержкой макросов (XLSM) — это тип файлов электронных таблиц, поддерживающих макросы. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Рабочая книга Office Open XML без макросов (XLSX) представляет собой документы, представленные корпорацией Майкрософт в выпуске Microsoft Office 2007. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Шаблон Excel 97-2003 (XLT) представляет собой файлы шаблонов, созданные с помощью Microsoft Excel, приложения для работы с электронными таблицами, входящего в состав пакета Microsoft Office. Microsoft Office 97-2003 поддерживает создание новых файлов XLT, а также их открытие. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Шаблон Office Open XML с поддержкой макросов (XLTM) представляет файлы, созданные Microsoft Excel, как файлы шаблонов с поддержкой макросов. Файлы XLTM аналогичны XLTX по структуре, за исключением того, что последний не поддерживает создание файлов шаблонов с макросами. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Файл шаблона Office Open XML без макросов (XLTX) представляет собой шаблон Microsoft Excel, основанный на спецификациях формата файла Office OpenXML. Он используется для создания стандартного файла шаблона, который можно использовать для создания файлов XLSX с теми же настройками, что и в файле XLTX. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Возвращает внутренний класс, который предоставляет перечисляемые возможности для всех существующих форматов электронных таблиц |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Реализует общий интерфейс IEnumerable, который включает возможность foreach для SpreadsheetFormats type |

### Смотрите также

* interface [IDocumentFormat](../idocumentformat)
* пространство имен [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
