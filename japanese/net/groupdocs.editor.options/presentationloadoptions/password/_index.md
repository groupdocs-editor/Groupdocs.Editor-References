---
title: "パスワード"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "エンコードされた Presentation ドキュメントを開く際に使用されるパスワードを指定、変更、取得できます。パスワードを削除する場合は NULL または空文字列に設定してください。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

エンコードされたプレゼンテーションドキュメントを開く際に使用されるパスワードを指定、変更、取得できます。パスワードを削除するには NULL または空文字列に設定してください。

```csharp
public string Password { get; set; }
```

### 備考

既定ではこのプロパティは NULL 値です — パスワードは設定されていません。入力の Presentation ドキュメントがパスワードで保護されている場合、パスワードは必須で、指定されていないまたは無効な場合は例外がスローされます。入力の Presentation ドキュメントがパスワードで保護されていない場合でも、パスワードが設定されていると無視されます。

### 参照

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
