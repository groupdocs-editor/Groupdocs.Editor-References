---
title: "ExportImagesAsBase64"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحدد ما إذا كانت الصور تُحفظ بصيغة Base64 في ملف الإخراج. القيمة الافتراضية هي false."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64/
---
## MarkdownSaveOptions.ExportImagesAsBase64 property

يحدد ما إذا كانت الصور تُحفظ بتنسيق Base64 في ملف الإخراج. القيمة الافتراضية هي `false`.

```csharp
public bool ExportImagesAsBase64 { get; set; }
```

### ملاحظات

عند ضبط هذه الخاصية على `true`، يتم تصدير بيانات الصور مباشرةً إلى عناصر الصورة ![]() ولا يتم إنشاء ملفات منفصلة. هذه الخاصية، إذا تم ضبطها على `true`، لها أولوية أعلى من خاصية [`ImagesFolder`](../imagesfolder).

### انظر أيضًا

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
