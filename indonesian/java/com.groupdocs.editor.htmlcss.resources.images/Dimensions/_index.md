---
title: "Dimensi"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili dimensi linier lebar dan tinggi dari satu gambar raster persegi panjang dalam satuan arbitrer."
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Mewakili dimensi linier (lebar dan tinggi) dari satu raster persegi panjang
gambar dalam satuan arbitrer. Struktur tidak dapat diubah.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Membuat instance baru dari lebar dan tinggi yang ditentukan |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Mengembalikan lebar gambar |
|
|  | [getHeight()](#getHeight--) | Mengembalikan tinggi gambar |
|
|  | [isSquare()](#isSquare--) | Menentukan apakah 'Dimensions' yang ditentukan mewakili persegi, yaitu |
|
|  | [getArea()](#getArea--) | Mengembalikan area (Lebar x Tinggi) |
|
|  | [isEmpty()](#isEmpty--) | Menentukan apakah instance "Dimensions" ini kosong dan default, yaitu |
|
|  | [getAspectRatio()](#getAspectRatio--) | Rasio aspek dimensi ini sebagai lebar/tinggi |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Membuat dan mengembalikan instance "Dimensions" baru, yang secara proporsional |
diubah ukurannya dari yang sekarang, berdasarkan lebar yang ditentukan
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Membuat dan mengembalikan instance "Dimensions" baru, yang secara proporsional |
diubah ukurannya dari yang sekarang, berdasarkan tinggi yang ditentukan
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Menentukan apakah instance ini sama dengan "Dimensions" yang ditentukan |
instance
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, |
yang kemungkinan adalah instance "Dimensions" lain
|
|  | [hashCode()](#hashCode--) | Mengembalikan hashcode untuk instance ini, yang tidak dapat diubah selama |
masa hidup
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Memeriksa apakah dua nilai "Dimensions" sama, yaitu |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Memeriksa apakah dua nilai "Dimensions" tidak sama, yaitu |
|
|  | [toString()](#toString--) | Mengembalikan representasi string dari "Dimensions" ini |
|
|  | [deepClone()](#deepClone--) | Mengembalikan salinan penuh dari instance ini |
|
|  | [getEmpty()](#getEmpty--) | Mengembalikan instance Dimensions kosong |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Membuat instance baru dari lebar dan tinggi yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | lebar | int | Lebar gambar |
|
|  | tinggi | int | Tinggi gambar |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mengembalikan lebar gambar


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mengembalikan tinggi gambar


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Menentukan apakah 'Dimensions' yang ditentukan mewakili persegi, yaitu jika
lebar sama dengan tinggi


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Mengembalikan area (Lebar x Tinggi)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Menentukan apakah instance "Dimensions" ini kosong dan default, yaitu
tidak menyimpan lebar dan tinggi yang benar


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Rasio aspek dimensi ini sebagai lebar/tinggi


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Membuat dan mengembalikan instance "Dimensions" baru, yang secara proporsional
diubah ukurannya dari yang sekarang, berdasarkan lebar yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | targetWidth | int | Lebar target baru, yang akan ada dalam Dimension hasil |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Membuat dan mengembalikan instance "Dimensions" baru, yang secara proporsional
diubah ukurannya dari yang sekarang, berdasarkan tinggi yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | targetHeight | int | Tinggi target baru, yang akan ada dalam Dimension hasil |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Menentukan apakah instance ini sama dengan "Dimensions" yang ditentukan
instance


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Instansi \"Dimensions\" lain untuk memeriksa kesetaraan |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik,
yang kemungkinan adalah instance "Dimensions" lain


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Objek lain, yang kemungkinan berjenis \"Dimensions\", yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan hashcode untuk instance ini, yang tidak dapat diubah selama
masa hidup


**Returns:**
int - hash-code tidak dapat diubah (untuk instansi ini) sebagai integer 4-byte bertanda

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Memeriksa apakah dua nilai \"Dimensions\" sama, yaitu mereka memiliki
lebar dan tinggi, atau keduanya kosong


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Instansi pertama untuk diperiksa |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Instansi kedua untuk diperiksa |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Memeriksa apakah dua nilai \"Dimensions\" tidak sama, yaitu
lebar dan/atau tinggi yang bersesuaian berbeda


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Instansi pertama untuk diperiksa |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Instansi kedua untuk diperiksa |
|

**Returns:**
boolean - True jika tidak sama, false jika sama

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari "Dimensions" ini

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - Instansi String, yang berisi lebar dan tinggi dalam format W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Mengembalikan salinan penuh dari instance ini


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Mengembalikan instance Dimensions kosong


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
