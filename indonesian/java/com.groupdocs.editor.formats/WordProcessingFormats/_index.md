---
title: "WordProcessingFormats"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan semua format Pengolah Kata."
type: docs
weight: 17
url: /id/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Menyatukan semua format WordProcessing. Menyertakan jenis berkas berikut:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Pelajari lebih lanjut tentang format Word Processing [di sini](../https://wiki.fileformat.com/word-processing).

Kode MIME diambil dari sumber yang diberikan:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Doc](#Doc) | Format File Biner MS Word 97-2007 (DOC) mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. |
|
|  | [Docx](#Docx) | Dokumen Office Open XML WordProcessingML Tanpa Makro (DOCX) adalah format yang terkenal untuk dokumen Microsoft Word. |
|
|  | [Dot](#Dot) | Templat MS Word 97-2007 (DOT) adalah berkas templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan berkas DOC atau DOCX selanjutnya. |
|
|  | [Docm](#Docm) | Berkas Office Open XML WordProcessingML Dokumen Makro-Aktif (DOCM) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau lebih tinggi dengan kemampuan menjalankan makro. |
|
|  | [Dotx](#Dotx) | Templat Office Open XML WordprocessingML Tanpa Makro (DOTX) adalah berkas templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan berkas DOCX selanjutnya. |
|
|  | [Dotm](#Dotm) | Templat Office Open XML WordprocessingML Makro-Aktif (DOTM) mewakili berkas templat yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML disimpan dalam berkas XML datar alih-alih paket ZIP. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) mewakili metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. |
|
|  | [Odt](#Odt) | Berkas Open Document Format Text Document (ODT) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format Berkas Teks OpenDocument. |
|
|  | [Ott](#Ott) | Templat Open Document Format Text Document (OTT) mewakili dokumen templat yang dihasilkan oleh aplikasi sesuai dengan format standar OpenDocument OASIS. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML Format \u2014 WordProcessingML atau WordML (.XML). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan koleksi enumerable dari semua [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mengambil sebuah instance dari tipe yang ditentukan [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) yang memiliki ekstensi berkas yang ditentukan. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Mengonversi string yang mewakili ekstensi berkas menjadi objek [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


Format File Biner MS Word 97-2007 (DOC) mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Dokumen Office Open XML WordProcessingML Tanpa Makro (DOCX) adalah format yang terkenal untuk dokumen Microsoft Word.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


Templat MS Word 97-2007 (DOT) adalah berkas templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan berkas DOC atau DOCX selanjutnya.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Berkas Office Open XML WordProcessingML Dokumen Makro-Aktif (DOCM) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau lebih tinggi dengan kemampuan menjalankan makro.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Templat Office Open XML WordprocessingML Tanpa Makro (DOTX) adalah berkas templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan berkas DOCX selanjutnya.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Templat Office Open XML WordprocessingML Makro-Aktif (DOTM) mewakili berkas templat yang dibuat dengan Microsoft Word 2007 atau lebih tinggi.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML disimpan dalam berkas XML datar alih-alih paket ZIP.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) mewakili metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Berkas Open Document Format Text Document (ODT) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format Berkas Teks OpenDocument.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Templat Open Document Format Text Document (OTT) mewakili dokumen templat yang dihasilkan oleh aplikasi sesuai dengan format standar OpenDocument OASIS.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML Format \u2014 WordProcessingML atau WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Mendapatkan koleksi enumerable dari semua [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
Nilai: Sebuah IEnumerable{WordProcessingFormats} yang berisi semua instance dari [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Mengambil sebuah instance dari tipe yang ditentukan [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) yang memiliki ekstensi berkas yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dari format dokumen. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Mengonversi string yang mewakili ekstensi berkas menjadi objek [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

