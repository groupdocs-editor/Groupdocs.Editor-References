---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Kapselt Optionen zum Blattschutz, die es ermöglichen, ein Arbeitsblatt im ausgegebenen Spreadsheet-Dokument vor Änderungen eines angegebenen Typs mit einem festgelegten Passwort zu schützen."
type: docs
weight: 49
url: /de/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Kapselt Optionen zum Blattschutz, die es ermöglichen, ein Arbeitsblatt zu schützen
im ausgegebenen Spreadsheet-Dokument vor Änderungen eines angegebenen Typs mit einem
festgelegten Passwort.


*** ** * ** ***

Die meisten Spreadsheet-Formate wie XLSX erlauben, ein Arbeitsblatt mit einem Passwort vor Bearbeitung zu schützen. Diese Klasse ermöglicht, solchen Schutz zu aktivieren und ihre Optionen festzulegen.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Erstellt eine neue Instanz mit Standardparametern. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Erstellt eine neue Instanz mit dem angegebenen Blattschutztyp und |
Passwort
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Ermöglicht die Angabe eines Typs des Blattschutzes. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Ermöglicht die Angabe eines Typs des Blattschutzes. |
|
|  | [getPassword()](#getPassword--) | Passwort, das zum Schutz eines Arbeitsblatts verwendet wird. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Passwort, das zum Schutz eines Arbeitsblatts verwendet wird. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Erstellt eine neue Instanz mit Standardparametern. Wenn nicht geändert und übergeben
an SpreadsheetSaveOptions, wird kein Blattschutz angewendet


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Erstellt eine neue Instanz mit dem angegebenen Blattschutztyp und
Passwort


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | protectionType | int | Typ des Blattschutzes |
|
|  | Passwort | java.lang.String | Passwort, das den Schutz sperrt |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Ermöglicht die Angabe eines Typs des Blattschutzes. Standard ist 'None' -
Schutz wird nicht angewendet.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Ermöglicht die Angabe eines Typs des Blattschutzes. Standard ist 'None' -
Schutz wird nicht angewendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Passwort, das zum Schutz eines Arbeitsblatts verwendet wird. Wenn NULL oder leer
Zeichenkette, der Schutz wird nicht angewendet.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Passwort, das zum Schutz eines Arbeitsblatts verwendet wird. Wenn NULL oder leer
Zeichenkette, der Schutz wird nicht angewendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

