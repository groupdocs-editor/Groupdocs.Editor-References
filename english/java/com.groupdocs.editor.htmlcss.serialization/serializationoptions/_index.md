---
title: SerializationOptions
second_title: GroupDocs.Editor for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.groupdocs.editor.htmlcss.serialization/serializationoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.serialization.ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions)
```
public class SerializationOptions implements ISerializationOptions
```
## Constructors

| Constructor | Description |
| --- | --- |
| [SerializationOptions()](#SerializationOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAllEmbedded()](#getAllEmbedded--) | Creates and returns a new instance of the options class, which is setted to provide an embedded HTML document |
| [getEmbedImagesIntoCss()](#getEmbedImagesIntoCss--) |  |
| [setEmbedImagesIntoCss(boolean value)](#setEmbedImagesIntoCss-boolean-) |  |
| [getRemoteCssImagesCommonPrefixPath()](#getRemoteCssImagesCommonPrefixPath--) |  |
| [setRemoteCssImagesCommonPrefixPath(String value)](#setRemoteCssImagesCommonPrefixPath-java.lang.String-) |  |
| [getEmbedFontsIntoCss()](#getEmbedFontsIntoCss--) |  |
| [setEmbedFontsIntoCss(boolean value)](#setEmbedFontsIntoCss-boolean-) |  |
| [getRemoteFontsCommonPrefixPath()](#getRemoteFontsCommonPrefixPath--) |  |
| [setRemoteFontsCommonPrefixPath(String value)](#setRemoteFontsCommonPrefixPath-java.lang.String-) |  |
| [getEmbedRasterImagesIntoHtml()](#getEmbedRasterImagesIntoHtml--) |  |
| [setEmbedRasterImagesIntoHtml(boolean value)](#setEmbedRasterImagesIntoHtml-boolean-) |  |
| [getRemoteRasterImagesInHtmlCommonPrefixPath()](#getRemoteRasterImagesInHtmlCommonPrefixPath--) |  |
| [setRemoteRasterImagesInHtmlCommonPrefixPath(String value)](#setRemoteRasterImagesInHtmlCommonPrefixPath-java.lang.String-) |  |
| [getEmbedCssIntoHtml()](#getEmbedCssIntoHtml--) |  |
| [setEmbedCssIntoHtml(boolean value)](#setEmbedCssIntoHtml-boolean-) |  |
| [getRemoteCssCommonPrefixPath()](#getRemoteCssCommonPrefixPath--) |  |
| [setRemoteCssCommonPrefixPath(String value)](#setRemoteCssCommonPrefixPath-java.lang.String-) |  |
| [getSvgEmbeddingOptions()](#getSvgEmbeddingOptions--) |  |
| [setSvgEmbeddingOptions(byte value)](#setSvgEmbeddingOptions-byte-) |  |
| [getHtmlAttributeValueDelimiter()](#getHtmlAttributeValueDelimiter--) |  |
| [setHtmlAttributeValueDelimiter(int value)](#setHtmlAttributeValueDelimiter-int-) |  |
| [getCssDeclarationValueDelimiter()](#getCssDeclarationValueDelimiter--) |  |
| [setCssDeclarationValueDelimiter(int value)](#setCssDeclarationValueDelimiter-int-) |  |
| [getHtmlTagCase()](#getHtmlTagCase--) |  |
| [setHtmlTagCase(byte value)](#setHtmlTagCase-byte-) |  |
| [getHumanReadableCss()](#getHumanReadableCss--) |  |
| [setHumanReadableCss(boolean value)](#setHumanReadableCss-boolean-) |  |
| [getHumanReadableHtml()](#getHumanReadableHtml--) |  |
| [setHumanReadableHtml(boolean value)](#setHumanReadableHtml-boolean-) |  |
| [deepClone()](#deepClone--) |  |
### SerializationOptions() {#SerializationOptions--}
```
public SerializationOptions()
```


### getAllEmbedded() {#getAllEmbedded--}
```
public static SerializationOptions getAllEmbedded()
```


Creates and returns a new instance of the options class, which is setted to provide an embedded HTML document

**Returns:**
[SerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/serializationoptions) - 
### getEmbedImagesIntoCss() {#getEmbedImagesIntoCss--}
```
public final boolean getEmbedImagesIntoCss()
```




**Returns:**
boolean
### setEmbedImagesIntoCss(boolean value) {#setEmbedImagesIntoCss-boolean-}
```
public final void setEmbedImagesIntoCss(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoteCssImagesCommonPrefixPath() {#getRemoteCssImagesCommonPrefixPath--}
```
public final String getRemoteCssImagesCommonPrefixPath()
```




**Returns:**
java.lang.String
### setRemoteCssImagesCommonPrefixPath(String value) {#setRemoteCssImagesCommonPrefixPath-java.lang.String-}
```
public final void setRemoteCssImagesCommonPrefixPath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbedFontsIntoCss() {#getEmbedFontsIntoCss--}
```
public final boolean getEmbedFontsIntoCss()
```




**Returns:**
boolean
### setEmbedFontsIntoCss(boolean value) {#setEmbedFontsIntoCss-boolean-}
```
public final void setEmbedFontsIntoCss(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoteFontsCommonPrefixPath() {#getRemoteFontsCommonPrefixPath--}
```
public final String getRemoteFontsCommonPrefixPath()
```




**Returns:**
java.lang.String
### setRemoteFontsCommonPrefixPath(String value) {#setRemoteFontsCommonPrefixPath-java.lang.String-}
```
public final void setRemoteFontsCommonPrefixPath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbedRasterImagesIntoHtml() {#getEmbedRasterImagesIntoHtml--}
```
public final boolean getEmbedRasterImagesIntoHtml()
```




**Returns:**
boolean
### setEmbedRasterImagesIntoHtml(boolean value) {#setEmbedRasterImagesIntoHtml-boolean-}
```
public final void setEmbedRasterImagesIntoHtml(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoteRasterImagesInHtmlCommonPrefixPath() {#getRemoteRasterImagesInHtmlCommonPrefixPath--}
```
public final String getRemoteRasterImagesInHtmlCommonPrefixPath()
```




**Returns:**
java.lang.String
### setRemoteRasterImagesInHtmlCommonPrefixPath(String value) {#setRemoteRasterImagesInHtmlCommonPrefixPath-java.lang.String-}
```
public final void setRemoteRasterImagesInHtmlCommonPrefixPath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbedCssIntoHtml() {#getEmbedCssIntoHtml--}
```
public final boolean getEmbedCssIntoHtml()
```




**Returns:**
boolean
### setEmbedCssIntoHtml(boolean value) {#setEmbedCssIntoHtml-boolean-}
```
public final void setEmbedCssIntoHtml(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoteCssCommonPrefixPath() {#getRemoteCssCommonPrefixPath--}
```
public final String getRemoteCssCommonPrefixPath()
```




**Returns:**
java.lang.String
### setRemoteCssCommonPrefixPath(String value) {#setRemoteCssCommonPrefixPath-java.lang.String-}
```
public final void setRemoteCssCommonPrefixPath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSvgEmbeddingOptions() {#getSvgEmbeddingOptions--}
```
public final byte getSvgEmbeddingOptions()
```




**Returns:**
byte
### setSvgEmbeddingOptions(byte value) {#setSvgEmbeddingOptions-byte-}
```
public final void setSvgEmbeddingOptions(byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHtmlAttributeValueDelimiter() {#getHtmlAttributeValueDelimiter--}
```
public final int getHtmlAttributeValueDelimiter()
```


Defines a type of the quote mark (single ' or double "), which will be used for enclosing values in HTML attributes

**Returns:**
int
### setHtmlAttributeValueDelimiter(int value) {#setHtmlAttributeValueDelimiter-int-}
```
public final void setHtmlAttributeValueDelimiter(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCssDeclarationValueDelimiter() {#getCssDeclarationValueDelimiter--}
```
public final int getCssDeclarationValueDelimiter()
```


Defines a type of the quote mark (single ' or double "), which will be used for enclosing values in CSS declarations

**Returns:**
int
### setCssDeclarationValueDelimiter(int value) {#setCssDeclarationValueDelimiter-int-}
```
public final void setCssDeclarationValueDelimiter(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHtmlTagCase() {#getHtmlTagCase--}
```
public final byte getHtmlTagCase()
```


Defines a case of the HTML tag names: ALL-CAPITAL, all-lower, or First capital.

**Returns:**
byte
### setHtmlTagCase(byte value) {#setHtmlTagCase-byte-}
```
public final void setHtmlTagCase(byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHumanReadableCss() {#getHumanReadableCss--}
```
public final boolean getHumanReadableCss()
```


If set, adds line breaks to the resultant CSS string, making it more human-readable

**Returns:**
boolean
### setHumanReadableCss(boolean value) {#setHumanReadableCss-boolean-}
```
public final void setHumanReadableCss(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHumanReadableHtml() {#getHumanReadableHtml--}
```
public final boolean getHumanReadableHtml()
```


If set, adds line breaks and tab indents to the resultant HTML string, making it more human-readable and tree-like

**Returns:**
boolean
### setHumanReadableHtml(boolean value) {#setHumanReadableHtml-boolean-}
```
public final void setHumanReadableHtml(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### deepClone() {#deepClone--}
```
public final SerializationOptions deepClone()
```




**Returns:**
[SerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/serializationoptions)
