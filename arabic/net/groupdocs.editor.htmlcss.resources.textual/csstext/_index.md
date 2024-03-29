---
title: CssText
second_title: GroupDocs.Editor لمرجع .NET API
description: يمثل موردًا نصيًا واحدًا لـ CSS
type: docs
weight: 630
url: /ar/net/groupdocs.editor.htmlcss.resources.textual/csstext/
---
## CssText class

يمثل موردًا نصيًا واحدًا لـ CSS

```csharp
public sealed class CssText : TextResourceBase
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | إرجاع محتوى مورد النص هذا على هيئة دفق بايت مع الترميز الأصلي |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | إرجاع ترميز هذا المورد النصي. تُرجع عادةً UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | إرجاع اسم الملف الصحيح لمصدر النص هذا ، والذي يتكون من الاسم والملحق |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | تحديد ما إذا كان مصدر النص هذا قد تم التخلص منه أم لا |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | إرجاع اسم مورد النص هذا بدون امتداد الملف |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | إرجاع محتوى مورد النص هذا كسلسلة قياسية |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/csstext/type) { get; } | إرجاع TextType.Css |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | التخلص من هذا المورد النصي والتخلص من محتوياته وجعل معظم الأساليب والخصائص لا تعمل. متسامح مع مكالمات متعددة. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | التحقق من هذا المثيل بالمساواة . |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | يحفظ هذا المورد النصي في الملف المحدد |

## الأحداث

| اسم | وصف |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | الحدث الذي يحدث عندما يتم التخلص من مورد النص هذا |

### أنظر أيضا

* class [TextResourceBase](../textresourcebase)
* مساحة الاسم [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* المجسم [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
