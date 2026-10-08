---
title: "FixedName"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "修復後のフォームフィールドの新しい名前を取得または設定します。この名前は他のフォームフィールドとの重複する一意の識別子を削除し、一意のブックマーク名を設定します。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor.words.fieldmanagement/invalidformfield/fixedname/
---
## InvalidFormField.FixedName property

修復後のフォームフィールドの新しい名前を取得または設定します。この名前は他のフォームフィールドとの重複する一意の識別子を削除し、一意のブックマーク名を設定します。

```csharp
public string FixedName { get; set; }
```

### 備考

```csharp
FixedName = string.Format("{0}_fixed", name) // as default value.
```

### 参照

* class [InvalidFormField](../../invalidformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
