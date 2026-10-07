---
title: "EditableDocument"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "مستند وسيط يحتوي على المحتوى قبل وبعد التحرير"
type: docs
weight: 10
url: /ar/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

مستند وسيط يحتوي على المحتوى قبل وبعد التحرير

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | يرجع قائمة بجميع الموارد الموجودة: جميع أوراق الأنماط، الصور من HTML وجميع أوراق الأنماط، الخطوط، الصوت |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | يرجع قائمة بموارد الصوت |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | يسمح بالحصول على موارد ورقة الأنماط (CSS) (سواء الخارجية أو المدمجة، ولكن ليس المضمنة داخل النص)، التي يستخدمها هذا المستند HTML |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | يسمح بالحصول على موارد الخطوط الخارجية، التي يستخدمها هذا المستند HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | يسمح بالحصول على موارد الصور الخارجية (صور نقطية ومتجهة)، التي يستخدمها هذا المستند HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | يحدد ما إذا كان هذا المستند Editable قد تم التخلص منه بالفعل (true) أم لا (false) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | مصنع ثابت، ينشئ كائنًا من EditableDocument من ملف HTML، يتم تحديده عبر مسار ملف *.html نفسه ومجلد يحتوي على الموارد المرتبطة |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | مصنع ثابت، ينشئ كائنًا من [`EditableDocument`](../editabledocument) من ترميز HTML المحدد |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | مصنع ثابت، ينشئ كائنًا من EditableDocument من ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | مصنع ثابت، ينشئ كائنًا من EditableDocument من ترميز HTML المحدد ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | يتخلص من كائن هذا المستند Editable، مما يؤدي إلى التخلص من محتواه وجعل طرقه وخصائصه غير عاملة |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | يرجع جسم مستند HTML (المحتوى الداخلي بين وسمي BODY الافتتاحية والإغلاقية دون هذه الوسوم) كسلسلة نصية. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | يرجع جسم مستند HTML (المحتوى الداخلي بين وسمي BODY الافتتاحية والإغلاقية دون هذه الوسوم) كسلسلة نصية، حيث تحتوي الروابط إلى الموارد الخارجية على القالب المحدد مع العناصر النائبة. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | يرجع المحتوى الكلي لمستند HTML كسلسلة نصية. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | يرجع المحتوى الكلي لمستند HTML كسلسلة نصية، حيث تحتوي الروابط إلى الموارد الخارجية على القالب المحدد مع العناصر النائبة. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | يرجع المحتوى الكلي لمستند HTML كتيار بايت عن طريق كتابة هذا المحتوى إلى التيار المحدد باستخدام الترميز النصي المحدد |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | يرجع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث تمثل كل سلسلة ورقة نمط واحدة. يرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | يرجع محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث تمثل كل سلسلة ورقة نمط واحدة. سيتم تطبيق البادئة المحددة على كل رابط إلى المورد الخارجي في كل ورقة نمط ناتجة. يرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | يرجع كل محتوى هذا المستند HTML مع جميع الموارد المرتبطة في شكل سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل ترميز HTML بصيغة مشفرة بقاعدة64. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث سيتم تخزين ترميز HTML، وإلى المجلد المصاحب للموارد. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث سيتم تخزين ترميز HTML، وإلى المجلد المصاحب للموارد، الذي يقع في المسار المحدد. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | يحفظ محتوى هذا [`EditableDocument`](../editabledocument) كملف HTML إلى كاتب النص المحدد، بينما يسمح معامل الخيارات الثاني بتخصيص عملية الحفظ وتحديد رد الاتصال لحفظ الموارد |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | الحدث الذي يحدث عندما يتم التخلص من المستند القابل للتحرير هذا، مباشرةً بعد إكمال عملية التخلص |

### ملاحظات

يمكن إنشاء نسخة من فئة `EditableDocument` عن طريق طريقة '[`Edit`](../editor/edit)' أو إنشاؤها من قبل المستخدم نفسه باستخدام المصانع الثابتة. يقوم `EditableDocument` داخليًا بتخزين المستند بتنسيقه المغلق الخاص، والذي يتوافق (قابل للتحويل) مع جميع صيغ الاستيراد والتصدير التي يدعمها GroupDocs.Editor. لجعل المستند قابلاً للتحرير في أي محرر WYSIWYG من جانب العميل (مثل CKEditor أو TinyMCE)، يوفر `EditableDocument` طرقًا لإنشاء علامات HTML وإنتاج الموارد التي يمكن للمستخدم قبولها.

### انظر أيضًا

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
