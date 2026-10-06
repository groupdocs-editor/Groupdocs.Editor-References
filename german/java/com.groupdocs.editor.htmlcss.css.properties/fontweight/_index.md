---
title: "FontWeight"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Die Font-weight‑Eigenschaft legt das Gewicht oder die Fettigkeit der Schrift fest."
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
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
|  | [isInitial()](#isInitial--) | Gibt an, ob diese Schriftgröße einen Anfangswert hat (Medium) |
|
|  | [getNumber()](#getNumber--) | Gibt eine Zahl zurück – einen ganzzahligen Wert zwischen 1 und 1000, inklusiv, der die Fettigkeit der Schrift beschreibt, oder wirft eine Ausnahme, wenn die aktuelle Fettigkeit nicht absolut, sondern relativ ist. |
|
|  | [isAbsolute()](#isAbsolute--) | Gibt an, ob diese Font-weight‑Instanz einen absoluten Wert des Gewichts (der Fettigkeit) der Schrift als ganze Zahl speichert. |
|
|  | [isRelative()](#isRelative--) | Gibt an, ob diese font-weight-Instanz einen relativen Wert der Gewichtung (Fettdichte) der Schrift speichert – verglichen mit der Fettdichte des übergeordneten Elements |
|
|  | [getValue()](#getValue--) | Gibt einen Wert dieser font-weight als Zeichenkette zurück |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Bestimmt, ob die angegebenen FontWeight-Instanzen gleich sind |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese FontWeight-Instanz gleich dem angegebenen nicht gecasteten Wert ist |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code für diese Instanz zurück |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Überprüft, ob zwei \"FontWeight\"-Werte gleich sind |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Überprüft, ob zwei \"FontWeight\"-Werte ungleich sind |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Erstellt ein font-weight aus einer angegebenen Zahl |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Versucht, eine angegebene Zeichenkette zu parsen und bei Erfolg eine gültige FontWeight-Instanz zurückzugeben |
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


Normales font-weight. Gleichbedeutend mit 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Fettes font-weight. Gleichbedeutend mit 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Gibt an, ob diese Schriftgröße einen Anfangswert hat (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Gibt eine Zahl zurück – einen ganzzahligen Wert zwischen 1 und 1000, inklusiv, der die Fettigkeit der Schrift beschreibt, oder wirft eine Ausnahme, wenn die aktuelle Fettigkeit nicht absolut, sondern relativ ist.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Gibt an, ob diese Font-weight‑Instanz einen absoluten Wert des Gewichts (der Fettigkeit) der Schrift als ganze Zahl speichert.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Gibt an, ob diese font-weight-Instanz einen relativen Wert der Gewichtung (Fettdichte) der Schrift speichert – verglichen mit der Fettdichte des übergeordneten Elements


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Gibt einen Wert dieser font-weight als Zeichenkette zurück


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Bestimmt, ob die angegebenen FontWeight-Instanzen gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Andere FontWeight-Instanz zum Prüfen der Gleichheit |
|

**Returns:**
boolean – true, wenn gleich, false, wenn ungleich

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese FontWeight-Instanz gleich dem angegebenen nicht gecasteten Wert ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere nicht gecastete FontWeight-Instanz, kann null sein |
|

**Returns:**
boolean - true, wenn gleich, sonst false, null oder anderer Typ

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash-Code für diese Instanz zurück


**Returns:**
int - Hash-Code als vorzeichenbehaftete Ganzzahl

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Überprüft, ob zwei \"FontWeight\"-Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Erster zu prüfender Wert |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Zweiter zu prüfender Wert |
|

**Returns:**
boolean - true, wenn gleich, sonst false

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Überprüft, ob zwei \"FontWeight\"-Werte ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Erster zu prüfender Wert |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Zweiter zu prüfender Wert |
|

**Returns:**
boolean - false, wenn gleich, sonst true

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Erstellt ein font-weight aus einer angegebenen Zahl


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Unsigned Integer, muss im Bereich [1..1000] liegen |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Versucht, eine angegebene Zeichenkette zu parsen und bei Erfolg eine gültige FontWeight-Instanz zurückzugeben


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Eingabe | java.lang.String | Einzugebende Zeichenkette zum Parsen |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Gültiger FontWeight-Wert bei Erfolg oder #Normal.Normal bei Misserfolg |
|

**Returns:**
boolean – Erfolg (true) oder Misserfolg (false) des Parsens

