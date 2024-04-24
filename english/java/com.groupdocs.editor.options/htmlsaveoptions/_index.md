---
title: HtmlSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for saving the  instance to the HTML format
type: docs
weight: 19
url: /java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Allows to specify custom options for saving the [EditableDocument](../../com.groupdocs.editor/editabledocument) instance to the HTML format
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHtmlTagCase()](#getHtmlTagCase--) | Controls how the HTML tag names will be present in HTML markup: All lower case (default value), All upper case, or First letter upper case |
| [setHtmlTagCase(byte value)](#setHtmlTagCase-byte-) | Controls how the HTML tag names will be present in HTML markup: All lower case (default value), All upper case, or First letter upper case |
| [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Controls which delimiter around the attribute values in HTML elements will be used: single quote (default value) or double quote |
| [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Controls which delimiter around the attribute values in HTML elements will be used: single quote (default value) or double quote |
| [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Controls where to store the CSS stylesheet(s): as external resources ( false ), or embed them into the HTML markup, inside the STYLE element in the HTML->HEAD section ( true ) |
| [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Controls where to store the CSS stylesheet(s): as external resources ( false ), or embed them into the HTML markup, inside the STYLE element in the HTML->HEAD section ( true ) |
| [getSavingCallback()](#getSavingCallback--) | Interface, which must be implemented by the end-user for saving all the external HTML resources |
| [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Interface, which must be implemented by the end-user for saving all the external HTML resources |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final byte getHtmlTagCase()
```


Controls how the HTML tag names will be present in HTML markup: All lower case (default value), All upper case, or First letter upper case

**Returns:**
byte
### setHtmlTagCase(byte value) {#setHtmlTagCase-byte-}
```
public final void setHtmlTagCase(byte value)
```


Controls how the HTML tag names will be present in HTML markup: All lower case (default value), All upper case, or First letter upper case

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Controls which delimiter around the attribute values in HTML elements will be used: single quote (default value) or double quote

**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Controls which delimiter around the attribute values in HTML elements will be used: single quote (default value) or double quote

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Controls where to store the CSS stylesheet(s): as external resources ( false ), or embed them into the HTML markup, inside the STYLE element in the HTML->HEAD section ( true )

**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Controls where to store the CSS stylesheet(s): as external resources ( false ), or embed them into the HTML markup, inside the STYLE element in the HTML->HEAD section ( true )

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Interface, which must be implemented by the end-user for saving all the external HTML resources

**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Interface, which must be implemented by the end-user for saving all the external HTML resources

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

