---
title: "IImageResource"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ラスタまたはベクターの任意のタイプの画像リソースを表します"
type: docs
weight: 470
url: /ja/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

任意のタイプ（ラスタまたはベクタ）の画像リソースを表します。

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | 実装時には、タイプに関係なく特定の画像のアスペクト比を返す必要があります。ベクター画像とラスタ画像の両方は、幅と高さの間に固有のアスペクト比を持ちます。 |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | 実装時には、画像の線形寸法を返す必要があります。ラスタ画像の場合、ピクセル単位の固有寸法です。ベクター画像は固定寸法を持ちませんが、メタデータに異なる測定単位で基本的な寸法が含まれることがあります。 |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | 実装時には、すべてのタイプ固有情報をカプセル化した特定の ImageType のインスタンスとして、特定画像のタイプを返す必要があります。 |

### 備考

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### 参照

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
