---
title: MarkdownDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one Markdown document
type: docs
weight: 13
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
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this Markdown document \\u2014 always is [TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats\#Md) |
| [getPageCount()](#getPageCount--) | Returns number of pages. |
| [getSize()](#getSize--) | Returns size in bytes of this Markdown document |
| [isEncrypted()](#isEncrypted--) | Because Markdown documents cannot be encrypted with password, this property always returns 'false' |
| [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Determines whether this instance is equal to the other specified [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance. |
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Returns a format of this Markdown document \\u2014 always is [TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats\#Md)

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
