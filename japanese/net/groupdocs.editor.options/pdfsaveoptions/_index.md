---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "PDF（Portable Document Format）ドキュメントの生成および保存のためのカスタムオプションを指定できます。"
type: docs
weight: 1070
url: /ja/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

PDF（Portable Document Format）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | 出力ドキュメントの PDF 標準準拠レベルを指定します。デフォルトは PdfCompliance.Pdf17 です。 |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | 元のドキュメントで使用されているフォントリソースを、生成された PDF ドキュメントに埋め込むことを担当します。デフォルトではフォントは埋め込まれません (NotEmbed)。 |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。このオプションを true に設定すると、大きなドキュメント生成時のメモリ消費を大幅に削減できますが、保存時間が遅くなります。デフォルトは false で、より高いパフォーマンスのためにメモリ最適化は無効になっています。 |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | 生成された PDF ドキュメントにユーザーパスワードとして適用されるパスワードで、開く際に必要です。NULL または空文字列の場合、ドキュメントにパスワードは適用されません。それ以外の場合、ドキュメントは RC4（鍵長 128 ビット）で暗号化されます。デフォルトは NULL で、パスワードは適用されません。 |

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
