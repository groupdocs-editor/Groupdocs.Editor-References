---
title: InvalidFontFormatException
second_title: GroupDocs.Editor for Java API Reference
description: The exception that is thrown when trying to open load save or process somehow else some content that presumably is a font of supported known format but actually is a font of unsupported or unexpected format or not a font at all.
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

The exception that is thrown when trying to open, load, save or process somehow else some content, that presumably is a font of supported (known) format, but actually is a font of unsupported or unexpected format or not a font at all.
## Constructors

| Constructor | Description |
| --- | --- |
| [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Creates new instance of  with specified error message |
| [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Creates new instance of @see "InvalidFontFormatException" with specified error message and a reference to the inner exception that is the cause of this exception |
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Creates new instance of  with specified error message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Textual message, that describes the error, can be null or empty |

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Creates new instance of @see "InvalidFontFormatException" with specified error message and a reference to the inner exception that is the cause of this exception

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Textual message, that describes the error, can be null or empty |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception, or a null reference if no inner exception is specified. |

