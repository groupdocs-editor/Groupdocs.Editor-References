---
title: "WordProcessingDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen Pengolah Kata"
type: docs
weight: 17
url: /id/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen Pengolah Kata

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dari dokumen WordProcessing ini |
|
|  | [getPageCount()](#getPageCount--) | Mengembalikan jumlah halaman |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dari dokumen WordProcessing ini |
|
|  | [isEncrypted()](#isEncrypted--) | Menentukan apakah dokumen WordProcessing spesifik ini terenkripsi dan |
memerlukan kata sandi untuk dibuka
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Membuat dan mengembalikan pratinjau halaman yang dipilih dalam bentuk gambar SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Menentukan apakah instance ini sama dengan yang lain yang ditentukan |
instance WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Mengembalikan format dari dokumen WordProcessing ini


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Mengembalikan jumlah halaman


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte dari dokumen WordProcessing ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Menentukan apakah dokumen WordProcessing spesifik ini terenkripsi dan
memerlukan kata sandi untuk dibuka


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Membuat dan mengembalikan pratinjau halaman yang dipilih dalam bentuk gambar SVG


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageIndex | int | Indeks berbasis 0 dari halaman yang diinginkan. Tidak boleh kurang dari 0, tidak dapat melebihi jumlah halaman dalam dokumen WordProcessing ini. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Menentukan apakah instance ini sama dengan yang lain yang ditentukan
instance WordProcessingDocumentInfo


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Instance WordProcessingDocumentInfo lain, yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

