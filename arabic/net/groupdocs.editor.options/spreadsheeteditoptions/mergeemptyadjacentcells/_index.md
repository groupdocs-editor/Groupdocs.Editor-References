---
title: "MergeEmptyAdjacentCells"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "عند التفعيل، سيتم تمثيل الخلايا الأفقية الفارغة المتجاورة من مستند Spreadsheet المدخل في مستند HTML القابل للتحرير كخلية واحدة مدمجة مع خاصية colspan المقابلة. بشكل افتراضي يكون معطلاً false."
type: docs
weight: 40
url: /ar/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

عند التفعيل، سيتم تمثيل الخلايا الأفقية المتجاورة الفارغة من مستند Spreadsheet المدخل في مستند HTML القابل للتحرير كخلية واحدة مدمجة مع سمة `colspan` المقابلة. بشكل افتراضي معطل (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### ملاحظات

بشكل افتراضي يقوم GroupDocs.Editor بتحويل جدول من مستند Spreadsheet المدخل إلى مستند HTML الناتج مع الحفاظ على كل خلية. ومع ذلك، قد تكون مستندات Spreadsheet متفرقة — قد تحتوي على كميات هائلة من \"المناطق الفارغة\" حيث تكون العديد من الخلايا فارغة. عند تمكين هذا الخيار، يتم دمج هذه الخلايا الفارغة في خلية واحدة باستخدام خاصية `colspan` في عنصر `TD`، وبالتالي يمكن تقليل حجم العلامات HTML المنتجة بشكل كبير.

### انظر أيضًا

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
