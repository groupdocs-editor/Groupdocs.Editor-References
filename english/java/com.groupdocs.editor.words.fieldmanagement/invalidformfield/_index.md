---
title: InvalidFormField
second_title: GroupDocs.Editor for Java API Reference
description: Represents the update of invalid form field names during the FormFieldManager.FixInvalidFormFieldNames operation.
type: docs
weight: 18
url: /java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

Represents the update of invalid form field names during the  FormFieldManager.FixInvalidFormFieldNames  operation.
## Constructors

| Constructor | Description |
| --- | --- |
| [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | Initializes a new instance of the [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) class with the specified name. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the original name of the form field that cannot be modified outside  FormFieldManager . |
| [getFixedName()](#getFixedName--) | Gets or sets the new name for the form field after repair. |
| [setFixedName(String value)](#setFixedName-java.lang.String-) | Gets or sets the new name for the form field after repair. |
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


Initializes a new instance of the [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) class with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The original name of the form field. |

### getName() {#getName--}
```
public final String getName()
```


Gets the original name of the form field that cannot be modified outside  FormFieldManager .

**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


Gets or sets the new name for the form field after repair. This name removes duplicate unique identifiers with other form fields and sets a unique bookmark name.

--------------------

```
FixedName = String.format("%s_fixed", name); // as default value.
```

**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


Gets or sets the new name for the form field after repair. This name removes duplicate unique identifiers with other form fields and sets a unique bookmark name.

--------------------

```
FixedName = string.Format("{0}_fixed", name) // as default value.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

