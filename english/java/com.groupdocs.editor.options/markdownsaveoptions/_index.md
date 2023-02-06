---
title: MarkdownSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving Markdown documents
type: docs
weight: 22
url: /java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving Markdown documents

--------------------

MarkdownSaveOptions class must be applied by the user when there is an instance of EditableDocument class, that contains an edited document content, and it is required to save this content to the new document of Markdown format.
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
| [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Specifies whether images are saved in Base64 format to the output file. |
| [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Specifies whether images are saved in Base64 format to the output file. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. Setting this option to  true  can significantly decrease memory consumption while generating large documents at the cost of slower saving time. Default is  false  (memory optimization is disabled for the sake of better performance).

**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. Setting this option to  true  can significantly decrease memory consumption while generating large documents at the cost of slower saving time. Default is  false  (memory optimization is disabled for the sake of better performance).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow specifies how to align contents in tables when exporting into the Markdown format. The default value is [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment\#Auto).

Value: The table content alignment

**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow specifies how to align contents in tables when exporting into the Markdown format. The default value is [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment\#Auto).

Value: The table content alignment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Specifies the physical folder where images are saved when exporting a document to the Markdown format. Default is null.

--------------------

If neither the  ImagesFolder (\#getImagesFolder.getImagesFolder/\#setImagesFolder(String).setImagesFolder(String)) nor  ExportImagesAsBase64 (\#getExportImagesAsBase64.getExportImagesAsBase64/\#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) are specified by the user, then the GroupDocs.Editor will try to determine the  ImagesFolder (\#getImagesFolder.getImagesFolder/\#setImagesFolder(String).setImagesFolder(String)) by itself and apply it on success

**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Specifies the physical folder where images are saved when exporting a document to the Markdown format. Default is null.

--------------------

If neither the  ImagesFolder (\#getImagesFolder.getImagesFolder/\#setImagesFolder(String).setImagesFolder(String)) nor  ExportImagesAsBase64 (\#getExportImagesAsBase64.getExportImagesAsBase64/\#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) are specified by the user, then the GroupDocs.Editor will try to determine the  ImagesFolder (\#getImagesFolder.getImagesFolder/\#setImagesFolder(String).setImagesFolder(String)) by itself and apply it on success

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Specifies whether images are saved in Base64 format to the output file. Default is  false .

--------------------

When this property is set to  true , then images data are exported directly into the image elements ![](../) and separate files are not created. This property, if set to  true , has the higher priority than the  MarkdownSaveOptions.ImagesFolder (\#getImagesFolder.getImagesFolder/\#setImagesFolder(String).setImagesFolder(String)) property.

**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Specifies whether images are saved in Base64 format to the output file. Default is  false .

--------------------

When this property is set to  true , then images data are exported directly into the image elements ![](../) and separate files are not created. This property, if set to  true , has the higher priority than the  MarkdownSaveOptions.ImagesFolder (\#getImagesFolder.getImagesFolder/\#setImagesFolder(String).setImagesFolder(String)) property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

