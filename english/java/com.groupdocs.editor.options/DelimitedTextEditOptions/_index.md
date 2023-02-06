---
title: DelimitedTextEditOptions
second_title: GroupDocs.Editor for Java API Reference
description: Options for loading text-based Spreadsheet documents CSV Tab-based etc. that use a separator delimiter
type: docs
weight: 11
url: /java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Options for loading text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter)

--------------------

https://en.wikipedia.org/wiki/Delimiter-separated\_values
## Constructors

| Constructor | Description |
| --- | --- |
| [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Creates an instance of options class for delimited text with mandatory separator (delimiter) |
## Methods

| Method | Description |
| --- | --- |
| [getSeparator()](#getSeparator--) | Allows to specify a string separator (delimiter) for text-based Spreadsheet documents |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Allows to specify a string separator (delimiter) for text-based Spreadsheet documents |
| [getConvertDateTimeData()](#getConvertDateTimeData--) | Gets or sets a value that indicates whether the string in text-based document is converted to the date data. |
| [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Gets or sets a value that indicates whether the string in text-based document is converted to the date data. |
| [getConvertNumericData()](#getConvertNumericData--) | Gets or sets a value that indicates whether the string in text-based document is converted to numeric data. |
| [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Gets or sets a value that indicates whether the string in text-based document is converted to numeric data. |
| [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Defines whether consecutive delimiters should be treated as one. |
| [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Defines whether consecutive delimiters should be treated as one. |
| [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. |
| [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. |
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Creates an instance of options class for delimited text with mandatory separator (delimiter)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| separator | java.lang.String | Mandatory separator (delimiter), that cannot be NULL or empty |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Allows to specify a string separator (delimiter) for text-based Spreadsheet documents

**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Allows to specify a string separator (delimiter) for text-based Spreadsheet documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Gets or sets a value that indicates whether the string in text-based document is converted to the date data. Default is false.

**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Gets or sets a value that indicates whether the string in text-based document is converted to the date data. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Gets or sets a value that indicates whether the string in text-based document is converted to numeric data. Default is false.

**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Gets or sets a value that indicates whether the string in text-based document is converted to numeric data. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Defines whether consecutive delimiters should be treated as one. By default is false.

**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Defines whether consecutive delimiters should be treated as one. By default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. Useful when processing huge documents and facing OutOfMemoryException. Default is false (memory optimization is disabled for the sake of better performance).

**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. Useful when processing huge documents and facing OutOfMemoryException. Default is false (memory optimization is disabled for the sake of better performance).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

