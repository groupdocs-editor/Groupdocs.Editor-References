---
title: PageRange
second_title: GroupDocs.Editor for Java API Reference
description: Encapsulates one page range which can have open or closed bounds.
type: docs
weight: 24
url: /java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Encapsulates one page range, which can have open or closed bounds. By default is "fully open" - it includes all existing pages. Page numbering starts from 1, not from 0.

--------------------

Immutable struct, that encapsulates a page range, which is not related to any specific document, and can represent a page range for any document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Fields

| Field | Description |
| --- | --- |
| [AllPages](#AllPages) | Represents all existing pages of a document. |
## Methods

| Method | Description |
| --- | --- |
| [getStartNumber()](#getStartNumber--) | Inclusive start page number, from which this page range starts. |
| [getEndNumber()](#getEndNumber--) | Exclusive end page number, until which this page range continues and on which is stops exclusively. |
| [getCount()](#getCount--) | Numbers of pages within range. |
| [isDefault()](#isDefault--) | Indicates whether this instance represents a default "fully open" page range i.e. |
| [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Detects whether this instance of PageRange is equal to specified |
| [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Creates a page range, that starts from the first page and has specified amount of pages |
| [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Creates a page range, that starts from the specified page number and continues till the end of the document |
| [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Creates a page range, that starts from the specified page number and has specified amount of pages, or unlimited page count (till the end) |
| [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Creates a page range, that starts from the specified page number (inclusively) and continues until the specified page number (exclusively) |
| [convertToAspose()](#convertToAspose--) |  |
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Represents all existing pages of a document. Default value.

### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Inclusive start page number, from which this page range starts. If 1 - page range starts from the first page of a document

**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Exclusive end page number, until which this page range continues and on which is stops exclusively. If 0 - page range spreads until end of the document

**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Numbers of pages within range. If 0 - page range spreads until end of the document no matter how much pages it consists of

**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this instance represents a default "fully open" page range i.e. it consists all pages of a document

**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Detects whether this instance of PageRange is equal to specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Other PageRange instance to check on equality |

**Returns:**
boolean - true is are equal; false if are unequal
### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Creates a page range, that starts from the first page and has specified amount of pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageCount | int | Number of pages, must be strictly bigger than zero |

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance
### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Creates a page range, that starts from the specified page number and continues till the end of the document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPageNumber | int | Page number, from which page range starts, inclusively. Page numbers are 1-based, so must be strictly bigger than zero |

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance
### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Creates a page range, that starts from the specified page number and has specified amount of pages, or unlimited page count (till the end)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPageNumber | int | Page number, from which page range starts, inclusively. Page numbers are 1-based, so must be strictly bigger than zero |
| pageCount | int | Number of pages, must be strictly bigger than zero. If zero - this means all pages till the end of a document |

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance
### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Creates a page range, that starts from the specified page number (inclusively) and continues until the specified page number (exclusively)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPageNumber | int | Page number, from which page range starts, inclusively. Page numbers are 1-based, so must be strictly bigger than zero |
| endPageNumber | int | Page number, until which page range continues, exclusively. Page numbers are 1-based, so must be strictly bigger than zero, and also must be strictly greater than  startPageNumber  |

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
### convertToAspose() {#convertToAspose--}
```
public final System.Collections.Generic.KeyValuePair<Integer,Integer> convertToAspose()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.Integer,java.lang.Integer>
