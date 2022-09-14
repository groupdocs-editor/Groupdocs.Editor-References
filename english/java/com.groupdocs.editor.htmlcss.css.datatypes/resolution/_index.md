---
title: Resolution
second_title: GroupDocs.Editor for Java API Reference
description: Resolution CSS data type is used for describing resolutions in media queries denotes the pixel density of an output device i.e. its resolution.
type: docs
weight: 25
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/resolution/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Resolution extends Struct<Resolution> implements ICssDataType
```

Resolution CSS data type is used for describing resolutions in media queries, denotes the pixel density of an output device, i.e., its resolution. The 'resolution' data type consists of a strictly positive 'number' (Integer or Float) followed by one of the units. There is no space between the unit literal and the number.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/resolution
## Constructors

| Constructor | Description |
| --- | --- |
| [Resolution()](#Resolution--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Invalid](#Invalid) |  |
## Methods

| Method | Description |
| --- | --- |
| [tryParseUnitName(String input)](#tryParseUnitName-java.lang.String-) |  |
| [serialize(byte input)](#serialize-byte-) |  |
| [create(long value, byte unit)](#create-long-byte-) |  |
| [create(int value, byte unit)](#create-int-byte-) |  |
| [create(float value, byte unit)](#create-float-byte-) |  |
| [create(double value, byte unit)](#create-double-byte-) |  |
| [getUnitType()](#getUnitType--) |  |
| [isInteger()](#isInteger--) |  |
| [isFloat()](#isFloat--) |  |
| [getNumberType()](#getNumberType--) |  |
| [getFloatValue()](#getFloatValue--) | Gets the raw value of the length without relation to the unit type. |
| [getIntegerValue()](#getIntegerValue--) |  |
| [isValid()](#isValid--) |  |
| [isDefault()](#isDefault--) |  |
| [serializeDefault()](#serializeDefault--) |  |
| [convertTo(byte targetUnit)](#convertTo-byte-) |  |
| [areEqual(Resolution first, Resolution second)](#areEqual-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-) |  |
| [equals(Resolution other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-) |  |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [op_Equality(Resolution first, Resolution second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-) | Compares two resolutions and returns a boolean indicating if the two do match. |
| [op_Inequality(Resolution first, Resolution second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-) | Compares two resolutions and returns a boolean indicating if the two dont match. |
| [hashCode()](#hashCode--) | Returns a hashcode for this Resolution instance, which cannot be changed during its lifetime |
| [tryParse(String input, Resolution[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Resolution---) | Tries to parse a resolution from string and returns it via output parameter. |
| [CloneTo(Resolution that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Resolution obj1, Resolution obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-) |  |
### Resolution() {#Resolution--}
```
public Resolution()
```


### Invalid {#Invalid}
```
public static final Resolution Invalid
```


### tryParseUnitName(String input) {#tryParseUnitName-java.lang.String-}
```
public static byte tryParseUnitName(String input)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String |  |

**Returns:**
byte
### serialize(byte input) {#serialize-byte-}
```
public static String serialize(byte input)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | byte |  |

**Returns:**
java.lang.String
### create(long value, byte unit) {#create-long-byte-}
```
public static Resolution create(long value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
| unit | byte |  |

**Returns:**
[Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution)
### create(int value, byte unit) {#create-int-byte-}
```
public static Resolution create(int value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
| unit | byte |  |

**Returns:**
[Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution)
### create(float value, byte unit) {#create-float-byte-}
```
public static Resolution create(float value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
| unit | byte |  |

**Returns:**
[Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution)
### create(double value, byte unit) {#create-double-byte-}
```
public static Resolution create(double value, byte unit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
| unit | byte |  |

**Returns:**
[Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution)
### getUnitType() {#getUnitType--}
```
public final byte getUnitType()
```




**Returns:**
byte
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```




**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```




**Returns:**
boolean
### getNumberType() {#getNumberType--}
```
public final byte getNumberType()
```




**Returns:**
byte
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Gets the raw value of the length without relation to the unit type. Never throws an exception - converts Integer value to Float if necessary

**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final long getIntegerValue()
```




**Returns:**
long
### isValid() {#isValid--}
```
public final boolean isValid()
```




**Returns:**
boolean
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
### convertTo(byte targetUnit) {#convertTo-byte-}
```
public final Resolution convertTo(byte targetUnit)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetUnit | byte |  |

**Returns:**
[Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution)
### areEqual(Resolution first, Resolution second) {#areEqual-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-}
```
public static boolean areEqual(Resolution first, Resolution second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |
| second | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |

**Returns:**
boolean
### equals(Resolution other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-}
```
public final boolean equals(Resolution other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |

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
### op_Equality(Resolution first, Resolution second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-}
```
public static boolean op_Equality(Resolution first, Resolution second)
```


Compares two resolutions and returns a boolean indicating if the two do match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |
| second | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |

**Returns:**
boolean - 
### op_Inequality(Resolution first, Resolution second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-}
```
public static boolean op_Inequality(Resolution first, Resolution second)
```


Compares two resolutions and returns a boolean indicating if the two dont match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |
| second | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |

**Returns:**
boolean - 
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hashcode for this Resolution instance, which cannot be changed during its lifetime

**Returns:**
int - 
### tryParse(String input, Resolution[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Resolution---}
```
public static boolean tryParse(String input, Resolution[] result)
```


Tries to parse a resolution from string and returns it via output parameter. Never throws an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String | Any string, including null; exception will not be thrown anyway |
| result | com.groupdocs.editor.htmlcss.css.datatypes.Resolution[] | Valid resolution on success or 'Resolution.Invalid' on failure |

**Returns:**
boolean - 
### CloneTo(Resolution that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-}
```
public void CloneTo(Resolution that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |

### Clone() {#Clone--}
```
public Resolution Clone()
```




**Returns:**
[Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Resolution obj1, Resolution obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-com.groupdocs.editor.htmlcss.css.datatypes.Resolution-}
```
public static boolean equals(Resolution obj1, Resolution obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |
| obj2 | [Resolution](../../com.groupdocs.editor.htmlcss.css.datatypes/resolution) |  |

**Returns:**
boolean
