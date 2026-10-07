---
title: "MarkdownDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mewakili metadata satu dokumen Markdown"
type: docs
weight: 13
url: /id/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Mewakili metadata satu dokumen Markdown

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFormat()](#getFormat--) | Mengembalikan format dokumen Markdown ini \\u2014 selalu |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Mengembalikan jumlah halaman. |
|
|  | [getSize()](#getSize--) | Mengembalikan ukuran dalam byte dokumen Markdown ini |
|
|  | [isEncrypted()](#isEncrypted--) | Karena dokumen Markdown tidak dapat dienkripsi dengan kata sandi, ini |
properti selalu mengembalikan 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Menentukan apakah instance ini sama dengan yang lain yang ditentukan |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Mengembalikan format dokumen Markdown ini \\u2014 selalu
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Mengembalikan jumlah halaman. Dokumen Markdown biasanya tidak memiliki halaman tetap
dan karena itu jumlah halaman, sehingga angka ini dihitung dari ukuran halaman standar
diatur ke A4 dalam orientasi potret.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Mengembalikan ukuran dalam byte dokumen Markdown ini


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Karena dokumen Markdown tidak dapat dienkripsi dengan kata sandi, ini
properti selalu mengembalikan 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Menentukan apakah instance ini sama dengan yang lain yang ditentukan
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Instansi lain [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo), yang harus diperiksa kesetaraannya dengan ini |
|

**Returns:**
boolean - True jika sama, false jika tidak sama

