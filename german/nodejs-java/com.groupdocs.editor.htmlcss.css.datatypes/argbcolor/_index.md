---
title: "ArgbColor"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt einen Farbwert im ARGB-Format mit Konvertern und Serialisierern dar."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Stellt einen Farbwert im ARGB-Format mit Konvertern und Serialisierern dar.

<br />

*** ** * ** ***

Dieser Typ ist für (aber nicht ausschließlich) CSS‑Operationen gedacht. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-Wert aus den angegebenen Rot-, Grün-, Blau- und Alpha‑Kanälen |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-Wert aus den angegebenen Rot-, Grün- und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig ist |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Wert, der auf alle Kanäle angewendet wird. |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-Wert aus dem angegebenen [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) |
|
|  | [getValue()](#getValue--) | Liefert den Int32‑Wert der Farbe. |
|
|  | [getA()](#getA--) | Liefert den Alpha‑Teil der Farbe. |
|
|  | [getAlpha()](#getAlpha--) | Liefert den Alpha‑Teil der Farbe in Prozent (0..1). |
|
|  | [getR()](#getR--) | Liefert den Rot‑Teil der Farbe. |
|
|  | [getG()](#getG--) | Liefert den grünen Teil der Farbe. |
|
|  | [getB()](#getB--) | Liefert den blauen Teil der Farbe. |
|
|  | [isEmpty()](#isEmpty--) | Nicht initialisierte Farbe - alle 4 Kanäle sind auf 0 gesetzt. |
|
|  | [isDefault()](#isDefault--) | Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz Standard (Transparent) ist - alle 4 Kanäle sind auf 0 gesetzt. |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig transparent ist - ihr Alpha‑Kanal hat den Minimalwert (0), sodass die anderen R‑, G‑ und B‑Kanäle keine sichtbare Wirkung haben. |
|
|  | [isTranslucent()](#isTranslucent--) | Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz transluzent (nicht vollständig transparent, aber auch nicht vollständig undurchsichtig) ist. |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha‑Kanal hat den Maximalwert). |
|
|  | [toSystemColor()](#toSystemColor--) | Konvertiert einen Wert dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) Instanz und gibt sie zurück. |
|
|  | [toRGBA()](#toRGBA--) | Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die CSS‑Funktionsnotation 'rgba'. |
|
|  | [toRGB()](#toRGB--) | Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die CSS‑Funktionsnotation 'rgb'. |
|
|  | [serializeDefault()](#serializeDefault--) | Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die am besten geeignete CSS‑Funktionsnotation, abhängig von der Transparenz. |
|
|  | [toString()](#toString--) | Gleich wie #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht übereinstimmen. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit. |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Testet, ob ein anderes Objekt dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz gleich ist. |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash‑Code zurück, der die aktuelle Farbe definiert. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-Wert aus den angegebenen Rot-, Grün-, Blau- und Alpha‑Kanälen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rot | int | Wert des Rot‑Kanals |
|
|  | grün | int | Wert des Grün‑Kanals |
|
|  | blau | int | Blaukanalwert |
|
|  | Alpha | int | Alphakanalwert |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-Wert aus den angegebenen Rot-, Grün- und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rot | int | Wert des Rot‑Kanals |
|
|  | grün | int | Wert des Grün‑Kanals |
|
|  | blau | int | Blaukanalwert |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Wert, der auf alle Kanäle angewendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | Byte | Ein Bytewert, gleich für Rot-, Grün- und Blaukanäle |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-Wert aus dem angegebenen [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Farbe | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Liefert den Int32‑Wert der Farbe.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Liefert den Alpha‑Teil der Farbe.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Liefert den Alpha‑Teil der Farbe in Prozent (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Liefert den Rot‑Teil der Farbe.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Liefert den grünen Teil der Farbe.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Liefert den blauen Teil der Farbe.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Nicht initialisierte Farbe - alle 4 Kanäle sind auf 0 gesetzt. Gleich wie Default und Transparent.


**Returns:**
boolesch
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz Standard (Transparent) ist - alle 4 Kanäle sind auf 0 gesetzt.


**Returns:**
boolesch
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig transparent ist - ihr Alpha‑Kanal hat den Minimalwert (0), sodass die anderen R‑, G‑ und B‑Kanäle keine sichtbare Wirkung haben.


**Returns:**
boolesch
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz transluzent (nicht vollständig transparent, aber auch nicht vollständig undurchsichtig) ist.


**Returns:**
boolesch
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha‑Kanal hat den Maximalwert).


**Returns:**
boolesch
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Konvertiert einen Wert dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) Instanz und gibt sie zurück.


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die CSS‑Funktionsnotation 'rgba'.


**Returns:**
java.lang.String - Eine Zeichenkette im Format 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die CSS‑Funktionsnotation 'rgb'.


**Returns:**
java.lang.String - Eine Zeichenkette im Format 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die am besten geeignete CSS‑Funktionsnotation, abhängig von der Transparenz.


**Returns:**
java.lang.String - Eine Zeichenkette im Format 'rgba(r, g, b, a)' oder 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Gleich wie #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Derselbe Rückgabewert wie in #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Die erste zu verwendende Farbe. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Die zweite zu verwendende Farbe. |
|

**Returns:**
boolean - Wahr, wenn beide Farben gleich sind, sonst falsch.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht übereinstimmen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Die erste zu verwendende Farbe. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Die zweite zu verwendende Farbe. |
|

**Returns:**
boolean - Wahr, wenn beide Farben nicht gleich sind, sonst falsch.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Die andere [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farbe |
|

**Returns:**
boolean - Wahr, wenn beide Farben gleich sind, sonst falsch.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Die andere [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farbe, gecastet zu ICssDataType |
|

**Returns:**
boolean - Wahr, wenn beide Farben gleich sind, sonst falsch.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Testet, ob ein anderes Objekt dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz gleich ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | andere | java.lang.Object | Das zu testende Objekt. |
|

**Returns:**
boolean - Wahr, wenn die beiden Objekte gleich sind, sonst falsch.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash‑Code zurück, der die aktuelle Farbe definiert.


**Returns:**
int - Der ganzzahlige Wert des Hashcodes.

