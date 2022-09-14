---
title: IMarkdownImageSavingCallback
second_title: GroupDocs.Editor for Java API Reference
description:  Implement this interface if you want to control how GroupDocs.Editor saves
 images when saving a document to Markdown.
type: docs
weight: 57
url: /java/com.groupdocs.editor.options/imarkdownimagesavingcallback/
---```
public interface IMarkdownImageSavingCallback
```

Implement this interface if you want to control how GroupDocs.Editor saves images when saving a document to Markdown.
## Methods

| Method | Description |
| --- | --- |
| [imageSaving(MarkdownImageSavingArgs args)](#imageSaving-com.groupdocs.editor.options.MarkdownImageSavingArgs-) | Called when GroupDocs.Editor saves an image to Markdown. |
### imageSaving(MarkdownImageSavingArgs args) {#imageSaving-com.groupdocs.editor.options.MarkdownImageSavingArgs-}
```
public abstract byte imageSaving(MarkdownImageSavingArgs args)
```


Called when GroupDocs.Editor saves an image to Markdown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [MarkdownImageSavingArgs](../../com.groupdocs.editor.options/markdownimagesavingargs) | The arguments. |

**Returns:**
byte
