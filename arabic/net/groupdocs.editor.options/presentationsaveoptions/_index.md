---
title: "PresentationSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Presentation المتوافقة مع PowerPoint."
type: docs
weight: 1100
url: /ar/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات العروض التقديمية (متوافقة مع PowerPoint)

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | هذا المُنشئ بدون معلمات ينشئ مثيلاً جديدًا من PresentationSaveOptions بصيغة إخراج PPTX (يمكن تعديله لاحقًا عبر خاصية [`OutputFormat`](./outputformat)). |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | ينشئ مثيلاً جديدًا من PresentationSaveOptions بصيغة إخراج Presentation الإلزامية المحددة، بينما تكون جميع المعلمات الأخرى افتراضية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | علامة منطقية تحدد ما إذا كانت الشريحة المعدلة يجب أن تستبدل الشريحة الموجودة في العرض التقديمي الأصلي في الموضع المحدد بواسطة خاصية [`SlideNumber`](./slidenumber)، أم يجب إدراجها بين الشريحة الموجودة والسابقة دون استبدال محتواها. القيمة الافتراضية هي `false` — سيتم استبدال الشريحة الموجودة. يتم تجاهل هذه الخاصية إذا تم ضبط قيمة خاصية [`SlideNumber`](./slidenumber) على `'0'`. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | يسمح بتحديد صيغة Presentation التي ستُستخدم لحفظ المستند. |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لتشفير مستند Presentation الناتج. القيمة الافتراضية هي NULL - لن يتم تعيين كلمة مرور. اضبطها على NULL أو سلسلة فارغة لإزالة كلمة المرور إذا كانت مُحددة مسبقًا. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | يسمح بإدراج الشريحة المعدلة في عرض تقديمي موجود بدلاً من إنشاء عرض تقديمي جديد بشريحة واحدة (السلوك الافتراضي). رقم الشريحة هو رقم يبدأ من 1 يحدد الشريحة في العرض التقديمي المحمَّل في فئة Editor. إذا كان 0 (القيمة الافتراضية)، سيتم إنشاء عرض تقديمي جديد بشريحة واحدة معدلة. إذا كان أكبر أو أصغر من الصفر، وكان هناك عرض تقديمي صالح محمَّل في فئة Editor، فسيتم إدراج الشريحة المعدلة، المخزنة داخل مثيل EditableDocument المدخل، في هذا العرض التقديمي. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | يسمح بتحديد مصفوفة بأرقام الشرائح (بدءًا من 1) التي يجب حذفها من العرض التقديمي أثناء حفظه، في حال تم إدراج الشريحة المعدلة في عرض تقديمي موجود. |

### ملاحظات

يجب تمرير مثيل هذه الفئة إلى طريقة  لحفظ العرض التقديمي المعدل في المستند النهائي بصيغة Presentation محددة. جميع المعلمات الأخرى اختيارية ويمكن إهمالها، وبشكل افتراضي تكون صيغة العرض التقديمي المحفوظ هي PPTX، ولكن يمكن تغييرها عبر المُنشئ أو الخاصية.

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
