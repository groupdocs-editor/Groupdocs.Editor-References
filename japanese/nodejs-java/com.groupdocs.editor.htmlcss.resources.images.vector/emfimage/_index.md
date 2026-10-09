---
title: "EmfImage"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "拡張メタファイル形式（EMF）でのベクター画像を表し、そのメタデータと追加メソッドを提供します"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

拡張メタファイル形式（EMF）でのベクター画像を表し、その
メタデータと追加メソッド

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | コンテンツから新しい EmfImage インスタンスを作成し、base64 エンコードとして表現します |
文字列で、指定された名前と共に
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | コンテンツから新しい EmfImage インスタンスを作成し、バイトストリームとして表現します、 |
指定された名前と共に
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 指定されたストリームが有効な EMF 画像かどうかをチェックします |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 指定された base64 エンコード文字列が有効な EMF 画像かどうかをチェックします |
|
|  | [getType()](#getType--) | ImageType.Emf を返します |
|
|  | [getByteContent()](#getByteContent--) | この EMF 画像のコンテンツをバイナリストリームとして返します |
|
|  | [getTextContent()](#getTextContent--) | この EMF 画像のコンテンツをプレーンテキストとして返します |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | この EMF 画像をファイルに保存します |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | このベクター EMF 画像をラスタ PNG 画像に保存します |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | このベクター EMF 画像をベクター SVG 画像に保存します |
|
|  | [dispose()](#dispose--) | この EMF 画像をコンテンツを破棄し、ほとんどのリソースを解放することで破棄します |
メソッドとプロパティが機能しなくなります
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


コンテンツから新しい EmfImage インスタンスを作成し、base64 エンコードとして表現します
文字列で、指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | EMF 画像の名前。null、空、または空白文字にできません。 |
|
|  | contentInBase64 | java.lang.String | コンテンツは base64 エンコード文字列です。null、空、または空白文字にできません。EMF コンテンツでない場合は例外がスローされます。 |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


コンテンツから新しい EmfImage インスタンスを作成し、バイトストリームとして表現します、
指定された名前と共に


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | EMF 画像の名前。null、空、または空白文字にできません。 |
|
|  | binaryContent | java.io.InputStream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


指定されたストリームが有効な EMF 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 入力バイトストリーム。NULL であってはならず、読み取りとシークをサポートする必要があります。 |
|

**Returns:**
boolean - 指定されたストリームが有効な EMF 画像を保持している場合は true、そうでない場合は false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


指定された base64 エンコード文字列が有効な EMF 画像かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 入力文字列。EMF 画像のコンテンツが base64 エンコードで格納されています。NULL または空にできません。 |
|

**Returns:**
boolean - 指定された文字列が有効な EMF 画像を保持している場合は true、そうでない場合は false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Emf を返します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


この EMF 画像のコンテンツをバイナリストリームとして返します


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


この EMF 画像のコンテンツをプレーンテキストとして返します


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


この EMF 画像をファイルに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | この EMF 画像のコンテンツで作成（存在しない場合）または上書き（存在する場合）されるファイルへのフルパス |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


このベクター EMF 画像をラスタ PNG 画像に保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | PNG 画像のコンテンツが書き込まれる出力ストリーム。NULL であってはならず、書き込み可能である必要があります。 |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


このベクター EMF 画像をベクター SVG 画像に保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | SVG 画像のコンテンツが書き込まれる出力ストリーム。NULL であってはならず、書き込み可能である必要があります。 |
|

### dispose() {#dispose--}
```
public void dispose()
```


この EMF 画像をコンテンツを破棄し、ほとんどのリソースを解放することで破棄します
メソッドとプロパティが機能しなくなります


