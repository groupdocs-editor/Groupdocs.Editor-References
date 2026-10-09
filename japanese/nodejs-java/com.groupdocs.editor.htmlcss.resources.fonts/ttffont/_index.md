---
title: "TtfFont"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "TTF TrueType フォント形式のフォントを表します"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

TTF（TrueType Font）フォーマットのフォントを 1 つ表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | コンテンツ（base64 エンコードされたもの）から新しい TtfFont クラスを作成します |
文字列で、指定された名前と共に
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | バイトストリームとして表現されたコンテンツから新しい TtfFont クラスを作成し、 |
指定された名前で
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | 検証に必要な TTF ヘッダーサイズ（バイト単位） |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な TTF フォントかどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な TTF フォントかどうかをチェックします |
|
|  | [getType()](#getType--) | FontType.Ttf を返します |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


コンテンツ（base64 エンコードされたもの）から新しい TtfFont クラスを作成します
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | TTF フォントの名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 エンコード文字列として提供されます。null、空、または空白文字にできません。TTF コンテンツでない場合、例外がスローされます。 |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


バイトストリームとして表現されたコンテンツから新しい TtfFont クラスを作成し、
指定された名前で


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | TTF フォントの名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


検証に必要な TTF ヘッダーサイズ（バイト単位）


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な TTF フォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | TTF リソースを含んでいると推測されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な TTF フォントを含む場合は True、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な TTF フォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 推測される TTF フォントのコンテンツを base64 エンコード文字列の形で表したもの |
|

**Returns:**
boolean - 指定された文字列が有効な TTF フォントを含む場合は True、そうでない場合は false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttf を返します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
