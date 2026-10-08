---
title: "FormFieldManager"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "レガシーフォームフィールドを使用してフォームを管理します。レガシーフォームフィールドは、以前のバージョンの Word 処理で利用可能だったフィールドタイプです。レガシーツール アイコンをクリックすると表示されるレガシーフォーム グループには、ドキュメントに挿入できるテキスト、チェックボックス、ドロップダウン、日付などの3種類のフォームフィールドが含まれます。詳細は FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype を参照してください。これらのフォームフィールドは、フォームのユーザーが適切と考えるタイプの情報を選択または入力できるようにします。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

レガシーフォームフィールドを使用してフォームを管理します。レガシーフォームフィールドは、以前のバージョンの Word 処理で利用可能だったフィールドタイプです。レガシーツール アイコンをクリックすると表示されるレガシーフォーム グループには、ドキュメントに挿入できるテキスト、チェックボックス、ドロップダウン、日付などの3種類のフォームフィールドが含まれます。詳細は [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype) を参照してください。これらのフォームフィールドは、フォームのユーザーが適切と考えるタイプの情報を選択または入力できるようにします。

```csharp
public sealed class FormFieldManager
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | ドキュメント内のフォームフィールドのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | 指定された更新を適用するか、または自動的に一意の名前を生成することで、ドキュメント内の無効なフォームフィールド名を修正します。 |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | ドキュメントから無効なフォームフィールド名のコレクションを取得します。 |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | ドキュメントに無効なフォームフィールドが含まれているかどうかを確認します。 |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | ドキュメントから複数のフォームフィールドを削除します。 |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | ドキュメントから特定のフォームフィールドを削除します。 |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | 提供されたフォームフィールドのコレクションに基づいて、ドキュメント内のフォームフィールドを更新します。 |

### 備考

[`FormFieldManager`](../formfieldmanager) クラスは、ドキュメント内のフォームフィールドを処理する機能を提供します。ユーザーはフォームフィールドを取得、更新、修正、無効性をチェックし、削除することができます。

### 参照

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
