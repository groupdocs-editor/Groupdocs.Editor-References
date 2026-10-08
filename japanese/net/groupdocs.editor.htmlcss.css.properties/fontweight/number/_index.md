---
title: "数"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "1 から 1000 までの整数値を返します。この値はフォントの太さを示しますが、現在の太さが絶対値ではなく相対値の場合は例外をスローします。"
type: docs
weight: 90
url: /ja/net/groupdocs.editor.htmlcss.css.properties/fontweight/number/
---
## FontWeight.Number property

1 から 1000 の範囲（包括）の整数値を返します。この数値はフォントの太さを表しますが、現在の太さが絶対値ではなく相対値の場合は例外をスローします。

```csharp
public ushort Number { get; }
```

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | 現在の font-weight がフォントの太さの相対値を保持している場合にスローされます。 |

### 参照

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
