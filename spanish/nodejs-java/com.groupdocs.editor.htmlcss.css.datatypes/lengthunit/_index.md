---
title: "LengthUnit"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Todas las unidades de longitud soportadas."
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Todas las unidades de longitud soportadas.


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Campos

| Campo | Descripción |
| --- | --- |
|  | [Unitless](#Unitless) | Sin unidad - sin unidad de longitud definida. |
|
|  | [Px](#Px) | Píxel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (longitud x). |
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
|  | [Vw](#Vw) | Vw - ancho del viewport. |
|
|  | [Vh](#Vh) | Vh - altura del viewport. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | El valor es relativo a un valor fijo (externo), que es el contexto |
dependiente.
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Sin unidad - sin unidad de longitud definida. Valor predeterminado.


### Px {#Px}
```
public static final int Px
```


Pixel. Relativo al dispositivo de visualización. Para la visualización en pantalla, típicamente
un pixel del dispositivo (punto) de la pantalla.


### Em {#Em}
```
public static final int Em
```


Em. Esta unidad representa el tamaño de fuente calculado del elemento.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-length). Esta unidad representa la altura x del elemento
fuente. En fuentes con la letra 'x', esto generalmente es la altura de
las letras minúsculas en la fuente; 1ex \\u2248 0.5em en muchas fuentes.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Un centímetro (10 milímetros).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Un milímetro.


### In {#In}
```
public static final int In
```


In. Una pulgada (2.54 centímetros).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Un punto es 1/72 de una pulgada o 0.353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Una pica (12 puntos).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Esta unidad representa el ancho, o más precisamente el avance
medida, del glifo '0' (cero, el carácter Unicode U+0030) en el
fuente del elemento.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Esta unidad representa el tamaño de fuente del elemento raíz (p. ej., el
tamaño de fuente del elemento \<html\>). Cuando se usa en el tamaño de fuente en
este elemento raíz, representa su valor inicial.


### Vw {#Vw}
```
public static final int Vw
```


Vw - ancho del viewport. 1/100 del ancho del viewport.


### Vh {#Vh}
```
public static final int Vh
```


Vh - altura del viewport. 1/100 de la altura del viewport.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 del valor mínimo entre la altura y el ancho
del viewport.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 del valor máximo entre la altura y el ancho
del viewport.


### Percent {#Percent}
```
public static final int Percent
```


El valor es relativo a un valor fijo (externo), que es el contexto
dependiente. 1% = 1/100 del valor externo.


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
