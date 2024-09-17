---
title: FormatFamilyBase
second_title: GroupDocs.Editor for .NET API Reference
description: Represents the base class for format families providing common functionality for format family instances.
type: docs
weight: 60
url: /net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Represents the base class for format families, providing common functionality for format family instances.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Properties

| Name | Description |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Gets the unique identifier for the format family. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Gets the name of the format family. |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Determines whether this instance is equal to the specified [`FormatFamilyBase`](../formatfamilybase) instance. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Determines whether this instance is equal to the specified [`FormatFamilyBase`](../formatfamilybase) instance. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Returns a hash code for the current object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returns a string that represents the current object. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Retrieves an instance of the specified type *T* that has the specified name. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Retrieves an instance of the specified type *T* that has the specified identifier. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Retrieves all instances of the specified type *T* that derive from [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | Determines whether two [`FormatFamilyBase`](../formatfamilybase) instances are equal. (2 operators) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Converts a string representing a format family name to a [`FormatFamilyBase`](../formatfamilybase) object. (2 operators) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Converts a [`FormatFamilyBase`](../formatfamilybase) instance to an integer implicitly. (2 operators) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | Determines whether two [`FormatFamilyBase`](../formatfamilybase) instances are not equal. (2 operators) |

### Remarks

This class is abstract and must be inherited by a derived class that specifies the actual format family details.

### See Also

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->