---
title: WorksheetIndex
second_title: GroupDocs.Editor لمرجع .NET API
description: يسمح بتحديد فهرس ورقة العمل علامة التبويب على أساس 0  والذي يجب تحويله إلى HTML انظر الملاحظات .
type: docs
weight: 30
url: /ar/net/groupdocs.editor.options/spreadsheeteditoptions/worksheetindex/
---
## SpreadsheetEditOptions.WorksheetIndex property

يسمح بتحديد فهرس ورقة العمل (علامة التبويب) على أساس 0 ، والذي يجب تحويله إلى HTML (انظر الملاحظات) .

```csharp
public int WorksheetIndex { get; set; }
```

### ملاحظات

تدعم معظم مستندات جداول البيانات مفهوم علامات التبويب ، أي يمكن أن تكون متعددة الجداول. من ناحية أخرى ، لا يدعم تنسيق HTML مثل هذه البنية. بسبب هذا GroupDocs.Editor يمكن التحويل إلى HTML فقط علامة تبويب واحدة محددة من مستند الإدخال ، ويسمح هذا الخيار بتحديده . فهرس Tab يستند إلى 0 ، القيم السلبية محظورة. إذا تجاوز الفهرس المحدد عدد جميع علامات التبويب ، فسيتم طرح الاستثناء . إذا كان مستند جدول البيانات يحتوي على علامة تبويب واحدة فقط ، فسيتم تجاهل هذا الخيار. القيمة الافتراضية هي 0 (علامة التبويب الأولى) .

### أنظر أيضا

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* مساحة الاسم [GroupDocs.Editor.Options](../../spreadsheeteditoptions)
* المجسم [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
