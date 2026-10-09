---
title: "MarkdownDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "Markdown ドキュメントのメタデータを表します"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Markdown ドキュメントのメタデータを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | この Markdown ドキュメントの形式を返します \\u2014 常に同じです |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | ページ数を返します。 |
|
|  | [getSize()](#getSize--) | この Markdown ドキュメントのバイトサイズを返します |
|
|  | [isEncrypted()](#isEncrypted--) | Markdown ドキュメントはパスワードで暗号化できないため、こちらは |
プロパティは常に 'false' を返します
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | このインスタンスが指定された別のインスタンスと等しいかどうかを判断します |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


この Markdown ドキュメントの形式を返します \\u2014 常に同じです
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


ページ数を返します。Markdown ドキュメントは通常、固定ページを持ちません
したがってページ数は標準ページサイズから計算されます
縦向きの A4 に設定されています。


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


この Markdown ドキュメントのバイトサイズを返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Markdown ドキュメントはパスワードで暗号化できないため、こちらは
プロパティは常に 'false' を返します


**Returns:**
ブール
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


このインスタンスが指定された別のインスタンスと等しいかどうかを判断します
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | このインスタンスと等価性をチェックすべき他の [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

