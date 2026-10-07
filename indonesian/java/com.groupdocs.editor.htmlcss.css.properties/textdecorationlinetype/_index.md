---
title: "TextDecorationLineType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili tipe-tipe garis dekorasi teks underline underscore overline dan line-through strikethrough"
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Mewakili jenis garis dekorasi teks: underline (garis bawah), overline, dan line-through (garis tengah).

<br />

*** ** * ** ***

Struct tak dapat diubah. Mirip dengan https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [None](#None) | Tidak menghasilkan dekorasi teks. |
|
|  | [Underline](#Underline) | Setiap baris teks digarisbawahi. |
|
|  | [Overline](#Overline) | Setiap baris teks memiliki garis di atasnya. |
|
|  | [LineThrough](#LineThrough) | Setiap baris teks memiliki garis melalui tengah. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isInitial()](#isInitial--) | Menunjukkan apakah instance ini memiliki nilai awal — None |
|
|  | [isUnderline()](#isUnderline--) | Menunjukkan apakah garis bawah (underscore) diaktifkan |
|
|  | [isOverline()](#isOverline--) | Menunjukkan apakah garis atas diaktifkan |
|
|  | [isLineThrough()](#isLineThrough--) | Menunjukkan apakah garis coret (strikethrough) diaktifkan |
|
|  | [getValue()](#getValue--) | Mengembalikan nilai semua flag dalam instance ini sebagai teks |
|
|  | [toString()](#toString--) | Mengembalikan nilai semua flag dalam instance ini sebagai teks |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Menunjukkan apakah instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) ini sama dengan yang ditentukan |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Menunjukkan apakah instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) ini sama dengan yang ditentukan tanpa casting |
|
|  | [hashCode()](#hashCode--) | Mengembalikan hash-code dari instance ini |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Memeriksa apakah dua nilai \"TextDecorationLineType\" sama |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Memeriksa apakah dua nilai \"TextDecorationLineType\" tidak sama |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Membuat dan mengembalikan instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) dengan flag, yang didefinisikan oleh parameter yang ditentukan |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Mencoba mengurai string yang ditentukan dan mengembalikan instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) yang valid |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Menggabungkan (meng-merge) dua tipe garis yang ditentukan dan menghasilkan tipe garis baru, di mana flag digabungkan (union) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Mengurangi tipe garis kedua yang ditentukan dari tipe garis pertama yang ditentukan dan menghasilkan tipe garis baru, di mana hanya flag dari operand pertama yang tidak ditemukan di operand kedua yang hadir (difference) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Mengembalikan irisan antara tipe garis pertama dan kedua, di mana hanya flag yang diaktifkan secara bersamaan pada kedua operand yang diaktifkan. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Meng-cast byte spesifik (oktet 8-bit) ke [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), melempar pengecualian jika casting tidak valid |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Tidak menghasilkan dekorasi teks. Nilai awal.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Setiap baris teks digarisbawahi.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Setiap baris teks memiliki garis di atasnya.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Setiap baris teks memiliki garis melalui tengah.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Menunjukkan apakah instance ini memiliki nilai awal — None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Menunjukkan apakah garis bawah (underscore) diaktifkan


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Menunjukkan apakah garis atas diaktifkan


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Menunjukkan apakah garis coret (strikethrough) diaktifkan


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Mengembalikan nilai semua flag dalam instance ini sebagai teks


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Mengembalikan nilai semua flag dalam instance ini sebagai teks


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Menunjukkan apakah instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) ini sama dengan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) lain |
|

**Returns:**
boolean -  true  jika sama,  false  jika tidak

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Menunjukkan apakah instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) ini sama dengan yang ditentukan tanpa casting


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | java.lang.Object | Instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) lain, di-cast ke objek |
|

**Returns:**
boolean -  true  jika sama,  false  jika tidak

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hash-code dari instance ini


**Returns:**
int - Kode hash bilangan bulat bertanda

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Memeriksa apakah dua nilai \"TextDecorationLineType\" sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand pertama untuk diperiksa |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand kedua untuk diperiksa |
|

**Returns:**
boolean -  true  jika sama,  false  jika tidak

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Memeriksa apakah dua nilai \"TextDecorationLineType\" tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand pertama untuk diperiksa |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand kedua untuk diperiksa |
|

**Returns:**
boolean -  true  jika tidak sama,  false  sebaliknya

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Membuat dan mengembalikan instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) dengan flag, yang didefinisikan oleh parameter yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | isUnderline | boolean | Menentukan apakah flag underline diaktifkan atau tidak |
|
|  | isOverline | boolean | Menentukan apakah flag overline diaktifkan atau tidak |
|
|  | isLineThrough | boolean | Menentukan apakah flag line-through diaktifkan atau tidak |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Mencoba mengurai string yang ditentukan dan mengembalikan instance [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | input | java.lang.String | String masukan |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Hasil. Jika parsing tidak valid, itu adalah nilai #None.None |
|

**Returns:**
boolean -  true  jika parsing berhasil,  false  jika gagal

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Menggabungkan (meng-merge) dua tipe garis yang ditentukan dan menghasilkan tipe garis baru, di mana flag digabungkan (union)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand tipe baris pertama |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand tipe baris kedua |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Mengurangi tipe garis kedua yang ditentukan dari tipe garis pertama yang ditentukan dan menghasilkan tipe garis baru, di mana hanya flag dari operand pertama yang tidak ditemukan di operand kedua yang hadir (difference)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand tipe baris pertama |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand tipe baris kedua |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Mengembalikan irisan antara tipe baris pertama dan kedua, di mana hanya flag yang diaktifkan secara bersamaan pada kedua operand yang diaktifkan. Memiliki prioritas tertinggi di antara semua operator (lebih tinggi daripada union dan difference)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand tipe baris pertama |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Operand tipe baris kedua |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Meng-cast byte spesifik (oktet 8-bit) ke [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), melempar pengecualian jika casting tidak valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | oktet | byte | Sebuah oktet 8-bit (bitfield), di mana 5 bit terdepan adalah nol, sementara 3 bit terakhir menunjukkan flag |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
