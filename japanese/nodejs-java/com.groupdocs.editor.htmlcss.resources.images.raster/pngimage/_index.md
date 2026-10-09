---
title: "PngImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PNG Portable Network Graphics 形式の画像を 1 つ表し、メタデータと追加メソッドを提供します"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

PNG（Portable Network Graphics）形式の画像を 1 つ表し、
メタデータと追加メソッド

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | コンテンツから新しい PngImage インスタンスを作成します（base64 エンコードとして表現） |
文字列で、指定された名前と共に
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい PngImage インスタンスを作成します（バイトストリームとして表現） |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な PNG 画像かどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な PNG 画像かどうかをチェックします |
|
|  | [getType()](#getType--) | ImageType.Png を返します |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


コンテンツから新しい PngImage インスタンスを作成します（base64 エンコードとして表現）
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | PNG 画像の名前。null、空、または空白文字にできません |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 エンコード文字列です。null、空、または空白文字にできません。PNG コンテンツでない場合、例外がスローされます |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


コンテンツから新しい PngImage インスタンスを作成します（バイトストリームとして表現）
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | PNG 画像の名前。null、空、または空白文字にできません |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な PNG 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | バイトストリーム、恐らく PNG 画像を含む |
|

**Returns:**
boolean - 指定されたストリームが有効な PNG 画像を含む場合は True、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な PNG 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 恐らく PNG 画像のコンテンツを base64 エンコードされた文字列として |
|

**Returns:**
boolean - 指定された文字列が有効な PNG 画像を含む場合は True、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Png を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
