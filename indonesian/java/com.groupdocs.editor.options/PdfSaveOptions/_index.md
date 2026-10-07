---
title: "PdfSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen PDF Portable Document Format"
type: docs
weight: 31
url: /id/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Memungkinkan menentukan opsi khusus untuk menghasilkan dan menyimpan PDF (Portable
Document Format) dokumen

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Kata sandi, yang akan diterapkan pada dokumen PDF yang dihasilkan sebagai kata sandi pengguna, diperlukan untuk membuka. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Kata sandi, yang akan diterapkan pada dokumen PDF yang dihasilkan sebagai kata sandi pengguna, diperlukan untuk membuka. |
|
|  | [getCompliance()](#getCompliance--) | Menentukan tingkat kepatuhan standar PDF untuk dokumen keluaran. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Menentukan tingkat kepatuhan standar PDF untuk dokumen keluaran. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen PDF hasil, yang digunakan dalam dokumen asli. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen PDF hasil, yang digunakan dalam dokumen asli. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi, yang akan diterapkan pada dokumen PDF yang dihasilkan sebagai kata sandi pengguna, diperlukan untuk membuka.
Jika NULL atau kosong, tidak ada kata sandi yang akan diterapkan pada dokumen. Jika tidak, dokumen akan dienkripsi dengan RC4 (panjang kunci 128 bit).
Secara default adalah NULL — kata sandi tidak diterapkan.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Kata sandi, yang akan diterapkan pada dokumen PDF yang dihasilkan sebagai kata sandi pengguna, diperlukan untuk membuka.
Jika NULL atau kosong, tidak ada kata sandi yang akan diterapkan pada dokumen. Jika tidak, dokumen akan dienkripsi dengan RC4 (panjang kunci 128 bit).
Secara default adalah NULL — kata sandi tidak diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Menentukan tingkat kepatuhan standar PDF untuk dokumen keluaran. Default adalah PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Menentukan tingkat kepatuhan standar PDF untuk dokumen keluaran. Default adalah PdfCompliance.Pdf17.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen PDF hasil, yang digunakan dalam dokumen asli. Secara default tidak menyematkan font apa pun (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen PDF hasil, yang digunakan dalam dokumen asli. Secara default tidak menyematkan font apa pun (NotEmbed).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori.
Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan biaya waktu penyimpanan yang lebih lambat.
Defaultnya adalah false (optimasi memori dinonaktifkan demi kinerja yang lebih baik).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori.
Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan biaya waktu penyimpanan yang lebih lambat.
Defaultnya adalah false (optimasi memori dinonaktifkan demi kinerja yang lebih baik).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

