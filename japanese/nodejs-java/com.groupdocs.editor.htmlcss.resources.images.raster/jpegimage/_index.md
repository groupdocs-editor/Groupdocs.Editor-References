---
title: "JpegImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "JPEG Joint Photographic Experts Group 形式の画像を 1 つ表し、そのメタデータと追加メソッドを提供します"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

JPEG (Joint Photographic Experts Group) 形式の画像を 1 つ表し、
そのメタデータと追加メソッド

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | コンテンツから新しい JpegImage インスタンスを作成し、表現形式は |
base64 エンコードされた文字列で、指定された名前と共に
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい JpegImage インスタンスを作成し、バイトストリームとして表現します、 |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な JPEG 画像かどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコードされた文字列が有効な JPEG 画像かどうかをチェックします |
|
|  | [getType()](#getType--) | ImageType.Jpeg を返します |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


コンテンツから新しい JpegImage インスタンスを作成し、表現形式は
base64 エンコードされた文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | JPEG 画像の名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツを base64 エンコードされた文字列として表します。null、空、または空白文字にできません。JPEG コンテンツでない場合、例外がスローされます。 |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


コンテンツから新しい JpegImage インスタンスを作成し、バイトストリームとして表現します、
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | JPEG 画像の名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な JPEG 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | バイトストリーム、恐らく JPEG 画像を含む |
|

**Returns:**
boolean - 指定されたストリームが有効な JPEG 画像を含む場合は True、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコードされた文字列が有効な JPEG 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 恐らく JPEG 画像のコンテンツを base64 エンコードされた文字列として |
|

**Returns:**
boolean - 指定された文字列が有効な JPEG 画像を含む場合は True、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Jpeg を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
