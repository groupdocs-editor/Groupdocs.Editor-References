---
title: FixedLayoutDocumentInfo
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents metadata of one document with fixed layout format like PDF or XPS
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Represents metadata of one document with fixed layout format like PDF or XPS
## Constructors

| Constructor | Description |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this fixed-layout format document |
| [getPageCount()](#getPageCount--) | Returns number of pages |
| [getSize()](#getSize--) | Returns size in bytes of this fixed-layout format document |
| [isEncrypted()](#isEncrypted--) | Determines whether this specific fixed-layout format document in encrypted and requires password for opening |
| [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Determines whether this instance is equal to the other specified FixedLayoutDocumentInfo instance |
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final FixedLayoutFormats getFormat()
```


Returns a format of this fixed-layout format document

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returns number of pages

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this fixed-layout format document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Determines whether this specific fixed-layout format document in encrypted and requires password for opening

**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Determines whether this instance is equal to the other specified FixedLayoutDocumentInfo instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Other FixedLayoutDocumentInfo instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
