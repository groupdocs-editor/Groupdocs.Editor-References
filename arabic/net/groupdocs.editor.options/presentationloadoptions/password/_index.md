---
title: "كلمة المرور"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند Presentation إذا كان مشفرًا. اضبطها على NULL أو سلسلة فارغة لإزالة كلمة المرور."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لفتح مستند Presentation إذا كان مشفّراً. اضبطها على NULL أو سلسلة فارغة لإزالة كلمة المرور.

```csharp
public string Password { get; set; }
```

### ملاحظات

بشكل افتراضي، هذه الخاصية لها قيمة NULL — كلمة المرور غير مضبوطة. إذا كان مستند Presentation المدخل محميًا بكلمة مرور، تكون كلمة المرور إلزامية وسيتم رمي استثناء إذا لم يتم تحديد كلمة المرور أو كانت غير صالحة. إذا لم يكن مستند Presentation المدخل محميًا بكلمة مرور، لكن تم ضبط كلمة المرور، فسيتم تجاهلها.

### انظر أيضًا

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
