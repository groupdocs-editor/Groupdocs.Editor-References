---
title: "EmailDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen email dalam format email yang didukung apa pun"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen email dalam format email yang didukung apa pun

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dari dokumen email ini |
|
|  | [getPageCount()](#getPageCount--) | Selalu mengembalikan 1, karena dokumen email tidak memiliki tampilan berhalaman |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dari dokumen email ini |
|
|  | [isEncrypted()](#isEncrypted--) | Karena dokumen email tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Menentukan apakah instance ini sama dengan instance EmailDocumentInfo lain yang ditentukan |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Mengembalikan format dari dokumen email ini


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Selalu mengembalikan 1, karena dokumen email tidak memiliki tampilan berhalaman


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte dari dokumen email ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Karena dokumen email tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Menentukan apakah instance ini sama dengan instance EmailDocumentInfo lain yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Instance EmailDocumentInfo lain, yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

