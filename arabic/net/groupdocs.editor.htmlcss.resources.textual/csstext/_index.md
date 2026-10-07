---
title: "CssText"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل مورد نصي واحد للـ CSS"
type: docs
weight: 620
url: /ar/net/groupdocs.editor.htmlcss.resources.textual/csstext/
---
## CssText class

يمثل مورد نصي واحد للـ CSS

```csharp
public sealed class CssText : TextResourceBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | يعيد محتوى هذا المورد النصي كتيار بايت مع الترميز الأصلي |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | يعيد ترميز هذا المورد النصي. عادةً يعيد UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | يعيد اسم الملف الصحيح لهذا المورد النصي، والذي يتكون من الاسم والامتداد |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا المورد النصي تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | يعيد اسم هذا المورد النصي بدون امتداد الملف |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | يعيد محتوى هذا المورد النصي كسلسلة قياسية |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/csstext/type) { get; } | يعيد TextType.Css |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | يتخلص من هذا المورد النصي، متخلصًا من محتواه وجاعلاً معظم الطرق والخصائص غير عاملة. يتحمل الاستدعاءات المتعددة. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | يفحص هذه الحالة مع المحدد على المساواة. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | يحفظ هذا المورد النصي إلى الملف المحدد |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | حدث يحدث عندما يتم التخلص من هذا المورد النصي |

### انظر أيضًا

* class [TextResourceBase](../textresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
