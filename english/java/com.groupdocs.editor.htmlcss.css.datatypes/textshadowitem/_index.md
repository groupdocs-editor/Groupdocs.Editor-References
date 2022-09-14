---
title: TextShadowItem
second_title: GroupDocs.Editor for Java API Reference
description:  Represents a single text-shadow value.
type: docs
weight: 27
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class TextShadowItem extends Struct<TextShadowItem> implements ICssDataType
```

Represents a single text-shadow value. Immutable struct, CSS data type.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow\#Values
## Constructors

| Constructor | Description |
| --- | --- |
| [TextShadowItem()](#TextShadowItem--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isDefault()](#isDefault--) |  |
| [hasBlurRadius()](#hasBlurRadius--) |  |
| [hasColor()](#hasColor--) |  |
| [getOffsetX()](#getOffsetX--) | offset-x - the required Length value, specifies the horizontal shadow's distance from the text. |
| [getOffsetY()](#getOffsetY--) | offset-y - the required Length value, specifies the vertical shadow's distance from the text. |
| [getBlurRadius()](#getBlurRadius--) | Optional length value. |
| [getColor()](#getColor--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(TextShadowItem other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object other)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) | \`\`\`  \`\`\` |
| [op_Equality(TextShadowItem first, TextShadowItem second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-) | Checks two "TextShadowItem" instances on equality |
| [op_Inequality(TextShadowItem first, TextShadowItem second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-) | Checks two "TextShadowItem" instances on inequality |
| [create(Length offsetX, Length offsetY)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) |  |
| [create(Length offsetX, Length offsetY, Length blurRadius)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) |  |
| [create(Length offsetX, Length offsetY, ColorValue color)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) |  |
| [create(Length offsetX, Length offsetY, Length blurRadius, ColorValue color)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) |  |
| [CloneTo(TextShadowItem that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(TextShadowItem obj1, TextShadowItem obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-) |  |
### TextShadowItem() {#TextShadowItem--}
```
public TextShadowItem()
```


### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Should define whether the current value of the data type is the default value for this specific data type or not

**Returns:**
boolean
### hasBlurRadius() {#hasBlurRadius--}
```
public final boolean hasBlurRadius()
```




**Returns:**
boolean
### hasColor() {#hasColor--}
```
public final boolean hasColor()
```




**Returns:**
boolean
### getOffsetX() {#getOffsetX--}
```
public final Length getOffsetX()
```


offset-x - the required Length value, specifies the horizontal shadow's distance from the text. Negative values are allowed. Percentage and unitless non-zero are prohibited. By default is unitless zero.

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getOffsetY() {#getOffsetY--}
```
public final Length getOffsetY()
```


offset-y - the required Length value, specifies the vertical shadow's distance from the text. Negative values are allowed. Percentage and unitless non-zero are prohibited. By default is unitless zero.

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getBlurRadius() {#getBlurRadius--}
```
public final Length getBlurRadius()
```


Optional length value. The higher the value, the bigger the blur; the shadow becomes wider and lighter. Negative values are prohibited. Percentage and unitless non-zero are prohibited. By default is unitless zero.

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getColor() {#getColor--}
```
public final ColorValue getColor()
```




**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue)
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Should return a default string representation of the current value of the data type

**Returns:**
java.lang.String
### equals(TextShadowItem other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-}
```
public final boolean equals(TextShadowItem other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |

**Returns:**
boolean
### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) |  |

**Returns:**
boolean
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


\`\`\`  \`\`\`

**Returns:**
int
### op_Equality(TextShadowItem first, TextShadowItem second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-}
```
public static boolean op_Equality(TextShadowItem first, TextShadowItem second)
```


Checks two "TextShadowItem" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |
| second | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |

**Returns:**
boolean - 
### op_Inequality(TextShadowItem first, TextShadowItem second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-}
```
public static boolean op_Inequality(TextShadowItem first, TextShadowItem second)
```


Checks two "TextShadowItem" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |
| second | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |

**Returns:**
boolean - 
### create(Length offsetX, Length offsetY) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static TextShadowItem create(Length offsetX, Length offsetY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| offsetY | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

**Returns:**
[TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem)
### create(Length offsetX, Length offsetY, Length blurRadius) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static TextShadowItem create(Length offsetX, Length offsetY, Length blurRadius)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| offsetY | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| blurRadius | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

**Returns:**
[TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem)
### create(Length offsetX, Length offsetY, ColorValue color) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public static TextShadowItem create(Length offsetX, Length offsetY, ColorValue color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| offsetY | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| color | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) |  |

**Returns:**
[TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem)
### create(Length offsetX, Length offsetY, Length blurRadius, ColorValue color) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public static TextShadowItem create(Length offsetX, Length offsetY, Length blurRadius, ColorValue color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| offsetY | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| blurRadius | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| color | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) |  |

**Returns:**
[TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem)
### CloneTo(TextShadowItem that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-}
```
public void CloneTo(TextShadowItem that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |

### Clone() {#Clone--}
```
public TextShadowItem Clone()
```




**Returns:**
[TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(TextShadowItem obj1, TextShadowItem obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.TextShadowItem-}
```
public static boolean equals(TextShadowItem obj1, TextShadowItem obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |
| obj2 | [TextShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/textshadowitem) |  |

**Returns:**
boolean
