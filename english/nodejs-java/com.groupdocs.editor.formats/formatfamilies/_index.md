---
title: FormatFamilies
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents the different format families available in the system.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Represents the different format families available in the system.

## Fields

| Field | Description |
| --- | --- |
| [EBook](#EBook) | Represents the eBook format family.
 |
| [Email](#Email) | Represents the Email format family.
 |
| [FixedLayout](#FixedLayout) | Represents the Fixed Layout format family.
 |
| [Presentation](#Presentation) | Represents the Presentation format family.
 |
| [Spreadsheet](#Spreadsheet) | Represents the Spreadsheet format family.
 |
| [Textual](#Textual) | Represents the Textual format family.
 |
| [WordProcessing](#WordProcessing) | Represents the Word Processing format family.
 |
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Represents the eBook format family.
Learn more about Mobi format 
[here](../https://docs.fileformat.com/ebook/mobi/)
,
about AZW3 format 
[here](../https://docs.fileformat.com/ebook/azw3/)
,
and about ePub format 
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Represents the Email format family.
Learn more about emails format 
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Represents the Fixed Layout format family.
Various document viewing or publishing applications allow users to open (Adobe Acrobat, XPS Viewer), and sometimes edit (Adobe InDesign) documents of specific formats.
These applications typically produce so-called \\u201cfixed-page\\u201d format documents.
Such a document format describes precisely where a document\\u2019s content is placed on every page.
Internally, the PDF or XPS format contains a description of every page, as well as drawing instructions, specifying the layout of the content on the page.
This is similar to image formats, describing where the content is shown either in raster or vector form.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Represents the Presentation format family.
Learn more about Presentation formats 
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Represents the Spreadsheet format family.
All binary, XML and textual Spreadsheet formats (excluding all textual delimiter-based formats with separator like CSV, TSV, semicolon-delimited etc.), in which the workbook can be saved.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Represents the Textual format family.
Encapsulates all textual (text-based) formats, including markup (XML, HTML) and others.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Represents the Word Processing format family.
Learn more about Word Processing formats 
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME codes are grabbed from the given resources: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



