---
title: TextFormField
second_title: GroupDocs.Editor for Java API Reference
description: Represents a form field that accepts text input.
type: docs
weight: 20
url: /java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

Represents a form field that accepts text input.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Initializes a new instance of the [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) class with the specified stylesheet and name. |
## Methods

| Method | Description |
| --- | --- |
| [getStylesheet()](#getStylesheet--) | Gets the stylesheet applied to the form field. |
| [getReadonly()](#getReadonly--) | Gets or sets a value indicating whether the form field is read-only. |
| [setReadonly(boolean value)](#setReadonly-boolean-) | Gets or sets a value indicating whether the form field is read-only. |
| [getName()](#getName--) | Gets the name of the form field. |
| [getType()](#getType--) | Gets the type of the form field, which is always FormFieldType.Text for this class. |
| [getLocaleId()](#getLocaleId--) | Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field. |
| [setLocaleId(int value)](#setLocaleId-int-) | Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field. |
| [getStatusText()](#getStatusText--) | Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus. |
| [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus. |
| [getHelpText()](#getHelpText--) | Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1. |
| [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1. |
| [getValue()](#getValue--) | Gets or sets the value of the form field, which represents the text input. |
| [setValue(String value)](#setValue-java.lang.String-) | Gets or sets the value of the form field, which represents the text input. |
| [getMaxLength()](#getMaxLength--) | Gets or sets the maximum length of the input for the form field. |
| [setMaxLength(int value)](#setMaxLength-int-) | Gets or sets the maximum length of the input for the form field. |
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Initializes a new instance of the [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) class with the specified stylesheet and name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | java.lang.String | The stylesheet to apply to the form field. |
| name | java.lang.String | The name of the form field. |

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Gets the stylesheet applied to the form field.

**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Gets or sets a value indicating whether the form field is read-only.

**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Gets or sets a value indicating whether the form field is read-only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Gets the name of the form field.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Gets the type of the form field, which is always FormFieldType.Text for this class.

**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field.

--------------------

> ```
> The following example demonstrates how to set the LocaleId property:
>  
>  Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
> ```

--------------------

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field.

--------------------

> ```
> The following example demonstrates how to set the LocaleId property:
>  
>  Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
> ```

--------------------

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus.

--------------------

If set to  false , the status text will not be applied.

**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus.

--------------------

If set to  false , the status text will not be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.

--------------------

If set to  false , the help text will not be applied.

**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.

--------------------

If set to  false , the help text will not be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


Gets or sets the value of the form field, which represents the text input.

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Gets or sets the value of the form field, which represents the text input.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Gets or sets the maximum length of the input for the form field.

**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Gets or sets the maximum length of the input for the form field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
