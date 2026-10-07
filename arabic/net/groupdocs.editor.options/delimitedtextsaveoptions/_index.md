---
title: "DelimitedTextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحتوي على خيارات لإنشاء وحفظ مستندات Spreadsheet النصية مثل CSV وTab وغيرها التي تستخدم فاصلًا delimiter"
type: docs
weight: 820
url: /ar/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

يحتوي على خيارات إنشاء وحفظ مستندات جدول البيانات النصية (CSV، المستندات المستندة إلى علامات الجدولة وغيرها)، التي تستخدم فاصلًا (delimiter)

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من DelimitedTextSaveOptions باستخدام الفاصل الافتراضي الفاصلة المنقوطة (;) (يمكن تعديلها لاحقًا عبر خاصية [`Separator`](./separator)). |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | ينشئ نسخة من فئة الخيارات للنص المفصول بفاصل (delimiter) إلزامي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | يسمح بتعيين ترميز لمستند Spreadsheet النصي. افتراضيًا (وإذا لم يُحدد) يكون UTF8. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | يحدد ما إذا كان يجب إخراج الفواصل للصف الفارغ. القيمة الافتراضية هي `false` مما يعني أن محتوى الصف الفارغ سيكون فارغًا. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | يسمح بتحديد فاصل نصي (delimiter) لمستندات Spreadsheet النصية. |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | يحدد ما إذا كان يجب قص الصفوف والأعمدة الفارغة الأولية كما يفعل MS Excel. |

### ملاحظات

https://en.wikipedia.org/wiki/Delimiter-separated_values

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
