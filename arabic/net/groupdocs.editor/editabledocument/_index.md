---
title: EditableDocument
second_title: GroupDocs.Editor لمرجع .NET API
description: مستند متوسط يحتوي على محتوى قبل التحرير وبعده
type: docs
weight: 10
url: /ar/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

مستند متوسط يحتوي على محتوى قبل التحرير وبعده

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | إرجاع قائمة بجميع الموارد الموجودة: جميع أوراق الأنماط والصور من HTML وجميع أوراق الأنماط والخطوط و audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | إرجاع قائمة بالموارد الصوتية |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | إرجاع قائمة بموارد CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | يسمح بالحصول على موارد الخطوط الخارجية ، والتي يتم استخدامها بواسطة مستند HTML هذا |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | يسمح بالحصول على موارد الصور الخارجية (الصور النقطية والمتجهة) ، والتي يتم استخدامها بواسطة مستند HTML هذا |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | تحديد ما إذا كان هذا المستند القابل للتحرير قد تم التخلص منه بالفعل (صواب) أم لا (خطأ) |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | مصنع ثابت ، يقوم بإنشاء مثيل EditableDocument من ملف HTML ، المحدد بواسطة مسار إلى ملف * .html نفسه ومجلد به موارد مرتبطة |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | مصنع ثابت ، يقوم بإنشاء مثيل EditableDocument من ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | مصنع ثابت ، يقوم بإنشاء مثيل EditableDocument من ترميز HTML محدد ومن الموارد الموجودة في المجلد المحدد بواسطة المسار الكامل |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | التخلص من هذا المستند القابل للتحرير ، والتخلص من محتواه وجعل أساليبه وخصائصه غير عاملة |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | إرجاع نص مستند HTML (المحتوى الداخلي بين فتح وإغلاق علامات BODY بدون هذه العلامات) كسلسلة . |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | إرجاع نص مستند HTML (المحتوى الداخلي بين فتح وإغلاق علامات BODY بدون هذه العلامات) كسلسلة ، حيث تحتوي الارتباطات إلى الموارد الخارجية على بادئة محددة. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | إرجاع المحتوى الكلي لمستند HTML كسلسلة. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | إرجاع المحتوى الكلي لمستند HTML كسلسلة ، حيث تحتوي الارتباطات إلى الموارد الخارجية على بادئة محددة. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | إرجاع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل ، حيث تمثل إحدى السلاسل ورقة أنماط واحدة . إرجاع قائمة فارغة ، إذا لم يكن هناك CSS لهذا المستند. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | إرجاع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل ، حيث تمثل إحدى السلاسل ورقة أنماط واحدة . سيتم تطبيق البادئة المحددة على كل رابط للمورد الخارجي في كل ورقة أنماط ناتجة . إرجاع قائمة فارغة ، إذا لم يكن هناك CSS لهذا الغرض المستند . |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | إرجاع كل محتوى مستند HTML هذا مع جميع الموارد ذات الصلة في شكل سلسلة واحدة ، حيث يتم تضمين جميع الموارد داخل ترميز HTML في نموذج بترميز base64 . |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | يحفظ مستند HTML هذا في الملف على المسار المحدد ، حيث سيتم تخزين ترميز HTML ، وإلى المجلد المصاحب الذي يحتوي على الموارد. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | يحفظ مستند HTML هذا في الملف على المسار المحدد ، حيث سيتم تخزين ترميز HTML ، وإلى المجلد المصاحب الذي يحتوي على الموارد ، الموجود في المسار المحدد. |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | حدث ، يحدث عند التخلص من هذا المستند القابل للتحرير ، مباشرةً بعد الانتهاء من عملية التخلص |

### ملاحظات

يمكن إنتاج مثيل فئة EditableDocument بواسطة '[`Edit`](../editor/edit) طريقة أو أنشأها المستخدم بنفسه باستخدام مصانع ثابتة. يخزن EditableDocument داخليًا المستند بتنسيقه المغلق الخاص به ، وهو متوافق (قابل للتحويل) مع جميع تنسيقات الاستيراد والتصدير ، التي يدعمها GroupDocs.Editor. لجعل المستند قابلاً للتحرير في أي محرر من جانب العميل WYSIWYG (مثل CKEditor أو TinyMCE) ، يوفر EditableDocument طرقًا لإنشاء ترميز HTML وإنتاج الموارد التي يمكن أن يقبلها المستخدم.

### أنظر أيضا

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* مساحة الاسم [GroupDocs.Editor](../../groupdocs.editor)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
