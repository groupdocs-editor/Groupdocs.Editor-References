---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "バイナリ XML およびテキスト形式のスプレッドシートをカプセル化し、CSV、TSV、セミコロン区切りなどのテキスト区切り形式は除外します。これによりワークブックを保存できます。以下の形式が含まれます Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. スプレッドシート形式の詳細は https//wiki.fileformat.com/spreadsheet をご覧ください。"
type: docs
weight: 130
url: /ja/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

バイナリ、XML、テキスト形式のすべてのスプレッドシートをカプセル化し、CSV、TSV、セミコロン区切りなどのテキスト区切り形式は除外します。これによりワークブックを保存できます。以下の形式が含まれます: [`Xls`](./xls)、[`Xlt`](./xlt)、[`Xlsx`](./xlsx)、[`Xlsm`](./xlsm)、[`Xlsb`](./xlsb)、[`Xltx`](./xltx)、[`Xltm`](./xltm)、[`Xlam`](./xlam)、[`SpreadsheetML`](./spreadsheetml)、[`Ods`](./ods)、[`Fods`](./fods)、[`Sxc`](./sxc)、[`Dif`](./dif)、[`Csv`](./csv)、[`Tsv`](./tsv)。スプレッドシート形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet)をご覧ください。

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | すべての [`SpreadsheetFormats`](../spreadsheetformats) の列挙可能なコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | 指定されたファイル拡張子を持つ、指定されたタイプの [`SpreadsheetFormats`](../spreadsheetformats) インスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | ファイル拡張子を表す文字列を [`SpreadsheetFormats`](../spreadsheetformats) オブジェクトに変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | カンマ区切り値（CSV）。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/csv/)をご覧ください。 |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | データ交換フォーマット（DIF）。 |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | フラット OpenDocument スプレッドシート（FODS）。 |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument スプレッドシート（ODS）。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/ods)をご覧ください。 |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 および Excel 2003 の XML フォーマット。 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice または OpenOffice.org Calc XML スプレッドシート（SXC）。 |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | タブ区切り値（TSV）。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/tsv/)をご覧ください。 |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel アドイン（XLAM）。 |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 バイナリファイル形式 (XLS)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xls)をご覧ください。 |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel バイナリ ワークブック (XLSB)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xlsb)をご覧ください。 |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML ワークブック マクロ有効 (XLSM)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xlsm)をご覧ください。 |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML ワークブック マクロ無効 (XLSX)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xlsx)をご覧ください。 |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 テンプレート (XLT)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xlt)をご覧ください。 |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML テンプレート マクロ有効 (XLTM)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xltm)をご覧ください。 |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML テンプレート マクロ無効 (XLTX)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/xltx)をご覧ください。 |

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
