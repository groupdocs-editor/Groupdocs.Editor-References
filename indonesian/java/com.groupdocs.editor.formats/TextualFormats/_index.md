---
title: "TextualFormats"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Menyatukan semua format berbasis teks termasuk markup XML HTML dan lainnya."
type: docs
weight: 16
url: /id/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Mengkapsulkan semua format tekstual (berbasis teks), termasuk markup (XML, HTML) dan lainnya.
Menyertakan format berikut:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Html](#Html) | Dokumen HyperText Markup Language (HTML) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. |
|
|  | [Xml](#Xml) | Dokumen eXtensible Markup Language (XML) yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek. |
|
|  | [Txt](#Txt) | Dokumen Teks Biasa (TXT) mewakili dokumen teks yang berisi teks polos dalam bentuk baris. |
|
|  | [Md](#Md) | Markdown adalah bahasa markup ringan untuk membuat teks terformat menggunakan editor teks biasa. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mentransmisikan data. |
|
|  | [Mhtml](#Mhtml) | Enkapsulasi MIME dari dokumen HTML agregat adalah format arsip halaman web yang digunakan untuk menggabungkan, dalam satu file komputer, kode HTML dan sumber daya pendampingnya. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help adalah format biner bantuan daring milik Microsoft, yang terdiri dari kumpulan halaman HTML, indeks, dan alat navigasi lainnya. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan koleksi enumerable dari semua [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mengambil instance dari tipe [TextualFormats](../../com.groupdocs.editor.formats/textualformats) yang memiliki ekstensi file yang ditentukan. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Mengonversi string yang mewakili ekstensi file menjadi objek [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


Dokumen HyperText Markup Language (HTML) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


Dokumen eXtensible Markup Language (XML) yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Dokumen Teks Biasa (TXT) mewakili dokumen teks yang berisi teks polos dalam bentuk baris.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown adalah bahasa markup ringan untuk membuat teks terformat menggunakan editor teks biasa.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mentransmisikan data.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


Enkapsulasi MIME dari dokumen HTML agregat adalah format arsip halaman web yang digunakan untuk menggabungkan, dalam satu file komputer, kode HTML dan sumber daya pendampingnya.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help adalah format biner bantuan daring milik Microsoft, yang terdiri dari kumpulan halaman HTML, indeks, dan alat navigasi lainnya.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Mendapatkan koleksi enumerable dari semua [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Nilai: Sebuah IEnumerable{TextualFormats} yang berisi semua instance dari [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Mengambil instance dari tipe [TextualFormats](../../com.groupdocs.editor.formats/textualformats) yang memiliki ekstensi file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dari format dokumen. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Mengonversi string yang mewakili ekstensi file menjadi objek [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

