---
title: "EmailDocumentInfo"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされている任意のメール形式のメールドキュメントのメタデータを表します"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

サポートされている任意のメール形式のメールドキュメントのメタデータを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormat()](#getFormat--) | このメールドキュメントの形式を返します |
|
|  | [getPageCount()](#getPageCount--) | メールドキュメントはページビューを持たないため、常に 1 を返します |
|
|  | [getSize()](#getSize--) | このメールドキュメントのバイト単位のサイズを返します |
|
|  | [isEncrypted()](#isEncrypted--) | メールドキュメントはパスワードで暗号化できないため、このプロパティは常に 'false' を返します |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | このインスタンスが指定された他の EmailDocumentInfo インスタンスと等しいかどうかを判定します |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


このメールドキュメントの形式を返します


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


メールドキュメントはページビューを持たないため、常に 1 を返します


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


このメールドキュメントのバイト単位のサイズを返します


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


メールドキュメントはパスワードで暗号化できないため、このプロパティは常に 'false' を返します


**Returns:**
ブール
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


このインスタンスが指定された他の EmailDocumentInfo インスタンスと等しいかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | このインスタンスと等価性をチェックすべき他の EmailDocumentInfo インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

