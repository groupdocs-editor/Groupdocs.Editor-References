---
title: InvalidImageFormatException
second_title: GroupDocs.Editor for Java API Reference
description: The exception that is thrown when trying to open load save or process somehow else some content that presumably is an image raster or vector but actually is an image of unexpected type or not an image at all.
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

The exception that is thrown when trying to open, load, save or process somehow else some content, that presumably is an image (raster or vector), but actually is an image of unexpected type or not an image at all.
## Constructors

| Constructor | Description |
| --- | --- |
| [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Creates new instance of InvalidImageFormatException with specified error message |
| [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Creates new instance of InvalidImageFormatException with specified error message and a reference to the inner exception that is the cause of this exception |
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Creates new instance of InvalidImageFormatException with specified error message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Textual message, that describes the error, can be null or empty |

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Creates new instance of InvalidImageFormatException with specified error message and a reference to the inner exception that is the cause of this exception

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Textual message, that describes the error, can be null or empty |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception, or a null reference if no inner exception is specified. |

