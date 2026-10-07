---
title: "PngImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar dalam format PNG Portable Network Graphics dengan metadata dan metode tambahan"
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Mewakili satu gambar dalam format PNG (Portable Network Graphics) dengan
metadata dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Membuat instance PngImage baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Membuat instance PngImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah gambar PNG yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar PNG yang valid |
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Membuat instance PngImage baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar PNG. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau berisi spasi. Jika bukan konten PNG, pengecualian akan dilempar. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Membuat instance PngImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar PNG. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah gambar PNG yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi gambar PNG |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi gambar PNG yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar PNG yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten gambar PNG yang diperkirakan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi gambar PNG yang valid, false jika tidak

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
