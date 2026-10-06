---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Enthält Optionen zum Laden binärer Spreadsheet Cells Excel-kompatibler Dokumente wie XLSX, ODS usw."
type: docs
weight: 36
url: /de/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Enthält Optionen zum Laden binärer Spreadsheet (Cells, Excel-kompatibel)
Dokumente wie XLS(X), ODS usw. in die Editor-Klasse

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Standard‑Konstruktor ohne Parameter – alle Parameter haben Standardwerte |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Öffnen des Spreadsheet-Dokuments, falls es codiert ist.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für |
Öffnen des Spreadsheet-Dokuments, falls es codiert ist.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung des Eingabedokuments, |
die in einigen Sonderfällen die Leistung beeinträchtigen können, aber andererseits
die den Speicherverbrauch reduzieren.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiviert Speicheroptimierungsmechanismen während der Verarbeitung des Eingabedokuments, |
die in einigen Sonderfällen die Leistung beeinträchtigen können, aber andererseits
die den Speicherverbrauch reduzieren.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Standard‑Konstruktor ohne Parameter – alle Parameter haben Standardwerte


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Öffnen des Spreadsheet-Dokuments, falls es codiert ist. Auf NULL oder leer setzen
Zeichenfolge, um das Passwort nicht zu verwenden (Standardwert).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ermöglicht das Angeben, Ändern und Abrufen des Passworts, das verwendet wird für
Öffnen des Spreadsheet-Dokuments, falls es codiert ist. Auf NULL oder leer setzen
Zeichenfolge, um das Passwort nicht zu verwenden (Standardwert).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

