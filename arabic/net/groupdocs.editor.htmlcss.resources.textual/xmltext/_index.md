---
title: "XmlText"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل موردًا نصيًا واحدًا وهو XML"
type: docs
weight: 650
url: /ar/net/groupdocs.editor.htmlcss.resources.textual/xmltext/
---
## XmlText class

يمثل موردًا نصيًا واحدًا، وهو XML.

```csharp
public sealed class XmlText : TextResourceBase
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | يعيد محتوى هذا المورد النصي كتيار بايت مع الترميز الأصلي |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | يعيد ترميز هذا المورد النصي. عادةً يعيد UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | يعيد اسم الملف الصحيح لهذا المورد النصي، والذي يتكون من الاسم والامتداد |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | يحدد ما إذا كان هذا المورد النصي تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | يعيد اسم هذا المورد النصي بدون امتداد الملف |
| [ParsedDocument](../../groupdocs.editor.htmlcss.resources.textual/xmltext/parseddocument) { get; } | يعيد "XmlDocument" من هذا المورد XML |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | يعيد محتوى هذا المورد النصي كسلسلة قياسية |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/xmltext/type) { get; } | يعيد TextType.Xml |

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
