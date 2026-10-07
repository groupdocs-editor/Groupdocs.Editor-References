---
title: "SpreadsheetSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Spreadsheet المتوافقة مع Excel."
type: docs
weight: 1130
url: /ar/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات جداول البيانات (متوافقة مع Excel)

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | هذا المنشئ بدون معلمات ينشئ نسخة جديدة من SpreadsheetSaveOptions بصيغة إخراج XLSX (يمكن تعديلها لاحقًا عبر الخاصية [`OutputFormat`](./outputformat)) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | ينشئ نسخة جديدة من SpreadsheetSaveOptions بصيغة إخراج Spreadsheet المحددة إجباريًا، بينما تكون جميع المعلمات الأخرى افتراضية |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | علامة منطقية تحدد ما إذا كان يجب استبدال ورقة العمل المعدلة بورقة العمل الموجودة في جدول البيانات الأصلي في الموضع المحدد بواسطة الخاصية [`WorksheetNumber`](./worksheetnumber)، أم يجب إدراجها بين ورقة العمل الموجودة والسابقة دون استبدال محتواها. يكون الافتراضي false — سيتم استبدال ورقة العمل الموجودة. يتم تجاهل هذه الخاصية إذا تم ضبط قيمة الخاصية [`WorksheetNumber`](./worksheetnumber) على '0'. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | يسمح بتحديد تنسيق Spreadsheet الذي سيُستخدم لحفظ المستند |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | يسمح بتحديد أو تعديل أو الحصول على أو إزالة كلمة مرور ستُستخدم لتشفير مستند Spreadsheet المُولد، إذا كان تنسيق المستند يدعم حماية كلمة المرور. حدد NULL أو سلسلة فارغة لإزالة (تنظيف) كلمة المرور. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | يسمح بإدراج ورقة العمل المعدلة في نسخة من جدول البيانات الموجود بدلاً من إنشاء جدول بيانات جديد بورقة عمل واحدة (السلوك الافتراضي). WorksheetNumber هو رقم ورقة العمل يبدأ من 1 في جدول البيانات المحمَّل في فئة Editor. إذا كان 0 (القيمة الافتراضية)، سيتم إنشاء جدول بيانات جديد بورقة عمل واحدة معدلة. إذا كان أكبر أو أصغر من الصفر، وكان هناك جدول بيانات صالح محمَّل في فئة Editor، فستُدرج ورقة العمل المعدلة، التي تمثلها نسخة EditableDocument المدخلة، في هذا الجدول. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | يسمح بتحديد مصفوفة تحتوي على أرقام ورقات العمل بدءًا من 1 التي يجب حذفها من جدول البيانات أثناء حفظه، في حال تم إدراج ورقة العمل المعدلة في جدول بيانات موجود |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | يسمح بتمكين حماية ورقة العمل للمستند Spreadsheet الناتج. يكون الافتراضي NULL - لا تُطبق الحماية. ليست جميع الصيغ تدعم حماية ورقة العمل. |

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
