---
title: "MetaImageBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "WMF および EMF 画像形式の基本抽象クラス"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

WMF および EMF 画像形式の基本抽象クラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | 共通コンストラクタで、WMF または EMF インスタンスの作成を準備します。 |
base64 エンコードされた文字列
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | 共通コンストラクタで、WMF または EMF インスタンスの作成を準備します。 |
バイトストリーム
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | 指定されたバイトストリームが有効な WMF 画像を含むかどうかを判定します |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | 指定された文字列が有効な WMF 画像を含むかどうかを判定します、これは |
base64 でエンコードされた
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | 指定されたバイトストリームが有効な EMF 画像を含むかどうかを判定します |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | 指定された文字列が有効な EMF 画像を含むかどうかを判定します、これは |
base64 でエンコードされた
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 実装タイプでは、現在のベクターメタ画像を次の場所に保存する必要があります |
ベクター SVG 形式で指定されたバイトストリームへ
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


共通コンストラクタで、WMF または EMF インスタンスの作成を準備します。
base64 エンコードされた文字列


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | 必須の名前 |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 文字列です。NULL または空であってはなりません。 |
|
|  | isWmf | ブール | WMF の場合は true、EMF の場合は false |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


共通コンストラクタで、WMF または EMF インスタンスの作成を準備します。
バイトストリーム


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | 必須の名前 |
|
|  | binaryContent | java.io.InputStream | コンテンツはバイトストリームです。有効である必要があります。 |
|
|  | isWmf | ブール | WMF の場合は true、EMF の場合は false |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


指定されたバイトストリームが有効な WMF 画像を含むかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 入力バイトストリームです。有効である必要があります。 |
|

**Returns:**
boolean - 有効な場合は 'true'、無効な場合は 'false' を返します

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


指定された文字列が有効な WMF 画像を含むかどうかを判定します、これは
base64 でエンコードされた


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 文字列で、base64 エンコードされた WMF 画像を含むと想定されます |
|

**Returns:**
boolean - 有効な場合は 'true'、無効な場合は 'false' を返します

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


指定されたバイトストリームが有効な EMF 画像を含むかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 入力バイトストリームです。有効である必要があります。 |
|

**Returns:**
boolean - 有効な場合は 'true'、無効な場合は 'false' を返します

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


指定された文字列が有効な EMF 画像を含むかどうかを判定します、これは
base64 でエンコードされた


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 文字列で、base64 エンコードされた EMF 画像を含むと想定されます |
|

**Returns:**
boolean - 有効な場合は 'true'、無効な場合は 'false' を返します

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


実装タイプでは、現在のベクターメタ画像を次の場所に保存する必要があります
ベクター SVG 形式で指定されたバイトストリームへ


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | バイトストリームで、ここにこのベクターメタ画像の SVG バージョンが格納されます。NULL であってはならず、書き込みをサポートしている必要があります。 |
|

