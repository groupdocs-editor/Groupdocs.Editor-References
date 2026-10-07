---
title: "EotFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل خطًا واحدًا في تنسيق EOT Embedded OpenType"
type: docs
weight: 340
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
## EotFont class

يمثل خطًا واحدًا بتنسيق EOT (خط مفتوح مضمّن)

```csharp
public sealed class EotFont : FontResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EotFont](eotfont#constructor)(string, Stream) | ينشئ فئة EotFont جديدة من المحتوى، الممثل كتدفق بايت، ومع اسم محدد |
| [EotFont](eotfont#constructor_1)(string, string) | ينشئ فئة EotFont جديدة من المحتوى، الممثل كسلسلة مشفرة بقاعدة64، ومع اسم محدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | يعيد محتوى هذا الخط كتدفق بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذا المورد الخطّي، الذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | يعيد اسم مورد الخط هذا. عادةً لا يحتوي على امتداد اسم الملف ومن الناحية النظرية يمكن أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | يعيد محتوى هذا الخط كسلسلة مشفرة بقاعدة64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/type) { get; } | يعيد FontType.Eot |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | يتخلص من مورد الخط هذا، مما يتخلص من محتواه ويجعل معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | يتحقق من مساواة هذا الكائن مع مورد الخط المحدد على أساس المساواة المرجعية |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | يتحقق من مساواة هذا الكائن مع مورد HTML المحدد على أساس المساواة المرجعية |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | يحفظ هذا الخط إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التدفق المحدد خط EOT صالحًا |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid#isvalid_1)(string) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خطًا صالحًا من نوع EOT |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/requiredheadersize) | حجم رأس EOT (بالبايت)، وهو مطلوب للتحقق من صحته |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | حدث يحدث عندما يتم التخلص من هذا الخط |

### انظر أيضًا

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
