---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "集約された HTML ドキュメントの MHTML MIME カプセル化を生成および保存するためのカスタムオプションを指定できるようにします。"
type: docs
weight: 1020
url: /ja/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

MHTML（複数の HTML ドキュメントの MIME カプセル化）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照するために CID（Content-ID）URL を使用するかどうかを指定します。既定値は `false` です。 |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | 組み込みおよびカスタムのドキュメントプロパティを MHTML にエクスポートするかどうかを指定します。既定値は `false` です。 |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | 言語情報を MHTML にエクスポートするかどうかを指定します。既定値は `false` です。 |

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
