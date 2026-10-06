---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Optionen zum Laden textbasierter Tabellenkalkulationsdokumente CSV, Tab-basiert usw., die ein Trennzeichen verwenden"
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Optionen zum Laden textbasierter Tabellenkalkulationsdokumente (CSV, Tab-basiert usw.),
die ein Trennzeichen (delimiter) verwenden


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Erstellt eine Instanz der Optionsklasse für delimited Text mit obligatorischem |
Trennzeichen (delimiter)
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte |
Tabellenkalkulationsdokumente
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte |
Tabellenkalkulationsdokumente
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten |
Dokument in Datumsdaten konvertiert wird.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten |
Dokument in Datumsdaten konvertiert wird.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten |
Dokument in numerische Daten konvertiert wird.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten |
Dokument in numerische Daten konvertiert wird.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung des Eingabedokuments, |
die in einigen Sonderfällen die Leistung beeinträchtigen können, aber andererseits
die den Speicherverbrauch reduzieren.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung des Eingabedokuments, |
die in einigen Sonderfällen die Leistung beeinträchtigen können, aber andererseits
die den Speicherverbrauch reduzieren.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Erstellt eine Instanz der Optionsklasse für delimited Text mit obligatorischem
Trennzeichen (delimiter)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Trennzeichen | java.lang.String | Obligatorisches Trennzeichen (delimiter), das nicht NULL oder leer sein darf |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte
Tabellenkalkulationsdokumente


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Ermöglicht die Angabe eines Zeichenketten‑Trennzeichens (delimiter) für textbasierte
Tabellenkalkulationsdokumente


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten
Dokument wird in Datumsdaten konvertiert. Standard ist false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten
Dokument wird in Datumsdaten konvertiert. Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten
Dokument wird in numerische Daten konvertiert. Standard ist false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Zeichenkette in textbasierten
Dokument wird in numerische Daten konvertiert. Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. Durch
Standard ist false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Definiert, ob aufeinanderfolgende Trennzeichen als eines behandelt werden sollen. Durch
Standard ist false.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung des Eingabedokuments,
die in einigen Sonderfällen die Leistung beeinträchtigen können, aber andererseits
reduziert den Speicherverbrauch. Nützlich beim Verarbeiten riesiger Dokumente und
bei Auftreten einer OutOfMemoryException. Standard ist false (Speicheroptimierung ist
deaktiviert, um eine bessere Leistung zu erzielen).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung des Eingabedokuments,
die in einigen Sonderfällen die Leistung beeinträchtigen können, aber andererseits
reduziert den Speicherverbrauch. Nützlich beim Verarbeiten riesiger Dokumente und
bei Auftreten einer OutOfMemoryException. Standard ist false (Speicheroptimierung ist
deaktiviert, um eine bessere Leistung zu erzielen).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

