---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht die Angabe benutzerdefinierter Optionen zum Erzeugen und Speichern von Spreadsheet‑Excel‑konformen Dokumenten"
type: docs
weight: 37
url: /de/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Ermöglicht die Angabe benutzerdefinierter Optionen zum Erzeugen und Speichern von Spreadsheet
(Excel‑konforme) Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Dieser parameterlose Konstruktor erstellt eine neue Instanz von SpreadsheetSaveOptions mit dem XLSX‑Ausgabeformat (kann anschließend über |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) Eigenschaft)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Erstellt eine neue Instanz von SpreadsheetSaveOptions mit dem angegebenen obligatorischen |
Spreadsheet‑Ausgabeformat, während alle anderen Parameter Standardwerte haben
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das |
verwendet, um das erzeugte Spreadsheet‑Dokument zu kodieren, falls dieses Dokumentformat
unterstützt Passwortschutz.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das |
verwendet, um das erzeugte Spreadsheet‑Dokument zu kodieren, falls dieses Dokumentformat
unterstützt Passwortschutz.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Ermöglicht das Einfügen eines bearbeiteten Arbeitsblatts in eine Kopie eines bestehenden Spreadsheet |
statt ein neues ein‑Arbeitsblatt‑Spreadsheet zu erstellen (Standard
Verhalten).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Ermöglicht das Einfügen eines bearbeiteten Arbeitsblatts in eine Kopie eines bestehenden Spreadsheet |
statt ein neues ein‑Arbeitsblatt‑Spreadsheet zu erstellen (Standard
Verhalten).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Boolesches Flag, das angibt, ob das bearbeitete Arbeitsblatt das |
bestehende Arbeitsblatt im ursprünglichen Spreadsheet an der durch
die

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
Eigenschaft, oder es sollte zwischen dem bestehenden Arbeitsblatt und
dem vorherigen eingefügt werden, ohne dessen Inhalt zu ersetzen.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Boolesches Flag, das angibt, ob das bearbeitete Arbeitsblatt das |
bestehende Arbeitsblatt im ursprünglichen Spreadsheet an der durch
die

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
Eigenschaft, oder es sollte zwischen dem bestehenden Arbeitsblatt und
dem vorherigen eingefügt werden, ohne dessen Inhalt zu ersetzen.
|
|  | [getOutputFormat()](#getOutputFormat--) | Ermöglicht die Angabe eines Spreadsheet‑Formats, das zum Speichern von |
Dokument
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Ermöglicht die Angabe eines Spreadsheet‑Formats, das zum Speichern von |
Dokument
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Ermöglicht das Aktivieren eines Arbeitsblattschutzes für das Ausgabespreadsheet |
Dokument.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Ermöglicht das Aktivieren eines Arbeitsblattschutzes für das Ausgabespreadsheet |
Dokument.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Ermöglicht die Angabe eines Arrays mit 1‑basierten Nummern von Arbeitsblättern, die beim Speichern der Tabelle gelöscht werden sollen, falls das bearbeitete Arbeitsblatt in eine bestehende Tabelle eingefügt wird. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Ermöglicht die Angabe eines Arrays mit 1‑basierten Nummern von Arbeitsblättern, die beim Speichern der Tabelle gelöscht werden sollen, falls das bearbeitete Arbeitsblatt in eine bestehende Tabelle eingefügt wird. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Dieser parameterlose Konstruktor erstellt eine neue Instanz von SpreadsheetSaveOptions mit dem XLSX‑Ausgabeformat (kann anschließend über
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) Eigenschaft)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Erstellt eine neue Instanz von SpreadsheetSaveOptions mit dem angegebenen obligatorischen
Spreadsheet‑Ausgabeformat, während alle anderen Parameter Standardwerte haben


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Erforderliches Ausgabeformat, in dem das Spreadsheet‑Dokument gespeichert werden soll |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das
verwendet, um das erzeugte Spreadsheet‑Dokument zu kodieren, falls dieses Dokumentformat
unterstützt Passwortschutz. Geben Sie NULL oder einen leeren String an, um zu entfernen
(Bereinigung) des Passworts.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Festlegen, Ändern, Abrufen oder Entfernen eines Passworts, das
verwendet, um das erzeugte Spreadsheet‑Dokument zu kodieren, falls dieses Dokumentformat
unterstützt Passwortschutz. Geben Sie NULL oder einen leeren String an, um zu entfernen
(Bereinigung) des Passworts.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Ermöglicht das Einfügen eines bearbeiteten Arbeitsblatts in eine Kopie eines bestehenden Spreadsheet
statt ein neues ein‑Arbeitsblatt‑Spreadsheet zu erstellen (Standard
Verhalten). WorksheetNumber ist eine 1‑basierte Nummer eines Arbeitsblatts in der
Tabelle, die in der Editor‑Klasse geladen ist. Wenn sie 0 (Standardwert) ist, wird die
neue Tabelle mit einem einzigen bearbeiteten Arbeitsblatt erstellt. Wenn sie
größer oder kleiner als Null ist und eine gültige Tabelle geladen ist, in
der Editor‑Klasse, wird das bearbeitete Arbeitsblatt, das durch die Eingabe
der EditableDocument‑Instanz, in diese Tabelle eingefügt.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Ermöglicht das Einfügen eines bearbeiteten Arbeitsblatts in eine Kopie eines bestehenden Spreadsheet
statt ein neues ein‑Arbeitsblatt‑Spreadsheet zu erstellen (Standard
Verhalten). WorksheetNumber ist eine 1‑basierte Nummer eines Arbeitsblatts in der
Tabelle, die in der Editor‑Klasse geladen ist. Wenn sie 0 (Standardwert) ist, wird die
neue Tabelle mit einem einzigen bearbeiteten Arbeitsblatt erstellt. Wenn sie
größer oder kleiner als Null ist und eine gültige Tabelle geladen ist, in
der Editor‑Klasse, wird das bearbeitete Arbeitsblatt, das durch die Eingabe
der EditableDocument‑Instanz, in diese Tabelle eingefügt.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Boolesches Flag, das angibt, ob das bearbeitete Arbeitsblatt das
bestehende Arbeitsblatt im ursprünglichen Spreadsheet an der durch
die

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
Eigenschaft, oder es sollte zwischen dem bestehenden Arbeitsblatt und
vorherige, ohne deren Inhalt zu ersetzen. Standardmäßig ist false \\u2014
bestehendes Arbeitsblatt wird ersetzt. Diese Eigenschaft wird ignoriert, wenn Wert
von

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
Eigenschaft auf '0' gesetzt ist.


