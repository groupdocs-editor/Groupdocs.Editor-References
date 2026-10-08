---
title: "ExportImagesAsBase64"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "画像を出力ファイルに Base64 形式で保存するかどうかを指定します。デフォルトは false です。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64/
---
## MarkdownSaveOptions.ExportImagesAsBase64 property

画像を Base64 形式で出力ファイルに保存するかどうかを指定します。デフォルトは `false` です。

```csharp
public bool ExportImagesAsBase64 { get; set; }
```

### 備考

このプロパティが `true` に設定されている場合、画像データは画像要素 ![]() に直接エクスポートされ、別ファイルは作成されません。このプロパティが `true` の場合、[`ImagesFolder`](../imagesfolder) プロパティよりも優先されます。

### 参照

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
