---
title: BoxShadowItem
second_title: GroupDocs.Editor for Java API Reference
description:  Represents a single box-shadow value.
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class BoxShadowItem implements ICssDataType
```

Represents a single box-shadow value. Immutable struct, CSS data type.
## Constructors

| Constructor | Description |
| --- | --- |
| [BoxShadowItem()](#BoxShadowItem--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isInset()](#isInset--) |  |
| [hasBlurRadius()](#hasBlurRadius--) |  |
| [hasSpreadRadius()](#hasSpreadRadius--) |  |
| [hasColor()](#hasColor--) |  |
| [getOffsetX()](#getOffsetX--) | offset-x specifies the horizontal distance. |
| [getOffsetY()](#getOffsetY--) | offset-y specifies the vertical distance. |
| [getBlurRadius()](#getBlurRadius--) | The larger is this value, the bigger the blur, so the shadow becomes bigger and lighter. |
| [getSpreadRadius()](#getSpreadRadius--) | Positive values will cause the shadow to expand and grow bigger, negative values will cause the shadow to shrink. |
| [getColor()](#getColor--) |  |
| [isDefault()](#isDefault--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(BoxShadowItem other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object other)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [op_Equality(BoxShadowItem first, BoxShadowItem second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-) | Checks two "BoxShadowItem" instances on equality |
| [op_Inequality(BoxShadowItem first, BoxShadowItem second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-) | Checks two "BoxShadowItem" instances on inequality |
| [create(boolean inset, Length offsetX, Length offsetY, Length blurRadius, Length spreadRadius, ColorValue color)](#create-boolean-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) |  |
| [CloneTo(BoxShadowItem that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(BoxShadowItem obj1, BoxShadowItem obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-) |  |
### BoxShadowItem() {#BoxShadowItem--}
```
public BoxShadowItem()
```


### isInset() {#isInset--}
```
public final boolean isInset()
```




**Returns:**
boolean
### hasBlurRadius() {#hasBlurRadius--}
```
public final boolean hasBlurRadius()
```




**Returns:**
boolean
### hasSpreadRadius() {#hasSpreadRadius--}
```
public final boolean hasSpreadRadius()
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


offset-x specifies the horizontal distance. Negative values place the shadow to the left of the element.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow\#Values

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getOffsetY() {#getOffsetY--}
```
public final Length getOffsetY()
```


offset-y specifies the vertical distance. Negative values place the shadow above the element.

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getBlurRadius() {#getBlurRadius--}
```
public final Length getBlurRadius()
```


The larger is this value, the bigger the blur, so the shadow becomes bigger and lighter. Negative values are not allowed. If not specified, it will be 0 (the shadow's edge is sharp).

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow\#%3Cblur-radius%3E

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getSpreadRadius() {#getSpreadRadius--}
```
public final Length getSpreadRadius()
```


Positive values will cause the shadow to expand and grow bigger, negative values will cause the shadow to shrink. If not specified, it will be 0 (the shadow will be the same size as the element).

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow\#%3Cspread-radius%3E

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getColor() {#getColor--}
```
public final ColorValue getColor()
```




**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Should define whether the current value of the data type is the default value for this specific data type or not

**Returns:**
boolean
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Should return a default string representation of the current value of the data type

**Returns:**
java.lang.String
### equals(BoxShadowItem other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-}
```
public final boolean equals(BoxShadowItem other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |

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




**Returns:**
int
### op_Equality(BoxShadowItem first, BoxShadowItem second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-}
```
public static boolean op_Equality(BoxShadowItem first, BoxShadowItem second)
```


Checks two "BoxShadowItem" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |
| second | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |

**Returns:**
boolean - 
### op_Inequality(BoxShadowItem first, BoxShadowItem second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-}
```
public static boolean op_Inequality(BoxShadowItem first, BoxShadowItem second)
```


Checks two "BoxShadowItem" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |
| second | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |

**Returns:**
boolean - 
### create(boolean inset, Length offsetX, Length offsetY, Length blurRadius, Length spreadRadius, ColorValue color) {#create-boolean-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public static BoxShadowItem create(boolean inset, Length offsetX, Length offsetY, Length blurRadius, Length spreadRadius, ColorValue color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inset | boolean |  |
| offsetX | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| offsetY | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| blurRadius | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| spreadRadius | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| color | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) |  |

**Returns:**
[BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem)
### CloneTo(BoxShadowItem that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-}
```
public void CloneTo(BoxShadowItem that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |

### Clone() {#Clone--}
```
public BoxShadowItem Clone()
```




**Returns:**
[BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(BoxShadowItem obj1, BoxShadowItem obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-com.groupdocs.editor.htmlcss.css.datatypes.BoxShadowItem-}
```
public static boolean equals(BoxShadowItem obj1, BoxShadowItem obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |
| obj2 | [BoxShadowItem](../../com.groupdocs.editor.htmlcss.css.datatypes/boxshadowitem) |  |

**Returns:**
boolean
