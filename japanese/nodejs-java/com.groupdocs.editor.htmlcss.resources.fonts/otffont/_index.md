---
title: "OtfFont"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "OTF Open Type Format形式のフォントを1つ表します"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

OTF（Open Type Format）フォーマットのフォントを 1 つ表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | コンテンツ（base64エンコードされた形式）から新しいOtfFontクラスを作成します |
文字列で、指定された名前と共に
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | コンテンツ（バイトストリームとして表現された）から新しいOtfFontクラスを作成し、 |
指定された名前で
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | 検証に必要なOTFヘッダーサイズ（バイト単位） |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効なOTFフォントかどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定されたbase64エンコードされた文字列が有効なOTFフォントかどうかをチェックします |
|
|  | [getType()](#getType--) | 戻り値 |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


コンテンツ（base64エンコードされた形式）から新しいOtfFontクラスを作成します
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | OTFフォントの名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツをbase64エンコードされた文字列として。null、空、または空白文字にできません。OTFコンテンツでない場合、例外がスローされます。 |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


コンテンツ（バイトストリームとして表現された）から新しいOtfFontクラスを作成し、
指定された名前で


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | OTFフォントの名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


検証に必要なOTFヘッダーサイズ（バイト単位）


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効なOTFフォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | OTFリソースを含むと推定されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効なOTFフォントを含む場合はTrue、そうでない場合はfalse

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定されたbase64エンコードされた文字列が有効なOTFフォントかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 推定されるOTFフォントのコンテンツをbase64エンコードされた文字列の形式で |
|

**Returns:**
boolean - 指定された文字列が有効なOTFフォントを含む場合はTrue、そうでない場合はfalse

### getType() {#getType--}
```
public FontType getType()
```


戻り値
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
