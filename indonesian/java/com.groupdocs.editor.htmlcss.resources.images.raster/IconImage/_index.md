---
title: "IconImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar dalam format ICON dengan metadata-nya dan metode tambahan"
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Mewakili satu gambar dalam format ICON dengan metadata-nya dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Membuat instance IconImage baru dari konten, yang direpresentasikan sebagai |
string yang di-encode base64, dan dengan nama yang ditentukan
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Membuat instance IconImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah gambar ICON yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar ICON yang valid |
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Mengembalikan jumlah gambar yang ada dalam file ICON ini |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Membuat instance IconImage baru dari konten, yang direpresentasikan sebagai
string yang di-encode base64, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar ICON. Tidak boleh null, kosong, atau spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau spasi. Jika bukan konten ICON, pengecualian akan dilempar. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Membuat instance IconImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar ICON. Tidak boleh null, kosong, atau spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah gambar ICON yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte, yang kemungkinan berisi gambar ICON |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi gambar ICON yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar ICON yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Konten gambar ICON yang diperkirakan dalam bentuk string yang di-encode base64 |
|

**Returns:**
boolean - True jika string yang ditentukan berisi gambar ICON yang valid, false jika tidak

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Mengembalikan jumlah gambar yang ada dalam file ICON ini


**Returns:**
int
