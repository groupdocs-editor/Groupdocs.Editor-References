---
title: "FontStyle"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mendefinisikan bagaimana font harus diberi gaya dengan bentuk normal, italic, atau oblique dari keluarga fontnya."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Mendefinisikan bagaimana font harus diberi gaya: normal, italic, atau oblique dari font-family-nya.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Normal](#Normal) | Memilih font yang diklasifikasikan sebagai normal dalam sebuah keluarga font. |
|
|  | [Italic](#Italic) | Memilih font yang diklasifikasikan sebagai italic. |
|
|  | [Oblique](#Oblique) | Memilih font yang diklasifikasikan sebagai oblique. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isInitial()](#isInitial--) | Menunjukkan apakah font-style ini memiliki nilai awal (Normal). |
|
|  | [getValue()](#getValue--) | Mengembalikan nilai dari gaya font ini sebagai string. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Menentukan apakah instance font-style ini sama dengan yang ditentukan. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance font-style ini sama dengan yang ditentukan tanpa casting. |
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Memeriksa apakah dua nilai "FontStyle" sama. |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Memeriksa apakah dua nilai "FontStyle" tidak sama. |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Mencoba mengenali kata kunci yang ditentukan sebagai nilai kata kunci yang tepat untuk 'font-style' dan mengembalikannya jika berhasil atau NULL jika gagal. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Memilih font yang diklasifikasikan sebagai normal dalam sebuah keluarga font. Nilai awal.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Memilih font yang diklasifikasikan sebagai italic. Jika tidak ada versi italic dari font tersebut, yang diklasifikasikan sebagai oblique akan digunakan sebagai gantinya. Jika keduanya tidak tersedia, gaya tersebut disimulasikan secara artifisial.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Memilih font yang diklasifikasikan sebagai oblique. Jika tidak ada versi oblique dari font tersebut, yang diklasifikasikan sebagai italic akan digunakan sebagai gantinya. Jika keduanya tidak tersedia, gaya tersebut disimulasikan secara artifisial.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Menunjukkan apakah font-style ini memiliki nilai awal (Normal).


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Mengembalikan nilai dari gaya font ini sebagai string.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Menentukan apakah instance font-style ini sama dengan yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Instansi font-style lainnya |
|

**Returns:**
boolean - true jika sama, false jika tidak

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance font-style ini sama dengan yang ditentukan tanpa casting.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instansi font-style tidak ter-cast lainnya, mungkin null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Memeriksa apakah dua nilai "FontStyle" sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Nilai pertama untuk diperiksa |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - true jika sama, false jika tidak

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Memeriksa apakah dua nilai "FontStyle" tidak sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Nilai pertama untuk diperiksa |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - false jika sama, true jika tidak

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Mencoba mengenali kata kunci yang ditentukan sebagai nilai kata kunci yang tepat untuk 'font-style' dan mengembalikannya jika berhasil atau NULL jika gagal.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | keyword | java.lang.String | Sebuah keyword untuk diparsing |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Hasil, parsing berhasil, atau #Normal.Normal jika tidak |
|

**Returns:**
boolean - true jika parsing berhasil, false jika tidak

