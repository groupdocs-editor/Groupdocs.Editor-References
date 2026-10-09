---
title: "ImageType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポート可能な画像タイプ形式を表し、ラスタ形式とベクター形式の両方をサポートします"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

サポート可能な画像タイプ（フォーマット）を1つ表し、ラスタ形式とベクトル形式の両方をサポートします。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 未定義の画像タイプ - 通常は発生すべきでない特別な値 |
|
|  | [getJpeg()](#getJpeg--) | JPEG 画像タイプ |
|
|  | [getPng()](#getPng--) | PNG 画像タイプ |
|
|  | [getBmp()](#getBmp--) | BMP 画像タイプ |
|
|  | [getGif()](#getGif--) | GIF 画像タイプ |
|
|  | [getIcon()](#getIcon--) | ICON 画像タイプ |
|
|  | [getSvg()](#getSvg--) | SVG ベクター画像タイプ |
|
|  | [getWmf()](#getWmf--) | WMF（Windows MetaFile）ベクター画像タイプ |
|
|  | [getEmf()](#getEmf--) | EMF（Enhanced MetaFile）ベクター画像タイプ |
|
|  | [getTiff()](#getTiff--) | TIFF（Tagged Image File Format）ラスタ画像タイプ |
|
|  | [getFormalName()](#getFormalName--) | この画像フォーマットの正式名称を返します。 |
|
|  | [isVector()](#isVector--) | この特定のフォーマットがベクター（true）かラスタかを示します |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | 特定の画像タイプのファイル拡張子（先頭のドット文字なし） |
小文字で。
|
|  | [toString()](#toString--) | FormalName プロパティを返します |
|
|  | [getMimeCode()](#getMimeCode--) | 特定の画像タイプの MIME コードを文字列として返します。 |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | このインスタンスが指定された "ImageType" と等しいかどうかを判定します |
インスタンス
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、 |
それはおそらく別の "ImageType" インスタンスです
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 2つの特定の ImageType インスタンスが等しいかどうかを定義します |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 2つの特定の ImageType インスタンスが等しくないかどうかを定義します |
|
|  | [hashCode()](#hashCode--) | ハッシュコードを返します。これはこの特定のものに対する不変の数値です |
インスタンス
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | ファイル名拡張子に相当する ImageType の値を返します、 |
は指定されたファイル名から抽出されます
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | 指定された MIME コードに相当する ImageType の値を返します |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


未定義の画像タイプ - 通常は発生すべきでない特別な値


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG 画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG 画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP 画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF 画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON 画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG ベクター画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF（Windows MetaFile）ベクター画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF（Enhanced MetaFile）ベクター画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF（Tagged Image File Format）ラスタ画像タイプ


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


この画像フォーマットの正式名称を返します。NULL を返すことはありません。もし
インスタンスが破損していない場合、例外は決してスローされません。


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


この特定のフォーマットがベクター（true）かラスタかを示します
(false)


**Returns:**
ブール
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


特定の画像タイプのファイル拡張子（先頭のドット文字なし）
小文字で。Undefined タイプの場合は文字列 'unsefined' を返します。


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


FormalName プロパティを返します


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


特定の画像タイプの MIME コードを文字列として返します。Undefined タイプの場合
文字列 'unsefined' を返します。


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


このインスタンスが指定された "ImageType" と等しいかどうかを判定します
インスタンス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | このインスタンスと等価かどうかをチェックする他の ImageType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、
それはおそらく別の "ImageType" インスタンスです


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | このインスタンスと等価かどうかをチェックする、ImageType 型であると推測される他の System.Object インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


2つの特定の ImageType インスタンスが等しいかどうかを定義します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | チェックする最初の ImageType インスタンス |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | チェックする2番目の ImageType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


2つの特定の ImageType インスタンスが等しくないかどうかを定義します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | チェックする最初の ImageType インスタンス |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | チェックする2番目の ImageType インスタンス |
|

**Returns:**
boolean - 不等の場合は True、等しい場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


ハッシュコードを返します。これはこの特定のものに対する不変の数値です
インスタンス


**Returns:**
int - 符号付き 4 バイト整数

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


ファイル名拡張子に相当する ImageType の値を返します、
は指定されたファイル名から抽出されます


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ファイル名 | java.lang.String | 任意のファイル名で、相対パスまたはフルパスにすることができます |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


指定された MIME コードに相当する ImageType の値を返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | mimeCode | java.lang.String | 任意の MIME コード |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

