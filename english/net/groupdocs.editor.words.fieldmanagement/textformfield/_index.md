---
title: TextFormField
second_title: GroupDocs.Editor for .NET API Reference
description: Represents a form field that accepts text input.
type: docs
weight: 1420
url: /net/groupdocs.editor.words.fieldmanagement/textformfield/
---
## TextFormField class

Represents a form field that accepts text input.

```csharp
public sealed class TextFormField : IFormField
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFormField](textformfield)(string, string) | Initializes a new instance of the [`TextFormField`](../textformfield) class with the specified stylesheet and name. |

## Properties

| Name | Description |
| --- | --- |
| [HelpText](../../groupdocs.editor.words.fieldmanagement/textformfield/helptext) { get; set; } | Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1. |
| [LocaleId](../../groupdocs.editor.words.fieldmanagement/textformfield/localeid) { get; set; } | Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field. |
| [MaxLength](../../groupdocs.editor.words.fieldmanagement/textformfield/maxlength) { get; set; } | Gets or sets the maximum length of the input for the form field. |
| [Name](../../groupdocs.editor.words.fieldmanagement/textformfield/name) { get; } | Gets the name of the form field. |
| [Readonly](../../groupdocs.editor.words.fieldmanagement/textformfield/readonly) { get; set; } | Gets or sets a value indicating whether the form field is read-only. |
| [StatusText](../../groupdocs.editor.words.fieldmanagement/textformfield/statustext) { get; set; } | Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus. |
| [Stylesheet](../../groupdocs.editor.words.fieldmanagement/textformfield/stylesheet) { get; } | Gets the stylesheet applied to the form field. |
| [Type](../../groupdocs.editor.words.fieldmanagement/textformfield/type) { get; } | Gets the type of the form field, which is always FormFieldType.Text for this class. |
| [Value](../../groupdocs.editor.words.fieldmanagement/textformfield/value) { get; set; } | Gets or sets the value of the form field, which represents the text input. |

### See Also

* interface [IFormField](../iformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
