---
title: "SlideNumbersToDelete"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد مصفوفة تحتوي على أرقام الشرائح التي تبدأ من 1 والتي يجب حذفها من العرض التقديمي أثناء حفظه في حال تم إدراج الشريحة المعدلة في عرض تقديمي موجود."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

يسمح بتحديد مصفوفة بأرقام الشرائح (بدءًا من 1) التي يجب حذفها من العرض التقديمي أثناء حفظه، في حال تم إدراج الشريحة المعدلة في عرض تقديمي موجود.

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### ملاحظات

عند حفظ الشريحة المعدلة ليس كعرض تقديمي جديد من شريحة واحدة (السلوك الافتراضي)، بل يتم حفظها في عرض تقديمي موجود (باستخدام خاصية [`SlideNumber`](../slidenumber))، يمكن أيضًا حذف بعض الشرائح المحددة من هذا العرض التقديمي عن طريق تحديد أرقامها في هذه المصفوفة.

بشكل افتراضي تكون هذه المصفوفة `null` — لن يتم حذف أي شرائح. ومع ذلك، عندما تكون هذه المصفوفة غير فارغة وغير `null`، وتحتوي على رقم شريحة صالح واحد على الأقل، بعد إنشاء مستند Presentation الناتج بمحتوى الشريحة المعدلة، سيتم حذف الشرائح ذات الأرقام المحددة من العرض التقديمي قبل كتابة محتواها إلى تدفق الإخراج أو الملف.

أرقام الشرائح في هذا المصفوفة تبدأ من 1، ليست من 0، الأرقام غير الصالحة (أقل من 1 أو أكبر من العدد الإجمالي للشرائح) سيتم تجاهلها.

### انظر أيضًا

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
