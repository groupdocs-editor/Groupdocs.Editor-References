---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "HTML ドキュメントのリソースとして、すべてのプロパティを持つサポートされるフォントタイプの基底クラスです。"
type: docs
weight: 350
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

HTML ドキュメントのリソースとして、すべてのプロパティを持つサポートされるフォントタイプの基底クラスです。

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | このフォントのコンテンツをバイトストリームとして返します。 |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | このフォントリソースの正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | このフォントが破棄されているかどうかを判断します |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | このフォントリソースの名前を返します。通常、ファイル名の拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | このフォントのコンテンツを base64 エンコードされた文字列として返します。この値は最初の呼び出し後にキャッシュされます。 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | 実装型は、特定のフォントリソースのタイプに関する情報を、特定の FontType 型のインスタンスとして返す必要があります。このインスタンスはすべてのタイプ固有情報をカプセル化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | このフォントリソースを破棄し、コンテンツを破棄して、ほとんどのメソッドとプロパティを使用できなくします |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします。 |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | このフォントを指定されたファイルに保存します |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | このフォントが破棄されたときに発生するイベント |

### 参照

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
