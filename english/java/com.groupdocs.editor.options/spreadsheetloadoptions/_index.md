---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Editor for Java API Reference
description: Contains options for loading binary Spreadsheet Cells Excel-compatible documents like XLSX ODS etc. into Editor class
type: docs
weight: 25
url: /java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Contains options for loading binary Spreadsheet (Cells, Excel-compatible) documents like XLS(X), ODS etc. into Editor class
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Default parameterless constructor - all parameters have default values |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Allows to specify, modify and obtain the password, which will be used for opening the Spreadsheet document, if it is encoded. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify and obtain the password, which will be used for opening the Spreadsheet document, if it is encoded. |
| [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. |
| [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Enables memory optimization mechanisms during input document processing, which may degrade performance in some special cases, but on the other hand decrease memory usage. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Default parameterless constructor - all parameters have default values

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify and obtain the password, which will be used for opening the Spreadsheet document, if it is encoded. Set to NULL or empty string in order to not use the password (default value).

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify and obtain the password, which will be used for opening the Spreadsheet document, if it is encoded. Set to NULL or empty string in order to not use the password (default value).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

