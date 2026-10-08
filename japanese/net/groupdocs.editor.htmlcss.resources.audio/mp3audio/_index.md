---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "任意のフォーマットのオーディオリソースを 1 つ表します"
type: docs
weight: 330
url: /ja/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

任意のフォーマットのオーディオリソースを 1 つ表します

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | MP3 コンテンツ（バイトストリームで表現）から新しい Mp3Audio クラスを作成し、指定された名前を付けます。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | このフォントのコンテンツをバイトストリームとして返します。 |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | この MP3 コンテンツの正しいファイル名（名前と拡張子から構成）を返します。理論的には名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | この MP3 コンテンツが破棄されているかどうかを判断します。 |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | この MP3 コンテンツの名前を返します。通常はファイル名の拡張子を含まず、理論的にはファイル名とは異なる場合があります。 |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | この MP3 リソースのコンテンツを Base64 エンコードされた文字列として返します。この値は最初の呼び出し後にキャッシュされます。 |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | AudioType.Mp3 を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | この MP3 リソースを破棄し、そのコンテンツを破棄して、ほとんどのメソッドとプロパティを使用できなくします。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします。 |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | この MP3 リソースを指定されたファイルに保存します。 |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | 指定されたストリームが有効な MP3 コンテンツかどうかをチェックします。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | この MP3 コンテンツが破棄されたときに発生するイベントです。 |

### 参照

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
