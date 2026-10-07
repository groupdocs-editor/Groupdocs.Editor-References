---
title: "WordProcessingEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengizinkan untuk menentukan opsi khusus untuk mengedit dokumen dari semua format yang didukung WordProcessing yang sesuai dengan standar Words seperti DOCX, RTF, ODT, dll."
type: docs
weight: 44
url: /id/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Memungkinkan menentukan opsi khusus untuk mengedit semua dokumen yang didukung
Format WordProcessing (sesuai Words) seperti DOC(X), RTF, ODT, dll.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Membuat dan mengembalikan instance baru dari WordProcessingEditOptions |
kelas, di mana semua opsi diatur ke nilai defaultnya
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Membuat dan mengembalikan instance baru dari WordProcessingEditOptions |
kelas dengan pagination yang ditentukan dan semua opsi lainnya default
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Mengizinkan untuk mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Mengizinkan untuk mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Menentukan apakah informasi bahasa diekspor ke markup HTML dalam |
bentuk atribut HTML 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Menentukan apakah informasi bahasa diekspor ke markup HTML dalam |
bentuk atribut HTML 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang |
digunakan dalam konten teks dokumen.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang |
digunakan dalam konten teks dokumen.
|
|  | [getFontExtraction()](#getFontExtraction--) | Bertanggung jawab untuk mengekstrak sumber daya font, yang digunakan dalam input |
dokumen WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Bertanggung jawab untuk mengekstrak sumber daya font, yang digunakan dalam input |
dokumen WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Memungkinkan menentukan nama kelas, yang akan ditempatkan ke atribut 'class' |
atribut di setiap elemen HTML, yang mewakili beberapa bidang dalam input
dokumen WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Memungkinkan menentukan nama kelas, yang akan ditempatkan ke atribut 'class' |
atribut di setiap elemen HTML, yang mewakili beberapa bidang dalam input
dokumen WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Mengontrol dimana menyimpan data styling dan formatting dari dokumen WordProcessing input: dalam stylesheet eksternal ( |
false
) atau sebagai style inline dalam markup HTML (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Mengontrol dimana menyimpan data styling dan formatting dari dokumen WordProcessing input: dalam stylesheet eksternal ( |
false
) atau sebagai style inline dalam markup HTML (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Membuat dan mengembalikan instance baru dari WordProcessingEditOptions
kelas, di mana semua opsi diatur ke nilai defaultnya


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Membuat dan mengembalikan instance baru dari WordProcessingEditOptions
kelas dengan pagination yang ditentukan dan semua opsi lainnya default


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | enablePagination | boolean | Bendera pagination, yang mengaktifkan output HTML, disesuaikan untuk mode berhalaman |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Mengizinkan untuk mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML yang dihasilkan. By
defaultnya dinonaktifkan (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Mengizinkan untuk mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML yang dihasilkan. By
defaultnya dinonaktifkan (false).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Menentukan apakah informasi bahasa diekspor ke markup HTML dalam
bentuk atribut HTML 'lang'. Opsi ini mungkin berguna untuk roundtrip
konversi dokumen multi-bahasa. Secara default opsi ini dinonaktifkan
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Menentukan apakah informasi bahasa diekspor ke markup HTML dalam
bentuk atribut HTML 'lang'. Opsi ini mungkin berguna untuk roundtrip
konversi dokumen multi-bahasa. Secara default opsi ini dinonaktifkan
(false).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang
digunakan dalam konten teks dokumen.
Nilai:  true  jika diperlukan untuk mengekstrak hanya sumber daya font yang digunakan dalam konten teks dokumen; jika tidak,  false . Nilai default adalah  false .


*** ** * ** ***

Tidak semua font yang digunakan dalam dokumen WordProcessing digunakan secara langsung 100% (diterapkan pada teks). Mungkin ada situasi di mana font direferensikan dalam dokumen dan bahkan dapat disematkan, tetapi tidak diterapkan pada teks apa pun. Misalnya, beberapa font dapat terikat pada gaya tertentu, tetapi gaya tersebut tidak diterapkan pada bagian teks mana pun. Opsi ini mengontrol cara memproses kasus seperti itu.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang
digunakan dalam konten teks dokumen.
Nilai:  true  jika diperlukan untuk mengekstrak hanya sumber daya font yang digunakan dalam konten teks dokumen; jika tidak,  false . Nilai default adalah  false .


*** ** * ** ***

Tidak semua font yang digunakan dalam dokumen WordProcessing digunakan secara langsung 100% (diterapkan pada teks). Mungkin ada situasi di mana font direferensikan dalam dokumen dan bahkan dapat disematkan, tetapi tidak diterapkan pada teks apa pun. Misalnya, beberapa font dapat terikat pada gaya tertentu, tetapi gaya tersebut tidak diterapkan pada bagian teks mana pun. Opsi ini mengontrol cara memproses kasus seperti itu.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Bertanggung jawab untuk mengekstrak sumber daya font, yang digunakan dalam input
dokumen WordProcessing. Secara default tidak mengekstrak font apa pun
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Bertanggung jawab untuk mengekstrak sumber daya font, yang digunakan dalam input
dokumen WordProcessing. Secara default tidak mengekstrak font apa pun
(NotExtract).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Memungkinkan menentukan nama kelas, yang akan ditempatkan ke atribut 'class'
atribut di setiap elemen HTML, yang mewakili beberapa bidang dalam input
Dokumen WordProcessing. Secara default adalah NULL - atribut 'class' tidak
diterapkan.


*** ** * ** ***

Hampir semua format dari keluarga format WordProcessing berisi bidang \\u2014 entitas dokumen spesifik, yang memungkinkan memperoleh data masukan dari pengguna. Ada berbagai macam bidang: kotak teks, kotak centang, kotak kombo, daftar drop down, tombol, pemilih tanggal/waktu, dll. Semua itu diterjemahkan ke dalam struktur dan elemen HTML yang paling tepat, dengan mempertahankan data pengguna yang dimasukkan, jika ada dalam dokumen masukan. Dalam kasus penggunaan tertentu hanya diperlukan mengumpulkan data yang dimasukkan di sisi klien alih-alih mengedit seluruh konten dokumen. Untuk kasus tersebut diperlukan mengidentifikasi kontrol input dengan cara tertentu untuk mengambilnya beserta datanya di sisi klien. Properti ini memungkinkan menentukan nama kelas, yang akan diterapkan untuk setiap kontrol input dalam markup HTML, sehingga kode klien dapat menelusuri struktur dokumen HTML dan mengumpulkan data.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Memungkinkan menentukan nama kelas, yang akan ditempatkan ke atribut 'class'
atribut di setiap elemen HTML, yang mewakili beberapa bidang dalam input
Dokumen WordProcessing. Secara default adalah NULL - atribut 'class' tidak
diterapkan.


*** ** * ** ***

Hampir semua format dari keluarga format WordProcessing berisi bidang \\u2014 entitas dokumen spesifik, yang memungkinkan memperoleh data masukan dari pengguna. Ada berbagai macam bidang: kotak teks, kotak centang, kotak kombo, daftar drop down, tombol, pemilih tanggal/waktu, dll. Semua itu diterjemahkan ke dalam struktur dan elemen HTML yang paling tepat, dengan mempertahankan data pengguna yang dimasukkan, jika ada dalam dokumen masukan. Dalam kasus penggunaan tertentu hanya diperlukan mengumpulkan data yang dimasukkan di sisi klien alih-alih mengedit seluruh konten dokumen. Untuk kasus tersebut diperlukan mengidentifikasi kontrol input dengan cara tertentu untuk mengambilnya beserta datanya di sisi klien. Properti ini memungkinkan menentukan nama kelas, yang akan diterapkan untuk setiap kontrol input dalam markup HTML, sehingga kode klien dapat menelusuri struktur dokumen HTML dan mengumpulkan data.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Mengontrol dimana menyimpan data styling dan formatting dari dokumen WordProcessing input: dalam stylesheet eksternal (
false
) atau sebagai style inline dalam markup HTML (
true
). Secara default gaya eksternal digunakan (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Mengontrol dimana menyimpan data styling dan formatting dari dokumen WordProcessing input: dalam stylesheet eksternal (
false
) atau sebagai style inline dalam markup HTML (
true
). Secara default gaya eksternal digunakan (
false
).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

