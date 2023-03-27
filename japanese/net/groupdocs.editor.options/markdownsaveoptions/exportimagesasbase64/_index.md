---
title: ExportImagesAsBase64
second_title: GroupDocs.Editor for .NET API リファレンス
description: 画像を Base64 形式で出力ファイルに保存するかどうかを指定しますデフォルトは間違い.
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64/
---
## MarkdownSaveOptions.ExportImagesAsBase64 property

画像を Base64 形式で出力ファイルに保存するかどうかを指定します。デフォルトは`間違い`.

```csharp
public bool ExportImagesAsBase64 { get; set; }
```

### 備考

このプロパティが`真実`の場合、画像データは直接 the image elements ![]() にエクスポートされ、個別のファイルは作成されません。に設定されている場合、このプロパティ`真実`、より優先度が高い[`ImagesFolder`](../imagesfolder)財産。

### 関連項目

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* 名前空間 [GroupDocs.Editor.Options](../../markdownsaveoptions)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->