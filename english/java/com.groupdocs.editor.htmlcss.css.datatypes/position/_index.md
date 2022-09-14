---
title: Position
second_title: GroupDocs.Editor for Java API Reference
description: Position CSS data type specifies the position of a object area e.g.
type: docs
weight: 23
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/position/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Position extends Struct<Position> implements ICssDataType
```

Position CSS data type specifies the position of a object area (e.g. background image) inside a positioning area. It is specified with one or two keywords, with optional offsets.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/position\_value https://developer.mozilla.org/en-US/docs/Web/CSS/background-position https://drafts.csswg.org/css-values-3/\#position
## Constructors

| Constructor | Description |
| --- | --- |
| [Position()](#Position--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | 0% 0% - point is located in the left top corner. |
## Methods

| Method | Description |
| --- | --- |
| [isDefault()](#isDefault--) | Determines whether this position is default - left 0% top 0% (0% 0%) |
| [getInversedHorizontalDirection()](#getInversedHorizontalDirection--) | Returns 'true' if direction is from right to left |
| [isInversedVerticalDirection()](#isInversedVerticalDirection--) | Returns 'true' if direction is from bottom to top |
| [getHorizontalDir()](#getHorizontalDir--) |  |
| [getVerticalDir()](#getVerticalDir--) |  |
| [getHorizontalValue()](#getHorizontalValue--) |  |
| [getVerticalValue()](#getVerticalValue--) |  |
| [serializeDefault()](#serializeDefault--) | Returns string value of this position in the "Edge offsets" form (4-value syntax). |
| [toString()](#toString--) | Returns string value of this position in the "Edge offsets" form (4-value syntax). |
| [areEqual(Position first, Position second)](#areEqual-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
| [equals(Position other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [op_Equality(Position first, Position second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-) | Compares two positions and returns a boolean indicating if the two do match. |
| [op_Inequality(Position first, Position second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-) | Compares two positions and returns a boolean indicating if the two dont match. |
| [hashCode()](#hashCode--) | Returns a hashcode for this Position instance, which cannot be changed during its lifetime |
| [create(Integer horizontalDirection, Length horizontalOffset, Byte verticalDirection, Length verticalOffset)](#create-java.lang.Integer-com.groupdocs.editor.htmlcss.css.datatypes.Length-java.lang.Byte-com.groupdocs.editor.htmlcss.css.datatypes.Length-) |  |
| [from2Sides(byte first, byte second)](#from2Sides-byte-byte-) |  |
| [from2SidesWithOffsets(byte firstSide, Length firstOffset, byte secondSide, Length secondOffset)](#from2SidesWithOffsets-byte-com.groupdocs.editor.htmlcss.css.datatypes.Length-byte-com.groupdocs.editor.htmlcss.css.datatypes.Length-) |  |
| [fromCenterAndSide(byte side)](#fromCenterAndSide-byte-) |  |
| [fromKeywords(String horizontal, String vertical)](#fromKeywords-java.lang.String-java.lang.String-) |  |
| [fromKeyword(String oneKeyword)](#fromKeyword-java.lang.String-) |  |
| [CloneTo(Position that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Position obj1, Position obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
### Position() {#Position--}
```
public Position()
```


### Default {#Default}
```
public static final Position Default
```


0% 0% - point is located in the left top corner. Default value. Same as 0 0, left top.

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determines whether this position is default - left 0% top 0% (0% 0%)

**Returns:**
boolean
### getInversedHorizontalDirection() {#getInversedHorizontalDirection--}
```
public final boolean getInversedHorizontalDirection()
```


Returns 'true' if direction is from right to left

**Returns:**
boolean
### isInversedVerticalDirection() {#isInversedVerticalDirection--}
```
public final boolean isInversedVerticalDirection()
```


Returns 'true' if direction is from bottom to top

**Returns:**
boolean
### getHorizontalDir() {#getHorizontalDir--}
```
public final int getHorizontalDir()
```




**Returns:**
int
### getVerticalDir() {#getVerticalDir--}
```
public final byte getVerticalDir()
```




**Returns:**
byte
### getHorizontalValue() {#getHorizontalValue--}
```
public final Length getHorizontalValue()
```




**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getVerticalValue() {#getVerticalValue--}
```
public final Length getVerticalValue()
```




**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Returns string value of this position in the "Edge offsets" form (4-value syntax). Same as 'ToString()'.

**Returns:**
java.lang.String - 
### toString() {#toString--}
```
public String toString()
```


Returns string value of this position in the "Edge offsets" form (4-value syntax). Same as 'SerializeDefault()'.

**Returns:**
java.lang.String - 
### areEqual(Position first, Position second) {#areEqual-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public static boolean areEqual(Position first, Position second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |
| second | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

**Returns:**
boolean
### equals(Position other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public final boolean equals(Position other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### op_Equality(Position first, Position second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public static boolean op_Equality(Position first, Position second)
```


Compares two positions and returns a boolean indicating if the two do match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |
| second | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

**Returns:**
boolean - 
### op_Inequality(Position first, Position second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public static boolean op_Inequality(Position first, Position second)
```


Compares two positions and returns a boolean indicating if the two dont match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |
| second | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

**Returns:**
boolean - 
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hashcode for this Position instance, which cannot be changed during its lifetime

**Returns:**
int - 
### create(Integer horizontalDirection, Length horizontalOffset, Byte verticalDirection, Length verticalOffset) {#create-java.lang.Integer-com.groupdocs.editor.htmlcss.css.datatypes.Length-java.lang.Byte-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static Position create(Integer horizontalDirection, Length horizontalOffset, Byte verticalDirection, Length verticalOffset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| horizontalDirection | java.lang.Integer |  |
| horizontalOffset | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| verticalDirection | java.lang.Byte |  |
| verticalOffset | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### from2Sides(byte first, byte second) {#from2Sides-byte-byte-}
```
public static Position from2Sides(byte first, byte second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | byte |  |
| second | byte |  |

**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### from2SidesWithOffsets(byte firstSide, Length firstOffset, byte secondSide, Length secondOffset) {#from2SidesWithOffsets-byte-com.groupdocs.editor.htmlcss.css.datatypes.Length-byte-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static Position from2SidesWithOffsets(byte firstSide, Length firstOffset, byte secondSide, Length secondOffset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstSide | byte |  |
| firstOffset | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| secondSide | byte |  |
| secondOffset | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### fromCenterAndSide(byte side) {#fromCenterAndSide-byte-}
```
public static Position fromCenterAndSide(byte side)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| side | byte |  |

**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### fromKeywords(String horizontal, String vertical) {#fromKeywords-java.lang.String-java.lang.String-}
```
public static Position fromKeywords(String horizontal, String vertical)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| horizontal | java.lang.String |  |
| vertical | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### fromKeyword(String oneKeyword) {#fromKeyword-java.lang.String-}
```
public static Position fromKeyword(String oneKeyword)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneKeyword | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### CloneTo(Position that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public void CloneTo(Position that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

### Clone() {#Clone--}
```
public Position Clone()
```




**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Position obj1, Position obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Position-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public static boolean equals(Position obj1, Position obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |
| obj2 | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

**Returns:**
boolean
