---
title: "PngImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "PNG Portable Network Graphics 形式の画像を 1 つ表し、メタデータと追加メソッドを提供します"
type: docs
weight: 530
url: /ja/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
## PngImage class

PNG（Portable Network Graphics）フォーマットの画像を、そのメタデータと追加メソッドとともに表します。

```csharp
public sealed class PngImage : RasterImageResourceBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PngImage](pngimage#constructor)(string, Stream) | コンテンツ（バイトストリームで表現）と指定された名前から新しい PngImage インスタンスを作成します |
| [PngImage](pngimage#constructor_1)(string, string) | コンテンツ（base64 エンコード文字列で表現）と指定された名前から新しい PngImage インスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | この画像の幅と高さの比率としてアスペクト比を返します。 |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | このラスタ画像のコンテンツをバイトストリームとして返します。 |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | このラスタ画像の正しいファイル名（名前と拡張子から構成）を返します。理論的には名前と異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | このラスタ画像が破棄されているかどうかを判定します。 |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | このラスタ画像ファイルの長さ（バイト数）を返します。 |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | このラスタ画像の線形寸法（幅と高さ）を返します。 |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | このラスタ画像の名前を返します。通常はファイル名の拡張子を含まず、理論的にはファイル名と異なる場合があります。 |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | このラスタ画像のコンテンツを Base64 エンコードされた文字列として返します。 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/type) { get; } | ImageType.Png を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | このラスター画像を破棄し、その内容も破棄して、ほとんどのメソッドとプロパティが機能しなくなります |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | このラスタ画像を指定されたファイルに保存します。 |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/isvalid#isvalid)(Stream) | 指定されたストリームが有効な PNG 画像かどうかをチェックします |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/isvalid#isvalid_1)(string) | 指定された base64 エンコード文字列が有効な PNG 画像かどうかをチェックします |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
