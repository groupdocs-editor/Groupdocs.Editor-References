---
title: "FromStartPageWithCount"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定されたページ番号から開始し、指定されたページ数または終了までの無制限のページ数を持つページ範囲を作成します。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

指定されたページ番号から開始し、指定されたページ数、または無制限のページ数（末尾まで）を持つページ範囲を作成します。

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startPageNumber | UInt16 | ページ番号（ページ範囲が開始するページ番号、開始は含む）。ページ番号は1から始まり、0より大きい必要があります。 |
| pageCount | UInt16 | ページ数。0より大きい必要があります。0の場合は、ドキュメントの最後までのすべてのページを意味します。 |

### 戻り値

新しい PageRange インスタンス

### 参照

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
