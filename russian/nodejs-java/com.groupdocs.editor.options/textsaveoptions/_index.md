---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет задавать пользовательские параметры для создания и сохранения простых текстовых TXT‑документов"
type: docs
weight: 41
url: /ru/nodejs-java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Позволяет задавать пользовательские параметры для создания и сохранения простого текста (TXT)
документы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Кодировка символов текстового документа, которая будет применена к его |
сохранению
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Кодировка символов текстового документа, которая будет применена к его |
сохранению
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при |
экспорте в формате простого текста.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при |
экспорте в формате простого текста
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Указывает, должна ли программа пытаться сохранять макет таблиц |
при сохранении в формате простого текста.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Указывает, должна ли программа пытаться сохранять макет таблиц |
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
сохранению


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Кодировка символов текстового документа, которая будет применена к его
сохранению


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при
экспорте в формате простого текста. По умолчанию 'false' \u2014 не добавлять BiDi‑метки.


**Returns:**
boolean —
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при
экспорте в формате простого текста


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Указывает, должна ли программа пытаться сохранять макет таблиц
при сохранении в формате простого текста. Значение по умолчанию — false.


**Returns:**
boolean —
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Указывает, должна ли программа пытаться сохранять макет таблиц
при сохранении в формате простого текста. Значение по умолчанию — false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

