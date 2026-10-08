---
title: "GetInvalidFormFieldNames"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ドキュメントから無効なフォームフィールド名のコレクションを取得します。"
type: docs
weight: 30
url: /ja/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

ドキュメントから無効なフォームフィールド名のコレクションを取得します。

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### 戻り値

ドキュメント内で見つかった無効なフォーム フィールドの名前を表す文字列の列挙可能なコレクションです。

### 備考

`GetInvalidFormFieldNames` メソッドは、ドキュメントの内容をスキャンして、無効な名前を持つフォーム フィールドを特定します。無効なフォーム フィールドの名前を含む文字列のコレクションを返します。フォーム フィールドは、他のフォーム フィールドと一意の識別子が重複し、かつそれに関連付けられた一意のブックマーク名がない場合、無効とみなされます。これらのブックマーク名は各フォーム フィールドの識別子として機能します。返されたコレクションは、ドキュメント内に現れる順序でフォーム フィールド名を保持します。このメソッドは、フォーム フィールド内の命名問題を検出・分析するのに役立ち、必要に応じて [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames) メソッドで対処できます。

### 参照

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
