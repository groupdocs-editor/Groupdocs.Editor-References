---
title: "FixedLayoutEditOptionsBase"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas abstrak dasar untuk opsi semua dokumen dengan format tata letak tetap seperti PDF dan XPS"
type: docs
weight: 16
url: /id/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Kelas abstrak dasar untuk opsi semua dokumen dengan format tata letak tetap seperti PDF dan XPS

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Mendapatkan atau mengatur flag yang menunjukkan apakah gambar harus dilewati saat mengonversi dokumen fixed-layout input menjadi HTML hasil. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Mendapatkan atau mengatur flag yang menunjukkan apakah gambar harus dilewati saat mengonversi dokumen fixed-layout input menjadi HTML hasil. |
|
|  | [getPages()](#getPages--) | Memungkinkan untuk mengatur rentang halaman yang akan diproses. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Memungkinkan untuk mengatur rentang halaman yang akan diproses. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Memungkinkan untuk mengaktifkan (true) atau menonaktifkan (false) paginasi dalam dokumen HTML hasil. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Memungkinkan untuk mengaktifkan (true) atau menonaktifkan (false) paginasi dalam dokumen HTML hasil. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Mendapatkan atau mengatur flag yang menunjukkan apakah gambar harus dilewati saat mengonversi dokumen fixed-layout input menjadi HTML hasil. Default adalah false - gambar dipertahankan.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Mendapatkan atau mengatur flag yang menunjukkan apakah gambar harus dilewati saat mengonversi dokumen fixed-layout input menjadi HTML hasil. Default adalah false - gambar dipertahankan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Memungkinkan untuk mengatur rentang halaman yang akan diproses. Secara default semua halaman dokumen fixed-layout diproses.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Memungkinkan untuk mengatur rentang halaman yang akan diproses. Secara default semua halaman dokumen fixed-layout diproses.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Memungkinkan untuk mengaktifkan (true) atau menonaktifkan (false) paginasi dalam dokumen HTML hasil. Secara default dinonaktifkan (false).

<br />

*** ** * ** ***

Dokumen format fixed-layout (terutama PDF dan XPS) pada dasarnya memiliki halaman yang ketat, kontennya memiliki tata letak tetap dan terbagi menjadi halaman. Namun HTML yang dapat diedit sebagai hasil dapat ditampilkan dalam tampilan tanpa halaman atau tampilan berhalaman.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Memungkinkan untuk mengaktifkan (true) atau menonaktifkan (false) paginasi dalam dokumen HTML hasil. Secara default dinonaktifkan (false).

<br />

*** ** * ** ***

Dokumen format fixed-layout (terutama PDF dan XPS) pada dasarnya memiliki halaman yang ketat, kontennya memiliki tata letak tetap dan terbagi menjadi halaman. Namun HTML yang dapat diedit sebagai hasil dapat ditampilkan dalam tampilan tanpa halaman atau tampilan berhalaman.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

