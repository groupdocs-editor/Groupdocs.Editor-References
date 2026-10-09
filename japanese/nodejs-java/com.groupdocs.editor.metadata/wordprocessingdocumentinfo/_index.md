---
title: "WordProcessingDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "WordProcessing ドキュメントのメタデータを表します"
type: docs
weight: 17
url: /ja/nodejs-java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

WordProcessing ドキュメントのメタデータを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | この WordProcessing ドキュメントの形式を返します |
|
|  | [getPageCount()](#getPageCount--) | ページ数を返します |
|
|  | [getSize()](#getSize--) | この WordProcessing ドキュメントのバイト単位のサイズを返します |
|
|  | [isEncrypted()](#isEncrypted--) | この特定の WordProcessing ドキュメントが暗号化されているかどうかを判定します |
開く際にパスワードが必要です
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | 選択されたページのプレビューを SVG 画像の形で生成し、返します |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | このインスタンスが指定された別のインスタンスと等しいかどうかを判断します |
WordProcessingDocumentInfo インスタンス
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


この WordProcessing ドキュメントの形式を返します


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


ページ数を返します


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


この WordProcessing ドキュメントのバイト単位のサイズを返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


この特定の WordProcessing ドキュメントが暗号化されているかどうかを判定します
開く際にパスワードが必要です


**Returns:**
ブール
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


選択されたページのプレビューを SVG 画像の形で生成し、返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageIndex | int | 目的のページの 0 ベースインデックス。0 未満にすることはできず、この WordProcessing ドキュメントのページ数を超えることもできません。 |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


このインスタンスが指定された別のインスタンスと等しいかどうかを判断します
WordProcessingDocumentInfo インスタンス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | このインスタンスと等価性をチェックすべき他の WordProcessingDocumentInfo インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

