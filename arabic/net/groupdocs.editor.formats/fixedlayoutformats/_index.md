---
title: "FixedLayoutFormats"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل صيغ مستندات fixedlayout fixedpage مثل PDF مع استبعاد صيغ الصور النقطية."
type: docs
weight: 100
url: /ar/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

يمثل صيغ المستندات ذات التخطيط الثابت (صفحة ثابتة)، مثل PDF، مع استبعاد صيغ الصور النقطية.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | يحصل على امتداد الملف لتنسيق المستند. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | يحصل على عائلة التنسيق التي ينتمي إليها تنسيق المستند. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | يحصل على نوع MIME لتنسيق المستند. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | يحصل على جميع النسخ المتاحة من [`FixedLayoutFormats`](../fixedlayoutformats). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | يسترجع نسخة من [`FixedLayoutFormats`](../fixedlayoutformats) تتطابق مع امتداد الملف المحدد. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | يحدد ما إذا كان هذا المثيل مساويًا للمثيل المحدد [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | يقوم بتحويل سلسلة امتداد الملف صراحةً إلى نسخة من [`FixedLayoutFormats`](../fixedlayoutformats). |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | تنسيق المستندات القابل للنقل (PDF)، الذي قدمته شركة Adobe، يوفر تمثيلاً موحدًا للمستندات بغض النظر عن البرامج أو الأجهزة أو أنظمة التشغيل. لمزيد من التفاصيل، راجع: [تنسيق ملف PDF](https://docs.fileformat.com/pdf/). |

### ملاحظات

تحدد صيغ التخطيط الثابت بدقة موضع وعرض المحتوى على كل صفحة. تُستخدم عادةً في تطبيقات عرض المستندات أو النشر أو التحرير مثل Adobe Acrobat وAdobe InDesign. تقوم هذه الصيغ داخليًا بتعريف تخطيطات الصفحات وتحديد مواضع المحتوى باستخدام الرسومات المتجهة وتعليمات النص.

### انظر أيضًا

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
