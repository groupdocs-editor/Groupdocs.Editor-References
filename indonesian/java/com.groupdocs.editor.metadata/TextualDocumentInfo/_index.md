---
title: "TextualDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen tekstual seperti XML HTML atau teks biasa TXT"
type: docs
weight: 16
url: /id/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen tekstual seperti XML, HTML atau teks biasa
(TXT)

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dokumen tekstual ini. |
|
|  | [getPageCount()](#getPageCount--) | Selalu mengembalikan 1 |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte (bukan jumlah karakter) dari teks ini |
dokumen
|
|  | [isEncrypted()](#isEncrypted--) | Selalu mengembalikan 'false', karena dokumen tekstual tidak dapat dienkripsi. |
|
|  | [getEncoding()](#getEncoding--) | Mengembalikan encoding yang terdeteksi kemungkinan dari dokumen teks |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Mengembalikan format dokumen tekstual ini. Mungkin tidak 100% tepat dalam
beberapa kasus.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Selalu mengembalikan 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte (bukan jumlah karakter) dari teks ini
dokumen


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Selalu mengembalikan 'false', karena dokumen tekstual tidak dapat dienkripsi.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Mengembalikan encoding yang terdeteksi kemungkinan dari dokumen teks


**Returns:**
java.nio.charset.Charset
