---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "PDF などのラスタ画像形式を除く、fixedlayout fixedpage ドキュメント形式を表します。"
type: docs
weight: 100
url: /ja/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

PDF などの固定レイアウト（固定ページ）ドキュメント形式を表しますが、ラスター画像形式は除外します。

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | 利用可能なすべての[`FixedLayoutFormats`](../fixedlayoutformats)インスタンスを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | 指定されたファイル拡張子に一致する[`FixedLayoutFormats`](../fixedlayoutformats)インスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | ファイル拡張子文字列を[`FixedLayoutFormats`](../fixedlayoutformats)インスタンスに明示的に変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Adobe が導入した Portable Document Format (PDF) は、ソフトウェア、ハードウェア、オペレーティングシステムに依存しない文書の標準化された表現を提供します。詳細については、[PDF ファイル形式](https://docs.fileformat.com/pdf/)をご参照ください。 |

### 備考

Fixed-layout 形式は、各ページ上のコンテンツの配置とレンダリングを正確に指定します。Adobe Acrobat や Adobe InDesign などの文書閲覧、出版、編集アプリケーションで一般的に使用されます。これらの形式は、ベクターグラフィックスとテキスト指示を使用して、ページレイアウトとコンテンツの位置を内部的に定義します。

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
