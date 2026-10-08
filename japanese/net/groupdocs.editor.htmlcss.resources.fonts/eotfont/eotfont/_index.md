---
title: "EotFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された名前と base64 エンコードされた文字列で表現されたコンテンツから新しい EotFont クラスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Base64 エンコードされた文字列として表現されたコンテンツから、新しい EotFont クラスを作成し、指定された名前を設定します

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eotName | 文字列 | EOT フォントの名前。null、空文字、または空白にすることはできません。 |
| eotContentInBase64 | 文字列 | コンテンツは base64 エンコードされた文字列です。null、空文字、または空白にすることはできません。EOT コンテンツでない場合、例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

バイトストリームとして表現されたコンテンツから、新しい EotFont クラスを作成し、指定された名前を設定します

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eotName | 文字列 | EOT フォントの名前。null、空文字、または空白にすることはできません。 |
| eotBinaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
