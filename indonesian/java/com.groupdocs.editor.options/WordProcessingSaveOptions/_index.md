---
title: "WordProcessingSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen yang mematuhi WordProcessing setelah diedit"
type: docs
weight: 48
url: /id/java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan
dokumen yang mematuhi WordProcessing setelah diedit


*** ** * ** ***

WordProcessingSaveOptions diterapkan dalam situasi ketika terdapat instance kelas EditableDocument, yang berisi konten dokumen yang telah diedit, dan diperlukan untuk menyimpan konten ini ke dokumen baru dengan format WordProcessing.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Konstruktor tanpa parameter ini membuat instance baru dari WordProcessingSaveOptions dengan format output DOCX (dapat diubah kemudian melalui |
OutputFormat
 (#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Membuat instance baru dari WordProcessingSaveOptions dengan spesifikasi |
format output WordProcessing wajib, sementara semua parameter lainnya adalah
bawaan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Mengizinkan mengaktifkan atau menonaktifkan pagination yang akan digunakan untuk menyimpan |
dokumen.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Mengizinkan mengaktifkan atau menonaktifkan pagination yang akan digunakan untuk menyimpan |
dokumen.
|
|  | [getPassword()](#getPassword--) | Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan |
digunakan untuk mengkodekan dokumen WordProcessing yang dihasilkan.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan |
digunakan untuk mengkodekan dokumen WordProcessing yang dihasilkan.
|
|  | [getOutputFormat()](#getOutputFormat--) | Mengizinkan menentukan format WordProcessing, yang akan digunakan untuk menyimpan |
dokumen
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Mengizinkan menentukan format WordProcessing, yang akan digunakan untuk menyimpan |
dokumen
|
|  | [getLocale()](#getLocale--) | Mengizinkan mengatur penggantian locale default (bahasa) untuk WordProcessing |
dokumen, yang akan diterapkan selama pembuatan.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Mengizinkan mengatur penggantian locale default (bahasa) untuk WordProcessing |
dokumen, yang akan diterapkan selama pembuatan.
|
|  | [getLocaleBi()](#getLocaleBi--) | Mengizinkan mengatur penggantian locale (bahasa) untuk dokumen WordProcessing |
untuk teks RTL (right-to-left), yang akan diterapkan selama
pembuatan.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Mengizinkan mengatur penggantian locale (bahasa) untuk dokumen WordProcessing |
untuk teks RTL (right-to-left), yang akan diterapkan selama
pembuatan.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Mengizinkan mengganti locale (bahasa) untuk dokumen WordProcessing |
untuk teks Asia Timur, yang akan diterapkan selama pembuatan.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Mengizinkan mengganti locale (bahasa) untuk dokumen WordProcessing |
untuk teks Asia Timur, yang akan diterapkan selama pembuatan.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari |
HTML, yang menurunkan kinerja sebagai biaya untuk mengurangi penggunaan memori.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari |
HTML, yang menurunkan kinerja sebagai biaya untuk mengurangi penggunaan memori.
|
|  | [getProtection()](#getProtection--) | Mengizinkan mengontrol dan menerapkan opsi perlindungan dokumen untuk |
dokumen WordProcessing dengan format apa pun, yang mendukung dokumen
perlindungan.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Mengizinkan mengontrol dan menerapkan opsi perlindungan dokumen untuk |
dokumen WordProcessing dengan format apa pun, yang mendukung dokumen
perlindungan.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Bertanggung jawab untuk menyematkan sumber daya font ke dalam output WordProcessing |
dokumen.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Bertanggung jawab untuk menyematkan sumber daya font ke dalam output WordProcessing |
dokumen.
|
|  | [deepClone()](#deepClone--) | Membuat dan mengembalikan salinan penuh dari instance ini |
kelas WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Konstruktor tanpa parameter ini membuat instance baru dari WordProcessingSaveOptions dengan format output DOCX (dapat diubah kemudian melalui
OutputFormat
 (#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Membuat instance baru dari WordProcessingSaveOptions dengan spesifikasi
format output WordProcessing wajib, sementara semua parameter lainnya adalah
bawaan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Format output wajib, di mana dokumen WordProcessing harus disimpan |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Mengizinkan mengaktifkan atau menonaktifkan pagination yang akan digunakan untuk menyimpan
dokumen. Jika dokumen asli dibuka dan diedit dalam pagination
mode, opsi ini juga harus diaktifkan. Secara default dinonaktifkan.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Mengizinkan mengaktifkan atau menonaktifkan pagination yang akan digunakan untuk menyimpan
dokumen. Jika dokumen asli dibuka dan diedit dalam pagination
mode, opsi ini juga harus diaktifkan. Secara default dinonaktifkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan
digunakan untuk mengenkripsi dokumen WordProcessing yang dihasilkan. Tentukan NULL atau
string kosong untuk menghapus (membersihkan) kata sandi.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengizinkan menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan
digunakan untuk mengenkripsi dokumen WordProcessing yang dihasilkan. Tentukan NULL atau
string kosong untuk menghapus (membersihkan) kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Mengizinkan menentukan format WordProcessing, yang akan digunakan untuk menyimpan
dokumen


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Mengizinkan menentukan format WordProcessing, yang akan digunakan untuk menyimpan
dokumen


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Mengizinkan mengatur penggantian locale default (bahasa) untuk WordProcessing
dokumen, yang akan diterapkan selama pembuatan. Ketika tidak
ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau
memilih) locale dokumen sesuai dengan pengaturan sendiri atau lainnya
faktor.


*** ** * ** ***

Opsi ini secara paksa menerapkan locale yang ditentukan ke seluruh teks dalam dokumen. Jangan gunakan ini, jika dokumen berisi bagian teks yang berbeda, yang ditulis dalam bahasa yang berbeda.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Mengizinkan mengatur penggantian locale default (bahasa) untuk WordProcessing
dokumen, yang akan diterapkan selama pembuatan. Ketika tidak
ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau
memilih) locale dokumen sesuai dengan pengaturan sendiri atau lainnya
faktor.

*** ** * ** ***


Opsi ini secara paksa menerapkan locale yang ditentukan ke seluruh teks dalam
dokumen. Jangan gunakan ini, jika dokumen berisi bagian yang berbeda dari
teks, yang ditulis dalam bahasa yang berbeda.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Mengizinkan mengatur penggantian locale (bahasa) untuk dokumen WordProcessing
untuk teks RTL (right-to-left), yang akan diterapkan selama
pembuatan. Ketika tidak ditentukan (nilai default), MS Word (atau program lain
program) akan mendeteksi (atau memilih) locale RTL dokumen sesuai dengan
pengaturan sendiri atau faktor lain.

*** ** * ** ***


Opsi ini secara paksa menerapkan locale yang ditentukan ke seluruh teks RTL
dalam dokumen. Jangan gunakan ini, jika dokumen berisi bagian yang berbeda dari
teks, yang ditulis dalam bahasa yang berbeda.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Mengizinkan mengatur penggantian locale (bahasa) untuk dokumen WordProcessing
untuk teks RTL (right-to-left), yang akan diterapkan selama
pembuatan. Ketika tidak ditentukan (nilai default), MS Word (atau program lain
program) akan mendeteksi (atau memilih) locale RTL dokumen sesuai dengan
pengaturan sendiri atau faktor lain.

*** ** * ** ***


Opsi ini secara paksa menerapkan locale yang ditentukan ke seluruh teks RTL
dalam dokumen. Jangan gunakan ini, jika dokumen berisi bagian yang berbeda dari
teks, yang ditulis dalam bahasa yang berbeda.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Mengizinkan mengganti locale (bahasa) untuk dokumen WordProcessing
untuk teks East-Asian, yang akan diterapkan selama pembuatan. Ketika
tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi
(atau memilih) locale East-Asian dokumen sesuai dengan pengaturan sendiri
atau faktor lain.

*** ** * ** ***


Opsi ini secara paksa menerapkan locale yang ditentukan ke seluruh
Teks Asia Timur dalam dokumen. Jangan gunakan jika dokumen berisi
bagian teks yang berbeda, yang ditulis pada yang berbeda
bahasa.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Mengizinkan mengganti locale (bahasa) untuk dokumen WordProcessing
untuk teks East-Asian, yang akan diterapkan selama pembuatan. Ketika
tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi
(atau memilih) locale East-Asian dokumen sesuai dengan pengaturan sendiri
atau faktor lain.

*** ** * ** ***


Opsi ini secara paksa menerapkan locale yang ditentukan ke seluruh
Teks Asia Timur dalam dokumen. Jangan gunakan jika dokumen berisi
bagian teks yang berbeda, yang ditulis pada yang berbeda
bahasa.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari
HTML, yang menurunkan kinerja sebagai biaya untuk mengurangi penggunaan memori.
Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori
saat menghasilkan dokumen besar dengan mengorbankan waktu penyimpanan yang lebih lambat.
Defaultnya adalah false (optimisasi memori dinonaktifkan demi
kinerja).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari
HTML, yang menurunkan kinerja sebagai biaya untuk mengurangi penggunaan memori.
Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori
saat menghasilkan dokumen besar dengan mengorbankan waktu penyimpanan yang lebih lambat.
Defaultnya adalah false (optimisasi memori dinonaktifkan demi
kinerja).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Mengizinkan mengontrol dan menerapkan opsi perlindungan dokumen untuk
dokumen WordProcessing dengan format apa pun, yang mendukung dokumen
perlindungan. Secara default adalah NULL - perlindungan dokumen tidak akan digunakan.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Mengizinkan mengontrol dan menerapkan opsi perlindungan dokumen untuk
dokumen WordProcessing dengan format apa pun, yang mendukung dokumen
perlindungan. Secara default adalah NULL - perlindungan dokumen tidak akan digunakan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Bertanggung jawab untuk menyematkan sumber daya font ke dalam output WordProcessing
dokumen. Secara default tidak menyematkan font apa pun (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Bertanggung jawab untuk menyematkan sumber daya font ke dalam output WordProcessing
dokumen. Secara default tidak menyematkan font apa pun (NotEmbed).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Membuat dan mengembalikan salinan penuh dari instance ini
kelas WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

