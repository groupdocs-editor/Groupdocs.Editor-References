---
title: XpsSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving XPS XML Paper Specifications documents
type: docs
weight: 49
url: /java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving XPS (XML Paper Specifications) documents

--------------------

An XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.
## Constructors

| Constructor | Description |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFontEmbedding()](#getFontEmbedding--) | Responsible for embedding font resources into resultant XPS document, which are used in the original document. |
| [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
| [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Responsible for embedding font resources into resultant XPS document, which are used in the original document. By default doesn't embed any fonts (NotEmbed).

**Returns:**
byte
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. Setting this option to true can significantly decrease memory consumption while generating large documents at the cost of slower saving time. Default is false (memory optimization is disabled for the sake of better performance).

**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. Setting this option to true can significantly decrease memory consumption while generating large documents at the cost of slower saving time. Default is false (memory optimization is disabled for the sake of better performance).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

