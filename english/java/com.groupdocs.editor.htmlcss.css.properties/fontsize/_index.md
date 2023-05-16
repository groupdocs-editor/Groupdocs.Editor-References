---
title: FontSize
second_title: GroupDocs.Editor for Java API Reference
description: Represents a font size as a special unit or a length value which specifies the size of the font historically the width of the capital M.
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Represents a font size as a special unit or a length value, which specifies the size of the font (historically the width of the capital "M").
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Medium](#Medium) | Medium size. |
| [XxSmall](#XxSmall) | The very small absolute-size |
| [XSmall](#XSmall) | The mediocre small absolute-size |
| [Small](#Small) | The normally small absolute-size |
| [Large](#Large) | The normally large absolute-size |
| [XLarge](#XLarge) | The mediocre large absolute-size |
| [XxLarge](#XxLarge) | The very large absolute-size |
| [Larger](#Larger) | Larger relative-size - font will be larger relative to the parent element's font-size, roughly by the ratio used to separate the absolute-size keywords above. |
| [Smaller](#Smaller) | Smaller relative-size - font will be smaller relative to the parent element's font-size, roughly by the ratio used to separate the absolute-size keywords above. |
## Methods

| Method | Description |
| --- | --- |
| [isInitial()](#isInitial--) | Indicates whether this font-size has an initial value (Medium) |
| [getValue()](#getValue--) | Returns a value of this font size as a string |
| [isLengthDefined()](#isLengthDefined--) | Indicates whether this font-size is defined with a [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) value |
| [getLength()](#getLength--) | A length value, if this font-size was defined with it, or throwed exception otherwise |
| [isAbsoluteSize()](#isAbsoluteSize--) | Indicates whether this font-size is defined with an absolute size as a keyword, based on the user's default font size (which is medium) |
| [isRelativeSize()](#isRelativeSize--) | Indicates whether this font-size is defined with an relative size as a keyword. |
| [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Determines whether this font-size instance is equal to specified |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this font-size instance is equal to specified uncasted |
| [hashCode()](#hashCode--) | Returns a hash-code for this instance |
| [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Checks whether two "FontSize" values are equal |
| [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Checks whether two "FontSize" values are not equal |
| [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Creates a font-size from specified length |
| [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Tries to recognize a specified keyword as a proper keyword value of the 'font-size' and return it on success or NULL on failure. |
| [equals(FontSize obj1, FontSize obj2)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) |  |
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Medium size. Initial value.

### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


The very small absolute-size

### XSmall {#XSmall}
```
public static final FontSize XSmall
```


The mediocre small absolute-size

### Small {#Small}
```
public static final FontSize Small
```


The normally small absolute-size

### Large {#Large}
```
public static final FontSize Large
```


The normally large absolute-size

### XLarge {#XLarge}
```
public static final FontSize XLarge
```


The mediocre large absolute-size

### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


The very large absolute-size

### Larger {#Larger}
```
public static final FontSize Larger
```


Larger relative-size - font will be larger relative to the parent element's font-size, roughly by the ratio used to separate the absolute-size keywords above.

### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Smaller relative-size - font will be smaller relative to the parent element's font-size, roughly by the ratio used to separate the absolute-size keywords above.

### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indicates whether this font-size has an initial value (Medium)

**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returns a value of this font size as a string

**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Indicates whether this font-size is defined with a [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) value

**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


A length value, if this font-size was defined with it, or throwed exception otherwise

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Indicates whether this font-size is defined with an absolute size as a keyword, based on the user's default font size (which is medium)

**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Indicates whether this font-size is defined with an relative size as a keyword. The font will be larger or smaller relative to the parent element's font size, roughly by the ratio used to separate the absolute-size keywords.

**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Determines whether this font-size instance is equal to specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Other font-size instance |

**Returns:**
boolean - true if are equal, false otherwise
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this font-size instance is equal to specified uncasted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other uncasted font-size instance, may be null |

**Returns:**
boolean - true if are equal, false if not equal, null or of other type
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code for this instance

**Returns:**
int - Hash-code as an signed integer
### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Checks whether two "FontSize" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | First value to check |
| second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Second value to check |

**Returns:**
boolean - true if are equal, false otherwise
### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Checks whether two "FontSize" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | First value to check |
| second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Second value to check |

**Returns:**
boolean - false if are equal, true otherwise
### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Creates a font-size from specified length

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | A length value, cannot be unitless or negative |

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance
### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Tries to recognize a specified keyword as a proper keyword value of the 'font-size' and return it on success or NULL on failure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyword | java.lang.String | A keyword to parse |
| result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Result, of parsing was successful, or \#Medium.Medium otherwise |

**Returns:**
boolean - true if parsing was successful, false otherwise
### equals(FontSize obj1, FontSize obj2) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean equals(FontSize obj1, FontSize obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |
| obj2 | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

**Returns:**
boolean
