---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten Spreadsheet-Excel-kompatiblen Formate"
type: docs
weight: 35
url: /de/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten
Spreadsheet-Formate (Excel-kompatibel)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ermöglicht das Festlegen des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe |
Spreadsheet-Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ermöglicht das Festlegen des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe |
Spreadsheet-Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Spreadsheet‑Dokument, sodass |
sie vollständig ignoriert werden.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Spreadsheet‑Dokument, sodass |
sie vollständig ignoriert werden.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Wenn aktiviert, werden die leeren benachbarten horizontalen Zellen aus dem Eingabe‑Spreadsheet‑Dokument |
im editierbaren HTML-Dokument als zusammengeführt in einer einzelnen Zelle mit entsprechender
colspan‑Attribut.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Wenn aktiviert, enthält die HTML‑Tabelle im erzeugten HTML‑Dokument eine leere untere versteckte Zeile mit |
nuller Höhe und leeren Zellen, bei denen nur die Breite angegeben ist.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Ermöglicht das Festlegen des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe
Spreadsheet-Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).


*** ** * ** ***

Die meisten Spreadsheet‑Dokumente unterstützen das Konzept von Registerkarten, d. h. sie können mehrere Registerkarten besitzen. Andererseits unterstützt das HTML‑Format eine solche Struktur nicht. Deshalb kann GroupDocs.Editor beim Konvertieren in HTML nur eine bestimmte Registerkarte des Eingabedokuments verarbeiten, und diese Option ermöglicht deren Angabe. Der Registerkarten‑Index ist nullbasiert, negative Werte sind nicht zulässig. Wird ein Index angegeben, der die Anzahl aller Registerkarten überschreitet, wird eine Ausnahme ausgelöst. Enthält das Eingabe‑Spreadsheet‑Dokument nur eine Registerkarte, wird diese Option ignoriert. Der Standardwert ist 0 (erste Registerkarte).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Ermöglicht das Festlegen des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe
Spreadsheet-Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).


*** ** * ** ***

Die meisten Spreadsheet‑Dokumente unterstützen das Konzept von Registerkarten, d. h. sie können mehrere Registerkarten besitzen. Andererseits unterstützt das HTML‑Format eine solche Struktur nicht. Deshalb kann GroupDocs.Editor beim Konvertieren in HTML nur eine bestimmte Registerkarte des Eingabedokuments verarbeiten, und diese Option ermöglicht deren Angabe. Der Registerkarten‑Index ist nullbasiert, negative Werte sind nicht zulässig. Wird ein Index angegeben, der die Anzahl aller Registerkarten überschreitet, wird eine Ausnahme ausgelöst. Enthält das Eingabe‑Spreadsheet‑Dokument nur eine Registerkarte, wird diese Option ignoriert. Der Standardwert ist 0 (erste Registerkarte).

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Spreadsheet‑Dokument, sodass
sie werden vollständig ignoriert. Standard ist false – versteckte Arbeitsblätter sind
verfügbar und werden wie üblich verarbeitet.


*** ** * ** ***

Mehrere binäre Spreadsheet‑Formate (wie XLSX) unterstützen das Konzept versteckter Arbeitsblätter (Registerkarten). Ein Dokument dieses Formats kann, wenn es mehr als ein Arbeitsblatt enthält, zusätzliche versteckte Arbeitsblätter besitzen. Standardmäßig sind solche versteckten Arbeitsblätter für die Verarbeitung verfügbar, aber mit dieser Option können sie ignoriert werden, als ob diese versteckten Arbeitsblätter nicht vorhanden wären. Wenn diese Option aktiviert ist, kann man kein verstecktes Arbeitsblatt mit der Eigenschaft ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' auswählen.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Spreadsheet‑Dokument, sodass
sie werden vollständig ignoriert. Standard ist false – versteckte Arbeitsblätter sind
verfügbar und werden wie üblich verarbeitet.


*** ** * ** ***

Mehrere binäre Spreadsheet‑Formate (wie XLSX) unterstützen das Konzept versteckter Arbeitsblätter (Registerkarten). Ein Dokument dieses Formats kann, wenn es mehr als ein Arbeitsblatt enthält, zusätzliche versteckte Arbeitsblätter besitzen. Standardmäßig sind solche versteckten Arbeitsblätter für die Verarbeitung verfügbar, aber mit dieser Option können sie ignoriert werden, als ob diese versteckten Arbeitsblätter nicht vorhanden wären. Wenn diese Option aktiviert ist, kann man kein verstecktes Arbeitsblatt mit der Eigenschaft ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' auswählen.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Wenn aktiviert, werden die leeren benachbarten horizontalen Zellen aus dem Eingabe‑Spreadsheet‑Dokument
im editierbaren HTML-Dokument als zusammengeführt in einer einzelnen Zelle mit entsprechender
colspan‑Attribut. Standardmäßig ist es deaktiviert (false).


Standardmäßig konvertiert GroupDocs.Editor eine Tabelle aus dem Eingabe‑Spreadsheet‑Dokument in die Ausgabe
HTML‑Dokument, wobei jede Zelle erhalten bleibt. Allerdings können Spreadsheet‑Dokumente spärlich sein \\u2014 sie
können eine riesige Menge an \"empty areas\" enthalten, in denen viele Zellen leer sind. Diese Option, wenn
aktiviert, führt solche leeren Zellen zu einer einzigen Zelle mit colspan‑Attribut im TD‑Element zusammen,
und kann dadurch die Größe des erzeugten HTML‑Markups erheblich reduzieren.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Wenn aktiviert, enthält die HTML‑Tabelle im erzeugten HTML‑Dokument eine leere untere versteckte Zeile mit
nuller Höhe und leere Zellen, bei denen nur die Breite angegeben ist. Diese Zeile mit leeren Zellen enthält
exakte Breitenwerte für jede Spalte und verbessert die Rückkonvertierung von HTML nach Spreadsheet. Durch
Standard ist aktiviert (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

