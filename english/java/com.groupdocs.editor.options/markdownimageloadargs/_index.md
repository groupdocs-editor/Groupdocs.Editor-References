---
title: MarkdownImageLoadArgs
second_title: GroupDocs.Editor for Java API Reference
description: Provides data for the MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs event.
type: docs
weight: 19
url: /java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Provides data for the  M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)  event.
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getImageFileName()](#getImageFileName--) | Gets or sets the file name (as is in the Markdown document) that will be process. |
| [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Gets or sets the file name (as is in the Markdown document) that will be process. |
| [isAbsoluteUri()](#isAbsoluteUri--) | Get a value indicating whether this image has absolute URI link. |
| [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Get a value indicating whether this image has absolute URI link. |
| [setData(byte[] data)](#setData-byte---) | Sets user provided data of the resource which is used if  M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)  |
| [getImageData()](#getImageData--) |  |
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Gets or sets the file name (as is in the Markdown document) that will be process.

**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Gets or sets the file name (as is in the Markdown document) that will be process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Get a value indicating whether this image has absolute URI link.

Value:  true  if this image has absolute URI link; otherwise,  false .

**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Get a value indicating whether this image has absolute URI link.

Value:  true  if this image has absolute URI link; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Sets user provided data of the resource which is used if  M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs) 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```




**Returns:**
byte[]
