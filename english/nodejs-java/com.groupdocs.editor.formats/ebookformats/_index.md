---
title: EBookFormats
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Encapsulates all eBook formats.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat)
```
public class EBookFormats implements IDocumentFormat
```

Encapsulates all eBook formats. Includes the following file types: [Mobi](../../com.groupdocs.editor.formats/ebookformats\#Mobi), [Epub](../../com.groupdocs.editor.formats/ebookformats\#Epub) Learn more about Mobi format [here][], and about ePub format [here][here 1].


[here]: https://docs.fileformat.com/ebook/mobi/
[here 1]: https://docs.fileformat.com/ebook/epub/
## Constructors

| Constructor | Description |
| --- | --- |
| [EBookFormats()](#EBookFormats--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Mobi](#Mobi) | MOBI is the name given to the format developed for the MobiPocket Reader. |
| [Epub](#Epub) | Electronic Publication (ePub) format is an e-book file format that provide a standard digital publication format for publishers and consumers. |
| [Azw3](#Azw3) | AZW3, also known as Kindle Format 8 (KF8), is the modified version of the AZW ebook digital file format developed for Amazon Kindle devices. |
| [All](#All) | Returns an internal class, that provides enumerable possibilities over all existing EBook formats |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns a formal full name of this eBook format |
| [getExtension()](#getExtension--) | Returns an extension (without leading dot character) of this EBook format in lower case |
| [getMime()](#getMime--) | Returns a MIME code for this format |
| [op_Equality(EBookFormats first, EBookFormats second)](#op-Equality-com.groupdocs.editor.formats.EBookFormats-com.groupdocs.editor.formats.EBookFormats-) | Checks two given EBookFormats instances on equality |
| [op_Inequality(EBookFormats first, EBookFormats second)](#op-Inequality-com.groupdocs.editor.formats.EBookFormats-com.groupdocs.editor.formats.EBookFormats-) | Checks two given EBookFormats instances on inequality |
| [equals(EBookFormats other)](#equals-com.groupdocs.editor.formats.EBookFormats-) | Determines whether this instance is equal to the other specified EBookFormats instance |
| [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.IDocumentFormat-) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the other specified object, that is presumably of boxed EBookFormats |
| [hashCode()](#hashCode--) | Returns a hash-code, that is immutable for this instance |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Returns instance of [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [toString()](#toString--) | Returns a format name of this format |
### EBookFormats() {#EBookFormats--}
```
public EBookFormats()
```


### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI is the name given to the format developed for the MobiPocket Reader. It is currently used by Amazon with a slightly different DRM scheme and called AZW. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/ebook/mobi/

### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (ePub) format is an e-book file format that provide a standard digital publication format for publishers and consumers. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/ebook/epub/

### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, also known as Kindle Format 8 (KF8), is the modified version of the AZW ebook digital file format developed for Amazon Kindle devices. The format is an enhancement to older AZW files. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/ebook/azw3/

### All {#All}
```
public static final EBookFormats.AllEnumerable All
```


Returns an internal class, that provides enumerable possibilities over all existing EBook formats

### getName() {#getName--}
```
public final String getName()
```


Returns a formal full name of this eBook format

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Returns an extension (without leading dot character) of this EBook format in lower case

**Returns:**
java.lang.String
### getMime() {#getMime--}
```
public final String getMime()
```


Returns a MIME code for this format

**Returns:**
java.lang.String
### op_Equality(EBookFormats first, EBookFormats second) {#op-Equality-com.groupdocs.editor.formats.EBookFormats-com.groupdocs.editor.formats.EBookFormats-}
```
public static boolean op_Equality(EBookFormats first, EBookFormats second)
```


Checks two given EBookFormats instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | First EBookFormats instance to check |
| second | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | Second EBookFormats instance to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(EBookFormats first, EBookFormats second) {#op-Inequality-com.groupdocs.editor.formats.EBookFormats-com.groupdocs.editor.formats.EBookFormats-}
```
public static boolean op_Inequality(EBookFormats first, EBookFormats second)
```


Checks two given EBookFormats instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | First EBookFormats instance to check |
| second | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | Second EBookFormats instance to check |

**Returns:**
boolean - True if are not equal, false if are equal
### equals(EBookFormats other) {#equals-com.groupdocs.editor.formats.EBookFormats-}
```
public final boolean equals(EBookFormats other)
```


Determines whether this instance is equal to the other specified EBookFormats instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | Other EBookFormats instance, that should be checked on equality with this |

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
| other | [IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat) | Other IDocumentFormat instance. If it is not a EBookFormats, method will return 'false' |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the other specified object, that is presumably of boxed EBookFormats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other boxed EBookFormats instance |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, that is immutable for this instance

**Returns:**
int - Signed 4-byte integer
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Returns instance of [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Filename extension of any supportable EBook format, with or without leading dot character, case-independent. Cannot be NULL or empty, should be valid. |

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - Instance of [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) structure on success or thrown exception on failure
### toString() {#toString--}
```
public String toString()
```


Returns a format name of this format

**Returns:**
java.lang.String - A String that represents this instance.
