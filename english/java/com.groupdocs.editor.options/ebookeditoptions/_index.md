---
title: EbookEditOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify and adjust custom options for editing E-book documents in all supported formats ePub MOBI and AZW3.
type: docs
weight: 12
url: /java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Allows to specify and adjust custom options for editing E-book documents in all supported formats: ePub, MOBI, and AZW3.

--------------------

Supported E-book formats:

1.  
2.  
3.  
## Constructors

| Constructor | Description |
| --- | --- |
| [EbookEditOptions()](#EbookEditOptions--) | Initializes a new instance of the [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) class, where all options are set to their default values |
| [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Initializes a new instance of the [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) class with specified pagination mode |
## Methods

| Method | Description |
| --- | --- |
| [getEnablePagination()](#getEnablePagination--) | Allows to enable or disable pagination in the resultant HTML document. |
| [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Allows to enable or disable pagination in the resultant HTML document. |
| [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. |
| [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. |
| [cloneToWordProcessing()](#cloneToWordProcessing--) |  |
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Initializes a new instance of the [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) class, where all options are set to their default values

### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Initializes a new instance of the [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) class with specified pagination mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enablePagination | boolean | Enables ( true ) or disables ( false ) pagination of the e-book content in the resultant HTML document. By default is disabled ( false ). |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled ( false ).

--------------------

In its essence most of e-book formats internally is a flow format like Office Open XML, where content is a solid and is splitted onto chapters but not the pages. However, it contains some page-specific info like the page numbers, footnotes, heraders/footers and so on. Some e-book readers perform a splitting of the e-book content onto pages, while others (especially mobile) \\u2014 not. This option allows to control how the e-book content should be represented in HTML/CSS while editing \\u2014 in the float ( false ) or paged ( true ) view.

**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled ( false ).

--------------------

In its essence most of e-book formats internally is a flow format like Office Open XML, where content is a solid and is splitted onto chapters but not the pages. However, it contains some page-specific info like the page numbers, footnotes, heraders/footers and so on. Some e-book readers perform a splitting of the e-book content onto pages, while others (especially mobile) \\u2014 not. This option allows to control how the e-book content should be represented in HTML/CSS while editing \\u2014 in the float ( false ) or paged ( true ) view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. This option may be useful for roundtrip conversion of the multi-language documents. By default it is disabled ( false ).

**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. This option may be useful for roundtrip conversion of the multi-language documents. By default it is disabled ( false ).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### cloneToWordProcessing() {#cloneToWordProcessing--}
```
public final WordProcessingEditOptions cloneToWordProcessing()
```




**Returns:**
[WordProcessingEditOptions](../../com.groupdocs.editor.options/wordprocessingeditoptions)
