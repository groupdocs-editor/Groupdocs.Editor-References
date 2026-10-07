---
title: "RasterImageResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas dasar untuk semua gambar raster yang didukung dengan nama, dimensi, rasio aspek, tipe, ukuran, dan konten yang tetap."
type: docs
weight: 15
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Kelas dasar untuk semua gambar raster yang didukung dengan nama, dimensi, aspek
rasio, tipe, ukuran, dan konten.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mengembalikan nama gambar raster ini. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Mengembalikan nama file yang benar dari gambar raster ini, yang terdiri dari nama dan |
ekstensi.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Mengembalikan dimensi linier gambar raster ini (lebar dan tinggi) |
|
|  | [getAspectRatio()](#getAspectRatio--) | Mengembalikan rasio aspek gambar ini sebagai hubungan lebar-tinggi |
|
|  | [getLength()](#getLength--) | Mengembalikan panjang berkas gambar raster ini dalam byte |
|
|  | [getByteContent()](#getByteContent--) | Mengembalikan konten gambar raster ini sebagai aliran byte |
|
|  | [getTextContent()](#getTextContent--) | Mengembalikan konten gambar raster ini sebagai string base64-encoded |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Menyimpan gambar raster ini ke file yang ditentukan |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
|
|  | [dispose()](#dispose--) | Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode |
dan properti tidak berfungsi
|
|  | [isDisposed()](#isDisposed--) | Menentukan apakah gambar raster ini telah dibuang atau tidak |
|
|  | [getType()](#getType--) | Dalam implementasi, tipe harus mengembalikan informasi tentang tipe raster |
gambar
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Mengembalikan nama gambar raster ini. Biasanya tidak berisi nama file
ekstensi dan secara teoritis dapat berbeda dari nama file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Mengembalikan nama file yang benar dari gambar raster ini, yang terdiri dari nama dan
ekstensi. Secara teoritis dapat berbeda dari nama.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Mengembalikan dimensi linier gambar raster ini (lebar dan tinggi)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Mengembalikan rasio aspek gambar ini sebagai hubungan lebar-tinggi


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Mengembalikan panjang berkas gambar raster ini dalam byte


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Mengembalikan konten gambar raster ini sebagai aliran byte


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Mengembalikan konten gambar raster ini sebagai string base64-encoded


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Menyimpan gambar raster ini ke file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Jalur lengkap ke file, yang akan dibuat atau ditulis ulang |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Memeriksa instance ini dengan kesetaraan referensi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Pewarisan IHtmlResource lainnya |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang gambar raster ini, membuang kontennya dan membuat sebagian besar metode
dan properti tidak berfungsi


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Menentukan apakah gambar raster ini telah dibuang atau tidak


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Dalam implementasi, tipe harus mengembalikan informasi tentang tipe raster
gambar


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
