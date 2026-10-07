---
title: "EbookEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengizinkan penentuan dan penyesuaian opsi khusus untuk mengedit dokumen E-book dalam semua format yang didukung seperti ePub, MOBI, dan AZW3."
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Memungkinkan untuk menentukan dan menyesuaikan opsi khusus untuk mengedit dokumen E-book dalam semua format yang didukung: ePub, MOBI, dan AZW3.

<br />

*** ** * ** ***

Format E-book yang didukung:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Publikasi Elektronik)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Menginisialisasi instance baru dari kelas [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), di mana semua opsi diatur ke nilai default. |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Menginisialisasi instance baru dari kelas [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) dengan mode paginasi yang ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Mengizinkan untuk mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Mengizinkan untuk mengaktifkan atau menonaktifkan pagination dalam dokumen HTML hasil. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Menentukan apakah informasi bahasa diekspor ke markup HTML dalam bentuk atribut HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Menentukan apakah informasi bahasa diekspor ke markup HTML dalam bentuk atribut HTML 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Menginisialisasi instance baru dari kelas [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), di mana semua opsi diatur ke nilai default.


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Menginisialisasi instance baru dari kelas [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) dengan mode paginasi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | enablePagination | boolean | Mengaktifkan ( true ) atau menonaktifkan ( false ) paginasi konten e-book dalam dokumen HTML yang dihasilkan. Secara default dinonaktifkan ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Mengizinkan mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML yang dihasilkan. Secara default dinonaktifkan ( Pada dasarnya sebagian besar format e-book secara internal adalah format aliran seperti Office Open XML, di mana konten bersifat solid dan dibagi menjadi bab tetapi bukan halaman. Namun, ia berisi beberapa informasi khusus halaman seperti nomor halaman, catatan kaki, header/footer, dan sebagainya. Beberapa pembaca e-book melakukan pemisahan konten e-book menjadi halaman, sementara yang lain (terutama pada perangkat seluler) \\u2014 tidak.
false
).

<br />

*** ** * ** ***

Opsi ini memungkinkan mengontrol bagaimana konten e-book harus direpresentasikan dalam HTML/CSS saat diedit \\u2014 dalam tampilan mengambang ( false ) atau berhalaman ( true ).

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Mengizinkan mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML yang dihasilkan. Secara default dinonaktifkan ( Pada dasarnya sebagian besar format e-book secara internal adalah format aliran seperti Office Open XML, di mana konten bersifat solid dan dibagi menjadi bab tetapi bukan halaman. Namun, ia berisi beberapa informasi khusus halaman seperti nomor halaman, catatan kaki, header/footer, dan sebagainya. Beberapa pembaca e-book melakukan pemisahan konten e-book menjadi halaman, sementara yang lain (terutama pada perangkat seluler) \\u2014 tidak.
false
).

<br />

*** ** * ** ***

Opsi ini memungkinkan mengontrol bagaimana konten e-book harus direpresentasikan dalam HTML/CSS saat diedit \\u2014 dalam tampilan mengambang ( false ) atau berhalaman ( true ).

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Menentukan apakah informasi bahasa diekspor ke markup HTML dalam bentuk atribut HTML 'lang'.
Opsi ini mungkin berguna untuk konversi bolak-balik dokumen multi-bahasa. Secara default opsi ini dinonaktifkan (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Menentukan apakah informasi bahasa diekspor ke markup HTML dalam bentuk atribut HTML 'lang'.
Opsi ini mungkin berguna untuk konversi bolak-balik dokumen multi-bahasa. Secara default opsi ini dinonaktifkan (
false
).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

