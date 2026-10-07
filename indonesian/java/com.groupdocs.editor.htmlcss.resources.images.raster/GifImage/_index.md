---
title: "GifImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar dalam format GIF Graphics Interchange Format dengan metadata dan metode tambahan"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Mewakili satu gambar dalam format GIF (Graphics Interchange Format) dengan
metadata dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah gambar GIF yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string base64-encoded yang ditentukan adalah gambar GIF yang valid |
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Mengembalikan versi internal dari gambar GIF ini (versi diambil dari |
header)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar GIF. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau berisi spasi. Jika bukan konten GIF, pengecualian akan dilempar. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar GIF. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah gambar GIF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi gambar GIF |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi gambar GIF yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string base64-encoded yang ditentukan adalah gambar GIF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten gambar GIF yang diperkirakan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi gambar GIF yang valid, false jika tidak

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Mengembalikan versi internal dari gambar GIF ini (versi diambil dari
header)


**Returns:**
java.lang.String
