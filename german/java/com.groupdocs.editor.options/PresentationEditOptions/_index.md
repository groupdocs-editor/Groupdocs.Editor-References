---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht die Angabe benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten Präsentationsformate, die mit PowerPoint kompatibel sind."
type: docs
weight: 32
url: /de/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten
Präsentationsformate (PowerPoint‑kompatibel)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Ermöglicht die Angabe der Foliennummern, die zum Bearbeiten geöffnet werden sollen. |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Ermöglicht die Angabe der Foliennummern, die zum Bearbeiten geöffnet werden sollen. |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob die versteckten Folien einbezogen werden sollen oder nicht. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob die versteckten Folien einbezogen werden sollen oder nicht. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Ermöglicht die Angabe der Foliennummern, die zum Bearbeiten geöffnet werden sollen.


*** ** * ** ***

Die Foliennummer ist ein nullbasierter Index einer Folie, der es ermöglicht, eine bestimmte Folie aus einer Präsentation zur Bearbeitung anzugeben und auszuwählen. Ist sie kleiner als 0, wird die erste Folie ausgewählt (entspricht SlideNumber = 0). Ist sie größer als die Gesamtzahl der Folien in der Präsentation, wird die letzte Folie ausgewählt. Enthält die Eingabepraesentation nur eine einzelne Folie, wird diese Option ignoriert und diese einzelne Folie wird bearbeitet. Wird versucht, eine versteckte Folie zur Bearbeitung zu öffnen, während die ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) Option auf 'false' gesetzt ist, wird eine Ausnahme ausgelöst.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Ermöglicht die Angabe der Foliennummern, die zum Bearbeiten geöffnet werden sollen.


*** ** * ** ***

Die Foliennummer ist ein nullbasierter Index einer Folie, der es ermöglicht, eine bestimmte Folie aus einer Präsentation zur Bearbeitung anzugeben und auszuwählen. Ist sie kleiner als 0, wird die erste Folie ausgewählt (entspricht SlideNumber = 0). Ist sie größer als die Gesamtzahl der Folien in der Präsentation, wird die letzte Folie ausgewählt. Enthält die Eingabepraesentation nur eine einzelne Folie, wird diese Option ignoriert und diese einzelne Folie wird bearbeitet. Wird versucht, eine versteckte Folie zur Bearbeitung zu öffnen, während die ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) Option auf 'false' gesetzt ist, wird eine Ausnahme ausgelöst.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Gibt an, ob die versteckten Folien einbezogen werden sollen oder nicht. Standard ist
false - versteckte Folien werden nicht angezeigt und es wird eine Ausnahme ausgelöst, während
versucht, sie zu bearbeiten.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Gibt an, ob die versteckten Folien einbezogen werden sollen oder nicht. Standard ist
false - versteckte Folien werden nicht angezeigt und es wird eine Ausnahme ausgelöst, während
versucht, sie zu bearbeiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

