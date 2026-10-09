---
title: "MarkdownImageLoadArgs"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs イベントに対するデータを提供します。"
type: docs
weight: 22
url: /ja/nodejs-java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

以下のデータを提供します。

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

イベント。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Markdown ドキュメント内のままのファイル名を取得または設定します。 |
処理されます。
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Markdown ドキュメント内のままのファイル名を取得または設定します。 |
処理されます。
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | この画像が絶対 URI リンクを持つかどうかを示す値を取得します。 |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | この画像が絶対 URI リンクを持つかどうかを示す値を取得します。 |
|
|  | [setData(byte[] data)](#setData-byte---) | リソースのユーザー提供データを設定します。使用されるのは |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Markdown ドキュメント内のままのファイル名を取得または設定します。
処理されます。


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Markdown ドキュメント内のままのファイル名を取得または設定します。
処理されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


この画像が絶対 URI リンクを持つかどうかを示す値を取得します。
値: この画像が絶対 URI リンクを持つ場合は true、そうでない場合は false。


**Returns:**
ブール
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


この画像が絶対 URI リンクを持つかどうかを示す値を取得します。
値: この画像が絶対 URI リンクを持つ場合は true、そうでない場合は false。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


リソースのユーザー提供データを設定します。使用されるのは

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] |  |

