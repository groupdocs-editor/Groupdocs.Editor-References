---
title: "WordProcessingSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "編集後の WordProcessing 準拠ドキュメントの生成および保存のためにカスタムオプションを指定できるようにします。"
type: docs
weight: 48
url: /ja/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

生成および保存のためのカスタムオプションを指定できるようにします。
編集後の WordProcessing 準拠ドキュメント


*** ** * ** ***

WordProcessingSaveOptions は、編集されたドキュメント内容を含む EditableDocument クラスのインスタンスがあり、その内容を WordProcessing 形式の新しいドキュメントに保存する必要がある状況で適用されます。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | このパラメータなしコンストラクタは、DOCX 出力形式で WordProcessingSaveOptions の新しいインスタンスを作成します（その後、次を通じて変更可能です |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) プロパティ)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | 指定された |
必須の WordProcessing 出力形式で、他のすべてのパラメータは
デフォルト
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 保存に使用されるページングを有効または無効にすることを許可します |
ドキュメント。
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 保存に使用されるページングを有効または無効にすることを許可します |
ドキュメント。
|
|  | [getPassword()](#getPassword--) | パスワードを指定、変更、取得、または削除することを許可します |
生成された WordProcessing ドキュメントをエンコードするために使用されます。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを指定、変更、取得、または削除することを許可します |
生成された WordProcessing ドキュメントをエンコードするために使用されます。
|
|  | [getOutputFormat()](#getOutputFormat--) | 保存に使用される WordProcessing フォーマットを指定することを許可します |
ドキュメント
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | 保存に使用される WordProcessing フォーマットを指定することを許可します |
ドキュメント
|
|  | [getLocale()](#getLocale--) | WordProcessing のデフォルトロケール（言語）を上書き設定することを許可します |
ドキュメントは作成時に適用されます。
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | WordProcessing のデフォルトロケール（言語）を上書き設定することを許可します |
ドキュメントは作成時に適用されます。
|
|  | [getLocaleBi()](#getLocaleBi--) | WordProcessing ドキュメントのロケール（言語）を上書き設定することを許可します |
RTL（右から左）テキスト用に、作成時に適用されます
作成時に。
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | WordProcessing ドキュメントのロケール（言語）を上書き設定することを許可します |
RTL（右から左）テキスト用に、作成時に適用されます
作成時に。
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | WordProcessing ドキュメントのロケール（言語）を上書きすることを許可します |
東アジア文字用に、作成時に適用されます。
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | WordProcessing ドキュメントのロケール（言語）を上書きすることを許可します |
東アジア文字用に、作成時に適用されます。
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | ドキュメント生成時にメモリ最適化機構を有効にします |
HTML では、メモリ使用量を減らす代償としてパフォーマンスが低下します。
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | ドキュメント生成時にメモリ最適化機構を有効にします |
HTML では、メモリ使用量を減らす代償としてパフォーマンスが低下します。
|
|  | [getProtection()](#getProtection--) | ドキュメント保護オプションを制御および適用することを許可します |
任意の形式の WordProcessing ドキュメントで、
ドキュメント保護をサポートします。
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | ドキュメント保護オプションを制御および適用することを許可します |
任意の形式の WordProcessing ドキュメントで、
ドキュメント保護をサポートします。
|
|  | [getFontEmbedding()](#getFontEmbedding--) | 出力 WordProcessing にフォントリソースを埋め込むことを担当します |
ドキュメント。
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 出力 WordProcessing にフォントリソースを埋め込むことを担当します |
ドキュメント。
|
|  | [deepClone()](#deepClone--) | このインスタンスの完全なコピーを作成して返します |
WordProcessingSaveOptions クラス
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


このパラメータなしコンストラクタは、DOCX 出力形式で WordProcessingSaveOptions の新しいインスタンスを作成します（その後、次を通じて変更可能です
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) プロパティ)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


指定された
必須の WordProcessing 出力形式で、他のすべてのパラメータは
デフォルト


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | WordProcessing ドキュメントを保存すべき必須の出力形式 |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


保存に使用されるページングを有効または無効にすることを許可します
ドキュメントです。元のドキュメントがページングモードで開かれ、編集されていた場合
このオプションも有効にする必要があります。デフォルトでは無効です。


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


保存に使用されるページングを有効または無効にすることを許可します
ドキュメントです。元のドキュメントがページングモードで開かれ、編集されていた場合
このオプションも有効にする必要があります。デフォルトでは無効です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードを指定、変更、取得、または削除することを許可します
生成された WordProcessing ドキュメントをエンコードするために使用されます。NULL または
パスワードを削除（クリア）するために空文字列を指定します。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワードを指定、変更、取得、または削除することを許可します
生成された WordProcessing ドキュメントをエンコードするために使用されます。NULL または
パスワードを削除（クリア）するために空文字列を指定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


保存に使用される WordProcessing フォーマットを指定することを許可します
ドキュメント


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


保存に使用される WordProcessing フォーマットを指定することを許可します
ドキュメント


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


WordProcessing のデフォルトロケール（言語）を上書き設定することを許可します
ドキュメントは、作成時に適用されます。指定されていない場合は
指定された（デフォルト値）場合、MS Word（または他のプログラム）は検出（または
選択）ドキュメントのロケールを独自の設定またはその他の
要因です。


*** ** * ** ***

このオプションは、指定されたロケールをドキュメント内の全体テキストに強制的に適用します。異なる言語で書かれたテキストの異なる部分がドキュメントに含まれる場合は使用しないでください。

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


WordProcessing のデフォルトロケール（言語）を上書き設定することを許可します
ドキュメントは、作成時に適用されます。指定されていない場合は
指定された（デフォルト値）場合、MS Word（または他のプログラム）は検出（または
選択）ドキュメントのロケールを独自の設定またはその他の
要因です。

*** ** * ** ***


このオプションは、指定されたロケールを全体テキストに強制的に適用します
ドキュメントに適用します。ドキュメントに異なる部分が含まれる場合は
テキストが異なる言語で書かれている場合です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


WordProcessing ドキュメントのロケール（言語）を上書き設定することを許可します
RTL（右から左）テキスト用に、作成時に適用されます
作成時に指定されていない場合（デフォルト値）、MS Word（または他の
プログラム）は、ドキュメントのRTLロケールをその
独自の設定またはその他の要因です。

*** ** * ** ***


このオプションは、指定されたロケールを全体のRTLテキストに強制的に適用します
ドキュメントに適用します。ドキュメントに異なる部分が含まれる場合は
テキストが異なる言語で書かれている場合です。


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


WordProcessing ドキュメントのロケール（言語）を上書き設定することを許可します
RTL（右から左）テキスト用に、作成時に適用されます
作成時に指定されていない場合（デフォルト値）、MS Word（または他の
プログラム）は、ドキュメントのRTLロケールをその
独自の設定またはその他の要因です。

*** ** * ** ***


このオプションは、指定されたロケールを全体のRTLテキストに強制的に適用します
ドキュメントに適用します。ドキュメントに異なる部分が含まれる場合は
テキストが異なる言語で書かれている場合です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


WordProcessing ドキュメントのロケール（言語）を上書きすることを許可します
東アジアテキスト用に、作成時に適用されます。指定されていない場合は
指定されていない場合（デフォルト値）、MS Word（または他のプログラム）は検出します
（または選択）ドキュメントの東アジアロケールを独自の設定に従って
またはその他の要因です。

*** ** * ** ***


このオプションは、指定されたロケールを全体に強制的に適用します
ドキュメント内の東アジアテキストに適用します。ドキュメントに含まれる場合は使用しないでください
異なるテキストの部分が、異なる
言語で書かれている場合です。


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


WordProcessing ドキュメントのロケール（言語）を上書きすることを許可します
東アジアテキスト用に、作成時に適用されます。指定されていない場合は
指定されていない場合（デフォルト値）、MS Word（または他のプログラム）は検出します
（または選択）ドキュメントの東アジアロケールを独自の設定に従って
またはその他の要因です。

*** ** * ** ***


このオプションは、指定されたロケールを全体に強制的に適用します
ドキュメント内の東アジアテキストに適用します。ドキュメントに含まれる場合は使用しないでください
異なるテキストの部分が、異なる
言語で書かれている場合です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


ドキュメント生成時にメモリ最適化機構を有効にします
HTML では、メモリ使用量を減らす代償としてパフォーマンスが低下します。
このオプションを true に設定すると、メモリ消費を大幅に削減できます
ただし、保存時間が遅くなるという代償があります
デフォルトは false (メモリ最適化はパフォーマンス向上のために
パフォーマンス).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


ドキュメント生成時にメモリ最適化機構を有効にします
HTML では、メモリ使用量を減らす代償としてパフォーマンスが低下します。
このオプションを true に設定すると、メモリ消費を大幅に削減できます
ただし、保存時間が遅くなるという代償があります
デフォルトは false (メモリ最適化はパフォーマンス向上のために
パフォーマンス).


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


ドキュメント保護オプションを制御および適用することを許可します
任意の形式の WordProcessing ドキュメントで、
保護。デフォルトは NULL です - ドキュメント保護は使用されません。


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


ドキュメント保護オプションを制御および適用することを許可します
任意の形式の WordProcessing ドキュメントで、
保護。デフォルトは NULL です - ドキュメント保護は使用されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


出力 WordProcessing にフォントリソースを埋め込むことを担当します
ドキュメント。デフォルトではフォントを埋め込みません (NotEmbed)。


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


出力 WordProcessing にフォントリソースを埋め込むことを担当します
ドキュメント。デフォルトではフォントを埋め込みません (NotEmbed)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


このインスタンスの完全なコピーを作成して返します
WordProcessingSaveOptions クラス


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

