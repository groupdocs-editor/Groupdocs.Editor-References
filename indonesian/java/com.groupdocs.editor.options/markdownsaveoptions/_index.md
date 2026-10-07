---
title: "MarkdownSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Markdown"
type: docs
weight: 24
url: /id/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Markdown

<br />

*** ** * ** ***

Kelas MarkdownSaveOptions harus diterapkan oleh pengguna ketika ada instance kelas EditableDocument, yang berisi konten dokumen yang telah diedit, dan diperlukan untuk menyimpan konten ini ke dokumen baru dalam format Markdown.

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow menentukan cara menyelaraskan konten dalam tabel saat mengekspor ke format Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow menentukan cara menyelaraskan konten dalam tabel saat mengekspor ke format Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Menentukan folder fisik tempat gambar disimpan saat mengekspor dokumen ke |
format Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Menentukan folder fisik tempat gambar disimpan saat mengekspor dokumen ke |
format Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Menentukan apakah gambar disimpan dalam format Base64 ke file output. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Menentukan apakah gambar disimpan dalam format Base64 ke file output. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori.
Mengatur opsi ini ke
true
dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan mengorbankan waktu penyimpanan yang lebih lambat.
Default adalah
false
(optimasi memori dinonaktifkan demi kinerja yang lebih baik).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang menurunkan kinerja sebagai biaya pengurangan penggunaan memori.
Mengatur opsi ini ke
true
dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan mengorbankan waktu penyimpanan yang lebih lambat.
Default adalah
false
(optimasi memori dinonaktifkan demi kinerja yang lebih baik).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow menentukan cara menyelaraskan konten dalam tabel saat mengekspor ke format Markdown.
Nilai default adalah [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Nilai: Penyelarasan konten tabel


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow menentukan cara menyelaraskan konten dalam tabel saat mengekspor ke format Markdown.
Nilai default adalah [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Nilai: Penyelarasan konten tabel


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Menentukan folder fisik tempat gambar disimpan saat mengekspor dokumen ke
format Markdown. Default adalah null.

<br />

*** ** * ** ***

Jika tidak ada ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) maupun ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) yang ditentukan oleh pengguna, maka GroupDocs.Editor akan mencoba menentukan ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) secara otomatis dan menerapkannya jika berhasil

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Menentukan folder fisik tempat gambar disimpan saat mengekspor dokumen ke
format Markdown. Default adalah null.

<br />

*** ** * ** ***

Jika tidak ada ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) maupun ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) yang ditentukan oleh pengguna, maka GroupDocs.Editor akan mencoba menentukan ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) secara otomatis dan menerapkannya jika berhasil

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Menentukan apakah gambar disimpan dalam format Base64 ke file output. Default adalah
false
.

<br />

*** ** * ** ***

Ketika properti ini diatur ke true, data gambar diekspor langsung ke elemen gambar ![](../) dan file terpisah tidak dibuat. Properti ini, jika diatur ke true, memiliki prioritas lebih tinggi daripada properti MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Menentukan apakah gambar disimpan dalam format Base64 ke file output. Default adalah
false
.

<br />

*** ** * ** ***

Ketika properti ini diatur ke true, data gambar diekspor langsung ke elemen gambar ![](../) dan file terpisah tidak dibuat. Properti ini, jika diatur ke true, memiliki prioritas lebih tinggi daripada properti MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

