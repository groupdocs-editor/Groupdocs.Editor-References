---
title: "Panjang"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili nilai panjang CSS dalam unit apa pun yang didukung termasuk persentase dan tipe tanpa satuan."
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Mewakili nilai panjang CSS dalam unit apa pun yang didukung, termasuk persentase
dan tipe tanpa satuan. Nilai dapat berupa integer atau float, negatif, nol, dan
positif. Struktur tidak dapat diubah.

*** ** * ** ***


Tipe ini mencakup tipe data CSS berikut:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Length()](#Length--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Nol integer tanpa satuan - nilai default, sama dengan default tanpa parameter |
konstruktor
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Membuat dan mengembalikan sebuah instance tipe Length dengan angka float yang ditentukan |
dan satuan
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Membuat dan mengembalikan sebuah instance tipe Length dengan angka double yang ditentukan |
dan satuan
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Membuat dan mengembalikan sebuah instance tipe Length dengan integer yang ditentukan |
angka dan satuan
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Menentukan apakah instance ini adalah nol tanpa satuan atau tidak. |
|
|  | [isDefault()](#isDefault--) | Menunjukkan apakah instance Length ini memiliki nilai default \u2014 tanpa satuan |
nol.
|
|  | [getUnitType()](#getUnitType--) | Mengembalikan tipe satuan dari instance Length ini. |
|
|  | [isInteger()](#isInteger--) | Menunjukkan apakah nilai numerik dari instance Length ini adalah |
awalnya ditentukan dan disimpan sebagai angka integer (INT32)
|
|  | [isFloat()](#isFloat--) | Menunjukkan apakah nilai numerik dari instance Length ini adalah |
awalnya ditentukan dan disimpan sebagai angka float (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | Mengembalikan nilai numerik float dari instance Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Mengembalikan nilai numerik integer dari instance Length ini, jika itu |
disimpan secara internal sebagai integer, atau melempar pengecualian, jika itu
awalnya disimpan sebagai angka float.
|
|  | [isAbsolute()](#isAbsolute--) | Mendapatkan apakah panjang diberikan dalam satuan absolut. |
|
|  | [isRelative()](#isRelative--) | Mendapatkan apakah panjang diberikan dalam satuan relatif. |
|
|  | [isZero()](#isZero--) | Menentukan apakah nilai numerik dari panjang ini adalah angka nol |
|
|  | [isNegative()](#isNegative--) | Menentukan apakah nilai numerik dari panjang ini adalah angka negatif |
|
|  | [isPositive()](#isPositive--) | Menentukan apakah nilai numerik dari panjang ini adalah angka positif |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Nilai memiliki tipe tanpa satuan, tetapi bukan nol - positif atau negatif |
number
|
|  | [toPixel()](#toPixel--) | Mengonversi panjang menjadi sejumlah piksel, jika memungkinkan. |
|
|  | [to(int unit)](#to-int-) | Mengonversi panjang ke satuan yang diberikan, jika memungkinkan. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Mengembalikan representasi string dari panjang ini dalam tipe satuan yang ditentukan. |
|
|  | [serializeDefault()](#serializeDefault--) | Mengembalikan representasi string dari panjang ini dalam bentuk asli |
bentuk (sebagaimana disimpan), tanpa mengonversi nilai panjang ke bentuk lain
tipe satuan
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Mendefinisikan apakah nilai ini sama dengan panjang lain yang ditentukan |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah panjang ini sama dengan objek yang ditentukan |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Mengalikan Length yang diberikan dengan faktor yang diberikan |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Memeriksa kesetaraan dua panjang yang diberikan. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Memeriksa ketidaksamaan dua panjang yang diberikan. |
|
|  | [hashCode()](#hashCode--) | Menghitung dan mengembalikan hash-code dari instance Length ini dengan menggabungkan |
hash-code dari nilai dan tipe satuan
|
|  | [deepClone()](#deepClone--) | Mengembalikan salinan penuh dari instance Length ini |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Mencoba mengurai nama satuan yang ditentukan dan mengembalikan nilai yang sesuai dari sebuah |
Enum Unit.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Mencoba mengurai string yang ditentukan sebagai nilai Length, termasuk |
nilai numerik dan nama satuan
|
|  | [parse(String input)](#parse-java.lang.String-) | Mengurai dan mengembalikan string yang ditentukan sebagai nilai Length, termasuk |
nilai numerik dan nama satuan, atau melempar pengecualian jika gagal
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Nol integer tanpa satuan - nilai default, sama dengan default tanpa parameter
konstruktor


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Membuat dan mengembalikan sebuah instance tipe Length dengan angka float yang ditentukan
dan satuan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | float | \>Setiap float (FP32) number |
|
|  | satuan | int | Setiap tipe satuan yang valid |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Membuat dan mengembalikan sebuah instance tipe Length dengan angka double yang ditentukan
dan satuan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Setiap double (FP64) number, yang akan dikonversi ke float (FP32) |
|
|  | satuan | int | Setiap tipe satuan yang valid |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Membuat dan mengembalikan sebuah instance tipe Length dengan integer yang ditentukan
angka dan satuan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Setiap bilangan bulat |
|
|  | satuan | int | Setiap tipe satuan yang valid |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Menentukan apakah instance ini adalah nol tanpa satuan atau tidak. Nol tanpa satuan
adalah nilai default dari tipe ini. Sama dengan properti IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Menunjukkan apakah instance Length ini memiliki nilai default \u2014 tanpa satuan
nol. Sama dengan properti IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Mengembalikan tipe satuan dari instance Length ini.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Menunjukkan apakah nilai numerik dari instance Length ini adalah
awalnya ditentukan dan disimpan sebagai angka integer (INT32)


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Menunjukkan apakah nilai numerik dari instance Length ini adalah
awalnya ditentukan dan disimpan sebagai angka float (FP32)


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Mengembalikan nilai numerik float dari instance Length. Tidak pernah melempar
exception - mengonversi nilai Integer ke Float jika diperlukan.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Mengembalikan nilai numerik integer dari instance Length ini, jika itu
disimpan secara internal sebagai integer, atau melempar pengecualian, jika itu
awalnya disimpan sebagai angka float.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Mendapatkan apakah panjang diberikan dalam satuan absolut. Panjang seperti itu dapat
dikonversi ke piksel.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Mendapatkan apakah panjang diberikan dalam satuan relatif. Panjang seperti itu tidak dapat
dikonversi ke piksel.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Menentukan apakah nilai numerik dari panjang ini adalah angka nol


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Menentukan apakah nilai numerik dari panjang ini adalah angka negatif


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Menentukan apakah nilai numerik dari panjang ini adalah angka positif


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Nilai memiliki tipe tanpa satuan, tetapi bukan nol - positif atau negatif
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Mengonversi panjang ke sejumlah piksel, jika memungkinkan. Jika saat ini
satuan relatif, maka exception akan dilempar.


**Returns:**
float - Jumlah piksel yang direpresentasikan oleh panjang saat ini.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Mengonversi panjang ke satuan yang diberikan, jika memungkinkan. Jika saat ini atau
satuan yang diberikan relatif, maka exception akan dilempar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | satuan | int | Satuan untuk dikonversi ke. |
|

**Returns:**
float - Nilai dalam satuan yang diberikan dari panjang saat ini.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Mengembalikan representasi string dari panjang ini dalam tipe satuan yang ditentukan.
Nilai numerik akan dikonversi sesuai dengan perubahan tipe satuan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | satuan | int | Satuan yang ditentukan, ke mana instance ini harus dikonversi sebelum diserialisasi ke string. Harus valid. Tidak boleh tanpa satuan. |
|

**Returns:**
java.lang.String - Representasi String

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Mengembalikan representasi string dari panjang ini dalam bentuk asli
bentuk (sebagaimana disimpan), tanpa mengonversi nilai panjang ke bentuk lain
tipe satuan


**Returns:**
java.lang.String - Instance String

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Mendefinisikan apakah nilai ini sama dengan panjang lain yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Instansi Length lain |
|

**Returns:**
boolean - True jika sama, jika tidak false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah panjang ini sama dengan objek yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instansi lain dari tipe Length, yang dibungkus ke System.Object atau tipe abstrak atau antarmuka lain apa pun |
|

**Returns:**
boolean - True jika sama, jika tidak false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Mengalikan Length yang diberikan dengan faktor yang diberikan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - faktor perkalian |
|
|  | faktor | int | Integer sewenang-wenang - faktor |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Memeriksa kesetaraan dua panjang yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Operand length kiri. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Operand length kanan. |
|

**Returns:**
boolean - True jika kedua length sama, jika tidak false.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Memeriksa ketidaksamaan dua panjang yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Operand length kiri. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Operand length kanan. |
|

**Returns:**
boolean - True jika kedua length tidak sama, jika tidak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menghitung dan mengembalikan hash-code dari instance Length ini dengan menggabungkan
hash-code dari nilai dan tipe satuan


**Returns:**
int - Angka integer

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Mengembalikan salinan penuh dari instance Length ini


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Mencoba mengurai nama satuan yang ditentukan dan mengembalikan nilai yang sesuai dari sebuah
Enum Unit. Mengembalikan LengthUnit.Unitless jika tidak dapat menemukan LengthUnit yang sesuai.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | unitName | java.lang.String | String, yang mewakili nama unit |
|

**Returns:**
int - Nilai enum Unit dalam kasus apa pun, LengthUnit.Unitless ketika tidak dapat menemukan unit yang sesuai

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Mencoba mengurai string yang ditentukan sebagai nilai Length, termasuk
nilai numerik dan nama satuan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | input | java.lang.String | String input, yang harus diparsing |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Parameter output, yang berisi hasil parsing. Jika parsing tidak berhasil, berisi nilai Length default \\u2014 nol tanpa unit. |
|

**Returns:**
boolean - True jika parsing berhasil, false jika tidak berhasil

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Mengurai dan mengembalikan string yang ditentukan sebagai nilai Length, termasuk
nilai numerik dan nama satuan, atau melempar pengecualian jika gagal


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | input | java.lang.String | String input, yang harus diparsing |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

