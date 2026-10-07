---
title: "op_Explicit"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن EBookFormatsgroupdocs.editor.formats/ebookformats."
type: docs
weight: 60
url: /ar/net/groupdocs.editor.formats/ebookformats/op_explicit/
---
## EBookFormats Explicit operator

يقوم بتحويل سلسلة تمثل امتداد ملف إلى كائن [`EBookFormats`](../../ebookformats).

```csharp
public static explicit operator EBookFormats(string extension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | String | امتداد الملف المراد تحويله. إذا كان الامتداد يحتوي على عدة نقاط، يتم استخدام الجزء بعد آخر نقطة. |

### قيمة الإرجاع

كائن [`EBookFormats`](../../ebookformats) يتطابق مع امتداد الملف المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [EBookFormats](../../ebookformats) | يُرمى عندما يكون امتداد الملف المحدد فارغًا (null). |

### انظر أيضًا

* class [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