*** ** * ** ***

Standardmäßig wird das Arbeitsblatt ersetzt. Das bedeutet, dass wenn die gegebene Tabelle 5 Arbeitsblätter enthält und WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 ist, das 4. Arbeitsblatt durch das neue bearbeitete Arbeitsblatt ersetzt wird, während die Gesamtzahl der Arbeitsblätter in der Tabelle (5) unverändert bleibt. Wird jedoch der Wert dieser Eigenschaft auf *true* gesetzt, wird das neue bearbeitete Arbeitsblatt als 4. Arbeitsblatt eingefügt und alle nachfolgenden Arbeitsblätter werden ans Ende verschoben: Das "old" 4. Arbeitsblatt wird zum 5., das 5. wird zum 6., und die Gesamtzahl der Arbeitsblätter in der Tabelle wird um eins erhöht und beträgt 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Boolesches Flag, das angibt, ob das bearbeitete Arbeitsblatt das
bestehende Arbeitsblatt im ursprünglichen Spreadsheet an der durch
die

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
Eigenschaft, oder es sollte zwischen dem bestehenden Arbeitsblatt und
vorherige, ohne deren Inhalt zu ersetzen. Standardmäßig ist false \\u2014
bestehendes Arbeitsblatt wird ersetzt. Diese Eigenschaft wird ignoriert, wenn Wert
von

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
Eigenschaft auf '0' gesetzt ist.


