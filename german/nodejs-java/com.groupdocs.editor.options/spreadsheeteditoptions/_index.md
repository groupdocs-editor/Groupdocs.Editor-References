---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Festlegen benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten tabellenkalkulations‑Excel‑kompatiblen Formate"
type: docs
weight: 35
url: /de/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten
Tabellenkalkulations‑ (Excel‑kompatible) Formate

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ermöglicht die Angabe des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe |
Tabellenkalkulations‑Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Ermöglicht die Angabe des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe |
Tabellenkalkulations‑Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Tabellenkalkulations‑Dokument, sodass |
sie vollständig ignoriert werden.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Tabellenkalkulations‑Dokument, sodass |
sie vollständig ignoriert werden.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Wenn aktiviert, werden die leeren benachbarten horizontalen Zellen aus dem Eingabe‑Tabellenkalkulations‑Dokument |
im editierbaren HTML‑Dokument als zu einer einzigen Zelle zusammengeführte Zelle mit entsprechender
colspan‑Attribut.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Wenn aktiviert, enthält die HTML‑Tabelle im erzeugten HTML‑Dokument eine leere untere versteckte Zeile mit |
null Höhe und leeren Zellen, bei denen nur die Breite angegeben ist.
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


Ermöglicht die Angabe des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe
Tabellenkalkulations‑Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).


*** ** * ** ***

Die meisten Tabellenkalkulations‑Dokumente unterstützen das Konzept von Tabs, d. h. sie können mehrere Tabs besitzen. Andererseits unterstützt das HTML‑Format eine solche Struktur nicht. Deshalb kann GroupDocs.Editor beim Konvertieren in HTML nur einen bestimmten Tab des Eingabedokuments umwandeln, und diese Option ermöglicht die Angabe dieses Tabs. Der Tab‑Index ist nullbasiert, negative Werte sind verboten. Wird ein Index angegeben, der die Anzahl aller Tabs überschreitet, wird eine Ausnahme ausgelöst. Enthält das Eingabe‑Tabellenkalkulations‑Dokument nur einen Tab, wird diese Option ignoriert. Der Standardwert ist 0 (erster Tab).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Ermöglicht die Angabe des nullbasierten Index des Arbeitsblatts (Tabs) der Eingabe
Tabellenkalkulations‑Dokument, das in HTML konvertiert werden soll (siehe
Hinweise).


*** ** * ** ***

Die meisten Tabellenkalkulations‑Dokumente unterstützen das Konzept von Tabs, d. h. sie können mehrere Tabs besitzen. Andererseits unterstützt das HTML‑Format eine solche Struktur nicht. Deshalb kann GroupDocs.Editor beim Konvertieren in HTML nur einen bestimmten Tab des Eingabedokuments umwandeln, und diese Option ermöglicht die Angabe dieses Tabs. Der Tab‑Index ist nullbasiert, negative Werte sind verboten. Wird ein Index angegeben, der die Anzahl aller Tabs überschreitet, wird eine Ausnahme ausgelöst. Enthält das Eingabe‑Tabellenkalkulations‑Dokument nur einen Tab, wird diese Option ignoriert. Der Standardwert ist 0 (erster Tab).

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Tabellenkalkulations‑Dokument, sodass
sie werden vollständig ignoriert. Standard ist false – versteckte Arbeitsblätter sind
verfügbar und werden wie üblich verarbeitet.


*** ** * ** ***

Mehrere binäre Tabellenkalkulations‑Formate (wie XLSX) unterstützen das Konzept versteckter Arbeitsblätter (Tabs). Ein Dokument eines solchen Formats kann, wenn es mehr als ein Arbeitsblatt enthält, zusätzliche versteckte Arbeitsblätter besitzen. Standardmäßig sind diese versteckten Arbeitsblätter für die Verarbeitung verfügbar, aber mit dieser Option können sie ignoriert werden, als wären sie nicht vorhanden. Wenn diese Option aktiviert ist, können Sie kein verstecktes Arbeitsblatt mit der Eigenschaft ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' auswählen.

<br />



**Returns:**
boolesch
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Ermöglicht das Ausschließen versteckter Arbeitsblätter im Eingabe‑Tabellenkalkulations‑Dokument, sodass
sie werden vollständig ignoriert. Standard ist false – versteckte Arbeitsblätter sind
verfügbar und werden wie üblich verarbeitet.


*** ** * ** ***

Mehrere binäre Tabellenkalkulations‑Formate (wie XLSX) unterstützen das Konzept versteckter Arbeitsblätter (Tabs). Ein Dokument eines solchen Formats kann, wenn es mehr als ein Arbeitsblatt enthält, zusätzliche versteckte Arbeitsblätter besitzen. Standardmäßig sind diese versteckten Arbeitsblätter für die Verarbeitung verfügbar, aber mit dieser Option können sie ignoriert werden, als wären sie nicht vorhanden. Wenn diese Option aktiviert ist, können Sie kein verstecktes Arbeitsblatt mit der Eigenschaft ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' auswählen.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Wenn aktiviert, werden die leeren benachbarten horizontalen Zellen aus dem Eingabe‑Tabellenkalkulations‑Dokument
im editierbaren HTML‑Dokument als zu einer einzigen Zelle zusammengeführte Zelle mit entsprechender
colspan‑Attribut. Standardmäßig ist es deaktiviert (false).


Standardmäßig konvertiert GroupDocs.Editor eine Tabelle aus dem Eingabe‑Tabellenkalkulations‑Dokument in die Ausgabe
HTML‑Dokument, indem jede Zelle erhalten bleibt. Allerdings können die Tabellenkalkulations‑Dokumente spärlich sein — sie
können eine riesige Menge an \"empty areas\" enthalten, in denen viele Zellen leer sind. Diese Option, wenn
aktiviert, fügt solche leeren Zellen zu einer zusammen mit dem colspan-Attribut im TD-Element,
und kann dadurch die Größe des erzeugten HTML-Markups erheblich reduzieren.


**Returns:**
boolesch
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Wenn aktiviert, enthält die HTML‑Tabelle im erzeugten HTML‑Dokument eine leere untere versteckte Zeile mit
null Höhe und leere Zellen, bei denen nur die Breite angegeben ist. Diese Zeile mit leeren Zellen enthält
exakte Breitenwerte für jede Spalte und verbessert die Rückkonvertierung von HTML zu Spreadsheet. Durch
Standard ist aktiviert (true).


**Returns:**
boolesch
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

