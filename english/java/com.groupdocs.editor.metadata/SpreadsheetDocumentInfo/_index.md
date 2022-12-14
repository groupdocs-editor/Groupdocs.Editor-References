---
title: SpreadsheetDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one Spreadsheet document
type: docs
weight: 14
url: /java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Represents metadata of one Spreadsheet document
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this Spreadsheet document |
| [getPageCount()](#getPageCount--) | Returns number of tabs |
| [getSize()](#getSize--) | Returns size in bytes of this Spreadsheet document |
| [isEncrypted()](#isEncrypted--) | Indicates whether this specific Spreadsheet document in encrypted and requires password for opening |
| [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Determines whether this instance is equal to the other specified SpreadsheetDocumentInfo instance |
### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Returns a format of this Spreadsheet document

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returns number of tabs

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returns size in bytes of this Spreadsheet document

**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indicates whether this specific Spreadsheet document in encrypted and requires password for opening

**Returns:**
boolean
### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Determines whether this instance is equal to the other specified SpreadsheetDocumentInfo instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Other SpreadsheetDocumentInfo instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
