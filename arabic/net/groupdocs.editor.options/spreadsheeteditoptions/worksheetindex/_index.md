---
title: "WorksheetIndex"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد الفهرس الصفري للتاب الخاص بورقة العمل في مستند Spreadsheet المدخل الذي يجب تحويله إلى HTML (انظر الملاحظات)."
type: docs
weight: 50
url: /ar/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

يسمح بتحديد الفهرس القائم على الصفر لورقة العمل (التبويب) في مستند Spreadsheet الإدخالي، والذي يجب تحويله إلى HTML (انظر الملاحظات).

```csharp
public int WorksheetIndex { get; set; }
```

### ملاحظات

تدعم معظم مستندات Spreadsheet مفهوم الألسنة، أي يمكن أن تكون متعددة الألسنة. من ناحية أخرى، لا يدعم تنسيق HTML هذا الهيكل. لذلك يمكن لـ GroupDocs.Editor تحويل إلى HTML تابًا واحدًا محددًا فقط من المستند المدخل، ويسمح هذا الخيار بتحديده. الفهرس هو صفر-مبني، القيم السلبية غير مسموح بها. إذا تجاوز الفهرس المحدد عدد جميع الألسنة، سيتم رمي استثناء. إذا كان مستند Spreadsheet يحتوي على تاب واحد فقط، سيتجاهل هذا الخيار. القيمة الافتراضية هي 0 (التاب الأول).

### انظر أيضًا

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
