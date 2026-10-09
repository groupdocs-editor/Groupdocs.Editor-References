---
title: "InvalidFormField"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa la actualización de nombres de campos de formulario no válidos durante la operación FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /es/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Representa la actualización de nombres de campos de formulario inválidos durante el
FormFieldManager.FixInvalidFormFieldNames
operación.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Inicializa una nueva instancia de la clase [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) con el nombre especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Obtiene el nombre original del campo del formulario que no puede modificarse fuera de |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | Obtiene o establece el nuevo nombre del campo del formulario después de la reparación. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | Obtiene o establece el nuevo nombre del campo del formulario después de la reparación. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Inicializa una nueva instancia de la clase [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) con el nombre especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | El nombre original del campo del formulario. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre original del campo del formulario que no puede modificarse fuera de
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Obtiene o establece el nuevo nombre del campo del formulario después de la reparación.
Este nombre elimina identificadores únicos duplicados con otros campos de formulario y establece un nombre de marcador único.

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


Obtiene o establece el nuevo nombre del campo del formulario después de la reparación.
Este nombre elimina identificadores únicos duplicados con otros campos de formulario y establece un nombre de marcador único.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

