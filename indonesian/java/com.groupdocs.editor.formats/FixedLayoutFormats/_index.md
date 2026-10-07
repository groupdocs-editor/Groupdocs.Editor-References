---
title: "FixedLayoutFormats"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan semua format tata letak tetap yang juga dikenal sebagai format fixed-page yang mencakup PDF dan XPS, ini tidak termasuk gambar raster"
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Mengkapsulkan semua format tata letak tetap (juga dikenal sebagai "fixed-page"), yang mencakup PDF dan XPS (ini tidak termasuk gambar raster)

<br />

*** ** * ** ***

Berbagai aplikasi penampilan atau penerbitan dokumen memungkinkan pengguna membuka (Adobe Acrobat, XPS Viewer), dan kadang mengedit (Adobe InDesign) dokumen dengan format tertentu. Aplikasi ini biasanya menghasilkan dokumen format yang disebut \u201cfixed-page\u201d. Format dokumen semacam itu menjelaskan secara tepat di mana konten dokumen\u2019s ditempatkan pada setiap halaman. Secara internal, format PDF atau XPS berisi deskripsi setiap halaman, serta instruksi menggambar, yang menentukan tata letak konten pada halaman. Ini mirip dengan format gambar, yang menjelaskan di mana konten ditampilkan baik dalam bentuk raster maupun vektor.

<br />


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan koleksi dapat diiterasi dari semua [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mengambil sebuah instance dari tipe yang ditentukan [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) yang memiliki ekstensi file yang ditentukan. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Mengonversi string yang mewakili ekstensi file menjadi objek [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Mendapatkan koleksi dapat diiterasi dari semua [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Nilai: Sebuah IEnumerable{FixedLayoutFormats} yang berisi semua instance dari [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Mengambil sebuah instance dari tipe yang ditentukan [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) yang memiliki ekstensi file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dari format dokumen. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Mengonversi string yang mewakili ekstensi file menjadi objek [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

