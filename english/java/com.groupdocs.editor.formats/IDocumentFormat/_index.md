---
title: IDocumentFormat
second_title: GroupDocs.Editor for Java API Reference
description: Root interface for all supporting document formats
type: docs
weight: 17
url: /java/com.groupdocs.editor.formats/idocumentformat/
---```
public interface IDocumentFormat
```

Root interface for all supporting document formats
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | In implementing type should return full formal format name |
| [getExtension()](#getExtension--) | In implementing type should return format file extension |
| [getMime()](#getMime--) | In implementing type should return a MIME-code for the given format |
### getName() {#getName--}
```
public abstract String getName()
```


In implementing type should return full formal format name

**Returns:**
java.lang.String - 
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


In implementing type should return format file extension

**Returns:**
java.lang.String - 
### getMime() {#getMime--}
```
public abstract String getMime()
```


In implementing type should return a MIME-code for the given format

**Returns:**
java.lang.String
