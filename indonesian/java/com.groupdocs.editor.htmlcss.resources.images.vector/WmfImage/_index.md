---
title: "WmfImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar vektor dalam format WMF Windows MetaFile dengan metadata dan metode tambahan"
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Mewakili satu gambar vektor dalam format WMF (Windows MetaFile) dengan
metadata dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Membuat instance WmfImage baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Membuat instance WmfImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan adalah gambar WMF yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar WMF yang valid |
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten gambar WMF ini sebagai aliran biner |
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten gambar WMF ini sebagai teks biasa |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan gambar WMF ini ke file |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Menyimpan gambar WMF vektor ini menjadi gambar PNG raster |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Menyimpan gambar WMF vektor ini menjadi gambar SVG vektor |
|
|  | [dispose()](#dispose--) | Membuang gambar WMF ini dengan membuang kontennya dan membuat sebagian besar ... |
metode dan properti tidak berfungsi
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Membuat instance WmfImage baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar WMF. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau berisi spasi. Jika bukan konten WMF, pengecualian akan dilempar. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Membuat instance WmfImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar WMF. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan adalah gambar WMF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte masukan. Tidak boleh NULL, harus mendukung pembacaan dan pencarian. |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi gambar WMF yang valid, false jika tidak

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang di-encode base64 yang ditentukan adalah gambar WMF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String input, di mana konten gambar WMF disimpan dalam enkoding base64. Tidak boleh NULL atau kosong. |
|

**Returns:**
boolean - True jika string yang ditentukan berisi gambar WMF yang valid, false jika tidak

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Mengembalikan konten gambar WMF ini sebagai aliran biner


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Mengembalikan konten gambar WMF ini sebagai teks biasa


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Menyimpan gambar WMF ini ke file


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat (jika belum ada) atau ditimpa (jika sudah ada) dengan konten gambar WMF ini |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Menyimpan gambar WMF vektor ini menjadi gambar PNG raster


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Aliran output, tempat konten gambar PNG akan ditulis. Tidak boleh NULL dan harus dapat ditulisi. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Menyimpan gambar WMF vektor ini menjadi gambar SVG vektor


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Aliran output, tempat konten gambar SVG akan ditulis. Tidak boleh NULL dan harus dapat ditulisi. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Membuang gambar WMF ini dengan membuang kontennya dan membuat sebagian besar ...
metode dan properti tidak berfungsi


