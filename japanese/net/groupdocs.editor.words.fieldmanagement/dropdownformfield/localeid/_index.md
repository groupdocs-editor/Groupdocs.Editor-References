---
title: "LocaleId"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォームフィールドに関連付けられた文化または地域設定を表す locale ID を取得または設定します"
type: docs
weight: 30
url: /ja/net/groupdocs.editor.words.fieldmanagement/dropdownformfield/localeid/
---
## DropDownFormField.LocaleId property

フォームフィールドのロケール ID を取得または設定します。これは、フォームフィールドに関連付けられた文化または地域設定を表します。

```csharp
public int LocaleId { get; set; }
```

### 備考

LocaleId プロパティは、特定の文化または地域に対応するロケール識別子 (LCID) を指定します

### 例

以下の例は LocaleId プロパティの設定方法を示しています:

```csharp
Set the LocaleId to represent the English (United States) culture
dropDownField.LocaleId = new CultureInfo("en-US").LCID;
```

### 参照

* class [DropDownFormField](../../dropdownformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
