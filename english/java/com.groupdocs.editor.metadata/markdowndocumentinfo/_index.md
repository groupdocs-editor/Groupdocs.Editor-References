---
title: MarkdownDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one Markdown document
type: docs
weight: 19
url: /java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Represents metadata of one Markdown document
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownDocumentInfo()](#MarkdownDocumentInfo--) |  |
| [MarkdownDocumentInfo(int pageCount, long size)](#MarkdownDocumentInfo-int-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this Markdown document \\u2014 always is [TextualFormats\#Md](../../com.groupdocs.editor.formats/textualformats\#Md) |
| [getPageCount()](#getPageCount--) | Returns number of pages. |
| [getSize()](#getSize--) | Returns size in bytes of this Markdown document |
| [isEncrypted()](#isEncrypted--) | Because Markdown documents cannot be encrypted with password, this property always returns 'false' |
| [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Determines whether this instance is equal to the other specified [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance. |
| [CloneTo(MarkdownDocumentInfo that)](#CloneTo-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(MarkdownDocumentInfo obj1, MarkdownDocumentInfo obj2)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) |  |
### MarkdownDocumentInfo() {#MarkdownDocumentInfo--}
```
public MarkdownDocumentInfo()
```




### MarkdownDocumentInfo(int pageCount, long size) {#MarkdownDocumentInfo-int-long-}
```
public MarkdownDocumentInfo(int pageCount, long size)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageCount | int |  |
| size | long |  |

### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Returns a format of this Markdown document \\u2014 always is [TextualFormats\#Md](../../com.groupdocs.editor.formats/textualformats\#Md)

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returns number of pages. Markdown documents usually have no fixed pages and thus page count, so this number is calculated from standard page size set to A4 in portrait orientation.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this Markdown document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Because Markdown documents cannot be encrypted with password, this property always returns 'false'

**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Determines whether this instance is equal to the other specified [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Other [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### CloneTo(MarkdownDocumentInfo that) {#CloneTo-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public void CloneTo(MarkdownDocumentInfo that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) |  |

### Clone() {#Clone--}
```
public MarkdownDocumentInfo Clone()
```




**Returns:**
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo)
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
### equals(MarkdownDocumentInfo obj1, MarkdownDocumentInfo obj2) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public static boolean equals(MarkdownDocumentInfo obj1, MarkdownDocumentInfo obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) |  |
| obj2 | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) |  |

**Returns:**
boolean
