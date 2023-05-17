---
title: FontStyle
second_title: GroupDocs.Editor for Java API Reference
description: Defines how the font should be styled with a normal italic or oblique face from its font-family.
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Defines how the font should be styled with: a normal, italic, or oblique face from its font-family.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Normal](#Normal) | Selects a font that is classified as normal within a font-family. |
| [Italic](#Italic) | Selects a font that is classified as italic. |
| [Oblique](#Oblique) | Selects a font that is classified as oblique. |
## Methods

| Method | Description |
| --- | --- |
| [isInitial()](#isInitial--) | Indicates whether this font-style has an initial value (Normal) |
| [getValue()](#getValue--) | Returns a value of this font style as a string |
| [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Determines whether this font-style instance is equal to specified |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this font-style instance is equal to specified uncasted |
| [hashCode()](#hashCode--) | Returns a hash-code for this instance |
| [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Checks whether two "FontStyle" values are equal |
| [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Checks whether two "FontStyle" values are not equal |
| [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Tries to recognize a specified keyword as a proper keyword value of the 'font-style' and return it on success or NULL on failure. |
| [equals(FontStyle obj1, FontStyle obj2)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) |  |
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Selects a font that is classified as normal within a font-family. Initial value.

### Italic {#Italic}
```
public static final FontStyle Italic
```


Selects a font that is classified as italic. If no italic version of the face is available, one classified as oblique is used instead. If neither is available, the style is artificially simulated.

### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Selects a font that is classified as oblique. If no oblique version of the face is available, one classified as italic is used instead. If neither is available, the style is artificially simulated.

### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indicates whether this font-style has an initial value (Normal)

**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returns a value of this font style as a string

**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Determines whether this font-style instance is equal to specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Other font-style instance |

**Returns:**
boolean - true if are equal, false otherwise
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this font-style instance is equal to specified uncasted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other uncasted font-style instance, may be null |

**Returns:**
boolean - true if are equal, false if not equal, null or of other type
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code for this instance

**Returns:**
int - Hash-code as an signed integer
### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Checks whether two "FontStyle" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | First value to check |
| second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Second value to check |

**Returns:**
boolean - true if are equal, false otherwise
### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Checks whether two "FontStyle" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | First value to check |
| second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Second value to check |

**Returns:**
boolean - false if are equal, true otherwise
### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Tries to recognize a specified keyword as a proper keyword value of the 'font-style' and return it on success or NULL on failure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyword | java.lang.String | A keyword to parse |
| result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Result, of parsing was successful, or \#Normal.Normal otherwise |

**Returns:**
boolean - true if parsing was successful, false otherwise
### equals(FontStyle obj1, FontStyle obj2) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean equals(FontStyle obj1, FontStyle obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |
| obj2 | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

**Returns:**
boolean
