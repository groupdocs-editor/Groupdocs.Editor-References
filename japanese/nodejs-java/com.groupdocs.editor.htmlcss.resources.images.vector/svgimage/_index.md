---
title: "SvgImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "SVG（Scalable Vector Graphics）形式のベクター画像を表し、メタデータと追加メソッドを提供します"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

SVG（Scalable Vector Graphics）形式のベクター画像を表し、その
メタデータと追加メソッド

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | コンテンツから新しい SvgImage インスタンスを作成し、通常の文字列として表現します、 |
指定された名前と共に
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい SvgImage インスタンスを作成し、バイトストリームとして表現します、 |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | 指定されたテキストの XML 準拠コンテンツが有効かどうかの表面チェックを実行します |
SVG画像を表します
|
|  | [getType()](#getType--) | ImageType.Svg を返します |
|
|  | [getByteContent()](#getByteContent--) | このSVG画像の内容をバイナリストリームとして返します |
|
|  | [getTextContent()](#getTextContent--) | このSVG画像の内容をプレーンテキスト（XML形式）で返します |
|
|  | [getXmlContent()](#getXmlContent--) | このSVG画像の内容を元のXML準拠形式で返します |
テキスト形式
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | このSVG画像をファイルに保存します |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | このベクターSVG画像をラスタPNG画像に保存します |
|
|  | [dispose()](#dispose--) | このラスタ画像を破棄し、コンテンツも破棄して、ほとんどのメソッドを |
およびプロパティが機能しなくなります。
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


コンテンツから新しい SvgImage インスタンスを作成し、通常の文字列として表現します、
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | SVG画像の名前。null、空、または空白文字にできません。 |
|
|  | コンテンツ | java.lang.String | 通常の文字列としてのコンテンツで、SVG画像の有効なXML準拠コンテンツが含まれます。null、空、または空白文字にできません。SVGコンテンツでない場合、例外がスローされます。 |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


コンテンツから新しい SvgImage インスタンスを作成し、バイトストリームとして表現します、
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | SVG画像の名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


指定されたテキストの XML 準拠コンテンツが有効かどうかの表面チェックを実行します
SVG画像を表します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | コンテンツ | java.lang.String | SVG画像のXMLコンテンツを単純なテキストとして、Base64エンコードされたコンテンツではなく提供します |
|

**Returns:**
boolean - 指定された文字列が最初の見た目で有効なSVGとみなせる場合はTrue、確実にSVGでない場合はfalse

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Svg を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


このSVG画像の内容をバイナリストリームとして返します


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


このSVG画像の内容をプレーンテキスト（XML形式）で返します


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


このSVG画像の内容を元のXML準拠形式で返します
テキスト形式


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


このSVG画像をファイルに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | このSVG画像の内容で作成（存在しない場合）または上書き（存在する場合）されるファイルへのフルパス |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


このベクターSVG画像をラスタPNG画像に保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | PNG 画像のコンテンツが書き込まれる出力ストリーム。NULL であってはならず、書き込み可能である必要があります。 |
|

### dispose() {#dispose--}
```
public void dispose()
```


このラスタ画像を破棄し、コンテンツも破棄して、ほとんどのメソッドを
およびプロパティが機能しなくなります。


