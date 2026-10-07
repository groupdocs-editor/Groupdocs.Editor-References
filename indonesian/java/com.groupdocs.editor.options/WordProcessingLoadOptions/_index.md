---
title: "WordProcessingLoadOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Berisi opsi untuk memuat dokumen WordProcessing yang kompatibel dengan Word seperti DOCX, RTF, ODT, dll."
type: docs
weight: 45
url: /id/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Berisi opsi untuk memuat dokumen WordProcessing (kompatibel dengan Word) seperti
DOC(X), RTF, ODT dll. ke kelas Editor

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
membuka dokumen WordProcessing, jika itu terkodekan.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
membuka dokumen WordProcessing, jika itu terkodekan.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
membuka dokumen WordProcessing, jika itu terkodekan. Atur ke NULL atau kosong
string untuk tidak menggunakan kata sandi (nilai default).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
membuka dokumen WordProcessing, jika itu terkodekan. Atur ke NULL atau kosong
string untuk tidak menggunakan kata sandi (nilai default).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

