---
title: Angle
second_title: GroupDocs.Editor for Java API Reference
description: Represents one angle with numeric value and measurement unit.
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/angle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Angle extends Struct<Angle> implements ICssDataType
```

Represents one angle with numeric value and measurement unit. Stores direction - can be clockwise (positive number) or counter-clockwise (negative number). Can store multiple turns. Default value is unitless zero. Immutable struct.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/angle
## Constructors

| Constructor | Description |
| --- | --- |
| [Angle()](#Angle--) |  |
## Fields

| Field | Description |
| --- | --- |
| [UnitlessZero](#UnitlessZero) | Default zero unitless angle |
## Methods

| Method | Description |
| --- | --- |
| [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Tries to parse specified unit name and return corresponding value of a Unit enum. |
| [isDefault()](#isDefault--) | Indicates whether this Angle instance is default - it is a unitless zero angle |
| [getMeasurementUnit()](#getMeasurementUnit--) | Returns measurement unit of this angle |
| [isInteger()](#isInteger--) | Indicates whether the numeric value of this angle instance was originally specified and stored as an integer (INT32) number |
| [isFloat()](#isFloat--) | Indicates whether the numeric value of this angle instance was originally specified and stored as a float (FP32) number |
| [getFloatValue()](#getFloatValue--) | Returns a float numeric value of the angle instance. |
| [getIntegerValue()](#getIntegerValue--) | Returns an integer numeric value of this angle instance, if it is internally stored as an integer, or throws an exception, if it was originally stored as a float number. |
| [isZero()](#isZero--) | Determines whether the numeric value of this angle is a zero number |
| [serializeDefault()](#serializeDefault--) | Returns a string representation of this angle, with its original value and unit |
| [toNewUnit(byte newUnit)](#toNewUnit-byte-) | Converts this angle to other specified unit type (with appropriate numeric value conversion) and returns as a new instance |
| [isRight()](#isRight--) |  |
| [isStraight()](#isStraight--) |  |
| [isTripleQuarters()](#isTripleQuarters--) |  |
| [isFull()](#isFull--) |  |
| [op_Equality(Angle first, Angle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Angle-com.groupdocs.editor.htmlcss.css.datatypes.Angle-) | Checks two "Angle" instances on equality |
| [op_Inequality(Angle first, Angle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Angle-com.groupdocs.editor.htmlcss.css.datatypes.Angle-) | Checks two "Angle" instances on inequality |
| [equals(Angle other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Angle-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object other)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) | Calculates and returns a hash-code of this Angle instance by combining hash-codes of the value and unit type |
| [create(int value, byte unit)](#create-int-byte-) |  |
| [create(float value, byte unit)](#create-float-byte-) |  |
| [create(CssNumber value, byte unit)](#create-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-byte-) |  |
| [tryParse(String input, Angle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Angle---) | Tries to parse a specified string as an Angle value, including its numeric value and unit name |
| [CloneTo(Angle that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Angle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Angle obj1, Angle obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Angle-com.groupdocs.editor.htmlcss.css.datatypes.Angle-) |  |
### Angle() {#Angle--}
```
public Angle()
```


### UnitlessZero {#UnitlessZero}
```
public static final Angle UnitlessZero
```


Default zero unitless angle

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static byte getUnitFromName(String unitName)
```


Tries to parse specified unit name and return corresponding value of a Unit enum. Returns Unit.Unitless if cannot find appropriate unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unitName | java.lang.String | String, that represents a unit name |

**Returns:**
byte - Value of Unit enum in any case, Unit.Unitless when cannot find appropriate unit
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this Angle instance is default - it is a unitless zero angle

**Returns:**
boolean
### getMeasurementUnit() {#getMeasurementUnit--}
```
public final byte getMeasurementUnit()
```


Returns measurement unit of this angle

**Returns:**
byte
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Indicates whether the numeric value of this angle instance was originally specified and stored as an integer (INT32) number

**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Indicates whether the numeric value of this angle instance was originally specified and stored as a float (FP32) number

**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Returns a float numeric value of the angle instance. Never throws an exception - converts Integer value to Float if necessary.

**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Returns an integer numeric value of this angle instance, if it is internally stored as an integer, or throws an exception, if it was originally stored as a float number.

**Returns:**
int
### isZero() {#isZero--}
```
public final boolean isZero()
```


Determines whether the numeric value of this angle is a zero number

**Returns:**
boolean
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Returns a string representation of this angle, with its original value and unit

**Returns:**
java.lang.String - 
### toNewUnit(byte newUnit) {#toNewUnit-byte-}
```
public final Angle toNewUnit(byte newUnit)
```


Converts this angle to other specified unit type (with appropriate numeric value conversion) and returns as a new instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newUnit | byte |  |

**Returns:**
[Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) - 
### isRight() {#isRight--}
```
public final boolean isRight()
```




**Returns:**
boolean
### isStraight() {#isStraight--}
```
public final boolean isStraight()
```




**Returns:**
boolean
### isTripleQuarters() {#isTripleQuarters--}
```
public final boolean isTripleQuarters()
```




**Returns:**
boolean
### isFull() {#isFull--}
```
public final boolean isFull()
```




**Returns:**
boolean
### op_Equality(Angle first, Angle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Angle-com.groupdocs.editor.htmlcss.css.datatypes.Angle-}
```
public static boolean op_Equality(Angle first, Angle second)
```


Checks two "Angle" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |
| second | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |

**Returns:**
boolean - 
### op_Inequality(Angle first, Angle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Angle-com.groupdocs.editor.htmlcss.css.datatypes.Angle-}
```
public static boolean op_Inequality(Angle first, Angle second)
```


Checks two "Angle" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |
| second | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |

**Returns:**
boolean - 
### equals(Angle other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Angle-}
```
public final boolean equals(Angle other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |

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


Calculates and returns a hash-code of this Angle instance by combining hash-codes of the value and unit type

**Returns:**
int - Integer number
### create(int value, byte unit) {#create-int-byte-}
```
public static Angle create(int value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
| unit | byte |  |

**Returns:**
[Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle)
### create(float value, byte unit) {#create-float-byte-}
```
public static Angle create(float value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
| unit | byte |  |

**Returns:**
[Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle)
### create(CssNumber value, byte unit) {#create-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-byte-}
```
public static Angle create(CssNumber value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber) |  |
| unit | byte |  |

**Returns:**
[Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle)
### tryParse(String input, Angle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Angle---}
```
public static boolean tryParse(String input, Angle[] result)
```


Tries to parse a specified string as an Angle value, including its numeric value and unit name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String | Input string, that should be parsed |
| result | com.groupdocs.editor.htmlcss.css.datatypes.Angle[] | Output parameter, that contains a result of parsing. If parsing is unsuccessful, contains a default Angle value \\u2014 a unitless zero angle. |

**Returns:**
boolean - True if parsing is successful, false if unsuccessful
### CloneTo(Angle that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Angle-}
```
public void CloneTo(Angle that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |

### Clone() {#Clone--}
```
public Angle Clone()
```




**Returns:**
[Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Angle obj1, Angle obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Angle-com.groupdocs.editor.htmlcss.css.datatypes.Angle-}
```
public static boolean equals(Angle obj1, Angle obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |
| obj2 | [Angle](../../com.groupdocs.editor.htmlcss.css.datatypes/angle) |  |

**Returns:**
boolean
