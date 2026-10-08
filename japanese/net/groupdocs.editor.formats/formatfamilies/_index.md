---
title: "FormatFamilies"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "システムで利用可能なさまざまなフォーマットファミリーを表します。"
type: docs
weight: 110
url: /ja/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

システムで利用可能なさまざまなフォーマットファミリーを表します。

```csharp
public class FormatFamilies : FormatFamilyBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | eBook フォーマットファミリーを表します。Mobi フォーマットの詳細は[こちら](https://docs.fileformat.com/ebook/mobi/)、AZW3 フォーマットの詳細は[こちら](https://docs.fileformat.com/ebook/azw3/)、ePub フォーマットの詳細は[こちら](https://docs.fileformat.com/ebook/epub/)をご覧ください。 |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | Email フォーマットファミリーを表します。メール形式の詳細は[こちら](https://docs.fileformat.com/email/)をご覧ください。 |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Fixed Layout フォーマットファミリーを表します。さまざまな文書閲覧または出版アプリケーションは、特定のフォーマットの文書を開くことができ（Adobe Acrobat、XPS Viewer）、場合によっては編集（Adobe InDesign）も可能です。これらのアプリケーションは通常、いわゆる「fixed-page」形式の文書を生成します。この文書形式は、各ページに文書の内容が正確に配置されている位置を記述します。内部的には、PDF または XPS 形式は各ページの記述と、ページ上のコンテンツのレイアウトを指定する描画指示を含みます。これは画像形式に似ており、ラスタ形式またはベクトル形式でコンテンツがどこに表示されるかを記述します。 |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Presentation フォーマットファミリーを表します。プレゼンテーション形式の詳細は[こちら](https://wiki.fileformat.com/presentation)をご覧ください。 |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Spreadsheet フォーマットファミリーを表します。ワークブックを保存できるすべてのバイナリ、XML、テキスト形式のスプレッドシート（CSV、TSV、セミコロン区切りなどのテキスト区切り形式は除く）を含みます。 |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Textual フォーマットファミリーを表します。マークアップ（XML、HTML）などを含むすべてのテキスト（テキストベース）形式をカプセル化します。 |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Word Processing フォーマットファミリーを表します。ワードプロセッシング形式の詳細は[こちら](https://wiki.fileformat.com/word-processing)をご覧ください。 |

### 参照

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
