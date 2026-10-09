---
title: "EbookDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "EBook ドキュメントのメタデータを表します"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

EBook ドキュメントのメタデータを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | このドキュメントの形式を返します |
|
|  | [getPageCount()](#getPageCount--) | MOBI または AZW3 の場合はページ数を、ePub の場合は章数を返します。 |
|
|  | [getSize()](#getSize--) | この eBook ドキュメントのサイズ（バイト）を返します |
|
|  | [isEncrypted()](#isEncrypted--) | eBook ドキュメントはパスワードで暗号化できないため、このプロパティは常に 'false' を返します |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | このインスタンスが指定された別の EbookDocumentInfo インスタンスと等しいかどうかを判断します |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


このドキュメントの形式を返します


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


MOBI または AZW3 の場合はページ数を、ePub の場合は章数を返します。

<br />

*** ** * ** ***

eBook ドキュメントは通常固定ページがなく、ページ数もありません。ePub の場合は章数を計算することが可能です。ただし、MOBI および AZW3 形式にも章はないため、この数値は縦向きの A4 用紙サイズを標準ページサイズとして計算されます。

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


この eBook ドキュメントのサイズ（バイト）を返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


eBook ドキュメントはパスワードで暗号化できないため、このプロパティは常に 'false' を返します


**Returns:**
ブール
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


このインスタンスが指定された別の EbookDocumentInfo インスタンスと等しいかどうかを判断します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | このインスタンスと等価性をチェックすべき他の EbookDocumentInfo インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

