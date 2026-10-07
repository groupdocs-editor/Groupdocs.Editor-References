---
title: "EmfImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar vektor dalam format metafile yang ditingkatkan EMF dengan metadata dan metode tambahan"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Mewakili satu gambar vektor dalam format metafile yang ditingkatkan (EMF) dengan
metadata dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Membuat instance EmfImage baru dari konten, yang direpresentasikan sebagai base64-encoded |
string, dan dengan nama yang ditentukan
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Membuat instance EmfImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Memeriksa apakah aliran yang ditentukan merupakan gambar EMF yang valid |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Memeriksa apakah string yang dienkode base64 yang ditentukan merupakan gambar EMF yang valid |
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten gambar EMF ini sebagai aliran biner |
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten gambar EMF ini sebagai teks biasa |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan gambar EMF ini ke file |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Menyimpan gambar EMF vektor ini ke dalam gambar PNG raster |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Menyimpan gambar EMF vektor ini ke dalam gambar SVG vektor |
|
|  | [dispose()](#dispose--) | Menonaktifkan gambar EMF ini dengan membuang kontennya dan membuat sebagian besar |
metode dan properti tidak berfungsi
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Membuat instance EmfImage baru dari konten, yang direpresentasikan sebagai base64-encoded
string, dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar EMF. Tidak boleh null, kosong, atau hanya spasi. |
|
|  | contentInBase64 | java.lang.String | Konten sebagai string yang dienkode base64. Tidak boleh null, kosong, atau hanya spasi. Jika bukan konten EMF, pengecualian akan dilempar. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Membuat instance EmfImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar EMF. Tidak boleh null, kosong, atau hanya spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Memeriksa apakah aliran yang ditentukan merupakan gambar EMF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Aliran byte masukan. Tidak boleh NULL, harus mendukung pembacaan dan pencarian. |
|

**Returns:**
boolean - True jika aliran yang ditentukan berisi gambar EMF yang valid, false sebaliknya

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Memeriksa apakah string yang dienkode base64 yang ditentukan merupakan gambar EMF yang valid


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String input, tempat konten gambar EMF disimpan dalam enkoding base64. Tidak boleh NULL atau kosong. |
|

**Returns:**
boolean - True jika string yang ditentukan berisi gambar EMF yang valid, false sebaliknya

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Mengembalikan konten gambar EMF ini sebagai aliran biner


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Mengembalikan konten gambar EMF ini sebagai teks biasa


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Menyimpan gambar EMF ini ke file


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat (jika belum ada) atau ditimpa (jika sudah ada) dengan konten gambar EMF ini |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Menyimpan gambar EMF vektor ini ke dalam gambar PNG raster


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Aliran output, tempat konten gambar PNG akan ditulis. Tidak boleh NULL dan harus dapat ditulisi. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Menyimpan gambar EMF vektor ini ke dalam gambar SVG vektor


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Aliran output, tempat konten gambar SVG akan ditulis. Tidak boleh NULL dan harus dapat ditulisi. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Menonaktifkan gambar EMF ini dengan membuang kontennya dan membuat sebagian besar
metode dan properti tidak berfungsi


