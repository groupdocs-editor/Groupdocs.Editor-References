---
title: "WoffFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "WOFF Web Open Font Format フォーマット内のフォントを1つ表します"
type: docs
weight: 410
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
## WoffFont class

WOFF（Web Open Font Format）フォーマットのフォントを表します。

```csharp
public sealed class WoffFont : FontResourceBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WoffFont](wofffont#constructor)(string, Stream) | コンテンツ（バイトストリームで表現）から新しい WoffFont クラスを作成し、指定された名前を付けます |
| [WoffFont](wofffont#constructor_1)(string, string) | コンテンツ（Base64 エンコードされた文字列で表現）から新しい WoffFont クラスを作成し、指定された名前を付けます |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | このフォントのコンテンツをバイトストリームとして返します。 |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | このフォントリソースの正しいファイル名（名前と拡張子から構成）を返します。理論上、名前とは異なる場合があります。 |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | このフォントが破棄されているかどうかを判断します |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | このフォントリソースの名前を返します。通常、ファイル名の拡張子は含まれず、理論上、ファイル名とは異なる場合があります。 |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | このフォントのコンテンツを base64 エンコードされた文字列として返します。この値は最初の呼び出し後にキャッシュされます。 |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/type) { get; } | FontType.Woff を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | このフォントリソースを破棄し、コンテンツを破棄して、ほとんどのメソッドとプロパティを使用できなくします |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします。 |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします。 |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | このフォントを指定されたファイルに保存します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid)(Stream) | 指定されたストリームが有効な WOFF フォントかどうかをチェックします |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid_1)(string) | 指定された Base64 エンコード文字列が有効な WOFF フォントかどうかをチェックします |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/requiredheadersize) | 検証に必要な WOFF ヘッダーサイズ（バイト単位） |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | このフォントが破棄されたときに発生するイベント |

### 参照

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
