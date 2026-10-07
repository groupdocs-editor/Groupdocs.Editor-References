---
title: "FontWeight"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Properti font-weight mengatur berat atau ketebalan font."
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Properti font-weight mengatur berat (atau ketebalan) font. Berat yang tersedia tergantung pada font-family yang saat ini diatur.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Lighter](#Lighter) | Berat font relatif satu tingkat lebih ringan daripada elemen induk |
|
|  | [Bolder](#Bolder) | Berat font relatif satu tingkat lebih berat daripada elemen induk |
|
|  | [Normal](#Normal) | Berat font normal. |
|
|  | [Bold](#Bold) | Berat font tebal. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isInitial()](#isInitial--) | Menunjukkan apakah font-size ini memiliki nilai awal (Medium) |
|
|  | [getNumber()](#getNumber--) | Mengembalikan sebuah angka - nilai integer antara 1 dan 1000, inklusif, yang menggambarkan ketebalan huruf, atau melemparkan pengecualian, jika ketebalan saat ini tidak absolut, melainkan relatif |
|
|  | [isAbsolute()](#isAbsolute--) | Menunjukkan apakah instance font-weight ini menyimpan nilai absolut dari berat (ketebalan) font, sebagai angka integer |
|
|  | [isRelative()](#isRelative--) | Menunjukkan apakah instance font-weight ini menyimpan nilai relatif dari berat (ketebalan) font - dibandingkan dengan ketebalan elemen induk |
|
|  | [getValue()](#getValue--) | Mengembalikan nilai font-weight ini sebagai string |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Menentukan apakah instance FontWeight yang ditentukan sama |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance FontWeight ini sama dengan yang tidak dikastakan yang ditentukan |
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Memeriksa apakah dua nilai "FontWeight" sama |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Memeriksa apakah dua nilai "FontWeight" tidak sama |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Membuat font-weight dari angka yang ditentukan |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Mencoba mengurai string yang ditentukan dan mengembalikan instance FontWeight yang valid jika berhasil |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Berat font relatif satu tingkat lebih ringan daripada elemen induk


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Berat font relatif satu tingkat lebih berat daripada elemen induk


### Normal {#Normal}
```
public static final FontWeight Normal
```


Berat font Normal. Sama dengan 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Berat font Tebal. Sama dengan 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Menunjukkan apakah font-size ini memiliki nilai awal (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Mengembalikan sebuah angka - nilai integer antara 1 dan 1000, inklusif, yang menggambarkan ketebalan huruf, atau melemparkan pengecualian, jika ketebalan saat ini tidak absolut, melainkan relatif


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Menunjukkan apakah instance font-weight ini menyimpan nilai absolut dari berat (ketebalan) font, sebagai angka integer


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Menunjukkan apakah instance font-weight ini menyimpan nilai relatif dari berat (ketebalan) font - dibandingkan dengan ketebalan elemen induk


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Mengembalikan nilai font-weight ini sebagai string


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Menentukan apakah instance FontWeight yang ditentukan sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Instance FontWeight lain untuk memeriksa kesamaan |
|

**Returns:**
boolean - true jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance FontWeight ini sama dengan yang tidak dikastakan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance FontWeight lain yang tidak dikastakan, mungkin null |
|

**Returns:**
boolean - true jika sama, false jika tidak sama, null atau tipe lain

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.


**Returns:**
int - Hash-code sebagai integer bertanda

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Memeriksa apakah dua nilai "FontWeight" sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Nilai pertama untuk diperiksa |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - true jika sama, false jika tidak

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Memeriksa apakah dua nilai "FontWeight" tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Nilai pertama untuk diperiksa |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - false jika sama, true jika tidak

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Membuat font-weight dari angka yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | number | int | Integer tak bertanda, harus berada dalam rentang [1..1000] |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Mencoba mengurai string yang ditentukan dan mengembalikan instance FontWeight yang valid jika berhasil


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | input | java.lang.String | String input untuk diurai |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Nilai FontWeight yang valid jika berhasil atau #Normal.Normal jika gagal |
|

**Returns:**
boolean - Sukses (true) atau kegagalan (false) dari penguraian

