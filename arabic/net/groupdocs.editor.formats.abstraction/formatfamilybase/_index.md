---
title: "FormatFamilyBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل الفئة الأساسية لعائلات التنسيق التي توفر وظائف مشتركة لنسخ عائلات التنسيق."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

يمثل الفئة الأساسية لعائلات الصيغ، موفرًا وظائف مشتركة لحالات عائلة الصيغة.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | يحصل على المعرف الفريد لعائلة التنسيق. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | يحصل على اسم عائلة التنسيق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | يحدد ما إذا كانت هذه النسخة مساوية للنسخة المحددة من [`FormatFamilyBase`](../formatfamilybase). |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | يحدد ما إذا كانت هذه النسخة مساوية للنسخة المحددة من [`FormatFamilyBase`](../formatfamilybase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | يسترجع نسخة من النوع المحدد *T* التي لها الاسم المحدد. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | يسترجع نسخة من النوع المحدد *T* التي لها المعرف المحدد. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | يسترجع جميع النسخ من النوع المحدد *T* التي تُشتق من [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | يحدد ما إذا كان نسختا [`FormatFamilyBase`](../formatfamilybase) متساويتين. (عاملان) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | يحوّل سلسلة تمثل اسم عائلة تنسيق إلى كائن [`FormatFamilyBase`](../formatfamilybase). (عاملان) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | يحوّل نسخة من [`FormatFamilyBase`](../formatfamilybase) إلى عدد صحيح بشكل ضمني. (عاملان) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | يحدد ما إذا كان نسختا [`FormatFamilyBase`](../formatfamilybase) غير متساويتين. (عاملان) |

### ملاحظات

هذه الفئة مجردة ويجب أن يرثها صف مشتق يحدد تفاصيل عائلة التنسيق الفعلية.

### انظر أيضًا

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
