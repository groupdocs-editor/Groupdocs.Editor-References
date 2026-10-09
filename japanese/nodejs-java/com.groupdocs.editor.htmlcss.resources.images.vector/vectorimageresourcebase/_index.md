---
title: "VectorImageResourceBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされているすべてのベクター画像の基本クラス"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

サポートされているすべてのベクター画像の基本クラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Disposed](#Disposed) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | このベクター画像の名前を返します。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | このベクター画像の正しいファイル名を返します。名前と |
拡張子です。
|
|  | [getAspectRatio()](#getAspectRatio--) | このベクター画像のアスペクト比を返します |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | このベクター画像の線形寸法（幅と高さ）を返します |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | このインスタンスが指定されたものと参照等価かどうかをチェックします。 |
|
|  | [isDisposed()](#isDisposed--) | このラスター画像が破棄されているかどうかを判定します |
|
|  | [getType()](#getType--) | 実装時には、ベクターのタイプに関する情報を返す必要があります |
画像
|
|  | [getByteContent()](#getByteContent--) | 実装時には、このベクター画像の内容をバイトとして返す必要があります |
ストリーム
|
|  | [getTextContent()](#getTextContent--) | 実装時には、このベクター画像の内容をテキストで返す必要があります |
形式: 画像タイプに関する XML の Base64 エンコード
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 実装時には、指定されたパスでこの画像をディスクに保存する必要があります |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 実装時には、現在のベクター画像をラスター PNG に保存する必要があります |
指定されたバイトストリームにフォーマットします
|
|  | [dispose()](#dispose--) | 実装時には、このインスタンスを破棄する必要があります |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


このベクター画像の名前を返します。通常、ファイル名は含まれません
拡張子で、理論的にはファイル名と異なる場合があります。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


このベクター画像の正しいファイル名を返します。名前と
拡張子。理論的には名前と異なる場合があります。


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


このベクター画像のアスペクト比を返します


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


このベクター画像の線形寸法（幅と高さ）を返します


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


このインスタンスが指定されたものと参照等価かどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | ベクター画像のその他のインスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

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


実装時には、ベクターのタイプに関する情報を返す必要があります
画像


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


実装時には、このベクター画像の内容をバイトとして返す必要があります
ストリーム


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


実装時には、このベクター画像の内容をテキストで返す必要があります
形式: 画像タイプに関する XML の Base64 エンコード


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


実装時には、指定されたパスでこの画像をディスクに保存する必要があります


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


実装時には、現在のベクター画像をラスター PNG に保存する必要があります
指定されたバイトストリームにフォーマットします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | バイトストリームで、ここにこのラスタ画像の PNG バージョンが格納されます。NULL であってはならず、書き込みをサポートしている必要があります。 |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


実装時には、このインスタンスを破棄する必要があります


