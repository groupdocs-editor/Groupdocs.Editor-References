---
title: InvalidFormatException
second_title: GroupDocs.Editor for Java API Reference
description:  The exception that is thrown when user tries to open some document with
 format-specific options that are incompatible with original document format.
type: docs
weight: 15
url: /java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

The exception that is thrown when user tries to open some document with format-specific options that are incompatible with original document format.

--------------------

For example, this exception will be thrown, if try to open Spreadsheet document with WordProcessing document options.
## Constructors

| Constructor | Description |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String |  |
| inner | java.lang.RuntimeException |  |

