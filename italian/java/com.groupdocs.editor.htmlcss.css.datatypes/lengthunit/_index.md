---
title: "LengthUnit"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Tutte le unità di lunghezza supportate"
type: docs
weight: 13
url: /it/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Tutte le unità di lunghezza supportate


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Unitless](#Unitless) | Senza unità - nessuna unità di lunghezza definita. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (lunghezza x). |
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
|  | [Vw](#Vw) | Vw - larghezza della viewport. |
|
|  | [Vh](#Vh) | Vh - altezza della viewport. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Il valore è relativo a un valore fisso (esterno), che è il contesto |
dipendente.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Senza unità - nessuna unità di lunghezza definita. Valore predefinito.


### Px {#Px}
```
public static final int Px
```


Pixel. Relativo al dispositivo di visualizzazione. Per la visualizzazione su schermo, tipicamente
un pixel del dispositivo (punto) del display.


### Em {#Em}
```
public static final int Em
```


Em. Questa unità rappresenta la dimensione del carattere calcolata dell'elemento.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-length). Questa unità rappresenta l'altezza x dell'elemento
del carattere. Nei caratteri con la lettera 'x', questa è generalmente l'altezza di
le lettere minuscole nel carattere; 1ex \\u2248 0.5em in molti caratteri.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Un centimetro (10 millimetri).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Un millimetro.


### In {#In}
```
public static final int In
```


In. Un pollice (2,54 centimetri).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Un punto è 1/72 di pollice o 0,353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Una pica (12 punti).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Questa unità rappresenta la larghezza, o più precisamente l'avanzamento
di misura, del glifo '0' (zero, il carattere Unicode U+0030) nel
carattere dell'elemento.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Questa unità rappresenta la dimensione del carattere dell'elemento radice (ad es.
dimensione del carattere dell'elemento \<html\>). Quando usata sulla dimensione del carattere su
questo elemento radice, rappresenta il suo valore iniziale.


### Vw {#Vw}
```
public static final int Vw
```


Vw - larghezza della viewport. 1/100 della larghezza della viewport.


### Vh {#Vh}
```
public static final int Vh
```


Vh - altezza del viewport. 1/100 dell'altezza del viewport.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 del valore minimo tra l'altezza e la larghezza
del viewport.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 del valore massimo tra l'altezza e la larghezza
del viewport.


### Percent {#Percent}
```
public static final int Percent
```


Il valore è relativo a un valore fisso (esterno), che è il contesto
dipendente. 1% = 1/100 del valore esterno.


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
