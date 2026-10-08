---
title: "TtcFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "TTC TrueType コレクション形式のフォントを 1 つ表します"
type: docs
weight: 380
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
## TtcFont class

TTC（TrueType Collection）フォーマットのフォントを表します。

```csharp
public sealed class TtcFont : FontResourceBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TtcFont](ttcfont#constructor)(string, Stream) | コンテンツ（バイトストリーム）から新しい TtcFont クラスを作成し、指定された名前を付けます |
| [TtcFont](ttcfont#constructor_1)(string, string) | コンテンツ（base64 エンコードされた文字列）から新しい TtcFont クラスを作成し、指定された名前を付けます |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | このフォントのコンテンツをバイトストリームとして返します。 |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | このフォントリソースの正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [FontsNumber](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/fontsnumber) { get; } | この TTC に含まれるフォント数 |
| [HasDsigTable](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/hasdsigtable) { get; } | この TTC に DSIG テーブルが存在するかどうかを示します。DSIG テーブルは TTC のヘッダー バージョンが 2.0 の場合にのみ存在する可能性があります。 |
| [HeaderVersion](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/headerversion) { get; } | TTC ヘッダー バージョン（"1" または "2"） |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | このフォントが破棄されているかどうかを判断します |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | このフォントリソースの名前を返します。通常、ファイル名の拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | このフォントのコンテンツを base64 エンコードされた文字列として返します。この値は最初の呼び出し後にキャッシュされます。 |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/type) { get; } | FontType.Ttc を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | このフォントリソースを破棄し、コンテンツを破棄して、ほとんどのメソッドとプロパティを使用できなくします |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします。 |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | このフォントを指定されたファイルに保存します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid)(Stream) | 指定されたストリームが有効な TTC フォントかどうかを確認します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid_1)(string) | 指定された base64 エンコード文字列が有効な TTF フォントかどうかを確認します |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/requiredheadersize) | 検証に必要な TTC ヘッダー サイズ（バイト単位） |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | このフォントが破棄されたときに発生するイベント |

### 備考

詳細はこちら: https://docs.fileformat.com/font/ttc/

### 参照

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
