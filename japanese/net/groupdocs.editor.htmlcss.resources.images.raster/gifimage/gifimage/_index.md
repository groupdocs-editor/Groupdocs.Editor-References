---
title: "GifImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された名前と、base64 エンコードされた文字列として表現されたコンテンツから新しい GifImage インスタンスを作成します。"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.images.raster/gifimage/gifimage/
---
## GifImage(string, string) {#constructor_1}

Base64 エンコードされた文字列として表現されたコンテンツから新しい GifImage インスタンスを作成し、指定された名前を付けます。

```csharp
public GifImage(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | GIF 画像の名前。null、空文字、または空白のみであってはなりません。 |
| contentInBase64 | 文字列 | コンテンツを base64 エンコードされた文字列として表します。null、空文字、または空白のみであってはなりません。GIF コンテンツでない場合、例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## GifImage(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツから新しい GifImage インスタンスを作成し、指定された名前を付けます。

```csharp
public GifImage(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | GIF 画像の名前。null、空文字、または空白のみであってはなりません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
