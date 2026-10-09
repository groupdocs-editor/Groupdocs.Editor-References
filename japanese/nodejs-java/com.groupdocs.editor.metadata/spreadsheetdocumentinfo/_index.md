---
title: "SpreadsheetDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "スプレッドシートドキュメントのメタデータを表します"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

スプレッドシートドキュメントのメタデータを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | このスプレッドシート ドキュメントの形式を返します |
|
|  | [getPageCount()](#getPageCount--) | タブ数を返します |
|
|  | [getSize()](#getSize--) | このスプレッドシート ドキュメントのバイトサイズを返します |
|
|  | [isEncrypted()](#isEncrypted--) | この特定のスプレッドシート ドキュメントが暗号化されているかどうかを示します |
開く際にパスワードが必要です
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | 選択されたワークシートのプレビューを SVG 画像の形式で生成し、返します |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | このインスタンスが指定された別のインスタンスと等しいかどうかを判断します |
SpreadsheetDocumentInfo インスタンス
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


このスプレッドシート ドキュメントの形式を返します


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


タブ数を返します


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


このスプレッドシート ドキュメントのバイトサイズを返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


この特定のスプレッドシート ドキュメントが暗号化されているかどうかを示します
開く際にパスワードが必要です


**Returns:**
ブール
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


選択されたワークシートのプレビューを SVG 画像の形式で生成し、返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | worksheetIndex | int | 目的のワークシートの 0 ベースインデックス。0 未満にすることはできず、このスプレッドシートのワークシート数を超えることもできません。 |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


このインスタンスが指定された別のインスタンスと等しいかどうかを判断します
SpreadsheetDocumentInfo インスタンス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | このインスタンスと等価性をチェックすべき他の SpreadsheetDocumentInfo インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

