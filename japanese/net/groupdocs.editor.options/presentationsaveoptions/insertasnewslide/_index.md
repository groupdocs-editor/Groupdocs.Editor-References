---
title: "InsertAsNewSlide"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "スライドが編集された際に、元のプレゼンテーション内の既存スライドを、SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber プロパティで指定された位置に置き換えるか、既存スライドとその前のスライドの間に挿入して内容を置き換えないかを指定するブールフラグです。デフォルトは false で、既存スライドが置き換えられます。このプロパティは、SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber プロパティの値が 0 に設定されている場合は無視されます。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

編集されたスライドが、[`SlideNumber`](../slidenumber) プロパティで指定された位置にある元のプレゼンテーションの既存スライドを置き換えるか、既存スライドとその前のスライドの間に挿入して内容を置き換えないかを指定するブールフラグです。デフォルトは `false` で、既存スライドが置き換えられます。このプロパティは、[`SlideNumber`](../slidenumber) プロパティの値が `'0'` に設定されている場合は無視されます。

```csharp
public bool InsertAsNewSlide { get; set; }
```

### 備考

デフォルトではスライドは置き換えられます。つまり、プレゼンテーションにスライドが 5 枚あり、[`SlideNumber`](../slidenumber)=4 の場合、4 番目のスライドが新しい編集スライドに置き換えられ、プレゼンテーション全体のスライド数 (5) は変わりません。しかし、このプロパティの値が true に設定されている場合、新しい編集スライドは 4 番目のスライドとして挿入され、その後のすべてのスライドが末尾へシフトします。すなわち、\"old\" 4 番目のスライドが 5 番目になり、5 番目が 6 番目になり、プレゼンテーションのスライド総数は 1 増えて 6 になります。

### 参照

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
