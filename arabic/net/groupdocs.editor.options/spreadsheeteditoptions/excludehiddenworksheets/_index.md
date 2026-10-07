---
title: "ExcludeHiddenWorksheets"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح باستبعاد الأوراق المخفية في مستند Spreadsheet المدخل بحيث يتم تجاهلها تمامًا. القيمة الافتراضية هي false، وتظل الأوراق المخفية متاحة وتُعالج كالعادية."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.options/spreadsheeteditoptions/excludehiddenworksheets/
---
## SpreadsheetEditOptions.ExcludeHiddenWorksheets property

يسمح باستبعاد أوراق العمل المخفية في مستند Spreadsheet المدخل، بحيث يتم تجاهلها تمامًا. القيمة الافتراضية false - أوراق العمل المخفية متاحة وتُعالج كالعادية.

```csharp
public bool ExcludeHiddenWorksheets { get; set; }
```

### ملاحظات

تدعم عدة صيغ Spreadsheet الثنائية (مثل XLSX) مفهوم الأوراق المخفية (الألسنة). إذا كان المستند من هذا النوع يحتوي على أكثر من ورقة واحدة، قد يحتوي على أوراق مخفية إضافية. بشكل افتراضي تكون هذه الأوراق المخفية متاحة للمعالجة، ولكن باستخدام هذا الخيار يمكن تجاهلها كما لو أن هذه الأوراق المخفية غير موجودة. عند تمكين هذا الخيار، لا يمكنك تحديد ورقة مخفية باستخدام الخاصية '[`WorksheetIndex`](../worksheetindex)'.

### انظر أيضًا

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
