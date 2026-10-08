---
title: "SlideNumber"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "編集用に開くスライド番号を指定できます。"
type: docs
weight: 30
url: /ja/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

編集用に開くスライド番号を指定できます。

```csharp
public int SlideNumber { get; set; }
```

### 備考

スライド番号はスライドのゼロベースインデックスで、プレゼンテーションから特定のスライドを選択して編集できます。0 未満の場合は最初のスライドが選択されます（SlideNumber = 0 と同じ）。プレゼンテーション内のスライド数を超える場合は最後のスライドが選択されます。入力プレゼンテーションが単一スライドのみの場合、このオプションは無視され、そのスライドが編集されます。[`ShowHiddenSlides`](../showhiddenslides) オプションが 'false' に設定されている場合、例外がスローされます。

### 参照

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
