---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов электронных таблиц, совместимых с Excel"
type: docs
weight: 35
url: /ru/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых
Форматы электронных таблиц (совместимые с Excel)

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Позволяет указать 0‑based индекс листа (вкладки) входного документа |
Документ электронной таблицы, который должен быть преобразован в HTML (см
примечания).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Позволяет указать 0‑based индекс листа (вкладки) входного документа |
Документ электронной таблицы, который должен быть преобразован в HTML (см
примечания).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Позволяет исключить скрытые листы во входном документе электронной таблицы, так что |
они будут полностью игнорированы.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Позволяет исключить скрытые листы во входном документе электронной таблицы, так что |
они будут полностью игнорированы.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Если включено, пустые соседние горизонтальные ячейки из входного документа электронной таблицы будут |
отображаться в редактируемом HTML‑документе как объединённые в одну ячейку с соответствующим
атрибутом colspan.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Если включено, HTML‑таблица в полученном HTML‑документе будет содержать пустую нижнюю скрытую строку с |
нулевой высотой и пустыми ячейками, где указана только ширина.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Позволяет указать 0‑based индекс листа (вкладки) входного документа
Документ электронной таблицы, который должен быть преобразован в HTML (см
примечания).


*** ** * ** ***

Большинство документов электронных таблиц поддерживают концепцию вкладок, т.е. они могут быть многовкладочными. С другой стороны, формат HTML не поддерживает такую структуру. Поэтому GroupDocs.Editor может преобразовать в HTML только одну конкретную вкладку входного документа, и эта опция позволяет её указать. Индекс вкладки является 0‑based, отрицательные значения запрещены. Если указанный индекс превышает количество всех вкладок, будет выброшено исключение. Если входной документ электронной таблицы содержит только одну вкладку, эта опция будет игнорироваться. Значение по умолчанию — 0 (первая вкладка).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Позволяет указать 0‑based индекс листа (вкладки) входного документа
Документ электронной таблицы, который должен быть преобразован в HTML (см
примечания).


*** ** * ** ***

Большинство документов электронных таблиц поддерживают концепцию вкладок, т.е. они могут быть многовкладочными. С другой стороны, формат HTML не поддерживает такую структуру. Поэтому GroupDocs.Editor может преобразовать в HTML только одну конкретную вкладку входного документа, и эта опция позволяет её указать. Индекс вкладки является 0‑based, отрицательные значения запрещены. Если указанный индекс превышает количество всех вкладок, будет выброшено исключение. Если входной документ электронной таблицы содержит только одну вкладку, эта опция будет игнорироваться. Значение по умолчанию — 0 (первая вкладка).

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Позволяет исключить скрытые листы во входном документе электронной таблицы, так что
они будут полностью игнорированы. По умолчанию false — скрытые листы
доступны и обрабатываются как обычные.


*** ** * ** ***

Некоторые бинарные форматы электронных таблиц (например, XLSX) поддерживают концепцию скрытых листов (вкладок). Документ такого формата, если в нём более одного листа, может содержать дополнительные скрытые листы. По умолчанию такие скрытые листы доступны для обработки, но с этой опцией их можно игнорировать, как будто этих скрытых листов нет. Когда эта опция включена, нельзя выбрать скрытый лист с помощью свойства ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int)).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Позволяет исключить скрытые листы во входном документе электронной таблицы, так что
они будут полностью игнорированы. По умолчанию false — скрытые листы
доступны и обрабатываются как обычные.


*** ** * ** ***

Некоторые бинарные форматы электронных таблиц (например, XLSX) поддерживают концепцию скрытых листов (вкладок). Документ такого формата, если в нём более одного листа, может содержать дополнительные скрытые листы. По умолчанию такие скрытые листы доступны для обработки, но с этой опцией их можно игнорировать, как будто этих скрытых листов нет. Когда эта опция включена, нельзя выбрать скрытый лист с помощью свойства ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int)).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Если включено, пустые соседние горизонтальные ячейки из входного документа электронной таблицы будут
отображаться в редактируемом HTML‑документе как объединённые в одну ячейку с соответствующим
атрибут colspan. По умолчанию отключено (false).


По умолчанию GroupDocs.Editor преобразует таблицу из входного документа электронной таблицы в выходной
HTML‑документ, сохраняя каждую ячейку. Однако документы электронных таблиц могут быть разреженными \\u2014 они
могут содержать огромное количество "пустых областей", где много ячеек пусты. Эта опция, когда
включена, объединяет такие пустые ячейки в одну с атрибутом colspan в элементе TD,
и таким образом может значительно уменьшить размер создаваемой HTML‑разметки.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Если включено, HTML‑таблица в полученном HTML‑документе будет содержать пустую нижнюю скрытую строку с
ноль высоты и пустые ячейки, где указана только ширина. Эта строка с пустыми ячейками содержит
точные значения ширины для каждого столбца и улучшает обратное преобразование из HTML в Spreadsheet. By
по умолчанию включено (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

