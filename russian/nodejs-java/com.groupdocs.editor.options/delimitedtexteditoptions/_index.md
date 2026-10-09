---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Параметры загрузки текстовых документов Spreadsheet, таких как CSV, табличные и т.д., которые используют разделитель"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Параметры загрузки текстовых документов Spreadsheet (CSV, табличные и т.д.),
которые используют разделитель (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated-values

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Создаёт экземпляр класса параметров для разделённого текста с обязательным |
разделитель (разделитель)
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Позволяет указать строковый разделитель (разделитель) для текстовых |
Документы электронных таблиц
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Позволяет указать строковый разделитель (разделитель) для текстовых |
Документы электронных таблиц
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Получает или задает значение, указывающее, должна ли строка в текстовом |
документе быть преобразована в тип даты.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Получает или задает значение, указывающее, должна ли строка в текстовом |
документе быть преобразована в тип даты.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Получает или задает значение, указывающее, должна ли строка в текстовом |
документе быть преобразована в числовой тип.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Получает или задает значение, указывающее, должна ли строка в текстовом |
документе быть преобразована в числовой тип.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Определяет, следует ли рассматривать последовательные разделители как один. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Определяет, следует ли рассматривать последовательные разделители как один. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти во время обработки входного документа, |
что может ухудшить производительность в некоторых особых случаях, но с другой
стороны уменьшает использование памяти.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти во время обработки входного документа, |
что может ухудшить производительность в некоторых особых случаях, но с другой
стороны уменьшает использование памяти.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Создаёт экземпляр класса параметров для разделённого текста с обязательным
разделитель (разделитель)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | разделитель | java.lang.String | Обязательный разделитель (delimiter), который не может быть NULL или пустым |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Позволяет указать строковый разделитель (разделитель) для текстовых
Документы электронных таблиц


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Позволяет указать строковый разделитель (разделитель) для текстовых
Документы электронных таблиц


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Получает или задает значение, указывающее, должна ли строка в текстовом
документ преобразуется в тип даты. По умолчанию false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Получает или задает значение, указывающее, должна ли строка в текстовом
документ преобразуется в тип даты. По умолчанию false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Получает или задает значение, указывающее, должна ли строка в текстовом
документ преобразуется в числовой тип. По умолчанию false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Получает или задает значение, указывающее, должна ли строка в текстовом
документ преобразуется в числовой тип. По умолчанию false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Определяет, следует ли рассматривать последовательные разделители как один. По
по умолчанию — false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Определяет, следует ли рассматривать последовательные разделители как один. По
по умолчанию — false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти во время обработки входного документа,
что может ухудшить производительность в некоторых особых случаях, но с другой
стороны уменьшает использование памяти. Полезно при обработке огромных документов и
при возникновении OutOfMemoryException. По умолчанию false (оптимизация памяти
отключена ради лучшей производительности).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти во время обработки входного документа,
что может ухудшить производительность в некоторых особых случаях, но с другой
стороны уменьшает использование памяти. Полезно при обработке огромных документов и
при возникновении OutOfMemoryException. По умолчанию false (оптимизация памяти
отключена ради лучшей производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

