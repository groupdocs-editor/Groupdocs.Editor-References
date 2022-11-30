---
title: WmfImage
second_title: GroupDocs.Editor for .NET API Reference
description: Creates new WmfImage instance from content represented as base64encoded string and with specified name
type: docs
weight: 10
url: /net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Creates new WmfImage instance from content, represented as base64-encoded string, and with specified name

```csharp
public WmfImage(string name, string contentInBase64)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of the WMF image. Cannot be null, empty or whitespaces. |
| contentInBase64 | String | Content as base64-encoded string. Cannot be null, empty or whitespaces. If it is not a WMF content, exception will be thrown. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### See Also

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* assembly [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Creates new WmfImage instance from content, represented as byte stream, and with specified name

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of the WMF image. Cannot be null, empty or whitespaces. |
| binaryContent | Stream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### See Also

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->