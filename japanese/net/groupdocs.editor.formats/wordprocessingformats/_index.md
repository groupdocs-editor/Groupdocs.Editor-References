---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべての WordProcessing フォーマットをカプセル化します。以下のファイルタイプが含まれます"
type: docs
weight: 150
url: /ja/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

すべてのワードプロセッシング形式をカプセル化します。以下のファイルタイプが含まれます:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Word Processing フォーマットの詳細は[こちら](https://wiki.fileformat.com/word-processing)をご覧ください。

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | すべての[`WordProcessingFormats`](../wordprocessingformats)の列挙可能なコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | 指定されたファイル拡張子を持つ、指定されたタイプの[`WordProcessingFormats`](../wordprocessingformats)インスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | ファイル拡張子を表す文字列を[`WordProcessingFormats`](../wordprocessingformats)オブジェクトに変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 バイナリファイル形式 (DOC) は、Microsoft Word または他のワードプロセッシングアプリケーションで生成されたドキュメントをバイナリ形式で表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/doc)をご覧ください。 |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML マクロ有効ドキュメント (DOCM) ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/docm)をご覧ください。 |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML マクロ無効ドキュメント (DOCX) は、Microsoft Word ドキュメントの代表的な形式です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/docx)をご覧ください。 |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 テンプレート (DOT) は、Microsoft Word が作成したテンプレートファイルで、後続の DOC または DOCX ファイル生成のための事前設定が含まれます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/dot)をご覧ください。 |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML マクロ有効テンプレート (DOTM) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/dotm)をご覧ください。 |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML マクロ無効テンプレート (DOTX) は、Microsoft Word が作成したテンプレートファイルで、後続の DOCX ファイル生成のための事前設定が含まれます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/dotx)をご覧ください。 |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML は、ZIP パッケージではなくフラットな XML ファイルとして保存されます。 |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format テキストドキュメント (ODT) ファイルは、OpenDocument テキストファイル形式に基づくワードプロセッシングアプリケーションで作成されたドキュメントです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/odt)をご覧ください。 |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format テキストドキュメントテンプレート (OTT) は、OASIS の OpenDocument 標準に準拠したアプリケーションで生成されたテンプレートドキュメントです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/ott)をご覧ください。 |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | リッチテキスト形式 (RTF) は、アプリケーション内で使用するための書式設定されたテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/rtf)をご覧ください。 |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML 形式 — WordProcessingML または WordML (.XML)。 |

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
