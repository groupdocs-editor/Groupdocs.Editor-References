---
title: "LengthUnit"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Desteklenen tüm uzunluk birimleri"
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Desteklenen tüm uzunluk birimleri


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - tanımlı bir uzunluk birimi yok. |
|
|  | [Px](#Px) | Piksel. |
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
|  | [Vw](#Vw) | Vw - görünüm genişliği. |
|
|  | [Vh](#Vh) | Vh - görünüm yüksekliği. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Değer, bağlam olan sabit (harici) bir değere göredir |
bağlıdır.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Birim yok - tanımlı bir uzunluk birimi yok. Varsayılan değer.


### Px {#Px}
```
public static final int Px
```


Piksel. Görüntüleme cihazına göre. Ekran görüntüsü için genellikle
ekranın bir cihaz pikseli (nokta).


### Em {#Em}
```
public static final int Em
```


Em. Bu birim, öğenin hesaplanmış yazı tipi boyutunu temsil eder.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-uzunluğu). Bu birim, öğenin x-yüksekliğini temsil eder
yazı tipi. 'x' harfi içeren yazı tiplerinde, bu genellikle yüksekliğidir
yazı tipindeki küçük harfler; birçok yazı tipinde 1ex \\u2248 0.5em.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Bir santimetre (10 milimetre).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Bir milimetre.


### In {#In}
```
public static final int In
```


In. Bir inç (2.54 santimetre).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Bir nokta, bir inçin 1/72'si ya da 0.353 mm'dir.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Bir pica (12 nokta).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Bu birim, genişliği ya da daha kesin olarak ilerlemeyi temsil eder
ölçüsü, '0' (sıfır, Unicode karakteri U+0030) glifinin
öğenin yazı tipinde.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Bu birim, kök öğenin yazı tipi boyutunu temsil eder (ör. 
öğe \<html\> yazı tipi boyutu). Kullanıldığında yazı tipi boyutu üzerinde
bu kök öğe, başlangıç değerini temsil eder.


### Vw {#Vw}
```
public static final int Vw
```


Vw - görünüm alanı genişliği. Görünüm alanının genişliğinin 1/100'i.


### Vh {#Vh}
```
public static final int Vh
```


Vh - görünüm alanı yüksekliği. Görünüm alanının yüksekliğinin 1/100'i.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. Yükseklik ve genişlik arasındaki minimum değerin 1/100'i
görünüm alanının.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. Yükseklik ve genişlik arasındaki maksimum değerin 1/100'i
görünüm alanının.


### Percent {#Percent}
```
public static final int Percent
```


Değer, bağlam olan sabit (harici) bir değere göredir
bağımlı. %1 = dış değerin 1/100'i.


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
