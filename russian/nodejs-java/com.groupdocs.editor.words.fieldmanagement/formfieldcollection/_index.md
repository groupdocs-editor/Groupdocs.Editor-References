---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет коллекцию полей формы."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Представляет коллекцию полей формы.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Создаёт новый экземпляр класса [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Вставляет поле формы в коллекцию. |
|
|  | [get(String name)](#get-java.lang.String-) | Получает поле формы с указанным именем. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Получает поле формы с указанным именем и типом. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Создаёт новый экземпляр класса [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Возвращает перечислитель, который перебирает элементы коллекции.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> — перечислитель, который можно использовать для перебора элементов коллекции.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Вставляет поле формы в коллекцию.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | Поле формы для вставки. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Получает поле формы с указанным именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя поля формы. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Получает поле формы с указанным именем и типом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | Имя поля формы. |


T
: Тип поля формы.
|
| тип | java.lang.Class<T> |  |

**Returns:**
T — поле формы с указанным именем и типом, если найдено; иначе значение по умолчанию для типа.

