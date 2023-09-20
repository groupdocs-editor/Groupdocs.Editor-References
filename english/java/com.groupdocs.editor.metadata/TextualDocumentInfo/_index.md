---
title: TextualDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one textual document like XML HTML or plain text TXT
type: docs
weight: 16
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
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this textual document. |
| [getPageCount()](#getPageCount--) | Always returns 1 |
| [getSize()](#getSize--) | Returns size in bytes (not the number of characters) of this textual document |
| [isEncrypted()](#isEncrypted--) | Always returns 'false', as textual documents cannot be encrypted. |
| [getEncoding()](#getEncoding--) | Returns detected presumable encoding of the text document |
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
