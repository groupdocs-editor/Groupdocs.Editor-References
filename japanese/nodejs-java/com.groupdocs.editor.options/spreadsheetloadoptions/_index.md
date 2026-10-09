---
title: "SpreadsheetLoadOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "XLSX、ODS などのバイナリ Spreadsheet Cells Excel 互換ドキュメントを読み込むためのオプションを含みます"
type: docs
weight: 36
url: /ja/nodejs-java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

バイナリ Spreadsheet（Cells、Excel 互換）を読み込むためのオプションを含みます
XLS(X)、ODS などのドキュメントを Editor クラスに読み込みます

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | デフォルトのパラメータなしコンストラクタ - すべてのパラメータはデフォルト値を持ちます |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
Spreadsheet ドキュメントを開く際に、エンコードされている場合です。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
Spreadsheet ドキュメントを開く際に、エンコードされている場合です。
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 入力ドキュメントの処理中にメモリ最適化メカニズムを有効にします、 |
これは特定のケースでパフォーマンスが低下する可能性がありますが、しかし一方で
メモリ使用量を削減します。
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 入力ドキュメントの処理中にメモリ最適化メカニズムを有効にします、 |
これは特定のケースでパフォーマンスが低下する可能性がありますが、しかし一方で
メモリ使用量を削減します。
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


デフォルトのパラメータなしコンストラクタ - すべてのパラメータはデフォルト値を持ちます


### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
Spreadsheet ドキュメントを開く際に、エンコードされている場合です。NULL または空に設定します
パスワードを使用しないための文字列（デフォルト値）。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
Spreadsheet ドキュメントを開く際に、エンコードされている場合です。NULL または空に設定します
パスワードを使用しないための文字列（デフォルト値）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

