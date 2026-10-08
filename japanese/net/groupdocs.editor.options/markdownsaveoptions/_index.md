---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Markdown ドキュメントを生成および保存するためのカスタムオプションを指定できます。"
type: docs
weight: 1000
url: /ja/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | 画像を Base64 形式で出力ファイルに保存するかどうかを指定します。デフォルトは `false` です。 |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | ドキュメントを Markdown 形式でエクスポートする際に画像が保存される物理フォルダーを指定します。デフォルトは null です。 |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | HTML からのドキュメント生成中にメモリ最適化メカニズムを有効にしますが、メモリ使用量の削減を代償としてパフォーマンスが低下します。このオプションを `true` に設定すると、大きなドキュメント生成時のメモリ消費を大幅に減らすことができますが、保存時間が遅くなります。デフォルトは `false` です（パフォーマンス向上のためメモリ最適化は無効になっています）。 |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow は、Markdown 形式にエクスポートする際にテーブル内のコンテンツをどのように配置するかを指定します。デフォルト値は Auto です。 |

### 備考

MarkdownSaveOptions クラスは、編集されたドキュメントコンテンツを含む EditableDocument クラスのインスタンスが存在し、そのコンテンツを Markdown 形式の新しいドキュメントに保存する必要がある場合に、ユーザーによって適用されなければなりません。

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
