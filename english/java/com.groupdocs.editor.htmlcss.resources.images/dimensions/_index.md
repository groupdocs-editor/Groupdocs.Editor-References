---
title: Dimensions
second_title: GroupDocs.Editor for Java API Reference
description:  Represents the linear dimensions width and height of one raster rectangular
 image in arbitrary unit.
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Represents the linear dimensions (width and height) of one raster rectangular image in arbitrary unit. Immutable struct.
## Constructors

| Constructor | Description |
| --- | --- |
| [Dimensions()](#Dimensions--) |  |
| [Dimensions(int width, int height)](#Dimensions-int-int-) | Creates a new instance from specified width and height |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Returns width of the image |
| [getHeight()](#getHeight--) | Returns height of the image |
| [isSquare()](#isSquare--) | Determines whether specified 'Dimensions' represents square, i.e. |
| [getArea()](#getArea--) | Returns an area (Width x Height) |
| [isEmpty()](#isEmpty--) | Determines whether this "Dimensions" instance is empty and default, i.e. |
| [getAspectRatio()](#getAspectRatio--) | Aspect ratio of this dimensions as width/height |
| [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Creates and returns new "Dimensions" instance, which is proportionally resized from current, based on specified width |
| [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Creates and returns new "Dimensions" instance, which is proportionally resized from current, based on specified height |
| [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Determines whether this instance is equal with specified "Dimensions" instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal with specified uncasted object, which presumably is another "Dimensions" instance |
| [hashCode()](#hashCode--) | Returns a hashcode for this instance, which cannot be changed during its lifetime |
| [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Checks whether two "Dimensions" values are equal, i.e. |
| [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Checks whether two "Dimensions" values are not equal, i.e. |
| [toString()](#toString--) | Returns a string representation of this "Dimensions" |
| [deepClone()](#deepClone--) | Returns a full copy of this instance |
| [getEmpty()](#getEmpty--) | Returns an empty Dimensions instance |
| [fromSize(Dimension size)](#fromSize-java.awt.Dimension-) | Generates and returns a new instance from specified System.Drawing.Size instance |
| [fromSizeInternal(System.Drawing.Size size)](#fromSizeInternal-com.aspose.ms.System.Drawing.Size-) |  |
| [CloneTo(Dimensions that)](#CloneTo-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Dimensions obj1, Dimensions obj2)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) |  |
### Dimensions() {#Dimensions--}
```
public Dimensions()
```




### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Creates a new instance from specified width and height

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Width of image |
| height | int | Height of image |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Returns width of the image

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Returns height of the image

**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Determines whether specified 'Dimensions' represents square, i.e. if width is equal to height

**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Returns an area (Width x Height)

**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Determines whether this "Dimensions" instance is empty and default, i.e. it doesn't store correct width and height

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Aspect ratio of this dimensions as width/height

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Creates and returns new "Dimensions" instance, which is proportionally resized from current, based on specified width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetWidth | int | New target width, that will be present in resultant Dimension |

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height
### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Creates and returns new "Dimensions" instance, which is proportionally resized from current, based on specified height

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetHeight | int | New target height, that will be present in resultant Dimension |

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width
### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Determines whether this instance is equal with specified "Dimensions" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Other "Dimensions" instance to check on equality |

**Returns:**
boolean - True if are equal, false if are not equal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal with specified uncasted object, which presumably is another "Dimensions" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other object, that is presumably of "Dimensions" type, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are not equal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hashcode for this instance, which cannot be changed during its lifetime

**Returns:**
int - Immutable (for this instance) hash-code as signed 4-byte integer
### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Checks whether two "Dimensions" values are equal, i.e. they have equal width and height, or both are empty

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | First instance to check |
| second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Second instance to check |

**Returns:**
boolean - True if are equal, false if are not equal
### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Checks whether two "Dimensions" values are not equal, i.e. their corresponding width and/or height are different

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | First instance to check |
| second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Second instance to check |

**Returns:**
boolean - True if are unequal, false if are equal
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of this "Dimensions"

--------------------

> ```
> W640×H480
> ```

**Returns:**
java.lang.String - String instance, that contains a width and height in W:(width)×H:(height) format
### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Returns a full copy of this instance

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one
### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Returns an empty Dimensions instance

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### fromSize(Dimension size) {#fromSize-java.awt.Dimension-}
```
public static Dimensions fromSize(Dimension size)
```


Generates and returns a new instance from specified System.Drawing.Size instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | java.awt.Dimension | Any instance of System.Drawing.Size |

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that has the same width and height, as the specified
### fromSizeInternal(System.Drawing.Size size) {#fromSizeInternal-com.aspose.ms.System.Drawing.Size-}
```
public static Dimensions fromSizeInternal(System.Drawing.Size size)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | com.aspose.ms.System.Drawing.Size |  |

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### CloneTo(Dimensions that) {#CloneTo-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public void CloneTo(Dimensions that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) |  |

### Clone() {#Clone--}
```
public Dimensions Clone()
```




**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Dimensions obj1, Dimensions obj2) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean equals(Dimensions obj1, Dimensions obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) |  |
| obj2 | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) |  |

**Returns:**
boolean
