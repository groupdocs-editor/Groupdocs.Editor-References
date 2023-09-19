---
title: PresentationDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one Presentation document
type: docs
weight: 14
url: /java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Represents metadata of one Presentation document
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this Presentation document |
| [getPageCount()](#getPageCount--) | Returns number of slides in this Presentation document |
| [getSize()](#getSize--) | Returns size in bytes of this Presentation document |
| [isEncrypted()](#isEncrypted--) | Indicates whether this specific Presentation document in encrypted and requires password for opening |
| [generatePreview(int slideIndex)](#generatePreview-int-) | Generates and returns a preview of the selected slide in a form of SVG image |
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Returns a format of this Presentation document

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returns number of slides in this Presentation document

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this Presentation document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indicates whether this specific Presentation document in encrypted and requires password for opening

**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Generates and returns a preview of the selected slide in a form of SVG image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slideIndex | int | 0-based index of the desired slide. Canot be lesser then 0, cannot exceed the number of slides in this presentation. |

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class
