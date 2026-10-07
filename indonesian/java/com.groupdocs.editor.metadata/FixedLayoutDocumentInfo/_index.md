---
title: "FixedLayoutDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen dengan format tata letak tetap seperti PDF atau XPS"
type: docs
weight: 12
url: /id/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Mewakili metadata satu dokumen dengan format tata letak tetap seperti PDF atau XPS

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dari dokumen format tata letak tetap ini |
|
|  | [getPageCount()](#getPageCount--) | Mengembalikan jumlah halaman |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dari dokumen format tata letak tetap ini |
|
|  | [isEncrypted()](#isEncrypted--) | Menentukan apakah dokumen format tata letak tetap spesifik ini terenkripsi dan memerlukan kata sandi untuk dibuka |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Menentukan apakah instance ini sama dengan instance FixedLayoutDocumentInfo lain yang ditentukan |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Mengembalikan format dari dokumen format tata letak tetap ini


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Mengembalikan ukuran dalam byte dari dokumen format tata letak tetap ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Menentukan apakah dokumen format tata letak tetap spesifik ini terenkripsi dan memerlukan kata sandi untuk dibuka


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Menentukan apakah instance ini sama dengan instance FixedLayoutDocumentInfo lain yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Instance FixedLayoutDocumentInfo lain, yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

