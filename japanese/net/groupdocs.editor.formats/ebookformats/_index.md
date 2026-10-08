---
title: "EBookFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべてのeBook形式をカプセル化します。次のファイルタイプが含まれます Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3。"
type: docs
weight: 80
url: /ja/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

すべてのeBook形式をカプセル化します。次のファイルタイプが含まれます: [`Mobi`](./mobi)、[`Epub`](./epub)、[`Azw3`](./azw3)。

```csharp
public class EBookFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | すべての[`EBookFormats`](../ebookformats)の列挙可能なコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | 指定されたファイル拡張子を持つ、指定されたタイプ[`EBookFormats`](../ebookformats)のインスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | ファイル拡張子を表す文字列を[`EBookFormats`](../ebookformats)オブジェクトに変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3は、Kindle Format 8 (KF8)としても知られる、Amazon Kindleデバイス向けに開発されたAZW電子書籍デジタルファイル形式の改良版です。この形式は古いAZWファイルの拡張です。このファイル形式の詳細は[here](https://docs.fileformat.com/ebook/azw3/)でご覧ください。 |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Electronic Publication (IDPF ePub)形式は、出版社と消費者向けに標準的なデジタル出版形式を提供するeBookファイル形式です。このファイル形式の詳細は[here](https://docs.fileformat.com/ebook/epub/)でご覧ください。 |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBIはMobiPocket Reader用に開発された形式の名称です。PRC、AZWとも呼ばれます。現在はAmazonが若干異なるDRMスキームで使用しており、AZWと呼ばれます。このファイル形式の詳細は[here](https://docs.fileformat.com/ebook/mobi/)でご覧ください。 |

### 備考

Mobi形式の詳細は[here](https://docs.fileformat.com/ebook/mobi/)、AZW3形式の詳細は[here](https://docs.fileformat.com/ebook/azw3/)、ePub形式の詳細は[here](https://docs.fileformat.com/ebook/epub/)をご覧ください。

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
