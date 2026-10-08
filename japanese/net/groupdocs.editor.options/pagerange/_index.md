---
title: "PageRange"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1 つのページ範囲をカプセル化し、開いた境界または閉じた境界を持つことができます。デフォルトでは完全にオープンで、既存のすべてのページが含まれます。ページ番号は 0 ではなく 1 から始まります。"
type: docs
weight: 1030
url: /ja/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

開閉可能な境界を持つページ範囲をカプセル化します。デフォルトは「完全にオープン」で、すべての既存ページを含みます。ページ番号は 0 ではなく 1 から始まります。

```csharp
public struct PageRange : IEquatable<PageRange>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | 範囲内のページ数です。0 の場合、ページ範囲はドキュメントの末尾まで広がり、ページ数に関係なく続きます。 |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | 排他的な終了ページ番号で、このページ範囲はこの番号まで続き、そこまでで終了します。0 の場合、ページ範囲はドキュメントの末尾まで広がります。 |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | このインスタンスがデフォルトの "完全にオープン" ページ範囲（すなわちドキュメントのすべてのページを表す）かどうかを示します (true) または (false)。 |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | 包括的な開始ページ番号で、このページ範囲はこの番号から始まります。1 の場合、ページ範囲はドキュメントの最初のページから始まります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | 最初のページから開始し、指定されたページ数を持つページ範囲を作成します。 |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | 指定されたページ番号から開始し、ドキュメントの末尾まで続くページ範囲を作成します。 |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | 指定されたページ番号（包括的）から開始し、指定されたページ番号（排他的）まで続くページ範囲を作成します。 |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | 指定されたページ番号から開始し、指定されたページ数、または無制限のページ数（末尾まで）を持つページ範囲を作成します。 |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | この PageRange インスタンスが指定されたものと等しいかどうかを検出します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | ドキュメントのすべての既存ページを表します。デフォルト値です。 |

### 備考

特定のドキュメントに依存しないページ範囲をカプセル化する不変構造体で、任意のドキュメントのページ範囲を表すことができます。

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
