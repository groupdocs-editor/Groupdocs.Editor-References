---
title: "HtmlSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لحفظ نسخة EditableDocument../groupdocs.editor/editabledocument إلى صيغة HTML"
type: docs
weight: 900
url: /ar/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

يسمح بتحديد خيارات مخصصة لحفظ نسخة [`EditableDocument`](../../groupdocs.editor/editabledocument) إلى صيغة HTML

```csharp
public sealed class HtmlSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | يتحكم في أي فاصل سيُستخدم حول قيم السمات في عناصر HTML: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | يتحكم في مكان تخزين ورقة (أوراق) الأنماط CSS: كموارد خارجية (`false`)، أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-&gt;HEAD (`true`). |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | الواجهة التي يجب أن يطبقها المستخدم النهائي لحفظ جميع موارد HTML الخارجية. هذه الخاصية **must** `null`، وإلا سيطلق GroupDocs.Editor استثناءً أثناء حفظ [`EditableDocument`](../../groupdocs.editor/editabledocument) إلى صيغة HTML. |

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
