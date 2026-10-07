---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن EmailFormatsgroupdocs.editor.formats/emailformats."
type: docs
weight: 150
url: /ar/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن [`EmailFormats`](../../emailformats).

```csharp
public static explicit operator EmailFormats(string extension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف المراد تحويله. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |

### قيمة الإرجاع

كائن [`EmailFormats`](../../emailformats) يتطابق مع امتداد الملف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [EmailFormats](../../emailformats) | يُرمى عندما يكون امتداد الملف المحدد فارغًا (null). |

### انظر أيضًا

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
