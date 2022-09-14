---
title: MobiEditOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Allows to specify custom options for editing documents in MOBI MobiPocket
 format.
type: docs
weight: 25
url: /java/com.groupdocs.editor.options/mobieditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MobiEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents in MOBI (MobiPocket) format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MobiEditOptions()](#MobiEditOptions--) | Creates and returns a new instance of the MobiEditOptions class, where all options are set to their default values |
| [MobiEditOptions(boolean enablePagination)](#MobiEditOptions-boolean-) | Creates and returns a new instance of the MobiEditOptions class with specified pagination and default all other options |
## Methods

| Method | Description |
| --- | --- |
| [getEnablePagination()](#getEnablePagination--) | Allows to enable or disable pagination in the resultant HTML document. |
| [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Allows to enable or disable pagination in the resultant HTML document. |
| [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. |
| [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. |
| [cloneToWordProcessing()](#cloneToWordProcessing--) |  |
### MobiEditOptions() {#MobiEditOptions--}
```
public MobiEditOptions()
```


Creates and returns a new instance of the MobiEditOptions class, where all options are set to their default values

### MobiEditOptions(boolean enablePagination) {#MobiEditOptions-boolean-}
```
public MobiEditOptions(boolean enablePagination)
```


Creates and returns a new instance of the MobiEditOptions class with specified pagination and default all other options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enablePagination | boolean | Pagination flag, that enables HTML output, adjusted for paged mode |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled (false).

**Returns:**
boolean - 
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled (false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. This option may be useful for roundtrip conversion of the multi-language documents. By default it is disabled (false).

**Returns:**
boolean - 
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. This option may be useful for roundtrip conversion of the multi-language documents. By default it is disabled (false).

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
