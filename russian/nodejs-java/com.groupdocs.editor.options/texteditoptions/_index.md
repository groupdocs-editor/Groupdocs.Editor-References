---
title: "TextEditOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет указать пользовательские параметры загрузки текстовых документов TXT"
type: docs
weight: 39
url: /ru/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Позволяет задавать пользовательские параметры для загрузки простых текстовых (TXT) документов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Кодировка символов текстового документа, которая будет применена к его |
открытие
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Кодировка символов текстового документа, которая будет применена к его |
открытие
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Позволяет указать, как распознаются элементы нумерованных списков, когда документ |
импортируется из формата простого текста.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Позволяет указать, как распознаются элементы нумерованных списков, когда документ |
импортируется из формата простого текста.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Получает или задаёт предпочтительный вариант обработки начального пробела. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Получает или задаёт предпочтительный вариант обработки начального пробела. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Получает или задаёт предпочтительный вариант обработки конечного пробела. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Получает или задаёт предпочтительный вариант обработки конечного пробела. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [getDirection()](#getDirection--) | Позволяет указать направление потока текста во входном простом тексте |
документе.
|
|  | [setDirection(int value)](#setDirection-int-) | Позволяет указать направление потока текста во входном простом тексте |
документе.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Кодировка символов текстового документа, которая будет применена к его
открытие


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Кодировка символов текстового документа, которая будет применена к его
открытие


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Позволяет указать, как распознаются элементы нумерованных списков, когда документ
импортируется из формата простого текста. Значение по умолчанию — true.


*** ** * ** ***

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами маркеров (например, "\\u2022", "\*", "-" или "o"). Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") в качестве символов.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Позволяет указать, как распознаются элементы нумерованных списков, когда документ
импортируется из формата простого текста. Значение по умолчанию — true.


*** ** * ** ***

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами маркеров (например, "\\u2022", "\*", "-" или "o"). Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") в качестве символов.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Получает или задаёт предпочтительный вариант обработки начального пробела. По умолчанию
преобразует начальные пробелы в левый отступ.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Получает или задаёт предпочтительный вариант обработки начального пробела. По умолчанию
преобразует начальные пробелы в левый отступ.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Получает или задаёт предпочтительный вариант обработки конечного пробела. По умолчанию
удаляет все конечные пробелы.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Получает или задаёт предпочтительный вариант обработки конечного пробела. По умолчанию
удаляет все конечные пробелы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По
по умолчанию отключено (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По
по умолчанию отключено (false).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Позволяет указать направление потока текста во входном простом тексте
документ. По умолчанию слева направо.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Позволяет указать направление потока текста во входном простом тексте
документ. По умолчанию слева направо.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

