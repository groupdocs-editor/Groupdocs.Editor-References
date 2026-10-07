---
title: "EbookSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen dalam semua format e-Book yang didukung ePub, MOBI, dan AZW3."
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen dalam semua format e-Book yang didukung: ePub, MOBI, dan AZW3.

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
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Konstruktor tanpa parameter ini membuat instance baru dari EbookSaveOptions dengan format output ePub (dapat dimodifikasi kemudian melalui |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) properti)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Membuat instance baru dari [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) dengan format output e-Book wajib yang ditentukan, sementara semua parameter lain menggunakan nilai default |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Menentukan tingkat maksimum heading di mana file e-Book akan dipisah. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Menentukan tingkat maksimum heading di mana file e-Book akan dipisah. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus dalam file hasil. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus dalam file hasil. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Menentukan format file e-Book hasil: IDPF ePub, MOBI, atau AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Menentukan format file e-Book hasil: IDPF ePub, MOBI, atau AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Konstruktor tanpa parameter ini membuat instance baru dari EbookSaveOptions dengan format output ePub (dapat dimodifikasi kemudian melalui
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) properti)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Membuat instance baru dari [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) dengan format output e-Book wajib yang ditentukan, sementara semua parameter lain menggunakan nilai default


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | format output wajib, di mana e-Book harus disimpan |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Menentukan tingkat maksimum heading yang akan dipisah pada file e-Book. Nilai default adalah
2
.
Mengaturnya ke
0
akan menonaktifkan pemisahan, sehingga semua konten e-Book akan dimasukkan ke dalam satu paket di dalam file hasil.

<br />

*** ** * ** ***

Ketika properti ini diatur ke nilai antara 1 hingga 9, dokumen akan dipisah pada paragraf yang diformat menggunakan

**Heading 1**
,
**Heading 2**
,
**Heading 3**
dst. gaya hingga tingkat heading yang ditentukan.

Secara default, hanya
**Heading 1**
dan
**Heading 2**
paragraf menyebabkan dokumen dipisah.
Mengatur properti ini ke nol (atau kurang dari nol) akan menyebabkan dokumen tidak dipisah pada paragraf heading sama sekali.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Menentukan tingkat maksimum heading yang akan dipisah pada file e-Book. Nilai default adalah
2
.
Mengaturnya ke
0
akan menonaktifkan pemisahan, sehingga semua konten e-Book akan dimasukkan ke dalam satu paket di dalam file hasil.

<br />

*** ** * ** ***

Ketika properti ini diatur ke nilai antara 1 hingga 9, dokumen akan dipisah pada paragraf yang diformat menggunakan

**Heading 1**
,
**Heading 2**
,
**Heading 3**
dst. gaya hingga tingkat heading yang ditentukan.

Secara default, hanya
**Heading 1**
dan
**Heading 2**
paragraf menyebabkan dokumen dipisah.
Mengatur properti ini ke nol (atau kurang dari nol) akan menyebabkan dokumen tidak dipisah pada paragraf heading sama sekali.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus dalam file hasil.
Nilai default adalah
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus dalam file hasil.
Nilai default adalah
false
.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Menentukan format file e-Book hasil: IDPF ePub, MOBI, atau AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Menentukan format file e-Book hasil: IDPF ePub, MOBI, atau AZW3.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

