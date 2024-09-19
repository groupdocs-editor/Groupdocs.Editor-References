---
title: WordProcessingDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one WordProcessing document
type: docs
weight: 17
url: /java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Represents metadata of one WordProcessing document
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this WordProcessing document |
| [getPageCount()](#getPageCount--) | Returns number of pages |
| [getSize()](#getSize--) | Returns size in bytes of this WordProcessing document |
| [isEncrypted()](#isEncrypted--) | Determines whether this specific WordProcessing document in encrypted and requires password for opening |
| [generatePreview(int pageIndex)](#generatePreview-int-) | Generates and returns a preview of the selected page in a form of SVG image |
| [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Determines whether this instance is equal to the other specified WordProcessingDocumentInfo instance |
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Returns a format of this WordProcessing document

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returns number of pages

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this WordProcessing document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Determines whether this specific WordProcessing document in encrypted and requires password for opening

**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Generates and returns a preview of the selected page in a form of SVG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | 0-based index of the desired page. Cannot be lesser then 0, cannot exceed the number of pages in this WordProcessing document. |

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class
### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Determines whether this instance is equal to the other specified WordProcessingDocumentInfo instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Other WordProcessingDocumentInfo instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
