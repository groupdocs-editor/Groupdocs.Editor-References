---
title: "GetInvalidFormFieldNames"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسترجع مجموعة من أسماء حقول النموذج غير الصالحة من المستند."
type: docs
weight: 30
url: /ar/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

يسترجع مجموعة من أسماء حقول النموذج غير الصالحة من المستند.

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### قيمة الإرجاع

مجموعة قابلة للتعداد من السلاسل تمثل أسماء حقول النموذج غير الصالحة الموجودة في المستند.

### ملاحظات

تقوم طريقة `GetInvalidFormFieldNames` بمسح محتوى المستند لتحديد حقول النموذج ذات الأسماء غير الصالحة. تُعيد مجموعة من السلاسل التي تحتوي على أسماء هذه الحقول غير الصالحة. يُعتبر حقل النموذج غير صالح إذا كان يكرر معرفًا فريدًا مع حقول نموذج أخرى ولا يمتلك اسم إشارة مرجعية فريد مرتبط به. تُستخدم أسماء الإشارات المرجعية هذه كمعرفات لكل حقل نموذج. تحافظ المجموعة المعادة على ترتيب أسماء حقول النموذج كما تظهر في المستند. تُعد هذه الطريقة مفيدة لاكتشاف وتحليل مشكلات التسمية داخل حقول النموذج، والتي قد تحتاج إلى معالجة باستخدام طريقة [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames).

### انظر أيضًا

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
