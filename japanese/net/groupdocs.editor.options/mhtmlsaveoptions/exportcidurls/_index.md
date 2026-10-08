---
title: "ExportCidUrls"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照する際に CID ContentID URL を使用するかどうかを指定します。デフォルト値は false です。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

MHTML ドキュメントに含まれるリソース（画像、フォント、CSS）を参照するために CID（Content-ID）URL を使用するかどうかを指定します。既定値は `false` です。

```csharp
public bool ExportCidUrls { get; set; }
```

### 備考

デフォルトでは、MHTML ドキュメント内のリソースはファイル名（例: "image.png"）で参照され、MIME パートの "Content-Location" ヘッダーと照合されます。このオプションを有効にすると、リソースファイルへの参照を CID（Content-ID）URL（例: "cid:image.png"）として記述し、"Content-ID" ヘッダーと照合する代替方法が使用できるようになります。

理論上、2 つの参照方法に違いはなく、どちらも任意のブラウザやメールエージェントで正常に動作するはずです。しかし実際には、一部のエージェントがファイル名でリソースを取得できないことがあります。ブラウザやメールエージェントが MTHML ドキュメントに含まれるリソース（画像が表示されない、CSS が読み込まれないなど）をロードしない場合は、CID URL でドキュメントをエクスポートしてみてください。

### 参照

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
