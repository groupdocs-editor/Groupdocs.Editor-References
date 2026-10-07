---
title: "WorksheetProtection"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يضم خيارات حماية ورقة العمل التي تسمح بحماية ورقة العمل في مستند Spreadsheet الناتج من تعديل من النوع المحدد باستخدام كلمة مرور محددة."
type: docs
weight: 1250
url: /ar/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

يحتوي على خيارات حماية ورقة العمل، التي تسمح بحماية ورقة العمل في مستند Spreadsheet الناتج من تعديل من النوع المحدد باستخدام كلمة مرور محددة.

```csharp
public sealed class WorksheetProtection
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | ينشئ مثيلاً جديدًا باستخدام المعلمات الافتراضية. إذا لم يتم تعديلها وتم تمريرها إلى SpreadsheetSaveOptions، فلن يتم تطبيق حماية ورقة العمل. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | ينشئ مثيلاً جديدًا بنوع حماية ورقة العمل المحدد وكلمة المرور. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | كلمة المرور المستخدمة لحماية ورقة العمل. إذا كانت NULL أو سلسلة فارغة، لن يتم تطبيق الحماية. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | يسمح بتحديد نوع حماية ورقة العمل. القيمة الافتراضية هي 'None' - لا يتم تطبيق الحماية. |

### ملاحظات

تسمح معظم صيغ Spreadsheet مثل XLSX بحماية ورقة العمل من التحرير باستخدام كلمة مرور. هذه الفئة تسمح بتمكين هذه الحماية وتحديد خياراتها.

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
