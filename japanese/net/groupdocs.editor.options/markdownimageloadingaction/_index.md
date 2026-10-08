---
title: "MarkdownImageLoadingAction"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Markdown 形式でファイルを開いて編集する際の画像読み込みモードを定義します。"
type: docs
weight: 990
url: /ja/net/groupdocs.editor.options/markdownimageloadingaction/
---
## MarkdownImageLoadingAction enumeration

Markdown 形式でファイルを開いて編集する際の画像読み込みモードを定義します。

```csharp
public enum MarkdownImageLoadingAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | `0` | GroupDocs.Editor はこのリソースを通常どおりロードします |
| Skip | `1` | GroupDocs.Editor はこの画像のロードをスキップします |
| UserProvided | `2` | GroupDocs.Editor はユーザーが [`SetData`](../markdownimageloadargs/setdata) で提供したバイト配列を画像データとして使用します |

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
