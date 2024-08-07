---
title: DelimitedTextEditOptions
second_title: GroupDocs.Editor for .NET API Reference
description: Options for loading textbased Spreadsheet documents CSV Tabbased etc. that use a separator delimiter
type: docs
weight: 800
url: /net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Options for loading text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter)

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Creates an instance of options class for delimited text with mandatory separator (delimiter) |

## Properties

| Name | Description |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Gets or sets a value that indicates whether the string in text-based document is converted to the date data. Default is `false`. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Gets or sets a value that indicates whether the string in text-based document is converted to numeric data. Default is `false`. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. Useful when processing huge documents and facing OutOfMemoryException. Default is `false` (memory optimization is disabled for the sake of better performance). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Allows to specify a string separator (delimiter) for text-based Spreadsheet documents |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Defines whether consecutive delimiters should be treated as one. By default is `false`. |

### Remarks

https://en.wikipedia.org/wiki/Delimiter-separated_values

### See Also

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
