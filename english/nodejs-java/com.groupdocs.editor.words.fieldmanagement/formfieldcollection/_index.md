---
title: FormFieldCollection
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents a collection of form fields.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Represents a collection of form fields.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormFieldCollection()](#FormFieldCollection--) | Initializes a new instance of the [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) class. |
## Methods

| Method | Description |
| --- | --- |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Inserts a form field into the collection. |
| [get(String name)](#get-java.lang.String-) | Gets the form field with the specified name. |
| [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Gets the form field with the specified name and type. |
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Initializes a new instance of the [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) class.

### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - An enumerator that can be used to iterate through the collection.
### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Inserts a form field into the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | The form field to insert. |

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Gets the form field with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the form field. |

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .
### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Gets the form field with the specified name and type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the form field.

 T : The type of the form field. |
| type | java.lang.Class<T> |  |

**Returns:**
T - The form field with the specified name and type, if found; otherwise, the default value for the type.
