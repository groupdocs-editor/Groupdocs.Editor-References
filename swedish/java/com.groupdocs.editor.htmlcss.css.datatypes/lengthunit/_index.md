---
title: "LengthUnit"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Alla stödjade längdenheter."
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Alla stödjade längdenheter.


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - ingen definierad längdenhet. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-längd). |
|
|  | [Cm](#Cm) | Cm. |
|
|  | [Mm](#Mm) | Mm. |
|
|  | [In](#In) | In. |
|
|  | [Pt](#Pt) | Pt. |
|
|  | [Pc](#Pc) | Pc. |
|
|  | [Ch](#Ch) | Ch. |
|
|  | [Rem](#Rem) | Rem. |
|
|  | [Vw](#Vw) | Vw - viewportbredd. |
|
|  | [Vh](#Vh) | Vh - viewporthöjd. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Värdet är relativt ett fast (externt) värde, som är kontext |
beroende.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Enhetslös - ingen definierad längdenhet. Standardvärde.


### Px {#Px}
```
public static final int Px
```


Pixel. Relativt visningsenheten. För skärmvisning, vanligtvis
en enhetspixel (punkt) på skärmen.


### Em {#Em}
```
public static final int Em
```


Em. Denna enhet representerar det beräknade teckenstorleken för elementet.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-längd). Denna enhet representerar x-höjden på elementets
teckensnitt. På teckensnitt med bokstaven 'x' är detta generellt höjden på
gemena bokstäver i teckensnittet; 1ex \\u2248 0.5em i många teckensnitt.


### Cm {#Cm}
```
public static final int Cm
```


Cm. En centimeter (10 millimeter).


### Mm {#Mm}
```
public static final int Mm
```


Mm. En millimeter.


### In {#In}
```
public static final int In
```


In. En tum (2,54 centimeter).


### Pt {#Pt}
```
public static final int Pt
```


Pt. En punkt är 1/72 tum eller 0,353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. En pica (12 punkter).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Denna enhet representerar bredden, eller mer exakt förskjutningen
mått, av glyphen '0' (noll, Unicode-tecknet U+0030) i
elementets teckensnitt.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Denna enhet representerar teckenstorleken för rot‑elementet (t.ex. den
font-size av \<html\>-elementet). När den används på font-size på
detta rot-element, den representerar dess ursprungliga värde.


### Vw {#Vw}
```
public static final int Vw
```


Vw - visningsportens bredd. 1/100 av bredden på visningsporten.


### Vh {#Vh}
```
public static final int Vh
```


Vh - visningsportens höjd. 1/100 av höjden på visningsporten.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 av det minsta värdet mellan höjden och bredden
på visningsporten.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 av det största värdet mellan höjden och bredden
på visningsporten.


### Percent {#Percent}
```
public static final int Percent
```


Värdet är relativt ett fast (externt) värde, som är kontext
beroende. 1% = 1/100 av det externa värdet.


### getUnit() {#getUnit--}
```
public static Integer[] getUnit()
```




**Returns:**
java.lang.Integer[]
### getUnits() {#getUnits--}
```
public static Map<Integer,String> getUnits()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
