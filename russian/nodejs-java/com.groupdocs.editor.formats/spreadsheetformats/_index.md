---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Инкапсулирует все двоичные, XML и текстовые форматы электронных таблиц, исключая все текстовые форматы, основанные на разделителях, с разделителями вроде CSV, TSV, разделённых точкой с запятой и т.п., в которых можно сохранять книгу."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

Инкапсулирует все двоичные, XML и текстовые форматы электронных таблиц (исключая все текстовые форматы, основанные на разделителях, такие как CSV, TSV, форматы с разделителем‑точка с запятой и т.д.), в которые можно сохранять книгу.
Включает следующие форматы:
[Dif](../../com.groupdocs.editor.formats/spreadsheetformats#Dif),
[Fods](../../com.groupdocs.editor.formats/spreadsheetformats#Fods),
[Ods](../../com.groupdocs.editor.formats/spreadsheetformats#Ods),
[Sxc](../../com.groupdocs.editor.formats/spreadsheetformats#Sxc),
[Xlam](../../com.groupdocs.editor.formats/spreadsheetformats#Xlam),
[Xls](../../com.groupdocs.editor.formats/spreadsheetformats#Xls),
[Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsb),
[Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsm),
[Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsx),
[Xlt](../../com.groupdocs.editor.formats/spreadsheetformats#Xlt),
[Xltm](../../com.groupdocs.editor.formats/spreadsheetformats#Xltm),
[Xltx](../../com.groupdocs.editor.formats/spreadsheetformats#Xltx).
Узнайте больше о форматах электронных таблиц [здесь](../https://wiki.fileformat.com/spreadsheet).

## Поля

| Поле | Описание |
| --- | --- |
|  | [Xls](#Xls) | Бинарный файловый формат Excel 97-2003 (XLS). |
|
|  | [Xlt](#Xlt) | Шаблон Excel 97-2003 (XLT). |
|
|  | [Xlsx](#Xlsx) | Электронная таблица Office Open XML без макросов (XLSX). |
|
|  | [Xlsm](#Xlsm) | Электронная таблица Office Open XML с поддержкой макросов (XLSM). |
|
|  | [Xlsb](#Xlsb) | Бинарная электронная таблица Excel (XLSB). |
|
|  | [Xltx](#Xltx) | Шаблон Office Open XML без макросов (XLTX). |
|
|  | [Xltm](#Xltm) | Шаблон Office Open XML с поддержкой макросов (XLTM). |
|
|  | [Xlam](#Xlam) | Надстройка Excel (XLAM). |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML — формат XML Microsoft Office Excel 2002 и Excel 2003. |
|
|  | [Ods](#Ods) | Электронная таблица OpenDocument (ODS). |
|
|  | [Fods](#Fods) | Плоская электронная таблица OpenDocument (FODS). |
|
|  | [Sxc](#Sxc) | StarOffice или OpenOffice.org Calc XML Spreadsheet (SXC). |
|
|  | [Dif](#Dif) | Формат обмена данными (DIF). |
|
|  | [Csv](#Csv) | Значения, разделённые запятыми (CSV). |
|
|  | [Tsv](#Tsv) | Значения, разделённые табуляцией (TSV). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAll()](#getAll--) | Получает перечисляемую коллекцию всех [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Получает экземпляр указанного типа [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats), имеющий указанное расширение файла. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Преобразует строку, представляющую расширение файла, в объект [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats). |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Бинарный файловый формат Excel 97-2003 (XLS).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Шаблон Excel 97-2003 (XLT).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Электронная таблица Office Open XML без макросов (XLSX).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Электронная таблица Office Open XML с поддержкой макросов (XLSM).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Бинарная электронная таблица Excel (XLSB).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Шаблон Office Open XML без макросов (XLTX).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Шаблон Office Open XML с поддержкой макросов (XLTM).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Надстройка Excel (XLAM).


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML — формат XML Microsoft Office Excel 2002 и Excel 2003.


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


Электронная таблица OpenDocument (ODS).
Узнайте больше об этом формате файла
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Плоская электронная таблица OpenDocument (FODS).


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice или OpenOffice.org Calc XML Spreadsheet (SXC).


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


Формат обмена данными (DIF).


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


Значения, разделённые запятыми (CSV).
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


Значения, разделённые табуляцией (TSV).
Узнайте больше об этом формате файла
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


Получает перечисляемую коллекцию всех [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).
Значение: IEnumerable{SpreadsheetFormats}, содержащий все экземпляры [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


Получает экземпляр указанного типа [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats), имеющий указанное расширение файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла формата документа. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


Преобразует строку, представляющую расширение файла, в объект [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла для конвертации. Если расширение содержит несколько точек, используется часть после последней точки. |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.

