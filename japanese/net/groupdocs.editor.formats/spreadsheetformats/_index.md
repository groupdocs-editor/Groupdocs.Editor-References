---
title: SpreadsheetFormats
second_title: GroupDocs.Editor for .NET API リファレンス
description: ワークブックを保存できるすべてのバイナリXMLおよびテキスト形式のスプレッドシート形式 CSVTSVセミコロン区切りなどのセパレーターを含むすべてのテキスト区切り文字ベースの形式を除く をカプセル化します 次の形式が含まれます Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . スプレッドシート形式の詳細ここhttps//wiki.fileformat.com/spreadsheet.
type: docs
weight: 130
url: /ja/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

ワークブックを保存できる、すべてのバイナリ、XML、およびテキスト形式のスプレッドシート形式 (CSV、TSV、セミコロン区切りなどのセパレーターを含むすべてのテキスト区切り文字ベースの形式を除く) をカプセル化します。 次の形式が含まれます: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . スプレッドシート形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet).

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | このスプレッドシート形式の拡張子 (先頭のドット文字なし) を小文字で返します |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | このフォーマットの MIME コードを返します |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | このスプレッドシート形式の正式な完全な名前を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | のインスタンスを返します[`SpreadsheetFormats`](../spreadsheetformats)指定されたファイル拡張子に関連付けられた構造体、または拡張子を適切に解析できない場合は例外をスローします |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | このインスタンスが他の指定された IDocumentFormat と等しいかどうかを判断します instance |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | このインスタンスが、おそらくボックス化された SpreadsheetFormats の他の指定されたオブジェクトと等しいかどうかを判断します |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | このインスタンスが他の指定された SpreadsheetFormats と等しいかどうかを判断します instance |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | このインスタンスに対して不変のハッシュコードを返します |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | equality で指定された 2 つの SpreadsheetFormats インスタンスをチェックします。 |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | inequality で指定された 2 つの SpreadsheetFormats インスタンスをチェックします |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | カンマ区切り値 (CSV) ドキュメントは、カンマ区切りの値を持つデータのレコードを含むプレーン テキストを表します。 CSV ファイルの各行は、ファイルに含まれる一連のレコードからの新しいレコードです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | データ交換フォーマット (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — 単一の圧縮されていない XML ドキュメントとして保存されます |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument スプレッドシート (ODS) は、ユーザーが編集可能な OpenDocument スプレッドシート ドキュメント形式を表します。データは ODF ファイル内に行と列に保存されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 および Excel 2003 XML Format |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice または OpenOffice.org Calc XML スプレッドシート (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-Separated Values (TSV) ファイル形式は、プレーン テキスト形式のタブで区切られたデータを表します。 CSV に似たファイル形式は、異なるアプリケーション間でインポートおよびエクスポートするために、構造化された方法でデータを編成するために使用されます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel アドイン (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) は、Microsoft Excel や、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムで作成できるファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel バイナリ ブック (XLSB) は、Excel バイナリ ファイル形式を指定します。これは、Excel ブックのコンテンツを指定するレコードと構造のコレクションです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) は、マクロをサポートするスプレッドシート ファイルの一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) は、Microsoft Office 2007 のリリースで Microsoft によって導入されたドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 テンプレート (XLT) は、Microsoft Office スイートの一部として提供されるスプレッドシート アプリケーションである Microsoft Excel で作成されたテンプレート ファイルを表します。 Microsoft Office 97-2003 では、新しい XLT ファイルの作成と開くことがサポートされていました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) は、Microsoft Excel によってマクロ有効テンプレート ファイルとして生成されるファイルを表します。 XLTM ファイルの構造は XLTX に似ていますが、XLTX はマクロを使用したテンプレート ファイルの作成をサポートしていません。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML テンプレート マクロフリー (XLTX) ファイルは、Office OpenXML ファイル形式の仕様に基づく Microsoft Excel テンプレートを表します。 XLTX ファイルで指定されたものと同じ設定を示す XLSX ファイルを生成するために利用できる標準テンプレート ファイルを作成するために使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltx) |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | 既存のすべてのスプレッドシート形式で列挙可能な可能性を提供する内部クラスを返します |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | SpreadsheetFormats type の「foreach」機能を有効にする IEnumerable ジェネリック インターフェイスを実装します。 |

### 関連項目

* interface [IDocumentFormat](../idocumentformat)
* 名前空間 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
