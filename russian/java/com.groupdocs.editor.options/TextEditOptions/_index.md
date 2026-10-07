---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры загрузки простых текстовых TXT‑документов"
type: docs
weight: 39
url: /ru/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Позволяет указать пользовательские параметры для загрузки простых текстовых (TXT) документов

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Кодировка символов текстового документа, которая будет применена к его |
открытию
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Кодировка символов текстового документа, которая будет применена к его |
открытию
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Позволяет указать, как распознаются элементы нумерованных списков, когда документ |
импортируется из формата простого текста.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Позволяет указать, как распознаются элементы нумерованных списков, когда документ |
импортируется из формата простого текста.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Получает или задаёт предпочтительный вариант обработки ведущих пробелов. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Получает или задаёт предпочтительный вариант обработки ведущих пробелов. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Получает или задаёт предпочтительный вариант обработки завершающих пробелов. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Получает или задаёт предпочтительный вариант обработки завершающих пробелов. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. |
|
|  | [getDirection()](#getDirection--) | Позволяет указать направление потока текста во входном простом тексте |
документа.
|
|  | [setDirection(int value)](#setDirection-int-) | Позволяет указать направление потока текста во входном простом тексте |
документа.
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
открытию


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Кодировка символов текстового документа, которая будет применена к его
открытию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Позволяет указать, как распознаются элементы нумерованных списков, когда документ
импортированном из формата простого текста. Значение по умолчанию — true.


*** ** * ** ***

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами‑маркирами (например, "\\u2022", "\*", "-" или "o"). Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") в качестве символов.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Позволяет указать, как распознаются элементы нумерованных списков, когда документ
импортированном из формата простого текста. Значение по умолчанию — true.


*** ** * ** ***

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами‑маркирами (например, "\\u2022", "\*", "-" или "o"). Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") в качестве символов.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Получает или задаёт предпочтительный вариант обработки ведущих пробелов. По умолчанию
преобразует ведущие пробелы в левый отступ.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Получает или задаёт предпочтительный вариант обработки ведущих пробелов. По умолчанию
преобразует ведущие пробелы в левый отступ.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Получает или задаёт предпочтительный вариант обработки завершающих пробелов. По умолчанию
обрезает все завершающие пробелы.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Получает или задаёт предпочтительный вариант обработки завершающих пробелов. По умолчанию
обрезает все завершающие пробелы.


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

