---
title: "FontStyle"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Definiert, wie die Schriftart mit einer normalen, kursiven oder schrägen Variante aus ihrer Schriftfamilie formatiert werden soll."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Definiert, wie die Schrift mit einer normalen, kursiven oder schrägen Variante aus ihrer Schriftfamilie gestaltet werden soll.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Normal](#Normal) | Wählt eine Schriftart aus, die innerhalb einer Schriftfamilie als normal klassifiziert ist. |
|
|  | [Italic](#Italic) | Wählt eine Schriftart aus, die als kursiv klassifiziert ist. |
|
|  | [Oblique](#Oblique) | Wählt eine Schriftart aus, die als schräg klassifiziert ist. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isInitial()](#isInitial--) | Gibt an, ob dieser font-style einen Anfangswert (Normal) hat |
|
|  | [getValue()](#getValue--) | Gibt einen Wert dieses Font-Stils als Zeichenkette zurück |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Bestimmt, ob diese Font-Style-Instanz gleich dem angegebenen ist |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Font-Style-Instanz gleich dem nicht gecasteten angegebenen ist |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code für diese Instanz zurück |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Überprüft, ob zwei "FontStyle"-Werte gleich sind |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Überprüft, ob zwei "FontStyle"-Werte ungleich sind |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Versucht, ein angegebenes Schlüsselwort als gültigen Schlüsselwortwert von 'font-style' zu erkennen und gibt es bei Erfolg zurück, andernfalls NULL. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Wählt eine Schriftart aus, die innerhalb einer Schriftfamilie als normal klassifiziert ist. Anfangswert.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Wählt eine Schriftart aus, die als kursiv klassifiziert ist. Wenn keine kursive Version der Schrift verfügbar ist, wird stattdessen eine als schräg klassifizierte verwendet. Wenn keine von beiden verfügbar ist, wird der Stil künstlich simuliert.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Wählt eine Schriftart aus, die als schräg klassifiziert ist. Wenn keine schräge Version der Schrift verfügbar ist, wird stattdessen eine als kursiv klassifizierte verwendet. Wenn keine von beiden verfügbar ist, wird der Stil künstlich simuliert.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Gibt an, ob dieser font-style einen Anfangswert (Normal) hat


**Returns:**
boolesch
### getValue() {#getValue--}
```
public final String getValue()
```


Gibt einen Wert dieses Font-Stils als Zeichenkette zurück


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Bestimmt, ob diese Font-Style-Instanz gleich dem angegebenen ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Andere Schriftstil-Instanz |
|

**Returns:**
boolesch - true, wenn gleich, false sonst

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Font-Style-Instanz gleich dem nicht gecasteten angegebenen ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere nicht gecastete Schriftstil-Instanz, kann null sein |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Überprüft, ob zwei "FontStyle"-Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Erster zu prüfender Wert |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Zweiter zu prüfender Wert |
|

**Returns:**
boolesch - true, wenn gleich, false sonst

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Überprüft, ob zwei "FontStyle"-Werte ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Erster zu prüfender Wert |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Zweiter zu prüfender Wert |
|

**Returns:**
boolesch - false, wenn gleich, true sonst

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Versucht, ein angegebenes Schlüsselwort als gültigen Schlüsselwortwert von 'font-style' zu erkennen und gibt es bei Erfolg zurück, andernfalls NULL.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Schlüsselwort | java.lang.String | Ein Schlüsselwort zum Parsen |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Ergebnis, wenn das Parsen erfolgreich war, sonst #Normal.Normal |
|

**Returns:**
boolesch - true, wenn das Parsen erfolgreich war, false sonst

