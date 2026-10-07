---
title: "MhtmlSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan enkapsulasi MIME MHTML dari dokumen HTML agregat"
type: docs
weight: 26
url: /id/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen MHTML (enkapsulasi MIME dari dokumen HTML agregat)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Menentukan apakah akan menggunakan URL CID (Content-ID) untuk merujuk sumber daya (gambar, font, CSS) yang termasuk dalam dokumen MHTML. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Menentukan apakah akan menggunakan URL CID (Content-ID) untuk merujuk sumber daya (gambar, font, CSS) yang termasuk dalam dokumen MHTML. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus ke MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus ke MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Menentukan apakah informasi bahasa diekspor ke MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Menentukan apakah informasi bahasa diekspor ke MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Menentukan apakah akan menggunakan URL CID (Content-ID) untuk merujuk sumber daya (gambar, font, CSS) yang termasuk dalam dokumen MHTML. Nilai default adalah
false
.

<br />

*** ** * ** ***


Secara default, sumber daya dalam dokumen MHTML dirujuk dengan nama file (misalnya, "image.png"), yang dicocokkan dengan header "Content-Location" pada bagian MIME. Opsi ini memungkinkan metode alternatif, di mana referensi ke file sumber daya ditulis sebagai URL CID (Content-ID) (misalnya, "cid:image.png") dan dicocokkan dengan header "Content-ID".


Secara teori, tidak seharusnya ada perbedaan antara dua metode referensi tersebut dan keduanya harusnya berfungsi dengan baik di semua peramban atau agen email. Namun dalam praktik, beberapa agen gagal mengambil sumber daya berdasarkan nama file. Jika peramban atau agen email Anda menolak memuat sumber daya yang termasuk dalam dokumen MTHML (tidak menampilkan gambar atau tidak memuat gaya CSS), coba ekspor dokumen dengan URL CID.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Menentukan apakah akan menggunakan URL CID (Content-ID) untuk merujuk sumber daya (gambar, font, CSS) yang termasuk dalam dokumen MHTML. Nilai default adalah
false
.

<br />

*** ** * ** ***


Secara default, sumber daya dalam dokumen MHTML dirujuk dengan nama file (misalnya, "image.png"), yang dicocokkan dengan header "Content-Location" pada bagian MIME. Opsi ini memungkinkan metode alternatif, di mana referensi ke file sumber daya ditulis sebagai URL CID (Content-ID) (misalnya, "cid:image.png") dan dicocokkan dengan header "Content-ID".


Secara teori, tidak seharusnya ada perbedaan antara dua metode referensi tersebut dan keduanya harusnya berfungsi dengan baik di semua peramban atau agen email. Namun dalam praktik, beberapa agen gagal mengambil sumber daya berdasarkan nama file. Jika peramban atau agen email Anda menolak memuat sumber daya yang termasuk dalam dokumen MTHML (tidak menampilkan gambar atau tidak memuat gaya CSS), coba ekspor dokumen dengan URL CID.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus ke MHTML. Nilai default adalah
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Menentukan apakah akan mengekspor properti dokumen bawaan dan khusus ke MHTML. Nilai default adalah
false
.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Menentukan apakah informasi bahasa diekspor ke MHTML. Nilai default adalah
false
.

<br />

*** ** * ** ***

Ketika properti ini diatur ke  true , GroupDocs.Editor menghasilkan atribut HTML  lang  pada elemen dokumen yang menentukan bahasa. Ini dapat diperlukan untuk mempertahankan semantik terkait bahasa.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Menentukan apakah informasi bahasa diekspor ke MHTML. Nilai default adalah
false
.

<br />

*** ** * ** ***

Ketika properti ini diatur ke  true , GroupDocs.Editor menghasilkan atribut HTML  lang  pada elemen dokumen yang menentukan bahasa. Ini dapat diperlukan untuk mempertahankan semantik terkait bahasa.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

