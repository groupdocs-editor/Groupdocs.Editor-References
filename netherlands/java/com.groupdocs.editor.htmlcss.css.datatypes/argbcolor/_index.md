---
title: "ArgbColor"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één kleurwaarde in ARGB‑formaat voor met converters en serializers."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Stelt één kleurwaarde in ARGB‑formaat voor met converters en serializers.

<br />

*** ** * ** ***

Dit type is ontworpen om nuttig te zijn voor (maar niet beperkt tot) CSS‑operaties. Zie meer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Maakt één [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) waarde aan vanuit opgegeven rode, groene, blauwe en alfakanalen |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Maakt één [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) waarde aan vanuit opgegeven rode, groene en blauwe kanalen, terwijl het alfakanaal volledig ondoorzichtig is |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Maakt een volledig ondoorzichtige (A=255) kleur aan vanuit één enkele waarde, die op alle kanalen wordt toegepast |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Maakt één [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) waarde aan vanuit opgegeven [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) |
|
|  | [getValue()](#getValue--) | Haalt de Int32‑waarde van de kleur op. |
|
|  | [getA()](#getA--) | Haalt het alfagedeelte van de kleur op. |
|
|  | [getAlpha()](#getAlpha--) | Haalt het alfagedeelte van de kleur op in percentage (0..1). |
|
|  | [getR()](#getR--) | Haalt het rode gedeelte van de kleur op. |
|
|  | [getG()](#getG--) | Haalt het groene gedeelte van de kleur op. |
|
|  | [getB()](#getB--) | Haalt het blauwe gedeelte van de kleur op. |
|
|  | [isEmpty()](#isEmpty--) | Niet‑geïnitieerde kleur - alle 4 kanalen zijn ingesteld op 0. |
|
|  | [isDefault()](#isDefault--) | Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie standaard (Transparent) is - alle 4 kanalen zijn ingesteld op 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie volledig transparant is - het alfakanaal heeft de minimum (0) waarde, waardoor de andere R-, G- en B-kanalen geen zichtbaar effect hebben. |
|
|  | [isTranslucent()](#isTranslucent--) | Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie doorschijnend is (niet volledig transparant, maar ook niet volledig ondoorzichtig) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie volledig ondoorzichtig is, zonder transparantie (het alfakanaal heeft de maximale waarde) |
|
|  | [toSystemColor()](#toSystemColor--) | Converteert een waarde van deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instantie en retourneert deze |
|
|  | [toRGBA()](#toRGBA--) | Serialiseert deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de 'rgba' CSS-functienotatie |
|
|  | [toRGB()](#toRGB--) | Serialiseert deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de 'rgb' CSS-functienotatie |
|
|  | [serializeDefault()](#serializeDefault--) | Serialiseert deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de meest geschikte CSS-functienotatie afhankelijk van doorschijnendheid |
|
|  | [toString()](#toString--) | Hetzelfde als #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vergelijkt twee kleuren en retourneert een boolean die aangeeft of de twee overeenkomen. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Vergelijkt twee kleuren en retourneert een boolean die aangeeft of de twee niet overeenkomen. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Controleert twee [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) kleuren op gelijkheid |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Controleert twee [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) kleuren op gelijkheid |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Test of een ander object gelijk is aan deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie. |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode die de huidige kleur definieert. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Maakt één [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) waarde aan vanuit opgegeven rode, groene, blauwe en alfakanalen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rood | int | Rood kanaalwaarde |
|
|  | groen | int | Groen kanaalwaarde |
|
|  | blauw | int | Blauw kanaalwaarde |
|
|  | alfa | int | Alfa kanaalwaarde |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Maakt één [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) waarde aan vanuit opgegeven rode, groene en blauwe kanalen, terwijl het alfakanaal volledig ondoorzichtig is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rood | int | Rood kanaalwaarde |
|
|  | groen | int | Groen kanaalwaarde |
|
|  | blauw | int | Blauw kanaalwaarde |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Maakt een volledig ondoorzichtige (A=255) kleur aan vanuit één enkele waarde, die op alle kanalen wordt toegepast


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte | Een byte-waarde, gelijk voor rode, groene en blauwe kanalen. |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Maakt één [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) waarde aan vanuit opgegeven [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| kleur | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Haalt de Int32‑waarde van de kleur op.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Haalt het alfagedeelte van de kleur op.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Haalt het alfagedeelte van de kleur op in percentage (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Haalt het rode gedeelte van de kleur op.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Haalt het groene gedeelte van de kleur op.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Haalt het blauwe gedeelte van de kleur op.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Niet-geïnitialiseerde kleur - alle 4 kanalen zijn ingesteld op 0. Hetzelfde als Default en Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie standaard (Transparent) is - alle 4 kanalen zijn ingesteld op 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie volledig transparant is - het alfakanaal heeft de minimum (0) waarde, waardoor de andere R-, G- en B-kanalen geen zichtbaar effect hebben.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie doorschijnend is (niet volledig transparant, maar ook niet volledig ondoorzichtig)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Geeft aan of deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie volledig ondoorzichtig is, zonder transparantie (het alfakanaal heeft de maximale waarde)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Converteert een waarde van deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instantie en retourneert deze


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serialiseert deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de 'rgba' CSS-functienotatie


**Returns:**
java.lang.String - Een string met het formaat 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serialiseert deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de 'rgb' CSS-functienotatie


**Returns:**
java.lang.String - Een string met het formaat 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialiseert deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie naar de meest geschikte CSS-functienotatie afhankelijk van doorschijnendheid


**Returns:**
java.lang.String - Een string met het formaat 'rgba(r, g, b, a)' of 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Hetzelfde als #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Zelfde retourwaarde als in #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Vergelijkt twee kleuren en retourneert een boolean die aangeeft of de twee overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | De eerste te gebruiken kleur. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | De tweede te gebruiken kleur. |
|

**Returns:**
boolean - Waar als beide kleuren gelijk zijn, anders onwaar.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Vergelijkt twee kleuren en retourneert een boolean die aangeeft of de twee niet overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | De eerste te gebruiken kleur. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | De tweede te gebruiken kleur. |
|

**Returns:**
boolean - Waar als beide kleuren niet gelijk zijn, anders onwaar.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Controleert twee [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) kleuren op gelijkheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | De andere [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) kleur |
|

**Returns:**
boolean - Waar als beide kleuren gelijk zijn, anders onwaar.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Controleert twee [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) kleuren op gelijkheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | De andere [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) kleur, gecast naar de ICssDataType |
|

**Returns:**
boolean - Waar als beide kleuren gelijk zijn, anders onwaar.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Test of een ander object gelijk is aan deze [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instantie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | anders | java.lang.Object | Het object om mee te testen. |
|

**Returns:**
boolean - Waar als de twee objecten gelijk zijn, anders onwaar.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode die de huidige kleur definieert.


**Returns:**
int - De gehele getalwaarde van de hashcode.

