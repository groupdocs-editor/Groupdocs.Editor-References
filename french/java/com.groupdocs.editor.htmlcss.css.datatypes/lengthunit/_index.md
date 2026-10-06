---
title: "LengthUnit"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Toutes les unités de longueur prises en charge"
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Toutes les unités de longueur prises en charge


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Champs

| Champ | Description |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - aucune unité de longueur définie. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (longueur x). |
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
|  | [Vw](#Vw) | Vw - largeur du viewport. |
|
|  | [Vh](#Vh) | Vh - hauteur du viewport. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | La valeur est relative à une valeur fixe (externe), qui est le contexte |
dépendante.
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Sans unité - aucune unité de longueur définie. Valeur par défaut.


### Px {#Px}
```
public static final int Px
```


Pixel. Relatif au dispositif d'affichage. Pour l'affichage à l'écran, généralement
un pixel (point) du dispositif d'affichage.


### Em {#Em}
```
public static final int Em
```


Em. Cette unité représente la taille de police calculée de l'élément.


### Ex {#Ex}
```
public static final int Ex
```


Ex (longueur x). Cette unité représente la hauteur x de l'élément
de police. Sur les polices contenant la lettre 'x', c'est généralement la hauteur de
les lettres minuscules de la police ; 1ex \\u2248 0.5em dans de nombreuses polices.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Un centimètre (10 millimètres).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Un millimètre.


### In {#In}
```
public static final int In
```


In. Un pouce (2,54 centimètres).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Un point vaut 1/72 de pouce ou 0,353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Un pica (12 points).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Cette unité représente la largeur, ou plus précisément l'avance
mesure, du glyphe '0' (zéro, le caractère Unicode U+0030) dans le
police de l'élément.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Cette unité représente la taille de police de l'élément racine (par ex.
taille de police de l'élément \<html\>). Lorsqu'elle est utilisée sur la taille de police du
cet élément racine, elle représente sa valeur initiale.


### Vw {#Vw}
```
public static final int Vw
```


Vw - largeur du viewport. 1/100e de la largeur du viewport.


### Vh {#Vh}
```
public static final int Vh
```


Vh - hauteur du viewport. 1/100e de la hauteur du viewport.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100e de la valeur minimale entre la hauteur et la largeur
de la fenêtre d'affichage.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100e de la valeur maximale entre la hauteur et la largeur
de la fenêtre d'affichage.


### Percent {#Percent}
```
public static final int Percent
```


La valeur est relative à une valeur fixe (externe), qui est le contexte
dépendant. 1 % = 1/100 de la valeur externe.


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
