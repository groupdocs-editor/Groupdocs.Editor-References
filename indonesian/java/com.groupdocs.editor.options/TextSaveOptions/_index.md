---
title: "TextSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen teks biasa TXT"
type: docs
weight: 41
url: /id/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan teks biasa (TXT)
dokumen

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Pengkodean karakter dokumen teks, yang akan diterapkan untuk |
menyimpan
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Pengkodean karakter dokumen teks, yang akan diterapkan untuk |
menyimpan
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Menentukan apakah menambahkan tanda bi-directional sebelum setiap run BiDi ketika |
mengekspor dalam format teks biasa.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Menentukan apakah menambahkan tanda bi-directional sebelum setiap run BiDi ketika |
mengekspor dalam format teks biasa
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Menentukan apakah program harus berusaha mempertahankan tata letak tabel |
saat menyimpan dalam format teks biasa.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Menentukan apakah program harus berusaha mempertahankan tata letak tabel |
saat menyimpan dalam format teks biasa.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Pengkodean karakter dokumen teks, yang akan diterapkan untuk
menyimpan


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Pengkodean karakter dokumen teks, yang akan diterapkan untuk
menyimpan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Menentukan apakah menambahkan tanda bi-directional sebelum setiap run BiDi ketika
mengekspor dalam format teks biasa. Defaultnya adalah 'false' \u2014 jangan tambahkan tanda BiDi.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Menentukan apakah menambahkan tanda bi-directional sebelum setiap run BiDi ketika
mengekspor dalam format teks biasa


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Menentukan apakah program harus berusaha mempertahankan tata letak tabel
saat menyimpan dalam format teks biasa. Nilai defaultnya adalah false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Menentukan apakah program harus berusaha mempertahankan tata letak tabel
saat menyimpan dalam format teks biasa. Nilai defaultnya adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

