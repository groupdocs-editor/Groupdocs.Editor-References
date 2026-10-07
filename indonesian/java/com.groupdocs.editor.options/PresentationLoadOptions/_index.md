---
title: "PresentationLoadOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk memuat dokumen dari semua format Presentation yang didukung seperti PPTX PPTM PPSX, dll."
type: docs
weight: 33
url: /id/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Memungkinkan untuk menentukan opsi khusus untuk memuat dokumen dari semua yang didukung
Format Presentation seperti PPT(X), PPTM, PPS(X), dll.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
membuka dokumen Presentation, jika dokumen tersebut dienkripsi.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk |
membuka dokumen Presentation, jika dokumen tersebut dienkripsi.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
membuka dokumen Presentation, jika dokumen tersebut dienkripsi. Atur ke NULL atau kosong
string untuk menghapus kata sandi.


*** ** * ** ***

Secara default properti ini memiliki nilai NULL \\u2014 kata sandi tidak disetel. Jika dokumen Presentation input dilindungi kata sandi, kata sandi wajib dan pengecualian akan dilemparkan jika kata sandi tidak diberikan atau tidak valid. Jika dokumen Presentation input TIDAK dilindungi kata sandi, tetapi kata sandi disetel, maka akan diabaikan.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Memungkinkan untuk menentukan, memodifikasi, dan memperoleh kata sandi, yang akan digunakan untuk
membuka dokumen Presentation, jika dokumen tersebut dienkripsi. Atur ke NULL atau kosong
string untuk menghapus kata sandi.


*** ** * ** ***

Secara default properti ini memiliki nilai NULL \\u2014 kata sandi tidak disetel. Jika dokumen Presentation input dilindungi kata sandi, kata sandi wajib dan pengecualian akan dilemparkan jika kata sandi tidak diberikan atau tidak valid. Jika dokumen Presentation input TIDAK dilindungi kata sandi, tetapi kata sandi disetel, maka akan diabaikan.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

