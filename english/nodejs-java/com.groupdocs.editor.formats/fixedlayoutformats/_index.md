---
title: FixedLayoutFormats
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Encapsulates all fixed-layout also know as fixed-page formats which includes PDF and XPS this does not include raster images
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat)
```
public class FixedLayoutFormats implements IDocumentFormat
```

Encapsulates all fixed-layout (also know as "fixed-page") formats, which includes PDF and XPS (this does not include raster images)

--------------------

Various document viewing or publishing applications allow users to open (Adobe Acrobat, XPS Viewer), and sometimes edit (Adobe InDesign) documents of specific formats. These applications typically produce so-called \\u201cfixed-page\\u201d format documents. Such a document format describes precisely where a document\\u2019s content is placed on every page. Internally, the PDF or XPS format contains a description of every page, as well as drawing instructions, specifying the layout of the content on the page. This is similar to image formats, describing where the content is shown either in raster or vector form.
## Constructors

| Constructor | Description |
| --- | --- |
| [FixedLayoutFormats()](#FixedLayoutFormats--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Pdf](#Pdf) | Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. |
| [Xps](#Xps) | XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. |
| [All](#All) | Returns an internal class, that provides enumerable possibilities over all existing fixed-layout formats |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns a formal full name of this fixed layout format |
| [getExtension()](#getExtension--) | Returns an extension (without leading dot character) of this fixed-layout format in lower case |
| [getMime()](#getMime--) | Returns a MIME code for this format |
| [toString()](#toString--) | Returns the name of this particular format, same as 'Name' property |
| [op_Equality(FixedLayoutFormats first, FixedLayoutFormats second)](#op-Equality-com.groupdocs.editor.formats.FixedLayoutFormats-com.groupdocs.editor.formats.FixedLayoutFormats-) | Checks two given FixedLayoutFormats instances on equality |
| [op_Inequality(FixedLayoutFormats first, FixedLayoutFormats second)](#op-Inequality-com.groupdocs.editor.formats.FixedLayoutFormats-com.groupdocs.editor.formats.FixedLayoutFormats-) | Checks two given FixedLayoutFormats instances on inequality |
| [equals(FixedLayoutFormats other)](#equals-com.groupdocs.editor.formats.FixedLayoutFormats-) | Determines whether this instance is equal to the other specified FixedLayoutFormats instance |
| [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.IDocumentFormat-) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the other specified object, that is presumably of boxed FixedLayoutFormats |
| [hashCode()](#hashCode--) | Returns a hash-code, that is immutable for this instance |
| [iterator()](#iterator--) | Returns an enumerator for all supportable WordProcessing formats |
| [to_Byte(FixedLayoutFormats input)](#to-Byte-com.groupdocs.editor.formats.FixedLayoutFormats-) | Returns a byte value from underlying field of specified FixedLayoutFormats instance |
| [to_FixedLayoutFormats(byte raw)](#to-FixedLayoutFormats-byte-) | Casts specified raw byte value to valid FixedLayoutFormats instance and returns it or throws an exception, is specified value is invalid |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Returns instance of [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
### FixedLayoutFormats() {#FixedLayoutFormats--}
```
public FixedLayoutFormats()
```


### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/pdf/

### Xps {#Xps}
```
public static final FixedLayoutFormats Xps
```


XPS file represents page layout files that are based on XML Paper Specifications created by Microsoft. It was developed as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/page-description-language/xps/

### All {#All}
```
public static final Iterator<FixedLayoutFormats> All
```


Returns an internal class, that provides enumerable possibilities over all existing fixed-layout formats

### getName() {#getName--}
```
public final String getName()
```


Returns a formal full name of this fixed layout format

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Returns an extension (without leading dot character) of this fixed-layout format in lower case

**Returns:**
java.lang.String
### getMime() {#getMime--}
```
public final String getMime()
```


Returns a MIME code for this format

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns the name of this particular format, same as 'Name' property

**Returns:**
java.lang.String - A String that represents this instance
### op_Equality(FixedLayoutFormats first, FixedLayoutFormats second) {#op-Equality-com.groupdocs.editor.formats.FixedLayoutFormats-com.groupdocs.editor.formats.FixedLayoutFormats-}
```
public static boolean op_Equality(FixedLayoutFormats first, FixedLayoutFormats second)
```


Checks two given FixedLayoutFormats instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) | First FixedLayoutFormats instance to check |
| second | [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) | Second FixedLayoutFormats instance to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(FixedLayoutFormats first, FixedLayoutFormats second) {#op-Inequality-com.groupdocs.editor.formats.FixedLayoutFormats-com.groupdocs.editor.formats.FixedLayoutFormats-}
```
public static boolean op_Inequality(FixedLayoutFormats first, FixedLayoutFormats second)
```


Checks two given FixedLayoutFormats instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) | First FixedLayoutFormats instance to check |
| second | [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) | Second FixedLayoutFormats instance to check |

**Returns:**
boolean - True if are not equal, false if are equal
### equals(FixedLayoutFormats other) {#equals-com.groupdocs.editor.formats.FixedLayoutFormats-}
```
public final boolean equals(FixedLayoutFormats other)
```


Determines whether this instance is equal to the other specified FixedLayoutFormats instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) | Other FixedLayoutFormats instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Determines whether this instance is equal to the other specified IDocumentFormat instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat) | Other IDocumentFormat instance. If it is not a FixedLayoutFormats, method will return 'false' |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the other specified object, that is presumably of boxed FixedLayoutFormats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other boxed FixedLayoutFormats instance |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, that is immutable for this instance

**Returns:**
int - Signed 4-byte integer
### iterator() {#iterator--}
```
public final Iterator<FixedLayoutFormats> iterator()
```


Returns an enumerator for all supportable WordProcessing formats

**Returns:**
java.util.Iterator<com.groupdocs.editor.formats.FixedLayoutFormats> - Instance of internal class, that implements IEnumerator
### to_Byte(FixedLayoutFormats input) {#to-Byte-com.groupdocs.editor.formats.FixedLayoutFormats-}
```
public static byte to_Byte(FixedLayoutFormats input)
```


Returns a byte value from underlying field of specified FixedLayoutFormats instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) | Input FixedLayoutFormats instance |

**Returns:**
byte
### to_FixedLayoutFormats(byte raw) {#to-FixedLayoutFormats-byte-}
```
public static FixedLayoutFormats to_FixedLayoutFormats(byte raw)
```


Casts specified raw byte value to valid FixedLayoutFormats instance and returns it or throws an exception, is specified value is invalid

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| raw | byte | Raw byte value |

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Returns instance of [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Filename extension of any supportable FixedLayoutFormats format, with or without leading dot character, case-independent. Cannot be NULL or empty, should be valid. |

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - Instance of [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) structure on success or thrown exception on failure
