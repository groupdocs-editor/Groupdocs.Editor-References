---
title: "TtcFont"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "TTC TrueType コレクション形式のフォントを 1 つ表します"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

TTC（TrueType Collection）フォーマットのフォントを 1 つ表します。


詳細はこちら: https://docs.fileformat.com/font/ttc/

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | コンテンツから新しい TtcFont クラスを作成します（base64 エンコードされた形式） |
文字列で、指定された名前と共に
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | コンテンツから新しい TtcFont クラスを作成します（バイトストリームとして表現され、そして） |
指定された名前で
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC ヘッダーサイズ（バイト単位）、検証に必要です |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な TTC フォントかどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な TTC フォントかどうかをチェックします |
|
|  | [getType()](#getType--) | FontType.Ttc を返します |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC ヘッダー バージョン、"1" または "2" のいずれかです |
|
|  | [getFontsNumber()](#getFontsNumber--) | この TTC のフォント数 |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | この TTC に DSIG テーブルがあるかどうかを示します。 |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


コンテンツから新しい TtcFont クラスを作成します（base64 エンコードされた形式）
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | TTC フォントの名前。null、空、または空白にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 エンコード文字列です。null、空、または空白にできません。TTC コンテンツでない場合、例外がスローされます。 |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


コンテンツから新しい TtcFont クラスを作成します（バイトストリームとして表現され、そして）
指定された名前で


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | TTC フォントの名前。null、空、または空白にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC ヘッダーサイズ（バイト単位）、検証に必要です


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な TTC フォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | TTC リソースを含んでいると推測されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な TTC フォントを含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な TTC フォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 推測される TTC フォントのコンテンツ（base64 エンコード文字列の形式） |
|

**Returns:**
boolean - 指定された文字列が有効な TTC フォントを含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttc を返します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC ヘッダー バージョン、"1" または "2" のいずれかです


**Returns:**
バイト
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


この TTC のフォント数


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


この TTC に DSIG テーブルがあるかどうかを示します。DSIG テーブルは存在する可能性があります
TTC のヘッダー バージョンが 2.0 の場合のみです。


**Returns:**
ブール
