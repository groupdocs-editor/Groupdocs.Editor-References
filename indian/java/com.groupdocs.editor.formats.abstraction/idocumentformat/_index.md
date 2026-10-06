---
title: "IDocumentFormat"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित दस्तावेज़ फ़ॉर्मेट्स के लिए मूल इंटरफ़ेस को दर्शाता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.formats.abstraction/idocumentformat/
---```
public interface IDocumentFormat
```

Represents the root interface for all supporting document formats.

## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the full formal name of the document format.
 |
| [getExtension()](#getExtension--) | Gets the file extension of the document format.
 |
| [getMime()](#getMime--) | Gets the MIME type of the document format.
 |
| [getFormatFamily()](#getFormatFamily--) | Gets the format family to which the document format belongs.
 |
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
