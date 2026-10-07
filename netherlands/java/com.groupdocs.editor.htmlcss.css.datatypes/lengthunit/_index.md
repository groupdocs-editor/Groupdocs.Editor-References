---
title: "LengthUnit"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Alle ondersteunde lengteenheden."
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Alle ondersteunde lengteenheden.


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - geen gedefinieerde lengteenheid. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-lengte). |
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
|  | [Vw](#Vw) | Vw - viewportbreedte. |
|
|  | [Vh](#Vh) | Vh - viewporthoogte. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | De waarde is relatief ten opzichte van een vaste (externe) waarde, die context |
afhankelijk.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Eenheidsloos - geen gedefinieerde lengteenheid. Standaardwaarde.


### Px {#Px}
```
public static final int Px
```


Pixel. Relatief ten opzichte van het weergaveapparaat. Voor schermweergave, meestal
één apparaatpixel (punt) van het scherm.


### Em {#Em}
```
public static final int Em
```


Em. Deze eenheid vertegenwoordigt de berekende lettergrootte van het element.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-lengte). Deze eenheid vertegenwoordigt de x-hoogte van het element.
lettertype. Bij lettertypen met de 'x'-letter is dit over het algemeen de hoogte van
kleine letters in het lettertype; 1ex \\u2248 0.5em in veel lettertypen.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Eén centimeter (10 millimeter).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Eén millimeter.


### In {#In}
```
public static final int In
```


In. Eén inch (2,54 centimeter).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Eén punt is 1/72e van een inch of 0,353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Eén pica (12 punten).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Deze eenheid vertegenwoordigt de breedte, of preciezer de voortgang
maat, van het glyph '0' (nul, het Unicode‑teken U+0030) in de
lettertype van het element.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Deze eenheid vertegenwoordigt de lettergrootte van het root‑element (bijv. de
lettergrootte van het \<html\>-element). Wanneer toegepast op de lettergrootte op
dit root‑element, vertegenwoordigt het de initiële waarde.


### Vw {#Vw}
```
public static final int Vw
```


Vw - viewportbreedte. 1/100ste van de breedte van de viewport.


### Vh {#Vh}
```
public static final int Vh
```


Vh - viewporthoogte. 1/100 van de hoogte van de viewport.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 van de minimumwaarde tussen de hoogte en de breedte
van de viewport.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 van de maximumwaarde tussen de hoogte en de breedte
van de viewport.


### Percent {#Percent}
```
public static final int Percent
```


De waarde is relatief ten opzichte van een vaste (externe) waarde, die context
afhankelijk. 1% = 1/100 van de externe waarde.


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
