---
title: IFormField
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents a form field.
type: docs
weight: 21
url: /nodejs-java/com.groupdocs.editor.words.fieldmanagement/iformfield/
---```
public interface IFormField
```

Represents a form field.
## Methods

| Method | Description |
| --- | --- |
| [getStylesheet()](#getStylesheet--) | Gets the stylesheet applied to the form field. |
| [getReadonly()](#getReadonly--) | Gets or sets a value indicating whether this [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) is readonly. |
| [setReadonly(boolean value)](#setReadonly-boolean-) | Gets or sets a value indicating whether this [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) is readonly. |
| [getName()](#getName--) | Gets the name of the form field. |
| [getType()](#getType--) | Gets the type of the form field. |
| [getLocaleId()](#getLocaleId--) | Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field. |
| [setLocaleId(int value)](#setLocaleId-int-) | Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field. |
| [getStatusText()](#getStatusText--) | Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus. |
| [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus. |
| [getHelpText()](#getHelpText--) | Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1. |
| [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1. |
### getStylesheet() {#getStylesheet--}
```
public abstract String getStylesheet()
```


Gets the stylesheet applied to the form field.

Value: The stylesheet.

**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public abstract boolean getReadonly()
```


Gets or sets a value indicating whether this [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) is readonly. Some analog of  HTML attribute: readonly .

Value:  true  if readonly; otherwise,  false .

**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public abstract void setReadonly(boolean value)
```


Gets or sets a value indicating whether this [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) is readonly. Some analog of  HTML attribute: readonly .

Value:  true  if readonly; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public abstract String getName()
```


Gets the name of the form field.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Gets the type of the form field.

**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public abstract int getLocaleId()
```


Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field.

--------------------

> ```
> The following example demonstrates how to set the LocaleId property:
>  
>  Set the LocaleId to represent the English (United States) culture
>  field.LocaleId = new CultureInfo("en-US").LCID;
> ```

--------------------

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public abstract void setLocaleId(int value)
```


Gets or sets the locale ID of the form field, which represents the culture or regional settings associated with the form field.

--------------------

> ```
> The following example demonstrates how to set the LocaleId property:
>  
>  Set the LocaleId to represent the English (United States) culture
>  field.LocaleId = new CultureInfo("en-US").LCID;
> ```

--------------------

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatusText() {#getStatusText--}
```
public abstract HelpText getStatusText()
```


Gets or sets the status text associated with the form field, the source of the text that's displayed in the status bar when a form field has the focus.

--------------------

If set to  false , the status text will not be applied.

**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public abstract void setStatusText(HelpText value)
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
public abstract HelpText getHelpText()
```


Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.

--------------------

If set to  false , the help text will not be applied.

**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public abstract void setHelpText(HelpText value)
```


Gets or sets the help text associated with the form field, the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.

--------------------

If set to  false , the help text will not be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

