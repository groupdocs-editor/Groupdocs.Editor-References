---
title: "GeneratePreview"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "選択されたページのプレビューを SVG 画像として生成し、返します"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

選択されたページのプレビューを SVG 画像として生成し、返します

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageIndex | Int32 | 目的のページの 0 ベースインデックスです。0 未満にすることも、この WordProcessing ドキュメントのページ数を超えることもできません。 |

### 戻り値

SVG 画像は、[`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) クラスの null でないインスタンスとして

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された *pageIndex* が 0 未満、またはこの WordProcessing ドキュメントのページ数を超えています。 |

### 参照

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
