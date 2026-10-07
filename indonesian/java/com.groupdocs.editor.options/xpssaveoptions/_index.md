---
title: "XpsSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengizinkan penentuan opsi khusus untuk menghasilkan dan menyimpan dokumen XPS XML Paper Specifications"
type: docs
weight: 54
url: /id/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Memungkinkan menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen XPS (XML Paper Specifications).

<br />

*** ** * ** ***

File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen XPS hasil, yang digunakan dalam dokumen asli. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen XPS hasil, yang digunakan dalam dokumen asli.
Secara default tidak menyematkan font apa pun (NotEmbed).


**Returns:**
byte
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

