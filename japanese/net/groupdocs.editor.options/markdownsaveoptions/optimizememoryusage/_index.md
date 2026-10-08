---
title: "OptimizeMemoryUsage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。このオプションを true に設定すると、大きなドキュメント生成時のメモリ消費を大幅に減らすことができますが、保存時間が遅くなります。デフォルトは false で、より高いパフォーマンスを得るためにメモリ最適化は無効になっています。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.options/markdownsaveoptions/optimizememoryusage/
---
## MarkdownSaveOptions.OptimizeMemoryUsage property

HTML からのドキュメント生成中にメモリ最適化メカニズムを有効にしますが、メモリ使用量の削減を代償としてパフォーマンスが低下します。このオプションを `true` に設定すると、大きなドキュメント生成時のメモリ消費を大幅に減らすことができますが、保存時間が遅くなります。デフォルトは `false` です（パフォーマンス向上のためメモリ最適化は無効になっています）。

```csharp
public bool OptimizeMemoryUsage { get; set; }
```

### 参照

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
