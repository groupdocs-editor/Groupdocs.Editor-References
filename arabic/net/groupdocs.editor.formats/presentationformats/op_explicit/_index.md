---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يحوّل سلسلة تمثل امتداد ملف إلى كائن PresentationFormatsgroupdocs.editor.formats/presentationformats."
type: docs
weight: 150
url: /ar/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

يحوّل سلسلة تمثل امتداد ملف إلى كائن [`PresentationFormats`](../../presentationformats).

```csharp
public static explicit operator PresentationFormats(string extension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف المراد تحويله. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |

### قيمة الإرجاع

كائن [`PresentationFormats`](../../presentationformats) يتطابق مع امتداد الملف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [PresentationFormats](../../presentationformats) | يُرمى عندما يكون امتداد الملف المحدد فارغًا (null). |

### انظر أيضًا

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
