---
title: MarkdownEditOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Allows to specify custom options for editing documents in Markdown format.
type: docs
weight: 20
url: /java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents in Markdown format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownEditOptions()](#MarkdownEditOptions--) | Creates and returns a new instance of the MarkdownEditOptions class, where all options are set to their default values |
## Methods

| Method | Description |
| --- | --- |
| [getImageLoadCallback()](#getImageLoadCallback--) | Allows to control how images are saved when converting Markdown document to Html. |
| [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Allows to control how images are saved when converting Markdown document to Html. |
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Creates and returns a new instance of the MarkdownEditOptions class, where all options are set to their default values

### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Allows to control how images are saved when converting Markdown document to Html.

Value: The image saving callback.

**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Allows to control how images are saved when converting Markdown document to Html.

Value: The image saving callback.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

