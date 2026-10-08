---
title: "GetEmbeddedHtml"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "この HTML ドキュメントのすべてのコンテンツと関連リソースを、すべてのリソースが HTML マークアップ内に Base64 エンコードされた形で埋め込まれた単一の文字列として返します。"
type: docs
weight: 150
url: /ja/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

この HTML ドキュメントのすべてのコンテンツと関連リソースを、単一の文字列として返します。すべてのリソースは HTML マークアップ内に base64 エンコードされた形で埋め込まれます

```csharp
public string GetEmbeddedHtml()
```

### 戻り値

NULL でも空文字でもない文字列

### 例外

| 例外 | 条件 |
| --- | --- |
| ObjectDisposedException | この EditableDocument インスタンスは既に破棄されました |

### 備考

このメソッドはこの EditableDocument を HTML に変換し、すべてのリソースが HTML マークアップと共に文字列に埋め込まれた単一の文字列にシリアライズします。

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### 参照

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
