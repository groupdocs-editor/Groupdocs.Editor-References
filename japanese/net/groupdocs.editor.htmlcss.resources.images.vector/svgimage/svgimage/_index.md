---
title: "SvgImage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "通常の文字列として表現されたコンテンツと指定された名前から新しい SvgImage インスタンスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

通常の文字列として表現されたコンテンツから、新しい SvgImage インスタンスを作成し、指定された名前を付けます

```csharp
public SvgImage(string name, string content)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | SVG 画像の名前。null、空、または空白文字にできません。 |
| コンテンツ | 文字列 | コンテンツは通常の文字列で、SVG 画像の有効な XML 準拠コンテンツを含みます。null、空、または空白文字にできません。SVG コンテンツでない場合、例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | いくつかのパラメータが無効です |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* 引数は無効な SVG コンテンツを含んでいます |

### 参照

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツから、新しい SvgImage インスタンスを作成し、指定された名前を付けます

```csharp
public SvgImage(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | SVG 画像の名前。null、空、または空白文字にできません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
