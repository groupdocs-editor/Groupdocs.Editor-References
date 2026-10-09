---
title: "TextualDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "XML、HTML、またはプレーンテキストTXTのようなテキスト文書1つのメタデータを表します"
type: docs
weight: 16
url: /ja/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

XML、HTML、またはプレーンテキストのようなテキスト文書1つのメタデータを表します
(TXT)

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | このテキスト文書の形式を返します。 |
|
|  | [getPageCount()](#getPageCount--) | 常に1を返します |
|
|  | [getSize()](#getSize--) | このテキストのバイト単位のサイズ（文字数ではなく）を返します |
文書
|
|  | [isEncrypted()](#isEncrypted--) | テキスト文書は暗号化できないため、常に'false'を返します。 |
|
|  | [getEncoding()](#getEncoding--) | テキスト文書の検出された推定エンコーディングを返します |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


このテキスト文書の形式を返します。100％正確でない可能性がありますに
いくつかのケースです。


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


常に1を返します


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


このテキストのバイト単位のサイズ（文字数ではなく）を返します
文書


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


テキスト文書は暗号化できないため、常に'false'を返します。


**Returns:**
ブール
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


テキスト文書の検出された推定エンコーディングを返します


**Returns:**
java.nio.charset.Charset
