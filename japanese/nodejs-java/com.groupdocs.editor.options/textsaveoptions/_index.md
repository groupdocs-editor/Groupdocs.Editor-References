---
title: "TextSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "プレーンテキスト TXT ドキュメントの生成および保存のためのカスタムオプションを指定できます"
type: docs
weight: 41
url: /ja/nodejs-java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

プレーンテキスト（TXT）の生成および保存のためのカスタムオプションを指定できます
ドキュメント

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | テキストドキュメントの文字エンコーディングで、これが適用されます |
保存
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストドキュメントの文字エンコーディングで、これが適用されます |
保存
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | 各 BiDi ランの前に双方向マークを追加するかどうかを指定します |
プレーンテキスト形式でエクスポートする場合。
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | 各 BiDi ランの前に双方向マークを追加するかどうかを指定します |
プレーンテキスト形式でエクスポート
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | プログラムがテーブルのレイアウトを保持しようとするかどうかを指定します |
プレーンテキスト形式で保存する際に。
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | プログラムがテーブルのレイアウトを保持しようとするかどうかを指定します |
プレーンテキスト形式で保存する際に。
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


テキストドキュメントの文字エンコーディングで、これが適用されます
保存


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


テキストドキュメントの文字エンコーディングで、これが適用されます
保存


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


各 BiDi ランの前に双方向マークを追加するかどうかを指定します
プレーンテキスト形式でエクスポートする場合。デフォルトは 'false' — BiDi マークは追加しません。


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


各 BiDi ランの前に双方向マークを追加するかどうかを指定します
プレーンテキスト形式でエクスポート


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


プログラムがテーブルのレイアウトを保持しようとするかどうかを指定します
プレーンテキスト形式で保存する際。デフォルト値は false です。


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


プログラムがテーブルのレイアウトを保持しようとするかどうかを指定します
プレーンテキスト形式で保存する際。デフォルト値は false です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

