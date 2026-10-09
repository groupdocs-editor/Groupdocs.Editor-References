---
title: "ArgbColor"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett färgvärde i ARGB‑format med konverterare och serialiserare"
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Representerar ett färgvärde i ARGB‑format med konverterare och serialiserare

<br />

*** ** * ** ***

Denna typ är avsedd att vara användbar för (men inte begränsad till) CSS‑operationer. Se mer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Skapar ett [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-värde från angivna röd, grön, blå och alfa‑kanaler |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Skapar ett [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-värde från angivna röd, grön och blå kanaler, medan alfa‑kanalen är helt ogenomskinlig |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Skapar en helt ogenomskinlig (A=255) färg från ett enda värde, som kommer att tillämpas på alla kanaler |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Skapar ett [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-värde från angiven [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) |
|
|  | [getValue()](#getValue--) | Hämtar Int32‑värdet för färgen. |
|
|  | [getA()](#getA--) | Hämtar alfa‑delen av färgen. |
|
|  | [getAlpha()](#getAlpha--) | Hämtar alfa‑delen av färgen i procent (0..1). |
|
|  | [getR()](#getR--) | Hämtar den röda delen av färgen. |
|
|  | [getG()](#getG--) | Hämtar den gröna delen av färgen. |
|
|  | [getB()](#getB--) | Hämtar den blåa delen av färgen. |
|
|  | [isEmpty()](#isEmpty--) | Oinitierad färg - alla 4 kanaler är satta till 0. |
|
|  | [isDefault()](#isDefault--) | Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-objekt är standard (Transparent) - alla 4 kanaler är satta till 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt är helt genomskinligt - dess Alpha-kanal har det minsta (0) värdet, så de andra R-, G- och B-kanalerna har ingen synlig effekt. |
|
|  | [isTranslucent()](#isTranslucent--) | Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt är halvgenomskinligt (inte helt genomskinligt, men inte heller helt ogenomskinligt). |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt är helt ogenomskinligt, utan transparens (dess Alpha-kanal har maximalt värde). |
|
|  | [toSystemColor()](#toSystemColor--) | Konverterar ett värde från detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till ett [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)-objekt och returnerar det. |
|
|  | [toRGBA()](#toRGBA--) | Serialiserar detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till 'rgba'-CSS-funktionsnotationen. |
|
|  | [toRGB()](#toRGB--) | Serialiserar detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till 'rgb'-CSS-funktionsnotationen. |
|
|  | [serializeDefault()](#serializeDefault--) | Serialiserar detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till den mest lämpliga CSS-funktionsnotationen beroende på genomskinlighet. |
|
|  | [toString()](#toString--) | Samma som #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Jämför två färger och returnerar ett boolean‑värde som indikerar om de två matchar. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Jämför två färger och returnerar ett boolean‑värde som indikerar om de två inte matchar. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Kontrollerar om två [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) färger är lika. |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Kontrollerar om två [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) färger är lika. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Testar om ett annat objekt är lika med detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt. |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod som definierar den aktuella färgen. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Skapar ett [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-värde från angivna röd, grön, blå och alfa‑kanaler


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | röd | int | Röd kanalvärde |
|
|  | grön | int | Grön kanalvärde |
|
|  | blå | int | Blå kanalvärde |
|
|  | alpha | int | Alpha-kanalvärde |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Skapar ett [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-värde från angivna röd, grön och blå kanaler, medan alfa‑kanalen är helt ogenomskinlig


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | röd | int | Röd kanalvärde |
|
|  | grön | int | Grön kanalvärde |
|
|  | blå | int | Blå kanalvärde |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Skapar en helt ogenomskinlig (A=255) färg från ett enda värde, som kommer att tillämpas på alla kanaler


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte | Ett byte‑värde, samma för Röd-, Grön- och Blå-kanalerna. |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Skapar ett [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-värde från angiven [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| färg | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Hämtar Int32‑värdet för färgen.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Hämtar alfa‑delen av färgen.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Hämtar alfa‑delen av färgen i procent (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Hämtar den röda delen av färgen.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Hämtar den gröna delen av färgen.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Hämtar den blåa delen av färgen.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Oinitierad färg - alla 4 kanaler är satta till 0. Samma som Standard och Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)-objekt är standard (Transparent) - alla 4 kanaler är satta till 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt är helt genomskinligt - dess Alpha-kanal har det minsta (0) värdet, så de andra R-, G- och B-kanalerna har ingen synlig effekt.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt är halvgenomskinligt (inte helt genomskinligt, men inte heller helt ogenomskinligt).


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Indikerar om detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt är helt ogenomskinligt, utan transparens (dess Alpha-kanal har maximalt värde).


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Konverterar ett värde från detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till ett [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)-objekt och returnerar det.


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serialiserar detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till 'rgba'-CSS-funktionsnotationen.


**Returns:**
java.lang.String - En sträng med formatet 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serialiserar detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till 'rgb'-CSS-funktionsnotationen.


**Returns:**
java.lang.String - En sträng med formatet 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialiserar detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt till den mest lämpliga CSS-funktionsnotationen beroende på genomskinlighet.


**Returns:**
java.lang.String - En sträng med formatet 'rgba(r, g, b, a)' eller 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Samma som #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Samma returvärde som i #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Jämför två färger och returnerar ett boolean‑värde som indikerar om de två matchar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Den första färgen att använda. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Den andra färgen att använda. |
|

**Returns:**
boolean - Sant om båda färgerna är lika, annars falskt.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Jämför två färger och returnerar ett boolean‑värde som indikerar om de två inte matchar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Den första färgen att använda. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Den andra färgen att använda. |
|

**Returns:**
boolean - Sant om båda färgerna inte är lika, annars falskt.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Kontrollerar om två [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) färger är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Den andra [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) färgen |
|

**Returns:**
boolean - Sant om båda färgerna är lika, annars falskt.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Kontrollerar om två [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) färger är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Den andra [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) färgen, kastad till ICssDataType |
|

**Returns:**
boolean - Sant om båda färgerna är lika, annars falskt.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Testar om ett annat objekt är lika med detta [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | annan | java.lang.Object | Objektet att testa med. |
|

**Returns:**
boolean - Sant om de två objekten är lika, annars falskt.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod som definierar den aktuella färgen.


**Returns:**
int - Det heltalsvärde som hashkoden har.

