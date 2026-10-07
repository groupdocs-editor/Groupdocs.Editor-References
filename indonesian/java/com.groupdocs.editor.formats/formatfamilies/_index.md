---
title: "FormatFamilies"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili berbagai keluarga format yang tersedia dalam sistem."
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Mewakili berbagai keluarga format yang tersedia dalam sistem.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [EBook](#EBook) | Mewakili keluarga format eBook. |
|
|  | [Email](#Email) | Mewakili keluarga format Email. |
|
|  | [FixedLayout](#FixedLayout) | Mewakili keluarga format Fixed Layout. |
|
|  | [Presentation](#Presentation) | Mewakili keluarga format Presentation. |
|
|  | [Spreadsheet](#Spreadsheet) | Mewakili keluarga format Spreadsheet. |
|
|  | [Textual](#Textual) | Mewakili keluarga format Textual. |
|
|  | [WordProcessing](#WordProcessing) | Mewakili keluarga format Pengolahan Kata. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Mewakili keluarga format eBook.
Pelajari lebih lanjut tentang format Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
tentang format AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
dan tentang format ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Mewakili keluarga format Email.
Pelajari lebih lanjut tentang format email
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Mewakili keluarga format Fixed Layout.
Berbagai aplikasi penampilan atau penerbitan dokumen memungkinkan pengguna membuka (Adobe Acrobat, XPS Viewer), dan kadang mengedit (Adobe InDesign) dokumen dengan format tertentu.
Aplikasi ini biasanya menghasilkan dokumen format yang disebut \u201cfixed-page\u201d.
Format dokumen semacam itu menjelaskan secara tepat di mana konten dokumen\u2019s ditempatkan pada setiap halaman.
Secara internal, format PDF atau XPS berisi deskripsi setiap halaman, serta instruksi menggambar, yang menentukan tata letak konten pada halaman.
Ini mirip dengan format gambar, yang menjelaskan di mana konten ditampilkan baik dalam bentuk raster maupun vektor.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Mewakili keluarga format Presentation.
Pelajari lebih lanjut tentang format Presentasi
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Mewakili keluarga format Spreadsheet.
Semua format Spreadsheet biner, XML, dan tekstual (mengecualikan semua format berbasis pemisah teks dengan pemisah seperti CSV, TSV, dipisahkan titik koma, dll.), di mana buku kerja dapat disimpan.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Mewakili keluarga format Textual.
Mengkapsulkan semua format tekstual (berbasis teks), termasuk markup (XML, HTML) dan lainnya.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Mewakili keluarga format Pengolahan Kata.
Pelajari lebih lanjut tentang format Pengolahan Kata
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

Kode MIME diambil dari sumber yang diberikan: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



