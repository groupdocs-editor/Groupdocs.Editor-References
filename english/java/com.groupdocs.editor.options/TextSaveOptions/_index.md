---
title: TextSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving plain text TXT documents
type: docs
weight: 37
url: /java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving plain text (TXT) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getEncoding()](#getEncoding--) | Character encoding of the text document, which will be applied for its saving |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Character encoding of the text document, which will be applied for its saving |
| [getAddBidiMarks()](#getAddBidiMarks--) | Specifies whether to add bi-directional marks before each BiDi run when exporting in plain text format. |
| [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Specifies whether to add bi-directional marks before each BiDi run when exporting in plain text format |
| [getPreserveTableLayout()](#getPreserveTableLayout--) | Specifies whether the program should attempt to preserve layout of tables when saving in the plain text format. |
| [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Specifies whether the program should attempt to preserve layout of tables when saving in the plain text format. |
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Character encoding of the text document, which will be applied for its saving

**Returns:**
java.nio.charset.Charset - 
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Character encoding of the text document, which will be applied for its saving

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Specifies whether to add bi-directional marks before each BiDi run when exporting in plain text format. Default is 'false' \\u2014 do not add BiDi marks.

**Returns:**
boolean - 
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Specifies whether to add bi-directional marks before each BiDi run when exporting in plain text format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Specifies whether the program should attempt to preserve layout of tables when saving in the plain text format. The default value is false.

**Returns:**
boolean - 
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Specifies whether the program should attempt to preserve layout of tables when saving in the plain text format. The default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

