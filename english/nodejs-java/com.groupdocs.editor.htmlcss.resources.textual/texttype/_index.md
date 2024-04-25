---
title: TextType
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents one supportable textual resource type
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Represents one supportable textual resource type
## Constructors

| Constructor | Description |
| --- | --- |
| [TextType()](#TextType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getUndefined()](#getUndefined--) | Special value, which marks undefined, unknown or unsupported textual resource |
| [getCss()](#getCss--) | CSS type of the textual resource |
| [getXml()](#getXml--) | XML type of the textual resource |
| [getFormalName()](#getFormalName--) | Returns a formal name of this textual resource type |
| [getFileExtension()](#getFileExtension--) | File extension (without leading dot character) of a particular textual resource |
| [getMimeCode()](#getMimeCode--) | MIME code of a particular textual resource type |
| [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Determines whether this instance is equal with specified "TextType" instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal with specified uncasted object, which presumably is another "TextType" instance |
| [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Defines whether two specific "TextType" instances are equal |
| [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Defines whether two specific "TextType" instances are not equal |
| [hashCode()](#hashCode--) | Returns a hash-code, which is a constant number for this specific value type |
| [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returns TextType value, which is equivalent of filename extension, which is extracted from specified filename with extension or pure extension |
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Special value, which marks undefined, unknown or unsupported textual resource

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


CSS type of the textual resource

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


XML type of the textual resource

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Returns a formal name of this textual resource type

**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


File extension (without leading dot character) of a particular textual resource

**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME code of a particular textual resource type

**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Determines whether this instance is equal with specified "TextType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Other TextType instance, that should be compared with this on equality |

**Returns:**
boolean - Returns true if are equal or false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal with specified uncasted object, which presumably is another "TextType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other TextType instance, that is boxed to object |

**Returns:**
boolean - Returns true if are equal or false if are unequal
### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Defines whether two specific "TextType" instances are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | First TextType instance |
| second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Second TextType instance |

**Returns:**
boolean - Returns true if are equal or false if are unequal
### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Defines whether two specific "TextType" instances are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | First TextType instance |
| second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Second TextType instance |

**Returns:**
boolean - Returns true if are unequal or false if are equal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, which is a constant number for this specific value type

**Returns:**
int - Signed 4-byte integer number. Returns 0 if this instance has default value.
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Returns TextType value, which is equivalent of filename extension, which is extracted from specified filename with extension or pure extension

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Filename with extension, can be relative or absolute path, or pure extension itself |

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure
