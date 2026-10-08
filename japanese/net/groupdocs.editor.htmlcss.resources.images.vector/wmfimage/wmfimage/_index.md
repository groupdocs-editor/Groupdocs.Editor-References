---
title: "WmfImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Base64 エンコードされた文字列として表現されたコンテンツと指定された名前から新しい WmfImage インスタンスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

base64 エンコードされた文字列として表現されたコンテンツと指定された名前で新しい WmfImage インスタンスを作成します

```csharp
public WmfImage(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | WMF 画像の名前。null、空文字列、または空白のみであってはなりません。 |
| contentInBase64 | 文字列 | Base64 エンコードされた文字列としてのコンテンツ。null、空文字列、または空白のみであってはなりません。WMF コンテンツでない場合は例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツと指定された名前で新しい WmfImage インスタンスを作成します

```csharp
public WmfImage(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | WMF 画像の名前。null、空文字列、または空白のみであってはなりません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
