---
title: "DelimitedTextEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "区切り文字を使用するテキストベースのスプレッドシートドキュメント（CSV、タブ区切りなど）を読み込むためのオプション"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

テキストベースのスプレッドシートドキュメント（CSV、タブ区切りなど）を読み込むためのオプション、
区切り文字（デリミタ）を使用する


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | 必須の区切り文字を伴うデリミテッドテキスト用オプションクラスのインスタンスを作成します。 |
区切り文字（デリミタ）
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | テキストベースの文書用に文字列の区切り文字（デリミタ）を指定できます。 |
スプレッドシート文書
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | テキストベースの文書用に文字列の区切り文字（デリミタ）を指定できます。 |
スプレッドシート文書
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | テキストベースの文字列が...かどうかを示す値を取得または設定します |
ドキュメントは日付データに変換されます。
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | テキストベースの文字列が...かどうかを示す値を取得または設定します |
ドキュメントは日付データに変換されます。
|
|  | [getConvertNumericData()](#getConvertNumericData--) | テキストベースの文字列が...かどうかを示す値を取得または設定します |
ドキュメントは数値データに変換されます。
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | テキストベースの文字列が...かどうかを示す値を取得または設定します |
ドキュメントは数値データに変換されます。
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | 連続する区切り文字を1つとして扱うかどうかを定義します。 |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | 連続する区切り文字を1つとして扱うかどうかを定義します。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 入力ドキュメントの処理中にメモリ最適化メカニズムを有効にします、 |
これは特定のケースでパフォーマンスが低下する可能性がありますが、しかし一方で
メモリ使用量を削減します。
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 入力ドキュメントの処理中にメモリ最適化メカニズムを有効にします、 |
これは特定のケースでパフォーマンスが低下する可能性がありますが、しかし一方で
メモリ使用量を削減します。
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


必須の区切り文字を伴うデリミテッドテキスト用オプションクラスのインスタンスを作成します。
区切り文字（デリミタ）


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 区切り文字 | java.lang.String | NULLまたは空にできない必須の区切り文字（デリミタ） |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


テキストベースの文書用に文字列の区切り文字（デリミタ）を指定できます。
スプレッドシート文書


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


テキストベースの文書用に文字列の区切り文字（デリミタ）を指定できます。
スプレッドシート文書


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


テキストベースの文字列が...かどうかを示す値を取得または設定します
ドキュメントは日付データに変換されます。デフォルトは false です。


**Returns:**
ブール
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


テキストベースの文字列が...かどうかを示す値を取得または設定します
ドキュメントは日付データに変換されます。デフォルトは false です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


テキストベースの文字列が...かどうかを示す値を取得または設定します
ドキュメントは数値データに変換されます。デフォルトは false です。


**Returns:**
ブール
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


テキストベースの文字列が...かどうかを示す値を取得または設定します
ドキュメントは数値データに変換されます。デフォルトは false です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


連続する区切り文字を1つとして扱うかどうかを定義します。By
デフォルトは false です。


**Returns:**
ブール
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


連続する区切り文字を1つとして扱うかどうかを定義します。By
デフォルトは false です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


入力ドキュメントの処理中にメモリ最適化メカニズムを有効にします、
これは特定のケースでパフォーマンスが低下する可能性がありますが、しかし一方で
メモリ使用量を削減します。巨大なドキュメントを処理する際に有用です、
OutOfMemoryException に直面した場合。デフォルトは false です（メモリ最適化は
より良いパフォーマンスのために無効化されています)。


**Returns:**
ブール
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


入力ドキュメントの処理中にメモリ最適化メカニズムを有効にします、
これは特定のケースでパフォーマンスが低下する可能性がありますが、しかし一方で
メモリ使用量を削減します。巨大なドキュメントを処理する際に有用です、
OutOfMemoryException に直面した場合。デフォルトは false です（メモリ最適化は
より良いパフォーマンスのために無効化されています)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

