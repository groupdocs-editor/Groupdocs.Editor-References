---
title: "IMarkdownImageLoadCallback"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "यदि आप नियंत्रित करना चाहते हैं कि GroupDocs.Editor मार्कडाउन को HTML में परिवर्तित करते समय छवियों को कैसे लोड करता है, तो इस इंटरफ़ेस को लागू करें।"
type: docs
weight: 58
url: /hi/java/com.groupdocs.editor.options/imarkdownimageloadcallback/
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
