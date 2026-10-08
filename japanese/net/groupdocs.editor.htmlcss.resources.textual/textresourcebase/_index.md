---
title: "TextResourceBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "テキストコンテンツとエンコーディングを持つ、サポートされるテキストリソースすべての基底クラス"
type: docs
weight: 630
url: /ja/net/groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
## TextResourceBase class

テキストコンテンツとエンコーディングを持つ、サポートされるテキストリソースすべての基底クラス

```csharp
public abstract class TextResourceBase : IHtmlResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | このテキストリソースの内容を元のエンコーディングでバイトストリームとして返します |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | このテキストリソースのエンコーディングを返します。通常は UTF-8 を返します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | 名前と拡張子からなるこのテキストリソースの正しいファイル名を返します |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | このテキストリソースが破棄されているかどうかを判断します |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | このテキストリソースの名前を拡張子なしで返します |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | このテキストリソースの内容を標準文字列として返します |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/type) { get; } | 実装時にはテキストリソースのタイプに関する情報を返す必要があります |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | このテキストリソースを破棄し、その内容も破棄してほとんどのメソッドとプロパティを使用できなくします。複数回の呼び出しにも耐えます。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals#equals)(IHtmlResource) | このインスタンスを指定されたものと等価かどうかチェックします。 |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | このテキストリソースを指定されたファイルに保存します |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | このテキストリソースが破棄されたときに発生するイベント |

### 参照

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
