---
title: WmfImage
second_title: GroupDocs.Editor for .NET API Reference
description: Represents one vector image in WMF Windows MetaFile format with its metadata and additional methods
type: docs
weight: 590
url: /net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

Represents one vector image in WMF (Windows MetaFile) format with its metadata and additional methods

```csharp
public sealed class WmfImage : MetaImageBase
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | Creates new WmfImage instance from content, represented as byte stream, and with specified name |
| [WmfImage](wmfimage#constructor_1)(string, string) | Creates new WmfImage instance from content, represented as base64-encoded string, and with specified name |

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Returns aspect ratio of this vector image |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | Returns a content of this WMF image as a binary stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Returns correct filename of this vector image, which consists of name and extension. Theoretically can differ from the name. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Determines whether this raster image is disposed (`true`) or not (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Returns linear dimensions of this vector image (width and height) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Returns name of this vector image. Usually doesn't contain filename extension and theoretically can differ from filename. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | Returns a content of this WMF image as a plain text |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | Returns ImageType.Wmf |

## Methods

| Name | Description |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | Disposes this WMF image by disposing its content and making most its methods and properties non-working |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Checks this instance with specified on reference equality. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | Saves this WMF image to the file |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | Saves this vector WMF image into raster PNG image |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | Saves this vector WMF image into vector SVG image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | Checks whether specified stream is a valid WMF image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | Checks whether specified base64-encoded string is a valid WMF image |

## Events

| Name | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Event, which occurs when this raster image is disposed |

### See Also

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
