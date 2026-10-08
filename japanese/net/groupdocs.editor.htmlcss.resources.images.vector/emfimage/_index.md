---
title: "EmfImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "拡張メタファイル形式（EMF）でのベクタ画像を、メタデータと追加メソッドとともに表します"
type: docs
weight: 560
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

拡張メタファイル形式（EMF）のベクター画像を表し、そのメタデータと追加メソッドを提供します。

```csharp
public sealed class EmfImage : MetaImageBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | バイトストリームとして表現されたコンテンツから、新しい EmfImage インスタンスを作成し、指定された名前を付けます |
| [EmfImage](emfimage#constructor_1)(string, string) | base64 エンコード文字列として表現されたコンテンツから、新しい EmfImage インスタンスを作成し、指定された名前を付けます |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | このベクトル画像のアスペクト比を返します |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | この EMF 画像のコンテンツをバイナリストリームとして返します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | このベクトル画像の正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | このラスタ画像が破棄されているか (`true`) それともされていないか (`false`) を判定します |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | このベクトル画像の線形寸法（幅と高さ）を返します |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | このベクトル画像の名前を返します。通常、ファイル名拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | この EMF 画像のコンテンツをプレーンテキストとして返します |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | ImageType.Emf を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | この EMF 画像のコンテンツを破棄し、ほとんどのメソッドとプロパティを使用できなくすることで、画像を破棄します。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | この EMF 画像をファイルに保存します |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | このベクタ EMF 画像をラスタ PNG 画像に保存します |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | このベクタ EMF 画像をベクタ SVG 画像に保存します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | 指定されたストリームが有効な EMF 画像かどうかをチェックします |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | 指定された base64 エンコード文字列が有効な EMF 画像かどうかをチェックします |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
