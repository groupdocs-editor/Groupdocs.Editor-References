---
title: "WordProcessingLoadOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "DOCX、RTF、ODT などの Word 互換ドキュメントを読み込むためのオプションを含みます。"
type: docs
weight: 45
url: /ja/nodejs-java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

WordProcessing（Word 互換）ドキュメントを読み込むためのオプションを含みます（例：
DOC(X)、RTF、ODT などを Editor クラスに読み込みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
エンコードされている場合の WordProcessing ドキュメントのオープン時に使用されます。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
エンコードされている場合の WordProcessing ドキュメントのオープン時に使用されます。
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
エンコードされている場合の WordProcessing ドキュメントのオープン時に使用されます。NULL または空に設定します。
パスワードを使用しないための文字列（デフォルト値）。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
エンコードされている場合の WordProcessing ドキュメントのオープン時に使用されます。NULL または空に設定します。
パスワードを使用しないための文字列（デフォルト値）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

