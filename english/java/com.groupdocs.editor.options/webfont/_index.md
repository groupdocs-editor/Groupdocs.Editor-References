---
title: WebFont
second_title: GroupDocs.Editor for Java API Reference
description: Represents a font settings for the web
type: docs
weight: 38
url: /java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Represents a font settings for the web
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Font color in ARGB32 format |
| [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Font color in ARGB32 format |
| [getWeight()](#getWeight--) | Sets the weight (or boldness) of the font |
| [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Sets the weight (or boldness) of the font |
| [getStyle()](#getStyle--) | Sets whether a font should be styled with a normal, italic, or oblique face from its font-family. |
| [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Sets whether a font should be styled with a normal, italic, or oblique face from its font-family. |
| [getLine()](#getLine--) | Sets a line or combination of lines, applied to the text |
| [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Sets a line or combination of lines, applied to the text |
| [getSize()](#getSize--) | Sets the size of the font in absolute or relative units |
| [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Sets the size of the font in absolute or relative units |
| [getName()](#getName--) | Sets the font name. |
| [setName(String value)](#setName-java.lang.String-) | Sets the font name. |
| [deepClone()](#deepClone--) | Creates and returns a full deep copy of this [WebFont](../../com.groupdocs.editor.options/webfont) instance |
| [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Determines whether this instance of WebFont is equal to specified |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance of WebFont is equal to specified uncasted object |
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Font color in ARGB32 format

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Font color in ARGB32 format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Sets the weight (or boldness) of the font

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Sets the weight (or boldness) of the font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Sets whether a font should be styled with a normal, italic, or oblique face from its font-family.

**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Sets whether a font should be styled with a normal, italic, or oblique face from its font-family.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Sets a line or combination of lines, applied to the text

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Sets a line or combination of lines, applied to the text

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Sets the size of the font in absolute or relative units

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Sets the size of the font in absolute or relative units

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Sets the font name. If not specified, the default font will be used

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the font name. If not specified, the default font will be used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Creates and returns a full deep copy of this [WebFont](../../com.groupdocs.editor.options/webfont) instance

**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one
### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Determines whether this instance of WebFont is equal to specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [WebFont](../../com.groupdocs.editor.options/webfont) | Another WebFont to check equality, may be NULL |

**Returns:**
boolean - true if equal, false if unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance of WebFont is equal to specified uncasted object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Object, that is expected to be a [WebFont](../../com.groupdocs.editor.options/webfont) instance |

**Returns:**
boolean - true if equal, false if unequal
