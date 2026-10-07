---
title: "GetFormField"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحصل على حقل النموذج بالاسم والنوع المحددين."
type: docs
weight: 40
url: /ar/net/groupdocs.editor.words.fieldmanagement/formfieldcollection/getformfield/
---
## FormFieldCollection.GetFormField&lt;T&gt; method

يحصل على حقل النموذج بالاسم والنوع المحددين.

```csharp
public T GetFormField<T>(string name)
    where T : IFormField
```

| معامل | الوصف |
| --- | --- |
| T | نوع حقل النموذج. |
| name | اسم حقل النموذج. |

### قيمة الإرجاع

حقل النموذج بالاسم والنوع المحددين، إذا تم العثور عليه؛ وإلا، القيمة الافتراضية للنوع.

### انظر أيضًا

* interface [IFormField](../../iformfield)
* class [FormFieldCollection](../../formfieldcollection)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
