---
title: "TtfFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された名前と base64 エンコードされた文字列で表現されたコンテンツから新しい TtfFont クラスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/ttffont/
---
## TtfFont(string, string) {#constructor_1}

Base64 エンコードされた文字列として表現されたコンテンツから、新しい TtfFont クラスを作成し、指定された名前を設定します

```csharp
public TtfFont(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | TTF フォントの名前。null、空文字、または空白にすることはできません。 |
| contentInBase64 | 文字列 | コンテンツは base64 エンコードされた文字列です。null、空文字、または空白にすることはできません。TTF コンテンツでない場合、例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtfFont(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツから、新しい TtfFont クラスを作成し、指定された名前を設定します

```csharp
public TtfFont(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | TTF フォントの名前。null、空文字、または空白にすることはできません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | 指定されたバイナリコンテンツが有効な TTF フォントとして正しく解釈できない場合にスローされます |

### 参照

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
