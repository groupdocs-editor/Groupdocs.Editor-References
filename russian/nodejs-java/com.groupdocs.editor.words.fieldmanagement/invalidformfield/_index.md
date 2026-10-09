---
title: "InvalidFormField"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет обновление недействительных имен полей формы во время операции FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /ru/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Представляет обновление недопустимых имен полей формы во время
FormFieldManager.FixInvalidFormFieldNames
операция.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Инициализирует новый экземпляр класса [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) с указанным именем. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Получает оригинальное имя поля формы, которое нельзя изменить за пределами |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Получает или задает новое имя поля формы после исправления. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Получает или задает новое имя поля формы после исправления. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Инициализирует новый экземпляр класса [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) с указанным именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Исходное имя поля формы. |
|

### getName() {#getName--}
```
public final String getName()
```


Получает оригинальное имя поля формы, которое нельзя изменить за пределами
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Получает или задает новое имя поля формы после исправления.
Это имя удаляет дублирующие уникальные идентификаторы с другими полями формы и задает уникальное имя закладки.

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


Получает или задает новое имя поля формы после исправления.
Это имя удаляет дублирующие уникальные идентификаторы с другими полями формы и задает уникальное имя закладки.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

