---
title: "TextualFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "テキストベースのすべての形式（マークアップ XML、HTML など）をカプセル化します。以下の形式が含まれます: Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /ja/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

テキストベース（text-based）のすべての形式をカプセル化し、マークアップ（XML、HTML）やその他を含みます。以下の形式が含まれます: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | すべての [`TextualFormats`](../textualformats) の列挙可能なコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | 指定されたファイル拡張子を持つ、指定されたタイプの [`TextualFormats`](../textualformats) インスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | ファイル拡張子を表す文字列を [`TextualFormats`](../textualformats) オブジェクトに変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help は、Microsoft の独自オンラインヘルプバイナリ形式で、HTML ページのコレクション、インデックス、その他のナビゲーションツールで構成されています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/web/chm/)をご覧ください。 |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language ドキュメント（HTML）は、ブラウザーで表示するために作成されたウェブページの拡張子です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/web/html)をご覧ください。 |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON（JavaScript Object Notation）は、人間が読めるテキストを使用してデータを保存・転送する、データ共有のためのオープン標準ファイル形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/web/json/)をご覧ください。 |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown は、プレーンテキストエディタを使用して書式付きテキストを作成するための軽量マークアップ言語です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/word-processing/md/)をご覧ください。 |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME による集約 HTML ドキュメントのカプセル化は、HTML コードとそれに付随するリソースを単一のコンピュータファイルに結合するために使用されるウェブページアーカイブ形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/web/mhtml/)をご覧ください。 |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | プレーンテキストドキュメント（TXT）は、行形式のプレーンテキストを含むテキストドキュメントを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/txt)をご覧ください。 |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language ドキュメント（XML）は、HTML に似ていますが、オブジェクトを定義するためにタグを使用する点が異なります。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/web/xml)をご覧ください。 |

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
