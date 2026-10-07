---
title: "Editor"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "الفئة الرئيسية التي تضم طرق التحويل. توفر فئة Editor طرقًا لتحميل وتحرير وحفظ المستندات بجميع الصيغ المدعومة. هي قابلة للتصرف لذا استخدم توجيه using أو حرّر مواردها يدويًا عبر استدعاء طريقة Dispose. يتم تحميل المستند من خلال المنشئات. يتم تحرير المستند عبر طريقة Edit وحفظه مرة أخرى إلى المستند الناتج بعد التحرير عبر طريقة Save."
type: docs
weight: 20
url: /ar/net/groupdocs.editor/editor/
---
## Editor class

الفئة الرئيسية التي تُغلف أساليب التحويل. توفر فئة Editor أساليب لتحميل المستندات وتحريرها وحفظها بجميع الصيغ المدعومة. هي قابلة للتصرف، لذا استخدم توجيه 'using' أو حرّر مواردها يدويًا عبر استدعاء الطريقة 'Dispose()'. يتم تحميل المستند من خلال المُنشئات. تحرير المستند يتم عبر الطريقة 'Edit'، وحفظ المستند الناتج بعد التحرير يتم عبر الطريقة 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | يقوم بتهيئة نسخة جديدة من الفئة [`Editor`](../editor) ويُنشئ مستندًا فارغًا جديدًا بناءً على التنسيق المحدد. |
| [Editor](editor#constructor_1)(Stream) | يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كتيار). |
| [Editor](editor#constructor_3)(string) | يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كمسار ملف كامل) وإعدادات Editor. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كتيار) مع خيارات التحميل الخاصة به. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كمسار ملف كامل) مع خيارات التحميل الخاصة به. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | يوفر الوصول إلى الوظائف الخاصة بإدارة حقول النماذج داخل المستند. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | يشير إلى ما إذا كانت نسخة Editor هذه قد تم التخلص منها بالفعل ولا يمكن استخدامها بعد الآن (true) أو لم يتم التخلص منها بعد وبالتالي فهي نشطة (false). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | يتخلص من هذه النسخة من Editor، بحيث يحرّر جميع الموارد الداخلية ويصبح غير متاح للاستخدام لاحقًا. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام الخيارات الافتراضية عن طريق إنشاء وإرجاع نسخة من الفئة '[`EditableDocument`](../editabledocument)'، والتي بدورها تحتوي على طرق لإنشاء ترميز HTML والموارد المرتبطة. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع نسخة من الفئة '[`EditableDocument`](../editabledocument)'، والتي بدورها تحتوي على طرق لإنشاء ترميز HTML والموارد المرتبطة. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | يرجع البيانات الوصفية حول المستند الذي تم تحميله إلى نسخة 'Editor' هذه. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | احفظ محتوى المستند الحالي إلى التيار الخارج المحدد. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | يقوم بتحويل المستند المُحرَّر المحدد، الممثل كنسخة من '[`EditableDocument`](../editabledocument)'، إلى المستند الناتج بالتنسيق المحدد بناءً على امتداد اسم الملف، ويحفظ محتواه إلى ملف بالمسار المحدد. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | يقوم بتحويل المستند الأصلي بعد التعديل (على سبيل المثال، [`FormFieldManager`](./formfieldmanager)) إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى التيار المقدم. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | يقوم بتحويل المستند المُحرَّر المحدد، الممثل كنسخة من '[`EditableDocument`](../editabledocument)'، إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى التيار المحدد. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | يقوم بتحويل المستند المُحرَّر المحدد، الممثل كنسخة من '[`EditableDocument`](../editabledocument)'، إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى ملف بالمسار المحدد. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | الحدث الذي يحدث عندما يتم التخلص من نسخة Editor هذه مع جميع مواردها الداخلية. |

### ملاحظات

يجب اعتبار فئة Editor كنقطة دخول والكائن الجذري لـ GroupDocs.Editor. تُجرى جميع العمليات باستخدام هذه الفئة. الاستخدام النموذجي لفئة Editor لتنفيذ خط أنابيب تحرير المستند الكامل هو كما يلي:

1. تحميل مستند إلى نسخة Editor عبر المُنشئ الخاص بها.
2. اختياريًا، اكتشاف نوع المستند باستخدام طريقة [`GetDocumentInfo`](./getdocumentinfo).
3. فتح مستند للتحرير عن طريق استدعاء طريقة [`Edit`](./edit) والحصول على نسخة من فئة [`EditableDocument`](../editabledocument) منها.
4. تحرير محتوى المستند على جانب العميل باستخدام أي محرر HTML WYSIWYG.
5. إنشاء نسخة جديدة من [`EditableDocument`](../editabledocument) من محتوى المستند المُحرَّر.
6. حفظ المستند المُحرَّر إلى تنسيق إخراج معين عن طريق استدعاء طريقة [`Save`](./save).
7. التخلص من كائن من فئة Editor عبر عامل 'using' أو يدويًا.

### انظر أيضًا

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
