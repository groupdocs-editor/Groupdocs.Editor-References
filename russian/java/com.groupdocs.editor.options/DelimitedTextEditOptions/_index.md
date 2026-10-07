---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Параметры загрузки текстовых документов Spreadsheet, CSV, табличных и т.д., которые используют разделитель"
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Параметры загрузки текстовых документов Spreadsheet (CSV, табличных и т.д.),
которые используют разделитель (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Создаёт экземпляр класса параметров для разделённого текста с обязательным |
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
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Получает или задаёт значение, указывающее, является ли строка в текстовых |
документ преобразуется в данные даты.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Получает или задаёт значение, указывающее, является ли строка в текстовых |
документ преобразуется в данные даты.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Получает или задаёт значение, указывающее, является ли строка в текстовых |
документ преобразуется в числовые данные.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Получает или задаёт значение, указывающее, является ли строка в текстовых |
документ преобразуется в числовые данные.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Определяет, следует ли рассматривать последовательные разделители как один. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Определяет, следует ли рассматривать последовательные разделители как один. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти во время обработки входного документа, |
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти во время обработки входного документа, |
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Создаёт экземпляр класса параметров для разделённого текста с обязательным
разделитель (delimiter)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | разделитель | java.lang.String | Обязательный разделитель (delimiter), который не может быть NULL или пустым |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Позволяет указать строковый разделитель (delimiter) для текстовых
Документы Spreadsheet


**Returns:**
java.lang.String
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

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Получает или задаёт значение, указывающее, является ли строка в текстовых
Документ преобразуется в данные даты. По умолчанию false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Получает или задаёт значение, указывающее, является ли строка в текстовых
Документ преобразуется в данные даты. По умолчанию false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Получает или задаёт значение, указывающее, является ли строка в текстовых
Документ преобразуется в числовые данные. По умолчанию false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Получает или задаёт значение, указывающее, является ли строка в текстовых
Документ преобразуется в числовые данные. По умолчанию false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Определяет, следует ли рассматривать последовательные разделители как один. По
по умолчанию false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Определяет, следует ли рассматривать последовательные разделители как один. По
по умолчанию false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти во время обработки входного документа,
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти. Полезно при обработке огромных документов и
при возникновении OutOfMemoryException. По умолчанию false (оптимизация памяти
отключено ради лучшей производительности).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти во время обработки входного документа,
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти. Полезно при обработке огромных документов и
при возникновении OutOfMemoryException. По умолчанию false (оптимизация памяти
отключено ради лучшей производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

