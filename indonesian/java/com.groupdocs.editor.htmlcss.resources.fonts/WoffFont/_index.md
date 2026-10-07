---
title: "WoffFont"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu font dalam format WOFF Web Open Font Format"
type: docs
weight: 17
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

Mewakili satu font dalam format WOFF (Web Open Font Format).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Membuat kelas WoffFont baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Membuat kelas WoffFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan |
dengan nama yang ditentukan
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Ukuran header WOFF (dalam byte), yang diperlukan untuk validasinya |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah font WOFF yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah font WOFF yang valid |
|
|  | [getType()](#getType--) | Mengembalikan FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Membuat kelas WoffFont baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font WOFF. Tidak boleh null, kosong, atau spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau spasi. Jika bukan konten WOFF, pengecualian akan dilempar. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Membuat kelas WoffFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan
dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font WOFF. Tidak boleh null, kosong, atau spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di‑seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Ukuran header WOFF (dalam byte), yang diperlukan untuk validasinya


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah font WOFF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi sumber daya WOFF |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi font WOFF yang valid, false sebaliknya

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di-encode base64 yang ditentukan adalah font WOFF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten font WOFF yang kemungkinan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi font WOFF yang valid, false sebaliknya

### getType() {#getType--}
```
public FontType getType()
```


Mengembalikan FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
