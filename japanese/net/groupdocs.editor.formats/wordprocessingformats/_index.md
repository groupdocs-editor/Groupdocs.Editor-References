---
title: WordProcessingFormats
second_title: GroupDocs.Editor for .NET API リファレンス
description: すべての WordProcessing 形式をカプセル化します次のファイル タイプが含まれます Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . ワード プロセッシング形式の詳細ここhttps//wiki.fileformat.com/wordprocessing.
type: docs
weight: 170
url: /ja/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

すべての WordProcessing 形式をカプセル化します。次のファイル タイプが含まれます: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . ワード プロセッシング形式の詳細[ここ](https://wiki.fileformat.com/word-processing).

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | この WordProcessing 形式の拡張子 (先頭のドット文字なし) を小文字で返します |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | このフォーマットの MIME コードを返します |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | この WordProcessing 形式の正式な完全な名前を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | のインスタンスを返します[`WordProcessingFormats`](../wordprocessingformats)指定されたファイル拡張子に関連付けられた構造体、または拡張子を適切に解析できない場合は例外をスローします |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | このインスタンスが他の指定された IDocumentFormat と等しいかどうかを判断します instance |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | このインスタンスが、おそらくボックス化された WordProcessingFormats の他の指定されたオブジェクトと等しいかどうかを判断します |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | このインスタンスが他の指定された WordProcessingFormats と等しいかどうかを判断します instance |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | このインスタンスに対して不変のハッシュコードを返します |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | 「名前」と同じ、この特定の形式の名前を返します。 property |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | equality で指定された 2 つの WordProcessingFormats インスタンスをチェックします。 |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | 指定された WordProcessingFormats instance の基になるフィールドからバイト値を返します (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | inequality で指定された 2 つの WordProcessingFormats インスタンスをチェックします |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 バイナリ ファイル形式 (DOC) は、Microsoft Word またはその他のワード プロセッシング ドキュメントによって生成されたドキュメントをバイナリ ファイル形式で表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM) ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年の Microsoft Office 2007 のリリースで導入されたこの新しいドキュメント形式の構造は、プレーン バイナリから XML とバイナリ ファイルの組み合わせに変更されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 テンプレートは、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOC または DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) は、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) は、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML は、ZIP パッケージではなくフラットな XML ファイルに格納されています |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format テキスト ドキュメント (ODT) ファイルは、OpenDocument テキスト ファイル形式に基づくワード プロセッシング アプリケーションで作成されたドキュメントのタイプです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format テキスト ドキュメント テンプレート (OTT) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されたテンプレート ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | リッチ テキスト形式 (RTF) は、アプリケーション内で使用するために書式設定されたテキストとグラフィックをエンコードする方法を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML 形式 — WordProcessingML または WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | 既存のすべての WordProcessing フォーマットに対して列挙可能な可能性を提供する内部クラスを返します |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | WordProcessingFormats type の「foreach」の可能性を有効にする IEnumerable ジェネリック インターフェイスを実装します |

### 備考

MIME コードは、指定されたリソースから取得されます: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### 関連項目

* interface [IDocumentFormat](../idocumentformat)
* 名前空間 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
