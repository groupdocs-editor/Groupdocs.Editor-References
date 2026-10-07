---
title: "MarkdownImageLoadArgs"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Menyediakan data untuk peristiwa MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /id/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Menyediakan data untuk

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

peristiwa.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Mendapatkan atau mengatur nama file (seperti dalam dokumen Markdown) yang akan |
diproses.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Mendapatkan atau mengatur nama file (seperti dalam dokumen Markdown) yang akan |
diproses.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Dapatkan nilai yang menunjukkan apakah gambar ini memiliki tautan URI absolut. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Dapatkan nilai yang menunjukkan apakah gambar ini memiliki tautan URI absolut. |
|
|  | [setData(byte[] data)](#setData-byte---) | Mengatur data yang diberikan pengguna untuk sumber daya yang digunakan jika |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Mendapatkan atau mengatur nama file (seperti dalam dokumen Markdown) yang akan
diproses.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Mendapatkan atau mengatur nama file (seperti dalam dokumen Markdown) yang akan
diproses.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Dapatkan nilai yang menunjukkan apakah gambar ini memiliki tautan URI absolut.
Nilai:  true  jika gambar ini memiliki tautan URI absolut; jika tidak,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Dapatkan nilai yang menunjukkan apakah gambar ini memiliki tautan URI absolut.
Nilai:  true  jika gambar ini memiliki tautan URI absolut; jika tidak,  false .


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Mengatur data yang diberikan pengguna untuk sumber daya yang digunakan jika

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] |  |

