---
title: ISerializationOptions
second_title: GroupDocs.Editor for Java API Reference
description: Represents a set of all serialization options which are used during serialization process and which specify how exactly will be serialized different things.
type: docs
weight: 18
url: /java/com.groupdocs.editor.htmlcss.serialization/iserializationoptions/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface ISerializationOptions extends System.ICloneable
```

Represents a set of all serialization options, which are used during serialization process and which specify, how exactly will be serialized different things. This options class is common for HTML and CSS.
## Methods

| Method | Description |
| --- | --- |
| [getEmbedImagesIntoCss()](#getEmbedImagesIntoCss--) |  |
| [getRemoteCssImagesCommonPrefixPath()](#getRemoteCssImagesCommonPrefixPath--) |  |
| [getEmbedFontsIntoCss()](#getEmbedFontsIntoCss--) |  |
| [getRemoteFontsCommonPrefixPath()](#getRemoteFontsCommonPrefixPath--) |  |
| [getEmbedRasterImagesIntoHtml()](#getEmbedRasterImagesIntoHtml--) |  |
| [getRemoteRasterImagesInHtmlCommonPrefixPath()](#getRemoteRasterImagesInHtmlCommonPrefixPath--) |  |
| [getEmbedCssIntoHtml()](#getEmbedCssIntoHtml--) |  |
| [getRemoteCssCommonPrefixPath()](#getRemoteCssCommonPrefixPath--) |  |
| [getSvgEmbeddingOptions()](#getSvgEmbeddingOptions--) |  |
| [getHtmlAttributeValueDelimiter()](#getHtmlAttributeValueDelimiter--) | Defines a type of the quote mark (single ' or double "), which will be used for enclosing values in HTML attributes |
| [getCssDeclarationValueDelimiter()](#getCssDeclarationValueDelimiter--) | Defines a type of the quote mark (single ' or double "), which will be used for enclosing values in CSS declarations |
| [getHtmlTagCase()](#getHtmlTagCase--) | Defines a case of the HTML tag names: ALL-CAPITAL, all-lower, or First capital. |
| [getHumanReadableCss()](#getHumanReadableCss--) | If set, adds line breaks to the resultant CSS string, making it more human-readable |
| [getHumanReadableHtml()](#getHumanReadableHtml--) | If set, adds line breaks and tab indents to the resultant HTML string, making it more human-readable and tree-like |
### getEmbedImagesIntoCss() {#getEmbedImagesIntoCss--}
```
public abstract boolean getEmbedImagesIntoCss()
```




**Returns:**
boolean
### getRemoteCssImagesCommonPrefixPath() {#getRemoteCssImagesCommonPrefixPath--}
```
public abstract String getRemoteCssImagesCommonPrefixPath()
```




**Returns:**
java.lang.String
### getEmbedFontsIntoCss() {#getEmbedFontsIntoCss--}
```
public abstract boolean getEmbedFontsIntoCss()
```




**Returns:**
boolean
### getRemoteFontsCommonPrefixPath() {#getRemoteFontsCommonPrefixPath--}
```
public abstract String getRemoteFontsCommonPrefixPath()
```




**Returns:**
java.lang.String
### getEmbedRasterImagesIntoHtml() {#getEmbedRasterImagesIntoHtml--}
```
public abstract boolean getEmbedRasterImagesIntoHtml()
```




**Returns:**
boolean
### getRemoteRasterImagesInHtmlCommonPrefixPath() {#getRemoteRasterImagesInHtmlCommonPrefixPath--}
```
public abstract String getRemoteRasterImagesInHtmlCommonPrefixPath()
```




**Returns:**
java.lang.String
### getEmbedCssIntoHtml() {#getEmbedCssIntoHtml--}
```
public abstract boolean getEmbedCssIntoHtml()
```




**Returns:**
boolean
### getRemoteCssCommonPrefixPath() {#getRemoteCssCommonPrefixPath--}
```
public abstract String getRemoteCssCommonPrefixPath()
```




**Returns:**
java.lang.String
### getSvgEmbeddingOptions() {#getSvgEmbeddingOptions--}
```
public abstract byte getSvgEmbeddingOptions()
```




**Returns:**
byte
### getHtmlAttributeValueDelimiter() {#getHtmlAttributeValueDelimiter--}
```
public abstract int getHtmlAttributeValueDelimiter()
```


Defines a type of the quote mark (single ' or double "), which will be used for enclosing values in HTML attributes

**Returns:**
int
### getCssDeclarationValueDelimiter() {#getCssDeclarationValueDelimiter--}
```
public abstract int getCssDeclarationValueDelimiter()
```


Defines a type of the quote mark (single ' or double "), which will be used for enclosing values in CSS declarations

**Returns:**
int
### getHtmlTagCase() {#getHtmlTagCase--}
```
public abstract byte getHtmlTagCase()
```


Defines a case of the HTML tag names: ALL-CAPITAL, all-lower, or First capital.

**Returns:**
byte
### getHumanReadableCss() {#getHumanReadableCss--}
```
public abstract boolean getHumanReadableCss()
```


If set, adds line breaks to the resultant CSS string, making it more human-readable

**Returns:**
boolean
### getHumanReadableHtml() {#getHumanReadableHtml--}
```
public abstract boolean getHumanReadableHtml()
```


If set, adds line breaks and tab indents to the resultant HTML string, making it more human-readable and tree-like

**Returns:**
boolean
