---
title: "WoffFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "コンテンツをBase64エンコードされた文字列として表現し、指定された名前で新しいWoffFontクラスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/wofffont/
---
## WoffFont(string, string) {#constructor_1}

コンテンツ（Base64 エンコードされた文字列で表現）から新しい WoffFont クラスを作成し、指定された名前を付けます

```csharp
public WoffFont(string name, string contentInBase64)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | WOFFフォントの名前。null、空、または空白文字にできません |
| contentInBase64 | 文字列 | コンテンツをBase64エンコードされた文字列として。null、空、または空白文字にできません。WOFFコンテンツでない場合、例外がスローされます |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## WoffFont(string, Stream) {#constructor}

コンテンツ（バイトストリームで表現）から新しい WoffFont クラスを作成し、指定された名前を付けます

```csharp
public WoffFont(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | WOFFフォントの名前。null、空、または空白文字にできません |
| binaryContent | Stream | コンテンツをバイトストリームとして。読み取りは元の位置から開始します。nullにできません。読み取り可能でシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 参照

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
