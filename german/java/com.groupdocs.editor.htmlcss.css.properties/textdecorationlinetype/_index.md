---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt die Typen der Textdekoration dar: underline, underscore, overline und line-through (Durchgestrichen)"
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Stellt Typen der Textdekoration dar: underline (Unterstrich), overline und line-through (Durchgestrichen).

<br />

*** ** * ** ***

Unveränderliche Struktur. Ähnlich wie die https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [None](#None) | Erzeugt keine Textdekoration. |
|
|  | [Underline](#Underline) | Jede Textzeile ist unterstrichen. |
|
|  | [Overline](#Overline) | Jede Textzeile hat darüber eine Linie. |
|
|  | [LineThrough](#LineThrough) | Jede Textzeile hat eine Linie in der Mitte. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isInitial()](#isInitial--) | Gibt an, ob diese Instanz einen Anfangswert hat \\\\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | Gibt an, ob Unterstreichung (Unterstrich) aktiviert ist |
|
|  | [isOverline()](#isOverline--) | Gibt an, ob Oberlinie aktiviert ist |
|
|  | [isLineThrough()](#isLineThrough--) | Gibt an, ob Durchstreichen (Strikethrough) aktiviert ist |
|
|  | [getValue()](#getValue--) | Gibt einen Wert aller Flags in dieser Instanz als Text zurück |
|
|  | [toString()](#toString--) | Gibt einen Wert aller Flags in dieser Instanz als Text zurück |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Gibt an, ob diese [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz dem angegebenen entspricht |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Gibt an, ob diese [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz dem angegebenen ungecasteten entspricht |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode dieser Instanz zurück |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Prüft, ob zwei \"TextDecorationLineType\" Werte gleich sind |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Prüft, ob zwei \"TextDecorationLineType\" Werte ungleich sind |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Erstellt und gibt eine [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz mit Flags zurück, die durch die angegebenen Parameter definiert sind |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Versucht, einen angegebenen String zu parsen und gibt eine gültige [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz zurück |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kombiniert (vereinigt) zwei angegebene Linientypen und erzeugt einen neuen resultierenden Linientyp, bei dem die Flags zusammengeführt werden (Vereinigung) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Subtrahiert den zweiten angegebenen Linientyp vom ersten angegebenen Linientyp und erzeugt einen neuen resultierenden Linientyp, bei dem nur jene Flags des ersten Operanden vorhanden sind, die im zweiten Operanden nicht gefunden werden (Differenz) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Gibt eine Schnittmenge zwischen dem ersten und zweiten Linientyp zurück, bei der nur jene Flags aktiviert sind, die in beiden Operanden gleichzeitig aktiviert sind. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Wandelt ein bestimmtes Byte (8‑Bit‑Oktett) in den entsprechenden [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) um, wirft eine Ausnahme, wenn die Umwandlung ungültig ist |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Erzeugt keine Textdekoration. Anfangswert.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Jede Textzeile ist unterstrichen.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Jede Textzeile hat darüber eine Linie.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Jede Textzeile hat eine Linie in der Mitte.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Gibt an, ob diese Instanz einen Anfangswert hat \\\\u2014 None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Gibt an, ob Unterstreichung (Unterstrich) aktiviert ist


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Gibt an, ob Oberlinie aktiviert ist


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Gibt an, ob Durchstreichen (Strikethrough) aktiviert ist


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Gibt einen Wert aller Flags in dieser Instanz als Text zurück


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Gibt einen Wert aller Flags in dieser Instanz als Text zurück


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Gibt an, ob diese [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz dem angegebenen entspricht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andere [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz |
|

**Returns:**
boolean -  true  wenn gleich,  false  sonst

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Gibt an, ob diese [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz dem angegebenen ungecasteten entspricht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | java.lang.Object | Andere [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz, in Objekt gecastet |
|

**Returns:**
boolean -  true  wenn gleich,  false  sonst

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode dieser Instanz zurück


**Returns:**
int - Vorzeichenbehafteter Ganzzahl-Hashcode

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Prüft, ob zwei \"TextDecorationLineType\" Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Erster Operand zum Prüfen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Zweiter Operand zum Prüfen |
|

**Returns:**
boolean -  true  wenn gleich,  false  sonst

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Prüft, ob zwei \"TextDecorationLineType\" Werte ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Erster Operand zum Prüfen |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Zweiter Operand zum Prüfen |
|

**Returns:**
boolean -  true  wenn ungleich,  false  sonst

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Erstellt und gibt eine [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz mit Flags zurück, die durch die angegebenen Parameter definiert sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | isUnderline | boolean | Bestimmt, ob ein Unterstreichungs-Flag aktiviert ist oder nicht |
|
|  | isOverline | boolean | Bestimmt, ob ein Oberstreichungs-Flag aktiviert ist oder nicht |
|
|  | isLineThrough | boolean | Bestimmt, ob ein Durchstreichungs-Flag aktiviert ist oder nicht |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Versucht, einen angegebenen String zu parsen und gibt eine gültige [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) Instanz zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Eingabe | java.lang.String | Eingabezeichenfolge |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Ergebnis. Wenn das Parsen ungültig ist, ist es ein #None.None-Wert |
|

**Returns:**
boolean -  true  wenn das Parsen erfolgreich war,  false  bei Fehler

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Kombiniert (vereinigt) zwei angegebene Linientypen und erzeugt einen neuen resultierenden Linientyp, bei dem die Flags zusammengeführt werden (Vereinigung)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Erster Zeilentyp-Operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Zweiter Zeilentyp-Operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Subtrahiert den zweiten angegebenen Linientyp vom ersten angegebenen Linientyp und erzeugt einen neuen resultierenden Linientyp, bei dem nur jene Flags des ersten Operanden vorhanden sind, die im zweiten Operanden nicht gefunden werden (Differenz)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Erster Zeilentyp-Operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Zweiter Zeilentyp-Operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Gibt die Schnittmenge zwischen dem ersten und dem zweiten Zeilentyp zurück, wobei nur jene Flags aktiviert sind, die in beiden Operanden gleichzeitig aktiviert sind. Hat die höchste Priorität aller Operatoren (höher als Vereinigung und Differenz).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Erster Zeilentyp-Operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Zweiter Zeilentyp-Operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Wandelt ein bestimmtes Byte (8‑Bit‑Oktett) in den entsprechenden [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) um, wirft eine Ausnahme, wenn die Umwandlung ungültig ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Oktett | Byte | Ein 8‑Bit‑Oktett (Bitfeld), bei dem die ersten 5 Bits Null sind, während die letzten 3 Flags anzeigen |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
