---
title: EbookDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one EBook document
type: docs
weight: 10
url: /java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Represents metadata of one EBook document
## Constructors

| Constructor | Description |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this document |
| [getPageCount()](#getPageCount--) | Returns number of pages in case of MOBI or AZW3 or number of chapters in case of ePub. |
| [getSize()](#getSize--) | Returns size in bytes of this eBook document |
| [isEncrypted()](#isEncrypted--) | Because eBook documents cannot be encrypted with password, this property always returns 'false' |
| [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Determines whether this instance is equal to the other specified EbookDocumentInfo instance |
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Returns a format of this document

**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returns number of pages in case of MOBI or AZW3 or number of chapters in case of ePub.

--------------------

eBook documents usually have no fixed pages and thus page count. In case of ePub it is possible to calculate a number of chapters. However, the MOBI and AZW3 formats have no chapters either, so this number is calculated from standard page size set to A4 in portrait orientation.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this eBook document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Because eBook documents cannot be encrypted with password, this property always returns 'false'

**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Determines whether this instance is equal to the other specified EbookDocumentInfo instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Other EbookDocumentInfo instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
