---
title: "SpreadsheetDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen Spreadsheet"
type: docs
weight: 15
url: /id/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen Spreadsheet

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dokumen Spreadsheet ini |
|
|  | [getPageCount()](#getPageCount--) | Mengembalikan jumlah tab |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dari dokumen Spreadsheet ini |
|
|  | [isEncrypted()](#isEncrypted--) | Menunjukkan apakah dokumen Spreadsheet spesifik ini dienkripsi dan |
memerlukan kata sandi untuk dibuka
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Membuat dan mengembalikan pratinjau lembar kerja yang dipilih dalam bentuk gambar SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Menentukan apakah instance ini sama dengan yang lain yang ditentukan |
instance SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Mengembalikan format dokumen Spreadsheet ini


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Mengembalikan jumlah tab


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte dari dokumen Spreadsheet ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Menunjukkan apakah dokumen Spreadsheet spesifik ini dienkripsi dan
memerlukan kata sandi untuk dibuka


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Membuat dan mengembalikan pratinjau lembar kerja yang dipilih dalam bentuk gambar SVG


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | worksheetIndex | int | Indeks berbasis 0 dari lembar kerja yang diinginkan. Tidak boleh kurang dari 0, tidak boleh melebihi jumlah lembar kerja dalam spreadsheet ini. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Menentukan apakah instance ini sama dengan yang lain yang ditentukan
instance SpreadsheetDocumentInfo


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Instance SpreadsheetDocumentInfo lain, yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

