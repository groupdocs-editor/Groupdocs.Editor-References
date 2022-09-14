---
title: Circle
second_title: GroupDocs.Editor for Java API Reference
description: Defines the circle.
type: docs
weight: 12
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/circle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape)
```
public final class Circle implements IBasicShape
```

Defines the circle. 2nd of 5 basic-shape functions.
## Constructors

| Constructor | Description |
| --- | --- |
| [Circle()](#Circle--) | Creates a default instance of Circle, without position and with zero radius |
## Methods

| Method | Description |
| --- | --- |
| [getShapeRadius()](#getShapeRadius--) |  |
| [setShapeRadius(Length value)](#setShapeRadius-com.groupdocs.editor.htmlcss.css.datatypes.Length-) |  |
| [getPosition()](#getPosition--) |  |
| [setPosition(Position value)](#setPosition-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
| [isDefault()](#isDefault--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(Circle other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Circle-) | Defines whether this Circle is equal to the specified |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(IBasicShape other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [op_Equality(Circle first, Circle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Circle-com.groupdocs.editor.htmlcss.css.datatypes.Circle-) | Checks two "Circle" instances on equality |
| [op_Inequality(Circle first, Circle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Circle-com.groupdocs.editor.htmlcss.css.datatypes.Circle-) | Checks two "Circle" instances on inequality |
| [create(Length shapeRadius, Position position)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
### Circle() {#Circle--}
```
public Circle()
```


Creates a default instance of Circle, without position and with zero radius

### getShapeRadius() {#getShapeRadius--}
```
public final Length getShapeRadius()
```




**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setShapeRadius(Length value) {#setShapeRadius-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setShapeRadius(Length value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```




**Returns:**
[Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position)
### setPosition(Position value) {#setPosition-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public final void setPosition(Position value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

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
### equals(Circle other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Circle-}
```
public final boolean equals(Circle other)
```


Defines whether this Circle is equal to the specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Circle](../../com.groupdocs.editor.htmlcss.css.datatypes/circle) |  |

**Returns:**
boolean - 
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
### op_Equality(Circle first, Circle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Circle-com.groupdocs.editor.htmlcss.css.datatypes.Circle-}
```
public static boolean op_Equality(Circle first, Circle second)
```


Checks two "Circle" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Circle](../../com.groupdocs.editor.htmlcss.css.datatypes/circle) |  |
| second | [Circle](../../com.groupdocs.editor.htmlcss.css.datatypes/circle) |  |

**Returns:**
boolean - 
### op_Inequality(Circle first, Circle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Circle-com.groupdocs.editor.htmlcss.css.datatypes.Circle-}
```
public static boolean op_Inequality(Circle first, Circle second)
```


Checks two "Circle" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Circle](../../com.groupdocs.editor.htmlcss.css.datatypes/circle) |  |
| second | [Circle](../../com.groupdocs.editor.htmlcss.css.datatypes/circle) |  |

**Returns:**
boolean - 
### create(Length shapeRadius, Position position) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public static Circle create(Length shapeRadius, Position position)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeRadius | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| position | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

**Returns:**
[Circle](../../com.groupdocs.editor.htmlcss.css.datatypes/circle)
