---
title: "EotFont"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu font dalam format EOT Embedded OpenType"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Mewakili satu font dalam format EOT (Embedded OpenType).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Membuat kelas EotFont baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Membuat kelas EotFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan |
dengan nama yang ditentukan
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Ukuran header EOT (dalam byte), yang diperlukan untuk validasinya |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah font EOT yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah font EOT yang valid |
|
|  | [getType()](#getType--) | Mengembalikan FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Membuat kelas EotFont baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font EOT. Tidak boleh null, kosong, atau spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau spasi. Jika bukan konten EOT, pengecualian akan dilempar. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Membuat kelas EotFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan
dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font EOT. Tidak boleh null, kosong, atau spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Ukuran header EOT (dalam byte), yang diperlukan untuk validasinya


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah font EOT yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi sumber daya EOT |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi font EOT yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di-encode base64 yang ditentukan adalah font EOT yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten dari font EOT yang diperkirakan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi font EOT yang valid, false jika tidak

### getType() {#getType--}
```
public FontType getType()
```


Mengembalikan FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
