---
title: "TtcFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "base64 エンコードされた文字列で表現されたコンテンツと指定された名前から新しい TtcFont クラスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

コンテンツ（base64 エンコードされた文字列）から新しい TtcFont クラスを作成し、指定された名前を付けます

```csharp
public TtcFont(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | TTC フォントの名前。null、空文字、または空白のみであってはなりません。 |
| contentInBase64 | 文字列 | コンテンツを base64 エンコードされた文字列として指定します。null、空文字、または空白のみであってはなりません。TTC コンテンツでない場合、例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 入力文字列のいずれかが `null`、空文字、または空白のみです |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *contentInBase64* 引数のコンテンツは有効な TTC フォントとして認識できません |

### 参照

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

コンテンツ（バイトストリーム）から新しい TtcFont クラスを作成し、指定された名前を付けます

```csharp
public TtcFont(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | TTC フォントの名前。null、空文字、または空白のみであってはなりません。 |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *name* 引数が `null`、空文字、または空白のみです |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | 指定されたバイナリコンテンツが有効な TTF フォントとして正しく解釈できない場合にスローされます |

### 参照

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
