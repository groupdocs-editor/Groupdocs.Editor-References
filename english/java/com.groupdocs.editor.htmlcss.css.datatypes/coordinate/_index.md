---
title: Coordinate
second_title: GroupDocs.Editor for Java API Reference
description: Pair of Length values that represents coordinates of some object
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/coordinate/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Coordinate extends Struct<Coordinate> implements ICssDataType
```

Pair of Length values, that represents coordinates of some object
## Constructors

| Constructor | Description |
| --- | --- |
| [Coordinate()](#Coordinate--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Default coordinate - 0 0 |
## Methods

| Method | Description |
| --- | --- |
| [getXCoordinate()](#getXCoordinate--) |  |
| [getYCoordinate()](#getYCoordinate--) |  |
| [isDefault()](#isDefault--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(Coordinate other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object other)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [op_Equality(Coordinate first, Coordinate second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) | Checks two "Coordinate" instances on equality |
| [op_Inequality(Coordinate first, Coordinate second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) | Checks two "Coordinate" instances on inequality |
| [create(Length xCoordinate, Length yCoordinate)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) |  |
| [CloneTo(Coordinate that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Coordinate obj1, Coordinate obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-) |  |
### Coordinate() {#Coordinate--}
```
public Coordinate()
```


### Default {#Default}
```
public static final Coordinate Default
```


Default coordinate - 0 0

### getXCoordinate() {#getXCoordinate--}
```
public final Length getXCoordinate()
```




**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### getYCoordinate() {#getYCoordinate--}
```
public final Length getYCoordinate()
```




**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
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
### equals(Coordinate other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public final boolean equals(Coordinate other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

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
### op_Equality(Coordinate first, Coordinate second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public static boolean op_Equality(Coordinate first, Coordinate second)
```


Checks two "Coordinate" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |
| second | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

**Returns:**
boolean - 
### op_Inequality(Coordinate first, Coordinate second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public static boolean op_Inequality(Coordinate first, Coordinate second)
```


Checks two "Coordinate" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |
| second | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

**Returns:**
boolean - 
### create(Length xCoordinate, Length yCoordinate) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static Coordinate create(Length xCoordinate, Length yCoordinate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xCoordinate | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| yCoordinate | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

**Returns:**
[Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate)
### CloneTo(Coordinate that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public void CloneTo(Coordinate that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

### Clone() {#Clone--}
```
public Coordinate Clone()
```




**Returns:**
[Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Coordinate obj1, Coordinate obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-com.groupdocs.editor.htmlcss.css.datatypes.Coordinate-}
```
public static boolean equals(Coordinate obj1, Coordinate obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |
| obj2 | [Coordinate](../../com.groupdocs.editor.htmlcss.css.datatypes/coordinate) |  |

**Returns:**
boolean
