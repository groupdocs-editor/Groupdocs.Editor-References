---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Содержит параметры для создания и сохранения текстовых документов таблиц (CSV, табуляция и т.д.), использующих разделитель."
type: docs
weight: 11
url: /ru/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Содержит параметры для создания и сохранения текстовых документов Spreadsheet
(CSV, табличные и др.), которые используют разделитель (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Этот конструктор без параметров создает новый экземпляр DelimitedTextSaveOptions с точкой с запятой (;) в качестве разделителя по умолчанию (может быть изменён затем через |
Разделитель
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) свойство)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Создаёт экземпляр класса параметров для разделённого текста с обязательным |
разделитель (delimiter)
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Позволяет указать строковый разделитель (delimiter) для текстовых |
Документы Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Позволяет указать строковый разделитель (delimiter) для текстовых |
Документы Spreadsheet
|
|  | [getEncoding()](#getEncoding--) | Позволяет задать кодировку для текстового документа Spreadsheet. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Позволяет задать кодировку для текстового документа Spreadsheet. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Указывает, следует ли обрезать ведущие пустые строки и столбцы, как |
это делает MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Указывает, следует ли обрезать ведущие пустые строки и столбцы, как |
это делает MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Указывает, следует ли выводить разделители для пустой строки. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Указывает, следует ли выводить разделители для пустой строки. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Этот конструктор без параметров создает новый экземпляр DelimitedTextSaveOptions с точкой с запятой (;) в качестве разделителя по умолчанию (может быть изменён затем через
Разделитель
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) свойство)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Создаёт экземпляр класса параметров для разделённого текста с обязательным
разделитель (delimiter)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | разделитель | java.lang.String | Строковый разделитель (delimiter) для текстовых документов Spreadsheet |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Позволяет указать строковый разделитель (delimiter) для текстовых
Документы Spreadsheet


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Позволяет указать строковый разделитель (delimiter) для текстовых
Документы Spreadsheet


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Позволяет задать кодировку для текстового документа Spreadsheet. По
умолчанию (и если не указано) — UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Позволяет задать кодировку для текстового документа Spreadsheet. По
умолчанию (и если не указано) — UTF8.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Указывает, следует ли обрезать ведущие пустые строки и столбцы, как
это делает MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Указывает, следует ли обрезать ведущие пустые строки и столбцы, как
это делает MS Excel


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Указывает, следует ли выводить разделители для пустой строки. По умолчанию
значение — false, что означает, что содержимое пустой строки будет пустым.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Указывает, следует ли выводить разделители для пустой строки. По умолчанию
значение — false, что означает, что содержимое пустой строки будет пустым.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

