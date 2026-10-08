---
title: "OptimizeMemoryUsage"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "入力ドキュメントの処理中にメモリ最適化機構を有効にします。これにより特定のケースでパフォーマンスが低下する可能性がありますが、代わりにメモリ使用量が減少します。巨大なドキュメントを処理し、OutOfMemoryException に直面する場合に便利です。デフォルトは false で、パフォーマンス向上のためメモリ最適化は無効になっています。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage/
---
## DelimitedTextEditOptions.OptimizeMemoryUsage property

入力ドキュメントの処理中にメモリ最適化機構を有効にします。これにより特定のケースでパフォーマンスが低下する可能性がありますが、メモリ使用量は減少します。巨大なドキュメントを処理し、OutOfMemoryException に直面する場合に有用です。デフォルトは `false`（パフォーマンス向上のためメモリ最適化は無効になっています）。

```csharp
public bool OptimizeMemoryUsage { get; set; }
```

### 参照

* class [DelimitedTextEditOptions](../../delimitedtexteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
