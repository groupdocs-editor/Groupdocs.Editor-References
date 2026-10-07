---
title: "DropDownFormField"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un campo de formulario que muestra una lista desplegable."
type: docs
weight: 14
url: /es/java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

Representa un campo de formulario que muestra una lista desplegable.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) con la hoja de estilo y el nombre especificados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Obtiene la hoja de estilo aplicada al campo de formulario. |
|
|  | [getReadonly()](#getReadonly--) | Obtiene o establece un valor que indica si el campo de formulario es de solo lectura. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Obtiene o establece un valor que indica si el campo de formulario es de solo lectura. |
|
|  | [getName()](#getName--) | Obtiene el nombre del campo de formulario. |
|
|  | [getSelectedIndex()](#getSelectedIndex--) | Obtiene o establece el índice del elemento seleccionado en la lista desplegable. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | Obtiene o establece el índice del elemento seleccionado en la lista desplegable. |
|
|  | [getType()](#getType--) | Obtiene el tipo del campo de formulario, que siempre es FormFieldType.DropDown para esta clase. |
|
|  | [getLocaleId()](#getLocaleId--) | Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario. |
|
|  | [getStatusText()](#getStatusText--) | Obtiene o establece el texto de estado asociado al campo de formulario, la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtiene o establece el texto de estado asociado al campo de formulario, la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco. |
|
|  | [getHelpText()](#getHelpText--) | Obtiene o establece el texto de ayuda asociado al campo de formulario, la fuente del texto que se muestra en un cuadro de mensaje cuando el campo de formulario tiene el foco y el usuario pulsa F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtiene o establece el texto de ayuda asociado al campo de formulario, la fuente del texto que se muestra en un cuadro de mensaje cuando el campo de formulario tiene el foco y el usuario pulsa F1. |
|
|  | [getValue()](#getValue--) | Obtiene o establece el valor del campo de formulario, que representa la lista de opciones en la lista desplegable. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | Obtiene o establece el valor del campo de formulario, que representa la lista de opciones en la lista desplegable. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


Inicializa una nueva instancia de la clase [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) con la hoja de estilo y el nombre especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | hoja de estilo | java.lang.String | La hoja de estilo a aplicar al campo de formulario. |
|
|  | nombre | java.lang.String | El nombre del campo de formulario. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Obtiene la hoja de estilo aplicada al campo de formulario.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Obtiene o establece un valor que indica si el campo de formulario es de solo lectura.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Obtiene o establece un valor que indica si el campo de formulario es de solo lectura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre del campo de formulario.


**Returns:**
java.lang.String
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


Obtiene o establece el índice del elemento seleccionado en la lista desplegable.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


Obtiene o establece el índice del elemento seleccionado en la lista desplegable.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getType() {#getType--}
```
public final int getType()
```


Obtiene el tipo del campo de formulario, que siempre es FormFieldType.DropDown para esta clase.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La propiedad LocaleId especifica un identificador de configuración regional (LCID) que corresponde a una cultura o región particular.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

La propiedad LocaleId especifica un identificador de configuración regional (LCID) que corresponde a una cultura o región particular.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Obtiene o establece el texto de estado asociado al campo de formulario, la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco.

<br />

*** ** * ** ***

Si se establece en  false , el texto de estado no se aplicará.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Obtiene o establece el texto de estado asociado al campo de formulario, la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco.

<br />

*** ** * ** ***

Si se establece en  false , el texto de estado no se aplicará.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Obtiene o establece el texto de ayuda asociado al campo de formulario, la fuente del texto que se muestra en un cuadro de mensaje cuando el campo de formulario tiene el foco y el usuario pulsa F1.

<br />

*** ** * ** ***

Si se establece en  false , el texto de ayuda no se aplicará.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Obtiene o establece el texto de ayuda asociado al campo de formulario, la fuente del texto que se muestra en un cuadro de mensaje cuando el campo de formulario tiene el foco y el usuario pulsa F1.

<br />

*** ** * ** ***

Si se establece en  false , el texto de ayuda no se aplicará.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final List<String> getValue()
```


Obtiene o establece el valor del campo de formulario, que representa la lista de opciones en la lista desplegable.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


Obtiene o establece el valor del campo de formulario, que representa la lista de opciones en la lista desplegable.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.String> |  |

