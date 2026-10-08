---
title: "GetFormField"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された名前とタイプのフォームフィールドを取得します。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.words.fieldmanagement/formfieldcollection/getformfield/
---
## FormFieldCollection.GetFormField&lt;T&gt; method

指定された名前とタイプのフォームフィールドを取得します。

```csharp
public T GetFormField<T>(string name)
    where T : IFormField
```

| パラメーター | 説明 |
| --- | --- |
| T | フォームフィールドのタイプです。 |
| 名前 | フォームフィールドの名前です。 |

### 戻り値

指定された名前とタイプを持つフォームフィールドが見つかった場合はそれを返し、見つからない場合はそのタイプのデフォルト値を返します。

### 参照

* interface [IFormField](../../iformfield)
* class [FormFieldCollection](../../formfieldcollection)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
