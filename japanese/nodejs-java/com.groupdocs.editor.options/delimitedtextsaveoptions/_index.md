---
title: "DelimitedTextSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "区切り文字を使用するテキストベースのスプレッドシート文書（CSV、タブ区切りなど）を生成および保存するためのオプションを含みます。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

テキストベースのスプレッドシート文書を生成および保存するためのオプションを含みます。
（CSV、タブ区切りなど）、区切り文字（デリミタ）を使用します。


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | このパラメータなしコンストラクタは、デフォルトの区切り文字がセミコロン (;) の DelimitedTextSaveOptions の新しいインスタンスを作成します（その後、以下を通じて |
区切り文字
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) プロパティ)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | 必須の区切り文字を伴うデリミテッドテキスト用オプションクラスのインスタンスを作成します。 |
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
|  | [getEncoding()](#getEncoding--) | テキストベースのスプレッドシート ドキュメントのエンコーディングを設定できます。 |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのスプレッドシート ドキュメントのエンコーディングを設定できます。 |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | 先頭の空白行と列をトリムすべきかどうかを示します。 |
MS Excel が行うように
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | 先頭の空白行と列をトリムすべきかどうかを示します。 |
MS Excel が行うように
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | 空白行に対して区切り文字を出力すべきかどうかを示します。 |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | 空白行に対して区切り文字を出力すべきかどうかを示します。 |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


このパラメータなしコンストラクタは、デフォルトの区切り文字がセミコロン (;) の DelimitedTextSaveOptions の新しいインスタンスを作成します（その後、以下を通じて
区切り文字
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) プロパティ)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


必須の区切り文字を伴うデリミテッドテキスト用オプションクラスのインスタンスを作成します。
区切り文字（デリミタ）


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 区切り文字 | java.lang.String | テキストベースのスプレッドシート ドキュメント用の文字列区切り（デリミタ） |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


テキストベースの文書用に文字列の区切り文字（デリミタ）を指定できます。
スプレッドシート文書


**Returns:**
java.lang.String -
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

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


テキストベースのスプレッドシート ドキュメントのエンコーディングを設定できます。デフォルトで
デフォルト（指定されない場合）は UTF8 です。


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


テキストベースのスプレッドシート ドキュメントのエンコーディングを設定できます。デフォルトで
デフォルト（指定されない場合）は UTF8 です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


先頭の空白行と列をトリムすべきかどうかを示します。
MS Excel が行うように


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


先頭の空白行と列をトリムすべきかどうかを示します。
MS Excel が行うように


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


空白行に対して区切り文字を出力すべきかどうかを示します。デフォルト
値は false で、空白行の内容が空になることを意味します。


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


空白行に対して区切り文字を出力すべきかどうかを示します。デフォルト
値は false で、空白行の内容が空になることを意味します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

