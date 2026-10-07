---
title: "SlideNumber"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد أرقام الشرائح التي يجب فتحها للتحرير."
type: docs
weight: 30
url: /ar/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

يسمح بتحديد أرقام الشرائح التي يجب فتحها للتحرير

```csharp
public int SlideNumber { get; set; }
```

### ملاحظات

رقم الشريحة هو فهرس صفري الأساس لشريحة، يتيح تحديد واختيار شريحة معينة من العرض لتعديلها. إذا كان أقل من 0، تُختار الشريحة الأولى (نفس قيمة SlideNumber = 0). إذا كان أكبر من عدد جميع الشرائح في العرض، تُختار الشريحة الأخيرة. إذا كان العرض الإدخالي يحتوي على شريحة واحدة فقط، سيتجاهل هذا الخيار وتُحرَّر تلك الشريحة الوحيدة. إذا تم محاولة فتح شريحة مخفية للتحرير بينما خيار [`ShowHiddenSlides`](../showhiddenslides) مُعيَّن إلى 'false'، سيُرمي استثناء.

### انظر أيضًا

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
