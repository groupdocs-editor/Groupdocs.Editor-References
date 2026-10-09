---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет указать пользовательские параметры для загрузки документов всех поддерживаемых форматов презентаций, таких как PPTX, PPTM, PPSX и т.д."
type: docs
weight: 33
url: /ru/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Позволяет указать пользовательские параметры для загрузки документов всех поддерживаемых
Форматы презентаций, такие как PPT(X), PPTM, PPS(X) и т.д.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытие документа Presentation, если он закодирован.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытие документа Presentation, если он закодирован.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытие документа Presentation, если он закодирован. Установите значение NULL или пустое
строка для удаления пароля.


*** ** * ** ***

По умолчанию это свойство имеет значение NULL \u2014 пароль не установлен. Если входной документ Presentation защищён паролем, пароль обязателен, и будет выброшено исключение, если пароль не указан или неверен. Если входной документ Presentation НЕ защищён паролем, но пароль установлен, он будет игнорироваться.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытие документа Presentation, если он закодирован. Установите значение NULL или пустое
строка для удаления пароля.


*** ** * ** ***

По умолчанию это свойство имеет значение NULL \u2014 пароль не установлен. Если входной документ Presentation защищён паролем, пароль обязателен, и будет выброшено исключение, если пароль не указан или неверен. Если входной документ Presentation НЕ защищён паролем, но пароль установлен, он будет игнорироваться.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

