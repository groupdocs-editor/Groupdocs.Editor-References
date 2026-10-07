---
title: "PageRange"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يُغلف نطاق صفحة واحد يمكن أن يكون له حدود مفتوحة أو مغلقة. بشكل افتراضي يكون مفتوحًا بالكامل ويشمل جميع الصفحات الموجودة. يبدأ ترقيم الصفحات من 1 وليس من 0."
type: docs
weight: 1030
url: /ar/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

يحتوي على نطاق صفحة واحد، يمكن أن يكون له حدود مفتوحة أو مغلقة. بشكل افتراضي يكون "مفتوحًا بالكامل" - يشمل جميع الصفحات الموجودة. يبدأ ترقيم الصفحات من 1، وليس من 0.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | عدد الصفحات ضمن النطاق. إذا كان 0 - يمتد نطاق الصفحة حتى نهاية المستند بغض النظر عن عدد الصفحات التي يتكون منها |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | رقم الصفحة النهائية الحصري، الذي يستمر حتى هذا النطاق ويتوقف عنده حصريًا. إذا كان 0 - يمتد نطاق الصفحة حتى نهاية المستند |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | يشير إلى ما إذا كان هذا المثيل يمثل نطاق صفحة "مفتوح بالكامل" افتراضيًا أي يمثل جميع صفحات المستند (true) أو لا (false) |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | رقم الصفحة الابتدائية الشاملة، التي يبدأ منها نطاق الصفحة. إذا كان 1 - يبدأ نطاق الصفحة من الصفحة الأولى للمستند |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | ينشئ نطاق صفحة يبدأ من الصفحة الأولى ويحتوي على عدد محدد من الصفحات |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويستمر حتى نهاية المستند |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد (شاملاً) ويستمر حتى رقم الصفحة المحدد (حصريًا) |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | ينشئ نطاق صفحة يبدأ من رقم الصفحة المحدد ويحتوي على عدد محدد من الصفحات، أو عدد صفحات غير محدود (حتى النهاية) |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | يكشف ما إذا كان هذا المثيل من PageRange يساوي المحدد |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | يمثل جميع الصفحات الموجودة في المستند. القيمة الافتراضية. |

### ملاحظات

هيكل غير قابل للتغيير، يضم نطاق صفحات لا يرتبط بأي مستند محدد، ويمكنه تمثيل نطاق صفحات لأي مستند.

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
