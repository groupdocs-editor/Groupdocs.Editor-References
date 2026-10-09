---
title: "IMarkdownImageLoadCallback"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Υλοποιήστε αυτό το interface εάν θέλετε να ελέγχετε πώς το GroupDocs.Editor φορτώνει εικόνες κατά τη μετατροπή του Markdown σε Html."
type: docs
weight: 58
url: /el/nodejs-java/com.groupdocs.editor.options/imarkdownimageloadcallback/
---```
public interface IMarkdownImageLoadCallback
```

Implement this interface if you want to control how GroupDocs.Editor load
images when converting Markdown to Html.

## Methods

| Method | Description |
| --- | --- |
| [processImage(MarkdownImageLoadArgs args)](#processImage-com.groupdocs.editor.options.MarkdownImageLoadArgs-) | Called when GroupDocs.Editor load an image for converting Markdown to
Html.
 |
### processImage(MarkdownImageLoadArgs args) {#processImage-com.groupdocs.editor.options.MarkdownImageLoadArgs-}
```
public abstract byte processImage(MarkdownImageLoadArgs args)
```


Called when GroupDocs.Editor load an image for converting Markdown to
Html.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [MarkdownImageLoadArgs](../../com.groupdocs.editor.options/markdownimageloadargs) | The arguments.
 |

**Returns:**
byte
