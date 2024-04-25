---
title: XmlEditOptions
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Allows to specify custom options for loading XML eXtensible Markup Language documents and converting them to the HTML
type: docs
weight: 49
url: /nodejs-java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Allows to specify custom options for loading XML (eXtensible Markup Language) documents and converting them to the HTML
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getEncoding()](#getEncoding--) | Character encoding of the text document, which will be applied for its opening. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Character encoding of the text document, which will be applied for its opening. |
| [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Allows to enable or disable mechanism for fixing corrupted XML structure. |
| [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Allows to enable or disable mechanism for fixing corrupted XML structure. |
| [getRecognizeUris()](#getRecognizeUris--) | Allows to enable URI recognition algorithm |
| [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Allows to enable URI recognition algorithm |
| [getRecognizeEmails()](#getRecognizeEmails--) | Allows to enable recognition algorithm for email addresses in attribute values |
| [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Allows to enable recognition algorithm for email addresses in attribute values |
| [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Allows to enable the truncation of trailing whitespaces in the inner-tag text. |
| [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Allows to enable the truncation of trailing whitespaces in the inner-tag text. |
| [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Allows to specify quote type (single or double quotes) for attribute values. |
| [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Allows to specify quote type (single or double quotes) for attribute values. |
| [getHighlightOptions()](#getHighlightOptions--) | Allows to adjust the XML highlighting, that will be applied to the XML structure, when it is represented in HTML. |
| [getFormatOptions()](#getFormatOptions--) | Allows to adjust the XML formatting, that will be applied to the XML structure, when it is represented in HTML. |
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Character encoding of the text document, which will be applied for its opening. By default is null \\u2014 internal document encoding will be applied.

**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Character encoding of the text document, which will be applied for its opening. By default is null \\u2014 internal document encoding will be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Allows to enable or disable mechanism for fixing corrupted XML structure. By default is disabled (false).

--------------------

By default only proper valid well-formed XML documents are acceptable. When this option is enabled, GroupDocs.Editor will try to fix corrupted XML structure if possible.

**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Allows to enable or disable mechanism for fixing corrupted XML structure. By default is disabled (false).

--------------------

By default only proper valid well-formed XML documents are acceptable. When this option is enabled, GroupDocs.Editor will try to fix corrupted XML structure if possible.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Allows to enable URI recognition algorithm

**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Allows to enable URI recognition algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Allows to enable recognition algorithm for email addresses in attribute values

**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Allows to enable recognition algorithm for email addresses in attribute values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Allows to enable the truncation of trailing whitespaces in the inner-tag text. By default is disabled (false) \\u2014 trailing whitespaces will be preserved.

**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Allows to enable the truncation of trailing whitespaces in the inner-tag text. By default is disabled (false) \\u2014 trailing whitespaces will be preserved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Allows to specify quote type (single or double quotes) for attribute values. Double quotes are default.

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Allows to specify quote type (single or double quotes) for attribute values. Double quotes are default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Allows to adjust the XML highlighting, that will be applied to the XML structure, when it is represented in HTML. Default highlighting is used and is adjustable. Cannot be null.

**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Allows to adjust the XML formatting, that will be applied to the XML structure, when it is represented in HTML. Default formatting is used and is adjustable. Cannot be null.

**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
