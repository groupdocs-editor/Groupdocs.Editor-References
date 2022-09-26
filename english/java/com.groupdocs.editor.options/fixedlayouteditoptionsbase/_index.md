---
title: FixedLayoutEditOptionsBase
second_title: GroupDocs.Editor for Java API Reference
description: Base abstract class for the options for all documents of fixed-layout formats like PDF and XPS
type: docs
weight: 14
url: /java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Base abstract class for the options for all documents of fixed-layout formats like PDF and XPS
## Constructors

| Constructor | Description |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSkipImages()](#getSkipImages--) | Gets or sets the flag indicating whether images must be skipped while converting input fixed-layout document to the resultant HTML. |
| [setSkipImages(boolean value)](#setSkipImages-boolean-) | Gets or sets the flag indicating whether images must be skipped while converting input fixed-layout document to the resultant HTML. |
| [getPages()](#getPages--) | Allows to set a page range to process. |
| [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Allows to set a page range to process. |
| [getEnablePagination()](#getEnablePagination--) | Allows to enable (true) or disable (false) pagination in the resultant HTML document. |
| [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Allows to enable (true) or disable (false) pagination in the resultant HTML document. |
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Gets or sets the flag indicating whether images must be skipped while converting input fixed-layout document to the resultant HTML. Default is false - images are preserved.

**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Gets or sets the flag indicating whether images must be skipped while converting input fixed-layout document to the resultant HTML. Default is false - images are preserved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Allows to set a page range to process. By default all pages of a fixed-layout document are processed.

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Allows to set a page range to process. By default all pages of a fixed-layout document are processed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Allows to enable (true) or disable (false) pagination in the resultant HTML document. By default is disabled (false).

--------------------

Fixed-layout format documents (PDF and XPS in particular) in their essence are strictly paged, their content has a fixed layout and divided onto pages. But resultant editable HTML can be represented in either pageless or paginal view.

**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Allows to enable (true) or disable (false) pagination in the resultant HTML document. By default is disabled (false).

--------------------

Fixed-layout format documents (PDF and XPS in particular) in their essence are strictly paged, their content has a fixed layout and divided onto pages. But resultant editable HTML can be represented in either pageless or paginal view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

