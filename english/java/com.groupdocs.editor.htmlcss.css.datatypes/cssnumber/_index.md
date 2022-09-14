---
title: CssNumber
second_title: GroupDocs.Editor for Java API Reference
description: Represents a CSS number which may be an integer of float and is used in the CSS declaration and tokens during CSS tokenization procedure
type: docs
weight: 16
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/cssnumber/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CssNumber extends Struct<CssNumber>
```

Represents a CSS number, which may be an integer of float, and is used in the CSS declaration and tokens during CSS tokenization procedure
## Constructors

| Constructor | Description |
| --- | --- |
| [CssNumber()](#CssNumber--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Default empty number (zero, integer, NULL substring) |
## Methods

| Method | Description |
| --- | --- |
| [isDefault()](#isDefault--) | Indicates whether this instance has a default value - integer zero. |
| [getType()](#getType--) | Type of this CSS number - integer or float |
| [getLeadingSign()](#getLeadingSign--) | Returns a type of leading sign. |
| [getOrigin()](#getOrigin--) |  |
| [isZero()](#isZero--) | Indicates whether this number is a zero (integer or float) |
| [getInteger()](#getInteger--) |  |
| [getFloat()](#getFloat--) |  |
| [toFloat()](#toFloat--) |  |
| [toString()](#toString--) | Returns a string representation of this number. |
| [fromInteger(int value, Substring origin, byte leadingSign)](#fromInteger-int-com.groupdocs.editor.htmlcss.tools.Substring-byte-) |  |
| [fromFloat(float value, Substring origin, byte leadingSign)](#fromFloat-float-com.groupdocs.editor.htmlcss.tools.Substring-byte-) |  |
| [CloneTo(CssNumber that)](#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(CssNumber obj1, CssNumber obj2)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-) |  |
### CssNumber() {#CssNumber--}
```
public CssNumber()
```


### Empty {#Empty}
```
public static final CssNumber Empty
```


Default empty number (zero, integer, NULL substring)

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this instance has a default value - integer zero.

**Returns:**
boolean
### getType() {#getType--}
```
public final byte getType()
```


Type of this CSS number - integer or float

**Returns:**
byte
### getLeadingSign() {#getLeadingSign--}
```
public final byte getLeadingSign()
```


Returns a type of leading sign. Actual only when this instance is obtained from parsing procedure.

**Returns:**
byte
### getOrigin() {#getOrigin--}
```
public final Substring getOrigin()
```




**Returns:**
[Substring](../../com.groupdocs.editor.htmlcss.tools/substring)
### isZero() {#isZero--}
```
public final boolean isZero()
```


Indicates whether this number is a zero (integer or float)

**Returns:**
boolean
### getInteger() {#getInteger--}
```
public final int getInteger()
```




**Returns:**
int
### getFloat() {#getFloat--}
```
public final float getFloat()
```




**Returns:**
float
### toFloat() {#toFloat--}
```
public final float toFloat()
```




**Returns:**
float
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of this number. If number is float, it will be returned with InvariantCulture settings.

**Returns:**
java.lang.String - 
### fromInteger(int value, Substring origin, byte leadingSign) {#fromInteger-int-com.groupdocs.editor.htmlcss.tools.Substring-byte-}
```
public static CssNumber fromInteger(int value, Substring origin, byte leadingSign)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
| origin | [Substring](../../com.groupdocs.editor.htmlcss.tools/substring) |  |
| leadingSign | byte |  |

**Returns:**
[CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber)
### fromFloat(float value, Substring origin, byte leadingSign) {#fromFloat-float-com.groupdocs.editor.htmlcss.tools.Substring-byte-}
```
public static CssNumber fromFloat(float value, Substring origin, byte leadingSign)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
| origin | [Substring](../../com.groupdocs.editor.htmlcss.tools/substring) |  |
| leadingSign | byte |  |

**Returns:**
[CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber)
### CloneTo(CssNumber that) {#CloneTo-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-}
```
public void CloneTo(CssNumber that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber) |  |

### Clone() {#Clone--}
```
public CssNumber Clone()
```




**Returns:**
[CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
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
### equals(CssNumber obj1, CssNumber obj2) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-com.groupdocs.editor.htmlcss.css.datatypes.CssNumber-}
```
public static boolean equals(CssNumber obj1, CssNumber obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber) |  |
| obj2 | [CssNumber](../../com.groupdocs.editor.htmlcss.css.datatypes/cssnumber) |  |

**Returns:**
boolean
