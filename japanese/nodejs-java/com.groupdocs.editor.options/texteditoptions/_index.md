---
title: "TextEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "プレーンテキスト TXT ドキュメントの読み込み時にカスタムオプションを指定できます。"
type: docs
weight: 39
url: /ja/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

プレーンテキスト（TXT）ドキュメントの読み込みにカスタムオプションを指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | テキストドキュメントの文字エンコーディングで、これが適用されます |
開く
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストドキュメントの文字エンコーディングで、これが適用されます |
開く
|
|  | [getRecognizeLists()](#getRecognizeLists--) | ドキュメントがあるときに番号付きリスト項目がどのように認識されるかを指定できます |
プレーンテキスト形式からインポートされた場合。
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | ドキュメントがあるときに番号付きリスト項目がどのように認識されるかを指定できます |
プレーンテキスト形式からインポートされた場合。
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | 先頭スペースの処理に関する優先オプションを取得または設定します。 |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | 先頭スペースの処理に関する優先オプションを取得または設定します。 |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | 末尾スペースの処理に関する優先オプションを取得または設定します。 |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | 末尾スペースの処理に関する優先オプションを取得または設定します。 |
|
|  | [getEnablePagination()](#getEnablePagination--) | 生成された HTML ドキュメントでページングを有効または無効にできます。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 生成された HTML ドキュメントでページングを有効または無効にできます。 |
|
|  | [getDirection()](#getDirection--) | 入力プレーンテキストのテキストフローの方向を指定できます |
ドキュメント。
|
|  | [setDirection(int value)](#setDirection-int-) | 入力プレーンテキストのテキストフローの方向を指定できます |
ドキュメント。
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


テキストドキュメントの文字エンコーディングで、これが適用されます
開く


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


テキストドキュメントの文字エンコーディングで、これが適用されます
開く


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


ドキュメントがあるときに番号付きリスト項目がどのように認識されるかを指定できます
プレーンテキスト形式からインポートされた場合。デフォルト値は true です。


*** ** * ** ***

このオプションが false に設定されている場合、リスト認識アルゴリズムはリスト番号がドット、右括弧、または箇条書き記号（例: "\\u2022", "\*", "-", "o"）で終わるときにリスト段落を検出します。オプションが true に設定されている場合、空白もリスト番号の区切りとして使用されます。アラビア様式の番号付け（1., 1.1.2.）用のリスト認識アルゴリズムは、空白とドット（".") の両方を使用します。

<br />



**Returns:**
ブール
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


ドキュメントがあるときに番号付きリスト項目がどのように認識されるかを指定できます
プレーンテキスト形式からインポートされた場合。デフォルト値は true です。


*** ** * ** ***

このオプションが false に設定されている場合、リスト認識アルゴリズムはリスト番号がドット、右括弧、または箇条書き記号（例: "\\u2022", "\*", "-", "o"）で終わるときにリスト段落を検出します。オプションが true に設定されている場合、空白もリスト番号の区切りとして使用されます。アラビア様式の番号付け（1., 1.1.2.）用のリスト認識アルゴリズムは、空白とドット（".") の両方を使用します。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


先頭スペースの処理に関する優先オプションを取得または設定します。デフォルトでは
先頭のスペースを左インデントに変換します。


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


先頭スペースの処理に関する優先オプションを取得または設定します。デフォルトでは
先頭のスペースを左インデントに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


末尾スペースの処理に関する優先オプションを取得または設定します。デフォルトでは
すべての末尾スペースを切り捨てます。


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


末尾スペースの処理に関する優先オプションを取得または設定します。デフォルトでは
すべての末尾スペースを切り捨てます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


生成された HTML ドキュメントでページングを有効または無効にできます。
デフォルトでは無効です（false）。


**Returns:**
ブール
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


生成された HTML ドキュメントでページングを有効または無効にできます。
デフォルトでは無効です（false）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


入力プレーンテキストのテキストフローの方向を指定できます
ドキュメント。デフォルトでは左から右です。


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


入力プレーンテキストのテキストフローの方向を指定できます
ドキュメント。デフォルトでは左から右です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

