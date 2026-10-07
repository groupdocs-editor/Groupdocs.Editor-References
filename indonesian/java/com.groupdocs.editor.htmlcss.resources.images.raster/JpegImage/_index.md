---
title: "JpegImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar dalam format JPEG Joint Photographic Experts Group dengan metadata dan metode tambahan"
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Mewakili satu gambar dalam format JPEG (Joint Photographic Experts Group) dengan
metadata dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Membuat instance JpegImage baru dari konten, yang direpresentasikan sebagai |
string yang di-encode base64, dan dengan nama yang ditentukan
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Membuat instance JpegImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah gambar JPEG yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar JPEG yang valid |
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Membuat instance JpegImage baru dari konten, yang direpresentasikan sebagai
string yang di-encode base64, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar JPEG. Tidak boleh null, kosong, atau spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau spasi. Jika bukan konten JPEG, pengecualian akan dilempar. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Membuat instance JpegImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar JPEG. Tidak boleh null, kosong, atau spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah gambar JPEG yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi gambar JPEG |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi gambar JPEG yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar JPEG yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten gambar JPEG yang diperkirakan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi gambar JPEG yang valid, false jika tidak

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
