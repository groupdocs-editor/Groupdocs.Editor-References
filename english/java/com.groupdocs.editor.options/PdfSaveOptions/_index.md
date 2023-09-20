---
title: PdfSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving PDF Portable Document Format documents
type: docs
weight: 28
url: /java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving PDF (Portable Document Format) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Password, which will be applied to the generated PDF document as user password, required for opening. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password, which will be applied to the generated PDF document as user password, required for opening. |
| [getCompliance()](#getCompliance--) | Specifies the PDF standards compliance level for output documents. |
| [setCompliance(byte value)](#setCompliance-byte-) | Specifies the PDF standards compliance level for output documents. |
| [getFontEmbedding()](#getFontEmbedding--) | Responsible for embedding font resources into resultant PDF document, which are used in the original document. |
| [setFontEmbedding(byte value)](#setFontEmbedding-byte-) | Responsible for embedding font resources into resultant PDF document, which are used in the original document. |
| [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
| [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password, which will be applied to the generated PDF document as user password, required for opening. If NULL or empty, no password will be applied to the document. Otherwise, document will be encrypted with RC4 (key length of 128 bit). By default is NULL \\u2014 password is not applied.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password, which will be applied to the generated PDF document as user password, required for opening. If NULL or empty, no password will be applied to the document. Otherwise, document will be encrypted with RC4 (key length of 128 bit). By default is NULL \\u2014 password is not applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final byte getCompliance()
```


Specifies the PDF standards compliance level for output documents. Default is PdfCompliance.Pdf17.

**Returns:**
byte
### setCompliance(byte value) {#setCompliance-byte-}
```
public final void setCompliance(byte value)
```


Specifies the PDF standards compliance level for output documents. Default is PdfCompliance.Pdf17.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Responsible for embedding font resources into resultant PDF document, which are used in the original document. By default doesn't embed any fonts (NotEmbed).

**Returns:**
byte
### setFontEmbedding(byte value) {#setFontEmbedding-byte-}
```
public final void setFontEmbedding(byte value)
```


Responsible for embedding font resources into resultant PDF document, which are used in the original document. By default doesn't embed any fonts (NotEmbed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

