---
title: "PresentationEditOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la modifica di documenti di tutti i formati di presentazione compatibili con PowerPoint supportati"
type: docs
weight: 32
url: /it/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per la modifica di tutti i documenti supportati
Formati di presentazione (compatibili con PowerPoint)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Consente di specificare i numeri delle diapositive da aprire per la modifica |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Consente di specificare i numeri delle diapositive da aprire per la modifica |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se le diapositive nascoste devono essere incluse o meno. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se le diapositive nascoste devono essere incluse o meno. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Consente di specificare i numeri delle diapositive da aprire per la modifica


*** ** * ** ***

Il numero della diapositiva è un indice basato su zero di una diapositiva, che consente di specificare e selezionare una diapositiva particolare da una presentazione per la modifica. Se è inferiore a 0, verrà selezionata la prima diapositiva (come SlideNumber = 0). Se è superiore al numero totale di diapositive nella presentazione, verrà selezionata l'ultima diapositiva. Se la presentazione di input contiene una sola diapositiva, questa opzione verrà ignorata e verrà modificata quella singola diapositiva. Se si tenta di aprire per la modifica una diapositiva nascosta, mentre l'opzione ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) è impostata su 'false', verrà generata un'eccezione.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Consente di specificare i numeri delle diapositive da aprire per la modifica


*** ** * ** ***

Il numero della diapositiva è un indice basato su zero di una diapositiva, che consente di specificare e selezionare una diapositiva particolare da una presentazione per la modifica. Se è inferiore a 0, verrà selezionata la prima diapositiva (come SlideNumber = 0). Se è superiore al numero totale di diapositive nella presentazione, verrà selezionata l'ultima diapositiva. Se la presentazione di input contiene una sola diapositiva, questa opzione verrà ignorata e verrà modificata quella singola diapositiva. Se si tenta di aprire per la modifica una diapositiva nascosta, mentre l'opzione ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) è impostata su 'false', verrà generata un'eccezione.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifica se le diapositive nascoste devono essere incluse o meno. Il valore predefinito è
false - le diapositive nascoste non sono mostrate e verrà generata un'eccezione mentre
si tenta di modificarle.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifica se le diapositive nascoste devono essere incluse o meno. Il valore predefinito è
false - le diapositive nascoste non sono mostrate e verrà generata un'eccezione mentre
si tenta di modificarle.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

