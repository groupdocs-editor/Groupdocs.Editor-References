---
title: "EmailFormats"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengkapsulkan semua format email."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Menyatukan semua format email. Menyertakan jenis berkas berikut:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Pelajari lebih lanjut tentang format email [di sini](../https://docs.fileformat.com/email/).

<br />


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) adalah format kepemilikan Microsoft untuk mengenkapsulasi lampiran email berdasarkan Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. |
|
|  | [Emlx](#Emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. |
|
|  | [Msg](#Msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. |
|
|  | [Html](#Html) | Email berformat HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML, singkatan dari "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) adalah standar internet (RFC 2445) untuk pertukaran dan penyebaran acara kalender serta penjadwalan. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. |
|
|  | [Pst](#Pst) | File dengan ekstensi .pst mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. |
|
|  | [Mbox](#Mbox) | Format file MBox adalah istilah umum yang mewakili wadah untuk kumpulan pesan surat elektronik. |
|
|  | [Oft](#Oft) | File dengan ekstensi .oft adalah file templat yang dibuat menggunakan Microsoft Outlook. |
|
|  | [Ost](#Ost) | File Offline Storage Table (OST) mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAll()](#getAll--) | Mendapatkan koleksi enumerable dari semua [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mengambil sebuah instance dari tipe yang ditentukan [EmailFormats](../../com.groupdocs.editor.formats/emailformats) yang memiliki ekstensi file tertentu. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Mengonversi string yang mewakili ekstensi file menjadi objek [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) adalah format kepemilikan Microsoft untuk mengenkapsulasi lampiran email berdasarkan Messaging Application Programming Interface (MAPI).
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


Email berformat HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, singkatan dari "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Internet Calendaring and Scheduling Core Object Specification (iCalendar) adalah standar internet (RFC 2445) untuk pertukaran dan penyebaran acara kalender serta penjadwalan.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


File dengan ekstensi .pst mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


Format file MBox adalah istilah umum yang mewakili wadah untuk kumpulan pesan surat elektronik.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


File dengan ekstensi .oft adalah file templat yang dibuat menggunakan Microsoft Outlook.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


File Offline Storage Table (OST) mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook.
Pelajari lebih lanjut tentang format berkas ini
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Mendapatkan koleksi enumerable dari semua [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Nilai: Sebuah IEnumerable{EmailFormats} yang berisi semua instance dari [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Mengambil sebuah instance dari tipe yang ditentukan [EmailFormats](../../com.groupdocs.editor.formats/emailformats) yang memiliki ekstensi file tertentu.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dari format dokumen. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Mengonversi string yang mewakili ekstensi file menjadi objek [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file yang akan dikonversi. Jika ekstensi berisi beberapa titik, bagian setelah titik terakhir yang digunakan. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

