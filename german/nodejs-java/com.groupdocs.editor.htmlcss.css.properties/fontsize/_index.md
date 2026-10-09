---
title: "Schriftgröße"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt eine Schriftgröße als spezielle Einheit oder als Längenwert dar, der die Größe der Schrift angibt, historisch die Breite des Großbuchstabens M."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Stellt eine Schriftgröße als spezielle Einheit oder Längenwert dar, der die Größe der Schrift (historisch die Breite des Großbuchstabens \"M\") angibt.

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
|  | [XSmall](#XSmall) | Die mittelmäßige kleine absolute Größe |
|
|  | [Small](#Small) | Die normalerweise kleine absolute Größe |
|
|  | [Large](#Large) | Die normalerweise große absolute Größe |
|
|  | [XLarge](#XLarge) | Die mittelmäßige große absolute Größe |
|
|  | [XxLarge](#XxLarge) | Die sehr große absolute Größe |
|
|  | [Larger](#Larger) | Größere relative Größe - die Schrift wird relativ zur Schriftgröße des übergeordneten Elements größer sein, ungefähr im Verhältnis, das verwendet wird, um die obigen absolute-size-Schlüsselwörter zu trennen. |
|
|  | [Smaller](#Smaller) | Kleinere relative Größe - die Schrift wird relativ zur Schriftgröße des übergeordneten Elements kleiner sein, ungefähr im Verhältnis, das verwendet wird, um die obigen absolute-size-Schlüsselwörter zu trennen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isInitial()](#isInitial--) | Gibt an, ob diese Schriftgröße einen Anfangswert (Medium) hat |
|
|  | [getValue()](#getValue--) | Gibt den Wert dieser Schriftgröße als Zeichenkette zurück |
|
|  | [isLengthDefined()](#isLengthDefined--) | Gibt an, ob diese Schriftgröße mit einem [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)-Wert definiert ist |
|
|  | [getLength()](#getLength--) | Ein Längenwert, falls diese Schriftgröße damit definiert wurde, andernfalls wird eine Ausnahme ausgelöst |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Gibt an, ob diese Schriftgröße mit einer absoluten Größe als Schlüsselwort definiert ist, basierend auf der Standard-Schriftgröße des Benutzers (die Medium ist) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Gibt an, ob diese Schriftgröße mit einer relativen Größe als Schlüsselwort definiert ist. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Bestimmt, ob diese Schriftgrößen-Instanz gleich dem angegebenen ist |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Schriftgrößen-Instanz gleich dem angegebenen, nicht gecasteten ist |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code für diese Instanz zurück |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Überprüft, ob zwei "FontSize"-Werte gleich sind |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Überprüft, ob zwei "FontSize"-Werte nicht gleich sind |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Erstellt eine Schriftgröße aus der angegebenen Länge |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Versucht, ein angegebenes Schlüsselwort als gültigen Schlüsselwortwert von 'font-size' zu erkennen und gibt es bei Erfolg zurück, andernfalls NULL. |
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


Die mittelmäßige kleine absolute Größe


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


Die mittelmäßige große absolute Größe


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Die sehr große absolute Größe


### Larger {#Larger}
```
public static final FontSize Larger
```


Größere relative Größe - die Schrift wird relativ zur Schriftgröße des übergeordneten Elements größer sein, ungefähr im Verhältnis, das verwendet wird, um die obigen absolute-size-Schlüsselwörter zu trennen.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Kleinere relative Größe - die Schrift wird relativ zur Schriftgröße des übergeordneten Elements kleiner sein, ungefähr im Verhältnis, das verwendet wird, um die obigen absolute-size-Schlüsselwörter zu trennen.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Gibt an, ob diese Schriftgröße einen Anfangswert (Medium) hat


**Returns:**
boolesch
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


Gibt an, ob diese Schriftgröße mit einem [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)-Wert definiert ist


**Returns:**
boolesch
### getLength() {#getLength--}
```
public final Length getLength()
```


Ein Längenwert, falls diese Schriftgröße damit definiert wurde, andernfalls wird eine Ausnahme ausgelöst


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Gibt an, ob diese Schriftgröße mit einer absoluten Größe als Schlüsselwort definiert ist, basierend auf der Standard-Schriftgröße des Benutzers (die Medium ist)


**Returns:**
boolesch
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Gibt an, ob diese Schriftgröße mit einer relativen Größe als Schlüsselwort definiert ist. Die Schrift wird relativ zur Schriftgröße des übergeordneten Elements größer oder kleiner sein, ungefähr im Verhältnis, das zur Trennung der absoluten Größen‑Schlüsselwörter verwendet wird.


**Returns:**
boolesch
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Bestimmt, ob diese Schriftgrößen-Instanz gleich dem angegebenen ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Andere Schriftgrößen-Instanz |
|

**Returns:**
boolesch - true, wenn gleich, false sonst

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Schriftgrößen-Instanz gleich dem angegebenen, nicht gecasteten ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere nicht gecastete Schriftgrößen-Instanz, kann null sein |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Überprüft, ob zwei "FontSize"-Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Erster zu prüfender Wert |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Zweiter zu prüfender Wert |
|

**Returns:**
boolesch - true, wenn gleich, false sonst

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Überprüft, ob zwei "FontSize"-Werte nicht gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Erster zu prüfender Wert |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Zweiter zu prüfender Wert |
|

**Returns:**
boolesch - false, wenn gleich, true sonst

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


Versucht, ein angegebenes Schlüsselwort als gültigen Schlüsselwortwert von 'font-size' zu erkennen und gibt es bei Erfolg zurück, andernfalls NULL.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Schlüsselwort | java.lang.String | Ein Schlüsselwort zum Parsen |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Ergebnis, wenn das Parsen erfolgreich war, sonst #Medium.Medium |
|

**Returns:**
boolesch - true, wenn das Parsen erfolgreich war, false sonst

