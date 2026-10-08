---
title: "PresentationFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべてのプレゼンテーション形式をカプセル化します。以下の形式が含まれます"
type: docs
weight: 120
url: /ja/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

すべてのプレゼンテーション形式をカプセル化します。以下の形式が含まれます:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

プレゼンテーション形式の詳細は[こちら](https://wiki.fileformat.com/presentation)をご覧ください。

```csharp
public class PresentationFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | すべての[`PresentationFormats`](../presentationformats)の列挙可能なコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | 指定されたファイル拡張子を持つ、指定タイプの[`PresentationFormats`](../presentationformats)インスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | ファイル拡張子を表す文字列を[`PresentationFormats`](../presentationformats)オブジェクトに変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument プレゼンテーション (ODP)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/odp)をご覧ください。 |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument プレゼンテーションテンプレート (OTP)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/otp)をご覧ください。 |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 プレゼンテーションテンプレート (POT)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/pot)をご覧ください。 |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML マクロ有効テンプレート (POTM)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/potm)をご覧ください。 |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML マクロ無効テンプレート (POTX)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/potx)をご覧ください。 |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 スライドショー (PPS)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/pps)をご覧ください。 |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML マクロ有効スライドショー (PPSM)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/ppsm)をご覧ください。 |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML マクロ無効スライドショー (PPSX)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/ppsx)をご覧ください。 |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 プレゼンテーション (PPT)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/ppt)をご覧ください。 |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 プレゼンテーション (PPT)。 |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML マクロ有効ドキュメント (PPTM)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/pptm)をご覧ください。 |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML マクロ無効ドキュメント (PPTX)。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/pptx)をご覧ください。 |

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
