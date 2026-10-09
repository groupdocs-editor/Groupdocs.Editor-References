---
title: "IImageResource"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "ラスタまたはベクタの任意のタイプの画像リソースを表します"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

任意のタイプ（ラスタまたはベクトル）の画像リソースを表します。


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getType()](#getType--) | 実装時の型は、特定の画像のタイプとして返すべきです |
特定の ImageType のインスタンスで、タイプ固有の情報をすべてカプセル化します
|
|  | [getAspectRatio()](#getAspectRatio--) | 実装時の型は、特定の画像のアスペクト比を返すべきです |
タイプに関係なく。
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 実装時の型は、画像の線形寸法を返すべきです。 |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


実装時の型は、特定の画像のタイプとして返すべきです
特定の ImageType のインスタンスで、タイプ固有の情報をすべてカプセル化します


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


実装時の型は、特定の画像のアスペクト比を返すべきです
タイプに関係なく。ベクター画像とラスタ画像の両方は固有の
幅と高さの間のアスペクト比です。


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


実装時の型は、画像の線形寸法を返すべきです。対象は
ラスタ画像の場合、ピクセル単位の固有寸法です。ベクター画像は、
対照的に、固定された寸法はありませんが、メタデータに
異なる測定単位での基本的な寸法が含まれることがあります。


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
