---
title: "FixInvalidFormFieldNames"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يصلح أسماء حقول النموذج غير الصالحة في المستند عن طريق تطبيق التحديثات المحددة أو إنشاء أسماء فريدة تلقائيًا."
type: docs
weight: 20
url: /ar/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

يصلح أسماء حقول النموذج غير الصالحة في المستند عن طريق تطبيق التحديثات المحددة أو إنشاء أسماء فريدة تلقائيًا.

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | مجموعة من التحديثات لأسماء حقول النموذج غير الصالحة. يحتوي كل تحديث على الاسم الأصلي لحقل النموذج واسمه الجديد المقابل. إذا تُركت فارغة، سيتم إعادة تسمية أسماء حقول النموذج غير الصالحة تلقائيًا لضمان التفرد. |

### ملاحظات

تقوم طريقة `FixInvalidFormFieldNames` بحل تعارضات أو عدم اتساق في تسمية حقول النموذج داخل المستند عن طريق تطبيق التحديثات المحددة في مجموعة *updateInvalidFormFieldNames*، أو إنشاء أسماء فريدة تلقائيًا إذا كانت المجموعة فارغة. تُعد هذه الطريقة مفيدة عندما تكون بعض أسماء حقول النموذج غير صالحة أو متعارضة مع عناصر أخرى في المستند، وتحتاج إلى تصحيح لضمان الأداء السليم. ; ;

### انظر أيضًا

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
