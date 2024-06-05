---
title: IHtmlResource
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents one instance of the unknown HTML resource raster or vector image stylesheet font text resource CSS XML etc.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Represents one instance of the unknown HTML resource (raster or vector image, stylesheet, font, text resource (CSS, XML) etc.)
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Name of the HTML resource |
| [getFilenameWithExtension()](#getFilenameWithExtension--) | Correct filename of the specified resource with appropriate file extension |
| [getType()](#getType--) | Type of the HTML resource |
| [getByteContent()](#getByteContent--) | Content of the HTML resource in a form of a byte stream |
| [getTextContent()](#getTextContent--) | Content of the HTML resource in a form of a base64-encoded text string for binary resources or a simple text for textual resources |
| [save(String fullPathToFile)](#save-java.lang.String-) | Saves a current resource to the specified file |
### getName() {#getName--}
```
public abstract String getName()
```


Name of the HTML resource

**Returns:**
java.lang.String - 
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Correct filename of the specified resource with appropriate file extension

**Returns:**
java.lang.String - 
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Type of the HTML resource

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Content of the HTML resource in a form of a byte stream

**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Content of the HTML resource in a form of a base64-encoded text string for binary resources or a simple text for textual resources

**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Saves a current resource to the specified file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fullPathToFile | java.lang.String | Full path to the file, which will be created or rewritten with the content of a current resource |

