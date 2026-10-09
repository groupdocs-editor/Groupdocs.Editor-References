---
title: "FontWeight"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Die Font-weight‑Eigenschaft legt das Gewicht oder die Fettigkeit der Schrift fest."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Die Font-weight‑Eigenschaft legt das Gewicht (oder die Fettigkeit) der Schrift fest. Die verfügbaren Gewichte hängen von der aktuell eingestellten font-family ab.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Lighter](#Lighter) | Ein relativ leichteres Schriftgewicht als das des übergeordneten Elements |
|
|  | [Bolder](#Bolder) | Ein relativ schwereres Schriftgewicht als das des übergeordneten Elements |
|
|  | [Normal](#Normal) | Normales Schriftgewicht. |
|
|  | [Bold](#Bold) | Fettes Schriftgewicht. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isInitial()](#isInitial--) | Gibt an, ob diese Schriftgröße einen Anfangswert (Medium) hat |
|
|  | [getNumber()](#getNumber--) | Gibt eine Zahl zurück – einen ganzzahligen Wert zwischen 1 und 1000, inklusiv, der die Fettstärke der Schrift beschreibt, oder wirft eine Ausnahme, wenn die aktuelle Fettstärke nicht absolut, sondern relativ ist. |
|
|  | [isAbsolute()](#isAbsolute--) | Gibt an, ob diese FontWeight-Instanz einen absoluten Wert des Gewichts (der Fettstärke) der Schrift als ganze Zahl speichert. |
|
|  | [isRelative()](#isRelative--) | Gibt an, ob diese FontWeight-Instanz einen relativen Wert des Gewichts (der Fettstärke) der Schrift speichert – verglichen mit der Fettstärke des übergeordneten Elements. |
|
|  | [getValue()](#getValue--) | Gibt einen Wert dieser FontWeight als Zeichenkette zurück. |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Bestimmt, ob angegebene FontWeight-Instanzen gleich sind. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese FontWeight-Instanz gleich dem angegebenen ungecasteten ist. |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code für diese Instanz zurück |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Prüft, ob zwei \"FontWeight\"-Werte gleich sind. |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Prüft, ob zwei \"FontWeight\"-Werte ungleich sind. |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Erstellt ein FontWeight aus einer angegebenen Zahl. |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Versucht, eine angegebene Zeichenkette zu parsen und bei Erfolg eine gültige FontWeight-Instanz zurückzugeben. |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Ein relativ leichteres Schriftgewicht als das des übergeordneten Elements


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Ein relativ schwereres Schriftgewicht als das des übergeordneten Elements


### Normal {#Normal}
```
public static final FontWeight Normal
```


Normales Schriftgewicht. Gleichbedeutend mit 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Fettes Schriftgewicht. Gleichbedeutend mit 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Gibt an, ob diese Schriftgröße einen Anfangswert (Medium) hat


**Returns:**
boolesch
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Gibt eine Zahl zurück – einen ganzzahligen Wert zwischen 1 und 1000, inklusiv, der die Fettstärke der Schrift beschreibt, oder wirft eine Ausnahme, wenn die aktuelle Fettstärke nicht absolut, sondern relativ ist.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Gibt an, ob diese FontWeight-Instanz einen absoluten Wert des Gewichts (der Fettstärke) der Schrift als ganze Zahl speichert.


**Returns:**
boolesch
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Gibt an, ob diese FontWeight-Instanz einen relativen Wert des Gewichts (der Fettstärke) der Schrift speichert – verglichen mit der Fettstärke des übergeordneten Elements.


**Returns:**
boolesch
### getValue() {#getValue--}
```
public final String getValue()
```


Gibt einen Wert dieser FontWeight als Zeichenkette zurück.


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Bestimmt, ob angegebene FontWeight-Instanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Andere FontWeight-Instanz zum Prüfen der Gleichheit. |
|

**Returns:**
boolean – true, wenn gleich, false, wenn ungleich.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese FontWeight-Instanz gleich dem angegebenen ungecasteten ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere ungecastete FontWeight-Instanz, kann null sein. |
|

**Returns:**
boolesch - true, wenn gleich, false, wenn nicht gleich, null oder anderer Typ

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash-Code für diese Instanz zurück


**Returns:**
int - Hashcode als vorzeichenbehaftete ganze Zahl

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Prüft, ob zwei \"FontWeight\"-Werte gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Erster zu prüfender Wert |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Zweiter zu prüfender Wert |
|

**Returns:**
boolesch - true, wenn gleich, false sonst

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Prüft, ob zwei \"FontWeight\"-Werte ungleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Erster zu prüfender Wert |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Zweiter zu prüfender Wert |
|

**Returns:**
boolesch - false, wenn gleich, true sonst

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Erstellt ein FontWeight aus einer angegebenen Zahl.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Vorzeichenlose ganze Zahl, muss im Bereich [1..1000] liegen. |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Versucht, eine angegebene Zeichenkette zu parsen und bei Erfolg eine gültige FontWeight-Instanz zurückzugeben.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Eingabe | java.lang.String | Zu parsende Eingabezeichenkette. |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Gültiger FontWeight-Wert bei Erfolg oder #Normal.Normal bei Misserfolg. |
|

**Returns:**
boolean – Erfolg (true) oder Misserfolg (false) beim Parsen.

