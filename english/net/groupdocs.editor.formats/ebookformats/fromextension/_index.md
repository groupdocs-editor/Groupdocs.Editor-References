---
title: FromExtension
second_title: GroupDocs.Editor for .NET API Reference
description: Returns instance of EBookFormatsgroupdocs.editor.formats/ebookformats structure associated to specified filename extension or throws an exception if extension cannot be properly parsed
type: docs
weight: 40
url: /net/groupdocs.editor.formats/ebookformats/fromextension/
---
## EBookFormats.FromExtension method

Returns instance of [`EBookFormats`](../../ebookformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed

```csharp
public static EBookFormats FromExtension(string extension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extension | String | Filename extension of any supportable EBook format, with or without leading dot character, case-independent. Cannot be NULL or empty, should be valid. |

### Return Value

Instance of [`EBookFormats`](../../ebookformats) structure on success or thrown exception on failure

### See Also

* struct [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
