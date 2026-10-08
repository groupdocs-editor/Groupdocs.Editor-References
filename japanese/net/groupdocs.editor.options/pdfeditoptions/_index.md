---
title: "PdfEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "PDF ドキュメントを編集するためのカスタムオプションを指定できます。"
type: docs
weight: 1050
url: /ja/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

PDF ドキュメントを編集するためのカスタムオプションを指定できます。

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | PdfEditOptions クラスの新しいインスタンスを作成して返します。すべてのオプションはデフォルト値に設定されています。 |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | 指定されたページングで PdfEditOptions クラスの新しいインスタンスを作成し、他のすべてのオプションはデフォルトに設定して返します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | 生成された HTML ドキュメントでページネーションを有効 (true) または無効 (false) にできます。デフォルトは無効 (false) です。 |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | 処理するページ範囲を設定できます。デフォルトでは固定レイアウトドキュメントのすべてのページが処理されます。 |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | 入力の固定レイアウトドキュメントを生成された HTML に変換する際に画像をスキップするかどうかを示すフラグを取得または設定します。デフォルトは false で、画像は保持されます。 |

### 参照

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
