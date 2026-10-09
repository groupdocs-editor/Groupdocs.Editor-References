---
title: "RasterImageResourceBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "固定された名前、寸法、アスペクト比、タイプ、サイズ、コンテンツを持つ、サポートされるすべてのラスタ画像の基底クラスです。"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

固定された名前、寸法、アスペクト
比率、タイプ、サイズ、コンテンツです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Disposed](#Disposed) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | このラスタ画像の名前を返します。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | このラスタ画像の正しいファイル名を返します。ファイル名は名前と |
拡張子です。
|
|  | [getLinearDimensions()](#getLinearDimensions--) | このラスタ画像の線形寸法（幅と高さ）を返します。 |
|
|  | [getAspectRatio()](#getAspectRatio--) | この画像の幅対高さの関係としてアスペクト比を返します。 |
|
|  | [getLength()](#getLength--) | このラスタ画像ファイルのバイト単位の長さを返します。 |
|
|  | [getByteContent()](#getByteContent--) | このラスタ画像のコンテンツをバイトストリームとして返します。 |
|
|  | [getTextContent()](#getTextContent--) | このラスタ画像のコンテンツを base64 エンコード文字列として返します。 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | このラスタ画像を指定されたファイルに保存します。 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | このインスタンスが指定されたものと参照等価かどうかをチェックします。 |
|
|  | [dispose()](#dispose--) | このラスタ画像を破棄し、コンテンツも破棄して、ほとんどのメソッドを |
およびプロパティが機能しなくなります。
|
|  | [isDisposed()](#isDisposed--) | このラスター画像が破棄されているかどうかを判定します |
|
|  | [getType()](#getType--) | 実装時には、ラスターのタイプに関する情報を返す必要があります |
画像
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


このラスター画像の名前を返します。通常、ファイル名は含まれません
拡張子で、理論的にはファイル名と異なる場合があります。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


このラスタ画像の正しいファイル名を返します。ファイル名は名前と
拡張子。理論的には名前と異なる場合があります。


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


このラスタ画像の線形寸法（幅と高さ）を返します。


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


この画像の幅対高さの関係としてアスペクト比を返します。


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


このラスタ画像ファイルのバイト単位の長さを返します。


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


このラスタ画像のコンテンツをバイトストリームとして返します。


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


このラスタ画像のコンテンツを base64 エンコード文字列として返します。


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


このラスタ画像を指定されたファイルに保存します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 作成または上書きされるファイルへのフルパス |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


このインスタンスが指定されたものと参照等価かどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | その他の IHtmlResource 継承クラス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### dispose() {#dispose--}
```
public final void dispose()
```


このラスタ画像を破棄し、コンテンツも破棄して、ほとんどのメソッドを
およびプロパティが機能しなくなります。


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


このラスター画像が破棄されているかどうかを判定します


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


実装時には、ラスターのタイプに関する情報を返す必要があります
画像


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
