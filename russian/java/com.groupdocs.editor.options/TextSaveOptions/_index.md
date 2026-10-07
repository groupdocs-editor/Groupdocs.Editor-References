---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для создания и сохранения простых текстовых документов TXT"
type: docs
weight: 41
url: /ru/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Позволяет указать пользовательские параметры для создания и сохранения простого текста (TXT)
документы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Кодировка символов текстового документа, которая будет применена к его |
сохранения
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Кодировка символов текстового документа, которая будет применена к его |
сохранения
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при |
экспорте в формате простого текста.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при |
экспорт в формате простого текста
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Указывает, должен ли программа пытаться сохранить макет таблиц |
при сохранении в формате простого текста.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Указывает, должен ли программа пытаться сохранить макет таблиц |
при сохранении в формате простого текста.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Кодировка символов текстового документа, которая будет применена к его
сохранения


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Кодировка символов текстового документа, которая будет применена к его
сохранения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при
экспорт в формате простого текста. По умолчанию — 'false' \\u2014 не добавлять BiDi‑метки.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при
экспорт в формате простого текста


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Указывает, должен ли программа пытаться сохранить макет таблиц
при сохранении в формате простого текста. Значение по умолчанию — false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Указывает, должен ли программа пытаться сохранить макет таблиц
при сохранении в формате простого текста. Значение по умолчанию — false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

