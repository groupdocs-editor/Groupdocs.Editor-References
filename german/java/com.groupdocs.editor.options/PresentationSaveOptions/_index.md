---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht die Angabe benutzerdefinierter Optionen zum Erzeugen und Speichern von Präsentations-PowerPoint-kompatiblen Dokumenten"
type: docs
weight: 34
url: /de/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Ermöglicht die Angabe benutzerdefinierter Optionen zum Erzeugen und Speichern von Präsentationen
(PowerPoint-kompatible) Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Dieser parameterlose Konstruktor erstellt eine neue Instanz von PresentationSaveOptions mit dem PPTX-Ausgabeformat (kann anschließend über |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) Eigenschaft)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Erstellt eine neue Instanz von PresentationSaveOptions mit angegebenen |
obligatorischen Präsentationsausgabeformat, während alle anderen Parameter
Standard
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Kodierung des resultierenden Präsentationsdokuments.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht die Angabe, Änderung und den Erhalt des Passworts, das für die Kodierung des resultierenden Präsentationsdokuments verwendet wird. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Ermöglicht das Einfügen einer bearbeiteten Folie in eine bestehende Präsentation anstelle der Erstellung einer neuen Ein‑Folien‑Präsentation (Standardverhalten). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Ermöglicht das Einfügen einer bearbeiteten Folie in eine bestehende Präsentation anstelle der Erstellung einer neuen Ein‑Folien‑Präsentation (Standardverhalten). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Boolesches Flag, das angibt, ob die bearbeitete Folie die vorhandene Folie in der Originalpräsentation an der durch die |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) Eigenschaft, oder sie sollte zwischen der vorhandenen Folie und der vorherigen eingefügt werden, ohne deren Inhalt zu ersetzen.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Boolesches Flag, das angibt, ob die bearbeitete Folie die vorhandene Folie in der Originalpräsentation an der durch die |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) Eigenschaft, oder sie sollte zwischen der vorhandenen Folie und der vorherigen eingefügt werden, ohne deren Inhalt zu ersetzen.
|
|  | [getOutputFormat()](#getOutputFormat--) | Ermöglicht die Angabe eines Präsentationsformats, das zum Speichern des Dokuments verwendet wird. |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Ermöglicht die Angabe eines Präsentationsformats, das zum Speichern des Dokuments verwendet wird. |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Ermöglicht die Angabe eines Arrays mit einsbasierten Foliennummern, die beim Speichern aus der Präsentation gelöscht werden sollen, falls die bearbeitete Folie in eine bestehende Präsentation eingefügt wird. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Ermöglicht die Angabe eines Arrays mit einsbasierten Foliennummern, die beim Speichern aus der Präsentation gelöscht werden sollen, falls die bearbeitete Folie in eine bestehende Präsentation eingefügt wird. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Dieser parameterlose Konstruktor erstellt eine neue Instanz von PresentationSaveOptions mit dem PPTX-Ausgabeformat (kann anschließend über
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) Eigenschaft)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Erstellt eine neue Instanz von PresentationSaveOptions mit angegebenen
obligatorischen Präsentationsausgabeformat, während alle anderen Parameter
Standard


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Obligatorisches Ausgabeformat, in dem das Präsentationsdokument gespeichert werden soll. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Kodierung des resultierenden Präsentationsdokuments. Standardmäßig ist NULL -
Passwort wird nicht gesetzt. Auf NULL oder leere Zeichenfolge setzen, um zu entfernen
das Passwort, falls es zuvor gesetzt wurde.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht die Angabe, Änderung und den Erhalt des Passworts, das für die Kodierung des resultierenden Präsentationsdokuments verwendet wird.
Standardmäßig ist NULL - das Passwort wird nicht gesetzt. Auf NULL oder leere Zeichenfolge setzen, um das Passwort zu entfernen, falls es zuvor gesetzt wurde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Ermöglicht das Einfügen einer bearbeiteten Folie in eine bestehende Präsentation anstelle der Erstellung einer neuen Ein‑Folien‑Präsentation (Standardverhalten).
Die Foliennummer ist eine einsbasierte Nummer einer Folie in der Präsentation, die in der Editor‑Klasse geladen ist. Wenn sie 0 (Standardwert) ist, wird die neue Präsentation mit einer einzigen bearbeiteten Folie erstellt. Wenn sie größer oder kleiner als null ist und eine gültige Präsentation in der Editor‑Klasse geladen ist, wird die bearbeitete Folie, die in der Eingabe‑EditableDocument‑Instanz gespeichert ist, in diese Präsentation eingefügt.

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


Ermöglicht das Einfügen einer bearbeiteten Folie in eine bestehende Präsentation anstelle der Erstellung einer neuen Ein‑Folien‑Präsentation (Standardverhalten).
Die Foliennummer ist eine einsbasierte Nummer einer Folie in der Präsentation, die in der Editor‑Klasse geladen ist. Wenn sie 0 (Standardwert) ist, wird die neue Präsentation mit einer einzigen bearbeiteten Folie erstellt. Wenn sie größer oder kleiner als null ist und eine gültige Präsentation in der Editor‑Klasse geladen ist, wird die bearbeitete Folie, die in der Eingabe‑EditableDocument‑Instanz gespeichert ist, in diese Präsentation eingefügt.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Boolesches Flag, das angibt, ob die bearbeitete Folie die vorhandene Folie in der Originalpräsentation an der durch die
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) Eigenschaft, oder sie sollte zwischen der vorhandenen Folie und der vorherigen eingefügt werden, ohne deren Inhalt zu ersetzen.
Standardmäßig ist false \u2014 die vorhandene Folie wird ersetzt. Diese Eigenschaft wird ignoriert, wenn der Wert von
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) Eigenschaft ist auf '0' gesetzt.

