---
title: "EbookDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen EBook"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen EBook

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dokumen ini |
|
|  | [getPageCount()](#getPageCount--) | Mengembalikan jumlah halaman dalam kasus MOBI atau AZW3 atau jumlah bab dalam kasus ePub. |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dari dokumen eBook ini |
|
|  | [isEncrypted()](#isEncrypted--) | Karena dokumen eBook tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Menentukan apakah instance ini sama dengan instance EbookDocumentInfo lain yang ditentukan |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Mengembalikan format dokumen ini


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Mengembalikan jumlah halaman dalam kasus MOBI atau AZW3 atau jumlah bab dalam kasus ePub.

<br />

*** ** * ** ***

Dokumen eBook biasanya tidak memiliki halaman tetap sehingga tidak ada jumlah halaman. Dalam kasus ePub memungkinkan menghitung jumlah bab. Namun, format MOBI dan AZW3 juga tidak memiliki bab, sehingga angka ini dihitung dari ukuran halaman standar yang ditetapkan ke A4 dalam orientasi potret.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte dari dokumen eBook ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Karena dokumen eBook tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false'


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Menentukan apakah instance ini sama dengan instance EbookDocumentInfo lain yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Instance EbookDocumentInfo lain, yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

