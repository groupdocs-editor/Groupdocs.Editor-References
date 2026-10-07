---
title: "Woff2Font"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل خطًا واحدًا في تنسيق WOFF2 Web Open Font Format"
type: docs
weight: 400
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
## Woff2Font class

يمثل خطًا واحدًا بتنسيق WOFF2 (تنسيق الخط المفتوح للويب)

```csharp
public sealed class Woff2Font : FontResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Woff2Font](woff2font#constructor)(string, Stream) | ينشئ فئة Woff2Font جديدة من المحتوى الممثل كتيار بايت، وباسم محدد |
| [Woff2Font](woff2font#constructor_1)(string, string) | ينشئ فئة Woff2Font جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة64، وباسم محدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | يعيد محتوى هذا الخط كتدفق بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذا المورد الخطّي، الذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | يعيد اسم مورد الخط هذا. عادةً لا يحتوي على امتداد اسم الملف ومن الناحية النظرية يمكن أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | يعيد محتوى هذا الخط كسلسلة مشفرة بقاعدة64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/type) { get; } | يرجع FontType.Woff2 |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | يتخلص من مورد الخط هذا، مما يتخلص من محتواه ويجعل معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | يتحقق من مساواة هذا الكائن مع مورد الخط المحدد على أساس المساواة المرجعية |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | يتحقق من مساواة هذا الكائن مع مورد HTML المحدد على أساس المساواة المرجعية |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | يحفظ هذا الخط إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التيار المحدد خط WOFF2 صالحًا |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid_1)(string) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة64 المحددة خط WOFF2 صالحًا |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/requiredheadersize) | حجم رأس WOFF2 (بالبايت)، المطلوب للتحقق من صلاحيته |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | حدث يحدث عندما يتم التخلص من هذا الخط |

### انظر أيضًا

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
