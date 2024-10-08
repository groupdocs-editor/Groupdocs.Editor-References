---
title: WordProcessingProtection
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Encapsulates document protection options for the WordProcessing document which is generated from HTML
type: docs
weight: 44
url: /nodejs-java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Encapsulates document protection options for the WordProcessing document, which is generated from HTML
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingProtection()](#WordProcessingProtection--) | Parameterless constructor - all parameters have default values |
| [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Allows to set all parameters during class instantiation |
## Methods

| Method | Description |
| --- | --- |
| [getProtectionType()](#getProtectionType--) | Allows to set a protection type of the document. |
| [setProtectionType(int value)](#setProtectionType-int-) | Allows to set a protection type of the document. |
| [getPassword()](#getPassword--) | The password to protect the document with. |
| [setPassword(String value)](#setPassword-java.lang.String-) | The password to protect the document with. |
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Parameterless constructor - all parameters have default values

### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Allows to set all parameters during class instantiation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| protectionType | int | Set the protection type of the document |
| password | java.lang.String | Set the protection password |

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Allows to set a protection type of the document. By default is set to not protect the document at all.

**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Allows to set a protection type of the document. By default is set to not protect the document at all.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


The password to protect the document with. If null or empty string - the protection will not be applied to the document.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


The password to protect the document with. If null or empty string - the protection will not be applied to the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
