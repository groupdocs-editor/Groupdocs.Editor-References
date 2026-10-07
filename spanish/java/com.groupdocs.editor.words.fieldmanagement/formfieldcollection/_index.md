---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una colección de campos de formulario."
type: docs
weight: 15
url: /es/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

Representa una colección de campos de formulario.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | Inicializa una nueva instancia de la clase [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | Inserta un campo de formulario en la colección. |
|
|  | [get(String name)](#get-java.lang.String-) | Obtiene el campo de formulario con el nombre especificado. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | Obtiene el campo de formulario con el nombre y tipo especificados. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


Inicializa una nueva instancia de la clase [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection).


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


Devuelve un enumerador que recorre la colección.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - Un enumerador que puede usarse para recorrer la colección.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


Inserta un campo de formulario en la colección.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | El campo de formulario a insertar. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


Obtiene el campo de formulario con el nombre especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | El nombre del campo de formulario. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


Obtiene el campo de formulario con el nombre y tipo especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | El nombre del campo de formulario. |


T
: El tipo del campo de formulario.
|
| tipo | java.lang.Class<T> |  |

**Returns:**
T - El campo de formulario con el nombre y tipo especificados, si se encuentra; de lo contrario, el valor predeterminado para el tipo.

