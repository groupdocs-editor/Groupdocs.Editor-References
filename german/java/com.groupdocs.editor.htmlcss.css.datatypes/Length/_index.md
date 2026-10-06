---
title: "Länge"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt einen CSS-Längenwert in jeder unterstützten Einheit dar, einschließlich Prozentwerten    und einheitenloser Typen."
type: docs
weight: 12
url: /de/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Stellt einen CSS-Längenwert in jeder unterstützten Einheit dar, einschließlich Prozentwerten
und einheitenloser Typ. Werte können ganzzahlig oder Fließkomma sein, negativ, null und
positiv. Unveränderliche Struktur.

*** ** * ** ***


Dieser Typ umfasst die folgenden CSS-Datentypen:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Length()](#Length--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Einheitenlose ganze Null – Standardwert, derselbe wie der parameterlose Standardwert |
Konstruktor
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Erstellt und gibt eine Instanz des Typs Länge zurück, basierend auf einer angegebenen Fließkommazahl |
und Einheit
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Erstellt und gibt eine Instanz des Typs Länge zurück, basierend auf einer angegebenen Doppelpräzisionszahl |
und Einheit
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Erstellt und gibt eine Instanz des Typs Länge zurück, basierend auf einer angegebenen Ganzzahl |
Zahl und Einheit
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Bestimmt, ob diese Instanz eine einheitenlose Null ist oder nicht. |
|
|  | [isDefault()](#isDefault--) | Gibt an, ob diese Length-Instanz einen Standardwert \\u2014 einheitenlos hat |
null.
|
|  | [getUnitType()](#getUnitType--) | Gibt den Einheitstyp dieser Length-Instanz zurück. |
|
|  | [isInteger()](#isInteger--) | Gibt an, ob der numerische Wert dieser Length-Instanz war |
ursprünglich als ganze Zahl (INT32) angegeben und gespeichert
|
|  | [isFloat()](#isFloat--) | Gibt an, ob der numerische Wert dieser Length-Instanz war |
ursprünglich angegeben und als Fließkommazahl (FP32) gespeichert
|
|  | [getFloatValue()](#getFloatValue--) | Gibt einen Fließkomma‑numerischen Wert der Length‑Instanz zurück. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Gibt einen ganzzahligen numerischen Wert dieser Length‑Instanz zurück, falls er |
intern als Ganzzahl gespeichert ist, oder wirft eine Ausnahme, falls er es war
ursprünglich als Fließkommazahl gespeichert.
|
|  | [isAbsolute()](#isAbsolute--) | Ermittelt, ob die Länge in absoluten Einheiten angegeben ist. |
|
|  | [isRelative()](#isRelative--) | Ermittelt, ob die Länge in relativen Einheiten angegeben ist. |
|
|  | [isZero()](#isZero--) | Bestimmt, ob der numerische Wert dieser Länge eine Null ist |
|
|  | [isNegative()](#isNegative--) | Bestimmt, ob der numerische Wert dieser Länge negativ ist |
|
|  | [isPositive()](#isPositive--) | Bestimmt, ob der numerische Wert dieser Länge positiv ist |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Der Wert hat keinen Einheitstyp, ist aber keine Null – positiv oder negativ |
number
|
|  | [toPixel()](#toPixel--) | Konvertiert die Länge, falls möglich, in eine Anzahl von Pixeln. |
|
|  | [to(int unit)](#to-int-) | Konvertiert die Länge, falls möglich, in die angegebene Einheit. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Gibt eine Zeichenkettenrepräsentation dieser Länge im angegebenen Einheitstyp zurück. |
|
|  | [serializeDefault()](#serializeDefault--) | Gibt eine Zeichenkettenrepräsentation dieser Länge in ihrer ursprünglichen nativen |
Form (wie sie gespeichert ist), ohne den Längenwert in eine andere
Einheitstyp
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Definiert, ob dieser Wert gleich der anderen angegebenen Länge ist |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Länge gleich dem angegebenen Objekt ist |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Multipliziert die gegebene Length mit dem angegebenen Faktor |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Prüft die Gleichheit der beiden angegebenen Längen. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Prüft die Ungleichheit der beiden angegebenen Längen. |
|
|  | [hashCode()](#hashCode--) | Berechnet und gibt einen Hash‑Code dieser Length‑Instanz zurück, indem er kombiniert |
Hash‑Codes des Werts und des Einheitstyps
|
|  | [deepClone()](#deepClone--) | Gibt eine vollständige Kopie dieser Length‑Instanz zurück |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Versucht, den angegebenen Einheitennamen zu analysieren und den entsprechenden Wert von a zurückzugeben |
Einheit-Enum.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Versucht, einen angegebenen String als Length-Wert zu analysieren, einschließlich seines |
numerischen Werts und Einheitennamens
|
|  | [parse(String input)](#parse-java.lang.String-) | Analysiert und gibt den angegebenen String als Length-Wert zurück, einschließlich seines |
numerischen Werts und Einheitennamens, oder wirft bei einem Fehler eine Ausnahme.
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Einheitenlose ganze Null – Standardwert, derselbe wie der parameterlose Standardwert
Konstruktor


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Erstellt und gibt eine Instanz des Typs Länge zurück, basierend auf einer angegebenen Fließkommazahl
und Einheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | float | \>Beliebige Fließkommazahl (FP32) |
|
|  | Einheit | int | Beliebiger gültiger Einheitstyp |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Erstellt und gibt eine Instanz des Typs Länge zurück, basierend auf einer angegebenen Doppelpräzisionszahl
und Einheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Beliebige Double‑Zahl (FP64), die in Float (FP32) konvertiert wird |
|
|  | Einheit | int | Beliebiger gültiger Einheitstyp |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Erstellt und gibt eine Instanz des Typs Länge zurück, basierend auf einer angegebenen Ganzzahl
Zahl und Einheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Beliebige Ganzzahl |
|
|  | Einheit | int | Beliebiger gültiger Einheitstyp |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Bestimmt, ob diese Instanz ein einheitenloses Null ist oder nicht. Einheitenlose Null
ist der Standardwert dieses Typs. Gleich wie die Eigenschaft IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Gibt an, ob diese Length-Instanz einen Standardwert \\u2014 einheitenlos hat
Null. Gleich wie die Eigenschaft IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Gibt den Einheitstyp dieser Length-Instanz zurück.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Gibt an, ob der numerische Wert dieser Length-Instanz war
ursprünglich als ganze Zahl (INT32) angegeben und gespeichert


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Gibt an, ob der numerische Wert dieser Length-Instanz war
ursprünglich angegeben und als Fließkommazahl (FP32) gespeichert


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Gibt einen Fließkomma‑Numerikwert der Length-Instanz zurück. Wirft niemals ein
Ausnahme - konvertiert bei Bedarf den Integer‑Wert zu Float.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Gibt einen ganzzahligen numerischen Wert dieser Length‑Instanz zurück, falls er
intern als Ganzzahl gespeichert ist, oder wirft eine Ausnahme, falls er es war
ursprünglich als Fließkommazahl gespeichert.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Ermittelt, ob die Länge in absoluten Einheiten angegeben ist. Eine solche Länge kann
in Pixel umgewandelt werden.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Ermittelt, ob die Länge in relativen Einheiten angegeben ist. Eine solche Länge kann nicht
in Pixel umgewandelt werden.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Bestimmt, ob der numerische Wert dieser Länge eine Null ist


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Bestimmt, ob der numerische Wert dieser Länge negativ ist


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Bestimmt, ob der numerische Wert dieser Länge positiv ist


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Der Wert hat keinen Einheitstyp, ist aber keine Null – positiv oder negativ
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Konvertiert die Länge, falls möglich, in eine Anzahl von Pixeln. Wenn die aktuelle
Einheit relativ ist, wird eine Ausnahme ausgelöst.


**Returns:**
float - Die Anzahl der Pixel, die die aktuelle Länge darstellt.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Konvertiert die Länge, falls möglich, in die angegebene Einheit. Wenn die aktuelle oder
die angegebene Einheit relativ ist, wird eine Ausnahme ausgelöst.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Einheit | int | Die Einheit, in die konvertiert werden soll. |
|

**Returns:**
float - Der Wert in der angegebenen Einheit der aktuellen Länge.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Gibt eine Zeichenkettenrepräsentation dieser Länge im angegebenen Einheitstyp zurück.
Der numerische Wert wird entsprechend der Änderung des Einheitentyps konvertiert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Einheit | int | Angegebene Einheit, in die diese Instanz vor der Serialisierung in einen String konvertiert werden soll. Sollte gültig sein. Darf nicht einheitenlos sein. |
|

**Returns:**
java.lang.String - String-Darstellung

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Gibt eine Zeichenkettenrepräsentation dieser Länge in ihrer ursprünglichen nativen
Form (wie sie gespeichert ist), ohne den Längenwert in eine andere
Einheitstyp


**Returns:**
java.lang.String - String-Instanz

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Definiert, ob dieser Wert gleich der anderen angegebenen Länge ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Andere Instanz des Typs Length |
|

**Returns:**
boolean - Wahr, wenn gleich, sonst falsch

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Länge gleich dem angegebenen Objekt ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere Instanz des Typs Length, die in ein System.Object oder einen anderen abstrakten Typ oder ein Interface verpackt ist |
|

**Returns:**
boolean - Wahr, wenn gleich, sonst falsch

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Multipliziert die gegebene Length mit dem angegebenen Faktor


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - Multiplikand |
|
|  | Faktor | int | Beliebige ganze Zahl - Faktor |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Prüft die Gleichheit der beiden angegebenen Längen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Der linke Längenoperand. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Der rechte Längenoperand. |
|

**Returns:**
boolean - Wahr, wenn beide Längen gleich sind, sonst falsch.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Prüft die Ungleichheit der beiden angegebenen Längen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Der linke Längenoperand. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Der rechte Längenoperand. |
|

**Returns:**
boolean - Wahr, wenn beide Längen ungleich sind, sonst falsch.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berechnet und gibt einen Hash‑Code dieser Length‑Instanz zurück, indem er kombiniert
Hash‑Codes des Werts und des Einheitstyps


**Returns:**
int - Ganzzahl

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Gibt eine vollständige Kopie dieser Length‑Instanz zurück


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Versucht, den angegebenen Einheitennamen zu analysieren und den entsprechenden Wert von a zurückzugeben
Unit-Enum. Gibt LengthUnit.Unitless zurück, wenn keine passende LengthUnit gefunden werden kann.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | unitName | java.lang.String | String, der einen Einheitennamen darstellt |
|

**Returns:**
int - Wert des Unit-Enums in jedem Fall, LengthUnit.Unitless wenn keine passende Einheit gefunden wird

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Versucht, einen angegebenen String als Length-Wert zu analysieren, einschließlich seines
numerischen Werts und Einheitennamens


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Eingabe | java.lang.String | Eingabestring, der geparst werden soll |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ausgabeparameter, der das Ergebnis des Parsens enthält. Wenn das Parsen erfolglos ist, enthält er einen Standard‑Length‑Wert \\u2014 ein einheitenloses Null. |
|

**Returns:**
boolean - Wahr, wenn das Parsen erfolgreich ist, sonst falsch

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Analysiert und gibt den angegebenen String als Length-Wert zurück, einschließlich seines
numerischen Werts und Einheitennamens, oder wirft bei einem Fehler eine Ausnahme.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Eingabe | java.lang.String | Eingabestring, der geparst werden soll |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

