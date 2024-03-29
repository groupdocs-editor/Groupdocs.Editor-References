---
title: WmfImage
second_title: GroupDocs.Editor for .NET API リファレンス
description: メタデータと追加メソッドを含む WMF Windows MetaFile 形式の 1 つのベクター画像を表します
type: docs
weight: 610
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

メタデータと追加メソッドを含む WMF (Windows MetaFile) 形式の 1 つのベクター画像を表します

```csharp
public sealed class WmfImage : MetaImageBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | コンテンツから新しい WmfImage インスタンスを作成し、バイト ストリームとして表され、指定された name を使用します |
| [WmfImage](wmfimage#constructor_1)(string, string) | コンテンツから新しい WmfImage インスタンスを作成し、base64 でエンコードされた文字列として表され、指定された name を使用します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | このベクターの縦横比を返します image |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | この WMF 画像のコンテンツをバイナリストリームとして返します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | 名前と拡張子で構成される、このベクター画像の正しいファイル名を返します。理論的には名前とは異なる場合があります. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | このラスター イメージを破棄するかどうかを決定します (`真実`） か否か （`間違い` ) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | このベクター画像の直線寸法 (幅と高さ) を返します |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | このベクター画像の名前を返します。通常、ファイル名の拡張子は含まれず、理論的には filename. とは異なる場合があります。 |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | この WMF 画像のコンテンツをプレーン テキストとして返します |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | ImageType.Wmf を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | この WMF 画像のコンテンツを破棄し、ほとんどのメソッドとプロパティを非動作状態にすることで、この WMF 画像を破棄します |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | 参照の等価性を指定してこのインスタンスをチェックします。 |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | この WMF イメージを file に保存します |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | このベクター WMF 画像をラスター PNG 画像に保存します image |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | このベクター WMF 画像をベクター SVG に保存します image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | 指定されたストリームが有効な WMF かどうかを確認します image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | 指定された base64 でエンコードされた文字列が有効な WMF かどうかを確認します image |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | このラスター画像が破棄されたときに発生するイベント |

### 関連項目

* class [MetaImageBase](../metaimagebase)
* 名前空間 [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
