---
title: "Förhållande"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en ratio CSS-datatyp som används för att beskriva bildförhållanden i mediaförfrågningar och för rasterbilder genom att ange förhållandet mellan två enhetslösa värden som kallas täljare och nämnare."
type: docs
weight: 14
url: /sv/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Representerar en "ratio" CSS-datatyp, som används för att beskriva bildförhållande
förhållanden i mediaförfrågningar och för rasterbilder genom att ange proportionen
mellan två enhetslösa värden som kallas "numerator" och "denominator". Oföränderlig
struct.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Single](#Single) | Enkel standardratio 1/1 |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Returnerar en täljare för detta förhållande |
|
|  | [getDenominator()](#getDenominator--) | Returnerar en nämnare för detta förhållande |
|
|  | [calculate()](#calculate--) | Beräknar och returnerar detta förhållande som ett enda flyttal |
|
|  | [getInverseRatio()](#getInverseRatio--) | Genererar och returnerar ett invers (reciprokt) förhållande för detta förhållande |
|
|  | [serializeDefault()](#serializeDefault--) | Serialiserar detta förhållande till en sträng och returnerar den |
|
|  | [toString()](#toString--) | Returnerar en strängrepresentation av detta förhållande; samma som |
\"SerializeDefault()\"
|
|  | [isDefault()](#isDefault--) | Bestämmer om detta förhållande har standardvärde eller är en "1/1" (Enkel) |
|
|  | [deepClone()](#deepClone--) | Returnerar en fullständig kopia av detta förhållande |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Bestämmer om detta objekt är lika med den angivna "Ratio"-instansen |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med angivet okastat objekt, |
vilket sannolikt är en annan "Ratio"-instans
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Jämför två förhållanden och returnerar ett booleskt värde som indikerar om de två matchar. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Jämför två förhållanden och returnerar ett booleskt värde som indikerar om de två inte |
matchar.
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt, som inte kan ändras under dess |
livstid
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Skapar och returnerar en Ratio-instans från angivet täljare och |
nämnare
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Enkel standardratio 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Returnerar en täljare för detta förhållande


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Returnerar en nämnare för detta förhållande


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Beräknar och returnerar detta förhållande som ett enda flyttal


**Returns:**
double - Flyttal med dubbel precision

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Genererar och returnerar ett invers (reciprokt) förhållande för detta förhållande


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialiserar detta förhållande till en sträng och returnerar den


**Returns:**
java.lang.String - Sträng i "täljare/nämnare"-format

### toString() {#toString--}
```
public String toString()
```


Returnerar en strängrepresentation av detta förhållande; samma som
\"SerializeDefault()\"


**Returns:**
java.lang.String - Sträng i "täljare/nämnare"-format

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bestämmer om detta förhållande har standardvärde eller är en "1/1" (Enkel)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Returnerar en fullständig kopia av detta förhållande


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Bestämmer om detta objekt är lika med den angivna "Ratio"-instansen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Annan Ratio-instans för att kontrollera likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bestämmer om detta objekt är lika med angivet okastat objekt,
vilket sannolikt är en annan "Ratio"-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | annan | java.lang.Object | Annan System.Object-instans, som sannolikt är av typen Ratio, för att kontrollera likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Jämför två förhållanden och returnerar ett booleskt värde som indikerar om de två matchar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Det första förhållandet att använda. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Det andra förhållandet att använda. |
|

**Returns:**
boolean - Sant om båda förhållandena är lika, annars falskt.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Jämför två förhållanden och returnerar ett booleskt värde som indikerar om de två inte
matchar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Det första förhållandet att använda. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Det andra förhållandet att använda. |
|

**Returns:**
boolean - Sant om båda förhållandena inte är lika, annars falskt.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt, som inte kan ändras under dess
livstid


**Returns:**
int - Signerat 4-byte heltal, som är oföränderligt för detta objekt

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Skapar och returnerar en Ratio-instans från angivet täljare och
nämnare


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | täljare | int | Täljare för förhållandet. Ska vara ett strikt positivt heltal. |
|
|  | nämnare | int | Nämnare för förhållandet. Ska vara ett strikt positivt heltal. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

