---
title: "IDocumentFormat"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "すべてのサポート対象ドキュメント形式のルートインターフェイスを表します。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.formats.abstraction/idocumentformat/
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
