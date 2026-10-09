---
title: "GifImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "GIF Graphics Interchange Format 形式の画像を表し、メタデータと追加メソッドを備えています"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

GIF (Graphics Interchange Format) 形式の画像を表し、その
メタデータと追加メソッド

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | コンテンツから新しい GifImage インスタンスを作成します（base64 エンコードされた形式で表現） |
文字列で、指定された名前と共に
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい GifImage インスタンスを作成します（バイトストリームとして表現） |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な GIF 画像かどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコードされた文字列が有効な GIF 画像かどうかをチェックします |
|
|  | [getType()](#getType--) | ImageType.Gif を返します |
|
|  | [getVersion()](#getVersion--) | この GIF 画像の内部バージョンを返します（バージョンは |
ヘッダー）
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


コンテンツから新しい GifImage インスタンスを作成します（base64 エンコードされた形式で表現）
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | GIF 画像の名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 エンコードされた文字列です。null、空、または空白文字にできません。GIF コンテンツでない場合、例外がスローされます。 |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


コンテンツから新しい GifImage インスタンスを作成します（バイトストリームとして表現）
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | GIF 画像の名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な GIF 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | バイトストリームで、恐らく GIF 画像が含まれています |
|

**Returns:**
boolean - 指定されたストリームが有効な GIF 画像を含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコードされた文字列が有効な GIF 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 恐らく GIF 画像の内容を base64 エンコードされた文字列として |
|

**Returns:**
boolean - 指定された文字列が有効な GIF 画像を含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Gif を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


この GIF 画像の内部バージョンを返します（バージョンは
ヘッダー）


**Returns:**
java.lang.String
