---
title: "Woff2Font"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "base64 エンコードされた文字列として表現されたコンテンツと指定された名前から新しい Woff2Font クラスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

Base64 エンコードされた文字列として表現されたコンテンツから新しい Woff2Font クラスを作成し、指定された名前を付けます

```csharp
public Woff2Font(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | WOFF2 フォントの名前。null、空文字、または空白のみであってはなりません。 |
| contentInBase64 | 文字列 | base64 エンコードされた文字列としてのコンテンツ。null、空文字、または空白のみであってはなりません。WOFF2 コンテンツでない場合は例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツから新しい Woff2Font クラスを作成し、指定された名前を付けます

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | WOFF2 フォントの名前。null、空文字、または空白のみであってはなりません。 |
| binaryContent | Stream | コンテンツをバイトストリームとして。読み取りは元の位置から開始します。nullにできません。読み取り可能でシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
