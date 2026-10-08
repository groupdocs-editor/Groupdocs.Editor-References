---
title: "WmfImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "WMF Windows MetaFile 形式のベクトル画像を 1 つ表し、メタデータと追加メソッドを提供します"
type: docs
weight: 600
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

WMF（Windows MetaFile）形式のベクター画像を表し、そのメタデータと追加メソッドを提供します。

```csharp
public sealed class WmfImage : MetaImageBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | バイトストリームとして表現されたコンテンツと指定された名前で新しい WmfImage インスタンスを作成します |
| [WmfImage](wmfimage#constructor_1)(string, string) | base64 エンコードされた文字列として表現されたコンテンツと指定された名前で新しい WmfImage インスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | このベクトル画像のアスペクト比を返します |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | この WMF 画像の内容をバイナリストリームとして返します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | このベクトル画像の正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | このラスタ画像が破棄されているか (`true`) それともされていないか (`false`) を判定します |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | このベクトル画像の線形寸法（幅と高さ）を返します |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | このベクトル画像の名前を返します。通常、ファイル名拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | この WMF 画像の内容をプレーンテキストとして返します |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | ImageType.Wmf を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | この WMF 画像をコンテンツを破棄し、ほとんどのメソッドとプロパティを使用不可にすることで破棄します |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | この WMF 画像をファイルに保存します |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | このベクタ WMF 画像をラスタ PNG 画像に保存します |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | このベクタ WMF 画像をベクタ SVG 画像に保存します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | 指定されたストリームが有効な WMF 画像かどうかをチェックします |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | 指定された base64 エンコード文字列が有効な WMF 画像かどうかをチェックします |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
