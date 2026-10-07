---
title: "SavingCallback"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "الواجهة التي يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية. يجب ألا تكون هذه الخاصية `null` وإلا سيقوم GroupDocs.Editor برمي استثناء أثناء حفظ EditableDocumentgroupdocs.editor/editabledocument إلى تنسيق HTML."
type: docs
weight: 50
url: /ar/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

الواجهة التي يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية. هذه الخاصية **must** لا يجب أن تكون `null`، وإلا سيقوم GroupDocs.Editor برمي استثناء أثناء حفظ [`EditableDocument`](../../../groupdocs.editor/editabledocument) إلى تنسيق HTML.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### ملاحظات

إذا تم تعيين قيمة الخاصية [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) إلى `true`، فسيتم تضمين جميع أوراق الأنماط في ترميز HTML وبالتالي لن يتم تمريرها إلى رد النداء هذا.

### انظر أيضًا

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
