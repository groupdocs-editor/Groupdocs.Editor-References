---
title: "GeneratePreview"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "選択されたワークシートのプレビューを SVG 画像として生成し、返します"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

選択されたワークシートのプレビューを SVG 画像として生成し、返します

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | Int32 | 目的のワークシートの 0 ベースインデックスです。0 未満にすることも、このスプレッドシートのワークシート数を超えることもできません。 |

### 戻り値

SVG 画像は、[`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) クラスの null でないインスタンスとして

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された *worksheetIndex* が 0 未満、またはこのスプレッドシートのワークシート数を超えています。 |

### 参照

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
