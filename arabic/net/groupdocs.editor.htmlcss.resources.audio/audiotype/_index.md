---
title: "AudioType"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يمثل تنسيق نوع صوتي مدعوم واحد"
type: docs
weight: 320
url: /ar/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

يمثل نوع صوتي قابل للدعم (صيغة)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | يمثل تنسيق صوتي من نوع MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | قيمة خاصة تشير إلى تنسيق صوت غير معرف أو غير معروف أو غير مدعوم |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | امتداد اسم الملف (بدون نقطة) لهذا التنسيق الصوتي |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | الاسم الرسمي لهذا التنسيق الصوتي |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | رمز MIME لهذا التنسيق الصوتي |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | يعيد قيمة AudioType التي تعادل امتداد اسم الملف المستخرج من اسم الملف المحدد |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | يحدد ما إذا كان هذا الكائن مساويًا لكائن \"AudioType\" المحدد |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | يحدد ما إذا كان هذا الكائن مساويًا لكائن غير محول محدد، والذي من المفترض أنه كائن \"AudioType\" آخر |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | يعيد قيمة تجزئة (hash-code) وهي رقم ثابت لهذا النوع القيمي المحدد |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | يتحقق مما إذا كانت قيمتي \"AudioType\" متساويتين |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | يتحقق مما إذا كانت قيمتي \"AudioType\" غير متساويتين |

### انظر أيضًا

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
