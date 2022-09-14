---
title: PdfLoadOptions
second_title: GroupDocs.Editor for Java API Reference
description: Contains options for loading PDF documents into Editor class
type: docs
weight: 29
url: /java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Contains options for loading PDF documents into Editor class
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Allows to specify, modify and obtain the password, which will be used for opening a PDF document, if it is encoded. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify and obtain the password, which will be used for opening a PDF document, if it is encoded. |
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify and obtain the password, which will be used for opening a PDF document, if it is encoded. Set to NULL or empty string in order to not use the password (default value).

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify and obtain the password, which will be used for opening a PDF document, if it is encoded. Set to NULL or empty string in order to not use the password (default value).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

