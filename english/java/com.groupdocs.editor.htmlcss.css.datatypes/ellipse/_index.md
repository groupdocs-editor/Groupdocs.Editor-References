---
title: Ellipse
second_title: GroupDocs.Editor for Java API Reference
description:  Defines the ellipse.
type: docs
weight: 17
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/ellipse/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape)
```
public final class Ellipse implements IBasicShape
```

Defines the ellipse. 3rd of 5 basic-shape functions.
## Constructors

| Constructor | Description |
| --- | --- |
| [Ellipse()](#Ellipse--) | Creates a default instance of Ellipse, without position and radius (empty function) |
## Methods

| Method | Description |
| --- | --- |
| [getRadii()](#getRadii--) |  |
| [setRadii(EllipseRadii value)](#setRadii-com.groupdocs.editor.htmlcss.css.datatypes.EllipseRadii-) |  |
| [getPosition()](#getPosition--) |  |
| [setPosition(Position value)](#setPosition-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
| [isDefault()](#isDefault--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(Ellipse other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(IBasicShape other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-) |  |
| [equals(Object other)](#equals-java.lang.Object-) |  |
| [op_Equality(Ellipse first, Ellipse second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-) | Checks two "Ellipse" instances on equality |
| [op_Inequality(Ellipse first, Ellipse second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-) | Checks two "Ellipse" instances on inequality |
| [create(EllipseRadii radii, Position position)](#create-com.groupdocs.editor.htmlcss.css.datatypes.EllipseRadii-com.groupdocs.editor.htmlcss.css.datatypes.Position-) |  |
### Ellipse() {#Ellipse--}
```
public Ellipse()
```


Creates a default instance of Ellipse, without position and radius (empty function)

### getRadii() {#getRadii--}
```
public final EllipseRadii getRadii()
```




**Returns:**
[EllipseRadii](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipseradii)
### setRadii(EllipseRadii value) {#setRadii-com.groupdocs.editor.htmlcss.css.datatypes.EllipseRadii-}
```
public final void setRadii(EllipseRadii value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EllipseRadii](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipseradii) |  |

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
### equals(Ellipse other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-}
```
public final boolean equals(Ellipse other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Ellipse](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipse) |  |

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
### op_Equality(Ellipse first, Ellipse second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-}
```
public static boolean op_Equality(Ellipse first, Ellipse second)
```


Checks two "Ellipse" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Ellipse](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipse) |  |
| second | [Ellipse](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipse) |  |

**Returns:**
boolean - 
### op_Inequality(Ellipse first, Ellipse second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-com.groupdocs.editor.htmlcss.css.datatypes.Ellipse-}
```
public static boolean op_Inequality(Ellipse first, Ellipse second)
```


Checks two "Ellipse" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Ellipse](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipse) |  |
| second | [Ellipse](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipse) |  |

**Returns:**
boolean - 
### create(EllipseRadii radii, Position position) {#create-com.groupdocs.editor.htmlcss.css.datatypes.EllipseRadii-com.groupdocs.editor.htmlcss.css.datatypes.Position-}
```
public static Ellipse create(EllipseRadii radii, Position position)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| radii | [EllipseRadii](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipseradii) |  |
| position | [Position](../../com.groupdocs.editor.htmlcss.css.datatypes/position) |  |

**Returns:**
[Ellipse](../../com.groupdocs.editor.htmlcss.css.datatypes/ellipse)
