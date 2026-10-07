---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для загрузки документов всех поддерживаемых форматов Presentation, таких как PPTX, PPTM, PPSX и т.д."
type: docs
weight: 33
url: /ru/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Позволяет указать пользовательские параметры для загрузки документов всех поддерживаемых
Форматы Presentation, такие как PPT(X), PPTM, PPS(X) и т.д.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытия документа Presentation, если он зашифрован.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытия документа Presentation, если он зашифрован.
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
открытия документа Presentation, если он зашифрован. Установите значение NULL или пустую строку
строку, чтобы удалить пароль.


*** ** * ** ***

По умолчанию это свойство имеет значение NULL — пароль не установлен. Если входной документ Presentation защищён паролем, пароль обязателен, и будет выброшено исключение, если пароль не указан или неверен. Если входной документ Presentation НЕ защищён паролем, но пароль установлен, он будет игнорироваться.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытия документа Presentation, если он зашифрован. Установите значение NULL или пустую строку
строку, чтобы удалить пароль.


*** ** * ** ***

По умолчанию это свойство имеет значение NULL — пароль не установлен. Если входной документ Presentation защищён паролем, пароль обязателен, и будет выброшено исключение, если пароль не указан или неверен. Если входной документ Presentation НЕ защищён паролем, но пароль установлен, он будет игнорироваться.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

