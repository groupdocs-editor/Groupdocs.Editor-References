---
title: "TiffImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "TIFF Tagged Image File Format 形式の画像を表し、メタデータと追加メソッドを備えています"
type: docs
weight: 16
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

TIFF (Tagged Image File Format) 形式の画像を表し、その
メタデータと追加メソッド


*** ** * ** ***

詳細は https://en.wikipedia.org/wiki/TIFF を参照してください。非常に稀なケースでは、TIFF が WordProcessing ドキュメント内に存在することがあります。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | コンテンツから新しい TiffImage インスタンスを作成します。表現は |
base64 エンコードされた文字列で、指定された名前と共に
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい GifImage インスタンスを作成します（バイトストリームとして表現） |
指定された名前と共に
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な TIFF 画像かどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な TIFF 画像かどうかをチェックします |
|
|  | [getType()](#getType--) | ImageType.Tiff を返します |
|
|  | [getFramesCount()](#getFramesCount--) | この TIFF 画像内のフレーム（画像）の数を返します |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


コンテンツから新しい TiffImage インスタンスを作成します。表現は
base64 エンコードされた文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | TIFF 画像の名前。null、空、または空白文字にできません |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 エンコード文字列です。null、空、または空白文字にできません。TIFF コンテンツでない場合、例外がスローされます |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
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

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な TIFF 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | おそらく TIFF 画像を含むバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な TIFF 画像を含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な TIFF 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | おそらく TIFF 画像のコンテンツ（base64 エンコード文字列形式） |
|

**Returns:**
boolean - 指定された文字列が有効な TIFF 画像を含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Tiff を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


この TIFF 画像内のフレーム（画像）の数を返します。できません
1 未満


**Returns:**
int -
