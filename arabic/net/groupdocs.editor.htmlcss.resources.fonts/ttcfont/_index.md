---
title: "TtcFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل خطًا واحدًا بتنسيق TTC TrueType Collection"
type: docs
weight: 380
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
## TtcFont class

يمثل خطًا واحدًا بتنسيق TTC (مجموعة خطوط TrueType)

```csharp
public sealed class TtcFont : FontResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TtcFont](ttcfont#constructor)(string, Stream) | ينشئ فئة TtcFont جديدة من المحتوى الممثَّل كتيار بايت، ومع اسم محدد |
| [TtcFont](ttcfont#constructor_1)(string, string) | ينشئ فئة TtcFont جديدة من المحتوى الممثَّل كنص مشفر بقاعدة 64، ومع اسم محدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | يعيد محتوى هذا الخط كتدفق بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذا المورد الخطّي، الذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [FontsNumber](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/fontsnumber) { get; } | عدد الخطوط في هذا الـ TTC |
| [HasDsigTable](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/hasdsigtable) { get; } | يشير إلى ما إذا كان هذا الـ TTC يحتوي على جدول DSIG. قد يكون جدول DSIG موجودًا فقط إذا كان للـ TTC رأس نسخة 2.0. |
| [HeaderVersion](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/headerversion) { get; } | إصدار رأس TTC، قد يكون "1" أو "2" |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | يعيد اسم مورد الخط هذا. عادةً لا يحتوي على امتداد اسم الملف ومن الناحية النظرية يمكن أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | يعيد محتوى هذا الخط كسلسلة مشفرة بقاعدة64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/type) { get; } | يعيد FontType.Ttc |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | يتخلص من مورد الخط هذا، مما يتخلص من محتواه ويجعل معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | يتحقق من مساواة هذا الكائن مع مورد الخط المحدد على أساس المساواة المرجعية |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | يتحقق من مساواة هذا الكائن مع مورد HTML المحدد على أساس المساواة المرجعية |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | يحفظ هذا الخط إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التدفق المحدد خط TTC صالحًا |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid_1)(string) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة64 المحددة خط TTF صالحًا |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/requiredheadersize) | حجم رأس TTC (بالبايت)، وهو مطلوب للتحقق من صلاحيته |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | حدث يحدث عندما يتم التخلص من هذا الخط |

### ملاحظات

انظر المزيد: https://docs.fileformat.com/font/ttc/

### انظر أيضًا

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
