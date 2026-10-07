---
title: "SvgImage"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu gambar vektor dalam format SVG Scalable Vector Graphics dengan metadata dan metode tambahan"
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Mewakili satu gambar vektor dalam format SVG (Scalable Vector Graphics) dengan
metadata dan metode tambahan

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai string biasa, |
dan dengan nama yang ditentukan
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai aliran byte, |
dan dengan nama yang ditentukan
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Melakukan pemeriksaan permukaan apakah konten teks yang sesuai XML yang ditentukan |
mewakili gambar SVG
|
|  | [getType()](#getType--) | Mengembalikan ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten gambar SVG ini sebagai aliran biner |
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten gambar SVG ini sebagai teks biasa (dalam format XML) |
|
|  | [getXmlContent()](#getXmlContent--) | Mengembalikan konten gambar SVG ini dalam bentuk XML yang sesuai aslinya |
bentuk tekstual
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan gambar SVG ini ke file |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Menyimpan gambar SVG vektor ini menjadi gambar PNG raster |
|
|  | [dispose()](#dispose--) | Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode |
dan properti tidak berfungsi
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai string biasa,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar SVG. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | konten | java.lang.String | Konten sebagai string biasa, yang berisi konten SVG yang valid dan sesuai XML. Tidak boleh null, kosong, atau berisi spasi. Jika bukan konten SVG, pengecualian akan dilempar. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai aliran byte,
dan dengan nama yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama gambar SVG. Tidak boleh null, kosong, atau berisi spasi. |
|
|  | binaryContent | java.io.InputStream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Melakukan pemeriksaan permukaan apakah konten teks yang sesuai XML yang ditentukan
mewakili gambar SVG


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | konten | java.lang.String | Konten XML gambar SVG sebagai teks sederhana, bukan konten yang dienkode base64 |
|

**Returns:**
boolean - True jika string yang diberikan dapat dianggap sebagai SVG yang valid pada pandangan pertama, false jika pasti bukan SVG

### getType() {#getType--}
```
public ImageType getType()
```


Mengembalikan ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Mengembalikan konten gambar SVG ini sebagai aliran biner


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Mengembalikan konten gambar SVG ini sebagai teks biasa (dalam format XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Mengembalikan konten gambar SVG ini dalam bentuk XML yang sesuai aslinya
bentuk tekstual


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Menyimpan gambar SVG ini ke file


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat (jika belum ada) atau ditimpa (jika sudah ada) dengan konten gambar SVG ini |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Menyimpan gambar SVG vektor ini menjadi gambar PNG raster


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Aliran output, tempat konten gambar PNG akan ditulis. Tidak boleh NULL dan harus dapat ditulisi. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode
dan properti tidak berfungsi


