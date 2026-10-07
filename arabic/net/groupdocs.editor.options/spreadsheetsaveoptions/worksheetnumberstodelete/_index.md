---
title: "WorksheetNumbersToDelete"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد مصفوفة تحتوي على أرقام الأوراق (بدءًا من 1) التي يجب حذفها من جدول البيانات أثناء حفظه في حال تم إدراج ورقة العمل المعدلة في جدول بيانات موجود."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete/
---
## SpreadsheetSaveOptions.WorksheetNumbersToDelete property

يسمح بتحديد مصفوفة تحتوي على أرقام ورقات العمل بدءًا من 1 التي يجب حذفها من جدول البيانات أثناء حفظه، في حال تم إدراج ورقة العمل المعدلة في جدول بيانات موجود

```csharp
public int[] WorksheetNumbersToDelete { get; set; }
```

### ملاحظات

عند حفظ ورقة العمل المعدلة ليس كجدول بيانات جديد يحتوي على ورقة عمل واحدة (السلوك الافتراضي)، بل يتم حفظها في جدول بيانات موجود (باستخدام خاصية [`WorksheetNumber`](../worksheetnumber))، يمكن أيضًا حذف بعض أوراق العمل المحددة من هذا الجدول عن طريق تحديد أرقامها في هذه المصفوفة.

بشكل افتراضي تكون هذه المصفوفة `null` — لن يتم حذف أي أوراق عمل. ومع ذلك، عندما تكون المصفوفة غير null وغير فارغة، وتحتوي على رقم ورقة عمل صالح واحد على الأقل، بعد إنشاء مستند جدول البيانات الناتج بمحتوى ورقة العمل المعدلة، سيتم حذف أوراق العمل ذات الأرقام المحددة من الجدول مباشرة قبل كتابة محتواها إلى تدفق الإخراج أو الملف.

أرقام أوراق العمل في هذه المصفوفة تبدأ من 1، ليست من 0؛ الأرقام غير الصالحة (أقل من 1 أو أكبر من إجمالي عدد أوراق العمل) سيتم تجاهلها.

### انظر أيضًا

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
