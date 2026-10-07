---
title: "MhtmlSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ تغليف MHTML MIME لمستندات HTML المجمعة"
type: docs
weight: 1020
url: /ar/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات MHTML (MIME encapsulation of aggregate HTML documents)

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | يحدد ما إذا كان سيتم استخدام عناوين CID (Content-ID) للإشارة إلى الموارد (الصور، الخطوط، CSS) المضمنة في مستندات MHTML. القيمة الافتراضية هي `false`. |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | يحدد ما إذا كان سيتم تصدير خصائص المستند المدمجة والمخصصة إلى MHTML. القيمة الافتراضية هي `false`. |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | يحدد ما إذا كان سيتم تصدير معلومات اللغة إلى MHTML. القيمة الافتراضية هي `false`. |

### انظر أيضًا

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
