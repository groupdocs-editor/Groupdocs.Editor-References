---
title: "InsertAsNewWorksheet"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "علامة منطقية تحدد ما إذا كان يجب استبدال ورقة العمل المعدلة للورقة الموجودة في المصنف الأصلي في الموضع المحدد بواسطة خاصية WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber أو يجب حقنها بين الورقة الموجودة والسابقة دون استبدال محتواها. بشكل افتراضي تكون false وسيتم استبدال الورقة الموجودة. يتم تجاهل هذه الخاصية إذا كانت قيمة خاصية WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber مضبوطة على 0."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

علامة منطقية، تحدد ما إذا كان يجب استبدال ورقة العمل المعدلة للورقة الموجودة في المصنف الأصلي في الموضع المحدد بواسطة خاصية [`WorksheetNumber`](../worksheetnumber)، أو يجب حقنها بين الورقة الموجودة والسابقة دون استبدال محتواها. بشكل افتراضي تكون false — سيتم استبدال الورقة الموجودة. يتم تجاهل هذه الخاصية إذا كانت قيمة خاصية [`WorksheetNumber`](../worksheetnumber) مضبوطة على '0'.

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### ملاحظات

بشكل افتراضي يتم استبدال ورقة العمل. هذا يعني أنه إذا كان المصنف يحتوي على 5 أوراق عمل، وكان [`WorksheetNumber`](../worksheetnumber)=4، فإن الورقة الرابعة سيتم استبدالها بورقة العمل المعدلة الجديدة، بينما سيظل عدد الأوراق في المصنف (5) دون تغيير. ومع ذلك، إذا تم ضبط قيمة هذه الخاصية على true، فسيتم حقن ورقة العمل المعدلة كورقة رابعة، وسيتم إزاحة جميع الأوراق اللاحقة إلى النهاية: تصبح الورقة "old" الرابعة هي الخامسة، وتصبح الخامسة هي السادسة، وسيتم زيادة عدد الأوراق في المصنف بمقدار واحد ليصبح 6.

### انظر أيضًا

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
