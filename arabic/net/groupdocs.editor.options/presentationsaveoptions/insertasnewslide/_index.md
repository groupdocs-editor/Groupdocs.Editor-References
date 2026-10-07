---
title: "InsertAsNewSlide"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "علامة منطقية تحدد ما إذا كان يجب استبدال الشريحة المعدلة بالشريحة الموجودة في العرض الأصلي في الموضع المحدد بواسطة الخاصية SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber أو يجب إدراجها بين الشريحة الموجودة والسابقة دون استبدال محتواها. بشكل افتراضي تكون false وسيتم استبدال الشريحة الموجودة. يتم تجاهل هذه الخاصية إذا تم ضبط قيمة الخاصية SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber إلى 0."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

علامة منطقية تحدد ما إذا كان يجب استبدال الشريحة المعدلة بالشريحة الموجودة في العرض الأصلي في الموضع المحدد بواسطة الخاصية [`SlideNumber`](../slidenumber)، أو يجب إدراجها بين الشريحة الموجودة والسابقة دون استبدال محتواها. بشكل افتراضي تكون `false` — سيتم استبدال الشريحة الموجودة. يتم تجاهل هذه الخاصية إذا تم ضبط قيمة الخاصية [`SlideNumber`](../slidenumber) إلى `'0'`.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### ملاحظات

بشكل افتراضي يتم استبدال الشريحة. هذا يعني أنه إذا كان العرض يحتوي على 5 شرائح، وكان [`SlideNumber`](../slidenumber)=4، فإن الشريحة الرابعة ستُستبدل بالشريحة المعدلة الجديدة، بينما سيظل العدد الإجمالي للشرائح في العرض (5) دون تغيير. ومع ذلك، إذا تم ضبط قيمة هذه الخاصية إلى true، سيتم إدراج الشريحة المعدلة الجديدة كشريحة رابعة، وستُدفع جميع الشرائح اللاحقة إلى النهاية: الشريحة "old" الرابعة تصبح الخامسة، والخامسة تصبح السادسة، وسيتم زيادة العدد الإجمالي للشرائح في العرض بمقدار واحد ليصبح 6.

### انظر أيضًا

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
