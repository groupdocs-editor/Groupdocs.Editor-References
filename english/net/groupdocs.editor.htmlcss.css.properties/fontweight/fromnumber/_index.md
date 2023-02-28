---
title: FromNumber
second_title: GroupDocs.Editor for .NET API Reference
description: Creates a fontweight from specified number
type: docs
weight: 50
url: /net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

Creates a font-weight from specified number

```csharp
public static FontWeight FromNumber(ushort number)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | UInt16 | Unsigned integer, must be within [1..1000] range |

### Return Value

New FontWeight instance or exception

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Specified number is out from [1..1000] range |

### See Also

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../fontweight)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->