---
title: "FormFieldManager"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "إدارة نموذج باستخدام حقول النماذج القديمة. حقول النماذج القديمة هي أنواع الحقول التي كانت متاحة في إصدارات سابقة من معالجة Word. مجموعة النماذج القديمة التي تظهر بعد النقر على أيقونة أدوات النماذج القديمة تشمل ثلاثة أنواع من حقول النماذج يمكنك إدراجها في مستند نص، مربع اختيار، قائمة منسدلة، تاريخ، إلخ. راجع المزيد FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype. كل من هذه الحقول يسمح لمستخدم النموذج باختيار أو إدخال معلومات من النوع الذي تعتقد أنه مناسب."
type: docs
weight: 40
url: /ar/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

إدارة نموذج باستخدام حقول النماذج القديمة. حقول النماذج القديمة هي أنواع الحقول التي كانت متاحة في إصدارات سابقة من معالجة Word. مجموعة النماذج القديمة (التي تظهر بعد النقر على أيقونة أدوات النماذج القديمة) تشمل ثلاثة أنواع من حقول النماذج يمكنك إدراجها في مستند: نص، مربع اختيار، قائمة منسدلة، تاريخ، إلخ، راجع المزيد [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype). كل من هذه الحقول يسمح لمستخدم النموذج باختيار أو إدخال معلومات من النوع الذي تعتقد أنه مناسب.

```csharp
public sealed class FormFieldManager
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | يحصل على مجموعة حقول النموذج في المستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | يصلح أسماء حقول النموذج غير الصالحة في المستند عن طريق تطبيق التحديثات المحددة أو إنشاء أسماء فريدة تلقائيًا. |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | يسترجع مجموعة من أسماء حقول النموذج غير الصالحة من المستند. |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | يتحقق مما إذا كان المستند يحتوي على أي حقول نموذج غير صالحة. |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | يزيل عدة حقول نموذج من المستند. |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | يزيل حقل نموذج محدد من المستند. |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | يقوم بتحديث حقول النموذج في المستند بناءً على مجموعة الحقول المقدمة. |

### ملاحظات

تقدم فئة [`FormFieldManager`](../formfieldmanager) وظيفة لمعالجة حقول النموذج في المستند. تسمح للمستخدمين بالحصول على حقول النموذج، وتحديثها، وإصلاحها، والتحقق من عدم صلاحيتها، وإزالتها من المستند.

### انظر أيضًا

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
