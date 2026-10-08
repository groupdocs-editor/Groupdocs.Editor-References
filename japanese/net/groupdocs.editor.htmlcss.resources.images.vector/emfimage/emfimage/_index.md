---
title: "EmfImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Base64 エンコードされた文字列として表現されたコンテンツと指定された名前から新しい EmfImage インスタンスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/emfimage/
---
## EmfImage(string, string) {#constructor_1}

base64 エンコード文字列として表現されたコンテンツから、新しい EmfImage インスタンスを作成し、指定された名前を付けます

```csharp
public EmfImage(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | EMF 画像の名前。null、空、または空白文字にできません。 |
| contentInBase64 | 文字列 | コンテンツは base64 エンコードされた文字列です。null、空、または空白文字にできません。EMF コンテンツでない場合、例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## EmfImage(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツから、新しい EmfImage インスタンスを作成し、指定された名前を付けます

```csharp
public EmfImage(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | EMF 画像の名前。null、空、または空白文字にできません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