<br />

*** ** * ** ***

Standardmäßig wird die Folie ersetzt. Das bedeutet, dass wenn die gegebene Präsentation 5 Folien hat und SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, die 4. Folie durch die neue bearbeitete Folie ersetzt wird, während die Gesamtzahl der Folien in der Präsentation (5) unverändert bleibt. Wenn jedoch der Wert dieser Eigenschaft auf  *true*  gesetzt ist, wird die neue bearbeitete Folie als 4. Folie eingefügt und alle nachfolgenden Folien werden zum Ende verschoben: \"alte\" 4. Folie wird zur 5. Folie, und die 5. wird zur 6. Folie, und die Gesamtzahl der Folien in der Präsentation wird um eins erhöht und beträgt 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Boolesches Flag, das angibt, ob die bearbeitete Folie die vorhandene Folie in der Originalpräsentation an der durch die
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) Eigenschaft, oder sie sollte zwischen der vorhandenen Folie und der vorherigen eingefügt werden, ohne deren Inhalt zu ersetzen.
Standardmäßig ist false \u2014 die vorhandene Folie wird ersetzt. Diese Eigenschaft wird ignoriert, wenn der Wert von
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) Eigenschaft ist auf '0' gesetzt.

<br />

*** ** * ** ***

Standardmäßig wird die Folie ersetzt. Das bedeutet, dass wenn die gegebene Präsentation 5 Folien hat und SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, die 4. Folie durch die neue bearbeitete Folie ersetzt wird, während die Gesamtzahl der Folien in der Präsentation (5) unverändert bleibt. Wenn jedoch der Wert dieser Eigenschaft auf  *true*  gesetzt ist, wird die neue bearbeitete Folie als 4. Folie eingefügt und alle nachfolgenden Folien werden zum Ende verschoben: \"alte\" 4. Folie wird zur 5. Folie, und die 5. wird zur 6. Folie, und die Gesamtzahl der Folien in der Präsentation wird um eins erhöht und beträgt 6.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Ermöglicht die Angabe eines Präsentationsformats, das zum Speichern des Dokuments verwendet wird.

<br />

*** ** * ** ***

Das Ausgabeformat wird normalerweise im Konstruktor dieser Klasse festgelegt, da es obligatorisch ist. Diese Eigenschaft ermöglicht es, das Ausgabeformat später zu erhalten oder zu ändern, wenn eine Instanz der Klasse [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) bereits erstellt wurde.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Ermöglicht die Angabe eines Präsentationsformats, das zum Speichern des Dokuments verwendet wird.

<br />

*** ** * ** ***

Das Ausgabeformat wird normalerweise im Konstruktor dieser Klasse festgelegt, da es obligatorisch ist. Diese Eigenschaft ermöglicht es, das Ausgabeformat später zu erhalten oder zu ändern, wenn eine Instanz der Klasse [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) bereits erstellt wurde.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Ermöglicht das Angeben eines Arrays mit 1‑basierten Foliennummern, die beim Speichern der Präsentation gelöscht werden sollen, falls die bearbeitete Folie in eine vorhandene Präsentation eingefügt wird. Wenn die bearbeitete Folie nicht als neue Einzelfolien‑Präsentation gespeichert wird (Standardverhalten), sondern stattdessen in eine vorhandene Präsentation gespeichert wird (unter Verwendung von #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), ist es ebenfalls möglich, bestimmte Folien aus dieser Präsentation zu löschen, indem deren Nummern in diesem Array angegeben werden. Standardmäßig ist dieses Array null  \\u2014 es werden keine Folien gelöscht. Wenn dieses Array jedoch nicht null und nicht leer ist und mindestens eine gültige Foliennummer enthält, werden nach der Erzeugung des Ausgabedokuments Presentation mit dem Inhalt der bearbeiteten Folie die Folien mit den angegebenen Nummern unmittelbar vor dem Schreiben des Inhalts in den Ausgabestream oder die Datei aus der Präsentation gelöscht. Foliennummern in diesem Array sind 1‑basiert, nicht 0‑basiert. Ungültige Nummern (kleiner als 1 oder größer als die Gesamtzahl der Folien) werden ignoriert.


**Returns:**
int[] - Array von 1‑basierten Foliennummern zum Löschen, oder  null  wenn nichts gelöscht werden soll.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Ermöglicht das Angeben eines Arrays mit 1‑basierten Foliennummern, die beim Speichern der Präsentation gelöscht werden sollen, falls die bearbeitete Folie in eine vorhandene Präsentation eingefügt wird. Foliennummern in diesem Array sind 1‑basiert. Ungültige Nummern werden ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Array von 1‑basierten Foliennummern zum Löschen (kann  null  oder leer sein). |
|

