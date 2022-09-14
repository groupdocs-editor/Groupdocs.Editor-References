---
title: Ratio
second_title: GroupDocs.Editor for Java API Reference
description: Represents a ratio CSS data type which is used for describing aspect ratios in media queries and for raster images by denoting the proportion between two unitless values called numerator and denominator.
type: docs
weight: 24
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Represents a "ratio" CSS data type, which is used for describing aspect ratios in media queries and for raster images by denoting the proportion between two unitless values called "numerator" and "denominator". Immutable struct.

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio
## Constructors

| Constructor | Description |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Single](#Single) | Single default ratio 1/1 |
## Methods

| Method | Description |
| --- | --- |
| [getNumerator()](#getNumerator--) | Returns a numerator of this ratio |
| [getDenominator()](#getDenominator--) | Returns a denominator of this ratio |
| [calculate()](#calculate--) | Calculates and returns this ratio as a single floating point number |
| [getInverseRatio()](#getInverseRatio--) | Generates and returns an inverse (reciprocal) ratio for this ratio |
| [serializeDefault()](#serializeDefault--) | Serializes this ratio to the string and returns it |
| [toString()](#toString--) | Returns a string representation of this ratio; same as "SerializeDefault()" |
| [isDefault()](#isDefault--) | Determines whether this ratio has default value or is a "1/1" (Single) |
| [deepClone()](#deepClone--) | Returns a full copy of this ratio |
| [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Determines whether this instance is equal with specified "Ratio" instance |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether this instance is equal with specified uncasted object, which presumably is another "Ratio" instance |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Compares two ratios and returns a boolean indicating if the two do match. |
| [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Compares two ratios and returns a boolean indicating if the two do not match. |
| [hashCode()](#hashCode--) | Returns a hashcode for this instance, which cannot be changed during its lifetime |
| [create(int numerator, int denominator)](#create-int-int-) | Creates and returns one Ratio instance from specified numerator and denominator |
| [CloneTo(Ratio that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Ratio obj1, Ratio obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) |  |
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Single default ratio 1/1

### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Returns a numerator of this ratio

**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Returns a denominator of this ratio

**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Calculates and returns this ratio as a single floating point number

**Returns:**
double - Floating-point number with double precision
### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Generates and returns an inverse (reciprocal) ratio for this ratio

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one
### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serializes this ratio to the string and returns it

**Returns:**
java.lang.String - String in "numerator/denominator" format
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of this ratio; same as "SerializeDefault()"

**Returns:**
java.lang.String - String in "numerator/denominator" format
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determines whether this ratio has default value or is a "1/1" (Single)

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Returns a full copy of this ratio

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one
### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Determines whether this instance is equal with specified "Ratio" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Other Ratio instance to check on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determines whether this instance is equal with specified uncasted object, which presumably is another "Ratio" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Other System.Object instance, that is presumably of Ratio type, to check on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
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
### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Compares two ratios and returns a boolean indicating if the two do match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | The first ratio to use. |
| right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | The second ratio to use. |

**Returns:**
boolean - True if both ratios are equal, otherwise false.
### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Compares two ratios and returns a boolean indicating if the two do not match.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | The first ratio to use. |
| right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | The second ratio to use. |

**Returns:**
boolean - True if both ratios are not equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hashcode for this instance, which cannot be changed during its lifetime

**Returns:**
int - Signed 4-byte integer, that is immutable for this instance
### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Creates and returns one Ratio instance from specified numerator and denominator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | int | Numerator for the ratio. Should be a strictly positive integer number. |
| denominator | int | Denominator for the ratio. Should be a strictly positive integer number. |

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance
### CloneTo(Ratio that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public void CloneTo(Ratio that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) |  |

### Clone() {#Clone--}
```
public Ratio Clone()
```




**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Ratio obj1, Ratio obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean equals(Ratio obj1, Ratio obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) |  |
| obj2 | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) |  |

**Returns:**
boolean
