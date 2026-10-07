---
title: "DelimitedTextSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Berisi opsi untuk menghasilkan dan menyimpan dokumen Spreadsheet berbasis teks seperti CSV, berbasis tab, dll. yang menggunakan pemisah delimiter"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Berisi opsi untuk menghasilkan dan menyimpan dokumen Spreadsheet berbasis teks
(CSV, berbasis Tab, dll.), yang menggunakan pemisah (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Konstruktor tanpa parameter ini membuat instance baru dari DelimitedTextSaveOptions dengan pemisah default titik koma (;) (dapat diubah kemudian melalui |
Pemisah
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) properti)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Membuat instance kelas opsi untuk teks berdelimiter dengan keharusan |
pemisah (delimiter)
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis |
dokumen Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis |
dokumen Spreadsheet
|
|  | [getEncoding()](#getEncoding--) | Mengizinkan penetapan encoding untuk dokumen Spreadsheet berbasis teks. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mengizinkan penetapan encoding untuk dokumen Spreadsheet berbasis teks. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Menunjukkan apakah baris dan kolom kosong di awal harus dipangkas seperti |
yang dilakukan MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Menunjukkan apakah baris dan kolom kosong di awal harus dipangkas seperti |
yang dilakukan MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Menunjukkan apakah pemisah harus dikeluarkan untuk baris kosong. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Menunjukkan apakah pemisah harus dikeluarkan untuk baris kosong. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Konstruktor tanpa parameter ini membuat instance baru dari DelimitedTextSaveOptions dengan pemisah default titik koma (;) (dapat diubah kemudian melalui
Pemisah
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) properti)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Membuat instance kelas opsi untuk teks berdelimiter dengan keharusan
pemisah (delimiter)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pemisah | java.lang.String | String pemisah (delimiter) untuk dokumen Spreadsheet berbasis teks |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis
dokumen Spreadsheet


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis
dokumen Spreadsheet


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Mengizinkan penetapan encoding untuk dokumen Spreadsheet berbasis teks. Dengan
default (dan jika tidak ditentukan) adalah UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Mengizinkan penetapan encoding untuk dokumen Spreadsheet berbasis teks. Dengan
default (dan jika tidak ditentukan) adalah UTF8.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Menunjukkan apakah baris dan kolom kosong di awal harus dipangkas seperti
yang dilakukan MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Menunjukkan apakah baris dan kolom kosong di awal harus dipangkas seperti
yang dilakukan MS Excel


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Menunjukkan apakah pemisah harus dikeluarkan untuk baris kosong. Default
nilainya adalah false yang berarti konten untuk baris kosong akan kosong.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Menunjukkan apakah pemisah harus dikeluarkan untuk baris kosong. Default
nilainya adalah false yang berarti konten untuk baris kosong akan kosong.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

