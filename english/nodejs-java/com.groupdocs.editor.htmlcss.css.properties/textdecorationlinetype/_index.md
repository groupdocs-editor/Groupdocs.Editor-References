---
title: TextDecorationLineType
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents types of the text decoration line underline underscore overline and line-through strikethrough
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Represents types of the text decoration line: underline (underscore), overline, and line-through (strikethrough)

--------------------

Immutable struct. Similar to the https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line
## Constructors

| Constructor | Description |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Produces no text decoration. |
| [Underline](#Underline) | Each line of text is underlined. |
| [Overline](#Overline) | Each line of text has a line above it. |
| [LineThrough](#LineThrough) | Each line of text has a line through the middle. |
## Methods

| Method | Description |
| --- | --- |
| [isInitial()](#isInitial--) | Indicates whether this instance has an initial value \\u2014 None |
| [isUnderline()](#isUnderline--) | Indicates whether underline (underscore) is enabled |
| [isOverline()](#isOverline--) | Indicates whether overline is enabled |
| [isLineThrough()](#isLineThrough--) | Indicates whether line-through (strikethrough) is enabled |
| [getValue()](#getValue--) | Returns a value of all flags in this instance as text |
| [toString()](#toString--) | Returns a value of all flags in this instance as text |
| [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Indicates whether this [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance is equal to specified |
| [equals(Object other)](#equals-java.lang.Object-) | Indicates whether this [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance is equal to specified uncasted |
| [hashCode()](#hashCode--) | Returns a hash-code of this instance |
| [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Checks whether two "TextDecorationLineType" values are equal |
| [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Checks whether two "TextDecorationLineType" values are not equal |
| [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Creates and returns a [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance with flags, defined by the specified parameters |
| [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Tries to parse a specified string and return a valid [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance |
| [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Combines (merges) two specified line types and produces new resultant line type, where flags are merged (union) |
| [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Subtracts second specified line type from the first specified line type and produces new resultant line type, where are present only those flags from the first operand, which are not found in the second operand (difference) |
| [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Returns an intersection between first and second line types, where only those flags are enabled, which are enabled simultaneously in both operands. |
| [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Casts specific byte (8-bit octet) to the corresponding [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), throws exception if casting is invalid |
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Produces no text decoration. Initial value.

### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Each line of text is underlined.

### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Each line of text has a line above it.

### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Each line of text has a line through the middle.

### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indicates whether this instance has an initial value \\u2014 None

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Indicates whether underline (underscore) is enabled

**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Indicates whether overline is enabled

**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Indicates whether line-through (strikethrough) is enabled

**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returns a value of all flags in this instance as text

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a value of all flags in this instance as text

**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Indicates whether this [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance is equal to specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Other [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance |

**Returns:**
boolean -  true  if are equal,  false  otherwise
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Indicates whether this [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance is equal to specified uncasted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Other [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance, casted to object |

**Returns:**
boolean -  true  if are equal,  false  otherwise
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code of this instance

**Returns:**
int - Signed integer hash-code
### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Checks whether two "TextDecorationLineType" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | First operand to check |
| second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Second operand to check |

**Returns:**
boolean -  true  if are equal,  false  otherwise
### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Checks whether two "TextDecorationLineType" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | First operand to check |
| second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Second operand to check |

**Returns:**
boolean -  true  if are unequal,  false  otherwise
### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Creates and returns a [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance with flags, defined by the specified parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isUnderline | boolean | Determines whether an underline flag is enabled or not |
| isOverline | boolean | Determines whether an overline flag is enabled or not |
| isLineThrough | boolean | Determines whether an line-through flag is enabled or not |

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance
### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Tries to parse a specified string and return a valid [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String | Input string |
| output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Result. If parsing is invalid, it is a \#None.None value |

**Returns:**
boolean -  true  if parsing was successful,  false  on failure
### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Combines (merges) two specified line types and produces new resultant line type, where flags are merged (union)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | First line type operand |
| second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Second line type operand |

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands
### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Subtracts second specified line type from the first specified line type and produces new resultant line type, where are present only those flags from the first operand, which are not found in the second operand (difference)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | First line type operand |
| second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Second line type operand |

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands
### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Returns an intersection between first and second line types, where only those flags are enabled, which are enabled simultaneously in both operands. Has the highest priority between all operators (higher than union and difference)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | First line type operand |
| second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Second line type operand |

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands
### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Casts specific byte (8-bit octet) to the corresponding [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), throws exception if casting is invalid

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| octet | byte | A 8-bit octet (bitfield), where 5 leading bits are zeros, while last 3 indicate flags |

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
