---
title: XmlFormatOptions
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Contains options that allow to adjust the formatting of XML document when it is represented as HTML
type: docs
weight: 50
url: /nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Contains options, that allow to adjust the formatting of XML document, when it is represented as HTML
## Methods

| Method | Description |
| --- | --- |
| [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | When enabled, each and every pair of attribute-value in every XML element will be placed on a new line. |
| [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | When enabled, each and every pair of attribute-value in every XML element will be placed on a new line. |
| [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | When enabled, leaf text nodes (textual content inside XML elements, that has no children) will be rendered on a new line with bigger left indent. |
| [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | When enabled, leaf text nodes (textual content inside XML elements, that has no children) will be rendered on a new line with bigger left indent. |
| [getLeftIndent()](#getLeftIndent--) | Allows to specify an offset for the left indent of every new line. |
| [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Allows to specify an offset for the left indent of every new line. |
| [isDefault()](#isDefault--) | Indicates whether this instance of XML formatting options has a default value |
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


When enabled, each and every pair of attribute-value in every XML element will be placed on a new line. By default is false (disabled) \\u2014 all attribute-value pairs are placed in a single line.

**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


When enabled, each and every pair of attribute-value in every XML element will be placed on a new line. By default is false (disabled) \\u2014 all attribute-value pairs are placed in a single line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


When enabled, leaf text nodes (textual content inside XML elements, that has no children) will be rendered on a new line with bigger left indent. By default is false (disabled) \\u2014 leaf text nodes are placed on the same line as their parents, without new indent.

**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


When enabled, leaf text nodes (textual content inside XML elements, that has no children) will be rendered on a new line with bigger left indent. By default is false (disabled) \\u2014 leaf text nodes are placed on the same line as their parents, without new indent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Allows to specify an offset for the left indent of every new line. Cannot be a unitless non-zero value. By default is 10pt

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Allows to specify an offset for the left indent of every new line. Cannot be a unitless non-zero value. By default is 10pt

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this instance of XML formatting options has a default value

**Returns:**
boolean
