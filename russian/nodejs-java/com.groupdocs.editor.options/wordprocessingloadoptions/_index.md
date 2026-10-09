---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Содержит параметры для загрузки совместимых с WordProcessing документов, таких как DOCX, RTF, ODT и т.д."
type: docs
weight: 45
url: /ru/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Содержит параметры для загрузки документов WordProcessing (совместимых с Word), таких как
DOC(X), RTF, ODT и т.д. в класс Editor

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытия документа WordProcessing, если он зашифрован.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытия документа WordProcessing, если он зашифрован.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытие документа WordProcessing, если он закодирован. Установите в NULL или пустую строку
строка, чтобы не использовать пароль (значение по умолчанию).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытие документа WordProcessing, если он закодирован. Установите в NULL или пустую строку
строка, чтобы не использовать пароль (значение по умолчанию).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

