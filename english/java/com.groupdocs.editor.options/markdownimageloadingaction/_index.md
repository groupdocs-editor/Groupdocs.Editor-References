---
title: MarkdownImageLoadingAction
second_title: GroupDocs.Editor for Java API Reference
description: Defines the mode of image loading while opening for editing the file in Markdown format
type: docs
weight: 23
url: /java/com.groupdocs.editor.options/markdownimageloadingaction/
---
**Inheritance:**
java.lang.Object
```
public final class MarkdownImageLoadingAction
```

Defines the mode of image loading while opening for editing the file in Markdown format
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | GroupDocs.Editor will load this resource as usual |
| [Skip](#Skip) | GroupDocs.Editor will skip loading of this image |
| [UserProvided](#UserProvided) | GroupDocs.Editor will use byte array provided by user in  M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])  as image data |
### Default {#Default}
```
public static final byte Default
```


GroupDocs.Editor will load this resource as usual

### Skip {#Skip}
```
public static final byte Skip
```


GroupDocs.Editor will skip loading of this image

### UserProvided {#UserProvided}
```
public static final byte UserProvided
```


GroupDocs.Editor will use byte array provided by user in  M:GroupDocs.Editor.Options.MarkdownImageLoadArgs.SetData(System.Byte[])  as image data

