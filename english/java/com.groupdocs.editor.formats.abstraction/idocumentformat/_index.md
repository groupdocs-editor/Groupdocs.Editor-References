---
title: IDocumentFormat
second_title: GroupDocs.Editor for Java API Reference
description: Represents the root interface for all supporting document formats.
type: docs
weight: 10
url: /java/com.groupdocs.editor.formats.abstraction/idocumentformat/
---```
public interface IDocumentFormat
```

Represents the root interface for all supporting document formats.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the full formal name of the document format. |
| [getExtension()](#getExtension--) | Gets the file extension of the document format. |
| [getMime()](#getMime--) | Gets the MIME type of the document format. |
| [getFormatFamily()](#getFormatFamily--) | Gets the format family to which the document format belongs. |
### getName() {#getName--}
```
public abstract String getName()
```


Gets the full formal name of the document format.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Gets the file extension of the document format.

**Returns:**
java.lang.String
### getMime() {#getMime--}
```
public abstract String getMime()
```


Gets the MIME type of the document format.

**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public abstract FormatFamilies getFormatFamily()
```


Gets the format family to which the document format belongs.

**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
