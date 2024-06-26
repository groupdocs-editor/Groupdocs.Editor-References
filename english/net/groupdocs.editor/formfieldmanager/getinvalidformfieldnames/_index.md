---
title: GetInvalidFormFieldNames
second_title: GroupDocs.Editor for .NET API Reference
description: Retrieves a collection of invalid form field names from the document.
type: docs
weight: 30
url: /net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

Retrieves a collection of invalid form field names from the document.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### Return Value

An enumerable collection of strings representing the names of invalid form fields found in the document.

### Remarks

The `GetInvalidFormFieldNames` method scans the document content to identify form fields with invalid names. It returns a collection of strings containing the names of these invalid form fields. A form field is considered invalid if it duplicates a unique identifier with other form fields and does not have a unique bookmark name associated with it. These bookmark names serve as identifiers for each form field. The returned collection maintains the order of form field names as they appear in the document. This method is useful for detecting and analyzing naming issues within form fields, which may need to be addressed using the [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames) method.

### See Also

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
