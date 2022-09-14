---
title: Polygon
second_title: GroupDocs.Editor for Java API Reference
description:  Holds a list of coordinates where each coordinate is represented as a pair
 of Length arguments.
type: docs
weight: 22
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/polygon/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape)
```
public final class Polygon implements IBasicShape
```

Holds a list of coordinates, where each coordinate is represented as a pair of Length arguments. Each pair argument in the list represents Xi and Yi - the X and Y axis coordinates of the i-th vertex of the polygon.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape\#polygon()
## Constructors

| Constructor | Description |
| --- | --- |
| [Polygon(Coordinate first)](#Polygon-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) |  |
| [Polygon(byte fillingRule, Coordinate first)](#Polygon-byte-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFillingRule()](#getFillingRule--) |  |
| [setFillingRule(byte value)](#setFillingRule-byte-) |  |
| [getCoordinates()](#getCoordinates--) |  |
| [isDefault()](#isDefault--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(Polygon other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(IBasicShape other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-) |  |
| [equals(Object other)](#equals-java.lang.Object-) |  |
| [op_Equality(Polygon first, Polygon second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-) | Checks two "Polygon" instances on equality |
| [op_Inequality(Polygon first, Polygon second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-) | Checks two "Polygon" instances on inequality |
### Polygon(Coordinate first) {#Polygon-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public Polygon(Coordinate first)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

### Polygon(byte fillingRule, Coordinate first) {#Polygon-byte-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public Polygon(byte fillingRule, Coordinate first)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillingRule | byte |  |
| first | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

### getFillingRule() {#getFillingRule--}
```
public final byte getFillingRule()
```




**Returns:**
byte
### setFillingRule(byte value) {#setFillingRule-byte-}
```
public final void setFillingRule(byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCoordinates() {#getCoordinates--}
```
public final NonEmptyCollection<Coordinate> getCoordinates()
```




**Returns:**
[NonEmptyCollection](../../com.groupdocs.editor.htmlcss.tools/nonemptycollection)
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
### equals(Polygon other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-}
```
public final boolean equals(Polygon other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Polygon](../../com.groupdocs.editor.htmlcss.css.datatypes/polygon) |  |

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
### equals(IBasicShape other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-}
```
public final boolean equals(IBasicShape other)
```


In implementing type should check equality between this and other specified basic shapes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape) |  |

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
### op_Equality(Polygon first, Polygon second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-}
```
public static boolean op_Equality(Polygon first, Polygon second)
```


Checks two "Polygon" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Polygon](../../com.groupdocs.editor.htmlcss.css.datatypes/polygon) |  |
| second | [Polygon](../../com.groupdocs.editor.htmlcss.css.datatypes/polygon) |  |

**Returns:**
boolean - 
### op_Inequality(Polygon first, Polygon second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-com.groupdocs.editor.htmlcss.css.datatypes.Polygon-}
```
public static boolean op_Inequality(Polygon first, Polygon second)
```


Checks two "Polygon" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Polygon](../../com.groupdocs.editor.htmlcss.css.datatypes/polygon) |  |
| second | [Polygon](../../com.groupdocs.editor.htmlcss.css.datatypes/polygon) |  |

**Returns:**
boolean - 
