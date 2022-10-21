---
title: TextResourceBase
second_title: GroupDocs.Editor for Java API Reference
description: Base class for any supported text resource with text content and encoding
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

Base class for any supported text resource with text content and encoding
## Constructors

| Constructor | Description |
| --- | --- |
| [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | Creates new text resource from specified textual content with encoding |
| [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | Creates new text resource from specified byte stream and encoding |
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns name of this text resource without file extension |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Returns correct filename of this text resource, which consists of name and extension |
| [getEncoding()](#getEncoding--) | Returns encoding of this textual resource. |
| [getByteContent()](#getByteContent--) | Returns content of this text resource as byte stream with original encoding |
| [getTextContent()](#getTextContent--) | Returns content of this text resource as a standard string |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this text resource to the specified file |
| [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Checks this instance with specified on equality. |
| [dispose()](#dispose--) | Disposes this text resource, disposing its content and making most methods and properties non-working. |
| [isDisposed()](#isDisposed--) | Determines whether this text resource is disposed or not |
| [getType()](#getType--) | In implementing type should return information about type of the text resource |
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


Creates new text resource from specified textual content with encoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Mandatory name of the resource, that serves as its unique identifier. Usually is a file name. |
| textualContent | java.lang.String | Textual content of the resource, cannot be NULL or empty |
| originalEncoding | java.nio.charset.Charset | Original encoding of the resource, cannot be NULL or empty |

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


Creates new text resource from specified byte stream and encoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Mandatory name of the resource, that serves as its unique identifier. Usually is a file name. |
| binaryContent | java.io.InputStream | Binary content of a resource as a byte stream. Cannot be NULL, disposed, should be readable and seekable. |
| originalEncoding | java.nio.charset.Charset | Original encoding of the resource, cannot be NULL or empty |

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Returns name of this text resource without file extension

**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returns correct filename of this text resource, which consists of name and extension

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Returns encoding of this textual resource. Usually returns UTF-8.

**Returns:**
java.nio.charset.Charset - 
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returns content of this text resource as byte stream with original encoding

**Returns:**
java.io.InputStream - 
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returns content of this text resource as a standard string

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Saves this text resource to the specified file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created or rewritten if already exists |

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Checks this instance with specified on equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Other HTML resource of unknown type, that is also presumable TextResourceBase inheritor |

**Returns:**
boolean - Returns true if are equal, or false if are unequal
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes this text resource, disposing its content and making most methods and properties non-working. Tolerant to multiple calls.

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determines whether this text resource is disposed or not

**Returns:**
boolean - 
### getType() {#getType--}
```
public abstract TextType getType()
```


In implementing type should return information about type of the text resource

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
