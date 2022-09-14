---
title: TextEditOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Allows to specify custom options for loading plain text TXT documents
type: docs
weight: 38
url: /java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Allows to specify custom options for loading plain text (TXT) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getEncoding()](#getEncoding--) | Character encoding of the text document, which will be applied for its opening |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Character encoding of the text document, which will be applied for its opening |
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
| [getRecognizeLists()](#getRecognizeLists--) | Allows to specify how numbered list items are recognized when document is imported from plain text format. |
| [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Allows to specify how numbered list items are recognized when document is imported from plain text format. |
| [getLeadingSpaces()](#getLeadingSpaces--) | Gets or sets preferred option of a leading space handling. |
| [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Gets or sets preferred option of a leading space handling. |
| [getTrailingSpaces()](#getTrailingSpaces--) | Gets or sets preferred option of a trailing space handling. |
| [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Gets or sets preferred option of a trailing space handling. |
| [getEnablePagination()](#getEnablePagination--) | Allows to enable or disable pagination in the resultant HTML document. |
| [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Allows to enable or disable pagination in the resultant HTML document. |
| [getDirection()](#getDirection--) | Allows to specify the direction of text flow in the input plain text document. |
| [setDirection(int value)](#setDirection-int-) | Allows to specify the direction of text flow in the input plain text document. |
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Character encoding of the text document, which will be applied for its opening

**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Character encoding of the text document, which will be applied for its opening

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Text.Encoding |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Allows to specify how numbered list items are recognized when document is imported from plain text format. The default value is true.

--------------------

If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "\\u2022", "\*", "-" or "o"). If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols.

**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Allows to specify how numbered list items are recognized when document is imported from plain text format. The default value is true.

--------------------

If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "\\u2022", "\*", "-" or "o"). If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Gets or sets preferred option of a leading space handling. By default converts leading spaces to the left indent.

**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Gets or sets preferred option of a leading space handling. By default converts leading spaces to the left indent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Gets or sets preferred option of a trailing space handling. By default truncates all trailing spaces.

**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Gets or sets preferred option of a trailing space handling. By default truncates all trailing spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled (false).

**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled (false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Allows to specify the direction of text flow in the input plain text document. By default is Left-to-Right.

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Allows to specify the direction of text flow in the input plain text document. By default is Left-to-Right.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

