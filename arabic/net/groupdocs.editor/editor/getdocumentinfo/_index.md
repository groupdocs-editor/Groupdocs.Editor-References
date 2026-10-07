---
title: "GetDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يرجع بيانات التعريف حول المستند الذي تم تحميله إلى هذه الحالة من Editor."
type: docs
weight: 70
url: /ar/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

يرجع البيانات الوصفية حول المستند الذي تم تحميله إلى نسخة 'Editor' هذه.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| password | String | يمكن للمستخدم تحديد كلمة مرور للمستند إذا كان هذا المستند مشفرًا باستخدام كلمة المرور. قد تكون NULL أو سلسلة فارغة، وهو ما يعادل عدم وجود كلمة مرور. بالنسبة لتنسيقات المستند التي لا تدعم ميزة حماية كلمة المرور، سيتم تجاهل هذا الوسيط. إذا كان المستند مشفرًا ولم يتم تحديد كلمة المرور في هذا الوسيط، ولكن تم تحديدها مسبقًا في خيارات التحميل أثناء إنشاء هذه الحالة من [`Editor`](../../editor)، فسيتم استخدامها. |

### قيمة الإرجاع

الوراثة الخاصة بالتنسيق لواجهة [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo)، التي تشير إلى التنسيق المكتشف مع بيانات تعريف خاصة بالتنسيق، أو NULL إذا لم يتم التعرف على المستند كدعم أو كان معطوبًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ObjectDisposedException | يتم إلقاؤه عندما تكون حالة Editor قد تم التخلص منها بالفعل عند استدعاء "GetDocumentInfo". |
| [PasswordRequiredException](../../passwordrequiredexception) | يتم إلقاؤه عندما يكون المستند المحمَّل محميًا بكلمة مرور، ولكن لم يتم تحديد كلمة المرور في الوسيط "*password*" ولا في خيارات التحميل أثناء إنشاء الحالة. |
| [IncorrectPasswordException](../../incorrectpasswordexception) | يتم إلقاؤه عندما يكون المستند المحمَّل محميًا بكلمة مرور، وتم تحديد كلمة المرور ولكنها غير صحيحة. |
| InvalidOperationException | يتم إلقاؤه عندما يحدث خطأ غير متوقع بطبيعة غير معروفة. |

### ملاحظات

طريقة GetDocumentInfo مفيدة عندما يكون غير واضح أي تنسيق للمستند المدخل، هل هو محمي بكلمة مرور و/أو عدد الصفحات/الأوراق/الشرائح التي يحتويها. استنادًا إلى بيانات التعريف هذه التي تُرجعها GetDocumentInfo، يمكن تعديل خيارات التحميل والتحرير بشكل صحيح لسلسلة المعالجة الرئيسية.

طريقة GetDocumentInfo تُرجع دائمًا البيانات الكاملة، ولا تتأثر بوضع التجربة، ولا يؤدي استخدامها إلى خصم البايتات أو الرصيد المستهلك.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### انظر أيضًا

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
