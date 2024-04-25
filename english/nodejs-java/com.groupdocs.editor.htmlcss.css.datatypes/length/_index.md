---
title: Length
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents a CSS length value in any supportable unit including percentage    and unitless type.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Represents a CSS length value in any supportable unit, including percentage and unitless type. Values may be integer or float, negative, zero and positive. Immutable structure.

--------------------

This type covers the next CSS data types:

https://developer.mozilla.org/en-US/docs/Web/CSS/length

https://developer.mozilla.org/en-US/docs/Web/CSS/percentage
## Constructors

| Constructor | Description |
| --- | --- |
| [Length()](#Length--) |  |
## Fields

| Field | Description |
| --- | --- |
| [UnitlessZero](#UnitlessZero) | Unitless integer zero - default value, the same as default parameterless constructor |
| [OneHundredPercents](#OneHundredPercents) | 100% |
| [FiftyPercents](#FiftyPercents) | 50% |
| [ZeroPercents](#ZeroPercents) | 0% |
## Methods

| Method | Description |
| --- | --- |
| [fromValueWithUnit(float value, byte unit)](#fromValueWithUnit-float-byte-) | Creates and returns an instance of Length type by specified float number and unit |
| [fromValueWithUnit(double value, byte unit)](#fromValueWithUnit-double-byte-) | Creates and returns an instance of Length type by specified double number and unit |
| [fromValueWithUnit(int value, byte unit)](#fromValueWithUnit-int-byte-) | Creates and returns an instance of Length type by specified integer number and unit |
| [isUnitlessZero()](#isUnitlessZero--) | Determines whether this instance is a unitless zero or not. |
| [isDefault()](#isDefault--) | Indicates whether this Length instance has a default value \\u2014 unitless zero. |
| [getUnitType()](#getUnitType--) | Returns a unit type of this Length instance. |
| [isInteger()](#isInteger--) | Indicates whether the numeric value of this Length instance was originally specified and stored as an integer (INT32) number |
| [isFloat()](#isFloat--) | Indicates whether the numeric value of this Length instance was originally specified and stored as a float (FP32) number |
| [getFloatValue()](#getFloatValue--) | Returns a float numeric value of the Length instance. |
| [getIntegerValue()](#getIntegerValue--) | Returns an integer numeric value of this Length instance, if it is internally stored as an integer, or throws an exception, if it was originally stored as a float number. |
| [isAbsolute()](#isAbsolute--) | Gets if the length is given in absolute units. |
| [isRelative()](#isRelative--) | Gets if the length is given in relative units. |
| [isZero()](#isZero--) | Determines whether the numeric value of this length is a zero number |
| [isNegative()](#isNegative--) | Determines whether the numeric value of this length is a negative number |
| [isPositive()](#isPositive--) | Determines whether the numeric value of this length is a positive number |
| [isUnitlessNonZero()](#isUnitlessNonZero--) | The value has unitless type, but is not a zero - positive or negative number |
| [toPixel()](#toPixel--) | Converts the length to a number of pixels, if possible. |
| [to(byte unit)](#to-byte-) | Converts the length to the given unit, if possible. |
| [toStringSpecified(byte unit)](#toStringSpecified-byte-) | Returns a string representation of this length in specified unit type. |
| [serializeDefault()](#serializeDefault--) | Returns a string representation of this length in its original native form (as it is stored), without converting length value to some other unit type |
| [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Defines whether this value is equal to the other specified length |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this length is equal to specified object |
| [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Multiplicates the given Length onto the given factor |
| [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Checks the equality of the two given lengths. |
| [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Checks the inequality of the two given lengths. |
| [hashCode()](#hashCode--) | Calculates and returns a hash-code of this Length instance by combining hash-codes of the value and unit type |
| [deepClone()](#deepClone--) | Returns a full copy of this Length instance |
| [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Tries to parse specified unit name and return corresponding value of a Unit enum. |
| [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Tries to parse a specified string as a Length value, including its numeric value and unit name |
| [parse(String input)](#parse-java.lang.String-) | Parses and returns specified string as a Length value, including its numeric value and unit name, or throws an exception on failure |
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Unitless integer zero - default value, the same as default parameterless constructor

### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%

### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%

### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%

### fromValueWithUnit(float value, byte unit) {#fromValueWithUnit-float-byte-}
```
public static Length fromValueWithUnit(float value, byte unit)
```


Creates and returns an instance of Length type by specified float number and unit

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | >Any float (FP32) number |
| unit | byte | Any valid unit type |

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type
### fromValueWithUnit(double value, byte unit) {#fromValueWithUnit-double-byte-}
```
public static Length fromValueWithUnit(double value, byte unit)
```


Creates and returns an instance of Length type by specified double number and unit

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Any double (FP64) number, that will be converted to float (FP32) |
| unit | byte | Any valid unit type |

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type
### fromValueWithUnit(int value, byte unit) {#fromValueWithUnit-int-byte-}
```
public static Length fromValueWithUnit(int value, byte unit)
```


Creates and returns an instance of Length type by specified integer number and unit

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Any integer number |
| unit | byte | Any valid unit type |

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type
### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Determines whether this instance is a unitless zero or not. Unitless zero is default value of this type. Same as IsDefault property.

**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this Length instance has a default value \\u2014 unitless zero. Same as IsUnitlessZero property.

**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final byte getUnitType()
```


Returns a unit type of this Length instance.

**Returns:**
byte
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Indicates whether the numeric value of this Length instance was originally specified and stored as an integer (INT32) number

**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Indicates whether the numeric value of this Length instance was originally specified and stored as a float (FP32) number

**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Returns a float numeric value of the Length instance. Never throws an exception - converts Integer value to Float if necessary.

**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Returns an integer numeric value of this Length instance, if it is internally stored as an integer, or throws an exception, if it was originally stored as a float number.

**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Gets if the length is given in absolute units. Such a length may be converted to pixels.

**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Gets if the length is given in relative units. Such a length cannot be converted to pixels.

**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Determines whether the numeric value of this length is a zero number

**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Determines whether the numeric value of this length is a negative number

**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Determines whether the numeric value of this length is a positive number

**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


The value has unitless type, but is not a zero - positive or negative number

**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Converts the length to a number of pixels, if possible. If the current unit is relative, then an exception will be thrown.

**Returns:**
float - The number of pixels represented by the current length.
### to(byte unit) {#to-byte-}
```
public final float to(byte unit)
```


Converts the length to the given unit, if possible. If the current or given unit is relative, then an exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unit | byte | The unit to convert to. |

**Returns:**
float - The value in the given unit of the current length.
### toStringSpecified(byte unit) {#toStringSpecified-byte-}
```
public final String toStringSpecified(byte unit)
```


Returns a string representation of this length in specified unit type. Numeric value will be converted in corresponding to unit type change.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unit | byte | Specified unit, to which this instance should be converted before serializing to the string. Should be valid. Cannot be unitless. |

**Returns:**
java.lang.String - String representation
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Returns a string representation of this length in its original native form (as it is stored), without converting length value to some other unit type

**Returns:**
java.lang.String - String instance
### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Defines whether this value is equal to the other specified length

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Other instance of Length type |

**Returns:**
boolean - True if equal, otherwise false
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this length is equal to specified object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other instance of Length type, that is boxed to the System.Object or any other abstract type or interface |

**Returns:**
boolean - True if equal, otherwise false
### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Multiplicates the given Length onto the given factor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - multiplicand |
| factor | int | Arbitrary integer - factor |

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication
### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Checks the equality of the two given lengths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | The left length operand. |
| right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | The right length operand. |

**Returns:**
boolean - True if both lengths are equal, otherwise false.
### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Checks the inequality of the two given lengths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | The left length operand. |
| right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | The right length operand. |

**Returns:**
boolean - True if both lengths are not equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calculates and returns a hash-code of this Length instance by combining hash-codes of the value and unit type

**Returns:**
int - Integer number
### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Returns a full copy of this Length instance

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one
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
### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Tries to parse a specified string as a Length value, including its numeric value and unit name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String | Input string, that should be parsed |
| result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Output parameter, that contains a result of parsing. If parsing is unsuccessful, contains a default Length value \\u2014 a unitless zero. |

**Returns:**
boolean - True if parsing is successful, false if unsuccessful
### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Parses and returns specified string as a Length value, including its numeric value and unit name, or throws an exception on failure

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String | Input string, that should be parsed |

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance
