---
title: SpreadsheetDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Represents metadata of one Spreadsheet document
type: docs
weight: 23
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
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
| [SpreadsheetDocumentInfo(SpreadsheetFormats format, int pageCount, long size, boolean isEncrypted)](#SpreadsheetDocumentInfo-com.groupdocs.editor.formats.SpreadsheetFormats-int-long-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Returns a format of this Spreadsheet document |
| [getPageCount()](#getPageCount--) | Returns number of tabs |
| [getSize()](#getSize--) | Returns size in bytes of this Spreadsheet document |
| [isEncrypted()](#isEncrypted--) | Indicates whether this specific Spreadsheet document in encrypted and requires password for opening |
| [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Determines whether this instance is equal to the other specified SpreadsheetDocumentInfo instance |
| [CloneTo(SpreadsheetDocumentInfo that)](#CloneTo-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [equals(SpreadsheetDocumentInfo obj1, SpreadsheetDocumentInfo obj2)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) |  |
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```




### SpreadsheetDocumentInfo(SpreadsheetFormats format, int pageCount, long size, boolean isEncrypted) {#SpreadsheetDocumentInfo-com.groupdocs.editor.formats.SpreadsheetFormats-int-long-boolean-}
```
public SpreadsheetDocumentInfo(SpreadsheetFormats format, int pageCount, long size, boolean isEncrypted)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |
| pageCount | int |  |
| size | long |  |
| isEncrypted | boolean |  |

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
### CloneTo(SpreadsheetDocumentInfo that) {#CloneTo-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public void CloneTo(SpreadsheetDocumentInfo that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) |  |

### Clone() {#Clone--}
```
public SpreadsheetDocumentInfo Clone()
```




**Returns:**
[SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo)
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
### equals(SpreadsheetDocumentInfo obj1, SpreadsheetDocumentInfo obj2) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public static boolean equals(SpreadsheetDocumentInfo obj1, SpreadsheetDocumentInfo obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) |  |
| obj2 | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) |  |

**Returns:**
boolean
