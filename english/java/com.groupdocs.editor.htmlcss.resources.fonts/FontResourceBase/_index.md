---
title: FontResourceBase
second_title: GroupDocs.Editor for Java API Reference
description: Base class for any supported font type as a resource for the HTML document with all its properties
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

Base class for any supported font type as a resource for the HTML document with all its properties
## Constructors

| Constructor | Description |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) | Event, which occurs when this font is disposed |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns name of this font resource. |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Returns correct filename of this font resource, which consists of name and extension. |
| [getByteContent()](#getByteContent--) | Returns content of this font as byte stream |
| [getTextContent()](#getTextContent--) | Returns content of this font as base64-encoded string. |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves this font to the specified file |
| [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Checks this instance with specified HTML resource on reference equality |
| [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | Checks this instance with specified font resource on reference equality |
| [dispose()](#dispose--) | Disposes this font resource, disposing its content and making most methods and properties non-working |
| [isDisposed()](#isDisposed--) | Determines whether this font is disposed or not |
| [getType()](#getType--) | In implementing type should return information about type of specific font resource as an instance of specific FontType type, which encapsulates all type-specific info |
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


Event, which occurs when this font is disposed

### getName() {#getName--}
```
public final String getName()
```


Returns name of this font resource. Usually doesn't contain filename extension and theoretically can differ from filename.

**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Returns correct filename of this font resource, which consists of name and extension. Theoretically can differ from the name.

**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Returns content of this font as byte stream

**Returns:**
java.io.InputStream - 
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Returns content of this font as base64-encoded string. This value is cached after first invoke.

**Returns:**
java.lang.String - 
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Saves this font to the specified file

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
### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


Checks this instance with specified font resource on reference equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | Other inheritor of FontResourceBase abstract class |

**Returns:**
boolean - True if are equal, false if are unequal
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes this font resource, disposing its content and making most methods and properties non-working

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determines whether this font is disposed or not

**Returns:**
boolean - 
### getType() {#getType--}
```
public abstract FontType getType()
```


In implementing type should return information about type of specific font resource as an instance of specific FontType type, which encapsulates all type-specific info

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
