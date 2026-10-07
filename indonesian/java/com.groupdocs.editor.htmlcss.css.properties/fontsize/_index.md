---
title: "FontSize"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili ukuran font sebagai satuan khusus atau nilai panjang yang menentukan ukuran font, secara historis lebar huruf kapital M."
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Mewakili ukuran font sebagai satuan khusus atau nilai panjang, yang menentukan ukuran font (secara historis lebar huruf kapital "M").

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Medium](#Medium) | Ukuran sedang. |
|
|  | [XxSmall](#XxSmall) | Ukuran absolute-size sangat kecil |
|
|  | [XSmall](#XSmall) | Ukuran absolute-size kecil sedang |
|
|  | [Small](#Small) | Ukuran absolute-size kecil normal |
|
|  | [Large](#Large) | Ukuran absolute-size besar normal |
|
|  | [XLarge](#XLarge) | Ukuran absolute-size besar sedang |
|
|  | [XxLarge](#XxLarge) | Ukuran absolute-size sangat besar |
|
|  | [Larger](#Larger) | Ukuran relative-size lebih besar - font akan lebih besar relatif terhadap font-size elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci absolute-size di atas. |
|
|  | [Smaller](#Smaller) | Ukuran relative-size lebih kecil - font akan lebih kecil relatif terhadap font-size elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci absolute-size di atas. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isInitial()](#isInitial--) | Menunjukkan apakah font-size ini memiliki nilai awal (Medium) |
|
|  | [getValue()](#getValue--) | Mengembalikan nilai ukuran font ini sebagai string |
|
|  | [isLengthDefined()](#isLengthDefined--) | Menunjukkan apakah font-size ini didefinisikan dengan nilai [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | Nilai panjang, jika font-size ini didefinisikan dengan itu, atau melempar pengecualian sebaliknya |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Menunjukkan apakah font-size ini didefinisikan dengan ukuran absolut sebagai kata kunci, berdasarkan ukuran font default pengguna (yang adalah medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Menunjukkan apakah font-size ini didefinisikan dengan ukuran relatif sebagai kata kunci. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Menentukan apakah instance font-size ini sama dengan yang ditentukan |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance font-size ini sama dengan yang tidak dikast |
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Memeriksa apakah dua nilai "FontSize" sama |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Memeriksa apakah dua nilai "FontSize" tidak sama |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Membuat font-size dari panjang yang ditentukan |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Mencoba mengenali kata kunci yang ditentukan sebagai nilai kata kunci yang tepat dari 'font-size' dan mengembalikannya jika berhasil atau NULL jika gagal. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Ukuran medium. Nilai awal.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Ukuran absolute-size sangat kecil


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Ukuran absolute-size kecil sedang


### Small {#Small}
```
public static final FontSize Small
```


Ukuran absolute-size kecil normal


### Large {#Large}
```
public static final FontSize Large
```


Ukuran absolute-size besar normal


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Ukuran absolute-size besar sedang


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Ukuran absolute-size sangat besar


### Larger {#Larger}
```
public static final FontSize Larger
```


Ukuran relative-size lebih besar - font akan lebih besar relatif terhadap font-size elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci absolute-size di atas.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Ukuran relative-size lebih kecil - font akan lebih kecil relatif terhadap font-size elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci absolute-size di atas.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Menunjukkan apakah font-size ini memiliki nilai awal (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Mengembalikan nilai ukuran font ini sebagai string


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Menunjukkan apakah font-size ini didefinisikan dengan nilai [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Nilai panjang, jika font-size ini didefinisikan dengan itu, atau melempar pengecualian sebaliknya


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Menunjukkan apakah font-size ini didefinisikan dengan ukuran absolut sebagai kata kunci, berdasarkan ukuran font default pengguna (yang adalah medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Menunjukkan apakah font-size ini didefinisikan dengan ukuran relatif sebagai kata kunci. Font akan lebih besar atau lebih kecil relatif terhadap ukuran font elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci ukuran absolut.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Menentukan apakah instance font-size ini sama dengan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Instance font-size lain |
|

**Returns:**
boolean - true jika sama, false jika tidak

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance font-size ini sama dengan yang tidak dikast


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instance font-size lain yang tidak dikast, mungkin null |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Memeriksa apakah dua nilai "FontSize" sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Nilai pertama untuk diperiksa |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - true jika sama, false jika tidak

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Memeriksa apakah dua nilai "FontSize" tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Nilai pertama untuk diperiksa |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - false jika sama, true jika tidak

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Membuat font-size dari panjang yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Nilai panjang, tidak boleh tanpa satuan atau negatif |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Mencoba mengenali kata kunci yang ditentukan sebagai nilai kata kunci yang tepat dari 'font-size' dan mengembalikannya jika berhasil atau NULL jika gagal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | keyword | java.lang.String | Sebuah keyword untuk diparsing |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Hasil, parsing berhasil, atau #Medium.Medium jika tidak |
|

**Returns:**
boolean - true jika parsing berhasil, false jika tidak

