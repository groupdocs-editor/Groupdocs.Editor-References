---
title: IDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Common interface for all file metadata wrappers
type: docs
weight: 18
url: /java/com.groupdocs.editor.metadata/idocumentinfo/
---```
public interface IDocumentInfo
```

Common interface for all file metadata wrappers
## Methods

| Method | Description |
| --- | --- |
| [getPageCount()](#getPageCount--) | In implementing type should return count (number) of pages or other similar format-dependent entities (tabs, slides etc.). |
| [getSize()](#getSize--) | Document size in bytes |
| [isEncrypted()](#isEncrypted--) | Indicates whether specific file is encrypted and requires password for opening. |
| [getFormat()](#getFormat--) | Returns a document format |
### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


In implementing type should return count (number) of pages or other similar format-dependent entities (tabs, slides etc.). For those family types, that don't have something similar (like plain text documents or XML) should return 1.

**Returns:**
int - 
### getSize() {#getSize--}
```
public abstract long getSize()
```


Document size in bytes

**Returns:**
long - 
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Indicates whether specific file is encrypted and requires password for opening. For the document types, that cannot be encrypted (like all text-based) should always return 'false'.

**Returns:**
boolean - 
### getFormat() {#getFormat--}
```
public abstract IDocumentFormat getFormat()
```


Returns a document format

**Returns:**
[IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat) - 
