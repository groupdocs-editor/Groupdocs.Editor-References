---
title: "WoffFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل خطًا واحدًا في تنسيق WOFF Web Open Font Format"
type: docs
weight: 410
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
## WoffFont class

يمثل خطًا واحدًا بتنسيق WOFF (تنسيق الخط المفتوح للويب)

```csharp
public sealed class WoffFont : FontResourceBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WoffFont](wofffont#constructor)(string, Stream) | ينشئ فئة WoffFont جديدة من المحتوى الممثل كتيار بايت، وبالاسم المحدد |
| [WoffFont](wofffont#constructor_1)(string, string) | ينشئ فئة WoffFont جديدة من المحتوى الممثل كسلسلة مشفرة بقاعدة 64، وبالاسم المحدد |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | يعيد محتوى هذا الخط كتدفق بايت |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | يرجع اسم الملف الصحيح لهذا المورد الخطّي، الذي يتكون من الاسم والامتداد. نظريًا قد يختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | يعيد اسم مورد الخط هذا. عادةً لا يحتوي على امتداد اسم الملف ومن الناحية النظرية يمكن أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | يعيد محتوى هذا الخط كسلسلة مشفرة بقاعدة64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/type) { get; } | يعيد FontType.Woff |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | يتخلص من مورد الخط هذا، مما يتخلص من محتواه ويجعل معظم الطرق والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | يتحقق من مساواة هذا الكائن مع مورد الخط المحدد على أساس المساواة المرجعية |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | يتحقق من مساواة هذا الكائن مع مورد HTML المحدد على أساس المساواة المرجعية |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | يحفظ هذا الخط إلى الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid)(Stream) | يتحقق مما إذا كان التيار المحدد خطًا صالحًا من نوع WOFF |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid_1)(string) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خطًا صالحًا من نوع WOFF |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/requiredheadersize) | حجم رأس WOFF (بالبايت)، وهو مطلوب للتحقق من صحته |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | حدث يحدث عندما يتم التخلص من هذا الخط |

### انظر أيضًا

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
