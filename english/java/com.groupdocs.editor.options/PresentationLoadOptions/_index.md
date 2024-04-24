---
title: PresentationLoadOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for loading documents of all supportable Presentation formats like PPTX PPTM PPSX etc.
type: docs
weight: 31
url: /java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Allows to specify custom options for loading documents of all supportable Presentation formats like PPT(X), PPTM, PPS(X) etc.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Allows to specify, modify and obtain the password, which will be used for opening the Presentation document, if it is encoded. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify and obtain the password, which will be used for opening the Presentation document, if it is encoded. |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify and obtain the password, which will be used for opening the Presentation document, if it is encoded. Set to NULL or empty string in order to remove the password.

--------------------

By default this property has NULL value \\u2014 password is not set. If input Presentation document is password-protected, the password is mandatory and an exception will be thrown if password is not specified or is invalid. If input Presentation document is NOT password-protected, but password is set, it will be ignored.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify and obtain the password, which will be used for opening the Presentation document, if it is encoded. Set to NULL or empty string in order to remove the password.

--------------------

By default this property has NULL value \\u2014 password is not set. If input Presentation document is password-protected, the password is mandatory and an exception will be thrown if password is not specified or is invalid. If input Presentation document is NOT password-protected, but password is set, it will be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

