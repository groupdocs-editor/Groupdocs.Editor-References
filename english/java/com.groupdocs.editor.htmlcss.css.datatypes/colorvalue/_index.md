---
title: ColorValue
second_title: GroupDocs.Editor for Java API Reference
description:  Represents CSS color value with converters and serializers
type: docs
weight: 13
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/colorvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ColorValue extends Struct<ColorValue> implements ICssDataType
```

Represents CSS color value with converters and serializers

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/color\_value
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorValue()](#ColorValue--) |  |
## Methods

| Method | Description |
| --- | --- |
| [fromColor(Color color)](#fromColor-java.awt.Color-) |  |
| [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) |  |
| [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) |  |
| [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Creates a fully opaque (A=255) color from single value, which will be applied to all channels |
| [getValue()](#getValue--) | Gets the Int32 value of the color. |
| [getA()](#getA--) | Gets the alpha part of the color. |
| [getAlpha()](#getAlpha--) | Gets the alpha part of the color in percent (0..1). |
| [getR()](#getR--) | Gets the red part of the color. |
| [getG()](#getG--) | Gets the green part of the color. |
| [getB()](#getB--) | Gets the blue part of the color. |
| [isEmpty()](#isEmpty--) | Uninitialized color - all 4 channels are set to 0. |
| [isGrey()](#isGrey--) |  |
| [isDefault()](#isDefault--) | Uninitialized color - all 4 channels are set to 0. |
| [isFullyTransparent()](#isFullyTransparent--) |  |
| [isTranslucent()](#isTranslucent--) |  |
| [isFullyOpaque()](#isFullyOpaque--) |  |
| [toSystemColor()](#toSystemColor--) |  |
| [toRGBA()](#toRGBA--) |  |
| [toRGB()](#toRGB--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [toString()](#toString--) |  |
| [op_Equality(ColorValue left, ColorValue right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) | Compares two colors and returns a boolean indicating if the two do match. |
| [op_Inequality(ColorValue left, ColorValue right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) | Compares two colors and returns a boolean indicating if the two do not match. |
| [equals(ColorValue other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) | Checks two colors for equality. |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object other)](#equals-java.lang.Object-) | Tests if another object is equal to this object. |
| [hashCode()](#hashCode--) | Returns a hash code that defines the current color. |
| [CloneTo(ColorValue that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(ColorValue obj1, ColorValue obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-) |  |
### ColorValue() {#ColorValue--}
```
public ColorValue()
```


### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ColorValue fromColor(Color color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color |  |

**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue)
### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ColorValue fromRgba(int red, int green, int blue, int alpha)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int |  |
| green | int |  |
| blue | int |  |
| alpha | int |  |

**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue)
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ColorValue fromRgb(int red, int green, int blue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int |  |
| green | int |  |
| blue | int |  |

**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue)
### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ColorValue fromSingleValueRgb(byte value)
```


Creates a fully opaque (A=255) color from single value, which will be applied to all channels

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Gets the Int32 value of the color.

**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Gets the alpha part of the color.

**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Gets the alpha part of the color in percent (0..1).

**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Gets the red part of the color.

**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Gets the green part of the color.

**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Gets the blue part of the color.

**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Uninitialized color - all 4 channels are set to 0. Same as Default and Transparent.

**Returns:**
boolean
### isGrey() {#isGrey--}
```
public final boolean isGrey()
```




**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Uninitialized color - all 4 channels are set to 0. Same as Empty.

**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```




**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```




**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```




**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final System.Drawing.Color toSystemColor()
```




**Returns:**
[Color](../../com.aspose.ms.system.drawing/color)
### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```




**Returns:**
java.lang.String
### toRGB() {#toRGB--}
```
public final String toRGB()
```




**Returns:**
java.lang.String
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Should return a default string representation of the current value of the data type

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### op_Equality(ColorValue left, ColorValue right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public static boolean op_Equality(ColorValue left, ColorValue right)
```


Compares two colors and returns a boolean indicating if the two do match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) | The first color to use. |
| right | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) | The second color to use. |

**Returns:**
boolean - True if both colors are equal, otherwise false.
### op_Inequality(ColorValue left, ColorValue right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public static boolean op_Inequality(ColorValue left, ColorValue right)
```


Compares two colors and returns a boolean indicating if the two do not match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) | The first color to use. |
| right | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) | The second color to use. |

**Returns:**
boolean - True if both colors are not equal, otherwise false.
### equals(ColorValue other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public final boolean equals(ColorValue other)
```


Checks two colors for equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) | The other color. |

**Returns:**
boolean - True if both colors or equal, otherwise false.
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


Tests if another object is equal to this object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | The object to test with. |

**Returns:**
boolean - True if the two objects are equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code that defines the current color.

**Returns:**
int - The integer value of the hashcode.
### CloneTo(ColorValue that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public void CloneTo(ColorValue that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) |  |

### Clone() {#Clone--}
```
public ColorValue Clone()
```




**Returns:**
[ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(ColorValue obj1, ColorValue obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-com.groupdocs.editor.htmlcss.css.datatypes.ColorValue-}
```
public static boolean equals(ColorValue obj1, ColorValue obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) |  |
| obj2 | [ColorValue](../../com.groupdocs.editor.htmlcss.css.datatypes/colorvalue) |  |

**Returns:**
boolean
