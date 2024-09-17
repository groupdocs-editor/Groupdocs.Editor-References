---
title: op_Explicit
second_title: GroupDocs.Editor for .NET API Reference
description: Converts a string representing a format family name to a FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase object.
type: docs
weight: 100
url: /net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

Converts a string representing a format family name to a [`FormatFamilyBase`](../../formatfamilybase) object.

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Parameter | Type | Description |
| --- | --- | --- |
| family | String | The name of the format family to convert. |

### Return Value

A [`FormatFamilyBase`](../../formatfamilybase) object corresponding to the specified format family name.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when the specified format family name is invalid. |

### See Also

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Converts an integer representing a format family ID to a [`FormatFamilyBase`](../../formatfamilybase) object.

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | Int32 | The ID of the format family to convert. |

### Return Value

A [`FormatFamilyBase`](../../formatfamilybase) object corresponding to the specified format family ID.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when the specified format family ID is invalid. |

### See Also

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->