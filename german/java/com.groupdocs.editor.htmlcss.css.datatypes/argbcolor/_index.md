---
title: "ArgbColor"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt einen Farbwert im ARGB-Format mit Konvertern und Serialisierern dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
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

Dieser Typ ist dafür ausgelegt, für (aber nicht ausschließlich) CSS‑Operationen nützlich zu sein. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Wert aus den angegebenen Rot-, Grün-, Blau- und Alpha‑Kanälen |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Wert aus den angegebenen Rot-, Grün- und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig ist |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Wert, der auf alle Kanäle angewendet wird |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Wert aus dem angegebenen [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) |
|
|  | [getValue()](#getValue--) | Gibt den Int32‑Wert der Farbe zurück. |
|
|  | [getA()](#getA--) | Gibt den Alpha‑Teil der Farbe zurück. |
|
|  | [getAlpha()](#getAlpha--) | Gibt den Alpha‑Teil der Farbe in Prozent (0..1) zurück. |
|
|  | [getR()](#getR--) | Gibt den Rot‑Teil der Farbe zurück. |
|
|  | [getG()](#getG--) | Gibt den Grün‑Teil der Farbe zurück. |
|
|  | [getB()](#getB--) | Gibt den Blau‑Teil der Farbe zurück. |
|
|  | [isEmpty()](#isEmpty--) | Nicht initialisierte Farbe – alle 4 Kanäle sind auf 0 gesetzt. |
|
|  | [isDefault()](#isDefault--) | Zeigt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz standardmäßig (Transparent) ist – alle 4 Kanäle sind auf 0 gesetzt |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Zeigt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig transparent ist – ihr Alpha‑Kanal hat den Minimalwert (0), sodass die anderen R‑, G‑ und B‑Kanäle keine sichtbare Wirkung haben. |
|
|  | [isTranslucent()](#isTranslucent--) | Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz transluzent ist (nicht vollständig transparent, aber auch nicht vollständig undurchsichtig) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha-Kanal hat den Maximalwert) |
|
|  | [toSystemColor()](#toSystemColor--) | Konvertiert einen Wert dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) Instanz und gibt sie zurück |
|
|  | [toRGBA()](#toRGBA--) | Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die 'rgba'-CSS-Funktionsnotation |
|
|  | [toRGB()](#toRGB--) | Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die 'rgb'-CSS-Funktionsnotation |
|
|  | [serializeDefault()](#serializeDefault--) | Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die am besten geeignete CSS-Funktionsnotation, abhängig von der Durchsichtigkeit |
|
|  | [toString()](#toString--) | Wie #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht übereinstimmen. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Testet, ob ein anderes Objekt dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz gleich ist. |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode zurück, der die aktuelle Farbe definiert. |
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


Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Wert aus den angegebenen Rot-, Grün-, Blau- und Alpha‑Kanälen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rot | int | Rot-Kanalwert |
|
|  | grün | int | Grün-Kanalwert |
|
|  | blau | int | Blau-Kanalwert |
|
|  | alpha | int | Alpha-Kanalwert |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Wert aus den angegebenen Rot-, Grün- und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rot | int | Rot-Kanalwert |
|
|  | grün | int | Grün-Kanalwert |
|
|  | blau | int | Blau-Kanalwert |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Wert, der auf alle Kanäle angewendet wird


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | Byte | Ein Bytewert, gleich für Rot-, Grün- und Blau-Kanäle |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Erstellt einen [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Wert aus dem angegebenen [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)


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


Gibt den Int32‑Wert der Farbe zurück.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Gibt den Alpha‑Teil der Farbe zurück.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Gibt den Alpha‑Teil der Farbe in Prozent (0..1) zurück.


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Gibt den Rot‑Teil der Farbe zurück.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Gibt den Grün‑Teil der Farbe zurück.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Gibt den Blau‑Teil der Farbe zurück.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Nicht initialisierte Farbe – alle 4 Kanäle sind auf 0 gesetzt. Gleich wie Standard und Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Zeigt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz standardmäßig (Transparent) ist – alle 4 Kanäle sind auf 0 gesetzt


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Zeigt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig transparent ist – ihr Alpha‑Kanal hat den Minimalwert (0), sodass die anderen R‑, G‑ und B‑Kanäle keine sichtbare Wirkung haben.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz transluzent ist (nicht vollständig transparent, aber auch nicht vollständig undurchsichtig)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Gibt an, ob diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha-Kanal hat den Maximalwert)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Konvertiert einen Wert dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) Instanz und gibt sie zurück


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die 'rgba'-CSS-Funktionsnotation


**Returns:**
java.lang.String - Ein String im Format 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die 'rgb'-CSS-Funktionsnotation


**Returns:**
java.lang.String - Ein String im Format 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialisiert diese [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz in die am besten geeignete CSS-Funktionsnotation, abhängig von der Durchsichtigkeit


**Returns:**
java.lang.String - Ein String im Format 'rgba(r, g, b, a)' oder 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Wie #serializeDefault.serializeDefault


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
boolean – Wahr, wenn beide Farben gleich sind, sonst falsch.

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
boolean – Wahr, wenn beide Farben nicht gleich sind, sonst falsch.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Die andere [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farbe |
|

**Returns:**
boolean – Wahr, wenn beide Farben gleich sind, sonst falsch.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Prüft zwei [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farben auf Gleichheit


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Die andere [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Farbe, umgewandelt zum ICssDataType |
|

**Returns:**
boolean – Wahr, wenn beide Farben gleich sind, sonst falsch.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Testet, ob ein anderes Objekt dieser [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) Instanz gleich ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | andere | java.lang.Object | Das Objekt, mit dem getestet wird. |
|

**Returns:**
boolean – Wahr, wenn die beiden Objekte gleich sind, sonst falsch.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode zurück, der die aktuelle Farbe definiert.


**Returns:**
int – Der ganzzahlige Wert des Hashcodes.

