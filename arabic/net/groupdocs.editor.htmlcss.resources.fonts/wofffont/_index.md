---
title: WoffFont
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل خطًا واحدًا بتنسيق WOFF تنسيق خط الويب المفتوح
type: docs
weight: 320
url: /ar/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
## WoffFont class

يمثل خطًا واحدًا بتنسيق WOFF (تنسيق خط الويب المفتوح)

```csharp
public sealed class WoffFont : FontResourceBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WoffFont](wofffont#constructor)(string, Stream) | إنشاء فئة WoffFont جديدة من المحتوى ، يتم تمثيلها على شكل دفق بايت ، وباسم محدد |
| [WoffFont](wofffont#constructor_1)(string, string) | إنشاء فئة WoffFont جديدة من المحتوى ، يتم تمثيلها كسلسلة مشفرة بـ base64 ، وباسم محدد |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | إرجاع محتوى هذا الخط كـ byte stream |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | إرجاع اسم الملف الصحيح لمورد الخط هذا ، والذي يتكون من الاسم والامتداد. من الناحية النظرية يمكن أن تختلف عن الاسم. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | إرجاع اسم مورد الخطوط هذا. عادة لا يحتوي على امتداد اسم الملف ويمكن نظريًا أن يختلف عن اسم الملف. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | إرجاع محتوى هذا الخط كسلسلة بتشفير base64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/type) { get; } | إرجاع نوع الخط. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | التخلص من مورد الخط هذا ، والتخلص من محتواه وجعل معظم الأساليب والخصائص غير عاملة |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | التحقق من هذا المثيل باستخدام مورد الخط المحدد عند المساواة المرجعية |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | التحقق من هذا المثيل بمورد HTML المحدد عند المساواة في المرجع |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | يحفظ هذا الخط في الملف المحدد |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid)(Stream) | للتحقق مما إذا كان الدفق المحدد هو WOFF font |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/isvalid#isvalid_1)(string) | للتحقق مما إذا كانت السلسلة المحددة بترميز base64 هي WOFF font صالح |

## مجالات

| اسم | وصف |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/wofffont/requiredheadersize) | حجم رأس WOFF (بالبايت) ، وهو مطلوب للتحقق من صحته |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | الحدث الذي يحدث عند التخلص من هذا الخط |

### أنظر أيضا

* class [FontResourceBase](../fontresourcebase)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->