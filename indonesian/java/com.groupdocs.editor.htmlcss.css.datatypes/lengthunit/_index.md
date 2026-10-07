---
title: "LengthUnit"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Semua unit panjang yang didukung"
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Semua unit panjang yang didukung


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - tidak ada satuan panjang yang didefinisikan. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-length). |
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
|  | [Vw](#Vw) | Vw - lebar viewport. |
|
|  | [Vh](#Vh) | Vh - tinggi viewport. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Nilai ini relatif terhadap nilai tetap (eksternal), yang merupakan konteks |
tergantung.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Tanpa satuan - tidak ada satuan panjang yang didefinisikan. Nilai default.


### Px {#Px}
```
public static final int Px
```


Pixel. Relatif terhadap perangkat tampilan. Untuk tampilan layar, biasanya
satu piksel perangkat (titik) pada layar.


### Em {#Em}
```
public static final int Em
```


Em. Unit ini mewakili ukuran font yang dihitung dari elemen.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-length). Unit ini mewakili tinggi-x dari font elemen
font. Pada font dengan huruf 'x', ini biasanya tinggi dari
huruf kecil dalam font; 1ex \\u2248 0.5em pada banyak font.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Satu sentimeter (10 milimeter).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Satu milimeter.


### In {#In}
```
public static final int In
```


In. Satu inci (2,54 sentimeter).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Satu poin adalah 1/72 inci atau 0,353 mm.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Satu pica (12 poin).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Unit ini mewakili lebar, atau lebih tepatnya ukuran maju
dari glif '0' (nol, karakter Unicode U+0030) dalam
font elemen.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Unit ini mewakili ukuran font dari elemen akar (misalnya
ukuran font dari elemen \<html\>). Ketika digunakan pada ukuran font pada
elemen akar ini, ia mewakili nilai awalnya.


### Vw {#Vw}
```
public static final int Vw
```


Vw - lebar viewport. 1/100 lebar viewport.


### Vh {#Vh}
```
public static final int Vh
```


Vh - tinggi viewport. 1/100 dari tinggi viewport.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 dari nilai minimum antara tinggi dan lebar
dari viewport.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 dari nilai maksimum antara tinggi dan lebar
dari viewport.


### Percent {#Percent}
```
public static final int Percent
```


Nilai ini relatif terhadap nilai tetap (eksternal), yang merupakan konteks
tergantung. 1% = 1/100 dari nilai eksternal.


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
