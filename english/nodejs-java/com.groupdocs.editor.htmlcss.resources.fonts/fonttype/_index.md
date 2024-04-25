---
title: FontType
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents one supportable font type
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Represents one supportable font type
## Constructors

| Constructor | Description |
| --- | --- |
| [FontType()](#FontType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getUndefined()](#getUndefined--) | Special value, which marks undefined, unknown or unsupported font resource |
| [getWoff()](#getWoff--) | Represents a WOFF (Web Open Font Format) font type |
| [getWoff2()](#getWoff2--) | Represents a WOFF2 (Web Open Font Format version 2) font type |
| [getTtf()](#getTtf--) | Represents a TTF (TrueType Font) font type |
| [getEot()](#getEot--) | Represents a EOT (Embedded OpenType) font type |
| [getOtf()](#getOtf--) | Represents a OTF (OpenType Font) font type |
| [getCssName()](#getCssName--) | Returns CSS-compatible name of this font type, which is used in the |
| [getFormalName()](#getFormalName--) | Returns a formal name of this font type |
| [getFileExtension()](#getFileExtension--) | Filename extension (without dot character) for this font type |
| [getFontFormat()](#getFontFormat--) | Font format for @font-face format |
| [getMimeCode()](#getMimeCode--) | MIME code of a particular font type |
| [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Returns FontType value, which is equivalent of specified CSS-compatible name of the font type |
| [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returns FontType value, which is equivalent of filename extension, which is extracted from specified filename |
| [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Returns FontType value, which is equivalent of specified MIME-code |
| [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Returns a first font type from specified set, which is not an "Undefined" value, or "Undefined" font type otherwise (when all items are "Undefined") |
| [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Determines whether this instance is equal with specified "FontType" instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal with specified uncasted object, which presumably is another "FontType" instance |
| [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Checks whether two "FontType" values are equal |
| [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Checks whether two "FontType" values are not equal |
| [hashCode()](#hashCode--) | Returns a hash-code, which is a constant number for this specific value type |
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Special value, which marks undefined, unknown or unsupported font resource

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Represents a WOFF (Web Open Font Format) font type

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Represents a WOFF2 (Web Open Font Format version 2) font type

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Represents a TTF (TrueType Font) font type

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Represents a EOT (Embedded OpenType) font type

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Represents a OTF (OpenType Font) font type

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Returns CSS-compatible name of this font type, which is used in the

**Returns:**
java.lang.String - 
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Returns a formal name of this font type

**Returns:**
java.lang.String - 
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Filename extension (without dot character) for this font type

**Returns:**
java.lang.String - 
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Font format for @font-face format

**Returns:**
java.lang.String - 
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME code of a particular font type

**Returns:**
java.lang.String - 
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Returns FontType value, which is equivalent of specified CSS-compatible name of the font type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | CSS-compatible name of the font type |

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Returns FontType value, which is equivalent of filename extension, which is extracted from specified filename

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Filename with extension, may be a full name |

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure
### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Returns FontType value, which is equivalent of specified MIME-code

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mimeCode | java.lang.String | MIME-code |

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure
### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Returns a first font type from specified set, which is not an "Undefined" value, or "Undefined" font type otherwise (when all items are "Undefined")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | One or more FontType values, NULL or empty collection is not allowed |

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined
### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Determines whether this instance is equal with specified "FontType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Other FontType instance to check with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal with specified uncasted object, which presumably is another "FontType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other instance presumably of FontType struct, that was boxed to System.Object |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Checks whether two "FontType" values are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | First FontType to check |
| second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Second FontType to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Checks whether two "FontType" values are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | First FontType to check |
| second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Second FontType to check |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, which is a constant number for this specific value type

**Returns:**
int - 4-byte signed integer, 0 for Undefined value
