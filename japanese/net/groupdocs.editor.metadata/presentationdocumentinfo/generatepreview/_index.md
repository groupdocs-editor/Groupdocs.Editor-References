---
title: "GeneratePreview"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "選択されたスライドのプレビューを SVG 画像として生成し、返します"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

選択されたスライドのプレビューを SVG 画像として生成し、返します

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| slideIndex | Int32 | 目的のスライドの 0 ベースインデックスです。0 未満にすることはできず、このプレゼンテーションのスライド数を超えることもできません。 |

### 戻り値

SVG 画像は、[`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) クラスの null でないインスタンスとして

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された *slideIndex* が 0 未満、またはこのプレゼンテーションのスライド数を超えています |

### 参照

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
