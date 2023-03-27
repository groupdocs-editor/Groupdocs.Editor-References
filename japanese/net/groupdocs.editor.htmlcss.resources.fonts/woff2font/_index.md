---
title: Woff2Font
second_title: GroupDocs.Editor for .NET API リファレンス
description: WOFF2 Web Open Font Format 形式の 1 つのフォントを表します
type: docs
weight: 410
url: /ja/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
## Woff2Font class

WOFF2 (Web Open Font Format) 形式の 1 つのフォントを表します

```csharp
public sealed class Woff2Font : FontResourceBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Woff2Font](woff2font#constructor)(string, Stream) | コンテンツから新しい Woff2Font クラスを作成し、バイト ストリームとして表され、指定された name を使用します |
| [Woff2Font](woff2font#constructor_1)(string, string) | base64 でエンコードされた文字列として表され、指定された name を持つコンテンツから新しい Woff2Font クラスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | このフォントのコンテンツをバイト stream として返します |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | 名前と拡張子で構成される、このフォント リソースの正しいファイル名を返します。理論的には名前とは異なる場合があります. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | このフォントを破棄するかどうかを決定します |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | このフォント リソースの名前を返します。通常、ファイル名の拡張子は含まれず、理論的には filename. とは異なる場合があります。 |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | このフォントのコンテンツを base64 でエンコードされた文字列として返します。この値は、最初の呼び出し後にキャッシュされます。 |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/type) { get; } | FontType.Woff2 を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | このフォント リソースを破棄し、そのコンテンツを破棄し、ほとんどのメソッドとプロパティを非動作にします |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | 参照等号で指定されたフォント リソースでこのインスタンスをチェックします |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | 参照 equality で、指定された HTML リソースでこのインスタンスをチェックします |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | このフォントを指定したファイルに保存します |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid)(Stream) | 指定されたストリームが有効な WOFF2 かどうかをチェックします font |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid_1)(string) | 指定された base64 でエンコードされた文字列が有効な WOFF2 かどうかを確認します font |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/requiredheadersize) | 検証に必要な WOFF2 ヘッダー サイズ (バイト単位) |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | このフォントが破棄されたときに発生するイベント |

### 関連項目

* class [FontResourceBase](../fontresourcebase)
* 名前空間 [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->