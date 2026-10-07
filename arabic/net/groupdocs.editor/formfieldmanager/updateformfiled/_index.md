---
title: "UpdateFormFiled"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحديث حقول النموذج في المستند بناءً على مجموعة الحقول المقدمة."
type: docs
weight: 70
url: /ar/net/groupdocs.editor/formfieldmanager/updateformfiled/
---
## FormFieldManager.UpdateFormFiled method

يقوم بتحديث حقول النموذج في المستند بناءً على مجموعة الحقول المقدمة.

```csharp
public void UpdateFormFiled(FormFieldCollection formFieldCollection)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| formFieldCollection | FormFieldCollection | مجموعة حقول النموذج التي تحتوي على التحديثات لتطبيقها على المستند. |

### ملاحظات

تقوم طريقة `UpdateFormFiled` بتحديث حقول النموذج في المستند بناءً على *formFieldCollection* المقدمة. كل حقل نموذج في المجموعة يتطابق مع حقل نموذج في المستند، ويتم تطبيق التحديثات المحددة في المجموعة وفقًا لذلك. تُعد هذه الطريقة مفيدة لمزامنة بيانات حقول النموذج بين المستند ومصدر خارجي، مثل واجهة المستخدم أو قاعدة البيانات.

### انظر أيضًا

* class [FormFieldCollection](../../../groupdocs.editor.words.fieldmanagement/formfieldcollection)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
