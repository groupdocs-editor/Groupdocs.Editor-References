---
title: "SvgImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "SVG（Scalable Vector Graphics）形式でのベクタ画像を、メタデータの寸法と PNG への保存機能を持つ追加メソッドとともに表します"
type: docs
weight: 580
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

SVG（Scalable Vector Graphics）形式のベクター画像を表し、メタデータ（寸法）と追加メソッド（PNG への保存）を提供します。

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | バイトストリームとして表現されたコンテンツから、新しい SvgImage インスタンスを作成し、指定された名前を付けます |
| [SvgImage](svgimage#constructor_1)(string, string) | 通常の文字列として表現されたコンテンツから、新しい SvgImage インスタンスを作成し、指定された名前を付けます |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | このベクトル画像のアスペクト比を返します |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | この SVG 画像のコンテンツを元の位置を保持したバイナリストリームとして返します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | このベクトル画像の正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | このラスタ画像が破棄されているか (`true`) それともされていないか (`false`) を判定します |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | このベクトル画像の線形寸法（幅と高さ）を返します |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | このベクトル画像の名前を返します。通常、ファイル名拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | この SVG 画像のコンテンツを base64 エンコードされたバイナリコンテンツとして返します（XML 形式の生テキストとしてではなく） |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | `[Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg)` を返します |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | この SVG 画像のコンテンツを元の XML 準拠テキスト形式で返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | このラスター画像を破棄し、その内容も破棄して、ほとんどのメソッドとプロパティが機能しなくなります |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | この SVG 画像をファイルに保存します |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | このベクター SVG 画像をラスター PNG 画像に保存します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | 指定されたテキストの XML 準拠コンテンツが SVG 画像を表すかどうかを表面的にチェックします |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
