---
title: "FontSize"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Schriftgröße als spezielle Einheit oder als Längenwert dar, der die Größe der Schrift angibt, historisch die Breite des Großbuchstabens M."
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Stellt eine Schriftgröße als spezielle Einheit oder Längenwert dar, der die Größe der Schrift festlegt (historisch die Breite des Großbuchstabens "M").

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Medium](#Medium) | Mittlere Größe. |
|
|  | [XxSmall](#XxSmall) | Die sehr kleine absolute Größe |
|
|  | [XSmall](#XSmall) | Die mittel kleine absolute Größe |
|
|  | [Small](#Small) | Die normalerweise kleine absolute Größe |
|
|  | [Large](#Large) | Die normalerweise große absolute Größe |
|
|  | [XLarge](#XLarge) | Die mittel große absolute Größe |
|
|  | [XxLarge](#XxLarge) | Die sehr große absolute Größe |
|
|  | [Larger](#Larger) | Größere relative Größe - font wird größer relativ zur Schriftgröße des Elternelements, ungefähr im Verhältnis, das zur Trennung der obigen absoluten Größen‑Schlüsselwörter verwendet wird. |
|
|  | [Smaller](#Smaller) | Kleinere relative Größe - font wird kleiner relativ zur Schriftgröße des Elternelements, ungefähr im Verhältnis, das zur Trennung der obigen absoluten Größen‑Schlüsselwörter verwendet wird. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isInitial()](#isInitial--) | Gibt an, ob diese Schriftgröße einen Anfangswert hat (Medium) |
|
|  | [getValue()](#getValue--) | Gibt den Wert dieser Schriftgröße als Zeichenkette zurück |
|
|  | [isLengthDefined()](#isLengthDefined--) | Gibt an, ob diese Schriftgröße mit einem [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) Wert definiert ist |
|
|  | [getLength()](#getLength--) | Ein Längenwert, wenn diese Schriftgröße damit definiert wurde, sonst wird eine Ausnahme ausgelöst. |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Gibt an, ob diese Schriftgröße mit einer absoluten Größe als Schlüsselwort definiert ist, basierend auf der Standard‑Schriftgröße des Benutzers (die medium ist). |
|
|  | [isRelativeSize()](#isRelativeSize--) | Gibt an, ob diese Schriftgröße mit einer relativen Größe als Schlüsselwort definiert ist. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Bestimmt, ob diese Schriftgrößen‑Instanz dem angegebenen Wert entspricht. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Schriftgrößen‑Instanz dem nicht gecasteten angegebenen Wert entspricht. |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code für diese Instanz zurück |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Prüft, ob zwei \"FontSize\"‑Werte gleich sind |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Prüft, ob zwei \"FontSize\"‑Werte ungleich sind |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Erstellt eine Schriftgröße aus der angegebenen Länge |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Versucht, ein angegebenes Schlüsselwort als gültigen Schlüsselwortwert der 'font-size' zu erkennen und gibt es bei Erfolg zurück, andernfalls NULL. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Mittlere Größe. Anfangswert.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Die sehr kleine absolute Größe


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Die mittel kleine absolute Größe


### Small {#Small}
```
public static final FontSize Small
```


Die normalerweise kleine absolute Größe


### Large {#Large}
```
public static final FontSize Large
```


Die normalerweise große absolute Größe


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Die mittel große absolute Größe


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Die sehr große absolute Größe


### Larger {#Larger}
```
public static final FontSize Larger
```


Größere relative Größe - font wird größer relativ zur Schriftgröße des Elternelements, ungefähr im Verhältnis, das zur Trennung der obigen absoluten Größen‑Schlüsselwörter verwendet wird.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Kleinere relative Größe - font wird kleiner relativ zur Schriftgröße des Elternelements, ungefähr im Verhältnis, das zur Trennung der obigen absoluten Größen‑Schlüsselwörter verwendet wird.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Gibt an, ob diese Schriftgröße einen Anfangswert hat (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Gibt den Wert dieser Schriftgröße als Zeichenkette zurück


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Gibt an, ob diese Schriftgröße mit einem [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) Wert definiert ist


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Ein Längenwert, wenn diese Schriftgröße damit definiert wurde, sonst wird eine Ausnahme ausgelöst.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Gibt an, ob diese Schriftgröße mit einer absoluten Größe als Schlüsselwort definiert ist, basierend auf der Standard‑Schriftgröße des Benutzers (die medium ist).


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Gibt an, ob diese Schriftgröße mit einer relativen Größe als Schlüsselwort definiert ist. Die Schrift wird relativ zur Schriftgröße des übergeordneten Elements größer oder kleiner sein, ungefähr im Verhältnis, das zur Trennung der absoluten Größen‑Schlüsselwörter verwendet wird.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Bestimmt, ob diese Schriftgrößen‑Instanz dem angegebenen Wert entspricht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Andere Schriftgrößen‑Instanz |
|

**Returns:**
boolean - true, wenn gleich, sonst false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Schriftgrößen‑Instanz dem nicht gecasteten angegebenen Wert entspricht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere nicht gecastete Schriftgrößen‑Instanz, kann null sein |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Prüft, ob zwei \"FontSize\"‑Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Erster zu prüfender Wert |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Zweiter zu prüfender Wert |
|

**Returns:**
boolean - true, wenn gleich, sonst false

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Prüft, ob zwei \"FontSize\"‑Werte ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Erster zu prüfender Wert |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Zweiter zu prüfender Wert |
|

**Returns:**
boolean - false, wenn gleich, sonst true

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Erstellt eine Schriftgröße aus der angegebenen Länge


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ein Längenwert, darf nicht einheitenlos oder negativ sein |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Versucht, ein angegebenes Schlüsselwort als gültigen Schlüsselwortwert der 'font-size' zu erkennen und gibt es bei Erfolg zurück, andernfalls NULL.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | keyword | java.lang.String | Ein Schlüsselwort zum Parsen |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Ergebnis, wenn das Parsen erfolgreich war, sonst #Medium.Medium |
|

**Returns:**
boolean - true, wenn das Parsen erfolgreich war, sonst false

