---
title: "PdfLoadOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "Editor クラスに PDF ドキュメントを読み込むためのオプションを含みます。"
type: docs
weight: 30
url: /ja/nodejs-java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Editor クラスに PDF ドキュメントを読み込むためのオプションを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | PDF 文書が暗号化されている場合に開くために使用されるパスワードを指定、変更、取得できるようにします。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | PDF 文書が暗号化されている場合に開くために使用されるパスワードを指定、変更、取得できるようにします。 |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


PDF 文書が暗号化されている場合に開くために使用されるパスワードを指定、変更、取得できるようにします。
パスワードを使用しないようにするには、NULL または空文字列に設定します（デフォルト値）。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


PDF 文書が暗号化されている場合に開くために使用されるパスワードを指定、変更、取得できるようにします。
パスワードを使用しないようにするには、NULL または空文字列に設定します（デフォルト値）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

