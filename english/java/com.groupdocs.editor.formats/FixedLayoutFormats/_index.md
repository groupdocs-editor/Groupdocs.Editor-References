---
title: FixedLayoutFormats
second_title: GroupDocs.Editor for Java API Reference
description: Encapsulates all fixed-layout also know as fixed-page formats which includes PDF and XPS this does not include raster images
type: docs
weight: 12
url: /java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Encapsulates all fixed-layout (also know as "fixed-page") formats, which includes PDF and XPS (this does not include raster images)

--------------------

Various document viewing or publishing applications allow users to open (Adobe Acrobat, XPS Viewer), and sometimes edit (Adobe InDesign) documents of specific formats. These applications typically produce so-called \\u201cfixed-page\\u201d format documents. Such a document format describes precisely where a document\\u2019s content is placed on every page. Internally, the PDF or XPS format contains a description of every page, as well as drawing instructions, specifying the layout of the content on the page. This is similar to image formats, describing where the content is shown either in raster or vector form.
## Fields

| Field | Description |
| --- | --- |
| [Pdf](#Pdf) | Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets an enumerable collection of all [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Retrieves an instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) that has the specified file extension. |
| [fromString(String extension)](#fromString-java.lang.String-) | Converts a string representing a file extension to a [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object. |
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/pdf/

### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Gets an enumerable collection of all [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).

Value: An  IEnumerable\{FixedLayoutFormats\}  containing all instances of [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).

**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Retrieves an instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) that has the specified file extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension of the document format. |

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.
### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Converts a string representing a file extension to a [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension to convert. If the extension contains multiple periods, the part after the last period is used. |

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.
