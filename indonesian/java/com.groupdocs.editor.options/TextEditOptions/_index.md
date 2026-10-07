---
title: "TextEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengizinkan untuk menentukan opsi khusus untuk memuat dokumen TXT teks biasa"
type: docs
weight: 39
url: /id/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Memungkinkan menentukan opsi khusus untuk memuat dokumen teks biasa (TXT).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Pengkodean karakter dokumen teks, yang akan diterapkan untuk |
pembukaan
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Pengkodean karakter dokumen teks, yang akan diterapkan untuk |
pembukaan
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Mengizinkan untuk menentukan bagaimana item daftar bernomor dikenali ketika dokumen |
diimpor dari format teks biasa.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Mengizinkan untuk menentukan bagaimana item daftar bernomor dikenali ketika dokumen |
diimpor dari format teks biasa.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Mengizinkan untuk mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Mengizinkan untuk mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. |
|
|  | [getDirection()](#getDirection--) | Mengizinkan untuk menentukan arah aliran teks dalam teks biasa input |
dokumen.
|
|  | [setDirection(int value)](#setDirection-int-) | Mengizinkan untuk menentukan arah aliran teks dalam teks biasa input |
dokumen.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Pengkodean karakter dokumen teks, yang akan diterapkan untuk
pembukaan


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Pengkodean karakter dokumen teks, yang akan diterapkan untuk
pembukaan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Mengizinkan untuk menentukan bagaimana item daftar bernomor dikenali ketika dokumen
diimpor dari format teks biasa. Nilai default adalah true.


*** ** * ** ***

Jika opsi ini diatur ke false, algoritma pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar diakhiri dengan titik, kurung kanan, atau simbol bullet (seperti "\\u2022", "\*", "-" atau "o"). Jika opsi ini diatur ke true, spasi juga digunakan sebagai pemisah nomor daftar: algoritma pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan baik spasi maupun simbol titik (".").

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Mengizinkan untuk menentukan bagaimana item daftar bernomor dikenali ketika dokumen
diimpor dari format teks biasa. Nilai default adalah true.


*** ** * ** ***

Jika opsi ini diatur ke false, algoritma pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar diakhiri dengan titik, kurung kanan, atau simbol bullet (seperti "\\u2022", "\*", "-" atau "o"). Jika opsi ini diatur ke true, spasi juga digunakan sebagai pemisah nomor daftar: algoritma pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan baik spasi maupun simbol titik (".").

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. Secara default
mengonversi spasi di awal menjadi indentasi kiri.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. Secara default
mengonversi spasi di awal menjadi indentasi kiri.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. Secara default
memotong semua spasi di akhir.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. Secara default
memotong semua spasi di akhir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Mengizinkan untuk menentukan arah aliran teks dalam teks biasa input
dokumen. Secara default adalah Kiri-ke-Kanan.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Mengizinkan untuk menentukan arah aliran teks dalam teks biasa input
dokumen. Secara default adalah Kiri-ke-Kanan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

