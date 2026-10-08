---
title: "FromStartPageTillEndPage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された開始ページ番号から（含む）開始し、指定された終了ページ番号まで（除く）続くページ範囲を作成します。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

指定されたページ番号（包括的）から開始し、指定されたページ番号（排他的）まで続くページ範囲を作成します。

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startPageNumber | UInt16 | ページ番号（ページ範囲が開始するページ番号、開始は含む）。ページ番号は1から始まり、0より大きい必要があります。 |
| endPageNumber | UInt16 | ページ番号（ページ範囲が終了するページ番号、終了は含まない）。ページ番号は1から始まり、0より大きい必要があり、さらに *startPageNumber* より大きくなければなりません。 |

### 参照

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
