---
title: EmailDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one email document of any supported email format
type: docs
weight: 10
url: /java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Represents metadata of one email document of any supported email format
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this email document |
| [getPageCount()](#getPageCount--) | Always returs 1, because email documents don't have paged view |
| [getSize()](#getSize--) | Returns size in bytes of this email document |
| [isEncrypted()](#isEncrypted--) | Because email documents cannot be encrypted with password, this property always returns 'false' |
| [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Determines whether this instance is equal to the other specified EmailDocumentInfo instance |
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


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
