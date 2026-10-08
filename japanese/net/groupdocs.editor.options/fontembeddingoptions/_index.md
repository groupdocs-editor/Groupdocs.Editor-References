---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォント埋め込みオプションは、出力される WordProcessing または PDF ドキュメントに埋め込むフォントリソースを制御します。"
type: docs
weight: 880
url: /ja/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

フォント埋め込みオプションは、出力される WordProcessing または PDF ドキュメントに埋め込むフォントリソースを制御します。

```csharp
public enum FontEmbeddingOptions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NotEmbed | `0` | EditableDocument またはシステムからフォントリソースを埋め込まないでください。デフォルト値です。 |
| EmbedAll | `1` | 入力 EditableDocument のドキュメント内容を解析し、使用されているすべてのフォントを見つけて、出力の WordProcessing または PDF ドキュメントに埋め込みます。まず、GroupDocs.Editor は EditableDocument 内のフォントリソースからフォントを取得します。もしそれらが不足または欠如している場合、GroupDocs.Editor は OS からフォントを取得します。 |
| EmbedWithoutSystem | `2` | EmbedAll と同等ですが、OS によってシステムフォントとみなされるフォントは除外します。 |

### 備考

フォント埋め込みオプションは、ドキュメントの保存時（中間の EditableDocument から出力の WordProcessing または PDF 形式への変換）に適用されます。この列挙型は WordProcessingSaveOptions と PdfSaveOptions のプロパティとして含まれており、そこから使用されます。

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
