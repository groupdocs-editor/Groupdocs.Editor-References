---
title: "IconImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "ICON 形式の画像を 1 つ表し、そのメタデータと追加のメソッドを提供します"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

ICON 形式の画像を 1 つ表し、そのメタデータと追加のメソッドを提供します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | コンテンツから新しい IconImage インスタンスを作成します、表現は |
base64 エンコードされた文字列で、指定された名前と共に
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい IconImage インスタンスを作成します、バイトストリームとして表現され、 |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な ICON 画像かどうかを確認します |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な ICON 画像かどうかを確認します |
|
|  | [getType()](#getType--) | ImageType.Icon を返します |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | この ICON ファイルに含まれる画像の数を返します |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


コンテンツから新しい IconImage インスタンスを作成します、表現は
base64 エンコードされた文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | ICON 画像の名前。null、空、または空白文字にすることはできません。 |
|
|  | contentInBase64 | java.lang.String | base64 エンコードされた文字列としてのコンテンツ。null、空、または空白文字にすることはできません。ICON コンテンツでない場合、例外がスローされます。 |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


コンテンツから新しい IconImage インスタンスを作成します、バイトストリームとして表現され、
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | ICON 画像の名前。null、空、または空白文字にすることはできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な ICON 画像かどうかを確認します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | バイトストリームで、恐らく ICON 画像が含まれています |
|

**Returns:**
boolean - 指定されたストリームが有効な ICON 画像を含む場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な ICON 画像かどうかを確認します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 恐らく ICON 画像の内容を base64 エンコードされた文字列として |
|

**Returns:**
boolean - 指定された文字列が有効な ICON 画像を含む場合は true、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Icon を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


この ICON ファイルに含まれる画像の数を返します


**Returns:**
int
