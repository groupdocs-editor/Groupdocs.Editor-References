---
title: "FixInvalidFormFieldNames"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された更新を適用するか、または自動的に一意の名前を生成することで、ドキュメント内の無効なフォームフィールド名を修正します。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

指定された更新を適用するか、または自動的に一意の名前を生成することで、ドキュメント内の無効なフォームフィールド名を修正します。

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | 無効なフォームフィールド名の更新のコレクションです。各更新はフォームフィールドの元の名前と対応する新しい名前を含みます。空の場合、無効なフォームフィールド名は一意性を確保するために自動的に名前が変更されます。 |

### 備考

`FixInvalidFormFieldNames` メソッドは、ドキュメント内のフォームフィールドの命名衝突や不整合を、*updateInvalidFormFieldNames* コレクションで指定された更新を適用するか、コレクションが空の場合は自動的に一意な名前を生成することで解決します。このメソッドは、特定のフォームフィールド名が無効であったり他の要素と衝突している場合に、適切な機能を確保するために修正が必要なときに有用です。 ; ;

### 参照

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
