---
title: ArgbColor
second_title: GroupDocs.Editor for Java API Reference
description: Represents one color value in ARGB format with converters and serializers
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Represents one color value in ARGB format with converters and serializers

--------------------

This type is designed to be useful for (but not limited to) CSS operations. See more: https://developer.mozilla.org/en-US/docs/Web/CSS/color\_value
## Constructors

| Constructor | Description |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Creates one [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value from specified Red, Green, Blue, and Alpha channels |
| [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Creates one [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value from specified Red, Green, Blue channels, while Alpha channel is fully opaque |
| [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Creates a fully opaque (A=255) color from single value, which will be applied to all channels |
| [fromColor(Color color)](#fromColor-java.awt.Color-) | Creates one [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value from specified [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) |
| [getValue()](#getValue--) | Gets the Int32 value of the color. |
| [getA()](#getA--) | Gets the alpha part of the color. |
| [getAlpha()](#getAlpha--) | Gets the alpha part of the color in percent (0..1). |
| [getR()](#getR--) | Gets the red part of the color. |
| [getG()](#getG--) | Gets the green part of the color. |
| [getB()](#getB--) | Gets the blue part of the color. |
| [isEmpty()](#isEmpty--) | Uninitialized color - all 4 channels are set to 0. |
| [isDefault()](#isDefault--) | Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is default (Transparent) - all 4 channels are set to 0 |
| [isFullyTransparent()](#isFullyTransparent--) | Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is fully transparent - its Alpha channel has the min (0) value, so other R, G, and B channels has no visible effect. |
| [isTranslucent()](#isTranslucent--) | Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is translucent (not fully transparent, but also not fully opaque) |
| [isFullyOpaque()](#isFullyOpaque--) | Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is fully opaque, without transparency (its Alpha channel has max value) |
| [toSystemColor()](#toSystemColor--) | Converts a value of this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance and returns it |
| [toRGBA()](#toRGBA--) | Serializes this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the 'rgba' CSS function notation |
| [toRGB()](#toRGB--) | Serializes this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the 'rgb' CSS function notation |
| [serializeDefault()](#serializeDefault--) | Serializes this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the most appropriate CSS function notation depending on translucency |
| [toString()](#toString--) | Same as \#serializeDefault.serializeDefault |
| [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Compares two colors and returns a boolean indicating if the two do match. |
| [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Compares two colors and returns a boolean indicating if the two do not match. |
| [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Checks two [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) colors for equality |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Checks two [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) colors for equality |
| [equals(Object other)](#equals-java.lang.Object-) | Tests if another object is equal to this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance. |
| [hashCode()](#hashCode--) | Returns a hash code that defines the current color. |
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Creates one [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value from specified Red, Green, Blue, and Alpha channels

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int | Red channel value |
| green | int | Green channel value |
| blue | int | Blue channel value |
| alpha | int | Alpha channel value |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Creates one [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value from specified Red, Green, Blue channels, while Alpha channel is fully opaque

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int | Red channel value |
| green | int | Green channel value |
| blue | int | Blue channel value |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value
### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Creates a fully opaque (A=255) color from single value, which will be applied to all channels

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | A byte value, same for Red, Green, and Blue channels |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance
### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Creates one [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value from specified [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
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
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is default (Transparent) - all 4 channels are set to 0

**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is fully transparent - its Alpha channel has the min (0) value, so other R, G, and B channels has no visible effect.

**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is translucent (not fully transparent, but also not fully opaque)

**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Indicates whether this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance is fully opaque, without transparency (its Alpha channel has max value)

**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Converts a value of this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance and returns it

**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance
### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serializes this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the 'rgba' CSS function notation

**Returns:**
java.lang.String - A string with 'rgba(r, g, b, a)' format
### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serializes this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the 'rgb' CSS function notation

**Returns:**
java.lang.String - A string with 'rgb(r, g, b)' format
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serializes this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance to the most appropriate CSS function notation depending on translucency

**Returns:**
java.lang.String - A string with 'rgba(r, g, b, a)' or 'rgb(r, g, b)' format
### toString() {#toString--}
```
public String toString()
```


Same as \#serializeDefault.serializeDefault

**Returns:**
java.lang.String - Same return value as in \#serializeDefault.serializeDefault
### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Compares two colors and returns a boolean indicating if the two do match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | The first color to use. |
| right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | The second color to use. |

**Returns:**
boolean - True if both colors are equal, otherwise false.
### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Compares two colors and returns a boolean indicating if the two do not match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | The first color to use. |
| right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | The second color to use. |

**Returns:**
boolean - True if both colors are not equal, otherwise false.
### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Checks two [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) colors for equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | The other [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) color |

**Returns:**
boolean - True if both colors or equal, otherwise false.
### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Checks two [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) colors for equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | The other [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) color, casted to the ICssDataType |

**Returns:**
boolean - True if both colors or equal, otherwise false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Tests if another object is equal to this [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance.

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
