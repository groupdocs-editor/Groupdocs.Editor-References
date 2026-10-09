---
title: "IMarkdownImageLoadCallback"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "نفّذ هذه الواجهة إذا كنت ترغب في التحكم في طريقة تحميل GroupDocs.Editor للصور عند تحويل Markdown إلى Html."
type: docs
weight: 58
url: /ar/nodejs-java/com.groupdocs.editor.options/imarkdownimageloadcallback/
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
