---
title: "ExportCidUrls"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحدد ما إذا كان سيتم استخدام عناوين CID ContentID للإشارة إلى الموارد (الصور، الخطوط، CSS) المضمنة في مستندات MHTML. القيمة الافتراضية هي false."
type: docs
weight: 20
url: /ar/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

يحدد ما إذا كان سيتم استخدام عناوين CID (Content-ID) للإشارة إلى الموارد (الصور، الخطوط، CSS) المضمنة في مستندات MHTML. القيمة الافتراضية هي `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### ملاحظات

بشكل افتراضي، يتم الإشارة إلى الموارد في مستندات MHTML بواسطة اسم الملف (على سبيل المثال, "image.png"), والذي يتم مطابقته مع رؤوس "Content-Location" لأجزاء MIME. يتيح هذا الخيار طريقة بديلة، حيث تُكتب الإشارات إلى ملفات الموارد كعناوين CID (Content-ID) (على سبيل المثال, "cid:image.png") وتُطابق مع رؤوس "Content-ID".

نظرياً، لا ينبغي أن يكون هناك فرق بين طريقتي الإشارة ويجب أن تعمل أي منهما بشكل جيد في أي متصفح أو عميل بريد. عملياً، ومع ذلك، بعض العملاء يفشلون في جلب الموارد بواسطة اسم الملف. إذا كان متصفحك أو عميل البريد يرفض تحميل الموارد المضمنة في مستند MTHML (لا يعرض الصور أو لا يحمل أنماط CSS)، جرّب تصدير المستند باستخدام عناوين CID.

### انظر أيضًا

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
