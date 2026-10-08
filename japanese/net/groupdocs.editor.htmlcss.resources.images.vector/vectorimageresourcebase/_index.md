---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポートされているすべてのベクター画像の基底クラス"
type: docs
weight: 590
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
## VectorImageResourceBase class

サポートされているすべてのベクター画像の基底クラス

```csharp
public abstract class VectorImageResourceBase : IImageResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | このベクトル画像のアスペクト比を返します |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | 実装では、このベクトル画像の内容をバイトストリームとして返す必要があります |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | このベクトル画像の正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | このラスタ画像が破棄されているか (`true`) それともされていないか (`false`) を判定します |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | このベクトル画像の線形寸法（幅と高さ）を返します |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | このベクトル画像の名前を返します。通常、ファイル名拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | 実装では、このベクトル画像の内容をテキスト形式で返す必要があります：画像タイプに関する XML の base64 エンコード |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | 実装では、ベクトル画像のタイプに関する情報を返す必要があります |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | 実装では、このインスタンスを破棄する必要があります |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals#equals)(IHtmlResource) | 指定された参照等価性でこのインスタンスをチェックします |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | 実装では、指定されたパスでこの画像をディスクに保存する必要があります |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | 実装では、指定されたバイトストリームにラスタ PNG 形式で現在のベクトル画像を保存する必要があります |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | このラスタ画像が破棄されたときに発生するイベント |

### 参照

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
