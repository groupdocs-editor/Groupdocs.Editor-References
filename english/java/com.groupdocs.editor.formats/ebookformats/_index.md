---
title: EBookFormats
second_title: GroupDocs.Editor for Java API Reference
description: Encapsulates all eBook formats.
type: docs
weight: 10
url: /java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Encapsulates all eBook formats. Includes the following file types: [Mobi](../../com.groupdocs.editor.formats/ebookformats\#Mobi), [Epub](../../com.groupdocs.editor.formats/ebookformats\#Epub) Learn more about Mobi format [here][], and about ePub format [here][here 1].


[here]: https://docs.fileformat.com/ebook/mobi/
[here 1]: https://docs.fileformat.com/ebook/epub/
## Fields

| Field | Description |
| --- | --- |
| [Mobi](#Mobi) | MOBI is the name given to the format developed for the MobiPocket Reader. |
| [Epub](#Epub) | Electronic Publication (IDPF ePub) format is an e-book file format that provides a standard digital publication format for publishers and consumers. |
| [Azw3](#Azw3) | AZW3, also known as Kindle Format 8 (KF8), is the modified version of the AZW ebook digital file format developed for Amazon Kindle devices. |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets an enumerable collection of all [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Retrieves an instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) that has the specified file extension. |
| [fromString(String extension)](#fromString-java.lang.String-) | Converts a string representing a file extension to a [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object. |
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI is the name given to the format developed for the MobiPocket Reader. Also called PRC, AZW. It is currently used by Amazon with a slightly different DRM scheme and called AZW. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/ebook/mobi/

### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (IDPF ePub) format is an e-book file format that provides a standard digital publication format for publishers and consumers. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/ebook/epub/

### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, also known as Kindle Format 8 (KF8), is the modified version of the AZW ebook digital file format developed for Amazon Kindle devices. The format is an enhancement to older AZW files. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/ebook/azw3/

### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Gets an enumerable collection of all [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).

Value: An  IEnumerable\{EBookFormats\}  containing all instances of [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).

**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Retrieves an instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) that has the specified file extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension of the document format. |

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.
### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Converts a string representing a file extension to a [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension to convert. If the extension contains multiple periods, the part after the last period is used. |

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.
