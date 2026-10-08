---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポートされている任意のメール形式の 1 つのメールドキュメントのメタデータを表します"
type: docs
weight: 720
url: /ja/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

サポートされている任意のメール形式の 1 つのメールドキュメントのメタデータを表します

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | このメールドキュメントの形式を返します |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | メールドキュメントはパスワードで暗号化できないため、このプロパティは常に 'false' を返します |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | メールドキュメントにはページビューがないため、常に 1 を返します |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | このメールドキュメントのサイズ（バイト）を返します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | このインスタンスが指定された EmailDocumentInfo インスタンスと等しいかどうかを判定します |

### 参照

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
