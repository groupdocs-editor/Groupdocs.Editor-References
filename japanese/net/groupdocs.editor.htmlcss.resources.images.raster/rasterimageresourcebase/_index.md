---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "固定された名前、寸法、アスペクト比、タイプ、サイズ、コンテンツを持つ、サポートされるすべてのラスター画像の基底クラスです。"
type: docs
weight: 540
url: /ja/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

固定された名前、寸法、アスペクト比、タイプ、サイズ、コンテンツを持つ、サポートされるすべてのラスタ画像の基底クラスです。

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

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
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | 実装時には、ラスター画像のタイプに関する情報を返す必要があります |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | このラスター画像を破棄し、その内容も破棄して、ほとんどのメソッドとプロパティが機能しなくなります |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | このラスタ画像を指定されたファイルに保存します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
