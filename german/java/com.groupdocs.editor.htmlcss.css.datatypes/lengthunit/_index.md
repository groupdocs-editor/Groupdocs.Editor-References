---
title: "LengthUnit"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Alle unterstützten Längeneinheiten"
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Alle unterstützten Längeneinheiten


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Unitless](#Unitless) | Einheitslos – keine definierte Längeneinheit. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-Länge). |
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
|  | [Vw](#Vw) | Vw - Viewport-Breite. |
|
|  | [Vh](#Vh) | Vh - Viewport-Höhe. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Der Wert ist relativ zu einem festen (externen) Wert, das ist Kontext |
abhängig.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Einheitenlos - keine definierte Längeneinheit. Standardwert.


### Px {#Px}
```
public static final int Px
```


Pixel. Relativ zum Anzeigegerät. Für Bildschirmanzeigen typischerweise
ein Gerätepixel (Punkt) des Displays.


### Em {#Em}
```
public static final int Em
```


Em. Diese Einheit stellt die berechnete Schriftgröße des Elements dar.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-Länge). Diese Einheit stellt die x-Höhe des Elements dar
Schrift. Bei Schriften mit dem Buchstaben 'x' ist dies im Allgemeinen die Höhe von
Kleinbuchstaben in der Schrift; 1ex \\u2248 0.5em in vielen Schriften.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Ein Zentimeter (10 Millimeter).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Ein Millimeter.


### In {#In}
```
public static final int In
```


In. Ein Zoll (2,54 Zentimeter).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Ein Punkt ist 1/72 Zoll oder 0,353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Ein Pica (12 Punkte).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Diese Einheit stellt die Breite dar, oder genauer den Vorlauf
Messung, des Glyphs '0' (Null, das Unicode‑Zeichen U+0030) im
Schrift des Elements.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Diese Einheit stellt die Schriftgröße des Wurzelelements dar (z. B. das
Schriftgröße des \<html\>-Elements). Wenn sie auf die Schriftgröße von
diesem Wurzelelement angewendet wird, stellt sie dessen Anfangswert dar.


### Vw {#Vw}
```
public static final int Vw
```


Vw – Viewport‑Breite. 1/100 der Breite des Viewports.


### Vh {#Vh}
```
public static final int Vh
```


Vh – Viewport‑Höhe. 1/100 der Höhe des Viewports.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 des Mindestwerts zwischen Höhe und Breite
des Viewports.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 des Höchstwerts zwischen Höhe und Breite
des Viewports.


### Percent {#Percent}
```
public static final int Percent
```


Der Wert ist relativ zu einem festen (externen) Wert, das ist Kontext
abhängig. 1 % = 1/100 des externen Werts.


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
