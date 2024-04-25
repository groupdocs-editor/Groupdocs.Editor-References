---
title: FontWeight
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Font-weight property sets the weight or boldness of the font.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Font-weight property sets the weight (or boldness) of the font. The weights available depend on the font-family that is currently set.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Lighter](#Lighter) | One relative font weight lighter than the parent element |
| [Bolder](#Bolder) | One relative font weight heavier than the parent element |
| [Normal](#Normal) | Normal font weight. |
| [Bold](#Bold) | Bold font weight. |
## Methods

| Method | Description |
| --- | --- |
| [isInitial()](#isInitial--) | Indicates whether this font-size has an initial value (Medium) |
| [getNumber()](#getNumber--) | Returns a number - integer value between 1 and 1000, inclusive, which describes the boldness of the font, or throws an exception, if current boldness is not absolute, but relative |
| [isAbsolute()](#isAbsolute--) | Indicates whether this font-weight instance stores an absolute value of the weight (boldness) of the font, as an integer number |
| [isRelative()](#isRelative--) | Indicates whether this font-weight instance stores a relative value of the weight (boldness) of the font - compared to the boldness of the parent element |
| [getValue()](#getValue--) | Returns a value of this font-weight as a string |
| [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Determines whether specified FontWeight instances are equal |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this FontWeight instance is equal to specified uncasted |
| [hashCode()](#hashCode--) | Returns a hash-code for this instance |
| [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Checks whether two "FontWeight" values are equal |
| [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Checks whether two "FontWeight" values are not equal |
| [fromNumber(int number)](#fromNumber-int-) | Creates a font-weight from specified number |
| [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Tries to parse a specified string and return a valid FontWeight instance on success |
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


One relative font weight lighter than the parent element

### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


One relative font weight heavier than the parent element

### Normal {#Normal}
```
public static final FontWeight Normal
```


Normal font weight. Same as 400.

### Bold {#Bold}
```
public static final FontWeight Bold
```


Bold font weight. Same as 700.

### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indicates whether this font-size has an initial value (Medium)

**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Returns a number - integer value between 1 and 1000, inclusive, which describes the boldness of the font, or throws an exception, if current boldness is not absolute, but relative

**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Indicates whether this font-weight instance stores an absolute value of the weight (boldness) of the font, as an integer number

**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Indicates whether this font-weight instance stores a relative value of the weight (boldness) of the font - compared to the boldness of the parent element

**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returns a value of this font-weight as a string

**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Determines whether specified FontWeight instances are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Other FontWeight instance to check the equality |

**Returns:**
boolean - true if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this FontWeight instance is equal to specified uncasted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other uncasted FontWeight instance, may be null |

**Returns:**
boolean - true if are equal, false if not equal, null or of other type
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code for this instance

**Returns:**
int - Hash-code as an signed integer
### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Checks whether two "FontWeight" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | First value to check |
| second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Second value to check |

**Returns:**
boolean - true if are equal, false otherwise
### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Checks whether two "FontWeight" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | First value to check |
| second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Second value to check |

**Returns:**
boolean - false if are equal, true otherwise
### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Creates a font-weight from specified number

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | Unsigned integer, must be within [1..1000] range |

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception
### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Tries to parse a specified string and return a valid FontWeight instance on success

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String | Input string to parse |
| result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Valid FontWeight value on success or \#Normal.Normal on failure |

**Returns:**
boolean - Success (true) or failure (false) of the parsing
