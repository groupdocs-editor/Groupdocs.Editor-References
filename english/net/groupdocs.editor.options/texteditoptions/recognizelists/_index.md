---
title: RecognizeLists
second_title: GroupDocs.Editor for .NET API Reference
description: Allows to specify how numbered list items are recognized when document is imported from plain text format. The default value is true.
type: docs
weight: 60
url: /net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Allows to specify how numbered list items are recognized when document is imported from plain text format. The default value is true.

```csharp
public bool RecognizeLists { get; set; }
```

### Remarks

If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "•", "*", "-" or "o"). If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols.

### See Also

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
