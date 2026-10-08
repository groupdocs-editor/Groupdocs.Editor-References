---
title: "パスワード"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "生成された PDF ドキュメントに適用されるユーザーパスワードです。NULL または空の場合、ドキュメントにパスワードは適用されません。それ以外の場合、ドキュメントは 128 ビットの RC4 鍵長で暗号化されます。デフォルトは NULL で、パスワードは適用されません。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor.options/pdfsaveoptions/password/
---
## PdfSaveOptions.Password property

生成された PDF ドキュメントにユーザーパスワードとして適用されるパスワードで、開く際に必要です。NULL または空文字列の場合、ドキュメントにパスワードは適用されません。それ以外の場合、ドキュメントは RC4（鍵長 128 ビット）で暗号化されます。デフォルトは NULL で、パスワードは適用されません。

```csharp
public string Password { get; set; }
```

### 参照

* class [PdfSaveOptions](../../pdfsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
