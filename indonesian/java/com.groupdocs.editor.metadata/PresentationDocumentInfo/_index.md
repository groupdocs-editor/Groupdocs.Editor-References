---
title: "PresentationDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen Presentasi"
type: docs
weight: 14
url: /id/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen Presentasi

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dokumen Presentasi ini |
|
|  | [getPageCount()](#getPageCount--) | Mengembalikan jumlah slide dalam dokumen Presentasi ini |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dokumen Presentasi ini |
|
|  | [isEncrypted()](#isEncrypted--) | Menunjukkan apakah dokumen Presentasi spesifik ini terenkripsi dan memerlukan kata sandi untuk dibuka |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Membuat dan mengembalikan pratinjau slide yang dipilih dalam bentuk gambar SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Mengembalikan format dokumen Presentasi ini


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Mengembalikan jumlah slide dalam dokumen Presentasi ini


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte dokumen Presentasi ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Menunjukkan apakah dokumen Presentasi spesifik ini terenkripsi dan memerlukan kata sandi untuk dibuka


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Membuat dan mengembalikan pratinjau slide yang dipilih dalam bentuk gambar SVG


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | slideIndex | int | Indeks berbasis 0 dari slide yang diinginkan. Tidak boleh kurang dari 0, tidak dapat melebihi jumlah slide dalam presentasi ini. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

