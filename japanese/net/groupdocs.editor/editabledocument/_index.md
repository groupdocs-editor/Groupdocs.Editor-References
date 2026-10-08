---
title: "EditableDocument"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集前後のコンテンツを含む中間ドキュメント"
type: docs
weight: 10
url: /ja/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

編集前後のコンテンツを含む中間ドキュメント

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | すべての既存リソースの一覧を返します：すべてのスタイルシート、HTML からの画像、フォント、オーディオ |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | オーディオリソースの一覧を返します |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | この HTML ドキュメントで使用されているスタイルシート (CSS) リソース（外部および埋め込み、インラインは除く）を取得できるようにします |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | この HTML ドキュメントで使用されている外部フォントリソースを取得できるようにします |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | この HTML ドキュメントで使用されている外部画像リソース（ラスタ画像およびベクタ画像）を取得できるようにします |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | この Editable ドキュメントが既に破棄されているか（true）またはされていないか（false）を判定します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | 静的ファクトリで、*.html ファイルへのパスとリンクされたリソースが格納されたフォルダーを指定して、HTML ファイルから EditableDocument のインスタンスを作成します |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | 静的ファクトリで、指定された HTML マークアップから [`EditableDocument`](../editabledocument) のインスタンスを作成します |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | 静的ファクトリで、指定された HTML マークアップと対応するリンクリソースのセットから EditableDocument のインスタンスを作成します |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | 静的ファクトリで、指定された HTML マークアップと、フルパスで指定されたフォルダー内にあるリソースから EditableDocument のインスタンスを作成します |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | この Editable ドキュメントインスタンスを破棄し、コンテンツを破棄してメソッドとプロパティを使用できなくします |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | HTML ドキュメントの BODY タグの開始と終了の間の内部コンテンツ（タグ自体は除く）を文字列として返します |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | HTML ドキュメントの BODY タグの開始と終了の間の内部コンテンツ（タグ自体は除く）を文字列として返します。外部リソースへのリンクは指定されたプレースホルダー付きテンプレートを含みます |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | HTML ドキュメント全体の内容を文字列として返します |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | HTML ドキュメント全体の内容を文字列として返します。外部リソースへのリンクは指定されたプレースホルダー付きテンプレートを含みます |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | 指定されたテキストエンコーディングでこの内容を指定されたストリームに書き込むことにより、HTML ドキュメント全体の内容をバイトストリームとして返します |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | すべての外部スタイルシートの内容を文字列のリストとして返します。1 つの文字列が 1 つのスタイルシートを表します。ドキュメントに CSS がない場合は空のリストを返します |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | すべての外部スタイルシートの内容を文字列のリストとして返します。1 つの文字列が 1 つのスタイルシートを表します。指定されたプレフィックスが各外部リソースへのリンクに適用されます。ドキュメントに CSS がない場合は空のリストを返します |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | この HTML ドキュメントのすべてのコンテンツと関連リソースを、単一の文字列として返します。すべてのリソースは HTML マークアップ内に base64 エンコードされた形で埋め込まれます |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | 指定されたパスに HTML マークアップを保存し、リソース用の付随フォルダーに保存することで、この HTML ドキュメントをファイルに保存します |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | 指定されたパスに HTML マークアップを保存し、リソース用の付随フォルダー（指定されたパスに位置する）に保存することで、この HTML ドキュメントをファイルに保存します |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | この [`EditableDocument`](../editabledocument) の内容を HTML ドキュメントとして指定されたテキストライターに保存します。2 番目のオプションパラメータで保存手順をカスタマイズし、リソース保存コールバックを指定できます |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | この Editable ドキュメントが破棄された直後に、破棄プロセスが完了したときに発生するイベント |

### 備考

`EditableDocument` クラスのインスタンスは、'[`Edit`](../editor/edit)' メソッドで生成するか、ユーザーが静的ファクトリを使用して自ら作成できます。`EditableDocument` は内部で独自のクローズド形式でドキュメントを保持し、GroupDocs.Editor がサポートするすべてのインポートおよびエクスポート形式と互換（変換）可能です。任意の WYSIWYG クライアントサイドエディタ（CKEditor や TinyMCE など）でドキュメントを編集可能にするために、`EditableDocument` は HTML マークアップを生成し、ユーザーが受け入れ可能なリソースを生成するメソッドを提供します

### 参照

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
