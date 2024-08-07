---
title: DelimitedTextSaveOptions
second_title: GroupDocs.Editor for .NET API Reference
description: Contains options for generating and saving textbased Spreadsheet documents CSV Tabbased etc. that use a separator delimiter
type: docs
weight: 810
url: /net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Contains options for generating and saving text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | This parameterless constructor creates a new instance of DelimitedTextSaveOptions with a semicolon (;) default separator (can be modified then through [`Separator`](./separator) property) |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Creates an instance of options class for delimited text with mandatory separator (delimiter) |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Allows to set an encoding for the text-based Spreadsheet document. By default (and if not specified) is UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Indicates whether separators should be output for blank row. Default value is `false` which means the content for blank row will be empty. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Allows to specify a string separator (delimiter) for text-based Spreadsheet documents |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Indicates whether leading blank rows and columns should be trimmed like what MS Excel does |

### Remarks

https://en.wikipedia.org/wiki/Delimiter-separated_values

### See Also

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
