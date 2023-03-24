---
title: GroupDocs.Editor.Formats
second_title: GroupDocs.Editor for .NET API リファレンス
description: GroupDocs.Editor.Formats 名前空間はサポートされているドキュメント形式を記述するインターフェイスとクラスを提供します.
type: docs
weight: 20
url: /ja/net/groupdocs.editor.formats/
---
GroupDocs.Editor.Formats 名前空間は、サポートされているドキュメント形式を記述するインターフェイスとクラスを提供します.

## クラス

| クラス | 説明 |
| --- | --- |
| [EBookFormats.AllEnumerable](./ebookformats.allenumerable) | EBookFormats type の「foreach」機能を有効にする IEnumerable ジェネリック インターフェイスを実装します |
| [EmailFormats.AllEnumerable](./emailformats.allenumerable) | 電子メール タイプの「foreach」機能を有効にする IEnumerable ジェネリック インターフェイスを実装します |
| [FixedLayoutFormats.AllEnumerable](./fixedlayoutformats.allenumerable) | FixedLayoutFormats type の「foreach」の可能性を有効にする IEnumerable ジェネリック インターフェイスを実装します |
| [PresentationFormats.AllEnumerable](./presentationformats.allenumerable) | IEnumerable ジェネリック インターフェイスを実装し、PresentationFormats type の「foreach」の可能性を有効にします |
| [SpreadsheetFormats.AllEnumerable](./spreadsheetformats.allenumerable) | SpreadsheetFormats type の「foreach」機能を有効にする IEnumerable ジェネリック インターフェイスを実装します。 |
| [TextualFormats.AllEnumerable](./textualformats.allenumerable) | TextualFormats type の「foreach」の可能性を有効にする IEnumerable ジェネリック インターフェイスを実装します。 |
| [WordProcessingFormats.AllEnumerable](./wordprocessingformats.allenumerable) | WordProcessingFormats type の「foreach」の可能性を有効にする IEnumerable ジェネリック インターフェイスを実装します |
## 構造物

| 構造 | 説明 |
| --- | --- |
| [EBookFormats](./ebookformats) | すべての eBook 形式をカプセル化します。次のファイル タイプが含まれます: [`Mobi`](../groupdocs.editor.formats/ebookformats/mobi) , [`Epub`](../groupdocs.editor.formats/ebookformats/epub) , [`Azw3`](../groupdocs.editor.formats/ebookformats/azw3) |
| [EmailFormats](./emailformats) | すべての電子メール形式をカプセル化します。次のファイル タイプが含まれます: [`Tnef`](../groupdocs.editor.formats/emailformats/tnef) , [`Eml`](../groupdocs.editor.formats/emailformats/eml) , [`Emlx`](../groupdocs.editor.formats/emailformats/emlx) , [`Msg`](../groupdocs.editor.formats/emailformats/msg) , [`Html`](../groupdocs.editor.formats/emailformats/html) , [`Mhtml`](../groupdocs.editor.formats/emailformats/mhtml). |
| [FixedLayoutFormats](./fixedlayoutformats) | PDF および XPS を含むすべての固定レイアウト (「固定ページ」とも呼ばれる) 形式をカプセル化します (これにはラスター イメージは含まれません) |
| [PresentationFormats](./presentationformats) | すべてのプレゼンテーション形式をカプセル化します。次の形式が含まれます: [`Odp`](../groupdocs.editor.formats/presentationformats/odp) , [`Otp`](../groupdocs.editor.formats/presentationformats/otp) , [`Pot`](../groupdocs.editor.formats/presentationformats/pot) , [`Potm`](../groupdocs.editor.formats/presentationformats/potm) , [`Potx`](../groupdocs.editor.formats/presentationformats/potx) , [`Pps`](../groupdocs.editor.formats/presentationformats/pps) , [`Ppsm`](../groupdocs.editor.formats/presentationformats/ppsm) , [`Ppsx`](../groupdocs.editor.formats/presentationformats/ppsx) , [`Ppt`](../groupdocs.editor.formats/presentationformats/ppt) , [`Ppt95`](../groupdocs.editor.formats/presentationformats/ppt95) , [`Pptm`](../groupdocs.editor.formats/presentationformats/pptm) , [`Pptx`](../groupdocs.editor.formats/presentationformats/pptx). プレゼンテーション形式の詳細[ここ](https://wiki.fileformat.com/presentation). |
| [SpreadsheetFormats](./spreadsheetformats) | ワークブックを保存できる、すべてのバイナリ、XML、およびテキスト形式のスプレッドシート形式 (CSV、TSV、セミコロン区切りなどのセパレーターを含むすべてのテキスト区切り文字ベースの形式を除く) をカプセル化します。 次の形式が含まれます: [`Dif`](../groupdocs.editor.formats/spreadsheetformats/dif) , [`Fods`](../groupdocs.editor.formats/spreadsheetformats/fods) , [`Ods`](../groupdocs.editor.formats/spreadsheetformats/ods) , [`Sxc`](../groupdocs.editor.formats/spreadsheetformats/sxc) , [`Xlam`](../groupdocs.editor.formats/spreadsheetformats/xlam) , [`Xls`](../groupdocs.editor.formats/spreadsheetformats/xls) , [`Xlsb`](../groupdocs.editor.formats/spreadsheetformats/xlsb) , [`Xlsm`](../groupdocs.editor.formats/spreadsheetformats/xlsm) , [`Xlsx`](../groupdocs.editor.formats/spreadsheetformats/xlsx) , [`Xlt`](../groupdocs.editor.formats/spreadsheetformats/xlt) , [`Xltm`](../groupdocs.editor.formats/spreadsheetformats/xltm) , [`Xltx`](../groupdocs.editor.formats/spreadsheetformats/xltx) . スプレッドシート形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet). |
| [TextualFormats](./textualformats) | マークアップ (XML、HTML) などを含むすべてのテキスト (テキストベース) 形式をカプセル化します。 次の形式が含まれます: [`Html`](../groupdocs.editor.formats/textualformats/html) , [`Txt`](../groupdocs.editor.formats/textualformats/txt) , [`Xml`](../groupdocs.editor.formats/textualformats/xml). [`Md`](../groupdocs.editor.formats/textualformats/md) , [`Json`](../groupdocs.editor.formats/textualformats/json). |
| [WordProcessingFormats](./wordprocessingformats) | すべての WordProcessing 形式をカプセル化します。次のファイル タイプが含まれます: [`Doc`](../groupdocs.editor.formats/wordprocessingformats/doc) , [`Docm`](../groupdocs.editor.formats/wordprocessingformats/docm) , [`Docx`](../groupdocs.editor.formats/wordprocessingformats/docx) , [`Dot`](../groupdocs.editor.formats/wordprocessingformats/dot) , [`Dotm`](../groupdocs.editor.formats/wordprocessingformats/dotm) , [`Dotx`](../groupdocs.editor.formats/wordprocessingformats/dotx) , [`FlatOpc`](../groupdocs.editor.formats/wordprocessingformats/flatopc) , [`Odt`](../groupdocs.editor.formats/wordprocessingformats/odt) , [`Ott`](../groupdocs.editor.formats/wordprocessingformats/ott) , [`Rtf`](../groupdocs.editor.formats/wordprocessingformats/rtf) , [`WordML`](../groupdocs.editor.formats/wordprocessingformats/wordml) . ワード プロセッシング形式の詳細[ここ](https://wiki.fileformat.com/word-processing). |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IDocumentFormat](./idocumentformat) | サポートするすべてのドキュメント形式のルート インターフェイス |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
