---
title: "BmpImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "BMP BitMap Picture 形式の画像を 1 つ表し、そのメタデータと追加メソッドを提供します"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

BMP (BitMap Picture) 形式の画像を 1 つ表し、そのメタデータと
追加メソッド

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | コンテンツから新しい BmpImage インスタンスを作成し、base64 エンコードされた形式で |
文字列で、指定された名前と共に
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい BmpImage インスタンスを作成し、バイトストリームとして表現します、 |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な BMP 画像かどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な BMP 画像かどうかをチェックします |
|
|  | [getType()](#getType--) | ImageType.Bmp を返します |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


コンテンツから新しい BmpImage インスタンスを作成し、base64 エンコードされた形式で
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | BMP 画像の名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツを base64 エンコード文字列として表します。null、空、または空白文字にできません。BMP コンテンツでない場合、例外がスローされます。 |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


コンテンツから新しい BmpImage インスタンスを作成し、バイトストリームとして表現します、
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | BMP 画像の名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な BMP 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | BMP 画像を含んでいると推測されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な BMP 画像を含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な BMP 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 推測される BMP 画像のコンテンツを base64 エンコード文字列の形で表します |
|

**Returns:**
boolean - 指定された文字列が有効な BMP 画像を含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Bmp を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
