---
title: "TtfFont"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu font dalam format TTF TrueType Font"
type: docs
weight: 15
url: /id/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Mewakili satu font dalam format TTF (TrueType Font).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Membuat kelas TtfFont baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Membuat kelas TtfFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan |
dengan nama yang ditentukan
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Ukuran header TTF (dalam byte), yang diperlukan untuk validasinya |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan merupakan font TTF yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di‑encode base64 yang ditentukan merupakan font TTF yang valid |
|
|  | [getType()](#getType--) | Mengembalikan FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Membuat kelas TtfFont baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font TTF. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di‑encode base64. Tidak boleh null, kosong, atau berisi spasi. Jika bukan konten TTF, pengecualian akan dilempar. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Membuat kelas TtfFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan
dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama font TTF. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Ukuran header TTF (dalam byte), yang diperlukan untuk validasinya


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan merupakan font TTF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi sumber daya TTF |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi font TTF yang valid, false sebaliknya

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di‑encode base64 yang ditentukan merupakan font TTF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten font TTF yang kemungkinan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi font TTF yang valid, false sebaliknya

### getType() {#getType--}
```
public FontType getType()
```


Mengembalikan FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
