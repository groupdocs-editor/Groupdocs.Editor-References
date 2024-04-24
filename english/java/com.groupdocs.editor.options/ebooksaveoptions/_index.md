---
title: EbookSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving the document in all supportable e-Book formats ePub MOBI and AZW3.
type: docs
weight: 13
url: /java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving the document in all supportable e-Book formats: ePub, MOBI, and AZW3.

--------------------

Supported E-book formats:

1.  [ePub][] (Electronic Publication)
2.  [MOBI][] (MobiPocket)
3.  [AZW3][] (Kindle Format 8t)


[ePub]: https://docs.fileformat.com/ebook/epub/
[MOBI]: https://docs.fileformat.com/ebook/mobi/
[AZW3]: https://docs.fileformat.com/ebook/azw3/
## Constructors

| Constructor | Description |
| --- | --- |
| [EbookSaveOptions()](#EbookSaveOptions--) | This parameterless constructor creates a new instance of EbookSaveOptions with ePub output format (can be modified then through  OutputFormat (\#getOutputFormat.getOutputFormat/\#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property) |
| [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Creates a new instance of [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) with specified mandatory e-Book output format, while all other parameters are default |
## Methods

| Method | Description |
| --- | --- |
| [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Specifies the maximum level of headings at which to split the e-Book file. |
| [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Specifies the maximum level of headings at which to split the e-Book file. |
| [getExportDocumentProperties()](#getExportDocumentProperties--) | Specifies whether to export built-in and custom document properties in resultant file. |
| [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Specifies whether to export built-in and custom document properties in resultant file. |
| [getOutputFormat()](#getOutputFormat--) | Specifies the format of the resultant e-Book file: IDPF ePub, MOBI, or AZW3. |
| [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Specifies the format of the resultant e-Book file: IDPF ePub, MOBI, or AZW3. |
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


This parameterless constructor creates a new instance of EbookSaveOptions with ePub output format (can be modified then through  OutputFormat (\#getOutputFormat.getOutputFormat/\#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)

### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Creates a new instance of [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) with specified mandatory e-Book output format, while all other parameters are default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | andatory output format, in which the e-Book should be saved |

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Specifies the maximum level of headings at which to split the e-Book file. Default value is  2 . Setting it to  0  will disable splitting, so all content of the e-Book will be incorporarted into a single package inside the resultant file.

--------------------

When this property is set to a value from 1 to 9, the document will be split at paragraphs formatted using  **Heading 1** ,  **Heading 2**  ,  **Heading 3**  etc. styles up to the specified heading level.

By default, only  **Heading 1**  and  **Heading 2**  paragraphs cause the document to be split. Setting this property to zero (or lesser then zero) will cause the document not to be split at heading paragraphs at all.

**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Specifies the maximum level of headings at which to split the e-Book file. Default value is  2 . Setting it to  0  will disable splitting, so all content of the e-Book will be incorporarted into a single package inside the resultant file.

--------------------

When this property is set to a value from 1 to 9, the document will be split at paragraphs formatted using  **Heading 1** ,  **Heading 2**  ,  **Heading 3**  etc. styles up to the specified heading level.

By default, only  **Heading 1**  and  **Heading 2**  paragraphs cause the document to be split. Setting this property to zero (or lesser then zero) will cause the document not to be split at heading paragraphs at all.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Specifies whether to export built-in and custom document properties in resultant file. Default value is  false .

**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Specifies whether to export built-in and custom document properties in resultant file. Default value is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Specifies the format of the resultant e-Book file: IDPF ePub, MOBI, or AZW3.

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Specifies the format of the resultant e-Book file: IDPF ePub, MOBI, or AZW3.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

