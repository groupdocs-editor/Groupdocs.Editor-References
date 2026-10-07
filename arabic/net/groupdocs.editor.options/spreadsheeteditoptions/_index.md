---
title: "SpreadsheetEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بجميع صيغ الجداول الإلكترونية المتوافقة مع Excel المدعومة"
type: docs
weight: 1110
url: /ar/net/groupdocs.editor.options/spreadsheeteditoptions/
---
## SpreadsheetEditOptions class

يسمح بتحديد خيارات مخصصة لتحرير مستندات جميع صيغ جداول البيانات (متوافقة مع Excel) المدعومة

```csharp
public class SpreadsheetEditOptions : IEditOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SpreadsheetEditOptions](spreadsheeteditoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ExcludeHiddenWorksheets](../../groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets) { get; set; } | يسمح باستبعاد أوراق العمل المخفية في مستند Spreadsheet المدخل، بحيث يتم تجاهلها تمامًا. القيمة الافتراضية false - أوراق العمل المخفية متاحة وتُعالج كالعادية. |
| [ExportBogusRowData](../../groupdocs.editor.options/spreadsheeteditoptions/exportbogusrowdata) { get; set; } | عند التفعيل، يحتوي جدول HTML في المستند HTML المُنتج على صف سفلي مخفي فارغ بارتفاع صفر وخلايا فارغة، حيث يتم تحديد العرض فقط. يحتوي هذا الصف على قيم عرض دقيقة لكل عمود ويُحسّن التحويل العكسي من HTML إلى Spreadsheet. بشكل افتراضي مُفعَّل (`true`). |
| [MergeEmptyAdjacentCells](../../groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells) { get; set; } | عند التفعيل، سيتم تمثيل الخلايا الأفقية المتجاورة الفارغة من مستند Spreadsheet المدخل في مستند HTML القابل للتحرير كخلية واحدة مدمجة مع سمة `colspan` المقابلة. بشكل افتراضي معطل (`false`). |
| [WorksheetIndex](../../groupdocs.editor.options/spreadsheeteditoptions/worksheetindex) { get; set; } | يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في مستند Spreadsheet الإدخالي، والذي يجب تحويله إلى HTML (انظر الملاحظات). |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
