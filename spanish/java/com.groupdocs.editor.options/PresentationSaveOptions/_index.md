---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de presentación compatibles con PowerPoint"
type: docs
weight: 34
url: /es/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar Presentaciones
(compatibles con PowerPoint) documentos

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Este constructor sin parámetros crea una nueva instancia de PresentationSaveOptions con formato de salida PPTX (puede modificarse luego a través de |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) propiedad)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Crea una nueva instancia de PresentationSaveOptions con el |
formato de salida de Presentación obligatorio, mientras que todos los demás parámetros son
predeterminado
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
codificando el documento de Presentación resultante.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar y obtener la contraseña que se utilizará para codificar el documento de Presentación resultante. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Permite insertar una diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Permite insertar una diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Bandera booleana que especifica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por el |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propiedad, o debe inyectarse entre la diapositiva existente y la anterior, sin reemplazar su contenido.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Bandera booleana que especifica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por el |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propiedad, o debe inyectarse entre la diapositiva existente y la anterior, sin reemplazar su contenido.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permite especificar un formato de Presentación que se utilizará para guardar el documento |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Permite especificar un formato de Presentación que se utilizará para guardar el documento |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Permite especificar una matriz con números de diapositivas basados en 1 que deben eliminarse de la presentación durante su guardado, en caso de que la diapositiva editada se inserte en una presentación existente. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Permite especificar una matriz con números de diapositivas basados en 1 que deben eliminarse de la presentación durante su guardado, en caso de que la diapositiva editada se inserte en una presentación existente. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Este constructor sin parámetros crea una nueva instancia de PresentationSaveOptions con formato de salida PPTX (puede modificarse luego a través de
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) propiedad)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Crea una nueva instancia de PresentationSaveOptions con el
formato de salida de Presentación obligatorio, mientras que todos los demás parámetros son
predeterminado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Formato de salida obligatorio en el que se debe guardar el documento de Presentación |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
codificando el documento de Presentación resultante. Por defecto es NULL -
no se establecerá la contraseña. Establezca NULL o una cadena vacía para eliminarla
la contraseña, si se había establecido previamente.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar y obtener la contraseña que se utilizará para codificar el documento de Presentación resultante.
Por defecto es NULL - la contraseña no se establecerá. Establécela en NULL o en una cadena vacía para eliminar la contraseña, si se había establecido previamente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Permite insertar una diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado).
Slide number es un número basado en 1 que indica una diapositiva en la presentación cargada en la clase Editor. Si es 0 (valor predeterminado), se creará una nueva presentación con una sola diapositiva editada. Si es mayor o menor que cero, y existe una presentación válida cargada en la clase Editor, la diapositiva editada, almacenada dentro de la instancia de EditableDocument de entrada, se insertará en esta presentación.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Permite insertar una diapositiva editada en una presentación existente en lugar de crear una nueva presentación de una sola diapositiva (comportamiento predeterminado).
Slide number es un número basado en 1 que indica una diapositiva en la presentación cargada en la clase Editor. Si es 0 (valor predeterminado), se creará una nueva presentación con una sola diapositiva editada. Si es mayor o menor que cero, y existe una presentación válida cargada en la clase Editor, la diapositiva editada, almacenada dentro de la instancia de EditableDocument de entrada, se insertará en esta presentación.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Bandera booleana que especifica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por el
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propiedad, o debe inyectarse entre la diapositiva existente y la anterior, sin reemplazar su contenido.
Por defecto es false \\u2014 la diapositiva existente será reemplazada. Esta propiedad se ignora si el valor de
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) la propiedad está establecida en '0'.

<br />

*** ** * ** ***

Por defecto la diapositiva se reemplaza. Esto significa que si la presentación tiene 5 diapositivas, y SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, entonces la cuarta diapositiva será reemplazada por la nueva diapositiva editada, mientras que la cantidad total de diapositivas en la presentación (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en *true*, la nueva diapositiva editada se insertará como cuarta diapositiva, y todas las diapositivas posteriores se desplazarán al final: la cuarta diapositiva \"old\" pasa a ser la quinta, y la quinta pasa a ser la sexta, y la cantidad total de diapositivas en la presentación se incrementará en una, quedando en 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Bandera booleana que especifica si la diapositiva editada debe reemplazar la diapositiva existente en la presentación original en la posición especificada por el
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) propiedad, o debe inyectarse entre la diapositiva existente y la anterior, sin reemplazar su contenido.
Por defecto es false \\u2014 la diapositiva existente será reemplazada. Esta propiedad se ignora si el valor de
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) la propiedad está establecida en '0'.

<br />

*** ** * ** ***

Por defecto la diapositiva se reemplaza. Esto significa que si la presentación tiene 5 diapositivas, y SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, entonces la cuarta diapositiva será reemplazada por la nueva diapositiva editada, mientras que la cantidad total de diapositivas en la presentación (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en *true*, la nueva diapositiva editada se insertará como cuarta diapositiva, y todas las diapositivas posteriores se desplazarán al final: la cuarta diapositiva \"old\" pasa a ser la quinta, y la quinta pasa a ser la sexta, y la cantidad total de diapositivas en la presentación se incrementará en una, quedando en 6.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Permite especificar un formato de Presentación que se utilizará para guardar el documento

<br />

*** ** * ** ***

El formato de salida suele establecerse en el constructor de esta clase, porque es obligatorio. Esta propiedad permite obtener o modificar el formato de salida más tarde, cuando ya se ha creado una instancia de la clase [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions).

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Permite especificar un formato de Presentación que se utilizará para guardar el documento

<br />

*** ** * ** ***

El formato de salida suele establecerse en el constructor de esta clase, porque es obligatorio. Esta propiedad permite obtener o modificar el formato de salida más tarde, cuando ya se ha creado una instancia de la clase [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions).

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Permite especificar una matriz con números de diapositivas basados en 1 que deben eliminarse de la presentación durante su guardado, en caso de que la diapositiva editada se inserte en una presentación existente. Cuando la diapositiva editada se guarda no como una nueva presentación de una sola diapositiva (comportamiento predeterminado), sino que se guarda en una presentación existente (usando #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), también es posible eliminar diapositivas específicas de esa presentación indicando sus números en esta matriz. Por defecto esta matriz es  null  \\u2014 no se eliminará ninguna diapositiva. Sin embargo, cuando esta matriz no es nula y no está vacía, y contiene al menos un número de diapositiva válido, después de generar el documento Presentation de salida con el contenido de la diapositiva editada, las diapositivas con los números especificados se eliminarán de la presentación justo antes de escribir su contenido al flujo o archivo de salida. Los números de diapositiva en esta matriz son basados en 1, no en 0. Los números inválidos (menores que 1 o mayores que el número total de diapositivas) se ignorarán.


**Returns:**
int[] - Matriz de números de diapositivas basados en 1 para eliminar, o  null  si no se debe eliminar nada.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Permite especificar una matriz con números de diapositivas basados en 1 que deben eliminarse de la presentación durante su guardado, en caso de que la diapositiva editada se inserte en una presentación existente. Los números de diapositiva en esta matriz son basados en 1. Los números inválidos se ignorarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | Matriz de números de diapositivas basados en 1 para eliminar (puede ser  null  o estar vacía). |
|

