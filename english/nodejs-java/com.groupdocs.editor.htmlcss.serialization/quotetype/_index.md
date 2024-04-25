---
title: QuoteType
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents quote characters - single quote  and double quote
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Represents quote characters - single quote (') and double quote (")
## Constructors

| Constructor | Description |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Fields

| Field | Description |
| --- | --- |
| [SingleQuote](#SingleQuote) | Single quote (U+0027 APOSTROPHE character) |
| [DoubleQuote](#DoubleQuote) | Double quote (U+0022 QUOTATION MARK character) |
## Methods

| Method | Description |
| --- | --- |
| [getCode()](#getCode--) | Code point of the current character (U+0027 or U+0022) |
| [getCharacter()](#getCharacter--) | Character to enquote |
| [getHtmlEncoded()](#getHtmlEncoded--) | HTML-encoded character |
| [toString()](#toString--) | Returns a "SingleQuote" or "DoubleQuote" string depending on the current value |
| [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Indicates whether this instance of the quote type is equal to specified |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether this instance of the quote type is equal to specified uncasted |
| [hashCode()](#hashCode--) | Returns a hash-code for this character |
| [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Checks whether two "QuoteType" values are equal |
| [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Checks whether two "QuoteType" values are not equal |
| [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Casts specified [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) instance to the char |
| [to_QuoteType(char character)](#to-QuoteType-char-) | Casts specific char to the corresponding [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), throws exception if casting is invalid |
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Single quote (U+0027 APOSTROPHE character)

### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Double quote (U+0022 QUOTATION MARK character)

### getCode() {#getCode--}
```
public final int getCode()
```


Code point of the current character (U+0027 or U+0022)

**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Character to enquote

**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML-encoded character

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a "SingleQuote" or "DoubleQuote" string depending on the current value

**Returns:**
java.lang.String - 
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Indicates whether this instance of the quote type is equal to specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Other instance of QuoteType to check |

**Returns:**
boolean - true if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indicates whether this instance of the quote type is equal to specified uncasted

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Uncasted object, expected to be of [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) type |

**Returns:**
boolean - true if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code for this character

**Returns:**
int - Hash-code as an signed integer
### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Checks whether two "QuoteType" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | First value to check |
| second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Second value to check |

**Returns:**
boolean - true if are equal, false otherwise
### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Checks whether two "QuoteType" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | First value to check |
| second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Second value to check |

**Returns:**
boolean - false if are equal, true otherwise
### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Casts specified [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) instance to the char

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Quote type instance to cast |

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Casts specific char to the corresponding [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), throws exception if casting is invalid

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | A single quote (U+0027 APOSTROPHE) or double quote (U+0022 QUOTATION MARK) character. Exception will be thrown if any other character will be specified. |

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
