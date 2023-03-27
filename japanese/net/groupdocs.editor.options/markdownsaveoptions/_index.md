---
title: MarkdownSaveOptions
second_title: GroupDocs.Editor for .NET API リファレンス
description: Markdown ドキュメントを生成および保存するためのカスタム オプションを指定できます
type: docs
weight: 990
url: /ja/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown ドキュメントを生成および保存するためのカスタム オプションを指定できます

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | 画像を Base64 形式で出力ファイルに保存するかどうかを指定します。デフォルトは`間違い`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | ドキュメントを Markdown 形式に エクスポートするときに画像が保存される物理フォルダーを指定します。デフォルトは null. です。 |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | HTML からドキュメントを生成する際にメモリ最適化メカニズムを有効にします。これにより、メモリ使用量が減少する代わりにパフォーマンスが低下します。 このオプションを`真実`保存時間が遅くなりますが、大きなドキュメントを生成する際のメモリ消費量を大幅に削減できます。 デフォルトは`間違い`(パフォーマンスを向上させるために、メモリの最適化は無効になっています). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow は、Markdown 形式にエクスポートするときにテーブルの内容を整列する方法を指定します。 デフォルト値はAuto. |

### 備考

MarkdownSaveOptions クラスは、編集されたドキュメント コンテンツを含む EditableDocument クラスのインスタンスがあり、このコンテンツを Markdown 形式の新しいドキュメントに保存する必要がある場合に、ユーザーが適用する必要があります。

### 関連項目

* interface [ISaveOptions](../isaveoptions)
* 名前空間 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->