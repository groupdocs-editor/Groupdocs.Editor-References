---
title: "XmlFormatOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحتوي على خيارات تسمح بضبط تنسيق مستند XML عندما يُمثَّل كـ HTML"
type: docs
weight: 1280
url: /ar/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

يتضمن خيارات تسمح بضبط تنسيق مستند XML عندما يتم تمثيله كـ HTML.

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | عند التفعيل، سيتم وضع كل زوج من السمة‑القيمة في كل عنصر XML على سطر جديد. بشكل افتراضي القيمة false (معطلة) — جميع أزواج السمة‑القيمة توضع في سطر واحد. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | يحدد ما إذا كان هذا المثال من خيارات تنسيق XML يحتوي على قيمة افتراضية |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | عند التفعيل، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر. بشكل افتراضي القيمة false (معطلة) — تُوضع عقد النص الورقية على نفس سطر عناصرها الأصلية دون مسافة بادئة جديدة. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. لا يمكن أن تكون قيمة غير صفرية بدون وحدة. بشكل افتراضي 10pt |

### انظر أيضًا

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
