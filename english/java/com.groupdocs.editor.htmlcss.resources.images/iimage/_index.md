---
title: IImage
second_title: GroupDocs.Editor for Java API Reference
description: Image CSS data type represents a two-dimensional image
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.resources.images/iimage/
---```
public interface IImage
```

Image CSS data type represents a two-dimensional image

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/image CSS reference declares 4 types of images, that can be handled: 1. Images with intrinsic dimensions (a natural size) and thus fixed aspect ratio, that includes all raster images. 2. Images with multiple intrinsic dimensions, existing in multiple versions inside a single file, that includes ICON (\*.ico) files. This may be also TIFF, as they support multiple images inside one file, however TIFF format is not supported in web. 3. Images with no intrinsic dimensions but with an intrinsic aspect ratio between its width and height. This includes all vector images, SVG first of all. 4. Images with neither intrinsic dimensions, nor an intrinsic aspect ratio. This includes all gradients.
