---
title: "JpegImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "base64 エンコードされた文字列で表されたコンテンツと指定された名前から新しい JpegImage インスタンスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.images.raster/jpegimage/jpegimage/
---
## JpegImage(string, string) {#constructor_1}

コンテンツ（base64 エンコード文字列で表現）と指定された名前から新しい JpegImage インスタンスを作成します

```csharp
public JpegImage(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | JPEG 画像の名前。null、空、または空白文字にすることはできません。 |
| contentInBase64 | 文字列 | コンテンツは base64 エンコードされた文字列です。null、空、または空白文字にすることはできません。JPEG コンテンツでない場合は例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [JpegImage](../../jpegimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## JpegImage(string, Stream) {#constructor}

コンテンツ（バイトストリームで表現）と指定された名前から新しい JpegImage インスタンスを作成します

```csharp
public JpegImage(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | JPEG 画像の名前。null、空、または空白文字にすることはできません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [JpegImage](../../jpegimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
