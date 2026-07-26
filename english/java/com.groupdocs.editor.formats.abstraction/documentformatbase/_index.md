---
title: DocumentFormatBase
second_title: GroupDocs.Editor for Java API Reference
description: Represents the base class for document formats providing common functionality for format instances.
type: docs
weight: 10
url: /java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Represents the base class for document formats, providing common functionality for format instances.

## Methods

| Method | Description |
| --- | --- |
| [getMime()](#getMime--) | Gets the MIME type of the document format.
 |
| [getExtension()](#getExtension--) | Gets the file extension of the document format.
 |
| [getFormatFamily()](#getFormatFamily--) | Gets the format family to which the document format belongs.
 |
| [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Retrieves an instance of the specified type 
T
 that has the specified MIME type.
 |
| [hashCode()](#hashCode--) | Returns a hash code for the current object.
 |
| [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Determines whether this instance is equal to the specified [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instance.
 |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the specified [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance.
 |
| [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Converts a [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance to a string implicitly.
 |
### getMime() {#getMime--}
```
public final String getMime()
```


Gets the MIME type of the document format.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Gets the file extension of the document format.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Gets the format family to which the document format belongs.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Retrieves an instance of the specified type 
T
 that has the specified MIME type.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
| mime | java.lang.String | The MIME type of the document format.


T
: The type of document format.
 |

**Returns:**
T - An instance of the specified type  T  with the specified MIME type.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for the current object.


**Returns:**
int - A hash code for the current object, combining the hash codes of the base object, MIME type, file extension, and format family.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Determines whether this instance is equal to the specified [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instance.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | The [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instance to compare with the current instance.
 |

**Returns:**
boolean -  true  if the specified [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) is equal to the current instance; otherwise,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the specified [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance to compare with the current instance.
 |

**Returns:**
boolean -  true  if the specified [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) is equal to the current instance; otherwise,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Converts a [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance to a string implicitly.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | The [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance to convert.
 |

**Returns:**
java.lang.String - The file extension of the [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instance.

