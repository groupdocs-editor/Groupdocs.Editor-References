---
title: MarkdownSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Allows to specify custom options for generating and saving Markdown documents
 after they were edited
type: docs
weight: 23
url: /java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving Markdown documents after they were edited

--------------------

MarkdownSaveOptions is applied in situations when there is an instance of EditableDocument class, that contains an edited document content, and it is required to save this content to the new document of Markdown format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
| [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
| [getTableContentAlignment()](#getTableContentAlignment--) | Allow specifies how to align contents in tables when exporting into the Markdown format. |
| [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow specifies how to align contents in tables when exporting into the Markdown format. |
| [getImagesFolder()](#getImagesFolder--) | Specifies the physical folder where images are saved when exporting a document to the Markdown format. |
| [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Specifies the physical folder where images are saved when exporting a document to the Markdown format. |
| [getImageSavingCallback()](#getImageSavingCallback--) | Allows to control how images are saved when a document is saved to Markdown format. |
| [setImageSavingCallback(IMarkdownImageSavingCallback value)](#setImageSavingCallback-com.groupdocs.editor.options.IMarkdownImageSavingCallback-) | Allows to control how images are saved when a document is saved to Markdown format. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


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

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow specifies how to align contents in tables when exporting into the Markdown format. The default value is [MarkdownTableContentAlignment\#Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment\#Auto).

Value: The table content alignment.

**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow specifies how to align contents in tables when exporting into the Markdown format. The default value is [MarkdownTableContentAlignment\#Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment\#Auto).

Value: The table content alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Specifies the physical folder where images are saved when exporting a document to the Markdown format. Default is an empty string.

Value: The images folder.

**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Specifies the physical folder where images are saved when exporting a document to the Markdown format. Default is an empty string.

Value: The images folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageSavingCallback() {#getImageSavingCallback--}
```
public final IMarkdownImageSavingCallback getImageSavingCallback()
```


Allows to control how images are saved when a document is saved to Markdown format.

Value: The image saving callback.

**Returns:**
[IMarkdownImageSavingCallback](../../com.groupdocs.editor.options/imarkdownimagesavingcallback)
### setImageSavingCallback(IMarkdownImageSavingCallback value) {#setImageSavingCallback-com.groupdocs.editor.options.IMarkdownImageSavingCallback-}
```
public final void setImageSavingCallback(IMarkdownImageSavingCallback value)
```


Allows to control how images are saved when a document is saved to Markdown format.

Value: The image saving callback.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMarkdownImageSavingCallback](../../com.groupdocs.editor.options/imarkdownimagesavingcallback) |  |

