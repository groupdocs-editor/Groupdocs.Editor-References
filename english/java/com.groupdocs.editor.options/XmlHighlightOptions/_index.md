---
title: XmlHighlightOptions
second_title: GroupDocs.Editor for Java API Reference
description: Contains options that allow to customize the XML highlighting during XML-to-HTML conversion
type: docs
weight: 49
url: /java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlHighlightOptions implements IEditOptions
```

Contains options, that allow to customize the XML highlighting during XML-to-HTML conversion
## Methods

| Method | Description |
| --- | --- |
| [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Responsible for representing the font of XML tags (angle brackets with tag names) |
| [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Responsible for representing the font of attribute names |
| [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Responsible for representing the font of attribute values |
| [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Responsible for representing the font of inner-tag text |
| [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Responsible for representing the font of HTML comments (including pair of opening and closing tags) |
| [getCDataFontSettings()](#getCDataFontSettings--) | Responsible for representing the font of CDATA sections (including pair of opening and closing tags) |
| [isDefault()](#isDefault--) | Determines whether this XML Highlight options object has a default font settings |
| [resetToDefault()](#resetToDefault--) | Resets the current font settings to their default values |
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Responsible for representing the font of XML tags (angle brackets with tag names)

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Responsible for representing the font of attribute names

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Responsible for representing the font of attribute values

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Responsible for representing the font of inner-tag text

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Responsible for representing the font of HTML comments (including pair of opening and closing tags)

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Responsible for representing the font of CDATA sections (including pair of opening and closing tags)

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determines whether this XML Highlight options object has a default font settings

**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Resets the current font settings to their default values

