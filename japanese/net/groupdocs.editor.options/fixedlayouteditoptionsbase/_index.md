---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "PDF や XPS などの固定レイアウト形式のすべてのドキュメント向けオプションの基底抽象クラスです"
type: docs
weight: 870
url: /ja/net/groupdocs.editor.options/fixedlayouteditoptionsbase/
---
## FixedLayoutEditOptionsBase class

PDFやXPSなどの固定レイアウト形式のすべてのドキュメント用オプションの基底抽象クラスです。

```csharp
public abstract class FixedLayoutEditOptionsBase : IEditOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | 生成された HTML ドキュメントでページネーションを有効 (true) または無効 (false) にできます。デフォルトは無効 (false) です。 |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | 処理するページ範囲を設定できます。デフォルトでは固定レイアウトドキュメントのすべてのページが処理されます。 |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | 入力の固定レイアウトドキュメントを生成された HTML に変換する際に画像をスキップするかどうかを示すフラグを取得または設定します。デフォルトは false で、画像は保持されます。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
