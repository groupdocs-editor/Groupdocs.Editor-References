---
title: Mp3Audio
second_title: GroupDocs.Editor for Java API Reference
description: Represents one audio resource of arbitrary format
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

Represents one audio resource of arbitrary format
## Constructors

| Constructor | Description |
| --- | --- |
| [Mp3Audio(String name, InputStream binaryContent)](#Mp3Audio-java.lang.String-java.io.InputStream-) | Creates new Mp3Audio class from MP3 content, represented as byte stream, and with specified name |
| [Mp3Audio(String name, System.IO.Stream binaryContent)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methods

| Method | Description |
| --- | --- |
| [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Checks whether specified stream is a valid MP3 content |
| [getName()](#getName--) | Returns name of this MP3 content. |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Returns correct filename of this MP3 content, which consists of name and extension. |
| [getType_Rename_Namesake()](#getType-Rename-Namesake--) |  |
| [getType()](#getType--) | Returns a AudioType.Mp3 |
| [getByteContent()](#getByteContent--) | Returns content of this font as byte stream |
| [getByteContentInternal()](#getByteContentInternal--) |  |
| [getTextContent()](#getTextContent--) | Returns content of this MP3 resource as base64-encoded string. |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this MP3 resource to the specified file |
| [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Checks this instance with specified HTML resource on reference equality |
| [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Checks this instance with specified font resource on reference equality |
| [dispose()](#dispose--) | Disposes this MP3 resource, disposing its content and making most methods and properties non-working |
| [isDisposed()](#isDisposed--) | Determines whether this MP3 content is disposed or not |
### Mp3Audio(String name, InputStream binaryContent) {#Mp3Audio-java.lang.String-java.io.InputStream-}
```
public Mp3Audio(String name, InputStream binaryContent)
```


Creates new Mp3Audio class from MP3 content, represented as byte stream, and with specified name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the MP3 content. Cannot be null, empty or whitespaces. |
| binaryContent | java.io.InputStream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too. |

### Mp3Audio(String name, System.IO.Stream binaryContent) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Checks whether specified stream is a valid MP3 content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | java.io.InputStream | Byte stream, that presumably contains a MP3 content |

**Returns:**
boolean - True if specified stream contains valid MP3 content, false otherwise
### getName() {#getName--}
```
public final String getName()
```


Returns name of this MP3 content. Usually doesn't contain filename extension and theoretically can differ from filename.

**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returns correct filename of this MP3 content, which consists of name and extension. Theoretically can differ from the name.

**Returns:**
java.lang.String
### getType_Rename_Namesake() {#getType-Rename-Namesake--}
```
public final IResourceType getType_Rename_Namesake()
```




**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
### getType() {#getType--}
```
public final AudioType getType()
```


Returns a AudioType.Mp3

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returns content of this font as byte stream

**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returns content of this MP3 resource as base64-encoded string. This value is cached after first invoke.

**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Saves this MP3 resource to the specified file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created or rewritten |

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Checks this instance with specified HTML resource on reference equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Other inheritor of IHtmlResource interface |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public final boolean equals(Mp3Audio other)
```


Checks this instance with specified font resource on reference equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Other instance of Mp3Audio class |

**Returns:**
boolean - True if are equal, false if are unequal
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes this MP3 resource, disposing its content and making most methods and properties non-working

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determines whether this MP3 content is disposed or not

**Returns:**
boolean
