---
title: WordProcessingDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description:  Represents metadata of one WordProcessing document
type: docs
weight: 25
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
| [WordProcessingDocumentInfo(WordProcessingFormats format, int pageCount, long size, boolean isEncrypted)](#WordProcessingDocumentInfo-com.groupdocs.editor.formats.WordProcessingFormats-int-long-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this WordProcessing document |
| [getPageCount()](#getPageCount--) | Returns number of pages |
| [getSize()](#getSize--) | Returns size in bytes of this WordProcessing document |
| [isEncrypted()](#isEncrypted--) | Determines whether this specific WordProcessing document in encrypted and requires password for opening |
| [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Determines whether this instance is equal to the other specified WordProcessingDocumentInfo instance |
| [CloneTo(WordProcessingDocumentInfo that)](#CloneTo-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(WordProcessingDocumentInfo obj1, WordProcessingDocumentInfo obj2)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) |  |
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```




### WordProcessingDocumentInfo(WordProcessingFormats format, int pageCount, long size, boolean isEncrypted) {#WordProcessingDocumentInfo-com.groupdocs.editor.formats.WordProcessingFormats-int-long-boolean-}
```
public WordProcessingDocumentInfo(WordProcessingFormats format, int pageCount, long size, boolean isEncrypted)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |
| pageCount | int |  |
| size | long |  |
| isEncrypted | boolean |  |

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
### CloneTo(WordProcessingDocumentInfo that) {#CloneTo-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public void CloneTo(WordProcessingDocumentInfo that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) |  |

### Clone() {#Clone--}
```
public WordProcessingDocumentInfo Clone()
```




**Returns:**
[WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### equals(WordProcessingDocumentInfo obj1, WordProcessingDocumentInfo obj2) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public static boolean equals(WordProcessingDocumentInfo obj1, WordProcessingDocumentInfo obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) |  |
| obj2 | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) |  |

**Returns:**
boolean
