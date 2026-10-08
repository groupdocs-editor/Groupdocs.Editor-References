---
title: "HasInvalidFormFields"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ドキュメントに無効なフォームフィールドが含まれているかどうかを確認します。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

ドキュメントに無効なフォームフィールドが含まれているかどうかを確認します。

```csharp
public bool HasInvalidFormFields()
```

### 戻り値

`true` は、ドキュメントに 1 つ以上の無効なフォーム フィールドが含まれている場合です。そうでない場合は `false` です。

### 備考

`HasInvalidFormFields` メソッドは、ドキュメントの内容をスキャンして、無効な名前のフォーム フィールドが含まれているかどうかを判断します。フォーム フィールドは、他のフォーム フィールドと一意の識別子が重複し、かつそれに関連付けられた一意のブックマーク名がない場合、無効とみなされます。これらのブックマーク名は各フォーム フィールドの識別子として機能します。このメソッドは、ドキュメントがさらに検査やフォーム フィールド名の修正を必要とするかどうかを迅速にチェックするのに役立ちます。 ; ; ;

### 参照

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