*** ** * ** ***

Standardmäßig wird das Arbeitsblatt ersetzt. Das bedeutet, dass wenn die gegebene Tabelle 5 Arbeitsblätter enthält und WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 ist, das 4. Arbeitsblatt durch das neue bearbeitete Arbeitsblatt ersetzt wird, während die Gesamtzahl der Arbeitsblätter in der Tabelle (5) unverändert bleibt. Wird jedoch der Wert dieser Eigenschaft auf *true* gesetzt, wird das neue bearbeitete Arbeitsblatt als 4. Arbeitsblatt eingefügt und alle nachfolgenden Arbeitsblätter werden ans Ende verschoben: Das "old" 4. Arbeitsblatt wird zum 5., das 5. wird zum 6., und die Gesamtzahl der Arbeitsblätter in der Tabelle wird um eins erhöht und beträgt 6.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Ermöglicht die Angabe eines Spreadsheet‑Formats, das zum Speichern von
Dokument


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Ermöglicht die Angabe eines Spreadsheet‑Formats, das zum Speichern von
Dokument


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Ermöglicht das Aktivieren eines Arbeitsblattschutzes für das Ausgabespreadsheet
Dokument. Standardmäßig ist NULL - Schutz wird nicht angewendet. Nicht alle Formate
unterstützen einen Arbeitsblattschutz.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Ermöglicht das Aktivieren eines Arbeitsblattschutzes für das Ausgabespreadsheet
Dokument. Standardmäßig ist NULL - Schutz wird nicht angewendet. Nicht alle Formate
unterstützen einen Arbeitsblattschutz.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Ermöglicht die Angabe eines Arrays mit 1‑basierten Nummern von Arbeitsblättern, die beim Speichern der Tabelle gelöscht werden sollen, falls das bearbeitete Arbeitsblatt in eine bestehende Tabelle eingefügt wird. Wenn das bearbeitete Arbeitsblatt nicht als neue ein‑Arbeitsblatt‑Tabelle gespeichert wird (Standardverhalten), sondern stattdessen in eine bestehende Tabelle (unter Verwendung von #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)) gespeichert wird, kann man ebenfalls bestimmte Arbeitsblätter aus dieser Tabelle löschen, indem man deren Nummern in diesem Array angibt. Standardmäßig ist dieses Array null \\u2014 es werden keine Arbeitsblätter gelöscht. Ist das Array jedoch nicht null und nicht leer und enthält mindestens eine gültige Arbeitsblatt‑Nummer, werden nach der Erzeugung des Ausgabetabelle‑Dokuments mit dem Inhalt des bearbeiteten Arbeitsblatts die Arbeitsblätter mit den angegebenen Nummern unmittelbar vor dem Schreiben des Inhalts in den Ausgabestream oder die Datei aus der Tabelle gelöscht. Die Arbeitsblatt‑Nummern in diesem Array sind 1‑basiert, nicht 0‑basiert. Ungültige Nummern (kleiner als 1 oder größer als die Gesamtzahl der Arbeitsblätter) werden ignoriert.


**Returns:**
int[] – Array von 1‑basierten Arbeitsblatt‑Nummern zum Löschen, oder  null  wenn nichts gelöscht werden soll.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Ermöglicht das Angeben eines Arrays mit 1‑basierten Nummern von Arbeitsblättern, die beim Speichern der Tabelle gelöscht werden sollen, falls das bearbeitete Arbeitsblatt in eine vorhandene Tabelle eingefügt wird. Die Arbeitsblattnummern in diesem Array sind 1‑basiert. Ungültige Nummern werden ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Array von 1‑basierten Arbeitsblattnummern zum Löschen (kann null oder leer sein). |
|

