---
title: "PresentationEditOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para editar documentos de todos los formatos de Presentación compatibles con PowerPoint"
type: docs
weight: 32
url: /es/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para editar documentos de todos los compatibles
Formatos de Presentación (compatibles con PowerPoint)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Permite especificar los números de diapositiva que deben abrirse para edición |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Permite especificar los números de diapositiva que deben abrirse para edición |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si las diapositivas ocultas deben incluirse o no. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si las diapositivas ocultas deben incluirse o no. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Permite especificar los números de diapositiva que deben abrirse para edición


*** ** * ** ***

El número de diapositiva es un índice basado en cero de una diapositiva, que permite especificar y seleccionar una diapositiva particular de una presentación para editar. Si es menor que 0, se seleccionará la primera diapositiva (igual que SlideNumber = 0). Si es mayor que la cantidad total de diapositivas en la presentación, se seleccionará la última diapositiva. Si la presentación de entrada contiene solo una diapositiva, esta opción se ignorará y esa única diapositiva se editará. Si se intenta abrir para edición una diapositiva oculta, mientras la opción ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) está establecida en 'false', se lanzará una excepción.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Permite especificar los números de diapositiva que deben abrirse para edición


*** ** * ** ***

El número de diapositiva es un índice basado en cero de una diapositiva, que permite especificar y seleccionar una diapositiva particular de una presentación para editar. Si es menor que 0, se seleccionará la primera diapositiva (igual que SlideNumber = 0). Si es mayor que la cantidad total de diapositivas en la presentación, se seleccionará la última diapositiva. Si la presentación de entrada contiene solo una diapositiva, esta opción se ignorará y esa única diapositiva se editará. Si se intenta abrir para edición una diapositiva oculta, mientras la opción ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) está establecida en 'false', se lanzará una excepción.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Especifica si las diapositivas ocultas deben incluirse o no. Por defecto es
false - las diapositivas ocultas no se muestran y se lanzará una excepción mientras
se intenta editarlas.


**Returns:**
booleano
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Especifica si las diapositivas ocultas deben incluirse o no. Por defecto es
false - las diapositivas ocultas no se muestran y se lanzará una excepción mientras
se intenta editarlas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

