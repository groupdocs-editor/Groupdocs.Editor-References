---
title: "VectorImageResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas dasar untuk setiap gambar vektor yang didukung"
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Kelas dasar untuk setiap gambar vektor yang didukung

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mengembalikan nama gambar vektor ini. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Mengembalikan nama file yang tepat untuk gambar vektor ini, yang terdiri dari nama dan |
ekstensi.
|
|  | [getAspectRatio()](#getAspectRatio--) | Mengembalikan rasio aspek gambar vektor ini |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Mengembalikan dimensi linier gambar vektor ini (lebar dan tinggi) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Memeriksa instance ini dengan kesetaraan referensi yang ditentukan. |
|
|  | [isDisposed()](#isDisposed--) | Menentukan apakah gambar raster ini telah dibuang atau tidak |
|
|  | [getType()](#getType--) | Dalam tipe implementasi, harus mengembalikan informasi tentang tipe vektor |
gambar
|
|  | [getByteContent()](#getByteContent--) | Dalam tipe implementasi, harus mengembalikan konten gambar vektor ini sebagai byte |
stream
|
|  | [getTextContent()](#getTextContent--) | Dalam tipe implementasi, harus mengembalikan konten gambar vektor ini dalam bentuk teks |
form: XML yang dienkode base64 terkait tipe gambar
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Dalam tipe implementasi, harus menyimpan gambar ini ke disk dengan jalur yang ditentukan |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Dalam tipe implementasi, harus menyimpan gambar vektor saat ini ke PNG raster |
format ke aliran byte yang ditentukan
|
|  | [dispose()](#dispose--) | Dalam tipe implementasi, harus membuang (dispose) instance ini |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Mengembalikan nama gambar vektor ini. Biasanya tidak mengandung nama file
ekstensi dan secara teoritis dapat berbeda dari nama file.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Mengembalikan nama file yang tepat untuk gambar vektor ini, yang terdiri dari nama dan
ekstensi. Secara teoritis dapat berbeda dari nama.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Mengembalikan rasio aspek gambar vektor ini


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Mengembalikan dimensi linier gambar vektor ini (lebar dan tinggi)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Memeriksa instance ini dengan kesetaraan referensi yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Instansi lain dari gambar vektor |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

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


Dalam tipe implementasi, harus mengembalikan informasi tentang tipe vektor
gambar


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Dalam tipe implementasi, harus mengembalikan konten gambar vektor ini sebagai byte
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Dalam tipe implementasi, harus mengembalikan konten gambar vektor ini dalam bentuk teks
form: XML yang dienkode base64 terkait tipe gambar


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Dalam tipe implementasi, harus menyimpan gambar ini ke disk dengan jalur yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Dalam tipe implementasi, harus menyimpan gambar vektor saat ini ke PNG raster
format ke aliran byte yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Aliran byte, tempat versi PNG dari gambar raster ini akan disimpan. Tidak boleh NULL dan harus mendukung penulisan. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Dalam tipe implementasi, harus membuang (dispose) instance ini


