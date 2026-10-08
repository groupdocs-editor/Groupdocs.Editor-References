---
title: "SlideNumbersToDelete"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集スライドが既存のプレゼンテーションに挿入される場合に、保存時にプレゼンテーションから削除すべきスライドの 1 ベース番号の配列を指定できます。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

編集されたスライドが既存のプレゼンテーションに挿入される場合に、保存時にプレゼンテーションから削除すべきスライドの 1 から始まる番号の配列を指定できます

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### 備考

編集スライドが新しい単一スライドプレゼンテーションとして保存されず（デフォルトの動作）、[`SlideNumber`](../slidenumber) プロパティを使用して既存のプレゼンテーションに保存される場合、この配列で番号を指定することで、特定のスライドを削除することも可能です。

デフォルトではこの配列は `null` で、スライドは削除されません。ただし、配列が null でなく空でもない場合、少なくとも 1 つの有効なスライド番号が含まれていれば、編集スライドの内容で出力プレゼンテーションドキュメントが生成された後、指定された番号のスライドは出力ストリームまたはファイルに書き込む直前にプレゼンテーションから削除されます。

この配列のスライド番号は 1 ベースであり、0 ベースではありません。無効な番号（1 未満またはスライド総数を超えるもの）は無視されます。

### 参照

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
