---
title: "Woff2Font"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu font dalam format WOFF2 Web Open Font Format"
type: docs
weight: 16
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

Mewakili satu font dalam format WOFF2 (Web Open Font Format).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | Membuat kelas Woff2Font baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | Membuat kelas Woff2Font baru dari konten, yang direpresentasikan sebagai aliran byte, dan |
dengan nama yang ditentukan
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Ukuran header WOFF2 (dalam byte), yang diperlukan untuk validasinya |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan merupakan font WOFF2 yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di‑encode base64 yang ditentukan merupakan font WOFF2 yang valid |
|
|  | [getType()](#getType--) | Mengembalikan FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


Membuat kelas Woff2Font baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font WOFF2. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di‑encode base64. Tidak boleh null, kosong, atau berisi spasi. Jika bukan konten WOFF2, pengecualian akan dilempar. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


Membuat kelas Woff2Font baru dari konten, yang direpresentasikan sebagai aliran byte, dan
dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font WOFF2. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di‑seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Ukuran header WOFF2 (dalam byte), yang diperlukan untuk validasinya


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan merupakan font WOFF2 yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang diperkirakan berisi sumber daya WOFF2 |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi font WOFF2 yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di‑encode base64 yang ditentukan merupakan font WOFF2 yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten dari font WOFF2 yang diperkirakan dalam bentuk string yang di‑encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi font WOFF2 yang valid, false jika tidak

### getType() {#getType--}
```
public FontType getType()
```


Mengembalikan FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
