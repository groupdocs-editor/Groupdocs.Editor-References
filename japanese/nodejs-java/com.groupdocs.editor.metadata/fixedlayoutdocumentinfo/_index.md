---
title: "FixedLayoutDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PDF や XPS のような固定レイアウト形式のドキュメントのメタデータを表します"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

PDF や XPS のような固定レイアウト形式のドキュメントのメタデータを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | この固定レイアウト形式ドキュメントの形式を返します |
|
|  | [getPageCount()](#getPageCount--) | ページ数を返します |
|
|  | [getSize()](#getSize--) | この固定レイアウト形式ドキュメントのバイト単位のサイズを返します |
|
|  | [isEncrypted()](#isEncrypted--) | この特定の固定レイアウト形式ドキュメントが暗号化されており、開く際にパスワードが必要かどうかを判定します |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | このインスタンスが指定された他の FixedLayoutDocumentInfo インスタンスと等しいかどうかを判定します |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


この固定レイアウト形式ドキュメントの形式を返します


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


この固定レイアウト形式ドキュメントのバイト単位のサイズを返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


この特定の固定レイアウト形式ドキュメントが暗号化されており、開く際にパスワードが必要かどうかを判定します


**Returns:**
ブール
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


このインスタンスが指定された他の FixedLayoutDocumentInfo インスタンスと等しいかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | このインスタンスと等価性をチェックすべき他の FixedLayoutDocumentInfo インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

