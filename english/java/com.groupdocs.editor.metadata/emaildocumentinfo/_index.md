---
title: EmailDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description:  Represents metadata of one email document of any supported email format
type: docs
weight: 17
url: /java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo), com.aspose.ms.System.IEquatable
```
public class EmailDocumentInfo extends Struct<EmailDocumentInfo> implements IDocumentInfo, System.IEquatable<EmailDocumentInfo>
```

Represents metadata of one email document of any supported email format
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
| [EmailDocumentInfo(EmailFormats format, long size)](#EmailDocumentInfo-com.groupdocs.editor.formats.EmailFormats-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this email document |
| [getPageCount()](#getPageCount--) | Always returs 1, because email documents don't have paged view |
| [getSize()](#getSize--) | Returns size in bytes of this email document |
| [isEncrypted()](#isEncrypted--) | Because email documents cannot be encrypted with password, this property always returns 'false' |
| [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Determines whether this instance is equal to the other specified EmailDocumentInfo instance |
| [CloneTo(EmailDocumentInfo that)](#CloneTo-com.groupdocs.editor.metadata.EmailDocumentInfo-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(EmailDocumentInfo obj1, EmailDocumentInfo obj2)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-com.groupdocs.editor.metadata.EmailDocumentInfo-) |  |
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### EmailDocumentInfo(EmailFormats format, long size) {#EmailDocumentInfo-com.groupdocs.editor.formats.EmailFormats-long-}
```
public EmailDocumentInfo(EmailFormats format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [EmailFormats](../../com.groupdocs.editor.formats/emailformats) |  |
| size | long |  |

### getFormat() {#getFormat--}
```
public final EmailFormats getFormat()
```


Returns a format of this email document

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Always returs 1, because email documents don't have paged view

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this email document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Because email documents cannot be encrypted with password, this property always returns 'false'

**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Determines whether this instance is equal to the other specified EmailDocumentInfo instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Other EmailDocumentInfo instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### CloneTo(EmailDocumentInfo that) {#CloneTo-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public void CloneTo(EmailDocumentInfo that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) |  |

### Clone() {#Clone--}
```
public EmailDocumentInfo Clone()
```




**Returns:**
[EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### equals(EmailDocumentInfo obj1, EmailDocumentInfo obj2) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public static boolean equals(EmailDocumentInfo obj1, EmailDocumentInfo obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) |  |
| obj2 | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) |  |

**Returns:**
boolean
