---
title: TextualDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one textual document like XML HTML or plain text TXT
type: docs
weight: 24
url: /java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Represents metadata of one textual document like XML, HTML or plain text (TXT)
## Constructors

| Constructor | Description |
| --- | --- |
| [TextualDocumentInfo()](#TextualDocumentInfo--) |  |
| [TextualDocumentInfo(TextualFormats format, long size, System.Text.Encoding encoding)](#TextualDocumentInfo-com.groupdocs.editor.formats.TextualFormats-long-com.aspose.ms.System.Text.Encoding-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this textual document. |
| [getPageCount()](#getPageCount--) | Always returns 1 |
| [getSize()](#getSize--) | Returns size in bytes (not the number of characters) of this textual document |
| [isEncrypted()](#isEncrypted--) | Always returns 'false', as textual documents cannot be encrypted. |
| [getEncoding()](#getEncoding--) | Returns detected presumable encoding of the text document |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [CloneTo(TextualDocumentInfo that)](#CloneTo-com.groupdocs.editor.metadata.TextualDocumentInfo-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(TextualDocumentInfo obj1, TextualDocumentInfo obj2)](#equals-com.groupdocs.editor.metadata.TextualDocumentInfo-com.groupdocs.editor.metadata.TextualDocumentInfo-) |  |
### TextualDocumentInfo() {#TextualDocumentInfo--}
```
public TextualDocumentInfo()
```




### TextualDocumentInfo(TextualFormats format, long size, System.Text.Encoding encoding) {#TextualDocumentInfo-com.groupdocs.editor.formats.TextualFormats-long-com.aspose.ms.System.Text.Encoding-}
```
public TextualDocumentInfo(TextualFormats format, long size, System.Text.Encoding encoding)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [TextualFormats](../../com.groupdocs.editor.formats/textualformats) |  |
| size | long |  |
| encoding | com.aspose.ms.System.Text.Encoding |  |

### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Returns a format of this textual document. May be not 100% correct in some cases.

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Always returns 1

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes (not the number of characters) of this textual document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Always returns 'false', as textual documents cannot be encrypted.

**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Returns detected presumable encoding of the text document

**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### CloneTo(TextualDocumentInfo that) {#CloneTo-com.groupdocs.editor.metadata.TextualDocumentInfo-}
```
public void CloneTo(TextualDocumentInfo that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [TextualDocumentInfo](../../com.groupdocs.editor.metadata/textualdocumentinfo) |  |

### Clone() {#Clone--}
```
public TextualDocumentInfo Clone()
```




**Returns:**
[TextualDocumentInfo](../../com.groupdocs.editor.metadata/textualdocumentinfo)
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
### equals(TextualDocumentInfo obj1, TextualDocumentInfo obj2) {#equals-com.groupdocs.editor.metadata.TextualDocumentInfo-com.groupdocs.editor.metadata.TextualDocumentInfo-}
```
public static boolean equals(TextualDocumentInfo obj1, TextualDocumentInfo obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [TextualDocumentInfo](../../com.groupdocs.editor.metadata/textualdocumentinfo) |  |
| obj2 | [TextualDocumentInfo](../../com.groupdocs.editor.metadata/textualdocumentinfo) |  |

**Returns:**
boolean
