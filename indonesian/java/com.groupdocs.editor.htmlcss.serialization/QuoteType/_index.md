---
title: "QuoteType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili karakter kutipan - kutipan tunggal dan kutipan ganda"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Mewakili karakter kutip - kutip tunggal (') dan kutip ganda (\")

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Kutipan tunggal (karakter U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | Kutipan ganda (karakter U+0022 QUOTATION MARK) |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCode()](#getCode--) | Titik kode dari karakter saat ini (U+0027 atau U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Karakter untuk dikutip |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | Karakter yang di-encode HTML |
|
|  | [toString()](#toString--) | Mengembalikan string "SingleQuote" atau "DoubleQuote" tergantung pada nilai saat ini |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Menunjukkan apakah instance tipe kutipan ini sama dengan yang ditentukan |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menunjukkan apakah instance tipe kutipan ini sama dengan yang ditentukan tanpa casting |
|
|  | [hashCode()](#hashCode--) | Mengembalikan kode hash untuk karakter ini |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Memeriksa apakah dua nilai "QuoteType" sama |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Memeriksa apakah dua nilai "QuoteType" tidak sama |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Mengonversi instance [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) yang ditentukan menjadi char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Mengonversi char tertentu menjadi [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) yang sesuai, melempar pengecualian jika konversi tidak valid |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Kutipan tunggal (karakter U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Kutipan ganda (karakter U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


Titik kode dari karakter saat ini (U+0027 atau U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Karakter untuk dikutip


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


Karakter yang di-encode HTML


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string "SingleQuote" atau "DoubleQuote" tergantung pada nilai saat ini


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Menunjukkan apakah instance tipe kutipan ini sama dengan yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Instance lain dari QuoteType untuk diperiksa |
|

**Returns:**
boolean - true jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menunjukkan apakah instance tipe kutipan ini sama dengan yang ditentukan tanpa casting


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Objek yang tidak dikonversi, diharapkan berjenis [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - true jika sama, false jika tidak sama

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk karakter ini


**Returns:**
int - Hash-code sebagai integer bertanda

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Memeriksa apakah dua nilai "QuoteType" sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Nilai pertama untuk diperiksa |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - true jika sama, false jika tidak

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Memeriksa apakah dua nilai "QuoteType" tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Nilai pertama untuk diperiksa |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Nilai kedua untuk diperiksa |
|

**Returns:**
boolean - false jika sama, true jika tidak

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Mengonversi instance [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) yang ditentukan menjadi char


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Instance tipe kutipan untuk dikonversi |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Mengonversi char tertentu menjadi [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) yang sesuai, melempar pengecualian jika konversi tidak valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | karakter | char | Karakter kutip tunggal (U+0027 APOSTROPHE) atau kutip ganda (U+0022 QUOTATION MARK). Pengecualian akan dilempar jika karakter lain ditentukan. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
