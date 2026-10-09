---
title: "WoffFont"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "WOFF Web Open Font Format形式のフォントを1つ表します"
type: docs
weight: 17
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

WOFF（Web Open Font Format）フォーマットのフォントを 1 つ表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | コンテンツ（base64エンコードされた形式）から新しいWoffFontクラスを作成します |
文字列で、指定された名前と共に
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | コンテンツ（バイトストリームとして表現された）から新しいWoffFontクラスを作成し、 |
指定された名前で
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | 検証に必要なWOFFヘッダーサイズ（バイト単位） |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効なWOFFフォントかどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定されたbase64エンコードされた文字列が有効なWOFFフォントかどうかをチェックします |
|
|  | [getType()](#getType--) | FontType.Woff を返します |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


コンテンツ（base64エンコードされた形式）から新しいWoffFontクラスを作成します
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | WOFF フォントの名前。null、空文字、または空白のみであってはなりません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツを base64 エンコードされた文字列として表します。null、空文字、または空白のみであってはなりません。WOFF コンテンツでない場合、例外がスローされます。 |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


コンテンツ（バイトストリームとして表現された）から新しいWoffFontクラスを作成し、
指定された名前で


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | WOFF フォントの名前。null、空文字、または空白のみであってはなりません。 |
|
|  | binaryContent | java.io.InputStream | コンテンツをバイトストリームとして表します。読み取りは元の位置から開始します。null であってはなりません。読み取り可能でシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


検証に必要なWOFFヘッダーサイズ（バイト単位）


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効なWOFFフォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | WOFF リソースを含んでいると推測されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な WOFF フォントを含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定されたbase64エンコードされた文字列が有効なWOFFフォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 推測される WOFF フォントのコンテンツを base64 エンコードされた文字列の形式で表します |
|

**Returns:**
boolean - 指定された文字列が有効な WOFF フォントを含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Woff を返します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
