---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "XPS XML Paper Specifications ドキュメントの生成および保存のためのカスタムオプションを指定できます"
type: docs
weight: 1300
url: /ja/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

XPS（XML Paper Specifications）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。このオプションを true に設定すると、大きなドキュメント生成時のメモリ消費を大幅に削減できますが、保存時間が遅くなります。デフォルトは false で、より高いパフォーマンスのためにメモリ最適化は無効になっています。 |

### 備考

XPS ファイルは、Microsoft が作成した XML Paper Specifications に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、ドキュメントのレイアウト、外観、印刷情報に XML を使用します。

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
