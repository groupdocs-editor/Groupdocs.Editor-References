---
title: LocaleId
second_title: GroupDocs.Editor for .NET API Reference
description: Gets or sets the locale ID of the form field which represents the culture or regional settings associated with the form field.
type: docs
weight: 30
url: /net/groupdocs.editor.words.fieldmanagement/numberformfield/localeid/
---
## NumberFormField.LocaleId property

Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field.

```csharp
public int LocaleId { get; set; }
```

### Remarks

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

### Examples

The following example demonstrates how to set the LocaleId property:

```csharp
Set the LocaleId to represent the English (United States) culture
numberField.LocaleId = new CultureInfo("en-US").LCID;
```

### See Also

* class [NumberFormField](../../numberformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
