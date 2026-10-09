---
title: "Woff2Font"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "WOFF2 Web Open Font Format 形式のフォントを表します"
type: docs
weight: 16
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

WOFF2（Web Open Font Format）フォーマットのフォントを 1 つ表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | コンテンツを base64 エンコードされた形式で表したものから新しい Woff2Font クラスを作成します |
文字列で、指定された名前と共に
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | コンテンツをバイトストリームとして表したものから新しい Woff2Font クラスを作成し、 |
指定された名前で
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | 検証に必要な WOFF2 ヘッダーサイズ（バイト単位） |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な WOFF2 フォントかどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な WOFF2 フォントかどうかをチェックします |
|
|  | [getType()](#getType--) | FontType.Woff2 を返します |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


コンテンツを base64 エンコードされた形式で表したものから新しい Woff2Font クラスを作成します
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | WOFF2 フォントの名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | base64 エンコードされた文字列としてのコンテンツ。null、空、または空白文字にできません。WOFF2 コンテンツでない場合は例外がスローされます。 |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


コンテンツをバイトストリームとして表したものから新しい Woff2Font クラスを作成し、
指定された名前で


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | WOFF2 フォントの名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | コンテンツをバイトストリームとして表します。読み取りは元の位置から開始します。null であってはなりません。読み取り可能でシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


検証に必要な WOFF2 ヘッダーサイズ（バイト単位）


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な WOFF2 フォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | WOFF2 リソースを含んでいると推測されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な WOFF2 フォントを含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な WOFF2 フォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 推測される WOFF2 フォントのコンテンツを base64 エンコード文字列の形で |
|

**Returns:**
boolean - 指定された文字列が有効な WOFF2 フォントを含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Woff2 を返します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
