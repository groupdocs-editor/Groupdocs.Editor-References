---
title: "GifImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "GIF Graphics Interchange Format の画像を 1 つ表し、メタデータと追加メソッドを提供します。"
type: docs
weight: 500
url: /ja/net/groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
## GifImage class

GIF（Graphics Interchange Format）フォーマットの画像を、そのメタデータと追加メソッドとともに表します。

```csharp
public sealed class GifImage : RasterImageResourceBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GifImage](gifimage#constructor)(string, Stream) | バイトストリームとして表現されたコンテンツから新しい GifImage インスタンスを作成し、指定された名前を付けます。 |
| [GifImage](gifimage#constructor_1)(string, string) | Base64 エンコードされた文字列として表現されたコンテンツから新しい GifImage インスタンスを作成し、指定された名前を付けます。 |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/gifimage/type) { get; } | ImageType.Gif を返します。 |
| [Version](../../groupdocs.editor.htmlcss.resources.images.raster/gifimage/version) { get; } | この GIF 画像の内部バージョンを返します（バージョンはヘッダーから抽出されます）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | このラスター画像を破棄し、その内容も破棄して、ほとんどのメソッドとプロパティが機能しなくなります |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | このラスタ画像を指定されたファイルに保存します。 |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/gifimage/isvalid#isvalid)(Stream) | 指定されたストリームが有効な GIF 画像かどうかを確認します。 |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/gifimage/isvalid#isvalid_1)(string) | 指定された base64 エンコード文字列が有効な GIF 画像かどうかをチェックします |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
