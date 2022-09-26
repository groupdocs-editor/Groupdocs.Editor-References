---
title: DelimitedTextSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Contains options for generating and saving text-based Spreadsheet documents CSV Tab-based etc. that use a separator delimiter
type: docs
weight: 11
url: /java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Contains options for generating and saving text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter)

--------------------

https://en.wikipedia.org/wiki/Delimiter-separated\_values
## Constructors

| Constructor | Description |
| --- | --- |
| [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Creates an instance of options class for delimited text with mandatory separator (delimiter) |
## Methods

| Method | Description |
| --- | --- |
| [getSeparator()](#getSeparator--) | Allows to specify a string separator (delimiter) for text-based Spreadsheet documents |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Allows to specify a string separator (delimiter) for text-based Spreadsheet documents |
| [getEncoding()](#getEncoding--) | Allows to set an encoding for the text-based Spreadsheet document. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Allows to set an encoding for the text-based Spreadsheet document. |
| [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Indicates whether leading blank rows and columns should be trimmed like what MS Excel does |
| [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Indicates whether leading blank rows and columns should be trimmed like what MS Excel does |
| [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Indicates whether separators should be output for blank row. |
| [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Indicates whether separators should be output for blank row. |
### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Creates an instance of options class for delimited text with mandatory separator (delimiter)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| separator | java.lang.String | String separator (delimiter) for text-based Spreadsheet documents |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Allows to specify a string separator (delimiter) for text-based Spreadsheet documents

**Returns:**
java.lang.String - 
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Allows to specify a string separator (delimiter) for text-based Spreadsheet documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Allows to set an encoding for the text-based Spreadsheet document. By default (and if not specified) is UTF8.

**Returns:**
java.nio.charset.Charset - 
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Allows to set an encoding for the text-based Spreadsheet document. By default (and if not specified) is UTF8.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Indicates whether leading blank rows and columns should be trimmed like what MS Excel does

**Returns:**
boolean - 
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Indicates whether leading blank rows and columns should be trimmed like what MS Excel does

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Indicates whether separators should be output for blank row. Default value is false which means the content for blank row will be empty.

**Returns:**
boolean - 
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Indicates whether separators should be output for blank row. Default value is false which means the content for blank row will be empty.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

