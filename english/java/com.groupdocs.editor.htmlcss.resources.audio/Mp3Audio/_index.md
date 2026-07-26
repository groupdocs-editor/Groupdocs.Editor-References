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
| [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | Creates new Mp3Audio class from MP3 content, represented as byte stream, and with specified name
 |
## Methods

| Method | Description |
| --- | --- |
| [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | Checks whether specified stream is a valid MP3 content
 |
| [getName()](#getName--) | Returns name of this MP3 content.
 |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Returns correct filename of this MP3 content, which consists of name and extension.
 |
| [getType()](#getType--) | Returns a AudioFormat.Mp3 (also satisfies IHtmlResource.getFormat() via covariant return)
 |
| [getByteContent()](#getByteContent--) | Returns content of this font as byte stream
 |
| [getByteContentInternal()](#getByteContentInternal--) | Returns content of this MP3 audio resource as byte stream with original position
 |
| [getTextContent()](#getTextContent--) | Returns content of this MP3 resource as base64-encoded string.
 |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this MP3 resource to the specified file
 |
| [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Checks this instance with specified HTML resource on reference equality
 |
| [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | Checks this instance with specified font resource on reference equality
 |
| [dispose()](#dispose--) | Disposes this MP3 resource, disposing its content and making most methods and properties non-working
 |
| [isDisposed()](#isDisposed--) | Determines whether this MP3 content is disposed or not
 |
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


Creates new Mp3Audio class from MP3 content, represented as byte stream, and with specified name


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the MP3 content. Cannot be null, empty or whitespaces.
 |
| binaryContent | com.aspose.ms.System.IO.Stream | Content as byte stream. Reading begins from original position. Cannot be null. Should be readable and seekable. If this instance will be disposed, this stream will be disposed too.
 |
| leaveOpen | boolean | Determines whether or not dispose specified stream when Mp3Audio instance is disposed
 |

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


Checks whether specified stream is a valid MP3 content


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryContent | com.aspose.ms.System.IO.Stream | Byte stream, that presumably contains a MP3 content
 |

**Returns:**
boolean - True if specified stream contains valid MP3 content, false otherwise

### getName() {#getName--}
```
public String getName()
```


Returns name of this MP3 content. Usually doesn't contain filename extension and theoretically can differ from filename.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


Returns correct filename of this MP3 content, which consists of name and extension. Theoretically can differ from the name.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


Returns a AudioFormat.Mp3 (also satisfies IHtmlResource.getFormat() via covariant return)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returns content of this font as byte stream


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


Returns content of this MP3 audio resource as byte stream with original position


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Returns content of this MP3 resource as base64-encoded string. This value is cached after first invoke.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Saves this MP3 resource to the specified file


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created or rewritten
 |

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


Checks this instance with specified HTML resource on reference equality


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Other inheritor of IHtmlResource interface
 |

**Returns:**
boolean - True if are equal, false if are unequal

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


Checks this instance with specified font resource on reference equality


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Other instance of Mp3Audio class
 |

**Returns:**
boolean - True if are equal, false if are unequal

### dispose() {#dispose--}
```
public void dispose()
```


Disposes this MP3 resource, disposing its content and making most methods and properties non-working


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


Determines whether this MP3 content is disposed or not


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

