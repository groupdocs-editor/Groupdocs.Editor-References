---
title: "PdfCompliance"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "PDF 標準準拠レベルを指定します。"
type: docs
weight: 1040
url: /ja/net/groupdocs.editor.options/pdfcompliance/
---
## PdfCompliance enumeration

PDF 標準準拠レベルを指定します。

```csharp
public enum PdfCompliance
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Pdf17 | `0` | PDF 1.7（ISO 32000-1）標準 |
| Pdf20 | `1` | PDF 2.0（ISO 32000-2）標準 |
| PdfA1a | `2` | PDF/A-1a 標準。このレベルは PDF/A-1b のすべての要件を含み、さらに文書構造（"tagged" とも呼ばれる）を含めることを要求します。目的は文書内容が検索可能で再利用できるようにすることです。 |
| PdfA1b | `3` | PDF/A-1b（ISO 19005-1）。PDF/A-1b の目的は、文書の視覚的外観を信頼性高く再現できるようにすることです。 |
| PdfA2a | `4` | PDF/A-2a（ISO 19005-2）標準。このレベルは PDF/A-2u のすべての要件を含み、さらに文書構造（"tagged" とも呼ばれる）を含めることを要求します。目的は文書内容が検索可能で再利用できるようにすることです。 |
| PdfA2u | `5` | PDF/A-2u（ISO 19005-2）標準。PDF/A-2u の目的は、作成・保存・表示に使用されるツールやシステムに依存せず、時間経過にわたって文書の静的な視覚外観を保持することです。さらに、文書に含まれるテキストは Unicode コードポイントの系列として信頼性高く抽出できます。 |
| PdfUa1 | `6` | PDF/UA-1（ISO 14289-1）標準。PDF/UA の主な目的は、PDF 形式で電子文書を表現し、ファイルをアクセシブルにできるように定義することです。 |

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
