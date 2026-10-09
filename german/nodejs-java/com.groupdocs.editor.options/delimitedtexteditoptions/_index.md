---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Optionen zum Laden von textbasierten Spreadsheet-Dokumenten (CSV, Tab-basiert usw.), die einen Trennzeichen‑Separator verwenden"
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Optionen zum Laden von textbasierten Spreadsheet-Dokumenten (CSV, Tab-basiert usw.),
die einen Separator (Trennzeichen) verwenden


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Erstellt eine Instanz der Optionsklasse für getrennten Text mit obligatorischem |
Separator (Trennzeichen)
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Ermöglicht das Angeben eines Zeichenketten‑Separators (Trennzeichen) für textbasierte |
Tabellenkalkulationsdokumente
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Ermöglicht das Angeben eines Zeichenketten‑Separators (Trennzeichen) für textbasierte |
Tabellenkalkulationsdokumente
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten |
Dokument in Datumsdaten konvertiert wird.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten |
Dokument in Datumsdaten konvertiert wird.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten |
Dokument in numerische Daten konvertiert wird.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten |
Dokument in numerische Daten konvertiert wird.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Definiert, ob aufeinanderfolgende Separatoren als ein einzelner behandelt werden sollen. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Definiert, ob aufeinanderfolgende Separatoren als ein einzelner behandelt werden sollen. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungs‑Mechanismen während der Verarbeitung des Eingabedokuments, |
die in einigen Sonderfällen die Leistung mindern können, aber andererseits
die den Speicherverbrauch reduzieren.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungs‑Mechanismen während der Verarbeitung des Eingabedokuments, |
die in einigen Sonderfällen die Leistung mindern können, aber andererseits
die den Speicherverbrauch reduzieren.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Erstellt eine Instanz der Optionsklasse für getrennten Text mit obligatorischem
Separator (Trennzeichen)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Trennzeichen | java.lang.String | Verpflichtender Separator (Trennzeichen), der nicht NULL oder leer sein darf |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Ermöglicht das Angeben eines Zeichenketten‑Separators (Trennzeichen) für textbasierte
Tabellenkalkulationsdokumente


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Ermöglicht das Angeben eines Zeichenketten‑Separators (Trennzeichen) für textbasierte
Tabellenkalkulationsdokumente


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten
Dokument in Datumsdaten konvertiert wird. Standard ist false.


**Returns:**
boolesch
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten
Dokument in Datumsdaten konvertiert wird. Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten
Dokument wird in numerische Daten konvertiert. Standard ist false.


**Returns:**
boolesch
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob die Zeichenfolge in textbasierten
Dokument wird in numerische Daten konvertiert. Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. Durch
Standard ist false.


**Returns:**
boolesch
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. Durch
Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungs‑Mechanismen während der Verarbeitung des Eingabedokuments,
die in einigen Sonderfällen die Leistung mindern können, aber andererseits
die den Speicherverbrauch reduzieren. Nützlich beim Verarbeiten riesiger Dokumente und
bei Auftreten einer OutOfMemoryException. Standard ist false (Speicheroptimierung ist
deaktiviert, um eine bessere Leistung zu erzielen).


**Returns:**
boolesch
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungs‑Mechanismen während der Verarbeitung des Eingabedokuments,
die in einigen Sonderfällen die Leistung mindern können, aber andererseits
die den Speicherverbrauch reduzieren. Nützlich beim Verarbeiten riesiger Dokumente und
bei Auftreten einer OutOfMemoryException. Standard ist false (Speicheroptimierung ist
deaktiviert, um eine bessere Leistung zu erzielen).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

