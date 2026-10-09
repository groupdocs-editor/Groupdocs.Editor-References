---
title: "SpreadsheetFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "バイナリ XML とテキストのすべてのスプレッドシートフォーマットをカプセル化し、CSV、TSV、セミコロン区切りなどの区切り文字ベースのテキスト形式は除外します。これにより、ワークブックを保存できます。"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.formats/spreadsheetformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class SpreadsheetFormats extends DocumentFormatBase
```

バイナリ、XML、テキストのスプレッドシート形式すべてをカプセル化します（CSV、TSV、セミコロン区切りなどのテキスト区切り形式は除外）。これらの形式でワークブックを保存できます。
以下の形式が含まれます：
[Dif](../../com.groupdocs.editor.formats/spreadsheetformats#Dif),
[Fods](../../com.groupdocs.editor.formats/spreadsheetformats#Fods),
[Ods](../../com.groupdocs.editor.formats/spreadsheetformats#Ods),
[Sxc](../../com.groupdocs.editor.formats/spreadsheetformats#Sxc),
[Xlam](../../com.groupdocs.editor.formats/spreadsheetformats#Xlam),
[Xls](../../com.groupdocs.editor.formats/spreadsheetformats#Xls),
[Xlsb](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsb),
[Xlsm](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsm),
[Xlsx](../../com.groupdocs.editor.formats/spreadsheetformats#Xlsx),
[Xlt](../../com.groupdocs.editor.formats/spreadsheetformats#Xlt),
[Xltm](../../com.groupdocs.editor.formats/spreadsheetformats#Xltm),
[Xltx](../../com.groupdocs.editor.formats/spreadsheetformats#Xltx).
スプレッドシート形式の詳細は [here](../https://wiki.fileformat.com/spreadsheet) でご覧ください。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Xls](#Xls) | Excel 97-2003 バイナリファイル形式 (XLS)。 |
|
|  | [Xlt](#Xlt) | Excel 97-2003 テンプレート (XLT)。 |
|
|  | [Xlsx](#Xlsx) | Office Open XML ワークブック（マクロなし） (XLSX)。 |
|
|  | [Xlsm](#Xlsm) | Office Open XML ワークブック（マクロ有効） (XLSM)。 |
|
|  | [Xlsb](#Xlsb) | Excel バイナリワークブック (XLSB)。 |
|
|  | [Xltx](#Xltx) | Office Open XML テンプレート（マクロなし） (XLTX)。 |
|
|  | [Xltm](#Xltm) | Office Open XML テンプレート（マクロ有効） (XLTM)。 |
|
|  | [Xlam](#Xlam) | Excel アドイン (XLAM)。 |
|
|  | [SpreadsheetML](#SpreadsheetML) | SpreadsheetML \u2014 Microsoft Office Excel 2002 および Excel 2003 XML フォーマット。 |
|
|  | [Ods](#Ods) | OpenDocument スプレッドシート (ODS)。 |
|
|  | [Fods](#Fods) | Flat OpenDocument スプレッドシート (FODS)。 |
|
|  | [Sxc](#Sxc) | StarOffice または OpenOffice.org Calc の XML スプレッドシート (SXC)。 |
|
|  | [Dif](#Dif) | データ交換フォーマット (DIF)。 |
|
|  | [Csv](#Csv) | カンマ区切り値 (CSV)。 |
|
|  | [Tsv](#Tsv) | タブ区切り値 (TSV)。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定されたタイプの [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) オブジェクトに変換します。 |
|
### Xls {#Xls}
```
public static final SpreadsheetFormats Xls
```


Excel 97-2003 バイナリファイル形式 (XLS)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xls)
.


### Xlt {#Xlt}
```
public static final SpreadsheetFormats Xlt
```


Excel 97-2003 テンプレート (XLT)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xlt)
.


### Xlsx {#Xlsx}
```
public static final SpreadsheetFormats Xlsx
```


Office Open XML ワークブック（マクロなし） (XLSX)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xlsx)
.


### Xlsm {#Xlsm}
```
public static final SpreadsheetFormats Xlsm
```


Office Open XML ワークブック（マクロ有効） (XLSM)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xlsm)
.


### Xlsb {#Xlsb}
```
public static final SpreadsheetFormats Xlsb
```


Excel バイナリワークブック (XLSB)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xlsb)
.


### Xltx {#Xltx}
```
public static final SpreadsheetFormats Xltx
```


Office Open XML テンプレート（マクロなし） (XLTX)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xltx)
.


### Xltm {#Xltm}
```
public static final SpreadsheetFormats Xltm
```


Office Open XML テンプレート（マクロ有効） (XLTM)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/xltm)
.


### Xlam {#Xlam}
```
public static final SpreadsheetFormats Xlam
```


Excel アドイン (XLAM)。


### SpreadsheetML {#SpreadsheetML}
```
public static final SpreadsheetFormats SpreadsheetML
```


SpreadsheetML \u2014 Microsoft Office Excel 2002 および Excel 2003 XML フォーマット。


### Ods {#Ods}
```
public static final SpreadsheetFormats Ods
```


OpenDocument スプレッドシート (ODS)。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/spreadsheet/ods)
.


### Fods {#Fods}
```
public static final SpreadsheetFormats Fods
```


Flat OpenDocument スプレッドシート (FODS)。


### Sxc {#Sxc}
```
public static final SpreadsheetFormats Sxc
```


StarOffice または OpenOffice.org Calc の XML スプレッドシート (SXC)。


### Dif {#Dif}
```
public static final SpreadsheetFormats Dif
```


データ交換フォーマット (DIF)。


### Csv {#Csv}
```
public static final SpreadsheetFormats Csv
```


カンマ区切り値 (CSV)。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/spreadsheet/csv/)
.


### Tsv {#Tsv}
```
public static final SpreadsheetFormats Tsv
```


タブ区切り値 (TSV)。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/spreadsheet/tsv/)
.


### getAll() {#getAll--}
```
public static List<SpreadsheetFormats> getAll()
```


すべての [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) の列挙可能なコレクションを取得します。
値: すべての [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) インスタンスを含む IEnumerable{SpreadsheetFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.SpreadsheetFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static SpreadsheetFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定されたタイプの [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - An instance of the specified type [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static SpreadsheetFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - A [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) object corresponding to the specified file extension.

