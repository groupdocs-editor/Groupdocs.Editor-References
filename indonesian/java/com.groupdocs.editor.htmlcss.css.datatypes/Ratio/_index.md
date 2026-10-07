---
title: "Rasio"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili tipe data CSS rasio yang digunakan untuk menggambarkan rasio aspek dalam kueri media dan untuk gambar raster dengan menunjukkan proporsi antara dua nilai tanpa satuan yang disebut pembilang dan penyebut."
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Mewakili tipe data CSS \"rasio\", yang digunakan untuk menggambarkan aspek
rasio dalam kueri media dan untuk gambar raster dengan menunjukkan proporsi
antara dua nilai tanpa satuan yang disebut \"pembilang\" dan \"penyebut\". Tidak dapat diubah
struct.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Single](#Single) | Rasio default tunggal 1/1 |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Mengembalikan pembilang dari rasio ini |
|
|  | [getDenominator()](#getDenominator--) | Mengembalikan penyebut dari rasio ini |
|
|  | [calculate()](#calculate--) | Menghitung dan mengembalikan rasio ini sebagai satu angka floating point tunggal |
|
|  | [getInverseRatio()](#getInverseRatio--) | Membuat dan mengembalikan rasio invers (reciprocal) untuk rasio ini |
|
|  | [serializeDefault()](#serializeDefault--) | Menyerialkan rasio ini ke string dan mengembalikannya |
|
|  | [toString()](#toString--) | Mengembalikan representasi string dari rasio ini; sama dengan |
\"SerializeDefault()\"
|
|  | [isDefault()](#isDefault--) | Menentukan apakah rasio ini memiliki nilai default atau merupakan \"1/1\" (Tunggal) |
|
|  | [deepClone()](#deepClone--) | Mengembalikan salinan penuh dari rasio ini |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Menentukan apakah instance ini sama dengan instance \"Rasio\" yang ditentukan |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, |
yang kemungkinan adalah instance "Ratio" lainnya
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Membandingkan dua rasio dan mengembalikan nilai boolean yang menunjukkan apakah keduanya cocok. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Membandingkan dua rasio dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak |
cocok.
|
|  | [hashCode()](#hashCode--) | Mengembalikan hashcode untuk instance ini, yang tidak dapat diubah selama |
masa hidup
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Membuat dan mengembalikan satu instance Ratio dari pembilang yang ditentukan dan |
penyebut
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Rasio default tunggal 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Mengembalikan pembilang dari rasio ini


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Mengembalikan penyebut dari rasio ini


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Menghitung dan mengembalikan rasio ini sebagai satu angka floating point tunggal


**Returns:**
double - Bilangan floating-point dengan presisi ganda

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Membuat dan mengembalikan rasio invers (reciprocal) untuk rasio ini


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Menyerialkan rasio ini ke string dan mengembalikannya


**Returns:**
java.lang.String - String dalam format "numerator/denominator"

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari rasio ini; sama dengan
\"SerializeDefault()\"


**Returns:**
java.lang.String - String dalam format "numerator/denominator"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Menentukan apakah rasio ini memiliki nilai default atau merupakan \"1/1\" (Tunggal)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Mengembalikan salinan penuh dari rasio ini


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Menentukan apakah instance ini sama dengan instance \"Rasio\" yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Instance Ratio lain untuk memeriksa kesetaraan dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik,
yang kemungkinan adalah instance "Ratio" lainnya


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | lainnya | java.lang.Object | Instance System.Object lain, yang kemungkinan berjenis Ratio, untuk memeriksa kesetaraan dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Membandingkan dua rasio dan mengembalikan nilai boolean yang menunjukkan apakah keduanya cocok.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Rasio pertama yang akan digunakan. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Rasio kedua yang akan digunakan. |
|

**Returns:**
boolean - True jika kedua rasio sama, jika tidak false.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Membandingkan dua rasio dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak
cocok.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Rasio pertama yang akan digunakan. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Rasio kedua yang akan digunakan. |
|

**Returns:**
boolean - True jika kedua rasio tidak sama, jika tidak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hashcode untuk instance ini, yang tidak dapat diubah selama
masa hidup


**Returns:**
int - Integer bertanda 4-byte, yang tidak dapat diubah untuk instance ini

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Membuat dan mengembalikan satu instance Ratio dari pembilang yang ditentukan dan
penyebut


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pembilang | int | Pembilang untuk rasio. Harus berupa bilangan bulat positif yang ketat. |
|
|  | penyebut | int | Penyebut untuk rasio. Harus berupa bilangan bulat positif yang ketat. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

