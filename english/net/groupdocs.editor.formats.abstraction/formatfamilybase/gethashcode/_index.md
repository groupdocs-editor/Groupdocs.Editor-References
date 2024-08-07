---
title: GetHashCode
second_title: GroupDocs.Editor for .NET API Reference
description: Returns a hash code for the current object.
type: docs
weight: 40
url: /net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Returns a hash code for the current object.

```csharp
public override int GetHashCode()
```

### Return Value

A hash code for the current object, suitable for use in hashing algorithms and data structures like a hash table.

### Remarks

This method overrides GetHashCode. The hash code is computed using the object's `Id` and `Name` properties. The `unchecked` context allows overflow, which is acceptable in a hash code calculation context.

### See Also

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
