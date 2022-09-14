---
title: WordProcessingLoadOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Contains options for loading WordProcessing Word-compatible documents like
 DOCX RTF ODT etc.
type: docs
weight: 43
url: /java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Contains options for loading WordProcessing (Word-compatible) documents like DOC(X), RTF, ODT etc. into Editor class
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Allows to specify, modify and obtain the password, which will be used for opening WordProcessing document, if it is encoded. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify and obtain the password, which will be used for opening WordProcessing document, if it is encoded. |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify and obtain the password, which will be used for opening WordProcessing document, if it is encoded. Set to NULL or empty string in order to not use the password (default value).

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify and obtain the password, which will be used for opening WordProcessing document, if it is encoded. Set to NULL or empty string in order to not use the password (default value).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

