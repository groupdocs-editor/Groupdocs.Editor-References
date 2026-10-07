---
title: "MarkdownImageLoadingAction"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحدد وضع تحميل الصور أثناء فتح الملف للتحرير بصيغة Markdown."
type: docs
weight: 990
url: /ar/net/groupdocs.editor.options/markdownimageloadingaction/
---
## MarkdownImageLoadingAction enumeration

يحدد وضع تحميل الصور أثناء فتح الملف للتحرير بصيغة Markdown.

```csharp
public enum MarkdownImageLoadingAction
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Default | `0` | سيقوم GroupDocs.Editor بتحميل هذا المورد كالمعتاد |
| Skip | `1` | سيقوم GroupDocs.Editor بتخطي تحميل هذه الصورة |
| UserProvided | `2` | سيستخدم GroupDocs.Editor مصفوفة البايت التي يوفرها المستخدم في [`SetData`](../markdownimageloadargs/setdata) كبيانات الصورة |

### انظر أيضًا

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
