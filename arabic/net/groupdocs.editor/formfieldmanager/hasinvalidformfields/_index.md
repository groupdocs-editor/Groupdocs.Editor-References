---
title: "HasInvalidFormFields"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يتحقق مما إذا كان المستند يحتوي على أي حقول نموذج غير صالحة."
type: docs
weight: 40
url: /ar/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

يتحقق مما إذا كان المستند يحتوي على أي حقول نموذج غير صالحة.

```csharp
public bool HasInvalidFormFields()
```

### قيمة الإرجاع

`true` إذا كان المستند يحتوي على حقل نموذج غير صالح واحد أو أكثر؛ وإلا، `false`.

### ملاحظات

تقوم طريقة `HasInvalidFormFields` بمسح محتوى المستند لتحديد ما إذا كان يحتوي على أي حقول نموذج بأسماء غير صالحة. يُعتبر حقل النموذج غير صالح إذا كان يكرر معرفًا فريدًا مع حقول نموذج أخرى ولا يمتلك اسم إشارة مرجعية فريد مرتبط به. تُستخدم أسماء الإشارات المرجعية هذه كمعرفات لكل حقل نموذج. تُعد هذه الطريقة مفيدة للتحقق بسرعة مما إذا كان المستند يحتاج إلى فحص إضافي وتصحيح محتمل لأسماء حقول النموذج. ; ; ;

### انظر أيضًا

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
