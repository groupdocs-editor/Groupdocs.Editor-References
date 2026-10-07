---
title: "PdfLoadOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Berisi opsi untuk memuat dokumen PDF ke dalam kelas Editor"
type: docs
weight: 30
url: /id/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Berisi opsi untuk memuat dokumen PDF ke dalam kelas Editor

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk membuka dokumen PDF, jika dokumen tersebut dienkripsi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk membuka dokumen PDF, jika dokumen tersebut dienkripsi. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk membuka dokumen PDF, jika dokumen tersebut dienkripsi.
Setel ke NULL atau string kosong agar tidak menggunakan kata sandi (nilai default).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk membuka dokumen PDF, jika dokumen tersebut dienkripsi.
Setel ke NULL atau string kosong agar tidak menggunakan kata sandi (nilai default).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

