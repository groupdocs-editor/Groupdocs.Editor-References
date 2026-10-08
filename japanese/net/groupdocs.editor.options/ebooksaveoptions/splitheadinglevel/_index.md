---
title: "SplitHeadingLevel"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "eBook ファイルを分割する見出しの最大レベルを指定します。デフォルト値は 2 です。0 に設定すると分割が無効になり、eBook のすべてのコンテンツが結果ファイル内の単一パッケージに組み込まれます。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

e-Book ファイルを分割する見出しの最大レベルを指定します。デフォルト値は `2` です。`0` に設定すると分割が無効になり、e-Book のすべてのコンテンツが結果ファイル内の単一パッケージに統合されます。

```csharp
public int SplitHeadingLevel { get; set; }
```

### 備考

このプロパティが 1 から 9 の値に設定されている場合、文書は **Heading 1**、**Heading 2**、**Heading 3** など、指定された見出しレベルまでのスタイルでフォーマットされた段落で分割されます。

デフォルトでは、**Heading 1** と **Heading 2** の段落だけが文書の分割を引き起こします。このプロパティを 0（または 0 未満）に設定すると、見出し段落で文書がまったく分割されなくなります。

### 参照

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
