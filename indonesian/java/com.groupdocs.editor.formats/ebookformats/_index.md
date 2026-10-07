---
title: "EBookFormats"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan semua format eBook."
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Menyatukan semua format eBook. Mencakup jenis berkas berikut:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Pelajari lebih lanjut tentang format Mobi [di sini](../https://docs.fileformat.com/ebook/mobi/), dan tentang format ePub [di sini](../https://docs.fileformat.com/ebook/epub/).

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI adalah nama yang diberikan untuk format yang dikembangkan bagi MobiPocket Reader. |
|
|  | [Epub](#Epub) | Format Electronic Publication (IDPF ePub) adalah format berkas e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. |
|
|  | [Azw3](#Azw3) | AZW3, juga dikenal sebagai Kindle Format 8 (KF8), adalah versi modifikasi dari format berkas digital ebook AZW yang dikembangkan untuk perangkat Amazon Kindle. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan koleksi enumerable dari semua [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mengambil sebuah instance dari tipe [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) yang memiliki ekstensi berkas yang ditentukan. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Mengonversi string yang mewakili ekstensi berkas menjadi objek [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI adalah nama yang diberikan untuk format yang dikembangkan bagi MobiPocket Reader. Juga disebut PRC, AZW.
Saat ini digunakan oleh Amazon dengan skema DRM yang sedikit berbeda dan disebut AZW.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Format Electronic Publication (IDPF ePub) adalah format berkas e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, juga dikenal sebagai Kindle Format 8 (KF8), adalah versi modifikasi dari format berkas digital ebook AZW yang dikembangkan untuk perangkat Amazon Kindle.
Format ini merupakan peningkatan dari berkas AZW lama.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Mendapatkan koleksi enumerable dari semua [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Nilai: Sebuah IEnumerable{EBookFormats} yang berisi semua instance dari [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Mengambil sebuah instance dari tipe [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) yang memiliki ekstensi berkas yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dari format dokumen. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Mengonversi string yang mewakili ekstensi berkas menjadi objek [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

