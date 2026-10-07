---
title: "ImageType"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili satu format tipe gambar yang didukung yang mendukung format raster dan vektor"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Mewakili satu tipe gambar yang dapat didukung (format), mendukung baik format raster maupun vektor.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Tipe gambar tak terdefinisi - nilai khusus, yang seharusnya tidak muncul secara normal |
|
|  | [getJpeg()](#getJpeg--) | tipe gambar JPEG |
|
|  | [getPng()](#getPng--) | tipe gambar PNG |
|
|  | [getBmp()](#getBmp--) | tipe gambar BMP |
|
|  | [getGif()](#getGif--) | tipe gambar GIF |
|
|  | [getIcon()](#getIcon--) | tipe gambar ICON |
|
|  | [getSvg()](#getSvg--) | tipe gambar vektor SVG |
|
|  | [getWmf()](#getWmf--) | tipe gambar vektor WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | tipe gambar vektor EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | tipe gambar raster TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Mengembalikan nama formal dari format gambar ini. |
|
|  | [isVector()](#isVector--) | Menunjukkan apakah format tertentu ini berupa vektor (true) atau raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Ekstensi file (tanpa karakter titik di depan) dari tipe gambar tertentu |
dalam huruf kecil.
|
|  | [toString()](#toString--) | Mengembalikan properti FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | Kode MIME dari tipe gambar tertentu sebagai string. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Menentukan apakah instance ini sama dengan "ImageType" yang ditentukan |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, |
yang kemungkinan merupakan instance "ImageType" lain
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Mendefinisikan apakah dua instance ImageType tertentu sama |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Mendefinisikan apakah dua instance ImageType tertentu tidak sama |
|
|  | [hashCode()](#hashCode--) | Mengembalikan hash-code, yang merupakan angka tak berubah untuk spesifik ini |
instance
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Mengembalikan nilai ImageType, yang setara dengan ekstensi nama file, yang |
diambil dari nama file yang ditentukan
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Mengembalikan nilai ImageType, yang setara dengan kode MIME yang ditentukan |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Tipe gambar tak terdefinisi - nilai khusus, yang seharusnya tidak muncul secara normal


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


tipe gambar JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


tipe gambar PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


tipe gambar BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


tipe gambar GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


tipe gambar ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


tipe gambar vektor SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


tipe gambar vektor WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


tipe gambar vektor EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


tipe gambar raster TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Mengembalikan nama formal dari format gambar ini. Tidak pernah mengembalikan NULL. Jika
instance tidak rusak, tidak pernah melempar pengecualian.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Menunjukkan apakah format tertentu ini berupa vektor (true) atau raster
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Ekstensi file (tanpa karakter titik di depan) dari tipe gambar tertentu
dalam huruf kecil. Untuk tipe Undefined mengembalikan string 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Mengembalikan properti FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Kode MIME dari tipe gambar tertentu sebagai string. Untuk tipe Undefined
mengembalikan string 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Menentukan apakah instance ini sama dengan "ImageType" yang ditentukan
instance


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Instansi ImageType lain untuk memeriksa kesetaraan dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik,
yang kemungkinan merupakan instance "ImageType" lain


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Instansi System.Object lain, yang kemungkinan berjenis ImageType, untuk memeriksa kesetaraan dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Mendefinisikan apakah dua instance ImageType tertentu sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Instansi ImageType pertama untuk diperiksa |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Instansi ImageType kedua untuk diperiksa |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Mendefinisikan apakah dua instance ImageType tertentu tidak sama


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Instansi ImageType pertama untuk diperiksa |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Instansi ImageType kedua untuk diperiksa |
|

**Returns:**
boolean - True jika tidak sama, false jika sama

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hash-code, yang merupakan angka tak berubah untuk spesifik ini
instance


**Returns:**
int - Bilangan bulat bertanda 4-byte

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Mengembalikan nilai ImageType, yang setara dengan ekstensi nama file, yang
diambil dari nama file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama file | java.lang.String | Nama file arbitrer, dapat berupa jalur relatif atau jalur lengkap |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Mengembalikan nilai ImageType, yang setara dengan kode MIME yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Kode MIME sewenang-wenang |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

