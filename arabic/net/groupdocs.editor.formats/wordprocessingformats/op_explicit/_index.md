---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats."
type: docs
weight: 140
url: /ar/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن [`WordProcessingFormats`](../../wordprocessingformats) object.

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف المراد تحويله. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |

### قيمة الإرجاع

كائن [`WordProcessingFormats`](../../wordprocessingformats) المقابل لامتداد الملف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون امتداد الملف المحدد فارغًا (null). |

### انظر أيضًا

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
