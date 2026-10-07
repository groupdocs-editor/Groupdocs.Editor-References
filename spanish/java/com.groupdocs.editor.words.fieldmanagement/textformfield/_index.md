---
title: "TextFormField"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un campo de formulario que acepta una entrada de texto."
type: docs
weight: 20
url: /es/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

Representa un campo de formulario que acepta una entrada de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) con la hoja de estilo y el nombre especificados. |
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
|  | [getType()](#getType--) | Obtiene el tipo del campo de formulario, que siempre es FormFieldType.Text para esta clase. |
|
|  | [getLocaleId()](#getLocaleId--) | Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Obtiene o establece el ID de configuración regional del campo de formulario, que representa la cultura o la configuración regional asociada al campo de formulario. |
|
|  | [getStatusText()](#getStatusText--) | Obtiene o establece el texto de estado asociado al campo de formulario, |
la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtiene o establece el texto de estado asociado al campo de formulario, |
la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco.
|
|  | [getHelpText()](#getHelpText--) | Obtiene o establece el texto de ayuda asociado al campo de formulario, |
la fuente del texto que se muestra en un cuadro de mensaje cuando un campo de formulario tiene el foco y el usuario presiona F1.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Obtiene o establece el texto de ayuda asociado al campo de formulario, |
la fuente del texto que se muestra en un cuadro de mensaje cuando un campo de formulario tiene el foco y el usuario presiona F1.
|
|  | [getValue()](#getValue--) | Obtiene o establece el valor del campo de formulario, que representa la entrada de texto. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | Obtiene o establece el valor del campo de formulario, que representa la entrada de texto. |
|
|  | [getMaxLength()](#getMaxLength--) | Obtiene o establece la longitud máxima de la entrada para el campo de formulario. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Obtiene o establece la longitud máxima de la entrada para el campo de formulario. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Inicializa una nueva instancia de la clase [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) con la hoja de estilo y el nombre especificados.


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
### getType() {#getType--}
```
public final int getType()
```


Obtiene el tipo del campo de formulario, que siempre es FormFieldType.Text para esta clase.


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
>  textField.LocaleId = new CultureInfo("en-US").LCID;
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
>  textField.LocaleId = new CultureInfo("en-US").LCID;
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


Obtiene o establece el texto de estado asociado al campo de formulario,
la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco.

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


Obtiene o establece el texto de estado asociado al campo de formulario,
la fuente del texto que se muestra en la barra de estado cuando un campo de formulario tiene el foco.

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


Obtiene o establece el texto de ayuda asociado al campo de formulario,
la fuente del texto que se muestra en un cuadro de mensaje cuando un campo de formulario tiene el foco y el usuario presiona F1.

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


Obtiene o establece el texto de ayuda asociado al campo de formulario,
la fuente del texto que se muestra en un cuadro de mensaje cuando un campo de formulario tiene el foco y el usuario presiona F1.

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
public final String getValue()
```


Obtiene o establece el valor del campo de formulario, que representa la entrada de texto.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Obtiene o establece el valor del campo de formulario, que representa la entrada de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Obtiene o establece la longitud máxima de la entrada para el campo de formulario.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Obtiene o establece la longitud máxima de la entrada para el campo de formulario.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

