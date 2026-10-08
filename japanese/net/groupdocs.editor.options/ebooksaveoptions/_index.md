---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポートされているすべての eBook 形式（ePub、MOBI、AZW3）でドキュメントを生成および保存するためのカスタムオプションを指定できるようにします。"
type: docs
weight: 840
url: /ja/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

すべてのサポート可能な電子書籍フォーマット（ePub、MOBI、AZW3）でドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | このパラメータなしコンストラクタは、ePub 出力形式で EbookSaveOptions の新しいインスタンスを作成します（その後、[`OutputFormat`](./outputformat) プロパティで変更可能です）。 |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | 指定された必須 e-Book 出力形式で、[`EbookSaveOptions`](../ebooksaveoptions) の新しいインスタンスを作成し、他のすべてのパラメータはデフォルトのままにします。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | 結果ファイルに組み込みおよびカスタムドキュメントプロパティをエクスポートするかどうかを指定します。デフォルト値は `false` です。 |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | 結果の e-Book ファイルの形式を指定します：IDPF ePub、MOBI、または AZW3。 |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | e-Book ファイルを分割する見出しの最大レベルを指定します。デフォルト値は `2` です。`0` に設定すると分割が無効になり、e-Book のすべてのコンテンツが結果ファイル内の単一パッケージに統合されます。 |

### 備考

サポートされている e-Book 形式：

1. [ePub](https://docs.fileformat.com/ebook/epub/)（Electronic Publication）
2. [MOBI](https://docs.fileformat.com/ebook/mobi/)（MobiPocket）
3. [AZW3](https://docs.fileformat.com/ebook/azw3/)（Kindle Format 8t）

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
