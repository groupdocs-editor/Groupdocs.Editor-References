---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "バイトストリームで表現された MP3 コンテンツと指定された名前から新しい Mp3Audio クラスを作成します"
type: docs
weight: 10
url: /ja/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/mp3audio/
---
## Mp3Audio constructor

MP3 コンテンツ（バイトストリームで表現）から新しい Mp3Audio クラスを作成し、指定された名前を付けます。

```csharp
public Mp3Audio(string name, Stream binaryContent)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | MP3 コンテンツの名前。null、空文字、または空白のみであってはなりません |
| binaryContent | Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始されます。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄される場合、このストリームも破棄されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  |

### 参照

* class [Mp3Audio](../../mp3audio)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
